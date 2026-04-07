Type



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayChar](carraychar.md) / Type

[![Previous](previous.png)](carraycharload.md) 
[![Next](next.png)](carrayshort.md)

Type

Gets the array type identifier.

```
virtual int  Type() const
```

Return Value

Array type identifier (for CArrayChar - 77).

Example:

```
//--- example for CArrayChar::Type()
#include <Arrays\ArrayChar.mqh>
//---
void OnStart()
  {
   CArrayChar *array=new CArrayChar;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- get array type
   int type=array.Type();
   //--- delete array
   delete array;
  }
```