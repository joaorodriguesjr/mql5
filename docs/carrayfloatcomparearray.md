CompareArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayFloat](carrayfloat.md) / CompareArray

[![Previous](previous.png)](carrayfloatat.md) 
[![Next](next.png)](carrayfloatcomparearrayconst.md)

CompareArray

Compares the array with another one.

```
bool  CompareArray(
   const float&  src[]      // source array
   ) const
```

Parameters

src[]

[in]  Reference to an array used as a source of elements for comparison.

Return Value

true - arrays are equal, false - arrays are not equal.

Example:

```
//--- example for CArrayFloat::CompareArray(const float &[])
#include <Arrays\ArrayFloat.mqh>
//---
float src[];
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
   //--- compare with another array
   int result=array.CompareArray(src);
   //--- delete array
   delete array;
  }
```