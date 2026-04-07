TrySetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CHashMap<TKey,TValue](chashmap.md)/

[![Previous](previous.png)](chashmaptrygetvalue.md) 
[![Next](next.png)](chashset.md)

TrySetValue

Changes the value of a key/value pair from the hash table at the specified key.

```
bool TrySetValue(
   TKey    key,      // key
   TValue  value     // new value
   );
```

Parameters

key

[in]  Key.

value

[in] The new value to assign to the specified key-value pair.

Return Value

Returns true on successful, or false otherwise.