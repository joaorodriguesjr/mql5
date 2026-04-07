Type



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [CChartObject](cchartobject.md) / Type

[![Previous](previous.png)](cchartobjectload.md) 
[![Next](next.png)](obj_lines.md)

Type

Gets the graphical object type ID.

```
virtual int  Type() const
```

Return Value

Object type ID (0x8888 for [CChartObject](cchartobject.md)).

Example:

```
//--- example for CChartObject::Type   
#include <ChartObjects\ChartObject.mqh>   
//---   
void OnStart()   
  {   
   CChartObject object;
   //--- get object type   
   int type=object.Type();   
  }
```