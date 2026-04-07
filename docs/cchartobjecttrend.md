CChartObjectTrend



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Line Objects](obj_lines.md) / CChartObjectTrend

[![Previous](previous.png)](cchartobjecthlinetype.md) 
[![Next](next.png)](cchartobjecttrendcreate.md)

CChartObjectTrend

CChartObjectTrend is a class for simplified access to "Trend Line" graphical object properties.

Description

CChartObjectTrend class provides access to "Trend Line" object properties.

Declaration

```
   class CChartObjectTrend : public CChartObject
```

Title

```
   #include <ChartObjects\ChartObjectsLines.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            CChartObjectTrend  Direct descendants  [CChartObjectChannel](cchartobjectchannel.md), [CChartObjectFibo](cchartobjectfibo.md), [CChartObjectFiboChannel](cchartobjectfibochannel.md), [CChartObjectFiboExpansion](cchartobjectfiboexpansion.md), [CChartObjectGannFan](cchartobjectgannfan.md), [CChartObjectGannGrid](cchartobjectganngrid.md), [CChartObjectPitchfork](cchartobjectpitchfork.md), [CChartObjectRegression](cchartobjectregression.md), [CChartObjectStdDevChannel](cchartobjectstddevchannel.md), [CChartObjectTrendByAngle](cchartobjecttrendbyangle.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjecttrendcreate.md) | Creates "Trend Line" graphical object |
| Properties |  |
| [RayLeft](cchartobjecttrendrayleft.md) | Gets/sets "Ray Left" property |
| [RayRight](cchartobjecttrendrayright.md) | Gets/sets "Ray Right" property |
| Input/output |  |
| virtual [Save](cchartobjecttrendsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjecttrendload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjecttrendtype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |

 

See also

[Object types](enum_object.md), [Graphic objects](objects.md)