CRedBlackTree<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CRedBlackTree<T

[![Previous](previous.png)](cqueuepeek.md) 
[![Next](next.png)](credblacktreeadd.md)

CRedBlackTree<T>

CRedBlackTree<T> is a generic class that implements the ICollection<T> interface.

Description

The CRedBlackTree<T> class is an implementation of a dynamic redblack tree whose nodes store T type data. The class provides basic methods to work with redblack trees, such as to add, delete, search for the maximum and minimum value, and more.

Declaration

```
   template<typename T>
   class CRedBlackTree : public ICollection<T>
```

Header

```
   #include <Generic\RedBlackTree.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        CRedBlackTree |

Class Methods

| Method | Description |
| --- | --- |
| [Add](credblacktreeadd.md) | Adds an element to a redblack tree |
| [Root](credblacktreeroot.md) | Returns a pointer to the root of the redblack tree |
| [Count](credblacktreecount.md) | Returns the number of elements in the redblack tree |
| [Contains](credblacktreecontains.md) | Determines whether the redblack tree contains an element with the specified value |
| [Comparer](credblacktreecomparer.md) | Returns a pointer to the IComparer<T> interface used to organize a redblack tree |
| [TryGetMin](credblacktreetrygetmin.md) | Gets the minimum element of a redblack tree |
| [TryGetMax](credblacktreetrygetmax.md) | Gets the maximum element of a redblack tree |
| [CopyTo](credblacktreecopyto.md) | Copies all elements of a redblack tree to the specified array starting at the specified index |
| [Clear](credblacktreeclear.md) | Removes all elements from a redblack tree |
| [Remove](credblacktreeremove.md) | Removes the occurrence of the specified element from a redblack tree |
| [RemoveMin](credblacktreeremovemin.md) | Removes an element with the minimum value from a redblack tree |
| [RemoveMax](credblacktreeremovemax.md) | Removes an element with the maximum value from a redblack tree |
| [Find](credblacktreefind.md) | Searches for the occurrence of a specified value in a redblack tree |
| [FindMax](credblacktreefindmax.md) | Searches for an element with the maximum value in a redblack tree |
| [FindMin](credblacktreefindmin.md) | Searches for an element with the minimum value in a redblack tree |