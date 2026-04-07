MarksToAxisAdd



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Scientific Charts](graphics.md)  /  [CGraphic](cgraphic.md) / MarksToAxisAdd

[![Previous](previous.png)](cgraphiccurvestotal.md) 
[![Next](next.png)](cgraphicmajormarksize.md)

MarksToAxisAdd

Add a scale mark (ticks) to the specified chart axis.

```
bool  MarksToAxisAdd(
   const double        &marks[],        // tick coordinates
   const int           mark_size,       // tick size
   ENUM_MARK_POSITION  position,        // tick location
   const int           dimension=0      // dimension
   )
```

Parameters

&marks[]

[in]  Tick coordinates

mark\_size

[in]  Tick size

position

[in]  Tick location

dimension=0

[in]  0 adding to X axis,

       1 adding to Y axis

Return Value

true - successful, otherwise - false.