Window



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [CChartObject](cchartobject.md) / Window

[![Previous](previous.png)](cchartobjectchartid.md) 
[![Next](next.png)](cchartobjectname.md)

Window

Gets the index of the chart window where the graphical object is located.

```
int  Window() const
```

Return Value

The number of the chart window where the graphical object is located (0 - main window). If there is no bound object, it returns -1.

Example:

```
//--- example for CChartObject::Window 
#include <ChartObjects\ChartObject.mqh> 
//--- 
void OnStart() 
  { 
   CChartObject object; 
   //--- get window of chart object  
   int window=object.Window(); 
  }
```