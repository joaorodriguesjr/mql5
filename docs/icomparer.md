IComparer<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / IComparer<T

[![Previous](previous.png)](icomparablecompare.md) 
[![Next](next.png)](icomparercompare.md)

IComparer<T>

IComparer<T> is an interface for implementing a generic class that compares two object of the T type, whether one is greater than, less than or equal to the other one

Description

The IComparer<T> interface determines a method to compare two objects of the T type, on the basis of which a collection of these objects can be sorted.

Declaration

```
   template<typename T>
   interface IComparer
```

Header

```
   #include <Generic\Interfaces\IComparer.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    IComparer  Direct descendants  [CDefaultComparer](cdefaultcomparer.md) |

Class Methods

| Method | Description |
| --- | --- |
| [Compare](icomparercompare.md) | Compares two values of type T |