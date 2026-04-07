CChartObjectText



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md) / CChartObjectText

[![Previous](previous.png)](obj_controls.md) 
[![Next](next.png)](cchartobjecttextcreate.md)

CChartObjectText

CChartObjectText is a class for simplified access to "Text" graphical object properties.

Description

CChartObjectText class provides access to "Text" object properties.

Declaration

```
   class CChartObjectText : public CChartObject
```

Title

```
   #include <ChartObjects\ChartObjectsTxtControls.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            CChartObjectText  Direct descendants  [CChartObjectLabel](cchartobjectlabel.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjecttextcreate.md) | Creates "Text" graphical object |
| Properties |  |
| [Angle](cchartobjecttextangle.md) | Gets/sets "Angle" property |
| [Font](cchartobjecttextfont.md) | Gets/sets "Font" property |
| [FontSize](cchartobjecttextfontsize.md) | Gets/sets "FontSize" property |
| [Anchor](cchartobjecttextanchor.md) | Gets/sets "Anchor" property |
| Input/output |  |
| virtual [Save](cchartobjecttextsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjecttextload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjecttexttype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |

Derived classes:

* [CChartObjectLabel](cchartobjectlabel.md)

See also

[Object types](enum_object.md), [Object properties](enum_object_property.md), [Methods of object binding](enum_anchorpoint.md), [Graphic objects](objects.md)