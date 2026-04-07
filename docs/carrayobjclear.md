Clear



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayObj](carrayobj.md) / Clear

[![Previous](previous.png)](carrayobjresize.md) 
[![Next](next.png)](carrayobjshutdown.md)

Clear

Removes all elements of the array without the release of the memory array.

```
void  Clear()
```

Return Value

No.

Note

If the memory management flag is enabled, the memory used for the deleted objects is released.

Example:

```
//--- example for CArrayObj::Clear()
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
   //--- clear array
   array.Clear();
   //--- delete array
   delete array;
  }
```