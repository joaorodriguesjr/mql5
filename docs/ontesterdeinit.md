OnTesterDeinit



[MQL5 Reference](index.md)  /  [Event Handling](event_handlers.md) / OnTesterDeinit

[![Previous](previous.png)](ontesterinit.md) 
[![Next](next.png)](ontesterpass.md)

OnTesterDeinit

The function is called in EAs when the [TesterDeinit](event_fire.md#testerdeinit) event occurs after EA optimization.

```
void  OnTesterDeinit(void);
```

Return Value

No return value

Note

The [TesterDeinit](event_fire.md#testerdeinit) event is generated after the end of EA optimization in the strategy tester.

An EA having OnTesterDeInit() or OnTesterPass() event handler is automatically downloaded on a separate terminal chart during the optimization start. It has the symbol and the period that have been specified in the tester. The function is designed for the final processing of all [optimization results](optimization_frames.md).

Keep in mind that optimization frames sent by test agents using the [FrameAdd()](frameadd.md) function may come in bundles and take time to deliver. Therefore, not all frames, as well as [TesterPass](event_fire.md#testerpass) events, may arrive and be processed in [OnTesterPass()](ontesterpass.md) before the end of optimization. If you want to receive all belated frames in OnTesterDeinit(), place the code block using the [FrameNext()](framenext.md) function.

See also

[Testing trading strategies](testing.md), [Working with optimization results](optimization_frames.md), [TesterStatistics](testerstatistics.md), [OnTesterInit](ontesterinit.md), [OnTesterPass](ontesterpass.md), [ParameterGetRange](parametergetrange.md), [ParameterSetRange](parametersetrange.md)