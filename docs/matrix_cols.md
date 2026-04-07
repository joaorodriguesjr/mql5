Cols



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Features](matrix_characteristics.md) / Cols

[![Previous](previous.png)](matrix_rows.md) 
[![Next](next.png)](matrix_size.md)

Cols

Return the number of columns in a matrix.

```
ulong matrix::Cols()
```

Return Value

Integer.

 

Example

```
  matrix m= {{1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12}};
  m.Reshape(3, 4);
  Print("matrix m \n" , m);
  Print("m.Cols()=", m.Cols());
  Print("m.Rows()=", m.Rows());
 
  /*
   matrix m 
   [[1,2,3,4]
    [5,6,7,8]
    [9,10,11,12]]
   m.Cols()=4
   m.Rows()=3
  */
```