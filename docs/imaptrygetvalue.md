TryGetValue



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [IMap<TKey,TValue](imap.md)/

[![Previous](previous.png)](imapremove.md) 
[![Next](next.png)](imaptrysetvalue.md)

TryGetValue

Gets an element with the specified key from a collection.

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