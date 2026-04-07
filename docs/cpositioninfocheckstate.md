CheckState



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CPositionInfo](cpositioninfo.md) / CheckState

[![Previous](previous.png)](cpositioninfostorestate.md) 
[![Next](next.png)](cdealinfo.md)

CheckState

Checks the current parameters against the saved parameters.

```
bool  CheckState()
```

Return Value

true - the position parameters have changed since the last call of the [StoreState()](cpositioninfostorestate.md) method, otherwise - false.