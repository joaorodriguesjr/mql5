CArrayShort



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayShort

[![Previous](previous.png)](carraychartype.md) 
[![Next](next.png)](carrayshortreserve.md)

CArrayShort

CArrayShort is a class of dynamic array of short or ushort variables.

Description

Class CArrayShort provides the ability to work with a dynamic array of short or ushort variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayShort : public CArray
```

Title

```
   #include <Arrays\ArrayShort.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayShort |

Class Methods by Groups

| Memory control |  |
| --- | --- |
| [Reserve](carrayshortreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carrayshortresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carrayshortshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carrayshortadd.md) | Adds an element to the end of the array |
| [AddArray](carrayshortaddarray.md) | Adds elements of one array to the end of another |
| [AddArray](carrayshortaddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carrayshortinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carrayshortinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carrayshortinsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carrayshortassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carrayshortassignarrayconst.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carrayshortupdate.md) | Changes the element at the specified array position |
| [Shift](carrayshortshift.md) | Moves an element from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carrayshortdelete.md) | Removes the element from the specified array position |
| [DeleteRange](carrayshortdeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carrayshortat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carrayshortcomparearray.md) | Compares the array with another one |
| [CompareArray](carrayshortcomparearrayconst.md) | Compares the array with another one |
| Sorted array operations |  |
| [InsertSort](carrayshortinsertsort.md) | Inserts an element in a sorted array |
| [Search](carrayshortsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carrayshortsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carrayshortsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carrayshortsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carrayshortsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carrayshortsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carrayshortsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carrayshortsearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carrayshortsave.md) | Saves data array in the file |
| virtual [Load](carrayshortload.md) | Loads data array from the file |
| virtual [Type](carrayshorttype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |