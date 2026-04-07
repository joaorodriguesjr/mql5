Step



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArray](carray.md) / Step

[![Previous](previous.png)](carraystep.md) 
[![Next](next.png)](carraytotal.md)

Step

Sets the increment size of the array.

```
bool  Step(
   int  step      // step
   )
```

Parameters

step

[in]  The new value of the increment size of the array.

Return Value

true - successful, false - there was an attempt to establish a step less than or equal to zero.

Example:

```
//--- example for CArray::Step(int)
#include <Arrays\Array.mqh>
//---
void OnStart()
  {
   CArray *array=new CArray;
   //---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
   //--- set resize step
   bool result=array.Step(1024);
   //--- use array
   //--- ...
   //--- delete array
   delete array;
  }
```