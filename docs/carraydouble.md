CArrayDouble



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayDouble

[![Previous](previous.png)](carrayfloattype.md) 
[![Next](next.png)](carraydoubledelta.md)

CArrayDouble

CArrayDouble class is a class of dynamic array of double variables.

Description

The CArrayDouble class provides the ability to work with a dynamic array of double variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayDouble : public CArray
```

Title

```
   #include <Arrays\ArrayDouble.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayDouble  Direct descendants  [CDoubleBuffer](cdoublebuffer.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Delta](carraydoubledelta.md) | Set the comparison tolerance |
| Memory control |  |
| [Reserve](carraydoublereserve.md) | Allocates memory to increase the size of the array |
| [Resize](carraydoubleresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carraydoubleshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carraydoubleadd.md) | Adds an element to the end of the array |
| [AddArray](carraydoubleaddarray.md) | Adds elements of one array to the end of another |
| [AddArray](carraydoubleaddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carraydoubleinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carraydoubleinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carraydoubleinsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carraydoubleassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carraydoubleassignarrayconst.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carraydoubleupdate.md) | Changes the element at the specified array position |
| [Shift](carraydoubleshift.md) | Moves an element from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carraydoubledelete.md) | Removes the element from the specified array position |
| [DeleteRange](carraydoubledeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carraydoubleat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carraydoublecomparearray.md) | Compares the array with another one |
| [CompareArray](carraydoublecomparearrayconst.md) | Compares the array with another one |
| Search for min/max |  |
| [Minimum](carraydoubleminimum.md) | Gets the lowest value index in the specified range |
| [Maximum](carraydoublemaximum.md) | Gets the highest value index in the specified range |
| Sorted array operations |  |
| [InsertSort](carraydoubleinsertsort.md) | Inserts an element in a sorted array |
| [Search](carraydoublesearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carraydoublesearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carraydoublesearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carraydoublesearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carraydoublesearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carraydoublesearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carraydoublesearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carraydoublesearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carraydoublesave.md) | Saves data array in the file |
| virtual [Load](carraydoubleload.md) | Loads data array from the file |
| virtual [Type](carraydoubletype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |