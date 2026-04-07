Equals<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / Equals<T

[![Previous](previous.png)](compare.md) 
[![Next](next.png)](gethashcode.md)

Equals

Compares two values ​​for equality.

```
template<typename T>
bool Equals(
   T  x,     // the first value
   T  y      // the second value
   );
```

Parameters

x

[in]  The first value

y

[in]  The second value

Return Value

Returns true if the objects are equal, or false otherwise.

Note

If the T type is an object that implements the IEqualityComparable<T> interface, then the objects will be compared based on its Equals comparison method. The standard comparison for equality is used in all other cases.