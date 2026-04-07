IComparable<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / IComparable<T

[![Previous](previous.png)](iequalitycomparablehashcode.md) 
[![Next](next.png)](icomparablecompare.md)

IComparable<T>

IComparable<T> is an interface for implementing objects that can be compared to find out whether one is greater than, less than or equal to the other one

Description

The IComparable<T> interface defines a method to compare the current object to another object of the same type, on the basis of which the collection of these objects can be sorted.

Declaration

```
   template<typename T>
   interface IComparable : public IEqualityComparable<T>
```

Header

```
   #include <Generic\Interfaces\IComparable.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [IEqualityComparable](iequalitycomparable.md)        IComparable  Direct descendants  [CKeyValuePair](ckeyvaluepair.md) |

Class Methods

| Method | Description |
| --- | --- |
| [Compare](icomparablecompare.md) | Compares the current object with the specified value |