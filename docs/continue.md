Continue Operator



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Operators](operators.md) / Continue Operator

[![Previous](previous.png)](break.md) 
[![Next](next.png)](matmul.md)

Continue Operator

The continue operator passes control to the beginning of the nearest outward loop [while](while.md), [do-while](dowhile.md) or [for](for.md) operator, the next iteration being called. The purpose of this operator is opposite to that of [break](break.md) operator.

Example:

```
//--- Sum of all nonzero elements
int func(int array[])
  {
   int array_size=ArraySize(array);
   int sum=0;
   for(int i=0;i<array_size; i++)
     {
      if(a[i]==0) continue;
      sum+=a[i];
     }
   return(sum);
  }
```

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)