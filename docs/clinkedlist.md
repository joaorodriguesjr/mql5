CLinkedList<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CLinkedList<T

[![Previous](previous.png)](chashsetsetequals.md) 
[![Next](next.png)](clinkedlistadd.md)

CLinkedList<T>

CLinkedList<T> is a generic class that implements the ICollection<T> interface.

Description

The CLinkedList<T> class is an implementation of the dynamic doubly linked data list of the T type. This class provides basic methods to work with doubly linked lists, such as to add, delete, search elements, and others.

Declaration

```
   template<typename T>
   class CLinkedList : public ICollection<T>
```

Header

```
   #include <Generic\LinkedList.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        CLinkedList |

Class Methods

| Method | Description |
| --- | --- |
| [Add](clinkedlistadd.md) | Adds an element to a linked list |
| [AddAfter](clinkedlistaddafter.md) | Adds an element after the specified node in the linked list |
| [AddBefore](clinkedlistaddbefore.md) | Adds an element before the specified node in the linked list |
| [AddFirst](clinkedlistaddfirst.md) | Adds an element at the beginning of the linked list |
| [AddLast](clinkedlistaddlast.md) | Adds an element at the end of the linked list |
| [Count](clinkedlistcount.md) | Returns the number of elements in the linked list |
| [Head](clinkedlisthead.md) | Returns a pointer to the first node of the linked list |
| [First](clinkedlistfirst.md) | Returns a pointer to the first node of the linked list |
| [Last](clinkedlistlast.md) | Returns a pointer to the last node of the linked list |
| [Contains](clinkedlistcontains.md) | Determines whether the linked list contains an element with the specified value |
| [CopyTo](clinkedlistcopyto.md) | Copies all elements of the linked list to the specified array starting at the specified index |
| [Clear](clinkedlistclear.md) | Removes all elements from a linked list |
| [Remove](clinkedlistremove.md) | Removes the first occurrence of the specified element from the linked list |
| [RemoveFirst](clinkedlistremovefirst.md) | Removes the first element of the linked list |
| [RemoveLast](clinkedlistremovelast.md) | Removes the last element of the linked list |
| [Find](clinkedlistfind.md) | Searches for the first occurrence of the specified value in the linked list |
| [FindLast](clinkedlistfindlast.md) | Searches for the last occurrence of the specified value in the linked list |