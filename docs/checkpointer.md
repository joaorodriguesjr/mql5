CheckPointer



[MQL5 Reference](index.md)  /  [Common Functions](common.md) / CheckPointer

[![Previous](previous.png)](alert.md) 
[![Next](next.png)](comment.md)

CheckPointer

The function returns the type of the object [pointer](object_pointers.md).

```
ENUM_POINTER_TYPE  CheckPointer(
   object* anyobject      // object pointer
   );
```

Parameters

anyobject

[in]  Object pointer.

Return value

Returns a value from the [ENUM\_POINTER\_TYPE](enum_pointer_type.md) enumeration.

Note

An attempt to call an incorrect pointer results in the [critical termination](errors.md) of a program. That's why it's necessary to call the CheckPointer function before using a pointer. A pointer can be incorrect in the following cases:

* the pointer is equal to [NULL](void.md);
* the object has been deleted using the [delete](deleteoperator.md) operator.

This function can be used for checking pointer validity. A non-zero value warranties that the pointer can be used for accessing.

To quickly validate the pointer, you can also use operator "!" ([example](object_pointers.md#lnot)) which checks it via an implicit call of the [CheckPointer](checkpointer.md) function.

Example:

```
//+------------------------------------------------------------------+
//| Deletes list by deleting its elements                            |
//+------------------------------------------------------------------+
void CMyList::Destroy()
  {
//--- service pointer for working in the loop
   CItem* item;
//--- go through loop and try to delete dynamic pointers
   while(CheckPointer(m_items)!=POINTER_INVALID)
     {
      item=m_items;
      m_items=m_items.Next();
      if(CheckPointer(item)==POINTER_DYNAMIC)
        {
         Print("Dynamic object ",item.Identifier()," to be deleted");
         delete (item);
        }
      else Print("Non-dynamic object ",item.Identifier()," cannot be deleted");
     }
//---
  }
```

See also

[Object Pointers](object_pointers.md), [Checking the Object Pointer](enum_pointer_type.md), [Object Delete Operator delete](deleteoperator.md)