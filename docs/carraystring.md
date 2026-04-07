CArrayString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayString

[![Previous](previous.png)](carraydoubletype.md) 
[![Next](next.png)](carraystringreserve.md)

CArrayString

CArrayString class is a class of dynamic array of string variables.

Description

The CArrayString class provides the ability to work with a dynamic array of string variables. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

Declaration

```
   class CArrayString : public CArray
```

Title

```
   #include <Arrays\ArrayString.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayString |

Class Methods by Groups

| Memory control |  |
| --- | --- |
| [Reserve](carraystringreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carraystringresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carraystringshutdown.md) | Clears the array with a full memory release |
| Add methods |  |
| [Add](carraystringadd.md) | Adds an element to the end of the array |
| [AddArray](carraystringaddarray.md) | Adds elements of one array to the end of another |
| [AddArray](carraystringaddarrayconst.md) | Adds elements of one array to the end of another |
| [Insert](carraystringinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carraystringinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [InsertArray](carraystringinsertarrayconst.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carraystringassignarray.md) | Copies the elements of one array to another |
| [AssignArray](carraystringassignarrayconst.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carraystringupdate.md) | Changes the element at the specified position array |
| [Shift](carraystringshift.md) | Moves an item from a given position in the array to the specified offset |
| Delete methods |  |
| [Delete](carraystringdelete.md) | Removes the element from the specified array position |
| [DeleteRange](carraystringdeleterange.md) | Deletes a group of elements from the specified array position |
| Access methods |  |
| [At](carraystringat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carraystringcomparearray.md) | Compares the array with another one |
| [CompareArray](carraystringcomparearrayconst.md) | Compares the array with another one |
| Sorted array opetations |  |
| [InsertSort](carraystringinsertsort.md) | Inserts an element in a sorted array |
| [Search](carraystringsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carraystringsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carraystringsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carraystringsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carraystringsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carraystringsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carraystringsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| [SearchLinear](carraystringsearchlinear.md) | Searches for the element equal to the sample in the array |
| Input/output |  |
| virtual [Save](carraystringsave.md) | Saves data array in the file |
| virtual [Load](carraystringload.md) | Loads data array from the file |
| virtual [Type](carraystringtype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |