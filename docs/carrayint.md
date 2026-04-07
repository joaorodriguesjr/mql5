CArrayInt



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayInt

[![Previous](previous.png)](carrayshorttype.md) 
[![Next](next.png)](carrayintreserve.md)

CArrayInt

CArrayInt is a class of dynamic array of int or uint variables.

Description

The class CArrayInt provides the ability to work with a dynamic array of int or uint variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayInt : public CArray
```

Title

```
   #include <Arrays\ArrayInt.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayInt  Direct descendants  [CSpreadBuffer](cspreadbuffer.md) |

Class Methods by Groups

| Memory control |  |
| --- | --- |
| [Reserve](carrayintreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carrayintresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carrayintshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carrayintadd.md) | Adds an element to the end of the array |
| [AddArray](carrayintaddarray.md) | Adds elements of one array to the end of another |
| [AddArray](carrayintaddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carrayintinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carrayintinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carrayintinsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carrayintassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carrayintassignarrayconst.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carrayintupdate.md) | Changes the element at the specified array position |
| [Shift](carrayintshift.md) | Moves an element from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carrayintdelete.md) | Removes the element from the specified array position |
| [DeleteRange](carrayintdeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carrayintat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carrayintcomparearray.md) | Compares the array with another one |
| [CompareArray](carrayintcomparearrayconst.md) | Compares the array with another one |
| Sorted array operations |  |
| [InsertSort](carrayintinsertsort.md) | Inserts an element in a sorted array |
| [Search](carrayintsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carrayintsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carrayintsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carrayintsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carrayintsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carrayintsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carrayintsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carrayintsearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carrayintsave.md) | Saves data array in the file |
| virtual [Load](carrayintload.md) | Loads data array from the file |
| virtual [Type](carrayinttype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |