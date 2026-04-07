CChartObject



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Graphic Objects](chart_object_classes.md) / CChartObject

[![Previous](previous.png)](chart_object_classes.md) 
[![Next](next.png)](cchartobjectchartid.md)

CChartObject

CChartObject is a base class for the classes of chart graphical objects of the Standard MQL5 library.

Description

CChartObject class provides the simplified access to MQL5 API functions for all of its descendants.

Declaration

```
   class CChartObject : public CObject
```

Title

```
   #include <ChartObjects\ChartObject.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CChartObject  Direct descendants  [CChartObjectArrow](cchartobjectarrow.md), [CChartObjectBitmap](cchartobjectbitmap.md), [CChartObjectBmpLabel](cchartobjectbmplabel.md), [CChartObjectCycles](cchartobjectcycles.md), [CChartObjectElliottWave3](cchartobjectelliottwave3.md), [CChartObjectEllipse](cchartobjectellipse.md), [CChartObjectFiboArc](cchartobjectfiboarc.md), [CChartObjectFiboFan](cchartobjectfibofan.md), [CChartObjectFiboTimes](cchartobjectfibotimes.md), [CChartObjectHLine](cchartobjecthline.md), [CChartObjectRectangle](cchartobjectrectangle.md), [CChartObjectSubChart](cchartobjectsubchart.md), [CChartObjectText](cchartobjecttext.md), [CChartObjectTrend](cchartobjecttrend.md), [CChartObjectTriangle](cchartobjecttriangle.md), [CChartObjectVLine](cchartobjectvline.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [ChartId](cchartobjectchartid.md) | Gets the ID of the chart a graphical object belongs to |
| [Window](cchartobjectwindow.md) | Gets the number of a chart window where a graphical object is located |
| [Name](cchartobjectname.md) | Gets/sets the name of a graphical object |
| [NumPoints](cchartobjectnumpoints.md) | Gets the number of anchor points |
| Assign |  |
| [Attach](cchartobjectattach.md) | Binds a chart graphical object |
| [SetPoint](cchartobjectsetpoint.md) | Sets the anchor point parameters |
| Delete |  |
| [Delete](cchartobjectdelete.md) | Deletes a chart graphical object |
| [Detach](cchartobjectdetach.md) | Detaches a chart graphical object |
| Shift |  |
| [ShiftObject](cchartobjectshiftobject.md) | The relative object shift |
| [ShiftPoint](cchartobjectshiftpoint.md) | The relative object point shift |
| Object properties |  |
| [Time](cchartobjecttime.md) | Gets/sets the time coordinates of an object point |
| [Price](cchartobjectprice.md) | Gets/sets the price coordinate of an object point |
| [Color](cchartobjectcolor.md) | Gets/sets the color of the object |
| [Style](cchartobjectstyle.md) | Gets/sets the object line style |
| [Width](cchartobjectwidth.md) | Gets/sets the object line width |
| [BackGround](cchartobjectbackground.md) | Gets/sets the flag of drawing an object in the background |
| [Selected](cchartobjectselected.md) | Gets/sets the "selected" flag of a graphical object |
| [Selectable](cchartobjectselectable.md) | Gets/sets the selectable object flag |
| [Description](cchartobjectdescription.md) | Gets/sets the text of the object |
| [Tooltip](cchartobjecttooltip.md) | Gets/sets the tooltip of the object |
| [Timeframes](cchartobjecttimeframes.md) | Gets/sets the mask of the object visibility flags |
| [Z\_Order](cchartobjectz_order.md) | Gets/sets the graphical object priority for receiving an event of mouse clicking on a chart |
| [CreateTime](cchartobjectcreatetime.md) | Gets the time of the object creation |
| Object level properties |  |
| [LevelsCount](cchartobjectlevelscount.md) | Gets/sets the number of object levels |
| [LevelColor](cchartobjectlevelcolor.md) | Gets/sets the level line color |
| [LevelStyle](cchartobjectlevelstyle.md) | Gets/sets the level line style |
| [LevelWidth](cchartobjectlevelwidth.md) | Gets/sets the level line width |
| [LevelValue](cchartobjectlevelvalue.md) | Gets/sets the level |
| [LevelDescription](cchartobjectleveldescription.md) | Gets/sets the level text |
| Access to API MQL5 functions |  |
| [GetInteger](cchartobjectgetinteger.md) | Gets the value of the object property |
| [SetInteger](cchartobjectsetinteger.md) | Sets the value of the object property |
| [GetDouble](cchartobjectgetdouble.md) | Gets the value of the object property |
| [SetDouble](cchartobjectsetdouble.md) | Sets the value of the object property |
| [GetString](cchartobjectgetstring.md) | Gets the value of the object property |
| [SetString](cchartobjectsetstring.md) | Sets the value of the object property |
| Input/Output |  |
| virtual [Save](cchartobjectsave.md) | Virtual method of writing to a file |
| virtual [Load](cchartobjectload.md) | Virtual method of reading from a file |
| virtual [Type](cchartobjecttype.md) | Virtual method of identification |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |