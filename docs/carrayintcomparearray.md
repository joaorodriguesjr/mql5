CompareArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayInt](carrayint.md) / CompareArray

[![Previous](previous.png)](carrayintat.md) 
[![Next](next.png)](carrayintcomparearrayconst.md)

CompareArray

Compares the array with another one.

```
bool  CompareArray(
   const int&  src[]      // source array
   ) const
```

Parameters

src[]

[in]  Reference to an array used as a source of elements for comparison.

Return Value

true - arrays are equal, false - arrays are not equal.

Example:

```
//--- example for CArrayInt::CompareArray(const int &[])
#include <Arrays\ArrayInt.mqh>
//---
int src[];
//---
void OnStart()
  {
   CArrayInt *array=new CArrayInt;
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