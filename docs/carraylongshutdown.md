Shutdown



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayLong](carraylong.md) / Shutdown

[![Previous](previous.png)](carraylongresize.md) 
[![Next](next.png)](carraylongadd.md)

Shutdown

Clears the array with a full memory release.

```
bool  Shutdown()
```

Return Value

true - successful, false - error.

Example:

```
//--- example for CArrayLong::Shutdown()
#include <Arrays\ArrayLong.mqh>
//---
void OnStart()
  {
   CArrayLong *array=new CArrayLong;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- add arrays elements
   //--- . . .
   //--- shutdown array
   if(!array.Shutdown())
     {
      printf("Shutdown error");
      delete array;
      return;
     }
   //--- delete array
   delete array;
  }
```