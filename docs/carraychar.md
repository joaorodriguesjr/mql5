CArrayChar



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayChar

[![Previous](previous.png)](carrayload.md) 
[![Next](next.png)](carraycharreserve.md)

CArrayChar

CArrayChar is a class of dynamic array of char or uchar variables.

Description

CArrayChar class provides the ability to work with a dynamic array of char or uchar variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayChar : public CArray
```

Title

```
   #include <Arrays\ArrayChar.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayChar |

Class Methods

| Memory control |  |
| --- | --- |
| [Reserve](carraycharreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carraycharresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carraycharshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carraycharadd.md) | Adds an element to the end of the array |
| [AddArray](carraycharaddarray.md) | Adds elements of one array to the end of another |
| [AddArray](carraycharaddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carraycharinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carraycharinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carraycharinsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carraycharassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carraycharassignarrayconst.md) | Copies the elements of one array to another |
| Modify methods |  |
| [Update](carraycharupdate.md) | Changes the element at the specified array position |
| [Shift](carraycharshift.md) | Moves an element from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carraychardelete.md) | Removes the element from the specified array position |
| [DeleteRange](carraychardeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carraycharat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carraycharcomparearray.md) | Compares the array with another one |
| [CompareArray](carraycharcomparearrayconst.md) | Compares the array with another one |
| Sorted array methods |  |
| [InsertSort](carraycharinsertsort.md) | Inserts an element in a sorted array |
| [Search](carraycharsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carraycharsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carraycharsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carraycharsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carraycharsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carraycharsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carraycharsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carraycharsearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carraysave.md) | Saves data array in the file |
| virtual [Load](carraycharload.md) | Loads data array from the file |
| virtual [Type](carraychartype.md) | Gets the array type identifier |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |