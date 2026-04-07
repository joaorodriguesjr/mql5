TradeEventNotIdentified



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpert](cexpert.md) / TradeEventNotIdentified

[![Previous](previous.png)](cexperttradeeventorderdeleted.md) 
[![Next](next.png)](cexperttimeframeadd.md)

TradeEventNotIdentified

Event handler of the non-identified event.

```
virtual bool  TradeEventNotIdentified()
```

Return Value

The [CExpert](cexpert.md) class method does nothing and always returns true.

Note

Note that several trade events can arrive, in such cases it is difficult to identify them.