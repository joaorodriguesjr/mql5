LongCondition



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertSignal](cexpertsignal.md) / LongCondition

[![Previous](previous.png)](cexpertsignalchecktrailingordershort.md) 
[![Next](next.png)](cexpertsignalshortcondition.md)

LongCondition

Checks conditions to open a long position.

```
virtual int  LongCondition()
```

Return Value

If the conditions are satisfied, it returns the value from 1 to 100 (depending on "strength" of a signal). If there is no signal to open a long position, it returns 0.

Note

The base class has no implementation of checking conditions to open a long position and always returns 0.