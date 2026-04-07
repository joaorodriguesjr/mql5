SearchLast



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayInt](carrayint.md) / SearchLast

[![Previous](previous.png)](carrayintsearchfirst.md) 
[![Next](next.png)](carrayintsearchlinear.md)

SearchLast

Searches for the last element equal to the sample in the sorted array.

```
int  SearchLast(
   int  element      // sample
   ) const
```

Parameters

element

[in]  The sample element to search in the array.

Return Value

The position of the found element - successful, -1 - the element not found.

Example:

```
//--- example for CArrayInt::SearchLast(int)
#include <Arrays\ArrayInt.mqh>
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
   //--- add arrays elements
   //--- . . .
   //--- sort array
   array.Sort();
   //--- search element
   if(array.SearchLast(10000)!=-1) printf("Element found");
   else                            printf("Element not found");
   //--- delete array
   delete array;
  }
```