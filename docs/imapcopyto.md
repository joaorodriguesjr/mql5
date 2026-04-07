CopyTo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [IMap<TKey,TValue](imap.md)/

[![Previous](previous.png)](imaptrysetvalue.md) 
[![Next](next.png)](iset.md)

CopyTo

Copies all key/value pairs from a collection to the specified arrays, starting at the specified index.

```
int CopyTo(
   TKey&      dst_keys[],       // an array for writing keys
   TValue&    dst_values[],     // an array for writing values
   const int  dst_start=0       // the starting index for writing
   );
```

Parameters

&dst\_keys[]

[out] An array to which all keys from the collection will be written.

&dst\_values[]

[out] An array to which values of corresponding keys from the collection will be written.

dst\_start=0

[in] An index in the array from which copying starts.

Return Value

Returns the number of copied key/value pairs.