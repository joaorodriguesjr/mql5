IEqualityComparer<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / IEqualityComparer<T

[![Previous](previous.png)](icomparercompare.md) 
[![Next](next.png)](iequalitycomparerequals.md)

IEqualityComparer<T>

IEqualityComparer<T> is an interface for implementing a generic class that compares two object of the T type.

Description

The IEqualityComparer<T> interface defines methods to retrieve the hash code of a T type object and to check whether two objects of type T are equal.

Declaration

```
   template<typename T>
   interface IEqualityComparer
```

Header

```
   #include <Generic\Interfaces\IEqualityComparer.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    IEqualityComparer  Direct descendants  [CDefaultEqualityComparer](cdefaultequalitycomparer.md) |

Class Methods

| Method | Description |
| --- | --- |
| [Equals](iequalitycomparerequals.md) | Compares two values of type T |
| [HashCode](iequalitycomparerhashcode.md) | Calculates the hash code value based on the T type object |