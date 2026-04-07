CArrayFloat



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayFloat

[![Previous](previous.png)](carraylongtype.md) 
[![Next](next.png)](carrayfloatdelta.md)

CArrayFloat

CArrayFloat class is a class of dynamic array of float variables.

Description

The CArrayFloat class provides the ability to work with a dynamic array of float variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayFloat : public CArray
```

Title

```
   #include <Arrays\ArrayFloat.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayFloat |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Delta](carrayfloatdelta.md) | Sets the comparison tolerance |
| Memory control |  |
| [Reserve](carrayfloatreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carrayfloatresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carrayfloatshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carrayfloatadd.md) | Adds an element to the end of the array |
| [AddArray](carrayfloataddarray.md) | Adds elements of one array to the end of another |
| [AddArray](carrayfloataddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carrayfloatinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carrayfloatinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carrayfloatinsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carrayfloatassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carrayfloatassignarrayconst.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carrayfloatupdate.md) | Changes the element at the specified array position |
| [Shift](carrayfloatshift.md) | Moves an element from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carrayfloatdelete.md) | Removes the element from the specified array position |
| [DeleteRange](carrayfloatdeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carrayfloatat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carrayfloatcomparearray.md) | Compares the array with another one |
| [CompareArray](carrayfloatcomparearrayconst.md) | Compares the array with another one |
| Sorted array operations |  |
| [InsertSort](carrayfloatinsertsort.md) | Inserts an element in a sorted array |
| [Search](carrayfloatsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carrayfloatsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carrayfloatsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carrayfloatsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carrayfloatsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carrayfloatsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carrayfloatsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carrayfloatsearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carrayfloatsave.md) | Saves data array in the file |
| virtual [Load](carrayfloatload.md) | Loads data array from the file |
| virtual [Type](carrayfloattype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |