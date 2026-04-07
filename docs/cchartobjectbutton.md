CChartObjectButton



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md)  /  [Control Objects](obj_controls.md) / CChartObjectButton

[![Previous](previous.png)](cchartobjectedittype.md) 
[![Next](next.png)](cchartobjectbuttonstate.md)

CChartObjectButton

CChartObjectButton is a class for simplified access to "Button" graphical object properties.

Description

CChartObjectButton class provides access to "Button" object properties.

Declaration

```
   class CChartObjectButton : public CChartObjectEdit
```

Title

```
   #include <ChartObjects\ChartObjectsTxtControls.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CChartObject](cchartobject.md)            [CChartObjectText](cchartobjecttext.md)                [CChartObjectLabel](cchartobjectlabel.md)                    [CChartObjectEdit](cchartobjectedit.md)                        CChartObjectButton  Direct descendants  CChartObjectPanel |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cchartobjecteditcreate.md) | Inherited form [CChartObjectEdit](cchartobjectedit.md) class |
| Properties |  |
| [State](cchartobjectbuttonstate.md) | Gets/sets button state (Pressed/Depressed) |
| Input/output |  |
| virtual [Save](cchartobjectbuttonsave.md) | Virtual method for writing to file |
| virtual [Load](cchartobjectbuttonload.md) | Virtual method for reading from file |
| virtual [Type](cchartobjectbuttontype.md) | Virtual method of identification |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CChartObject  [ChartId](cchartobjectchartid.md), [Window](cchartobjectwindow.md), [Name](cchartobjectname.md), [Name](cchartobjectname.md), [NumPoints](cchartobjectnumpoints.md), [Attach](cchartobjectattach.md), [SetPoint](cchartobjectsetpoint.md), [Delete](cchartobjectdelete.md), [Detach](cchartobjectdetach.md), [Time](cchartobjecttime.md), [Time](cchartobjecttime.md), [Price](cchartobjectprice.md), [Price](cchartobjectprice.md), [Color](cchartobjectcolor.md), [Color](cchartobjectcolor.md), [Style](cchartobjectstyle.md), [Style](cchartobjectstyle.md), [Width](cchartobjectwidth.md), [Width](cchartobjectwidth.md), [Background](cchartobjectbackground.md), [Background](cchartobjectbackground.md), Fill, Fill, [Z\_Order](cchartobjectz_order.md), [Z\_Order](cchartobjectz_order.md), [Selected](cchartobjectselected.md), [Selected](cchartobjectselected.md), [Selectable](cchartobjectselectable.md), [Selectable](cchartobjectselectable.md), [Description](cchartobjectdescription.md), [Description](cchartobjectdescription.md), [Tooltip](cchartobjecttooltip.md), [Tooltip](cchartobjecttooltip.md), [Timeframes](cchartobjecttimeframes.md), [Timeframes](cchartobjecttimeframes.md), [CreateTime](cchartobjectcreatetime.md), [LevelsCount](cchartobjectlevelscount.md), [LevelsCount](cchartobjectlevelscount.md), [LevelColor](cchartobjectlevelcolor.md), [LevelColor](cchartobjectlevelcolor.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelStyle](cchartobjectlevelstyle.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelWidth](cchartobjectlevelwidth.md), [LevelValue](cchartobjectlevelvalue.md), [LevelValue](cchartobjectlevelvalue.md), [LevelDescription](cchartobjectleveldescription.md), [LevelDescription](cchartobjectleveldescription.md), [GetInteger](cchartobjectgetinteger.md), [GetInteger](cchartobjectgetinteger.md), [SetInteger](cchartobjectsetinteger.md), [SetInteger](cchartobjectsetinteger.md), [GetDouble](cchartobjectgetdouble.md), [GetDouble](cchartobjectgetdouble.md), [SetDouble](cchartobjectsetdouble.md), [SetDouble](cchartobjectsetdouble.md), [GetString](cchartobjectgetstring.md), [GetString](cchartobjectgetstring.md), [SetString](cchartobjectsetstring.md), [SetString](cchartobjectsetstring.md), [ShiftObject](cchartobjectshiftobject.md), [ShiftPoint](cchartobjectshiftpoint.md) |
| Methods inherited from class CChartObjectText  [Angle](cchartobjecttextangle.md), [Angle](cchartobjecttextangle.md), [Font](cchartobjecttextfont.md), [Font](cchartobjecttextfont.md), [FontSize](cchartobjecttextfontsize.md), [FontSize](cchartobjecttextfontsize.md), [Anchor](cchartobjecttextanchor.md), [Anchor](cchartobjecttextanchor.md), [Create](cchartobjecttextcreate.md) |
| Methods inherited from class CChartObjectLabel  [X\_Distance](cchartobjectlabelx_distance.md), [X\_Distance](cchartobjectlabelx_distance.md), [Y\_Distance](cchartobjectlabely_distance.md), [Y\_Distance](cchartobjectlabely_distance.md), [X\_Size](cchartobjectlabelx_size.md), [Y\_Size](cchartobjectlabely_size.md), [Corner](cchartobjectlabelcorner.md), [Corner](cchartobjectlabelcorner.md), [Time](cchartobjectlabeltime.md), [Price](cchartobjectlabelprice.md), [Create](cchartobjectlabelcreate.md) |
| Methods inherited from class CChartObjectEdit  [X\_Size](cchartobjecteditx_size.md), [Y\_Size](cchartobjectedity_size.md), [BackColor](cchartobjecteditbackcolor.md), [BackColor](cchartobjecteditbackcolor.md), [BorderColor](cchartobjecteditbordercolor.md), [BorderColor](cchartobjecteditbordercolor.md), ReadOnly, ReadOnly, [TextAlign](cchartobjectedittextalign.md), [TextAlign](cchartobjectedittextalign.md), [Angle](cchartobjecteditangle.md), [Create](cchartobjecteditcreate.md) |

See also

[Object types](enum_object.md), [Object properties](enum_object_property.md), [Chart angle](enum_basecorner.md), [Methods of object binding](enum_anchorpoint.md), [Graphic objects](objects.md)