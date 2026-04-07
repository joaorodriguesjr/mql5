CChartObjectSubChart



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md) / CChartObjectSubChart

[![Previous](previous.png)](cchartobjectbuttontype.md) 
[![Next](next.png)](cchartobjectsubchartcreate.md)

CChartObjectSubChart

CChartObjectSubChart is a class for simplified access to "Chart" graphical object properties.

Description

CChartObjectSubChart class provides access to "Chart" object properties.

Declaration

```
   class CChartObjectSubChart : public CChartObject
```

Title

```
   #include <ChartObjects\ChartObjectSubChart.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            CChartObjectSubChart |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjectsubchartcreate.md) | Creates "Chart" graphical object |
| Properties |  |
| [X\_Distance](cchartobjectsubchartx_distance.md) | Gets/sets "X\_Distance" property |
| [Y\_Distance](cchartobjectsubcharty_distance.md) | Gets/sets "Y\_Distance" property |
| [Corner](cchartobjectsubchartcorner.md) | Gets/sets "Corner" property |
| [X\_Size](cchartobjectsubchartx_size.md) | Gets/sets "X\_Size" property |
| [Y\_Size](cchartobjectsubcharty_size.md) | Gets/sets "Y\_Size" property |
| [Symbol](cchartobjectsubchartsymbol.md) | Gets/sets "Symbol" property |
| [Period](cchartobjectsubchartperiod.md) | Gets/sets "Period" property |
| [Scale](cchartobjectsubchartscale.md) | Gets/sets "Scale" property |
| [DateScale](cchartobjectsubchartdatescale.md) | Gets/sets "Show date scale" property |
| [PriceScale](cchartobjectsubchartpricescale.md) | Gets/sets "Show price scale" property |
| [Time](cchartobjectsubcharttime.md) | "Stub" for time coordinate change |
| [Price](cchartobjectsubchartprice.md) | "Stub" for price coordinate change |
| Input/output |  |
| virtual [Save](cchartobjectsubchartsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjectsubchartload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjectsubcharttype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |

See also

[Object types](enum_object.md), [Object properties](enum_object_property.md), [Chart angle](enum_basecorner.md), [Graphic objects](objects.md)