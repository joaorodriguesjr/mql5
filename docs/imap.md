IMap<TKey,TValue>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / IMap<TKey,TValue

[![Previous](previous.png)](ilistremoveat.md) 
[![Next](next.png)](imapadd.md)

IMap<TKey, TValue>

IMap<TKey, TValue> is an interface for implementing generic collections of key/value pairs.

Description

The IMap<TKey, TValue> interface defines basic methods to work with collections whose data are stored as key/value pairs.

Declaration

```
   template<typename TKey, typename TValue>
   interface IMap : public ICollection<TKey>
```

Header

```
   #include <Generic\Interfaces\IMap.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        IMap  Direct descendants  [CHashMap](chashmap.md), [CSortedMap](csortedmap.md) |

Class Methods

| Method | Description |
| --- | --- |
| [Add](imapadd.md) | Adds a key/value pair to a collection |
| [Contains](imapcontains.md) | Determines whether a collection contains the key/value table with the specified key |
| [Remove](imapremove.md) | Removes the first occurrence of a key/value pair from a collection |
| [TryGetValue](imaptrygetvalue.md) | Gets an element with the specified key from a collection |
| [TrySetValue](imaptrysetvalue.md) | Changes the value of the key/value pair from a collection at the specified key |
| [CopyTo](imapcopyto.md) | Copies all key/value pairs from a collection to specified arrays, starting at the specified index |