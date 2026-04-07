Break Operator



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Operators](operators.md) / Break Operator

[![Previous](previous.png)](dowhile.md) 
[![Next](next.png)](continue.md)

Break Operator

The break operator terminates the execution of the nearest nested outward [switch](switch.md), [while](while.md), [do-while](dowhile.md) or [for](for.md) operator. The control is passed to the operator that follows the terminated one. One of the purposes of this operator is to finish the looping execution when a certain value is assigned to a variable.

Example:

```
//--- searching for the first zero element
for(i=0;i<array_size;i++)
  if(array[i]==0)
    break;
```

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)