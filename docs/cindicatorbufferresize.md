BufferResize



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md)  /  [CIndicator](cindicator.md) / BufferResize

[![Previous](previous.png)](cindicatorcreate.md) 
[![Next](next.png)](cindicatorbarscalculated.md)

BufferResize

Sets the sizes of the indicator buffers.

```
virtual bool  BufferResize(
   const int  size      // size
   )
```

Parameters

size

[in]  New buffer size.

Return Value

true successful, otherwise - false.

Note

All the indicator buffers have the same size.