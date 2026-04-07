Detach



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayObj](carrayobj.md) / Detach

[![Previous](previous.png)](carrayobjshift.md) 
[![Next](next.png)](carrayobjdelete.md)

Detach

Removes an element from a given position in the array.

```
CObject*  Detach(
   int  pos      // position
   )
```

Parameters

pos

[in] Position of a removed item in the array.

Return Value

Pointer to the removed element - success, NULL - cannot remove the element.

Note

When an element is removed from the array, it will not be deleted regardless of the memory management flag. Once the array element pointer is used, it has to be deallocated.

Example:

```
//--- example for CArrayObj::Detach(int)
#include <Arrays\ArrayObj.mqh>
//---
void OnStart()
  {
   CArrayObj *array=new CArrayObj;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- add arrays elements
   //--- . . .
   CObject *object=array.Detach(0);
   if(object==NULL)
     {
      printf("Detach error");
      delete array;
      return;
     }
   //--- use element
   //--- . . .
   //--- delete element
   delete object;
   //--- delete array
   delete array;
  }
```