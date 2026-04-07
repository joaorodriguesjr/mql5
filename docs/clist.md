CList



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CList

[![Previous](previous.png)](carrayobjtype.md) 
[![Next](next.png)](clistfreemode.md)

CList

CList Class is a class of dynamic list of instances of the CObject class and its derived classes.

Description

Class CList provides the ability to work with a list of instances of [CObject](cobject.md) and its derived classes. The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

There are some subtleties of working with the CList class. The class has a mechanism to control dynamic memory, so be careful when working with elements of the list.

[Subtleties](carrayobj.md#carrayobjfeatures) of the mechanism of memory management similar to those described in CArrayObj.

Declaration

```
   class CList : public CObject
```

Title

```
   #include <Arrays\List.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CList |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [FreeMode](clistfreemode.md) | Gets the flag of memory management when deleting list elements |
| [FreeMode](clistfreemode2.md) | Sets the flag of memory management when deleting list elements |
| [Total](clisttotal.md) | Gets the number of elements in the list |
| [IsSorted](clistissorted.md) | Gets sorted list flag |
| [SortMode](clistsortmode.md) | Gets the sorting mode |
| Create methods |  |
| [CreateElement](clistcreateelement.md) | Creates a new list element |
| Add methods |  |
| [Add](clistadd.md) | Adds an element to the end of the list |
| [Insert](clistinsert.md) | Inserts an element to the specified position of the list |
| Delete methods |  |
| [DetachCurrent](clistdetachcurrent.md) | Removes an element from the current position in the list without deleting it "physically" |
| [DeleteCurrent](clistdeletecurrent.md) | Removes the element from the current position in the list |
| [Delete](clistdelete.md) | Removes the element from the specified position in the list |
| [Clear](clistclear.md) | Removes all list elements |
| Navigation |  |
| [IndexOf](clistindexof.md) | Gets the index of the specified list element |
| [GetNodeAtIndex](clistgetnodeatindex.md) | Gets an item with the specified index of the list |
| [GetFirstNode](clistgetfirstnode.md) | Gets the first element of the list |
| [GetPrevNode](clistgetprevnode.md) | Gets the previous element of the list |
| [GetCurrentNode](clistgetcurrentnode.md) | Gets the current list element |
| [GetNextNode](clistgetnextnode.md) | Gets the next element in the list |
| [GetLastNode](clistgetlastnode.md) | Gets the last element in the list |
| Ordering methods |  |
| [Sort](clistsort.md) | Sorts the list |
| [MoveToIndex](clistmovetoindex.md) | Moves the current element in the list to the specified position |
| [Exchange](clistexchange.md) | Swaps two elements in the list |
| Compare methods |  |
| [CompareList](clistcomparelist.md) | Compares the list with another one |
| Search methods |  |
| [Search](clistsearch.md) | Searches for an element equal to the sample in sorted list |
| Input/output |  |
| virtual [Save](clistsave.md) | Saves list data in the file |
| virtual [Load](clistload.md) | Loads list data from the file |
| virtual [Type](clisttype.md) | Gets the list type identifier |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |