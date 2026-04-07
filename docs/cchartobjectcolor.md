Color



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [CChartObject](cchartobject.md) / Color

[![Previous](previous.png)](cchartobjectprice.md) 
[![Next](next.png)](cchartobjectstyle.md)

Color (Get Method)

Gets the line color of the graphical object.

```
color  Color() const
```

Return Value

Line color of the graphical object attached to the class instance. If there is no object attached, it returns CLR\_NONE.

Color (Set Method)

Sets the line color of the graphical object.

```
bool  Color(
   color  new_color      // new color
   )
```

Parameters

new\_color

[in]  New value of a graphical object line color.

Return Value

true - success, false - cannot change the color.

Example:

```
//--- example for CChartObject::Color 
#include <ChartObjects\ChartObject.mqh> 
//--- 
void OnStart() 
  { 
   CChartObject object; 
   //--- get color of chart object  
   color object_color=object.Color(); 
   if(object_color!=clrRed) 
     { 
     //--- set color of chart object 
     object.Color(clrRed); 
     } 
  }
```