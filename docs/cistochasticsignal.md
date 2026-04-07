Signal



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Oscillators](oscillatorindicators.md)  /  [CiStochastic](cistochastic.md) / Signal

[![Previous](previous.png)](cistochasticmain.md) 
[![Next](next.png)](cistochastictype.md)

Signal

Returns the buffer element of the signal line by the specified index.

```
double  Signal(
   int  index      // index
   )
```

Parameters

index

[in]  Buffer element index.

Return Value

The buffer element of the signal line by the specified index, or [EMPTY\_VALUE](otherconstants.md) if there is no correct data.