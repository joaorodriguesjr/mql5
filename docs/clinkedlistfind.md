Find



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CLinkedList<T](clinkedlist.md)/

[![Previous](previous.png)](clinkedlistremovelast.md) 
[![Next](next.png)](clinkedlistfindlast.md)

Find

Searches for the first occurrence of the specified value in the linked list.

```
CLinkedListNode<T>* Find(
   T  value     // the search value
   );
```

Parameters

value

[in]  The searched value.

Return Value

Returns a pointer to the first found node containing the search value on success, or NULL otherwise.