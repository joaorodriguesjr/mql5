Loop Operator while



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Operators](operators.md) / Loop Operator while

[![Previous](previous.png)](switch.md) 
[![Next](next.png)](for.md)

While Loop Operator

The while operator consists of a checked expression and the operator, which must be fulfilled:

```
while(expression)
  operator;
```

If the expression is true, the operator is executed until the expression becomes false. If the expression is false, the control is passed to the next operator. The expression value is defined before the operator is executed. Therefore, if the expression is false from the very beginning, the operator will not be executed at all.

Note

If it is expected that a large number of iterations will be handled in a loop, it is advisable that you check the fact of forced program termination using the [IsStopped()](isstopped.md) function.

Example:

```
while(k<n && !IsStopped())
  {
   y=y*x;
   k++;
  }
```

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)