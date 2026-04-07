Shutdown



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayString](carraystring.md) / Shutdown

[![Previous](previous.png)](carraystringresize.md) 
[![Next](next.png)](carraystringadd.md)

Shutdown

Clears the array with a full memory release.

```
bool  Shutdown()
```

Return Value

true - successful, false - error.

Example:

```
//--- example for CArrayString::Shutdown()
#include <Arrays\ArrayString.mqh>
//---
void OnStart()
  {
   CArrayString *array=new CArrayString;
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