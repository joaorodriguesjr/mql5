CChartObjectBmpLabel



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md) / CChartObjectBmpLabel

[![Previous](previous.png)](cchartobjectbitmaptype.md) 
[![Next](next.png)](cchartobjectbmplabelcreate.md)

CChartObjectBmpLabel

CChartObjectBmpLabel is a class for simplified access to "Bitmap Label" graphical object properties.

Description

CChartObjectBmpLabel class provides access to "Bitmap Label" object properties.

Declaration

```
   class CChartObjectBmpLabel : public CChartObject
```

Title

```
   #include <ChartObjects\ChartObjectsBmpControls.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            CChartObjectBmpLabel |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjectbmplabelcreate.md) | Creates "BmpLabel" graphical object |
| Properties |  |
| [X\_Distance](cchartobjectbmplabelx_distance.md) | Gets/sets "X\_Distance" property |
| [Y\_Distance](cchartobjectbmplabely_distance.md) | Gets/sets "Y\_Distance" property |
| [X\_Offset](cchartobjectbmplabelx_offset.md) | Gets/sets "X\_Offset" property |
| [Y\_Offset](cchartobjectbmplabely_offset.md) | Gets/sets "Y\_Offset" property |
| [Corner](cchartobjectbmplabelcorner.md) | Gets/sets "Corner" property |
| [X\_Size](cchartobjectbmplabelx_size.md) | Gets/sets "X\_Size" property |
| [Y\_Size](cchartobjectbmplabely_size.md) | Gets/sets "Y\_Size" property |
| [BmpFileOn](cchartobjectbmplabelbmpfileon.md) | Gets/sets "BmpFileOn" property for button pressed state (On) |
| [BmpFileOff](cchartobjectbmplabelbmpfileoff.md) | Gets/sets "BmpFileOff" property for button depressed state (Off) |
| [State](cchartobjectbmplabelstate.md) | Gets/sets "Button State" property (Pressed/Depressed) |
| [Time](cchartobjectbmplabeltime.md) | "Stub" for time coordinate change |
| [Price](cchartobjectbmplabelprice.md) | "Stub" for price coordinate change |
| Input/output |  |
| virtual [Save](cchartobjectbmplabelsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjectbmplabelload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjectbmplabeltype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |

See also

[Object types](enum_object.md), [Object properties](enum_object_property.md), [Chart angle](enum_basecorner.md), [Graphic objects](objects.md)