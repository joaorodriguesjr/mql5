Type



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Arrow Objects](obj_arrows.md)  /  [CChartObjectArrow](cchartobjectarrow.md) / Type

[![Previous](previous.png)](cchartobjectarrowload.md) 
[![Next](next.png)](arrowclassesfixedcode.md)

Type

Returns graphical object type identifier.

```
virtual int  Type() const
```

Return Value

Object type identifier (for example, OBJ\_ARROW for [CChartObjectArrow](cchartobjectarrow.md))

Example:

```
//--- example for CChartObjectArrow::Type   
#include <ChartObjects\ChartObjectsArrows.mqh>   
//---   
void OnStart()   
  {   
   CChartObjectArrow arrow;   
   //--- get arrow type   
   int type=arrow.Type();   
  }
```