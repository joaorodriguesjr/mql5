OnTesterPass



[MQL5 Reference](index.md)  /  [Event Handling](event_handlers.md) / OnTesterPass

[![Previous](previous.png)](ontesterdeinit.md) 
[![Next](next.png)](marketinformation.md)

OnTesterPass

The function is called in EAs when the [TesterPass](event_fire.md#testerpass) event occurs for handling a new data frame during EA optimization.

```
void  OnTesterPass(void);
```

Return Value

No return value

Note

The [TesterPass](event_fire.md#testerpass) event is generated automatically when receiving a frame during an Expert Advisor optimization in the strategy tester.

An EA having OnTesterDeInit() or OnTesterPass() event handler is automatically downloaded on a separate terminal chart during the optimization start. It has the symbol and the period that have been specified in the tester. The function is meant for handling frames received from test agents during optimization. The frame containing test results should be sent from the [OnTester()](ontester.md) handler using the [FrameAdd()](frameadd.md) function.

Keep in mind that optimization frames sent by test agents using the [FrameAdd()](frameadd.md) function may come in bundles and take time to deliver. Therefore, not all frames, as well as [TesterPass](event_fire.md#testerpass) events, may arrive and be processed in [OnTesterPass()](ontesterpass.md) before the end of optimization. If you want to receive all belated frames in OnTesterDeinit(), place the code block using the [FrameNext()](framenext.md) function.

After completing OnTesterDeinit() optimization, it is possible to sort all received frames again using the [FrameFirst()](framefirst.md)/[FrameFilter](framefilter.md) and [FrameNext()](framenext.md) functions.

See also

[Testing trading strategies](testing.md), [Working with optimization results](optimization_frames.md), [OnTesterInit](ontesterinit.md), [OnTesterDeinit](ontesterdeinit.md), [FrameFirst](framefirst.md), [FrameFilter](framefilter.md), [FrameNext](framenext.md), [FrameInputs](frameinputs.md)