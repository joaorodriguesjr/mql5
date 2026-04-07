CLinkedListNode<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CLinkedListNode<T

[![Previous](previous.png)](credblacktreenodecreateemptynode.md) 
[![Next](next.png)](clinkedlistnodelist.md)

CLinkedListNode<T>

CLinkedListNode<T> is a helper class used in implementing the CLinkedListNode<T> class.

Description

The CLinkedListNode<T> class is a node of the doubly linked list CLinkedListNode<T>. List navigation methods are implemented in the class.

Declaration

```
   template<typename T>
   class CLinkedListNode
```

Header

```
   #include <Generic\LinkedList.mqh>
```

Class Methods

| Method | Description |
| --- | --- |
| [List](clinkedlistnodelist.md) | Returns and sets a pointer to the CLinkedList<T> |
| [Next](clinkedlistnodenext.md) | Returns and sets a pointer to the next node |
| [Previous](clinkedlistnodeprevious.md) | Returns and sets a pointer to the previous node |
| [Value](clinkedlistnodevalue.md) | Returns and sets the node value |