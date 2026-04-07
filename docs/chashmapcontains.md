Contains



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CHashMap<TKey,TValue](chashmap.md)/

[![Previous](previous.png)](chashmapcomparer.md) 
[![Next](next.png)](chashmapcontainskey.md)

Contains

Determines whether the hash table contains the specified key/value pair.

The version for working with a generated key/value pair.

```
bool Contains(
   CKeyValuePair<TKeyTValue>*  item     // the key/value pair
   );
```

The version for working with a key/value pair in the form of a separately set key and value.

```
bool Contains(
   TKey   key,                          // key
   TValue value                         // value
   );
```

Parameters

*item

[in]  The key/value pair.

key

[in]  Key.

value

[in]  Value.

Return Value

Returns true, if the hash table contains the key/value pair with the specified key and value, or false otherwise.