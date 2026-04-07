SearchLinear



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CArrayDouble](carraydouble.md) / SearchLinear

[![Previous](previous.png)](carraydoublesearchlast.md) 
[![Next](next.png)](carraydoublesave.md)

SearchLinear

Searches for the element equal to the sample in the array.

```
int  SearchLinear(
   double  element      // sample
   ) const
```

Parameters

element

[in] The sample element to search in the array.

Return Value

The position of the found element - successful, -1 - the element not found.

Note

The method uses the linear search (or sequential search) algorithm for unsorted arrays.

Example:

```
//--- example for CArrayDouble::SearchLinear(double)
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
   //--- add arrays elements
   //--- . . .
   //--- search element
   if(array.SearchLinear(100.0)!=-1) printf("Element found");
   else                              printf("Element not found");
   //--- delete array
   delete array;
  }
```