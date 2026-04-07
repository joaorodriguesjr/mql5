Symbol



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / Symbol

[![Previous](previous.png)](cexpertbaseinit.md) 
[![Next](next.png)](cexpertbaseperiod.md)

Symbol

Sets the object symbol.

```
bool  Symbol(
   string    name     // symbol
   )
```

Parameters

name

[in]  Symbol.

Return Value

true - successful, otherwise - false.

Note

The setting of working symbol is necessary if the object uses the symbol different from symbol defined at the first initialization.