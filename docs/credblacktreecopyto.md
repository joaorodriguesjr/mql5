CopyTo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CRedBlackTree<T](credblacktree.md)/

[![Previous](previous.png)](credblacktreetrygetmax.md) 
[![Next](next.png)](credblacktreeclear.md)

CopyTo

Copies all elements of a redblack tree to the specified array starting at the specified index.

```
int CopyTo(
   T&         dst_array[],     // an array for writing
   const int  dst_start=0      // starting index for writing
   );
```

Parameters

&dst\_array[]

[out] An array to which the elements of the redblack tree will be written.

dst\_start=0

[in] An index in the array from which copying starts.

Return Value

Returns the number of copied elements.