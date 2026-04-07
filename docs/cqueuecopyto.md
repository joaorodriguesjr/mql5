CopyTo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CQueue<T](cqueue.md)/

[![Previous](previous.png)](cqueuetrimexcess.md) 
[![Next](next.png)](cqueueclear.md)

CopyTo

Copies all elements of a queue to the specified array starting at the specified index.

```
int CopyTo(
   T&         dst_array[],     // an array for writing
   const int  dst_start=0      // the starting index for writing
   );
```

Parameters

&dst\_array[]

[out] An array to which the elements of the queue will be written.

dst\_start=0

[in] An index in the array from which copying starts.

Return Value

Returns the number of copied elements.