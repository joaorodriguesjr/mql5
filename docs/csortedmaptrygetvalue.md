TryGetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CSortedMap<TKey, TValue](csortedmap.md)/

[![Previous](previous.png)](csortedmapremove.md) 
[![Next](next.png)](csortedmaptrysetvalue.md)

TryGetValue

Gets an element with the specified key from the sorted hash table.

```
bool TryGetValue(
   TKey     key,      // key
   TValue&  value     // a variable for writing the value
   );
```

Parameters

key

[in]  Key.

&value

[out]  The variable to which the specified value of the key/value pair will be written.

Return Value

Returns true on successful, or false otherwise.