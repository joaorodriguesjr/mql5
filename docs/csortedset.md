CSortedSet<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CSortedSet<T

[![Previous](previous.png)](csortedmaptrysetvalue.md) 
[![Next](next.png)](csortedsetadd.md)

CSortedSet<T>

CSortedSet<T> is a generic class that implements the ISet<T> interface.

Description

The CSortedSet<T> class is an implementation of the sorted dynamic data set of type T, with the required uniqueness of each value. This class provides basic methods to work with sets and related operations, such as: the union and intersection of sets, definition of strict and non-strict subsets, and others.

Declaration

```
   template<typename T>
   class CSortedSet : public ISet<T>
```

Header

```
   #include <Generic\SortedSet.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        [ISet](iset.md)            CSortedSet |

Class Methods

| Method | Description |
| --- | --- |
| [Add](csortedsetadd.md) | Adds an element to a sorted set |
| [Count](csortedsetcount.md) | Returns the number of elements in a sorted set |
| [Contains](csortedsetcontains.md) | Determines whether a sorted set contains an element with the specified value |
| [Comparer](csortedsetcomparer.md) | Returns a pointer to the IComparer<T> interface, used to organize a sorted set |
| [TryGetMin](csortedsettrygetmin.md) | Gets the minimum element from a sorted set |
| [TryGetMax](csortedsettrygetmax.md) | Gets the maximum element from a sorted set |
| [CopyTo](csortedsetcopyto.md) | Copies all elements of a sorted set to the specified array starting at the specified index |
| [Clear](csortedsetclear.md) | Removes all elements from a sorted set |
| [Remove](csortedsetremove.md) | Removes the occurrence of the specified element from a sorted set |
| [ExceptWith](csortedsetexceptwith.md) | Produces the operation of difference between the current collection and a passed collection (array) |
| [IntersectWith](csortedsetintersectwith.md) | Produces the operation of intersection of the current collection and a passed collection (array) |
| [SymmetricExceptWith](csortedsetsymmetricexceptwith.md) | Produces the operation of symmetrical difference between the current collection and a passed collection (array) |
| [UnionWith](csortedsetunionwith.md) | Produces the union of the current collection and a passed collection (array) |
| [IsProperSubsetOf](csortedsetispropersubsetof.md) | Determines whether the current sorted set is a proper subset of the specified collection or array |
| [IsProperSupersetOf](csortedsetispropersupersetof.md) | Determines whether the current sorted set is a proper superset of the specified collection or array |
| [IsSubsetOf](csortedsetissubsetof.md) | Determines whether the current sorted set is a subset of the specified collection or array |
| [IsSupersetOf](csortedsetissupersetof.md) | Determines whether the current sorted set is a superset of the specified collection or array |
| [Overlaps](csortedsetoverlaps.md) | Determines whether the current sorted set overlaps the specified collection or array |
| [SetEquals](csortedsetsetequals.md) | Determines whether the current sorted set contains all elements of the specified collection or array |
| [GetViewBetween](csortedsetgetviewbetween.md) | Gets from the current sorted set a subset specified by the minimum and maximum values |
| [GetReverse](csortedsetgetreverse.md) | Gets a copy of the current sorted set, in which all the elements are arranged in a reverse order |