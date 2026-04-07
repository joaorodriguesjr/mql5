CQueue<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CQueue<T

[![Previous](previous.png)](clinkedlistfindlast.md) 
[![Next](next.png)](cqueueadd.md)

CQueue<T>

CQueue<T> is a generic class that implements the ICollection<T> interface.

Description

The CQueue<T> class is a dynamic collection of T type data, which is organized as a queue that operates on the FIFO (first in, first out) principle.

Declaration

```
   template<typename T>
   class CQueue : public ICollection<T>
```

Header

```
   #include <Generic\Queue.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        CQueue |

Class Methods

| Method | Description |
| --- | --- |
| [Add](cqueueadd.md) | Adds an element to a queue |
| [Enqueue](cqueueenqueue.md) | Adds an element to a queue |
| [Count](cqueuecount.md) | Returns the number of elements in the queue |
| [Contains](cqueuecontains.md) | Determines whether the queue contains an element with the specified value |
| [TrimExcess](cqueuetrimexcess.md) | Sets the capacity of a queue to the actual number of elements, and thus frees up unused memory |
| [CopyTo](cqueuecopyto.md) | Copies all elements of a queue to the specified array starting at the specified index |
| [Clear](cqueueclear.md) | Removes all elements from a queue |
| [Remove](cqueueremove.md) | Removes the first occurrence of the specified element from the queue |
| [Dequeue](cqueuedequeue.md) | Returns the starting element and removes it from the queue |
| [Peek](cqueuepeek.md) | Returns the starting element without removing it from the queue |