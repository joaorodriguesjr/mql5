CArrayLong



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayLong

[![Previous](previous.png)](carrayinttype.md) 
[![Next](next.png)](carraylongreserve.md)

CArrayLong

CArrayLong class is a class of dynamic array of long or ulong variables.

Description

The CArrayLong class provides the ability to work with a dynamic array of long or ulong variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayLong : public CArray
```

Title

```
   #include <Arrays\ArrayLong.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayLong  Direct descendants  [CRealVolumeBuffer](crealvolumebuffer.md), [CTickVolumeBuffer](ctickvolumebuffer.md), [CTimeBuffer](ctimebuffer.md) |

Class Methods by Groups

| Memory control |  |
| --- | --- |
| [Reserve](carraylongreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carraylongresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carraylongshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carraylongadd.md) | Adds an element to the end of the array |
| [AddArray](carraylongaddarrayconst.md) | Adds elements of one array to the end of another |
| [AddArray](carraylongaddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carraylonginsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carraylonginsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carraylonginsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carraylongassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carraylongassignarrayconst.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carraylongupdate.md) | Changes the element at the specified array position |
| [Shift](carraylongshift.md) | Moves an element from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carraylongdelete.md) | Removes the element from the specified array position |
| [DeleteRange](carraylongdeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carraylongat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carraylongcomparearray.md) | Compares the array with another one |
| [CompareArray](carraylongcomparearrayconst.md) | Compares the array with another one |
| Sorted array operations |  |
| [InsertSort](carraylonginsertsort.md) | Inserts an element in a sorted array |
| [Search](carraylongsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carraylongsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carraylongsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carraylongsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carraylongsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carraylongsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carraylongsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carraylongsearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carraylongsave.md) | Saves data array in the file |
| virtual [Load](carraylongload.md) | Loads data array from the file |
| virtual [Type](carraylongtype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |