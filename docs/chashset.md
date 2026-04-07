CHashSet<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CHashSet<T

[![Previous](previous.png)](chashmaptrysetvalue.md) 
[![Next](next.png)](chashsetadd.md)

CHashSet<T>

CHashSet<T> is a generic class that implements the ISet<T> interface.

Description

The CHashSet<T> class is an implementation of the unordered dynamic data set of type T, with the required uniqueness of each value. This class provides basic methods to work with sets and related operations, such as: the union and intersection of sets, definition of strict and non-strict subsets, and others.

Declaration

```
   template<typename T>
   class CHashSet : public ISet<T>
```

Header

```
   #include <Generic\HashSet.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        [ISet](iset.md)            CHashSet |

Class Methods

| Method | Description |
| --- | --- |
| [Add](chashsetadd.md) | Adds an element to a set |
| [Count](chashsetcount.md) | Returns the number of elements in a set |
| [Comparer](chashsetcomparer.md) | Determines whether a set contains an element with the specified value |
| [Contains](chashsetcontains.md) | Returns a pointer to the IEqualityComparer<T> interface, used to organize a set |
| [TrimExcess](chashsettrimexcess.md) | Sets the capacity of a set to the actual number of elements, and thus frees up unused memory |
| [CopyTo](chashsetcopyto.md) | Copies all elements of a set to the specified array starting at the specified index |
| [Clear](chashsetclear.md) | Removes all elements from a set |
| [Remove](chashsetremove.md) | Removes the specified element from a set |
| [ExceptWith](chashsetexceptwith.md) | Produces the operation of difference between the current collection and a passed collection (array) |
| [IntersectWith](chashsetintersectwith.md) | Produces the operation of intersection of the current collection and a passed collection (array) |
| [SymmetricExceptWith](chashsetsymmetricexceptwith.md) | Produces the operation of symmetrical difference between the current collection and a passed collection (array) |
| [UnionWith](chashsetunionwith.md) | Produces the union of the current collection and a passed collection (array) |
| [IsProperSubsetOf](chashsetispropersubsetof.md) | Determines whether the current set is a proper subset of the specified collection or array |
| [IsProperSupersetOf](chashsetispropersupersetof.md) | Determines whether the current set is a proper superset of the specified collection or array |
| [IsSubsetOf](chashsetissubsetof.md) | Determines whether the current set is a subset of the specified collection or array |
| [IsSupersetOf](chashsetissupersetof.md) | Determines whether the current set is a superset of the specified collection or array |
| [Overlaps](chashsetoverlaps.md) | Determines whether the current set overlaps the specified collection or array |
| [SetEquals](chashsetsetequals.md) | Determines whether the current set contains all elements of the specified collection or array |