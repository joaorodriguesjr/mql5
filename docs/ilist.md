IList<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / IList<T

[![Previous](previous.png)](iequalitycomparerhashcode.md) 
[![Next](next.png)](ilisttrygetvalue.md)

IList<T>

IList<T> is an interface for implementing generic data lists.

Description

The IList<T> interface defines basic methods to work with lists, such as to access an element by index, to search and delete elements, sort, and others.

Declaration

```
   template<typename T>
   interface IList : public ICollection<T>
```

Header

```
   #include <Generic\Interfaces\IList.mqh>
```

|  |
| --- |
| Inheritance Hierarchy    [ICollection](icollection.md)        IList  Direct descendants  [CArrayList](carraylist.md) |

Class Methods

| Method | Description |
| --- | --- |
| [TryGetValue](ilisttrygetvalue.md) | Gets a list element at the specified index |
| [TrySetValue](ilisttrysetvalue.md) | Changes a value from the list at the specified index |
| [Insert](ilistinsert.md) | Inserts an element into the list at the specified index |
| [IndexOf](ilistindexof.md) | Searches for the first occurrence of a value in a list |
| [LastIndexOf](ilistlastindexof.md) | Searches for the last occurrence of a value in a list |
| [RemoveAt](ilistremoveat.md) | Removes a list element at the specified index |