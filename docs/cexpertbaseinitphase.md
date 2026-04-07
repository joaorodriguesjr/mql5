InitPhase



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Base classes for Expert Advisors](expertbaseclasses.md)  /  [CExpertBase](cexpertbase.md) / InitPhase

[![Previous](previous.png)](cexpertbase.md) 
[![Next](next.png)](cexpertbasetrendtype.md)

InitPhase

Gets the current phase of the object initialization.

```
ENUM_INIT_PHASE  InitPhase()
```

Return Value

Current phase of the object initialization.

Note

The object initialization consist of several phases:

1. Start initialization.

  - start              - after finish of the constructor  
   - finish             - after successful completion of the [Init(...)](cexpertbaseinit.md) method.  
   - allowed          - call of the [Init(...)](cexpertbaseinit.md) method  
   - not allowed    - call of the [ValidationSettings()](cexpertbasevalidationsettings.md) method and other initialization methods

2. Parameters setting phase. In this phase you need to set all the object parameters, used for creation of indicators.

  - start             - after successful completion of the [Init(...)](cexpertbaseinit.md) method  
   - finish            - after successful completion of the [ValidationSettings()](cexpertbasevalidationsettings.md) method  
   - allowed         - call of [Symbol(...)](cexpertbasesymbol.md) and [Period(...)](cexpertbaseperiod.md) methods  
   - not allowed   - call of the [Init(...)](cexpertbaseinit.md), [SetPriceSeries(...)](cexpertbasesetpriceseries.md), [SetOtherSeries(...)](cexpertbasesetotherseries.md) and [InitIndicators(...)](cexpertbaseinitindicators.md) methods

3. Checking of parameters.

  - start             - after successful completion of the [ValidationSettings()](cexpertbasevalidationsettings.md) method  
   - finish            - after successful completion of the [InitIndicators(...)](cexpertbaseinitindicators.md) method  
   - allowed         - call of the [Symbol(...)](cexpertbasesymbol.md), [Period(...)](cexpertbaseperiod.md) and [InitIndicators(...)](cexpertbaseinitindicators.md) methods  
   - not allowed   - call of any other initialization methods

4. Finish of initialization.

  - start             - after successful completion of the [InitIndicators(...)](cexpertbaseinitindicators.md) method  
   - not allowed    - call of initialization methods