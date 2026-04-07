BufferResize



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CSeries](cseries.md) / BufferResize

[![Previous](previous.png)](cseriesbuffersize.md) 
[![Next](next.png)](cseriesrefresh.md)

BufferResize

Sets buffer size of timeseries or indicator.

```
virtual bool  BufferResize(
   const int  size      // size
   )
```

Parameters

size

[in]  New size of the buffers.

Return Value

true successful, otherwise - false.

Note

All the timeseries or indicator buffers have the same size.