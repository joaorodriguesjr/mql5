CopyTo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CLinkedList<T](clinkedlist.md)/

[![Previous](previous.png)](clinkedlistcontains.md) 
[![Next](next.png)](clinkedlistclear.md)

CopyTo

Copies all elements of the linked list to the specified array starting at the specified index.

```
int CopyTo(
   T&         dst_array[],     // an array for writing
   const int  dst_start=0      // the starting index for writing
   );
```

Parameters

&dst\_array[]

[out] An array to which the elements of the linked list will be written.

dst\_start=0

[in] An index in the array from which copying starts.

Return Value

Returns the number of copied elements.