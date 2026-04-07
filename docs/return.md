Return Operator



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Operators](operators.md) / Return Operator

[![Previous](previous.png)](expression.md) 
[![Next](next.png)](if.md)

Return Operator

The return operator terminates the current [function](function.md) execution and returns control to the calling program. The expression calculation result is returned to the calling function. The expression can contain an assignment operator.

Example:

```
int CalcSum(int x, int y)
  {
   return(x+y);
  }
```

In functions with the [void](void.md) return type, the return operator without expression must be used:

```
void SomeFunction()
  {
   Print("Hello!");
   return;    // this operator can be removed
  }
```

The right brace of the function means implicit execution of the return operator without expression.

What can be returned: [simple types](types.md#base_types), [simple structures](classes.md#simple_structure), [object pointers](object_pointers.md). With  the return operator you can't return any arrays, class objects, variables of compound structure type.

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)