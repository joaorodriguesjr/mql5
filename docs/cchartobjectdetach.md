Detach



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [CChartObject](cchartobject.md) / Detach

[![Previous](previous.png)](cchartobjectdelete.md) 
[![Next](next.png)](cchartobjectshiftobject.md)

Detach

Detaches the graphical object.

```
void  Detach()
```

Return Value

None.

Example:

```
//--- example for CChartObject::Detach
#include <ChartObjects\ChartObject.mqh>
//---
void OnStart()
  {
   CChartObject object;
   //--- detach chart object 
   object.Detach();
  }
```