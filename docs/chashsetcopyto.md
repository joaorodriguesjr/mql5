CopyTo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CHashSet<T](chashset.md)/

[![Previous](previous.png)](chashsettrimexcess.md) 
[![Next](next.png)](chashsetclear.md)

CopyTo

Copies all elements of a set to the specified array starting at the specified index.

```
int CopyTo(
   T&         dst_array[],     // an array for writing
   const int  dst_start=0      // starting index for writing
   );
```

Parameters

&dst\_array[]

[out] An array to which the elements of the set will be written.

dst\_start=0

[in] An index in the array from which copying starts.

Return Value

Returns the number of copied elements.