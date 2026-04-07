CArrayList<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CArrayList<T

[![Previous](previous.png)](ckeyvaluepairhashcode.md) 
[![Next](next.png)](carraylistcapacity.md)

CArrayList<T>

CArrayList<T> is a generic class that implements the IList<T> interface.

Description

The CArrayList<T> class is an implementation of the dynamic data list of the T type. This class provides the basic methods to work with the list, such as to access an element by index, to search and delete elements, sort, and others.

Declaration

```
   template<typename T>
   class CArrayList : public IList<T>
```

Header

```
   #include <Generic\ArrayList.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        [IList](ilist.md)            CArrayList |

Class Methods

| Method | Description |
| --- | --- |
| [Capacity](carraylistcapacity.md) | Gets and sets the current capacity of a list |
| [Count](carraylistcount.md) | Returns the number of elements in the list |
| [Contains](carraylistcontains.md) | Determines whether a list contains an element with the specified value |
| [TrimExcess](carraylisttrimexcess.md) | Sets the capacity of a list to the actual number of elements |
| [TryGetValue](carraylisttrygetvalue.md) | Gets an element of the list at the specified index |
| [TrySetValue](carraylisttrysetvalue.md) | Sets the value of the list element at the specified index |
| [Add](carraylistadd.md) | Adds an element to the list |
| [AddRange](carraylistaddrange.md) | Adds a collection or an array of elements to the list |
| [Insert](carraylistinsert.md) | Inserts an element into the list at the specified index |
| [InsertRange](carraylistinsertrange.md) | Inserts a collection or an array of elements into the list at the specified index |
| [CopyTo](carraylistcopyto.md) | Copies all elements of a list to the specified array starting at the specified index |
| [BinarySearch](carraylistbinarysearch.md) | Searches for the specified value in an ascending-sorted list |
| [IndexOf](carraylistindexof.md) | Searches for the first occurrence of a value in a list |
| [LastIndexOf](carraylistlastindexof.md) | Searches for the last occurrence of a value in a list |
| [Clear](carraylistclear.md) | Removes all elements from a collection |
| [Remove](carraylistremove.md) | Removes the first occurrence of the specified element from the list |
| [RemoveAt](carraylistremoveat.md) | Removes an element at the specified index of the list |
| [RemoveRange](carraylistremoverange.md) | Removes a range of elements from the list |
| [Reverse](carraylistreverse.md) | Reverses the order of elements in the list |
| [Sort](carraylistsort.md) | Sorts elements in the list |