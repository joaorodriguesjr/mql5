CGraphic



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Scientific Charts](graphics.md) / CGraphic

[![Previous](previous.png)](ccurvevisible.md) 
[![Next](next.png)](cgraphiccreate.md)

CGraphic

CGraphic is a base class for creating custom charts.

Description

The CGraphic class provides numerous aspects of working with custom charts.

The class stores the main chart elements, sets their parameters and performs plotting.

Also, the class stores the curves for the chart and provides various display options.  

Declaration

```
   class CGraphic
```

Title

```
   #include <Graphics\Graphic.mqh>
```

Class methods

| Method | Description |
| --- | --- |
| [Create](cgraphiccreate.md) | Create a graphical resource bound to a chart object |
| [Destroy](cgraphicdestroy.md) | Remove a chart and destroy a graphical resource |
| [Update](cgraphicupdate.md) | Display implemented changes |
| [ChartObjectName](cgraphicchartobjectname.md) | Get the name of an object bound to a chart |
| [ResourceName](cgraphicresourcename.md) | Get the graphical resource name |
| [XAxis](cgraphicxaxis.md) | Get the pointer to the X axis |
| [YAxis](cgraphicyaxis.md) | Get the pointer to the Y axis |
| [GapSize](cgraphicgapsize.md) | Get/set the size of indents between the chart elements |
| [BackgroundColor](cgraphicbackgroundcolor.md) | Get/set a background color |
| [BackgroundMain](cgraphicbackgroundmain.md) | Get/set a chart header |
| [BackgroundMainSize](cgraphicbackgroundmainsize.md) | Get/set a sub-header font size |
| [BackgroundMainColor](cgraphicbackgroundmaincolor.md) | Get/set a chart header color |
| [BackgroundSub](cgraphicbackgroundsub.md) | Get/set a sub-header |
| [BackgroundSubSize](cgraphicbackgroundsubsize.md) | Get/set a sub-header font size |
| [BackgroundSubColor](cgraphicbackgroundsubcolor.md) | Get/set a chart sub-header color |
| [GridLineColor](cgraphicgridlinecolor.md) | Get/set a grid line color |
| [GridBackgroundColor](cgraphicgridbackgroundcolor.md) | Get/set a grid background color |
| [GridCircleRadius](cgraphicgridvcircleradius.md) | Get/set the dot radius in the grid nodes |
| [GridCircleColor](cgraphicgridcirclecolor.md) | Get/set the dot color in the grid nodes |
| [GridHasCircle](cgraphicgridhascircle.md) | Get/set the dot plotting flag in the grid nodes |
| [GridAxisLineColor](cgraphicgridaxislinecolor.md) | Get the value of a real chart axes color. |
| [HistoryNameWidth](cgraphichistorynamewidth.md) | Get/set the maximum allowed length for displaying a curve name |
| [HistoryNameSize](cgraphichistorynamesize.md) | Get/set the font size of a curve name |
| [HistorySymbolSize](cgraphichistorysymbolsize.md) | Get/set a size of notational convention symbols |
| [TextAdd](cgraphictextadd.md) | Add a text to the chart |
| [LineAdd](cgraphiclineadd.md) | Add a line to the chart |
| [CurveAdd](cgraphiccurveadd.md) | Create and add a curve to the chart |
| [CurvePlot](cgraphiccurveplot.md) | Plot a previously created curve by index |
| [CurvePlotAll](cgraphiccurveplotall.md) | Plot all previously created curves |
| [CurveGetByIndex](cgraphiccurvegetbyindex.md) | Get a curve by a specified index |
| [CurveGetByName](cgraphiccurvegetbyname.md) | Get a curve by a specified name |
| [CurveRemoveByIndex](cgraphiccurveremovebyindex.md) | Remove a curve by a specified index. |
| [CurveRemoveByName](cgraphiccurveremovebyname.md) | Remove a curve by a specified name. |
| [CurvesTotal](cgraphiccurvestotal.md) | Get the number of curves for the given chart. |
| [MarksToAxisAdd](cgraphicmarkstoaxisadd.md) | Add a scale mark to the chart axis |
| [MajorMarkSize](cgraphicmajormarksize.md) | Get/set the size of the scale's ticks on the chart axis |
| [FontSet](cgraphicfontset.md) | Set the current font parameters |
| [FontGet](cgraphicfontget.md) | Get the current font parameters |
| [Attach](cgraphicattach.md) | Get/set a graphical resource and bind it to the CGraphic class instance |
| [CalculateMaxMinValues](cgraphiccalculatemaxminvalues.md) | Calculate (re-calculate) minimum and maximum chart values on both axes. |
| [Height](cgraphicheight.md) | Get a chart height in pixels. |
| [IndentDown](cgraphicindentdown.md) | Get/set a chart indent from the lower border. |
| [IndentLeft](cgraphicindentleft.md) | Get/set a chart indent from the left border. |
| [IndentRight](cgraphicindentright.md) | Get/set a chart indent from the right border. |
| [IndentUp](cgraphicindentup.md) | Get/set a chart indent from the upper border. |
| [Redraw](cgraphicredraw.md) | Redraw the chart. |
| [ResetParameters](cgraphicresetparameters.md) | Reset the chart redrawing parameters. |
| [ScaleX](cgraphicscalex.md) | Scale the value by X axis. |
| [ScaleY](cgraphicscaley.md) | Scale the value by Y axis. |
| [SetDefaultParameters](cgraphicsetdefaultparameters.md) | Set the chart parameters to default values. |
| [Width](cgraphicwidth.md) | Get the chart width in pixels. |