CSortedMap<TKey,TValue>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CSortedMap<TKey, TValue

[![Previous](previous.png)](credblacktreefindmax.md) 
[![Next](next.png)](csortedmapadd.md)

CSortedMap<TKey,TValue>

CSortedMap<TKey,TValue> is a generic class that implements the IMap<TKey,TValue> interface.

Description

The CSortedMap<TKey,TValue> class is an implementation of a dynamic hash table whose data are stored as key/value pairs sorted by key and taking into account the key uniqueness requirement. This class provides basic methods to work with a hash table, such as to access a value by key, to search and delete a key/value pair, and others.

Declaration

```
   template<typename TKey, typename TValue>
   class CSortedMap : public IMap<TKey, TValue>
```

Header

```
   #include <Generic\SortedMap.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        [IMap](imap.md)            CSortedMap |

Class Methods

| Method | Description |
| --- | --- |
| [Add](csortedmapadd.md) | Adds a key/value pair to the hash table |
| [Count](csortedmapcount.md) | Returns the number of elements in the sorted hash table |
| [Contains](csortedmapcontains.md) | Determines whether the sorted hash table contains the specified key/value table |
| [ContainsKey](csortedmapcontainskey.md) | Determines whether the sorted hash table contains the key/value table with the specified key |
| [ContainsValue](csortedmapcontainsvalue.md) | Determines whether the sorted hash table contains the key/value table with the specified value |
| [Comparer](csortedmapcomparer.md) | Returns a pointer to the IComparer<T> interface, used to organize a sorted hash table |
| [CopyTo](csortedmapcopyto.md) | Copies all key/value pairs from the sorted hash table to the specified arrays, starting at the specified index |
| [Clear](csortedmapclear.md) | Removes all elements from the sorted hash table |
| [Remove](csortedmapremove.md) | Removes the first occurrence of the key/value pair from the sorted hash table |
| [TryGetValue](csortedmaptrygetvalue.md) | Gets an element with the specified key from the sorted hash table |
| [TrySetValue](csortedmaptrysetvalue.md) | Changes a key/value pair with the specified key from the sorted hash table |