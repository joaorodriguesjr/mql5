Operators



[MQL5 Reference](index.md)  /  [Language Basics](basis.md) / Operators

[![Previous](previous.png)](rules.md) 
[![Next](next.png)](compound.md)

Operators

Language operators describe some algorithmic operations that must be executed to accomplish a task. The program body is a sequence of such operators. Operators following one by one are separated by semicolons.

| Operator | Description |
| --- | --- |
| [Compound operator {}](compound.md) | One or more operators of any type, enclosed in curly braces {} |
| [Expression operator (;)](expression.md) | Any expression that ends with a semicolon (;) |
| [return](return.md) operator | Terminates the current function and returns control to the calling program |
| [if-else](if.md) conditional operator | Is used when it's necessary to make a choice |
| [?:](ternary.md) conditional operator | A simple analog of the if-else conditional operator |
| [switch](switch.md) selection operator | Passes control to the operator, which corresponds to the expression value |
| [while](while.md) loop operator | Performs an operator until the expression checked becomes false. The expression is checked before each iteration |
| [for](for.md) loop operator | Performs an operator until the expression checked becomes false. The expression is checked before each iteration |
| [do-while](dowhile.md) loop operator | Performs an operator until the expression checked becomes false. The end condition is checked, after each loop. The loop body is always executed at least once. |
| [break](break.md) operator | Terminates the execution of the nearest attached external operator switch, while, do-while or for |
| [continue](continue.md) operator | Passes control to the beginning of the nearest external loop operator while, do-while or for |
| [@](matmul.md) operator | Implements matrix multiplication according to the rules of linear algebra. It allows multiplying [matrices and vectors](matrix.md), as well as performing scalar multiplication of vectors. |
| [new](newoperator.md) operator | Creates an object of the appropriate size and returns a descriptor of the created object. |
| [delete](deleteoperator.md) operator | Deletes the object created by the new operator |

One operator can occupy one or more lines. Two or more operators can be located in the same line. Operators that control over the execution order (if, if-else, switch, while and for), can be nested into each other.

Example:

```
if(Month() == 12)
  if(Day() == 31) Print("Happy New Year!");
```

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)