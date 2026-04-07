NumPoints



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [CChartObject](cchartobject.md) / NumPoints

[![Previous](previous.png)](cchartobjectname.md) 
[![Next](next.png)](cchartobjectattach.md)

NumPoints

Gets the number of anchor points of a graphical object.

```
int  NumPoints() const
```

Return Value

Number of points linking a graphical object attached to an instance of the class. If there is no attached object, it returns 0.

Example:

```
//--- example for CChartObject::NumPoints 
#include <ChartObjects\ChartObject.mqh> 
//--- 
void OnStart() 
  { 
   CChartObject object; 
   //--- get points count of chart object  
   int points=object.NumPoints(); 
  }
```