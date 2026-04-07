Type



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayShort](carrayshort.md) / Type

[![Previous](previous.png)](carrayshortload.md) 
[![Next](next.png)](carrayint.md)

Type

Gets the array type identifier.

```
virtual int  Type() const
```

Return Value

Array type identifier (for CArrayShort - 82).

Example:

```
//--- example for CArrayShort::Type()
#include <Arrays\ArrayShort.mqh>
//---
void OnStart()
  {
   CArrayShort *array=new CArrayShort;
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