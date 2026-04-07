Expression Operator



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Operators](operators.md) / Expression Operator

[![Previous](previous.png)](compound.md) 
[![Next](next.png)](return.md)

Expression Operator

Any expression followed by a semicolon (;) is the operator. Here are some examples of expression operators.

Assignment Operator

Identifier = expression;

```
  x=3;
  y=x=3; 
  bool equal=(x==y);
```

Assignment operator can be used many times in an expression. In this case, the expression is processed from right to left.

Function Calling Operator

Function\_name (argument1,..., argumentN);

```
  FileClose(file);
```

Empty Operator

Consists only of a semicolon (;) and is used to denote an empty body of a control operator.

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)