CChartObjectLabel



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md) / CChartObjectLabel

[![Previous](previous.png)](cchartobjecttexttype.md) 
[![Next](next.png)](cchartobjectlabelcreate.md)

CChartObjectLabel

CChartObjectLabel is a class for simplified access to "Label" graphical object properties.

Description

CChartObjectLabel class provides access to "Label" object properties.

Declaration

```
   class CChartObjectLabel : public CChartObjectText
```

Title

```
   #include <ChartObjects\ChartObjectsTxtControls.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            [CChartObjectText](cchartobjecttext.md)                CChartObjectLabel  Direct descendants  [CChartObjectEdit](cchartobjectedit.md), [CChartObjectRectLabel](cchartobjectrectlabel.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjectlabelcreate.md) | Creates "Label" graphical object |
| Properties |  |
| [X\_Distance](cchartobjectlabelx_distance.md) | Gets/sets "X\_Distance" property |
| [Y\_Distance](cchartobjectlabely_distance.md) | Gets/sets "Y\_Distance" property |
| [X\_Size](cchartobjectlabelx_size.md) | Gets/sets "X\_Size" property |
| [Y\_Size](cchartobjectlabely_size.md) | Gets/sets "Y\_Size" property |
| [Corner](cchartobjectlabelcorner.md) | Gets/sets "Corner" property |
| [Time](cchartobjectlabeltime.md) | "Stub" for time coordinate change |
| [Price](cchartobjectlabelprice.md) | "Stub" for price coordinate change |
| Input/output |  |
| virtual [Save](cchartobjectlabelsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjectlabelload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjectlabeltype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |
| Methods inherited from class CChartObjectText  [Angle](cchartobjecttextangle.md), [Angle](cchartobjecttextangle.md), [Font](cchartobjecttextfont.md), [Font](cchartobjecttextfont.md), [FontSize](cchartobjecttextfontsize.md), [FontSize](cchartobjecttextfontsize.md), [Anchor](cchartobjecttextanchor.md), [Anchor](cchartobjecttextanchor.md), [Create](cchartobjecttextcreate.md) |

 

See also

[Object types](enum_object.md), [Object properties](enum_object_property.md), [Chart angle](enum_basecorner.md), [Methods of Object Binding](enum_anchorpoint.md), [Graphic objects](objects.md)