Generic



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md) / Generic Data Collections

[![Previous](previous.png)](ctreetype.md) 
[![Next](next.png)](icollection.md)

Generic Data Collections

The library provides classes and interfaces that define generic collections, which allow users to create strongly typed collections. These collections provide greater convenience and data handling performance than non-generic typed collections.

The library is available in the Include\Generic folder of the terminal working directory.

Objects:

| Object | Description | Type |
| --- | --- | --- |
| [ICollection](icollection.md) | Interface for implementing generic data collections | INTERFACE |
| [IEqualityComparable](iequalitycomparable.md) | Interface for implementing objects that can be compared | INTERFACE |
| [IComparable](icomparable.md) | Interface for implementing objects that can be compared in terms of "greater than, less than or equal to" | INTERFACE |
| [IComparer](icomparer.md) | Interface for implementing a generic class that compares two object of the T type, whether one is "greater than, less than or equal to" the other one | INTERFACE |
| [IEqualityComparer](iequalitycomparer.md) | Interface for implementing a generic class that compares two object of the T type for equality | INTERFACE |
| [IList](ilist.md) | Interface for implementing generic data lists | INTERFACE |
| [IMap](imap.md) | Interface for implementing generic collections of key/value pairs | INTERFACE |
| [ISet](iset.md) | Interface for implementing generic data sets | INTERFACE |
| [CDefaultComparer](cdefaultcomparer.md) | A helper class that implements the IComparer<T> generic interface based on Compare global methods | CLASS |
| [CDefaultEqualityComparer](cdefaultequalitycomparer.md) | A helper class that implements the IEqualityComparer<T> generic interface using Equals<T> and GetHashCode global methods | CLASS |
| [CArrayList](carraylist.md) | A generic class that implements the IList<T> interface | CLASS |
| [CKeyValuePair](ckeyvaluepair.md) | The class implements the key/value pair | CLASS |
| [CHashMap](chashmap.md) | A generic class that implements the IMap<TKey, TValue> interface | CLASS |
| [CHashSet](chashset.md) | A generic class that implements the ISet<T> interface | CLASS |
| [CLinkedListNode](clinkedlistnode.md) | A helper class for implementing the CLinkedListNode<T> class | CLASS |
| [CLinkedList](clinkedlist.md) | A generic class that implements the ICollection<T> interface | CLASS |
| [CQueue](cqueue.md) | A generic class that implements the ICollection<T> interface | CLASS |
| [CRedBlackTreeNode](credblacktreenode.md) | A helper class used in implementing the CRedBlackTree<T> class | CLASS |
| [CRedBlackTree](credblacktree.md) | A generic class that implements the ICollection<T> interface | CLASS |
| [CSortedMap](csortedmap.md) | A generic class that implements the IMap<TKey, TValue> interface | CLASS |
| [CSortedSet](csortedset.md) | A generic class that implements the ISet<T> interface | CLASS |
| [CStack](cstack.md) | A generic class that implements the ICollection<T> interface | CLASS |

Global methods:

| Method | Description |
| --- | --- |
| [ArrayBinarySearch](arraybinarysearch.md) | Searches for the specified value in an ascending-sorted one-dimensional array using the IComparable<T> interface to compare elements |
| [ArrayIndexOf](arrayindexof.md) | Searches for the first occurrence of a value in a one-dimensional array |
| [ArrayLastIndexOf](arraylastindexof.md) | Searches for the last occurrence of a value in a one-dimensional array |
| [ArrayReverse](arrayreverse.md) | Changes the sequence of elements in a one-dimensional array |
| [Compare](compare.md) | Compares two values, whether one of them is greater than, less than or equal to the other one |
| [Equals](equals.md) | Compares two values ​​for equality |
| [GetHashCode](gethashcode.md) | Calculates the hash code value |