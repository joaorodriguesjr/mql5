CompareArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayDouble](carraydouble.md) / CompareArray

[![Previous](previous.png)](carraydoubleat.md) 
[![Next](next.png)](carraydoublecomparearrayconst.md)

CompareArray

Compares the array with another one.

```
bool  CompareArray(
   const double&  src[]      // source array
   ) const
```

Parameters

src[]

[in] Reference to an array used as a source of elements for comparison.

Return Value

true - arrays are equal, false - arrays are not equal.

Example:

```
//--- example for CArrayDouble::CompareArray(const double &[])
#include <Arrays\ArrayDouble.mqh>
//---
double src[];
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
   //--- compare with another array
   int result=array.CompareArray(src);
   //--- delete array
   delete array;
  }
```