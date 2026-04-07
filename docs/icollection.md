ICollection<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / ICollection<T

[![Previous](previous.png)](generic.md) 
[![Next](next.png)](icollectionadd.md)

ICollection<T>

ICollection<T> is an interface for implementing generic data collections.

Description

The ICollection<T> interface determines basic methods to work with collections, including methods to count elements, to clear a collection, to add or delete elements, and others.

Declaration

```
   template<typename T>
   interface ICollection
```

Header

```
   #include <Generic\Interfaces\ICollection.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    ICollection  Direct descendants  [CLinkedList](clinkedlist.md), [CQueue](cqueue.md), [CRedBlackTree](credblacktree.md), [CStack](cstack.md), [IList](ilist.md), [IMap](imap.md), [ISet](iset.md) |

Class Methods

| Method | Description |
| --- | --- |
| [Add](icollectionadd.md) | Adds an element to a collection |
| [Count](icollectioncount.md) | Returns the number of elements in a collection |
| [Contains](icollectioncontains.md) | Determines whether a collection contains an element with the specified value |
| [CopyTo](icollectioncopyto.md) | Copies all elements of a collection to the specified array starting at the specified index |
| [Clear](icollectionclear.md) | Removes all elements from a collection |
| [Remove](icollectionremove.md) | Removes the first occurrence of the specified element from a collection |