CompareArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayShort](carrayshort.md) / CompareArray

[![Previous](previous.png)](carrayshortat.md) 
[![Next](next.png)](carrayshortcomparearrayconst.md)

CompareArray

Compares the array with another one.

```
bool  CompareArray(
   const short&  src[]      // source array
   ) const
```

Parameters

src[]

[in]  Reference to an array used as a source of elements for comparison.

Return Value

true - arrays are equal, false - arrays are not equal.

Example:

```
//--- example for CArrayShort::CompareArray(const short &[])
#include <Arrays\ArrayShort.mqh>
//---
short src[];
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
   //--- compare with another array
   int result=array.CompareArray(src);
   //--- delete array
   delete array;
  }
```