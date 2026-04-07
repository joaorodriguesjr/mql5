CheckState



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [COrderInfo](corderinfo.md) / CheckState

[![Previous](previous.png)](corderinfostorestate.md) 
[![Next](next.png)](corderinfoselect.md)

CheckState

Checks the current parameters against the saved parameters.

```
bool  CheckState()
```

Return Value

true - if the order parameters have changed since the last call of the [StoreState()](corderinfostorestate.md) method, otherwise - false.