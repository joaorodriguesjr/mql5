Arrows with fixed code



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Arrow Objects](obj_arrows.md) / Arrows with fixed code

[![Previous](previous.png)](cchartobjectarrowtype.md) 
[![Next](next.png)](chartobjectarrowfixedcreate.md)

Arrows with fixed code

"Arrows with fixed code" are classes for simplified access to the properties of the following graphical objects:

| Class name | Arrow object name |
| --- | --- |
| CChartObjectArrowCheck | "Arrow Check" |
| CChartObjectArrowDown | "Arrow Down" |
| CChartObjectArrowUp | "Arrow Up" |
| CChartObjectArrowStop | "Arrow Stop" |
| CChartObjectArrowThumbDown | "Good" ("Thumbs up") |
| CChartObjectArrowThumbUp | "Bad" ("Thumbs down") |
| CChartObjectArrowLeftPrice | "Left price" arrow |
| CChartObjectArrowRightPrice | "Right price" arrow |

Description

"Arrows with fixed code" classes provide access to the object properties.

Declarations

```
   class CChartObjectArrowCheck      : public CChartObjectArrow;
   class CChartObjectArrowDown       : public CChartObjectArrow;
   class CChartObjectArrowUp         : public CChartObjectArrow;
   class CChartObjectArrowStop       : public CChartObjectArrow;
   class CChartObjectArrowThumbDown  : public CChartObjectArrow;
   class CChartObjectArrowThumbUp    : public CChartObjectArrow;
   class CChartObjectArrowLeftPrice  : public CChartObjectArrow;
   class CChartObjectArrowRightPrice : public CChartObjectArrow;
```

Title

```
   <ChartObjects\ChartObjectsArrows.mqh>
```

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](chartobjectarrowfixedcreate.md) | Creates the graphical object matching the class |
| Properties |  |
| [ArrowCode](chartobjectarrowfixedarrowcode.md) | "Stub" for symbol code change method |
| Input/output |  |
| virtual [Type](chartobjectarrowfixedtype.md) | Virtual method of identification |

See also

[Object types](enum_object.md), [Methods of object binding](enum_anchorpoint.md), [Graphic objects](objects.md)