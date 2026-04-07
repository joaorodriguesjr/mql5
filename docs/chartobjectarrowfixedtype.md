Type



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Arrow Objects](obj_arrows.md)  /  [Arrows with fixed code](arrowclassesfixedcode.md) / Type

[![Previous](previous.png)](chartobjectarrowfixedarrowcode.md) 
[![Next](next.png)](obj_controls.md)

Type

Returns graphical object type identifier

```
virtual int  Type() const
```

Return Value

Object type identifier:

CChartObjectArrowCheck - OBJ\_ARROW\_CHECK,

CChartObjectArrowDown - OBJ\_ARROW\_DOWN,

CChartObjectArrowUp - OBJ\_ARROW\_UP,

CChartObjectArrowStop - OBJ\_ARROW\_STOP,

CChartObjectArrowThumbDown - OBJ\_ARROW\_THUMB\_DOWN,

CChartObjectArrowThumbUp - OBJ\_ARROW\_THUMB\_UP,

CChartObjectArrowLeftPrice - OBJ\_ARROW\_LEFT\_PRICE,

CChartObjectArrowRightPrice - OBJ\_ARROW\_RIGHT\_PRICE.

Example:

```
//--- example for CChartObjectArrowCheck::Type  
//--- example for CChartObjectArrowDown::Type  
//--- example for CChartObjectArrowUp::Type  
//--- example for CChartObjectArrowStop::Type   
//--- example for CChartObjectArrowThumbDown::Type   
//--- example for CChartObjectArrowThumbUp::Type   
//--- example for CChartObjectArrowLeftPrice::Type   
//--- example for CChartObjectArrowRightPrice::Type   
#include <ChartObjects\ChartObjectsArrows.mqh>  
//---  
void OnStart()  
  {  
//--- for example, take CChartObjectArrowCheck  
   CChartObjectArrowCheck arrow;  
//--- get arrow type  
   int type=arrow.Type();  
  }
```