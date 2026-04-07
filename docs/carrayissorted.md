IsSorted



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArray](carray.md) / IsSorted

[![Previous](previous.png)](carraymax.md) 
[![Next](next.png)](carraysortmode.md)

IsSorted

Gets the flag of array being sorted using the specified sorting mode.

```
bool  IsSorted(
   int  mode=0      // sorting mode
   ) const
```

Parameters

mode=0

[in]  Tested sorting mode.

Return Value

Flag of the sorted list. If the list is sorted using the specified mode - true, otherwise - false.

Note

The sort flag cannot be changed directly. It is set by the Sort() method and reset by any add/insert method except for the InserSort(...).

Example:

```
//--- example for CArray::IsSorted()
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
   //--- check sorted
   if(array.IsSorted())
     {
      //--- use methods for sorted array
      //--- ...
     }
   //--- delete array
   delete array;
  }
```