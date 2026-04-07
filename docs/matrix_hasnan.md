HasNan



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Manipulations](matrix_manipulations.md) / HasNan

[![Previous](previous.png)](matrix_manipulations.md) 
[![Next](next.png)](matrix_replacenan.md)

HasNan

Return the number of [NaN](double.md) values in a matrix/vector.

```
ulong vector::HasNan();
 
ulong matrix::HasNan();
```

Return Value

The number of matrix/vector elements that contain a NaN value.

 

Note

When comparing the appropriate pair of elements having NaN values, the [Compare](matrix_compare.md) and [CompareByDigits](matrix_comparebydigits.md) methods consider these elements equal, while in case of a usual comparison of floating-point numbers NaN != NaN.

 

Example:

```
void OnStart(void)
  {
   double x=sqrt(-1);
 
   Print("single: ",x==x);
 
   vector<double> v1={x};
   vector<double> v2={x};
 
   Print("vector: ", v1.Compare(v2,0)==0);
  }
 
/* Result:
 
 single: false
 vector: true
*/
```

 

See also

[MathClassify](mathclassify.md), [Compare](matrix_compare.md), [CompareByDigits](matrix_comparebydigits.md)