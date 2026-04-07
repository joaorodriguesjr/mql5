Remove



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CSortedMap<TKey, TValue](csortedmap.md)/

[![Previous](previous.png)](csortedmapclear.md) 
[![Next](next.png)](csortedmaptrygetvalue.md)

Remove

Removes the first occurrence of the key/value pair from the sorted hash table.

The version that removes a key-value pair based on the generated key-value pair.

```
bool Remove(
   CKeyValuePair<TKeyTValue>*  item     // the key/value pair
   );
```

The version that removes a key-value pair based on the key.

```
bool Remove(
   TKey  key                            // key
   );
```

Parameters

*item

[in]  The key/value pair.

key

[in]  Key.

Return Value

Returns true on successful, or false otherwise.