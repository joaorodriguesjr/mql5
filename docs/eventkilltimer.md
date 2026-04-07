EventKillTimer



[MQL5 Reference](index.md)  /  [Working with Events](eventfunctions.md) / EventKillTimer

[![Previous](previous.png)](eventsettimer.md) 
[![Next](next.png)](eventchartcustom.md)

EventKillTimer

Specifies the client terminal that is necessary to stop the generation of events from [Timer](event_fire.md#timer).

```
void  EventKillTimer();
```

Return Value

No return value.

Note

Typically, this function must be called from a function [OnDeinit()](ondeinit.md), if the [EventSetTimer()](eventsettimer.md) function has been called from [OnInit()](oninit.md). This function can also be called form the class destructor, if the EventSetTimer() function has been called in the [constructor](classes.md#destructor) of this class.

Every Expert Advisor, as well as every indicator works with its own timer and receives events only from it. As soon as a mql5 program stops operating, the timer is destroyed forcibly if it was created but hasn't been disabled by the [EventKillTimer()](eventkilltimer.md) function