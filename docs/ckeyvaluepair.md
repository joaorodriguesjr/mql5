CKeyValuePair<TKey,TValue>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CKeyValuePair<TKey,TValue

[![Previous](previous.png)](clinkedlistnodevalue.md) 
[![Next](next.png)](ckeyvaluepairkey.md)

CKeyValuePair<TKey,TValue>

The CKeyValuePair<TKey,TValue> class implements a key/value pair.

Description

The CKeyValuePair<TKey,TValue> class implements methods for working with the key and the value of the key/value pair.

Declaration

```
   template<typename TKey, typename TValue>
   class CKeyValuePair : public IComparable<CKeyValuePair<TKey,TValue>*>
```

Header

```
   #include <Generic\HashMap.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [IEqualityComparable](iequalitycomparable.md)        [IComparable](icomparable.md)            CKeyValuePair |

Class Methods

| Method | Description |
| --- | --- |
| [Key](ckeyvaluepairkey.md) | Gets and sets the key in the key/value pair |
| [Value](ckeyvaluepairvalue.md) | Gets and sets the value in the key/value pair |
| [Clone](ckeyvaluepairclone.md) | Creates a new key/value pair whose key and value are equal to the current ones |
| [Compare](ckeyvaluepaircompare.md) | Compares the current key/value pair to the specified one |
| [Equals](ckeyvaluepairequals.md) | Checks whether the current key/value pair and the specified one are equal |
| [HashCode](ckeyvaluepairhashcode.md) | Calculates the hash value based on the key/value pair |