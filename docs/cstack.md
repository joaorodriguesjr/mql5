CStack<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CStack<T

[![Previous](previous.png)](csortedsetgetreverse.md) 
[![Next](next.png)](cstackadd.md)

CStack<T>

CStack<T> is a generic class that implements the ICollection<T> interface.

Description

The CStack<T> class is a dynamic collection of T type data, which is organized as a stack that operates on the LIFO (last in, first out) principle.

Declaration

```
   template<typename T>
   class CStack : public ICollection<T>
```

Header

```
   #include <Generic\Stack.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        CStack |

Class Methods

| Method | Description |
| --- | --- |
| [Add](cstackadd.md) | Adds an element to a stack |
| [Count](cstackcount.md) | Returns the number of elements in a stack |
| [Contains](cstackcontains.md) | Determines whether a stack contains an element with the specified value |
| [TrimExcess](cstacktrimexcess.md) | Sets the capacity of a stack to the actual number of elements |
| [CopyTo](cstackcopyto.md) | Copies all elements of a stack to the specified array starting at the specified index |
| [Clear](cstackclear.md) | Removes all elements from a stack |
| [Remove](cstackremove.md) | Removes the first occurrence of the specified element from a stack |
| [Push](cstackpush.md) | Adds an element to a stack |
| [Peek](cstackpeek.md) | Returns the head element without removing it from a stack |
| [Pop](cstackpop.md) | Returns the head element and removes it from a stack |