CChartObjectGannGrid



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Gann Tools](obj_gann.md) / CChartObjectGannGrid

[![Previous](previous.png)](cchartobjectgannfantype.md) 
[![Next](next.png)](cchartobjectganngridcreate.md)

CChartObjectGannGrid

CChartObjectGannGrid is a class for simplified access to "Gann Grid" graphical object properties.

Description

CChartObjectGannGrid class provides access to "Gann Grid" object properties.

Declaration

```
   class CChartObjectGannGrid : public CChartObjectTrend
```

Title

```
   #include <ChartObjects\ChartObjectsGann.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            [CChartObjectTrend](cchartobjecttrend.md)                CChartObjectGannGrid |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjectganngridcreate.md) | Creates "Gann Grid" graphical object |
| Properties |  |
| [PipsPerBar](cchartobjectganngridpipsperbar.md) | Gets/sets "Pips per bar" property |
| [Downtrend](cchartobjectganngriddowntrend.md) | Gets/sets "Downtrend" property |
| Input/output |  |
| virtual [Save](cchartobjectganngridsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjectganngridload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjectganngridtype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |
| Methods inherited from class CChartObjectTrend  [RayLeft](cchartobjecttrendrayleft.md), [RayLeft](cchartobjecttrendrayleft.md), [RayRight](cchartobjecttrendrayright.md), [RayRight](cchartobjecttrendrayright.md), [Create](cchartobjecttrendcreate.md) |

See also

[Object types](enum_object.md), [Graphic objects](objects.md)