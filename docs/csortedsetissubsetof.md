IsSubsetOf



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CSortedSet<T](csortedset.md)/

[![Previous](previous.png)](csortedsetispropersupersetof.md) 
[![Next](next.png)](csortedsetissupersetof.md)

IsSubsetOf

Determines whether the current sorted set is a subset of the specified collection or array.

A version for working with the collection that implements the ICollection<T> interface.

```
bool IsSubsetOf(
   ICollection<T>*  collection     // a collection to determine the relation
   );
```

A version for working with an array.

```
bool IsSubsetOf(
   T&  array[]                     // an array to determine the relation
   );
```

Parameters

*collection

[in]  A collection to determine the relation.

&collection[]

[in]  An array to determine the relation.

Return Value

Returns true if the current sorted set is a subset, or false otherwise.