Type



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayDouble](carraydouble.md) / Type

[![Previous](previous.png)](carraydoubleload.md) 
[![Next](next.png)](carraystring.md)

Type

Gets the array type identifier.

```
virtual int  Type() const
```

Return Value

Array type identifier (for CArrayDouble - 87).

Example:

```
//--- example for CArrayDouble::Type()
#include <Arrays\ArrayDouble.mqh>
//---
void OnStart()
  {
   CArrayDouble *array=new CArrayDouble;
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