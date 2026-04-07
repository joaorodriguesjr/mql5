ISet<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / ISet<T

[![Previous](previous.png)](imapcopyto.md) 
[![Next](next.png)](isetexceptwith.md)

ISet<T>

ISet<T> is an interface for implementing generic data sets.

Description

The ISet interface defines basic methods to work with sets, such as: the union and intersection of sets, definition of strict and non-strict subsets, and others.

Declaration

```
   template<typename T>
   interface ISet : public ICollection<T>
```

Header

```
   #include <Generic\Interfaces\ISet.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        ISet  Direct descendants  [CHashSet](chashset.md), [CSortedSet](csortedset.md) |

Class Methods

| Method | Description |
| --- | --- |
| [ExceptWith](isetexceptwith.md) | Produces the operation of difference between the current collection and a passed collection (array) |
| [IntersectWith](isetintersectwith.md) | Produces the operation of intersection of the current collection and a passed collection (array) |
| [SymmetricExceptWith](isetsymmetricexceptwith.md) | Produces the operation of symmetrical difference between the current collection and a passed collection (array) |
| [UnionWith](isetunionwith.md) | Produces the union of the current collection and a passed collection (array) |
| [IsProperSubsetOf](isetispropersubsetof.md) | Determines whether the current set is a proper subset of the specified collection or array |
| [IsProperSupersetOf](isetispropersupersetof.md) | Determines whether the current set is a proper superset of the specified collection or array |
| [IsSubsetOf](isetissubsetof.md) | Determines whether the current set is a subset of the specified collection or array |
| [IsSupersetOf](isetissupersetof.md) | Determines whether the current set is a superset of the specified collection or array |
| [Overlaps](isetoverlaps.md) | Determines whether the current set overlaps the specified collection or array |
| [SetEquals](isetsetequals.md) | Determines whether the current set contains all elements of the specified collection or array |