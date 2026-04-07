Delete



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayFloat](carrayfloat.md) / Delete

[![Previous](previous.png)](carrayfloatshift.md) 
[![Next](next.png)](carrayfloatdeleterange.md)

Delete

Removes the element from the specified array position.

```
bool  Delete(
   int  pos      // position
   )
```

Parameters

pos

[in]  Position of the array element to be removed.

Return Value

true - successful, false - cannot remove the element.

Example:

```
//--- example for CArrayFloat::Delete(int)
#include <Arrays\ArrayFloat.mqh>
//---
void OnStart()
  {
   CArrayFloat *array=new CArrayFloat;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- add arrays elements
   //--- . . .
   //--- delete element
   if(!array.Delete(0))
     {
      printf("Delete error");
      delete array;
      return;
     }
   //--- delete array
   delete array;
  }
```