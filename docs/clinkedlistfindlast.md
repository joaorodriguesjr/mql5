FindLast



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CLinkedList<T](clinkedlist.md)/

[![Previous](previous.png)](clinkedlistfind.md) 
[![Next](next.png)](cqueue.md)

FindLast

Searches for the last occurrence of the specified value in the linked list.

```
CLinkedListNode<T>* FindLast(
   T  value     // the search value
   );
```

Parameters

value

[in]  The searched value.

Return Value

Returns a pointer to the last found node containing the search value on success, or NULL otherwise.