Price Charts



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md) / Price Charts

[![Previous](previous.png)](ccanvas3dviewupdirectionset.md) 
[![Next](next.png)](cchartchartid.md)

CChart

CChart is a class for simplified access to "Chart" graphic object properties.

Description

CChart class provides access to "Chart" object properties.

Declaration

```
   class CChart : public CObject
```

Title

```
   #include <Charts\Chart.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CChart |

Class Methods by Groups

| Access to protected data |  |
| --- | --- |
| [ChartID](cchartchartid.md) | Gets identifier of the chart |
| General properties |  |
| [Mode](cchartmode.md) | Gets/sets the value of "Mode" property (bars, candles, or line) |
| [Foreground](cchartforeground.md) | Gets/sets the value of "Foreground" property |
| [Shift](cchartshift.md) | Gets/sets the value of "Shift" property |
| [ShiftSize](cchartshiftsize.md) | Gets/sets the value of "ShiftSize" property (in percents) |
| [AutoScroll](cchartautoscroll.md) | Gets/sets the value of "AutoScroll" property |
| [Scale](cchartscale.md) | Gets/sets the value of "Scale" property |
| [ScaleFix](cchartscalefix.md) | Gets/sets the value of "ScaleFix" property (fixed chart scale or not) |
| [ScaleFix\_11](cchartscalefix_11.md) | Gets/sets the value of "ScaleFix\_11" property (chart scale is 1:1, or not) |
| [FixedMax](cchartfixedmax.md) | Gets/sets the value of "FixedMax" property (fixed maximal price) |
| [FixedMin](cchartfixedmin.md) | Gets/sets the value of "FixedMin" property (fixed minimal price) |
| [ScalePPB](cchartscaleppb.md) | Gets/sets the value of "ScalePPB" property (scale is "point per bar" or not) |
| [PointsPerBar](cchartpointsperbar.md) | Gets/sets the value of "PointsPerBar" property (in points per bar) |
| Show properties |  |
| [ShowOHLC](cchartshowohlc.md) | Gets/sets the value of "ShowOHLC" property |
| [ShowLineBid](cchartshowlinebid.md) | Gets/sets the value of "ShowLineBid" property |
| [ShowLineAsk](cchartshowlineask.md) | Gets/sets the value of "ShowLineAsk" property |
| [ShowLastLine](cchartshowlastline.md) | Gets/sets the value of "ShowLastLine" property |
| [ShowPeriodSep](cchartshowperiodsep.md) | Gets/sets the value of "ShowPeriodSep" property (show period separators) |
| [ShowGrid](cchartshowgrid.md) | Gets/sets the value of "ShowGrid" property |
| [ShowVolumes](cchartshowvolumes.md) | Gets/sets the value of "ShowVolumes" property (color for volumes and levels of opened positions) |
| [ShowObjectDescr](cchartshowobjectdescr.md) | Gets/sets the value of "ShowObjectDescr" property (show description for graphic objects) |
| [ShowDateScale](cchartshowdatescale.md) | Sets the value of "ShowDateScale" property (date scale of the chart) |
| [ShowPriceScale](cchartshowpricescale.md) | Sets the value of "ShowPriceScale" property (price scale of the chart) |
| Color properties |  |
| [ColorBackground](cchartcolorbackground.md) | Gets/sets the value of "ColorBackground" property (background color of the chart) |
| [ColorForeground](cchartcolorforeground.md) | Gets/sets the value of "ColorForeground" property (color of axes, scale and OHLC strings of the chart) |
| [ColorGrid](cchartcolorgrid.md) | Gets/sets the value of "ColorGrid" property (color of the grid) |
| [ColorBarUp](cchartcolorbarup.md) | Gets/sets the value of "ColorBarUp" property (color for bull bars, their shadow and candle body outlines) |
| [ColorBarDown](cchartcolorbardown.md) | Gets/sets the value of "ColorBarDown" property (color for bear bars, their shadow and candle body outlines) |
| [ColorCandleBull](cchartcolorcandlebull.md) | Gets/sets the value of "ColorCandleBull" property (body color of the bull candle) |
| [ColorCandleBear](cchartcolorcandlebear.md) | Gets/sets the value of "ColorCandleBear" property (body color of the bear candle) |
| [ColorChartLine](cchartcolorchartline.md) | Gets/sets the value of "ColorChartLine" property (color for line chart and Doji candles) |
| [ColorVolumes](cchartcolorvolumes.md) | Gets/sets the value of "ColorVolumes" property (color for volumes and levels of opened positions) |
| [ColorLineBid](cchartcolorlinebid.md) | Gets/sets the value of "ColorLineBid" property (color of Bid line) |
| [ColorLineAsk](cchartcolorlineask.md) | Gets/sets the value of "ColorLineAsk" property (color of Ask line) |
| [ColorLineLast](cchartcolorlinelast.md) | Gets/sets the value of "ColorLineLast" property (color of the last deal price line) |
| [ColorStopLevels](cchartcolorstoplevels.md) | Gets/sets the value of "ColorStopLevels" property (color of the SL and TP levels) |
| Read only properties |  |
| [VisibleBars](cchartvisiblebars.md) | Gets total number of visible chart bars |
| [WindowsTotal](cchartwindowstotal.md) | Gets total number of chart windows, including the chart indicator subwindows |
| [WindowIsVisible](cchartwindowisvisible.md) | Gets visibility flag of the specified chart subwindow |
| [WindowHandle](cchartwindowhandle.md) | Gets window handle of the chart (HWND) |
| [FirstVisibleBar](cchartfirstvisiblebar.md) | Gets the number of the first visible bar of the chart |
| [WidthInBars](cchartwidthinbars.md) | Gets window width in bars. |
| [WidthInPixels](cchartwidthinpixels.md) | Gets subwindow width in pixels. |
| [HeightInPixels](cchartheightinpixels.md) | Gets subwindow height in pixels. |
| [PriceMin](cchartpricemin.md) | Gets minimal price of the specified subwindow |
| [PriceMax](cchartpricemax.md) | Gets maximal price of the specified subwindow |
| Properties |  |
| [Attach](cchartattach.md) | Assigns the current chart to the class instance |
| [FirstChart](cchartfirstchart.md) | Assigns the first chart of the client terminal to the class instance |
| [NextChart](cchartnextchart.md) | Assigns the next chart of the client terminal to the class instance |
| [Open](cchartopen.md) | Opens chart with specified parameters and assign it to the class instance |
| [Detach](cchartdetach.md) | Detaches chart from the class instance |
| [Close](cchartclose.md) | Closes chart assigned to the class instance |
| [BringToTop](cchartbringtotop.md) | Show chart on top of other charts |
| [EventObjectCreate](ccharteventobjectcreate.md) | Sets a flag to send notifications of an event of new object creation on a chart |
| [EventObjectDelete](ccharteventobjectdelete.md) | Sets a flag to send notifications of an event of object deletion on a chart |
| Indicators |  |
| [IndicatorAdd](cchartindicatoradd.md) | Adds an indicator with the specified handle into a specified chart subwindow |
| [IndicatorDelete](cchartindicatordelete.md) | Removes an indicator with a specified name from the specified chart subwindow |
| [IndicatorsTotal](cchartindicatorstotal.md) | Returns the number of all indicators applied to the specified chart subwindow |
| [IndicatorName](cchartindicatorname.md) | Returns the short name of the indicator on the specified chart subwindow |
| Navigation |  |
| [Navigate](cchartnavigate.md) | Navigates the chart |
| Access to MQL5 API |  |
| [Symbol](cchartsymbol.md) | Gets symbol of the chart |
| [Period](cchartperiod.md) | Gets period of the chart |
| [Redraw](cchartredraw.md) | Redraws chart, assigned to the class instance |
| [GetInteger](cchartgetinteger.md) | The function returns the value of the corresponding object property |
| [SetInteger](cchartsetinteger.md) | Sets new value for the property of the integer type |
| [GetDouble](cchartgetdouble.md) | The function returns the value of the corresponding object property |
| [SetDouble](cchartsetdouble.md) | Sets new value for the property of the double type |
| [GetString](cchartgetstring.md) | The function returns the value of the corresponding object property |
| [SetString](cchartsetstring.md) | Sets new value for the property of the string type |
| [SetSymbolPeriod](cchartsetsymbolperiod.md) | Changes symbol and period of the chart assigned to the class instance |
| [ApplyTemplate](cchartapplytemplate.md) | Applies specified template to the chart |
| [ScreenShot](cchartscreenshot.md) | Creates screenshot of the specified chart and saves it to .gif file |
| [WindowOnDropped](cchartwindowondropped.md) | Gets chart subwindow number corresponding to the object (expert or script) drop point |
| [PriceOnDropped](cchartpriceondropped.md) | Gets price coordinate corresponding to the object (expert or script) drop point |
| [TimeOnDropped](ccharttimeondropped.md) | Gets time coordinate corresponding to the object (expert or script) drop point |
| [XOnDropped](cchartxondropped.md) | Gets X coordinate corresponding to the object (expert or script) drop point |
| [YOnDropped](cchartyondropped.md) | Gets Y coordinate corresponding to the object (expert or script) drop point |
| Input/Output |  |
| virtual [Save](cchartsave.md) | Saves object parameters to file |
| virtual [Load](cchartload.md) | Loads object parameters from file |
| virtual [Type](cchartype.md) | Gets graphic object type identifier |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |