List of MQL5 Constants



[MQL5 Reference](index.md) / List of MQL5 Constants

[![Previous](previous.png)](function_indices.md)

List of MQL5 Constants

All MQL5 constants in alphabetical order.

| Constant | Description | Usage |
| --- | --- | --- |
| \_\_DATE\_\_ | File compilation date without time (hours, minutes and seconds are equal to 0) | [Print](print.md) |
| \_\_DATETIME\_\_ | File compilation date and time | [Print](print.md) |
| \_\_FILE\_\_ | Name of the currently compiled file | [Print](print.md) |
| \_\_FUNCSIG\_\_ | Signature of the function in whose body the macro is located. Logging of the full description of functions can be useful in the identification of [overloaded functions](functionoverload.md) | [Print](print.md) |
| \_\_FUNCTION\_\_ | Name of the function, in whose body the macro is located | [Print](print.md) |
| \_\_LINE\_\_ | Line number in the source code, in which the macro is located | [Print](print.md) |
| \_\_MQLBUILD\_\_, \_\_MQL5BUILD\_\_ | Compiler build number | [Print](print.md) |
| \_\_PATH\_\_ | An absolute path to the file that is currently being compiled | [Print](print.md) |
| ACCOUNT\_ASSETS | The current assets of an account | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_BALANCE | Account balance in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_COMMISSION\_BLOCKED | The current blocked commission amount on an account | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_COMPANY | Name of a company that serves the account | [AccountInfoString](accountinfostring.md) |
| ACCOUNT\_CREDIT | Account credit in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_CURRENCY | Account currency | [AccountInfoString](accountinfostring.md) |
| ACCOUNT\_EQUITY | Account equity in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_LEVERAGE | Account leverage | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_LIABILITIES | The current liabilities on an account | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_LIMIT\_ORDERS | Maximum allowed number of active pending orders | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_LOGIN | Account number | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_MARGIN | Account margin used in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_MARGIN\_FREE | Free margin of an account in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_MARGIN\_INITIAL | Initial margin. The amount reserved on an account to cover the margin of all pending orders | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_MARGIN\_LEVEL | Account margin level in percents | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_MARGIN\_MAINTENANCE | Maintenance margin. The minimum equity reserved on an account to cover the minimum amount of all open positions | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_MARGIN\_SO\_CALL | Margin call level. Depending on the set ACCOUNT\_MARGIN\_SO\_MODE is expressed in percents or in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_MARGIN\_SO\_MODE | Mode for setting the minimal allowed margin | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_MARGIN\_SO\_SO | Margin stop out level. Depending on the set ACCOUNT\_MARGIN\_SO\_MODE is expressed in percents or in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_NAME | Client name | [AccountInfoString](accountinfostring.md) |
| ACCOUNT\_PROFIT | Current profit of an account in the deposit currency | [AccountInfoDouble](accountinfodouble.md) |
| ACCOUNT\_SERVER | Trade server name | [AccountInfoString](accountinfostring.md) |
| ACCOUNT\_STOPOUT\_MODE\_MONEY | Account stop out mode in money | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_STOPOUT\_MODE\_PERCENT | Account stop out mode in percents | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_TRADE\_ALLOWED | [Allowed trade](tradepermission.md) for the current account | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_TRADE\_EXPERT | [Allowed trade](tradepermission.md) for an Expert Advisor | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_TRADE\_MODE | Account trade mode | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_TRADE\_MODE\_CONTEST | Contest account | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_TRADE\_MODE\_DEMO | Demo account | [AccountInfoInteger](accountinfointeger.md) |
| ACCOUNT\_TRADE\_MODE\_REAL | Real account | [AccountInfoInteger](accountinfointeger.md) |
| ALIGN\_CENTER | Centered (only for the Edit object) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md), [ChartScreenShot](customind.md) |
| ALIGN\_LEFT | Left alignment | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md), [ChartScreenShot](customind.md) |
| ALIGN\_RIGHT | Right alignment | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md), [ChartScreenShot](customind.md) |
| ANCHOR\_CENTER | Anchor point strictly in the center of the object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_LEFT | Anchor point to the left in the center | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_LEFT\_LOWER | Anchor point at the lower left corner | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_LEFT\_UPPER | Anchor point at the upper left corner | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_LOWER | Anchor point below in the center | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_RIGHT | Anchor point to the right in the center | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_RIGHT\_LOWER | Anchor point at the lower right corner | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_RIGHT\_UPPER | Anchor point at the upper right corner | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ANCHOR\_UPPER | Anchor point above in the center | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| BASE\_LINE | Main line | [Indicators Lines](lines.md) |
| BOOK\_TYPE\_BUY | Buy order (Bid) | [MqlBookInfo](mqlbookinfo.md) |
| BOOK\_TYPE\_BUY\_MARKET | Buy order by Market | [MqlBookInfo](mqlbookinfo.md) |
| BOOK\_TYPE\_SELL | Sell order (Offer) | [MqlBookInfo](mqlbookinfo.md) |
| BOOK\_TYPE\_SELL\_MARKET | Sell order by Market | [MqlBookInfo](mqlbookinfo.md) |
| BORDER\_FLAT | Flat form | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| BORDER\_RAISED | Prominent form | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| BORDER\_SUNKEN | Concave form | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| CHAR\_MAX | Maximal value, which can be represented by char type | [Numerical Type Constants](typeconstants.md) |
| CHAR\_MIN | Minimal value, which can be represented by char type | [Numerical Type Constants](typeconstants.md) |
| [CHART\_AUTOSCROLL](charts_samples.md#chart_autoscroll) | Mode of automatic moving to the right border of the chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| CHART\_BARS | Display as a sequence of bars | [ChartSetInteger](chartsetinteger.md) |
| CHART\_BEGIN | Chart beginning (the oldest prices) | [ChartNavigate](chartnavigate.md) |
| [CHART\_BRING\_TO\_TOP](charts_samples.md#chart_bring_to_top) | Show chart on top of other charts | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| CHART\_CANDLES | Display as Japanese candlesticks | [ChartSetInteger](chartsetinteger.md) |
| [CHART\_COLOR\_ASK](charts_samples.md#chart_color_ask) | Ask price level color | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_BACKGROUND](charts_samples.md#chart_color_background) | Chart background color | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_BID](charts_samples.md#chart_color_bid) | Bid price level color | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_CANDLE\_BEAR](charts_samples.md#chart_color_candle_bear) | Body color of a bear candlestick | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_CANDLE\_BULL](charts_samples.md#chart_color_candle_bull) | Body color of a bull candlestick | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_CHART\_DOWN](charts_samples.md#chart_color_chart_down) | Color for the down bar, shadows and body borders of bear candlesticks | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_CHART\_LINE](charts_samples.md#chart_color_chart_line) | Line chart color and color of "Doji" Japanese candlesticks | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_CHART\_UP](charts_samples.md#chart_color_chart_up) | Color for the up bar, shadows and body borders of bull candlesticks | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_FOREGROUND](charts_samples.md#chart_color_foreground) | Color of axes, scales and OHLC line | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_GRID](charts_samples.md#chart_color_grid) | Grid color | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_LAST](charts_samples.md#chart_color_last) | Line color of the last executed deal price (Last) | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_STOP\_LEVEL](charts_samples.md#chart_color_stop_level) | Color of stop order levels (Stop Loss and Take Profit) | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COLOR\_VOLUME](charts_samples.md#chart_color_volume) | Color of volumes and position opening levels | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_COMMENT](charts_samples.md#chart_comment) | Text of a comment in a chart | [ChartSetString](chartsetstring.md), [ChartGetString](chartgetstring.md) |
| CHART\_CURRENT\_POS | Current position | [ChartNavigate](chartnavigate.md) |
| [CHART\_DRAG\_TRADE\_LEVELS](charts_samples.md#chart_drag_trade_levels) | Permission to drag trading levels on a chart with a mouse. The drag mode is enabled by default (true value) | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_EVENT\_MOUSE\_MOVE](charts_samples.md#chart_event_mouse_move) | Send notifications of mouse move and mouse click events ([CHARTEVENT\_MOUSE\_MOVE](enum_chartevents.md)) to all mql5 programs on a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_EVENT\_OBJECT\_CREATE](charts_samples.md#chart_event_object_create) | Send a notification of an event of new object creation ([CHARTEVENT\_OBJECT\_CREATE](enum_chartevents.md)) to all mql5-programs on a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_EVENT\_OBJECT\_DELETE](charts_samples.md#chart_event_object_delete) | Send a notification of an event of object deletion ([CHARTEVENT\_OBJECT\_DELETE](enum_chartevents.md)) to all mql5-programs on a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_FIRST\_VISIBLE\_BAR](charts_samples.md#chart_first_visible_bar) | Number of the first visible bar in the chart. Indexing of bars is the same as for [timeseries](series.md). | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_FIXED\_MAX](charts_samples.md#chart_fixed_max) | Fixed  chart maximum | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_FIXED\_MIN](charts_samples.md#chart_fixed_min) | Fixed  chart minimum | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_FIXED\_POSITION](charts_samples.md#chart_fixed_position) | Chart fixed position from the left border in percent value. Chart fixed position is marked by a small gray triangle on the horizontal time axis. It is displayed only if the automatic chart scrolling to the right on tick incoming is disabled (see CHART\_AUTOSCROLL property). The bar on a fixed position remains in the same place when zooming in and out. | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_FOREGROUND](charts_samples.md#chart_foreground) | Price chart in the foreground | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_HEIGHT\_IN\_PIXELS](charts_samples.md#chart_height_in_pixels) | Chart height in pixels | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_IS\_OBJECT](charts_samples.md#chart_is_object) | Identifying "Chart" ([OBJ\_CHART)](enum_object.md) object returns true for a graphical object. Returns false for a real chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| CHART\_LINE | Display as a line drawn by Close prices | [ChartSetInteger](chartsetinteger.md) |
| [CHART\_MODE](charts_samples.md#chart_mode) | Chart type (candlesticks, bars or line) | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_MOUSE\_SCROLL](charts_samples.md#chart_mouse_scroll) | Scrolling the chart horizontally using the left mouse button. Vertical scrolling is also available if the value of any following properties is set to true: CHART\_SCALEFIX, CHART\_SCALEFIX\_11 or CHART\_SCALE\_PT\_PER\_BAR | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_POINTS\_PER\_BAR](charts_samples.md#chart_points_per_bar) | Scale in points per bar | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_PRICE\_MAX](charts_samples.md#chart_price_max) | Chart maximum | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_PRICE\_MIN](charts_samples.md#chart_price_min) | Chart minimum | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_SCALE](charts_samples.md#chart_scale) | Scale | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SCALE\_PT\_PER\_BAR](charts_samples.md#chart_scale_pt_per_bar) | Scale to be specified in points per bar | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SCALEFIX](charts_samples.md#chart_scalefix) | Fixed scale mode | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SCALEFIX\_11](charts_samples.md#chart_scalefix_11) | Scale 1:1 mode | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHIFT](charts_samples.md#chart_shift) | Mode of price chart indent from the right border | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHIFT\_SIZE](charts_samples.md#chart_shift_size) | The size of the zero bar indent from the right border in percents | [ChartSetDouble](chartsetdouble.md), [ChartGetDouble](chartgetdouble.md) |
| [CHART\_SHOW\_ASK\_LINE](charts_samples.md#chart_show_ask_line) | Display Ask values as a horizontal line in a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_BID\_LINE](charts_samples.md#chart_show_bid_line) | Display Bid values as a horizontal line in a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_DATE\_SCALE](charts_samples.md#chart_show_date_scale) | Showing the time scale on a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_GRID](charts_samples.md#chart_show_grid) | Display grid in the chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_LAST\_LINE](charts_samples.md#chart_show_last_line) | Display Last values as a horizontal line in a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_OBJECT\_DESCR](charts_samples.md#chart_show_object_descr) | Pop-up descriptions of graphical objects | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_OHLC](charts_samples.md#chart_show_ohlc) | Show OHLC values in the upper left corner | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_ONE\_CLICK](charts_samples.md#chart_show_one_click) | Showing the ["One click trading"](https://www.metatrader5.com/en/terminal/help/startworking/settings "\"One click trading\"") panel on a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_PERIOD\_SEP](charts_samples.md#chart_show_period_sep) | Display vertical separators between adjacent periods | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_PRICE\_SCALE](charts_samples.md#chart_show_price_scale) | Showing the price scale on a chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_TRADE\_LEVELS](charts_samples.md#chart_show_trade_levels) | Displaying trade levels in the chart (levels of open positions, Stop Loss, Take Profit and pending orders) | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_SHOW\_VOLUMES](charts_samples.md#chart_show_volumes) | Display volume in the chart | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_VISIBLE\_BARS](charts_samples.md#chart_visible_bars) | The number of bars on the chart that can be displayed | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| CHART\_VOLUME\_HIDE | Volumes are not shown | [ChartSetInteger](chartsetinteger.md) |
| CHART\_VOLUME\_REAL | Trade volumes | [ChartSetInteger](chartsetinteger.md) |
| CHART\_VOLUME\_TICK | Tick volumes | [ChartSetInteger](chartsetinteger.md) |
| [CHART\_WIDTH\_IN\_BARS](charts_samples.md#chart_width_in_bars) | Chart width in bars | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_WIDTH\_IN\_PIXELS](charts_samples.md#chart_width_in_pixels) | Chart width in pixels | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_WINDOW\_HANDLE](charts_samples.md#chart_window_handle) | Chart window handle (HWND) | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_WINDOW\_IS\_VISIBLE](charts_samples.md#chart_window_is_visible) | Visibility of subwindows | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_WINDOW\_YDISTANCE](charts_samples.md#chart_window_ydistance) | The distance between the upper frame of the indicator subwindow and the upper frame of the main chart window, along the vertical Y axis, in pixels. In case of a mouse event, the cursor coordinates are passed in terms of the coordinates of the main chart window, while the coordinates of graphical objects in an indicator subwindow are set relative to the upper left corner of the subwindow.  The value is required for converting the absolute coordinates of the main chart to the local coordinates of a subwindow for correct work with the graphical objects, whose coordinates are set relative to  the upper left corner of the subwindow frame. | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| [CHART\_WINDOWS\_TOTAL](charts_samples.md#chart_windows_total) | The total number of chart windows, including indicator subwindows | [ChartSetInteger](chartsetinteger.md), [ChartGetInteger](chartgetinteger.md) |
| CHARTEVENT\_CHART\_CHANGE | Change of the chart size or modification of chart properties through the Properties dialog | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_CLICK | Clicking on a chart | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_CUSTOM | Initial number of an event from a range of custom events | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_CUSTOM\_LAST | The final number of an event from a range of custom events | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_KEYDOWN | Keystrokes | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_MOUSE\_MOVE | Mouse move, mouse clicks (if [CHART\_EVENT\_MOUSE\_MOVE](enum_chart_property.md#enum_chart_property_integer)=true is set for the chart) | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_OBJECT\_CHANGE | [Graphical object](enum_object.md) property changed via the properties dialog | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_OBJECT\_CLICK | Clicking on a [graphical object](enum_object.md) | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_OBJECT\_CREATE | [Graphical object](enum_object.md) created (if [CHART\_EVENT\_OBJECT\_CREATE](enum_chart_property.md#enum_chart_property_integer)=true is set for the chart) | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_OBJECT\_DELETE | [Graphical object](enum_object.md) deleted (if [CHART\_EVENT\_OBJECT\_DELETE](enum_chart_property.md#enum_chart_property_integer)=true is set for the chart) | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_OBJECT\_DRAG | Drag and drop of a [graphical object](enum_object.md) | [OnChartEvent](onchartevent.md) |
| CHARTEVENT\_OBJECT\_ENDEDIT | End of text editing in the graphical object Edit | [OnChartEvent](onchartevent.md) |
| CHARTS\_MAX | The maximum possible number of simultaneously open charts in the terminal | [Other Constants](otherconstants.md) |
| CHIKOUSPAN\_LINE | Chikou Span line | [Indicators Lines](lines.md) |
| clrAliceBlue | Alice Blue | [Web Colors](webcolors.md) |
| clrAntiqueWhite | Antique White | [Web Colors](webcolors.md) |
| clrAqua | Aqua | [Web Colors](webcolors.md) |
| clrAquamarine | Aquamarine | [Web Colors](webcolors.md) |
| clrBeige | Beige | [Web Colors](webcolors.md) |
| clrBisque | Bisque | [Web Colors](webcolors.md) |
| clrBlack | Black | [Web Colors](webcolors.md) |
| clrBlanchedAlmond | Blanched Almond | [Web Colors](webcolors.md) |
| clrBlue | Blue | [Web Colors](webcolors.md) |
| clrBlueViolet | Blue Violet | [Web Colors](webcolors.md) |
| clrBrown | Brown | [Web Colors](webcolors.md) |
| clrBurlyWood | Burly Wood | [Web Colors](webcolors.md) |
| clrCadetBlue | Cadet Blue | [Web Colors](webcolors.md) |
| clrChartreuse | Chartreuse | [Web Colors](webcolors.md) |
| clrChocolate | Chocolate | [Web Colors](webcolors.md) |
| clrCoral | Coral | [Web Colors](webcolors.md) |
| clrCornflowerBlue | Cornflower Blue | [Web Colors](webcolors.md) |
| clrCornsilk | Cornsilk | [Web Colors](webcolors.md) |
| clrCrimson | Crimson | [Web Colors](webcolors.md) |
| clrDarkBlue | Dark Blue | [Web Colors](webcolors.md) |
| clrDarkGoldenrod | Dark Goldenrod | [Web Colors](webcolors.md) |
| clrDarkGray | Dark Gray | [Web Colors](webcolors.md) |
| clrDarkGreen | Dark Green | [Web Colors](webcolors.md) |
| clrDarkKhaki | Dark Khaki | [Web Colors](webcolors.md) |
| clrDarkOliveGreen | Dark Olive Green | [Web Colors](webcolors.md) |
| clrDarkOrange | Dark Orange | [Web Colors](webcolors.md) |
| clrDarkOrchid | Dark Orchid | [Web Colors](webcolors.md) |
| clrDarkSalmon | Dark Salmon | [Web Colors](webcolors.md) |
| clrDarkSeaGreen | Dark Sea Green | [Web Colors](webcolors.md) |
| clrDarkSlateBlue | Dark Slate Blue | [Web Colors](webcolors.md) |
| clrDarkSlateGray | Dark Slate Gray | [Web Colors](webcolors.md) |
| clrDarkTurquoise | Dark Turquoise | [Web Colors](webcolors.md) |
| clrDarkViolet | Dark Violet | [Web Colors](webcolors.md) |
| clrDeepPink | Deep Pink | [Web Colors](webcolors.md) |
| clrDeepSkyBlue | Deep Sky Blue | [Web Colors](webcolors.md) |
| clrDimGray | Dim Gray | [Web Colors](webcolors.md) |
| clrDodgerBlue | Dodger Blue | [Web Colors](webcolors.md) |
| clrFireBrick | Fire Brick | [Web Colors](webcolors.md) |
| clrForestGreen | Forest Green | [Web Colors](webcolors.md) |
| clrGainsboro | Gainsboro | [Web Colors](webcolors.md) |
| clrGold | Gold | [Web Colors](webcolors.md) |
| clrGoldenrod | Goldenrod | [Web Colors](webcolors.md) |
| clrGray | Gray | [Web Colors](webcolors.md) |
| clrGreen | Green | [Web Colors](webcolors.md) |
| clrGreenYellow | Green Yellow | [Web Colors](webcolors.md) |
| clrHoneydew | Honeydew | [Web Colors](webcolors.md) |
| clrHotPink | Hot Pink | [Web Colors](webcolors.md) |
| clrIndianRed | Indian Red | [Web Colors](webcolors.md) |
| clrIndigo | Indigo | [Web Colors](webcolors.md) |
| clrIvory | Ivory | [Web Colors](webcolors.md) |
| clrKhaki | Khaki | [Web Colors](webcolors.md) |
| clrLavender | Lavender | [Web Colors](webcolors.md) |
| clrLavenderBlush | Lavender Blush | [Web Colors](webcolors.md) |
| clrLawnGreen | Lawn Green | [Web Colors](webcolors.md) |
| clrLemonChiffon | Lemon Chiffon | [Web Colors](webcolors.md) |
| clrLightBlue | Light Blue | [Web Colors](webcolors.md) |
| clrLightCoral | Light Coral | [Web Colors](webcolors.md) |
| clrLightCyan | Light Cyan | [Web Colors](webcolors.md) |
| clrLightGoldenrod | Light Goldenrod | [Web Colors](webcolors.md) |
| clrLightGray | Light Gray | [Web Colors](webcolors.md) |
| clrLightGreen | Light Green | [Web Colors](webcolors.md) |
| clrLightPink | Light Pink | [Web Colors](webcolors.md) |
| clrLightSalmon | Light Salmon | [Web Colors](webcolors.md) |
| clrLightSeaGreen | Light Sea Green | [Web Colors](webcolors.md) |
| clrLightSkyBlue | Light Sky Blue | [Web Colors](webcolors.md) |
| clrLightSlateGray | Light Slate Gray | [Web Colors](webcolors.md) |
| clrLightSteelBlue | Light Steel Blue | [Web Colors](webcolors.md) |
| clrLightYellow | Light Yellow | [Web Colors](webcolors.md) |
| clrLime | Lime | [Web Colors](webcolors.md) |
| clrLimeGreen | Lime Green | [Web Colors](webcolors.md) |
| clrLinen | Linen | [Web Colors](webcolors.md) |
| clrMagenta | Magenta | [Web Colors](webcolors.md) |
| clrMaroon | Maroon | [Web Colors](webcolors.md) |
| clrMediumAquamarine | Medium Aquamarine | [Web Colors](webcolors.md) |
| clrMediumBlue | Medium Blue | [Web Colors](webcolors.md) |
| clrMediumOrchid | Medium Orchid | [Web Colors](webcolors.md) |
| clrMediumPurple | Medium Purple | [Web Colors](webcolors.md) |
| clrMediumSeaGreen | Medium Sea Green | [Web Colors](webcolors.md) |
| clrMediumSlateBlue | Medium Slate Blue | [Web Colors](webcolors.md) |
| clrMediumSpringGreen | Medium Spring Green | [Web Colors](webcolors.md) |
| clrMediumTurquoise | Medium Turquoise | [Web Colors](webcolors.md) |
| clrMediumVioletRed | Medium Violet Red | [Web Colors](webcolors.md) |
| clrMidnightBlue | Midnight Blue | [Web Colors](webcolors.md) |
| clrMintCream | Mint Cream | [Web Colors](webcolors.md) |
| clrMistyRose | Misty Rose | [Web Colors](webcolors.md) |
| clrMoccasin | Moccasin | [Web Colors](webcolors.md) |
| clrNavajoWhite | Navajo White | [Web Colors](webcolors.md) |
| clrNavy | Navy | [Web Colors](webcolors.md) |
| clrNONE | Absence of color | [Other Constants](otherconstants.md) |
| clrOldLace | Old Lace | [Web Colors](webcolors.md) |
| clrOlive | Olive | [Web Colors](webcolors.md) |
| clrOliveDrab | Olive Drab | [Web Colors](webcolors.md) |
| clrOrange | Orange | [Web Colors](webcolors.md) |
| clrOrangeRed | Orange Red | [Web Colors](webcolors.md) |
| clrOrchid | Orchid | [Web Colors](webcolors.md) |
| clrPaleGoldenrod | Pale Goldenrod | [Web Colors](webcolors.md) |
| clrPaleGreen | Pale Green | [Web Colors](webcolors.md) |
| clrPaleTurquoise | Pale Turquoise | [Web Colors](webcolors.md) |
| clrPaleVioletRed | Pale Violet Red | [Web Colors](webcolors.md) |
| clrPapayaWhip | Papaya Whip | [Web Colors](webcolors.md) |
| clrPeachPuff | Peach Puff | [Web Colors](webcolors.md) |
| clrPeru | Peru | [Web Colors](webcolors.md) |
| clrPink | Pink | [Web Colors](webcolors.md) |
| clrPlum | Plum | [Web Colors](webcolors.md) |
| clrPowderBlue | Powder Blue | [Web Colors](webcolors.md) |
| clrPurple | Purple | [Web Colors](webcolors.md) |
| clrRed | Red | [Web Colors](webcolors.md) |
| clrRosyBrown | Rosy Brown | [Web Colors](webcolors.md) |
| clrRoyalBlue | Royal Blue | [Web Colors](webcolors.md) |
| clrSaddleBrown | Saddle Brown | [Web Colors](webcolors.md) |
| clrSalmon | Salmon | [Web Colors](webcolors.md) |
| clrSandyBrown | Sandy Brown | [Web Colors](webcolors.md) |
| clrSeaGreen | Sea Green | [Web Colors](webcolors.md) |
| clrSeashell | Seashell | [Web Colors](webcolors.md) |
| clrSienna | Sienna | [Web Colors](webcolors.md) |
| clrSilver | Silver | [Web Colors](webcolors.md) |
| clrSkyBlue | Sky Blue | [Web Colors](webcolors.md) |
| clrSlateBlue | Slate Blue | [Web Colors](webcolors.md) |
| clrSlateGray | Slate Gray | [Web Colors](webcolors.md) |
| clrSnow | Snow | [Web Colors](webcolors.md) |
| clrSpringGreen | Spring Green | [Web Colors](webcolors.md) |
| clrSteelBlue | Steel Blue | [Web Colors](webcolors.md) |
| clrTan | Tan | [Web Colors](webcolors.md) |
| clrTeal | Teal | [Web Colors](webcolors.md) |
| clrThistle | Thistle | [Web Colors](webcolors.md) |
| clrTomato | Tomato | [Web Colors](webcolors.md) |
| clrTurquoise | Turquoise | [Web Colors](webcolors.md) |
| clrViolet | Violet | [Web Colors](webcolors.md) |
| clrWheat | Wheat | [Web Colors](webcolors.md) |
| clrWhite | White | [Web Colors](webcolors.md) |
| clrWhiteSmoke | White Smoke | [Web Colors](webcolors.md) |
| clrYellow | Yellow | [Web Colors](webcolors.md) |
| clrYellowGreen | Yellow Green | [Web Colors](webcolors.md) |
| CORNER\_LEFT\_LOWER | Center of coordinates is in the lower left corner of the chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| CORNER\_LEFT\_UPPER | Center of coordinates is in the upper left corner of the chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| CORNER\_RIGHT\_LOWER | Center of coordinates is in the lower right corner of the chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| CORNER\_RIGHT\_UPPER | Center of coordinates is in the upper right corner of the chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| CP\_ACP | The current Windows ANSI code page. | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CP\_MACCP | The current system Macintosh code page.  Note: This value is mostly used in earlier created program codes and is of no use now, since modern Macintosh computers use Unicode for encoding. | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CP\_OEMCP | The current system OEM code page. | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CP\_SYMBOL | Symbol code page | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CP\_THREAD\_ACP | The Windows ANSI code page for the current thread. | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CP\_UTF7 | UTF-7 code page. | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CP\_UTF8 | UTF-8 code page. | [CharArrayToString](chararraytostring.md), [StringToCharArray](stringtochararray.md), [FileOpen](fileopen.md) |
| CRYPT\_AES128 | AES encryption with 128 bit key (16 bytes) | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_AES256 | AES encryption with 256 bit key (32 bytes) | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_ARCH\_ZIP | ZIP archives | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_BASE64 | BASE64 | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_DES | DES encryption with 56 bit key (7 bytes) | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_HASH\_MD5 | MD5 HASH calculation | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_HASH\_SHA1 | SHA1 HASH calculation | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| CRYPT\_HASH\_SHA256 | SHA256 HASH calculation | [CryptEncode](cryptencode.md), [CryptDecode](cryptdecode.md) |
| DBL\_DIG | Number of significant decimal digits for double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_EPSILON | Minimal value, which satisfies the condition:  1.0+DBL\_EPSILON != 1.0 (for double type) | [Numerical Type Constants](typeconstants.md) |
| DBL\_MANT\_DIG | Bits count in a mantissa for double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_MAX | Maximal value, which can be represented by double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_MAX\_10\_EXP | Maximal decimal value of exponent degree for double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_MAX\_EXP | Maximal binary value of exponent degree for double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_MIN | Minimal positive value, which can be represented by double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_MIN\_10\_EXP | Minimal decimal value of exponent degree for double type | [Numerical Type Constants](typeconstants.md) |
| DBL\_MIN\_EXP | Minimal binary value of exponent degree for double type | [Numerical Type Constants](typeconstants.md) |
| DEAL\_COMMENT | Deal comment | [HistoryDealGetString](historydealgetstring.md) |
| DEAL\_COMMISSION | Deal commission | [HistoryDealGetDouble](historydealgetdouble.md) |
| DEAL\_ENTRY | Deal entry - entry in, entry out, reverse | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_ENTRY\_IN | Entry in | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_ENTRY\_INOUT | Reverse | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_ENTRY\_OUT | Entry out | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_MAGIC | Deal magic number (see [ORDER\_MAGIC](orderproperties.md)) | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_ORDER | Deal [order number](historyordergetticket.md) | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_POSITION\_ID | [Identifier of a position](positionproperties.md#enum_position_property_integer), in the opening, modification or change of which this deal took part. Each position has a unique identifier that is assigned to all deals executed for the symbol during the entire lifetime of the position. | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_PRICE | Deal price | [HistoryDealGetDouble](historydealgetdouble.md) |
| DEAL\_PROFIT | Deal profit | [HistoryDealGetDouble](historydealgetdouble.md) |
| DEAL\_SWAP | Cumulative swap on close | [HistoryDealGetDouble](historydealgetdouble.md) |
| DEAL\_SYMBOL | Deal symbol | [HistoryDealGetString](historydealgetstring.md) |
| DEAL\_TIME | Deal time | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TIME\_MSC | The time of a deal execution in milliseconds since 01.01.1970 | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE | Deal type | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_BALANCE | Balance | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_BONUS | Bonus | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_BUY | Buy | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_BUY\_CANCELED | Canceled buy deal. There can be a situation when a previously executed buy deal is canceled. In this case, the type of the previously executed deal (DEAL\_TYPE\_BUY) is changed to DEAL\_TYPE\_BUY\_CANCELED, and its profit/loss is zeroized. Previously obtained profit/loss is charged/withdrawn using a separated balance operation | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_CHARGE | Additional charge | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_COMMISSION | Additional commission | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_COMMISSION\_AGENT\_DAILY | Daily agent commission | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_COMMISSION\_AGENT\_MONTHLY | Monthly agent commission | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_COMMISSION\_DAILY | Daily commission | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_COMMISSION\_MONTHLY | Monthly commission | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_CORRECTION | Correction | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_CREDIT | Credit | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_INTEREST | Interest rate | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_SELL | Sell | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_TYPE\_SELL\_CANCELED | Canceled sell deal. There can be a situation when a previously executed sell deal is canceled. In this case, the type of the previously executed deal (DEAL\_TYPE\_SELL) is changed to DEAL\_TYPE\_SELL\_CANCELED, and its profit/loss is zeroized. Previously obtained profit/loss is charged/withdrawn using a separated balance operation | [HistoryDealGetInteger](historydealgetinteger.md) |
| DEAL\_VOLUME | Deal volume | [HistoryDealGetDouble](historydealgetdouble.md) |
| [DRAW\_ARROW](draw_arrow.md) | Drawing arrows | [Drawing Styles](drawstyles.md) |
| [DRAW\_BARS](draw_bars.md) | Display as a sequence of bars | [Drawing Styles](drawstyles.md) |
| [DRAW\_CANDLES](draw_candles.md) | Display as a sequence of candlesticks | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_ARROW](draw_color_arrow.md) | Drawing multicolored arrows | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_BARS](draw_color_bars.md) | Multicolored bars | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_CANDLES](draw_color_candles.md) | Multicolored candlesticks | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_HISTOGRAM](draw_color_histogram.md) | Multicolored histogram from the zero line | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_HISTOGRAM2](draw_color_histogram2.md) | Multicolored histogram of the two indicator buffers | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_LINE](draw_color_line.md) | Multicolored line | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_SECTION](draw_color_section.md) | Multicolored section | [Drawing Styles](drawstyles.md) |
| [DRAW\_COLOR\_ZIGZAG](draw_color_zigzag.md) | Multicolored ZigZag | [Drawing Styles](drawstyles.md) |
| [DRAW\_FILLING](draw_filling.md) | Color fill between the two levels | [Drawing Styles](drawstyles.md) |
| [DRAW\_HISTOGRAM](draw_histogram.md) | Histogram from the zero line | [Drawing Styles](drawstyles.md) |
| [DRAW\_HISTOGRAM2](draw_histogram2.md) | Histogram of the two indicator buffers | [Drawing Styles](drawstyles.md) |
| [DRAW\_LINE](draw_line.md) | Line | [Drawing Styles](drawstyles.md) |
| [DRAW\_NONE](draw_none.md) | Not drawn | [Drawing Styles](drawstyles.md) |
| [DRAW\_SECTION](draw_section.md) | Section | [Drawing Styles](drawstyles.md) |
| [DRAW\_ZIGZAG](draw_zigzag.md) | Style Zigzag allows vertical section on the bar | [Drawing Styles](drawstyles.md) |
| ELLIOTT\_CYCLE | Cycle | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_GRAND\_SUPERCYCLE | Grand Supercycle | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_INTERMEDIATE | Intermediate | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_MINOR | Minor | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_MINUETTE | Minuette | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_MINUTE | Minute | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_PRIMARY | Primary | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_SUBMINUETTE | Subminuette | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ELLIOTT\_SUPERCYCLE | Supercycle | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| EMPTY\_VALUE | Empty value in an indicator buffer | [Other Constants](otherconstants.md) |
| ERR\_ACCOUNT\_WRONG\_PROPERTY | Wrong account property ID | [GetLastError](getlasterror.md) |
| ERR\_ARRAY\_BAD\_SIZE | Requested array size exceeds 2 GB | [GetLastError](getlasterror.md) |
| ERR\_ARRAY\_RESIZE\_ERROR | Not enough memory for the relocation of an array, or an attempt to change the size of a static array | [GetLastError](getlasterror.md) |
| ERR\_BOOKS\_CANNOT\_ADD | Depth Of Market can not be added | [GetLastError](getlasterror.md) |
| ERR\_BOOKS\_CANNOT\_DELETE | Depth Of Market can not be removed | [GetLastError](getlasterror.md) |
| ERR\_BOOKS\_CANNOT\_GET | The data from Depth Of Market can not be obtained | [GetLastError](getlasterror.md) |
| ERR\_BOOKS\_CANNOT\_SUBSCRIBE | Error in subscribing to receive new data from Depth Of Market | [GetLastError](getlasterror.md) |
| ERR\_BUFFERS\_NO\_MEMORY | Not enough memory for the distribution of indicator buffers | [GetLastError](getlasterror.md) |
| ERR\_BUFFERS\_WRONG\_INDEX | Wrong indicator buffer index | [GetLastError](getlasterror.md) |
| ERR\_CANNOT\_CLEAN\_DIRECTORY | Failed to clear the directory (probably one or more files are blocked and removal operation failed) | [GetLastError](getlasterror.md) |
| ERR\_CANNOT\_DELETE\_DIRECTORY | The directory cannot be removed | [GetLastError](getlasterror.md) |
| ERR\_CANNOT\_DELETE\_FILE | File deleting error | [GetLastError](getlasterror.md) |
| ERR\_CANNOT\_OPEN\_FILE | File opening error | [GetLastError](getlasterror.md) |
| ERR\_CHAR\_ARRAY\_ONLY | Must be an array of type char | [GetLastError](getlasterror.md) |
| ERR\_CHART\_CANNOT\_CHANGE | Failed to change chart symbol and period | [GetLastError](getlasterror.md) |
| ERR\_CHART\_CANNOT\_CREATE\_TIMER | Failed to create timer | [GetLastError](getlasterror.md) |
| ERR\_CHART\_CANNOT\_OPEN | Chart opening error | [GetLastError](getlasterror.md) |
| ERR\_CHART\_INDICATOR\_CANNOT\_ADD | Error adding an indicator to chart | [GetLastError](getlasterror.md) |
| ERR\_CHART\_INDICATOR\_CANNOT\_DEL | Error deleting an indicator from the chart | [GetLastError](getlasterror.md) |
| ERR\_CHART\_INDICATOR\_NOT\_FOUND | Indicator not found on the specified chart | [GetLastError](getlasterror.md) |
| ERR\_CHART\_NAVIGATE\_FAILED | Error navigating through chart | [GetLastError](getlasterror.md) |
| ERR\_CHART\_NO\_EXPERT | No Expert Advisor in the chart that could handle the event | [GetLastError](getlasterror.md) |
| ERR\_CHART\_NO\_REPLY | Chart does not respond | [GetLastError](getlasterror.md) |
| ERR\_CHART\_NOT\_FOUND | Chart not found | [GetLastError](getlasterror.md) |
| ERR\_CHART\_SCREENSHOT\_FAILED | Error creating screenshots | [GetLastError](getlasterror.md) |
| ERR\_CHART\_TEMPLATE\_FAILED | Error applying template | [GetLastError](getlasterror.md) |
| ERR\_CHART\_WINDOW\_NOT\_FOUND | Subwindow containing the indicator was not found | [GetLastError](getlasterror.md) |
| ERR\_CHART\_WRONG\_ID | Wrong chart ID | [GetLastError](getlasterror.md) |
| ERR\_CHART\_WRONG\_PARAMETER | Error value of the parameter for the [function of working with charts](chart_operations.md) | [GetLastError](getlasterror.md) |
| ERR\_CHART\_WRONG\_PROPERTY | Wrong chart property ID | [GetLastError](getlasterror.md) |
| ERR\_CUSTOM\_WRONG\_PROPERTY | Wrong ID of the custom indicator property | [GetLastError](getlasterror.md) |
| ERR\_DIRECTORY\_NOT\_EXIST | Directory does not exist | [GetLastError](getlasterror.md) |
| ERR\_DOUBLE\_ARRAY\_ONLY | Must be an array of type double | [GetLastError](getlasterror.md) |
| ERR\_FILE\_BINSTRINGSIZE | String size must be specified, because the file is opened as binary | [GetLastError](getlasterror.md) |
| ERR\_FILE\_CACHEBUFFER\_ERROR | Not enough memory for cache to read | [GetLastError](getlasterror.md) |
| ERR\_FILE\_CANNOT\_REWRITE | File can not be rewritten | [GetLastError](getlasterror.md) |
| ERR\_FILE\_IS\_DIRECTORY | This is not a file, this is a directory | [GetLastError](getlasterror.md) |
| ERR\_FILE\_ISNOT\_DIRECTORY | This is a file, not a directory | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOT\_EXIST | File does not exist | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOTBIN | The file must be opened as a binary one | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOTCSV | The file must be opened as CSV | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOTTOREAD | The file must be opened for reading | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOTTOWRITE | The file must be opened for writing | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOTTXT | The file must be opened as a text | [GetLastError](getlasterror.md) |
| ERR\_FILE\_NOTTXTORCSV | The file must be opened as a text or CSV | [GetLastError](getlasterror.md) |
| ERR\_FILE\_READERROR | File reading error | [GetLastError](getlasterror.md) |
| ERR\_FILE\_WRITEERROR | Failed to write a resource to a file | [GetLastError](getlasterror.md) |
| ERR\_FLOAT\_ARRAY\_ONLY | Must be an array of type float | [GetLastError](getlasterror.md) |
| ERR\_FTP\_SEND\_FAILED | File sending via ftp failed | [GetLastError](getlasterror.md) |
| ERR\_FUNCTION\_NOT\_ALLOWED | Function is not allowed for call | [GetLastError](getlasterror.md) |
| ERR\_GLOBALVARIABLE\_EXISTS | Global variable of the client terminal with the same name already exists | [GetLastError](getlasterror.md) |
| ERR\_GLOBALVARIABLE\_NOT\_FOUND | Global variable of the client terminal is not found | [GetLastError](getlasterror.md) |
| ERR\_HISTORY\_NOT\_FOUND | Requested history not found | [GetLastError](getlasterror.md) |
| ERR\_HISTORY\_WRONG\_PROPERTY | Wrong ID of the history property | [GetLastError](getlasterror.md) |
| ERR\_INCOMPATIBLE\_ARRAYS | Copying incompatible arrays. String array can be copied only to a string array, and a numeric array - in numeric array only | [GetLastError](getlasterror.md) |
| ERR\_INCOMPATIBLE\_FILE | A text file must be for string arrays, for other arrays - binary | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_CANNOT\_ADD | Error applying an indicator to chart | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_CANNOT\_APPLY | The indicator cannot be applied to another indicator | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_CANNOT\_CREATE | Indicator cannot be created | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_CUSTOM\_NAME | The first parameter in the array must be the name of the custom indicator | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_DATA\_NOT\_FOUND | Requested data not found | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_NO\_MEMORY | Not enough memory to add the indicator | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_PARAMETER\_TYPE | Invalid parameter type in the array when creating an indicator | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_PARAMETERS\_MISSING | No parameters when creating an indicator | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_UNKNOWN\_SYMBOL | Unknown symbol | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_WRONG\_HANDLE | Wrong indicator handle | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_WRONG\_INDEX | Wrong index of the requested indicator buffer | [GetLastError](getlasterror.md) |
| ERR\_INDICATOR\_WRONG\_PARAMETERS | Wrong number of parameters when creating an indicator | [GetLastError](getlasterror.md) |
| ERR\_INT\_ARRAY\_ONLY | Must be an array of type int | [GetLastError](getlasterror.md) |
| ERR\_INTERNAL\_ERROR | Unexpected internal error | [GetLastError](getlasterror.md) |
| ERR\_INVALID\_ARRAY | Array of a wrong type, wrong size, or a damaged object of a dynamic array | [GetLastError](getlasterror.md) |
| ERR\_INVALID\_DATETIME | Invalid date and/or time | [GetLastError](getlasterror.md) |
| ERR\_INVALID\_FILEHANDLE | A file with this handle was closed, or was not opening at all | [GetLastError](getlasterror.md) |
| ERR\_INVALID\_PARAMETER | Wrong parameter when calling the system function | [GetLastError](getlasterror.md) |
| ERR\_INVALID\_POINTER | Wrong pointer | [GetLastError](getlasterror.md) |
| ERR\_INVALID\_POINTER\_TYPE | Wrong type of pointer | [GetLastError](getlasterror.md) |
| ERR\_LONG\_ARRAY\_ONLY | Must be an array of type long | [GetLastError](getlasterror.md) |
| ERR\_MAIL\_SEND\_FAILED | Email sending failed | [GetLastError](getlasterror.md) |
| ERR\_MARKET\_LASTTIME\_UNKNOWN | Time of the last tick is not known (no ticks) | [GetLastError](getlasterror.md) |
| ERR\_MARKET\_NOT\_SELECTED | Symbol is not selected in MarketWatch | [GetLastError](getlasterror.md) |
| ERR\_MARKET\_SELECT\_ERROR | Error adding or deleting a symbol in MarketWatch | [GetLastError](getlasterror.md) |
| ERR\_MARKET\_UNKNOWN\_SYMBOL | Unknown symbol | [GetLastError](getlasterror.md) |
| ERR\_MARKET\_WRONG\_PROPERTY | Wrong identifier of a symbol property | [GetLastError](getlasterror.md) |
| ERR\_MQL5\_WRONG\_PROPERTY | Wrong identifier of the program property | [GetLastError](getlasterror.md) |
| ERR\_NO\_STRING\_DATE | No date in the string | [GetLastError](getlasterror.md) |
| ERR\_NOT\_ENOUGH\_MEMORY | Not enough memory to perform the system function | [GetLastError](getlasterror.md) |
| ERR\_NOTIFICATION\_SEND\_FAILED | Failed to send a [notification](sendnotification.md) | [GetLastError](getlasterror.md) |
| ERR\_NOTIFICATION\_TOO\_FREQUENT | Too frequent sending of notifications | [GetLastError](getlasterror.md) |
| ERR\_NOTIFICATION\_WRONG\_PARAMETER | Invalid parameter for sending a notification an empty string or [NULL](void.md) has been passed to the [SendNotification()](sendnotification.md) function | [GetLastError](getlasterror.md) |
| ERR\_NOTIFICATION\_WRONG\_SETTINGS | Wrong settings of notifications in the terminal (ID is not specified or permission is not set) | [GetLastError](getlasterror.md) |
| ERR\_NOTINITIALIZED\_STRING | Not initialized string | [GetLastError](getlasterror.md) |
| ERR\_NUMBER\_ARRAYS\_ONLY | Must be a numeric array | [GetLastError](getlasterror.md) |
| ERR\_OBJECT\_ERROR | Error working with a graphical object | [GetLastError](getlasterror.md) |
| ERR\_OBJECT\_GETDATE\_FAILED | Unable to get date corresponding to the value | [GetLastError](getlasterror.md) |
| ERR\_OBJECT\_GETVALUE\_FAILED | Unable to get value corresponding to the date | [GetLastError](getlasterror.md) |
| ERR\_OBJECT\_NOT\_FOUND | Graphical object was not found | [GetLastError](getlasterror.md) |
| ERR\_OBJECT\_WRONG\_PROPERTY | Wrong ID of a graphical object property | [GetLastError](getlasterror.md) |
| ERR\_ONEDIM\_ARRAYS\_ONLY | Must be a one-dimensional array | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_BUFFER\_CREATE | Failed to create an [OpenCL buffer](clbuffercreate.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_CONTEXT\_CREATE | Error creating the [OpenCL context](clcontextcreate.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_EXECUTE | [OpenCL program](clexecute.md) runtime error | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_INTERNAL | Internal error occurred when [running OpenCL](clexecute.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_INVALID\_HANDLE | Invalid [OpenCL handle](clprogramcreate.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_KERNEL\_CREATE | Error creating an [OpenCL kernel](clkernelcreate.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_NOT\_SUPPORTED | [OpenCL functions](opencl.md) are not supported on this computer | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_PROGRAM\_CREATE | Error occurred when [compiling an OpenCL program](clprogramcreate.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_QUEUE\_CREATE | Failed to create a run queue in OpenCL | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_SET\_KERNEL\_PARAMETER | Error occurred when [setting parameters](clsetkernelarg.md) for the OpenCL kernel | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_TOO\_LONG\_KERNEL\_NAME | Too long kernel name [(OpenCL kernel)](clkernelcreate.md) | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_WRONG\_BUFFER\_OFFSET | Invalid offset in the OpenCL buffer | [GetLastError](getlasterror.md) |
| ERR\_OPENCL\_WRONG\_BUFFER\_SIZE | Invalid size of the OpenCL buffer | [GetLastError](getlasterror.md) |
| ERR\_PLAY\_SOUND\_FAILED | Sound playing failed | [GetLastError](getlasterror.md) |
| ERR\_RESOURCE\_NAME\_DUPLICATED | The names of the [dynamic](resourcecreate.md) and the [static](resources.md) resource match | [GetLastError](getlasterror.md) |
| ERR\_RESOURCE\_NAME\_IS\_TOO\_LONG | The resource name exceeds 63 characters | [GetLastError](getlasterror.md) |
| ERR\_RESOURCE\_NOT\_FOUND | Resource with this name has not been found in EX5 | [GetLastError](getlasterror.md) |
| ERR\_RESOURCE\_UNSUPPORTED\_TYPE | Unsupported resource type or its size exceeds 16 Mb | [GetLastError](getlasterror.md) |
| ERR\_SERIES\_ARRAY | Timeseries cannot be used | [GetLastError](getlasterror.md) |
| ERR\_SHORT\_ARRAY\_ONLY | Must be an array of type short | [GetLastError](getlasterror.md) |
| ERR\_SMALL\_ARRAY | Too small array, the starting position is outside the array | [GetLastError](getlasterror.md) |
| ERR\_SMALL\_ASSERIES\_ARRAY | The receiving array is declared as AS\_SERIES, and it is of insufficient size | [GetLastError](getlasterror.md) |
| ERR\_STRING\_OUT\_OF\_MEMORY | Not enough memory for the string | [GetLastError](getlasterror.md) |
| ERR\_STRING\_RESIZE\_ERROR | Not enough memory for the relocation of string | [GetLastError](getlasterror.md) |
| ERR\_STRING\_SMALL\_LEN | The string length is less than expected | [GetLastError](getlasterror.md) |
| ERR\_STRING\_TIME\_ERROR | Error converting string to date | [GetLastError](getlasterror.md) |
| ERR\_STRING\_TOO\_BIGNUMBER | Too large number, more than ULONG\_MAX | [GetLastError](getlasterror.md) |
| ERR\_STRING\_UNKNOWNTYPE | Unknown data type when converting to a string | [GetLastError](getlasterror.md) |
| ERR\_STRING\_ZEROADDED | 0 added to the string end, a useless operation | [GetLastError](getlasterror.md) |
| ERR\_STRINGPOS\_OUTOFRANGE | Position outside the string | [GetLastError](getlasterror.md) |
| ERR\_STRUCT\_WITHOBJECTS\_ORCLASS | The structure contains objects of strings and/or dynamic arrays and/or structure of such objects and/or classes | [GetLastError](getlasterror.md) |
| ERR\_SUCCESS | The operation completed successfully | [GetLastError](getlasterror.md) |
| ERR\_TERMINAL\_WRONG\_PROPERTY | Wrong identifier of the terminal property | [GetLastError](getlasterror.md) |
| ERR\_TOO\_LONG\_FILENAME | Too long file name | [GetLastError](getlasterror.md) |
| ERR\_TOO\_MANY\_FILES | More than 64 files cannot be opened at the same time | [GetLastError](getlasterror.md) |
| ERR\_TOO\_MANY\_FORMATTERS | Amount of format specifiers more than the parameters | [GetLastError](getlasterror.md) |
| ERR\_TOO\_MANY\_PARAMETERS | Amount of parameters more than the format specifiers | [GetLastError](getlasterror.md) |
| ERR\_TRADE\_DEAL\_NOT\_FOUND | Deal not found | [GetLastError](getlasterror.md) |
| ERR\_TRADE\_DISABLED | Trading by Expert Advisors prohibited | [GetLastError](getlasterror.md) |
| ERR\_TRADE\_ORDER\_NOT\_FOUND | Order not found | [GetLastError](getlasterror.md) |
| ERR\_TRADE\_POSITION\_NOT\_FOUND | Position not found | [GetLastError](getlasterror.md) |
| ERR\_TRADE\_SEND\_FAILED | Trade request sending failed | [GetLastError](getlasterror.md) |
| ERR\_TRADE\_WRONG\_PROPERTY | Wrong trade property ID | [GetLastError](getlasterror.md) |
| ERR\_USER\_ERROR\_FIRST | [User defined](setusererror.md) errors start with this code | [GetLastError](getlasterror.md) |
| ERR\_WEBREQUEST\_CONNECT\_FAILED | Failed to connect to specified URL | [GetLastError](getlasterror.md) |
| ERR\_WEBREQUEST\_INVALID\_ADDRESS | Invalid URL | [GetLastError](getlasterror.md) |
| ERR\_WEBREQUEST\_REQUEST\_FAILED | HTTP request failed | [GetLastError](getlasterror.md) |
| ERR\_WEBREQUEST\_TIMEOUT | Timeout exceeded | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_DIRECTORYNAME | Wrong directory name | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_FILEHANDLE | Wrong file handle | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_FILENAME | Invalid file name | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_FORMATSTRING | Invalid format string | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_INTERNAL\_PARAMETER | Wrong parameter in the inner call of the client terminal function | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_STRING\_DATE | Wrong date in the string | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_STRING\_OBJECT | Damaged string object | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_STRING\_PARAMETER | Damaged parameter of string type | [GetLastError](getlasterror.md) |
| ERR\_WRONG\_STRING\_TIME | Wrong time in the string | [GetLastError](getlasterror.md) |
| ERR\_ZEROSIZE\_ARRAY | An array of zero length | [GetLastError](getlasterror.md) |
| FILE\_ACCESS\_DATE | Date of the last access to the file | [FileGetInteger](filegetinteger.md) |
| FILE\_ANSI | Strings of ANSI type (one byte symbols). Flag is used in [FileOpen()](fileopen.md). | [FileOpen](fileopen.md) |
| FILE\_BIN | Binary read/write mode (without string to string conversion). Flag is used in [FileOpen()](fileopen.md). | [FileOpen](fileopen.md) |
| FILE\_COMMON | The file path in the common folder of all client terminals \Terminal\Common\Files. Flag is used in [FileOpen()](fileopen.md), [FileCopy()](filecopy.md), [FileMove()](filemove.md) and in [FileIsExist()](fileisexist.md) functions. | [FileOpen](fileopen.md), [FileCopy](filecopy.md), [FileMove](filemove.md), [FileIsExist](fileisexist.md) |
| FILE\_CREATE\_DATE | Date of creation | [FileGetInteger](filegetinteger.md) |
| FILE\_CSV | CSV file (all its elements are converted to strings of the appropriate type, Unicode or ANSI, and separated by separator). Flag is used in [FileOpen()](fileopen.md). | [FileOpen](fileopen.md) |
| FILE\_END | Get the end of file sign | [FileGetInteger](filegetinteger.md) |
| FILE\_EXISTS | Check the existence | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_ANSI | The file is opened as ANSI (see [FILE\_ANSI](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_BINARY | The file is opened as a binary file (see [FILE\_BIN](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_COMMON | The file is opened in a shared folder of all terminals (see [FILE\_COMMON](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_CSV | The file is opened as CSV (see [FILE\_CSV](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_READABLE | The opened file is readable (see [FILE\_READ](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_TEXT | The file is opened as a text file (see [FILE\_TXT](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_IS\_WRITABLE | The opened file is writable (see [FILE\_WRITE](fileflags.md)) | [FileGetInteger](filegetinteger.md) |
| FILE\_LINE\_END | Get the end of line sign | [FileGetInteger](filegetinteger.md) |
| FILE\_MODIFY\_DATE | Date of the last modification | [FileGetInteger](filegetinteger.md) |
| FILE\_POSITION | Position of a pointer in the file | [FileGetInteger](filegetinteger.md) |
| FILE\_READ | File is opened for reading. Flag is used in [FileOpen()](fileopen.md). When opening a file specification of FILE\_WRITE and/or FILE\_READ is required. | [FileOpen](fileopen.md) |
| FILE\_REWRITE | Possibility for the file rewrite using functions [FileCopy()](filecopy.md) and [FileMove()](filemove.md). The file should exist or should be opened for writing, otherwise the file will not be opened. | [FileCopy](filecopy.md), [FileMove](filemove.md) |
| FILE\_SHARE\_READ | Shared access for reading from several programs. Flag is used in [FileOpen()](fileopen.md), but it does not replace the necessity to indicate FILE\_WRITE and/or the FILE\_READ flag when opening a file. | [FileOpen](fileopen.md) |
| FILE\_SHARE\_WRITE | Shared access for writing from several programs. Flag is used in [FileOpen()](fileopen.md), but it does not replace the necessity to indicate FILE\_WRITE and/or the FILE\_READ flag when opening a file. | [FileOpen](fileopen.md) |
| FILE\_SIZE | File size in bytes | [FileGetInteger](filegetinteger.md) |
| FILE\_TXT | Simple text file (the same as csv file, but without taking into account the separators). Flag is used in [FileOpen()](fileopen.md). | [FileOpen](fileopen.md) |
| FILE\_UNICODE | Strings of UNICODE type (two byte symbols). Flag is used in [FileOpen()](fileopen.md). | [FileOpen](fileopen.md) |
| FILE\_WRITE | File is opened for writing. Flag is used in [FileOpen()](fileopen.md). When opening a file specification of FILE\_WRITE and/or FILE\_READ is required. | [FileOpen](fileopen.md) |
| FLT\_DIG | Number of significant decimal digits for float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_EPSILON | Minimal value, which satisfies the condition:  1.0+DBL\_EPSILON != 1.0 (for float type) | [Numerical Type Constants](typeconstants.md) |
| FLT\_MANT\_DIG | Bits count in a mantissa for float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_MAX | Maximal value, which can be represented by float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_MAX\_10\_EXP | Maximal decimal value of exponent degree for float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_MAX\_EXP | Maximal binary value of exponent degree for float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_MIN | Minimal positive value, which can be represented by float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_MIN\_10\_EXP | Minimal decimal value of exponent degree for float type | [Numerical Type Constants](typeconstants.md) |
| FLT\_MIN\_EXP | Minimal binary value of exponent degree for float type | [Numerical Type Constants](typeconstants.md) |
| FRIDAY | Friday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| GANN\_DOWN\_TREND | Line corresponding to the downward trend | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| GANN\_UP\_TREND | Line corresponding to the uptrend line | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| GATORJAW\_LINE | Jaw line | [Indicators Lines](lines.md) |
| GATORLIPS\_LINE | Lips line | [Indicators Lines](lines.md) |
| GATORTEETH\_LINE | Teeth line | [Indicators Lines](lines.md) |
| IDABORT | "Abort" button has been pressed | [MessageBox](messagebox.md) |
| IDCANCEL | "Cancel" button has been pressed | [MessageBox](messagebox.md) |
| IDCONTINUE | "Continue" button has been pressed | [MessageBox](messagebox.md) |
| IDIGNORE | "Ignore" button has been pressed | [MessageBox](messagebox.md) |
| IDNO | "No" button has been pressed | [MessageBox](messagebox.md) |
| IDOK | "OK" button has been pressed | [MessageBox](messagebox.md) |
| IDRETRY | "Retry" button has been pressed | [MessageBox](messagebox.md) |
| IDTRYAGAIN | "Try Again" button has been pressed | [MessageBox](messagebox.md) |
| IDYES | "Yes" button has been pressed | [MessageBox](messagebox.md) |
| IND\_AC | Accelerator Oscillator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_AD | Accumulation/Distribution | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_ADX | Average Directional Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_ADXW | ADX by Welles Wilder | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_ALLIGATOR | Alligator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_AMA | Adaptive Moving Average | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_AO | Awesome Oscillator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_ATR | Average True Range | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_BANDS | Bollinger Bands® | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_BEARS | Bears Power | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_BULLS | Bulls Power | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_BWMFI | Market Facilitation Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_CCI | Commodity Channel Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_CHAIKIN | Chaikin Oscillator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_CUSTOM | Custom indicator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_DEMA | Double Exponential Moving Average | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_DEMARKER | DeMarker | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_ENVELOPES | Envelopes | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_FORCE | Force Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_FRACTALS | Fractals | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_FRAMA | Fractal Adaptive Moving Average | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_GATOR | Gator Oscillator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_ICHIMOKU | Ichimoku Kinko Hyo | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_MA | Moving Average | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_MACD | MACD | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_MFI | Money Flow Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_MOMENTUM | Momentum | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_OBV | On Balance Volume | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_OSMA | OsMA | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_RSI | Relative Strength Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_RVI | Relative Vigor Index | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_SAR | Parabolic SAR | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_STDDEV | Standard Deviation | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_STOCHASTIC | Stochastic Oscillator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_TEMA | Triple Exponential Moving Average | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_TRIX | Triple Exponential Moving Averages Oscillator | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_VIDYA | Variable Index Dynamic Average | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_VOLUMES | Volumes | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| IND\_WPR | Williams' Percent Range | [IndicatorCreate](indicatorcreate.md), [IndicatorParameters](indicatorparameters.md) |
| INDICATOR\_CALCULATIONS | Auxiliary buffers for intermediate calculations | [SetIndexBuffer](setindexbuffer.md) |
| INDICATOR\_COLOR\_INDEX | Color | [SetIndexBuffer](setindexbuffer.md) |
| INDICATOR\_DATA | Data to draw | [SetIndexBuffer](setindexbuffer.md) |
| INDICATOR\_DIGITS | Accuracy of drawing of indicator values | [IndicatorSetInteger](indicatorsetinteger.md) |
| INDICATOR\_HEIGHT | Fixed height of the indicator's window (the preprocessor command [#property indicator\_height](compilation.md)) | [IndicatorSetInteger](indicatorsetinteger.md) |
| INDICATOR\_LEVELCOLOR | Color of the level line | [IndicatorSetInteger](indicatorsetinteger.md) |
| INDICATOR\_LEVELS | Number of levels in the indicator window | [IndicatorSetInteger](indicatorsetinteger.md) |
| INDICATOR\_LEVELSTYLE | Style of the level line | [IndicatorSetInteger](indicatorsetinteger.md) |
| INDICATOR\_LEVELTEXT | Level description | [IndicatorSetString](indicatorsetstring.md) |
| INDICATOR\_LEVELVALUE | Level value | [IndicatorSetDouble](indicatorsetdouble.md) |
| INDICATOR\_LEVELWIDTH | Thickness of the level line | [IndicatorSetInteger](indicatorsetinteger.md) |
| INDICATOR\_MAXIMUM | Maximum of the indicator window | [IndicatorSetDouble](indicatorsetdouble.md) |
| INDICATOR\_MINIMUM | Minimum of the indicator window | [IndicatorSetDouble](indicatorsetdouble.md) |
| INDICATOR\_SHORTNAME | Short indicator name | [IndicatorSetString](indicatorsetstring.md) |
| INT\_MAX | Maximal value, which can be represented by int type | [Numerical Type Constants](typeconstants.md) |
| INT\_MIN | Minimal value, which can be represented by int type | [Numerical Type Constants](typeconstants.md) |
| INVALID\_HANDLE | Incorrect handle | [Other Constants](otherconstants.md) |
| IS\_DEBUG\_MODE | Flag that a mq5-program operates in debug mode | [Other Constants](otherconstants.md) |
| IS\_PROFILE\_MODE | Flag that a mq5-program operates in profiling mode | [Other Constants](otherconstants.md) |
| KIJUNSEN\_LINE | Kijun-sen line | [Indicators Lines](lines.md) |
| LICENSE\_DEMO | A trial version of a paid product from the Market. It works only in the strategy tester | [MQLInfoInteger](mqlinfointeger.md) |
| LICENSE\_FREE | A free unlimited version | [MQLInfoInteger](mqlinfointeger.md) |
| LICENSE\_FULL | A purchased licensed version allows at least 5 activations. The number of activations is specified by seller. Seller may increase the allowed number of activations | [MQLInfoInteger](mqlinfointeger.md) |
| LICENSE\_TIME | A version with a limited term license | [MQLInfoInteger](mqlinfointeger.md) |
| LONG\_MAX | Maximal value, which can be represented by long type | [Numerical Type Constants](typeconstants.md) |
| LONG\_MIN | Minimal value, which can be represented by long type | [Numerical Type Constants](typeconstants.md) |
| LOWER\_BAND | Lower limit | [Indicators Lines](lines.md) |
| LOWER\_HISTOGRAM | Bottom histogram | [Indicators Lines](lines.md) |
| LOWER\_LINE | Bottom line | [Indicators Lines](lines.md) |
| M\_1\_PI | 1/pi | [Mathematical Constants](mathsconstants.md) |
| M\_2\_PI | 2/pi | [Mathematical Constants](mathsconstants.md) |
| M\_2\_SQRTPI | 2/sqrt(pi) | [Mathematical Constants](mathsconstants.md) |
| M\_E | e | [Mathematical Constants](mathsconstants.md) |
| M\_LN10 | ln(10) | [Mathematical Constants](mathsconstants.md) |
| M\_LN2 | ln(2) | [Mathematical Constants](mathsconstants.md) |
| M\_LOG10E | log10(e) | [Mathematical Constants](mathsconstants.md) |
| M\_LOG2E | log2(e) | [Mathematical Constants](mathsconstants.md) |
| M\_PI | pi | [Mathematical Constants](mathsconstants.md) |
| M\_PI\_2 | pi/2 | [Mathematical Constants](mathsconstants.md) |
| M\_PI\_4 | pi/4 | [Mathematical Constants](mathsconstants.md) |
| M\_SQRT1\_2 | 1/sqrt(2) | [Mathematical Constants](mathsconstants.md) |
| M\_SQRT2 | sqrt(2) | [Mathematical Constants](mathsconstants.md) |
| MAIN\_LINE | Main line | [Indicators Lines](lines.md) |
| MB\_ABORTRETRYIGNORE | Message window contains three buttons: Abort, Retry and Ignore | [MessageBox](messagebox.md) |
| MB\_CANCELTRYCONTINUE | Message window contains three buttons: Cancel, Try Again, Continue | [MessageBox](messagebox.md) |
| MB\_DEFBUTTON1 | The first button MB\_DEFBUTTON1 - is default, if the other buttons MB\_DEFBUTTON2, MB\_DEFBUTTON3, or MB\_DEFBUTTON4 are not specified | [MessageBox](messagebox.md) |
| MB\_DEFBUTTON2 | The second button is default | [MessageBox](messagebox.md) |
| MB\_DEFBUTTON3 | The third button is default | [MessageBox](messagebox.md) |
| MB\_DEFBUTTON4 | The fourth button is default | [MessageBox](messagebox.md) |
| MB\_ICONEXCLAMATION,  MB\_ICONWARNING | The exclamation/warning sign icon | [MessageBox](messagebox.md) |
| MB\_ICONINFORMATION,  MB\_ICONASTERISK | The encircled i sign | [MessageBox](messagebox.md) |
| MB\_ICONQUESTION | The question sign icon | [MessageBox](messagebox.md) |
| MB\_ICONSTOP,  MB\_ICONERROR,  MB\_ICONHAND | The STOP sign icon | [MessageBox](messagebox.md) |
| MB\_OK | Message window contains only one button: OK. Default | [MessageBox](messagebox.md) |
| MB\_OKCANCEL | Message window contains two buttons: OK and Cancel | [MessageBox](messagebox.md) |
| MB\_RETRYCANCEL | Message window contains two buttons: Retry and Cancel | [MessageBox](messagebox.md) |
| MB\_YESNO | Message window contains two buttons: Yes and No | [MessageBox](messagebox.md) |
| MB\_YESNOCANCEL | Message window contains three buttons: Yes, No and Cancel | [MessageBox](messagebox.md) |
| MINUSDI\_LINE | Line DI | [Indicators Lines](lines.md) |
| MODE\_EMA | Exponential averaging | [Smoothing Methods](enum_ma_method.md) |
| MODE\_LWMA | Linear-weighted averaging | [Smoothing Methods](enum_ma_method.md) |
| MODE\_SMA | Simple averaging | [Smoothing Methods](enum_ma_method.md) |
| MODE\_SMMA | Smoothed averaging | [Smoothing Methods](enum_ma_method.md) |
| MONDAY | Monday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| MQL\_DEBUG | The flag, that indicates the debug mode | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_DLLS\_ALLOWED | The permission to use DLL for the given executed program | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_FRAME\_MODE | The flag, that indicates the Expert Advisor operating in [gathering optimization result frames mode](ontesterpass.md) | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_LICENSE\_TYPE | Type of license of the EX5 module. The license refers to the EX5 module, from which a request is made using MQLInfoInteger(MQL\_LICENSE\_TYPE). | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_MEMORY\_LIMIT | Maximum possible amount of dynamic memory for MQL5 program in MB | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_MEMORY\_USED | The memory size used by MQL5 program in MB | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_OPTIMIZATION | The flag, that indicates the optimization process | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_PROFILER | The flag, that indicates the program operating in the code profiling mode | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_PROGRAM\_NAME | Name of the mql5-program executed | [MQLInfoString](mqlinfostring.md) |
| MQL\_PROGRAM\_PATH | Path for the given executed program | [MQLInfoString](mqlinfostring.md) |
| MQL\_PROGRAM\_TYPE | Type of the mql5 program | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_SIGNALS\_ALLOWED | The permission to modify the Signals for the given executed program | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_TESTER | The flag, that indicates the tester process | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_TRADE\_ALLOWED | The [permission to trade](tradepermission.md) for the given executed program | [MQLInfoInteger](mqlinfointeger.md) |
| MQL\_VISUAL\_MODE | The flag, that indicates the visual tester process | [MQLInfoInteger](mqlinfointeger.md) |
| NULL | Zero for any types | [Other Constants](otherconstants.md) |
| OBJ\_ALL\_PERIODS | The object is drawn in all timeframes | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| [OBJ\_ARROW](obj_arrow.md) | Arrow | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_BUY](obj_arrow_buy.md) | Buy Sign | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_CHECK](obj_arrow_check.md) | Check Sign | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_DOWN](obj_arrow_down.md) | Arrow Down | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_LEFT\_PRICE](obj_arrow_left_price.md) | Left Price Label | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_RIGHT\_PRICE](obj_arrow_right_price.md) | Right Price Label | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_SELL](obj_arrow_sell.md) | Sell Sign | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_STOP](obj_arrow_stop.md) | Stop Sign | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_THUMB\_DOWN](obj_arrow_thumb_down.md) | Thumbs Down | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_THUMB\_UP](obj_arrow_thumb_up.md) | Thumbs Up | [Object Types](enum_object.md) |
| [OBJ\_ARROW\_UP](obj_arrow_up.md) | Arrow Up | [Object Types](enum_object.md) |
| [OBJ\_ARROWED\_LINE](obj_arrowed_line.md) | Arrowed Line | [Object Types](enum_object.md) |
| [OBJ\_BITMAP](obj_bitmap.md) | Bitmap | [Object Types](enum_object.md) |
| [OBJ\_BITMAP\_LABEL](obj_bitmap_label.md) | Bitmap Label | [Object Types](enum_object.md) |
| [OBJ\_BUTTON](obj_button.md) | Button | [Object Types](enum_object.md) |
| [OBJ\_CHANNEL](obj_channel.md) | Equidistant Channel | [Object Types](enum_object.md) |
| [OBJ\_CHART](obj_chart.md) | Chart | [Object Types](enum_object.md) |
| [OBJ\_CYCLES](obj_cycles.md) | Cycle Lines | [Object Types](enum_object.md) |
| [OBJ\_EDIT](obj_edit.md) | Edit | [Object Types](enum_object.md) |
| [OBJ\_ELLIOTWAVE3](obj_elliotwave3.md) | Elliott Correction Wave | [Object Types](enum_object.md) |
| [OBJ\_ELLIOTWAVE5](obj_elliotwave5.md) | Elliott Motive Wave | [Object Types](enum_object.md) |
| [OBJ\_ELLIPSE](obj_ellipse.md) | Ellipse | [Object Types](enum_object.md) |
| [OBJ\_EVENT](obj_event.md) | The "Event" object corresponding to an event in the economic calendar | [Object Types](enum_object.md) |
| [OBJ\_EXPANSION](obj_expansion.md) | Fibonacci Expansion | [Object Types](enum_object.md) |
| [OBJ\_FIBO](obj_fibo.md) | Fibonacci Retracement | [Object Types](enum_object.md) |
| [OBJ\_FIBOARC](obj_fiboarc.md) | Fibonacci Arcs | [Object Types](enum_object.md) |
| [OBJ\_FIBOCHANNEL](obj_fibochannel.md) | Fibonacci Channel | [Object Types](enum_object.md) |
| [OBJ\_FIBOFAN](obj_fibofan.md) | Fibonacci Fan | [Object Types](enum_object.md) |
| [OBJ\_FIBOTIMES](obj_fibotimes.md) | Fibonacci Time Zones | [Object Types](enum_object.md) |
| [OBJ\_GANNFAN](obj_gannfan.md) | Gann Fan | [Object Types](enum_object.md) |
| [OBJ\_GANNGRID](obj_ganngrid.md) | Gann Grid | [Object Types](enum_object.md) |
| [OBJ\_GANNLINE](obj_gannline.md) | Gann Line | [Object Types](enum_object.md) |
| [OBJ\_HLINE](obj_hline.md) | Horizontal Line | [Object Types](enum_object.md) |
| [OBJ\_LABEL](obj_label.md) | Label | [Object Types](enum_object.md) |
| OBJ\_NO\_PERIODS | The object is not drawn in all timeframes | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_D1 | The object is drawn in day charts | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H1 | The object is drawn in 1-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H12 | The object is drawn in 12-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H2 | The object is drawn in 2-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H3 | The object is drawn in 3-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H4 | The object is drawn in 4-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H6 | The object is drawn in 6-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_H8 | The object is drawn in 8-hour chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M1 | The object is drawn in 1-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M10 | The object is drawn in 10-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M12 | The object is drawn in 12-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M15 | The object is drawn in 15-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M2 | The object is drawn in 2-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M20 | The object is drawn in 20-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M3 | The object is drawn in 3-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M30 | The object is drawn in 30-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M4 | The object is drawn in 4-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M5 | The object is drawn in 5-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_M6 | The object is drawn in 6-minute chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_MN1 | The object is drawn in month charts | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJ\_PERIOD\_W1 | The object is drawn in week charts | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| [OBJ\_PITCHFORK](obj_pitchfork.md) | Andrews Pitchfork | [Object Types](enum_object.md) |
| [OBJ\_RECTANGLE](obj_rectangle.md) | Rectangle | [Object Types](enum_object.md) |
| [OBJ\_RECTANGLE\_LABEL](obj_rectangle_label.md) | The "Rectangle label" object for creating and designing the custom graphical interface. | [Object Types](enum_object.md) |
| [OBJ\_REGRESSION](obj_regression.md) | Linear Regression Channel | [Object Types](enum_object.md) |
| [OBJ\_STDDEVCHANNEL](obj_stddevchannel.md) | Standard Deviation Channel | [Object Types](enum_object.md) |
| [OBJ\_TEXT](obj_text.md) | Text | [Object Types](enum_object.md) |
| [OBJ\_TREND](obj_trend.md) | Trend Line | [Object Types](enum_object.md) |
| [OBJ\_TRENDBYANGLE](obj_trendbyangle.md) | Trend Line By Angle | [Object Types](enum_object.md) |
| [OBJ\_TRIANGLE](obj_triangle.md) | Triangle | [Object Types](enum_object.md) |
| [OBJ\_VLINE](obj_vline.md) | Vertical Line | [Object Types](enum_object.md) |
| OBJPROP\_ALIGN | Horizontal text alignment in the "Edit" object (OBJ\_EDIT) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_ANCHOR | Location of the anchor point of a graphical object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_ANGLE | Angle.  For the objects with no angle specified, created from a program, the value is equal to [EMPTY\_VALUE](otherconstants.md) | [ObjectSetDouble](objectsetdouble.md), [ObjectGetDouble](objectgetdouble.md) |
| OBJPROP\_ARROWCODE | Arrow code for the Arrow object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_BACK | Object in the background | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_BGCOLOR | The background color for  OBJ\_EDIT, OBJ\_BUTTON, OBJ\_RECTANGLE\_LABEL | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_BMPFILE | The name of BMP-file for Bitmap Label. See also [Resources](resources.md) | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_BORDER\_COLOR | Border color for the OBJ\_EDIT and OBJ\_BUTTON objects | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_BORDER\_TYPE | Border type for the "Rectangle label" object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_CHART\_ID | ID of the "Chart" object ([OBJ\_CHART](enum_object.md)). It allows working with the properties of this object like with a normal chart using the functions described in [Chart Operations](chart_operations.md), but there some [exceptions](enum_object_property.md#objprop_chart_id_exception). | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_CHART\_SCALE | The scale for the Chart object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_COLOR | Color | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_CORNER | The corner of the chart to link a graphical object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_CREATETIME | Time of object creation | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_DATE\_SCALE | Displaying the time scale for the Chart object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_DEGREE | Level of the Elliott Wave Marking | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_DEVIATION | Deviation for the Standard Deviation Channel | [ObjectSetDouble](objectsetdouble.md), [ObjectGetDouble](objectgetdouble.md) |
| OBJPROP\_DIRECTION | Trend of the Gann object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_DRAWLINES | Displaying lines for marking the Elliott Wave | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_ELLIPSE | Showing the full ellipse of the Fibonacci Arc object ([OBJ\_FIBOARC](enum_object.md)) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_FILL | Fill an object with color (for OBJ\_RECTANGLE, OBJ\_TRIANGLE, OBJ\_ELLIPSE, OBJ\_CHANNEL, OBJ\_STDDEVCHANNEL, OBJ\_REGRESSION) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_FONT | Font | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_FONTSIZE | Font size | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_HIDDEN | Prohibit showing of the name of a graphical object in the list of objects from the terminal menu "Charts" - "Objects" - "List of objects". The true value allows to hide an object from the list. By default, true is set to the objects that display calendar events, trading history and to the objects [created from MQL5 programs](objectcreate.md). To see such [graphical objects](enum_object.md) and access their properties, click on the "All" button in the "List of objects" window. | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_LEVELCOLOR | Color of the line-level | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_LEVELS | Number of levels | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_LEVELSTYLE | Style of the line-level | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_LEVELTEXT | Level description | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_LEVELVALUE | Level value | [ObjectSetDouble](objectsetdouble.md), [ObjectGetDouble](objectgetdouble.md) |
| OBJPROP\_LEVELWIDTH | Thickness of the line-level | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_NAME | Object name | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_PERIOD | Timeframe for the Chart object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_PRICE | Price coordinate | [ObjectSetDouble](objectsetdouble.md), [ObjectGetDouble](objectgetdouble.md) |
| OBJPROP\_PRICE\_SCALE | Displaying the price scale for the Chart object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_RAY | A vertical line goes through all the windows of a chart | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_RAY\_LEFT | Ray goes to the left | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_RAY\_RIGHT | Ray goes to the right | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_READONLY | Ability to edit text in the Edit object | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_SCALE | Scale (properties of Gann objects and Fibonacci Arcs) | [ObjectSetDouble](objectsetdouble.md), [ObjectGetDouble](objectgetdouble.md) |
| OBJPROP\_SELECTABLE | Object availability | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_SELECTED | Object is selected | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_STATE | Button state (pressed / depressed) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_STYLE | Style | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_SYMBOL | Symbol for the Chart object | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_TEXT | Description of the object (the text contained in the object) | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_TIME | Time coordinate | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_TIMEFRAMES | Visibility of an object at timeframes | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_TOOLTIP | The text of a tooltip. If the property is not set, then the tooltip generated automatically by the terminal is shown. A tooltip can be disabled by setting the "\n" (line feed) value to it | [ObjectSetString](objectsetstring.md), [ObjectGetString](objectgetstring.md) |
| OBJPROP\_TYPE | Object type | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_WIDTH | Line thickness | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_XDISTANCE | The distance in pixels along the X axis from the binding corner (see [note](enum_object_property.md#distance_fixedsize)) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_XOFFSET | The X coordinate of the upper left corner of the [rectangular visible area](enum_object_property.md#visual_rectangle) in the graphical objects "Bitmap Label" and "Bitmap" (OBJ\_BITMAP\_LABEL and OBJ\_BITMAP). The value is set in pixels relative to the upper left corner of the original image. | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_XSIZE | The object's width along the X axis in pixels. Specified for  OBJ\_LABEL (read only), OBJ\_BUTTON, OBJ\_CHART, OBJ\_BITMAP, OBJ\_BITMAP\_LABEL, OBJ\_EDIT, OBJ\_RECTANGLE\_LABEL objects. | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_YDISTANCE | The distance in pixels along the Y axis from the binding corner (see [note](enum_object_property.md#distance_fixedsize)) | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_YOFFSET | The Y coordinate of the upper left corner of the [rectangular visible area](enum_object_property.md#visual_rectangle) in the graphical objects "Bitmap Label" and "Bitmap" (OBJ\_BITMAP\_LABEL and OBJ\_BITMAP). The value is set in pixels relative to the upper left corner of the original image. | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_YSIZE | The object's height along the Y axis in pixels. Specified for  OBJ\_LABEL (read only), OBJ\_BUTTON, OBJ\_CHART, OBJ\_BITMAP, OBJ\_BITMAP\_LABEL, OBJ\_EDIT, OBJ\_RECTANGLE\_LABEL objects. | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| OBJPROP\_ZORDER | Priority of a graphical object for receiving events of clicking on a chart ([CHARTEVENT\_CLICK](enum_chartevents.md)). The default zero value is set when creating an object; the priority can be increased if necessary. When applying objects one over another, only one of them with the highest priority will receive the CHARTEVENT\_CLICK event. | [ObjectSetInteger](objectsetinteger.md), [ObjectGetInteger](objectgetinteger.md) |
| ORDER\_COMMENT | Order comment | [OrderGetString](ordergetstring.md), [HistoryOrderGetString](historyordergetstring.md) |
| ORDER\_FILLING\_FOK | This filling policy means that an order can be filled only in the specified amount. If the necessary amount of a financial instrument is currently unavailable in the market, the order will not be executed. The required volume can be filled using several offers available on the market at the moment. | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_FILLING\_IOC | This mode means that a trader agrees to execute a deal with the volume maximally available in the market within that indicated in the order. In case the the entire volume of an order cannot be filled, the available volume of it will be filled, and the remaining volume will be canceled. | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_FILLING\_RETURN | This policy is used only for market orders (ORDER\_TYPE\_BUY and ORDER\_TYPE\_SELL), limit and stop limit orders (ORDER\_TYPE\_BUY\_LIMIT, ORDER\_TYPE\_SELL\_LIMIT, ORDER\_TYPE\_BUY\_STOP\_LIMIT and ORDER\_TYPE\_SELL\_STOP\_LIMIT ) and only for the symbols with Market or Exchange [execution](marketinfoconstants.md#enum_symbol_trade_execution). In case of partial filling a market or limit order with remaining volume is not canceled but processed further.  For the activation of the ORDER\_TYPE\_BUY\_STOP\_LIMIT and ORDER\_TYPE\_SELL\_STOP\_LIMIT orders, a corresponding limit order ORDER\_TYPE\_BUY\_LIMIT/ORDER\_TYPE\_SELL\_LIMIT with the ORDER\_FILLING\_RETURN execution type is created. | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_MAGIC | ID of an Expert Advisor that has placed the order (designed to ensure that each Expert Advisor places its own unique number) | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_POSITION\_ID | [Position identifier](positionproperties.md#enum_position_property_integer) that is set to an order as soon as it is executed. Each executed order results in a [deal](dealproperties.md) that opens or modifies an already existing position. The identifier of exactly this position is set to the executed order at this moment. | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_PRICE\_CURRENT | The current price of the order symbol | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| ORDER\_PRICE\_OPEN | Price specified in the order | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| ORDER\_PRICE\_STOPLIMIT | The Limit order price for the StopLimit order | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| ORDER\_SL | Stop Loss value | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| ORDER\_STATE | Order state | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_CANCELED | Order canceled by client | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_EXPIRED | Order expired | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_FILLED | Order fully executed | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_PARTIAL | Order partially executed | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_PLACED | Order accepted | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_REJECTED | Order rejected | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_REQUEST\_ADD | Order is being registered (placing to the trading system) | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_REQUEST\_CANCEL | Order is being deleted (deleting from the trading system) | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_REQUEST\_MODIFY | Order is being modified (changing its parameters) | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_STATE\_STARTED | Order checked, but not yet accepted by broker | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_SYMBOL | Symbol of the order | [OrderGetString](ordergetstring.md), [HistoryOrderGetString](historyordergetstring.md) |
| ORDER\_TIME\_DAY | Good till current trade day order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_DONE | Order execution or cancellation time | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_DONE\_MSC | Order execution/cancellation time in milliseconds since 01.01.1970 | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_EXPIRATION | Order expiration time | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_GTC | Good till cancel order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_SETUP | Order setup time | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_SETUP\_MSC | The time of placing an order for execution in milliseconds since 01.01.1970 | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_SPECIFIED | Good till expired order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TIME\_SPECIFIED\_DAY | The order will be effective till 23:59:59 of the specified day. If this time is outside a trading session, the order expires in the nearest trading time. | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TP | Take Profit value | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| ORDER\_TYPE | Order type | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_BUY | Market Buy order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_BUY\_LIMIT | Buy Limit pending order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_BUY\_STOP | Buy Stop pending order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_BUY\_STOP\_LIMIT | Upon reaching the order price, a pending Buy Limit order is placed at the StopLimit price | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_FILLING | Order filling type | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_SELL | Market Sell order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_SELL\_LIMIT | Sell Limit pending order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_SELL\_STOP | Sell Stop pending order | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_SELL\_STOP\_LIMIT | Upon reaching the order price, a pending Sell Limit order is placed at the StopLimit price | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_TYPE\_TIME | Order lifetime | [OrderGetInteger](ordergetinteger.md), [HistoryOrderGetInteger](historyordergetinteger.md) |
| ORDER\_VOLUME\_CURRENT | Order current volume | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| ORDER\_VOLUME\_INITIAL | Order initial volume | [OrderGetDouble](ordergetdouble.md), [HistoryOrderGetDouble](historyordergetdouble.md) |
| PERIOD\_CURRENT | Current timeframe | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_D1 | 1 day | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H1 | 1 hour | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H12 | 12 hours | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H2 | 2 hours | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H3 | 3 hours | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H4 | 4 hours | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H6 | 6 hours | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_H8 | 8 hours | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M1 | 1 minute | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M10 | 10 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M12 | 12 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M15 | 15 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M2 | 2 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M20 | 20 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M3 | 3 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M30 | 30 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M4 | 4 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M5 | 5 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_M6 | 6 minutes | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_MN1 | 1 month | [Chart Timeframes](enum_timeframes.md) |
| PERIOD\_W1 | 1 week | [Chart Timeframes](enum_timeframes.md) |
| PLOT\_ARROW | Arrow code for style DRAW\_ARROW | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_ARROW\_SHIFT | Vertical shift of arrows for style DRAW\_ARROW | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_COLOR\_INDEXES | The number of colors | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_DRAW\_BEGIN | Number of initial bars without drawing and values in the DataWindow | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_DRAW\_TYPE | Type of graphical construction | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_EMPTY\_VALUE | An empty value for plotting, for which there is no drawing | [PlotIndexSetDouble](plotindexsetdouble.md) |
| PLOT\_LABEL | The name of the indicator graphical series to display in the DataWindow. When working with complex graphical styles requiring several indicator buffers for display, the names for each buffer can be specified using ";" as a separator. Sample code is shown in [DRAW\_CANDLES](draw_candles.md) | [PlotIndexSetString](plotindexsetstring.md) |
| PLOT\_LINE\_COLOR | The index of a buffer containing the drawing color | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_LINE\_STYLE | Drawing line style | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_LINE\_WIDTH | The thickness of the drawing line | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_SHIFT | Shift of indicator plotting along the time axis in bars | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLOT\_SHOW\_DATA | Sign of display of construction values in the DataWindow | [PlotIndexSetInteger](plotindexsetinteger.md), [PlotIndexGetInteger](plotindexgetinteger.md) |
| PLUSDI\_LINE | Line +DI | [Indicators Lines](lines.md) |
| POINTER\_AUTOMATIC | Pointer of any objects created automatically (not using new()) | [CheckPointer](checkpointer.md) |
| POINTER\_DYNAMIC | Pointer of the object created by the [new()](newoperator.md) operator | [CheckPointer](checkpointer.md) |
| POINTER\_INVALID | Incorrect pointer | [CheckPointer](checkpointer.md) |
| POSITION\_COMMENT | Position comment | [PositionGetString](positiongetstring.md) |
| POSITION\_COMMISSION | Commission | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_IDENTIFIER | Position identifier is a unique number that is assigned to every newly opened position and doesn't change during the entire lifetime of the position. Position turnover doesn't change its identifier. | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_MAGIC | Position magic number (see [ORDER\_MAGIC](orderproperties.md)) | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_PRICE\_CURRENT | Current price of the position symbol | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_PRICE\_OPEN | Position open price | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_PROFIT | Current profit | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_SL | Stop Loss level of opened position | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_SWAP | Cumulative swap | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_SYMBOL | Symbol of the position | [PositionGetString](positiongetstring.md) |
| POSITION\_TIME | Position open time | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_TIME\_MSC | Position opening time in milliseconds since 01.01.1970 | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_TIME\_UPDATE | Position changing time in seconds since 01.01.1970 | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_TIME\_UPDATE\_MSC | Position changing time in milliseconds since 01.01.1970 | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_TP | Take Profit level of opened position | [PositionGetDouble](positiongetdouble.md) |
| POSITION\_TYPE | Position type | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_TYPE\_BUY | Buy | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_TYPE\_SELL | Sell | [PositionGetInteger](positiongetinteger.md) |
| POSITION\_VOLUME | Position volume | [PositionGetDouble](positiongetdouble.md) |
| PRICE\_CLOSE | Close price | [Price Constants](prices.md) |
| PRICE\_HIGH | The maximum price for the period | [Price Constants](prices.md) |
| PRICE\_LOW | The minimum price for the period | [Price Constants](prices.md) |
| PRICE\_MEDIAN | Median price, (high + low)/2 | [Price Constants](prices.md) |
| PRICE\_OPEN | Open price | [Price Constants](prices.md) |
| PRICE\_TYPICAL | Typical price, (high + low + close)/3 | [Price Constants](prices.md) |
| PRICE\_WEIGHTED | Average price, (high + low + close + close)/4 | [Price Constants](prices.md) |
| PROGRAM\_EXPERT | Expert | [MQLInfoInteger](mqlinfointeger.md) |
| PROGRAM\_INDICATOR | Indicator | [MQLInfoInteger](mqlinfointeger.md) |
| PROGRAM\_SCRIPT | Script | [MQLInfoInteger](mqlinfointeger.md) |
| REASON\_ACCOUNT | Another account has been activated or reconnection to the trade server has occurred due to changes in the account settings | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_CHARTCHANGE | Symbol or chart period has been changed | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_CHARTCLOSE | Chart has been closed | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_CLOSE | Terminal has been closed | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_INITFAILED | This value means that [OnInit()](oninit.md) handler has returned a nonzero value | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_PARAMETERS | Input parameters have been changed by a user | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_PROGRAM | Expert Advisor terminated its operation by calling the [ExpertRemove()](expertremove.md) function | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_RECOMPILE | Program has been recompiled | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_REMOVE | Program has been deleted from the chart | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| REASON\_TEMPLATE | A new template has been applied | [UninitializeReason](uninitializereason.md), [OnDeinit](ondeinit.md) |
| SATURDAY | Saturday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| SEEK\_CUR | Current position of a file pointer | [FileSeek](fileseek.md) |
| SEEK\_END | File end | [FileSeek](fileseek.md) |
| SEEK\_SET | File beginning | [FileSeek](fileseek.md) |
| SENKOUSPANA\_LINE | Senkou Span A line | [Indicators Lines](lines.md) |
| SENKOUSPANB\_LINE | Senkou Span B line | [Indicators Lines](lines.md) |
| SERIES\_BARS\_COUNT | Bars count for the symbol-period for the current moment | [SeriesInfoInteger](seriesinfointeger.md) |
| SERIES\_FIRSTDATE | The very first date for the symbol-period for the current moment | [SeriesInfoInteger](seriesinfointeger.md) |
| SERIES\_LASTBAR\_DATE | Open time of the last bar of the symbol-period | [SeriesInfoInteger](seriesinfointeger.md) |
| SERIES\_SERVER\_FIRSTDATE | The very first date in the history of the symbol on the server regardless of the timeframe | [SeriesInfoInteger](seriesinfointeger.md) |
| SERIES\_SYNCHRONIZED | Symbol/period data synchronization flag for the current moment | [SeriesInfoInteger](seriesinfointeger.md) |
| SERIES\_TERMINAL\_FIRSTDATE | The very first date in the history of the symbol in the client terminal, regardless of the timeframe | [SeriesInfoInteger](seriesinfointeger.md) |
| SHORT\_MAX | Maximal value, which can be represented by short type | [Numerical Type Constants](typeconstants.md) |
| SHORT\_MIN | Minimal value, which can be represented by short type | [Numerical Type Constants](typeconstants.md) |
| SIGNAL\_BASE\_AUTHOR\_LOGIN | Author login | [SignalBaseGetString](signalbasegetstring.md) |
| SIGNAL\_BASE\_BALANCE | Account balance | [SignalBaseGetDouble](signalbasegetdouble.md) |
| SIGNAL\_BASE\_BROKER | Broker name (company) | [SignalBaseGetString](signalbasegetstring.md) |
| SIGNAL\_BASE\_BROKER\_SERVER | Broker server | [SignalBaseGetString](signalbasegetstring.md) |
| SIGNAL\_BASE\_CURRENCY | Signal base currency | [SignalBaseGetString](signalbasegetstring.md) |
| SIGNAL\_BASE\_DATE\_PUBLISHED | Publication date (date when it become available for subscription) | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_DATE\_STARTED | Monitoring starting date | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_EQUITY | Account equity | [SignalBaseGetDouble](signalbasegetdouble.md) |
| SIGNAL\_BASE\_GAIN | Account gain | [SignalBaseGetDouble](signalbasegetdouble.md) |
| SIGNAL\_BASE\_ID | Signal ID | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_LEVERAGE | Account leverage | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_MAX\_DRAWDOWN | Account maximum drawdown | [SignalBaseGetDouble](signalbasegetdouble.md) |
| SIGNAL\_BASE\_NAME | Signal name | [SignalBaseGetString](signalbasegetstring.md) |
| SIGNAL\_BASE\_PIPS | Profit in pips | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_PRICE | Signal subscription price | [SignalBaseGetDouble](signalbasegetdouble.md) |
| SIGNAL\_BASE\_RATING | Position in rating | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_ROI | Return on Investment (%) | [SignalBaseGetDouble](signalbasegetdouble.md) |
| SIGNAL\_BASE\_SUBSCRIBERS | Number of subscribers | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_TRADE\_MODE | Account type (0-real, 1-demo, 2-contest) | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_BASE\_TRADES | Number of trades | [SignalBaseGetInteger](signalbasegetinteger.md) |
| SIGNAL\_INFO\_CONFIRMATIONS\_DISABLED | The flag enables synchronization without confirmation dialog | [SignalInfoGetInteger](signalinfogetinteger.md), [SignalInfoSetInteger](signalinfosetinteger.md) |
| SIGNAL\_INFO\_COPY\_SLTP | Copy Stop Loss and Take Profit flag | [SignalInfoGetInteger](signalinfogetinteger.md), [SignalInfoSetInteger](signalinfosetinteger.md) |
| SIGNAL\_INFO\_DEPOSIT\_PERCENT | Deposit percent (%) | [SignalInfoGetInteger](signalinfogetinteger.md), [SignalInfoSetInteger](signalinfosetinteger.md) |
| SIGNAL\_INFO\_EQUITY\_LIMIT | Equity limit | [SignalInfoGetDouble](signalinfogetdouble.md), [SignalInfoSetDouble](signalinfosetdouble.md) |
| SIGNAL\_INFO\_ID | Signal id, r/o | [SignalInfoGetInteger](signalinfogetinteger.md), [SignalInfoSetInteger](signalinfosetinteger.md) |
| SIGNAL\_INFO\_NAME | Signal name, r/o | [SignalInfoGetString](signalinfogetstring.md) |
| SIGNAL\_INFO\_SLIPPAGE | Slippage (used when placing market orders in synchronization of positions and copying of trades) | [SignalInfoGetDouble](signalinfogetdouble.md), [SignalInfoSetDouble](signalinfosetdouble.md) |
| SIGNAL\_INFO\_SUBSCRIPTION\_ENABLED | "Copy trades by subscription" permission flag | [SignalInfoGetInteger](signalinfogetinteger.md), [SignalInfoSetInteger](signalinfosetinteger.md) |
| SIGNAL\_INFO\_TERMS\_AGREE | "Agree to terms of use of Signals service" flag, r/o | [SignalInfoGetInteger](signalinfogetinteger.md), [SignalInfoSetInteger](signalinfosetinteger.md) |
| SIGNAL\_INFO\_VOLUME\_PERCENT | Maximum percent of deposit used (%), r/o | [SignalInfoGetDouble](signalinfogetdouble.md), [SignalInfoSetDouble](signalinfosetdouble.md) |
| SIGNAL\_LINE | Signal line | [Indicators Lines](lines.md) |
| STAT\_BALANCE\_DD | Maximum balance drawdown in monetary terms. In the process of trading, a balance may have numerous drawdowns; here the largest value is taken | [TesterStatistics](testerstatistics.md) |
| STAT\_BALANCE\_DD\_RELATIVE | Balance drawdown in monetary terms that was recorded at the moment of the maximum balance drawdown as a percentage (STAT\_BALANCE\_DDREL\_PERCENT). | [TesterStatistics](testerstatistics.md) |
| STAT\_BALANCE\_DDREL\_PERCENT | Maximum balance drawdown as a percentage. In the process of trading, a balance may have numerous drawdowns, for each of which the relative drawdown value in percents is calculated. The greatest value is returned | [TesterStatistics](testerstatistics.md) |
| STAT\_BALANCEDD\_PERCENT | Balance drawdown as a percentage that was recorded at the moment of the maximum balance drawdown in monetary terms (STAT\_BALANCE\_DD). | [TesterStatistics](testerstatistics.md) |
| STAT\_BALANCEMIN | Minimum balance value | [TesterStatistics](testerstatistics.md) |
| STAT\_CONLOSSMAX | Maximum loss in a series of losing trades. The value is less than or equal to zero | [TesterStatistics](testerstatistics.md) |
| STAT\_CONLOSSMAX\_TRADES | The number of trades that have formed STAT\_CONLOSSMAX (maximum loss in a series of losing trades) | [TesterStatistics](testerstatistics.md) |
| STAT\_CONPROFITMAX | Maximum profit in a series of profitable trades. The value is greater than or equal to zero | [TesterStatistics](testerstatistics.md) |
| STAT\_CONPROFITMAX\_TRADES | The number of trades that have formed STAT\_CONPROFITMAX (maximum profit in a series of profitable trades) | [TesterStatistics](testerstatistics.md) |
| STAT\_CUSTOM\_ONTESTER | The value of the calculated custom optimization criterion returned by the [OnTester()](ontester.md) function | [TesterStatistics](testerstatistics.md) |
| STAT\_DEALS | The number of deals | [TesterStatistics](testerstatistics.md) |
| STAT\_EQUITY\_DD | Maximum equity drawdown in monetary terms. In the process of trading, numerous drawdowns may appear on the equity; here the largest value is taken | [TesterStatistics](testerstatistics.md) |
| STAT\_EQUITY\_DD\_RELATIVE | Equity drawdown in monetary terms that was recorded at the moment of the maximum equity drawdown in percent (STAT\_EQUITY\_DDREL\_PERCENT). | [TesterStatistics](testerstatistics.md) |
| STAT\_EQUITY\_DDREL\_PERCENT | Maximum equity drawdown as a percentage. In the process of trading, an equity may have numerous drawdowns, for each of which the relative drawdown value in percents is calculated. The greatest value is returned | [TesterStatistics](testerstatistics.md) |
| STAT\_EQUITYDD\_PERCENT | Drawdown in percent that was recorded at the moment of the maximum equity drawdown in monetary terms (STAT\_EQUITY\_DD). | [TesterStatistics](testerstatistics.md) |
| STAT\_EQUITYMIN | Minimum equity value | [TesterStatistics](testerstatistics.md) |
| STAT\_EXPECTED\_PAYOFF | Expected payoff | [TesterStatistics](testerstatistics.md) |
| STAT\_GROSS\_LOSS | Total loss, the sum of all negative trades. The value is less than or equal to zero | [TesterStatistics](testerstatistics.md) |
| STAT\_GROSS\_PROFIT | Total profit, the sum of all profitable (positive) trades. The value is greater than or equal to zero | [TesterStatistics](testerstatistics.md) |
| STAT\_INITIAL\_DEPOSIT | The value of the initial deposit | [TesterStatistics](testerstatistics.md) |
| STAT\_LONG\_TRADES | Long trades | [TesterStatistics](testerstatistics.md) |
| STAT\_LOSS\_TRADES | Losing trades | [TesterStatistics](testerstatistics.md) |
| STAT\_LOSSTRADES\_AVGCON | Average length of a losing series of trades | [TesterStatistics](testerstatistics.md) |
| STAT\_MAX\_CONLOSS\_TRADES | The number of trades in the longest series of losing trades STAT\_MAX\_CONLOSSES | [TesterStatistics](testerstatistics.md) |
| STAT\_MAX\_CONLOSSES | The total loss of the longest series of losing trades | [TesterStatistics](testerstatistics.md) |
| STAT\_MAX\_CONPROFIT\_TRADES | The number of trades in the longest series of profitable trades STAT\_MAX\_CONWINS | [TesterStatistics](testerstatistics.md) |
| STAT\_MAX\_CONWINS | The total profit of the longest series of profitable trades | [TesterStatistics](testerstatistics.md) |
| STAT\_MAX\_LOSSTRADE | Maximum loss the lowest value of all losing trades. The value is less than or equal to zero | [TesterStatistics](testerstatistics.md) |
| STAT\_MAX\_PROFITTRADE | Maximum profit the largest value of all profitable trades. The value is greater than or equal to zero | [TesterStatistics](testerstatistics.md) |
| STAT\_MIN\_MARGINLEVEL | Minimum value of the margin level | [TesterStatistics](testerstatistics.md) |
| STAT\_PROFIT | Net profit after testing, the sum of STAT\_GROSS\_PROFIT and STAT\_GROSS\_LOSS (STAT\_GROSS\_LOSS is always less than or equal to zero) | [TesterStatistics](testerstatistics.md) |
| STAT\_PROFIT\_FACTOR | Profit factor, equal to  the ratio of STAT\_GROSS\_PROFIT/STAT\_GROSS\_LOSS. If STAT\_GROSS\_LOSS=0, the profit factor is equal to [DBL\_MAX](typeconstants.md) | [TesterStatistics](testerstatistics.md) |
| STAT\_PROFIT\_LONGTRADES | Profitable long trades | [TesterStatistics](testerstatistics.md) |
| STAT\_PROFIT\_SHORTTRADES | Profitable short trades | [TesterStatistics](testerstatistics.md) |
| STAT\_PROFIT\_TRADES | Profitable trades | [TesterStatistics](testerstatistics.md) |
| STAT\_PROFITTRADES\_AVGCON | Average length of a profitable series of trades | [TesterStatistics](testerstatistics.md) |
| STAT\_RECOVERY\_FACTOR | Recovery factor, equal to the ratio of STAT\_PROFIT/STAT\_BALANCE\_DD | [TesterStatistics](testerstatistics.md) |
| STAT\_SHARPE\_RATIO | Sharpe ratio | [TesterStatistics](testerstatistics.md) |
| STAT\_SHORT\_TRADES | Short trades | [TesterStatistics](testerstatistics.md) |
| STAT\_TRADES | The number of trades | [TesterStatistics](testerstatistics.md) |
| STAT\_WITHDRAWAL | Money withdrawn from an account | [TesterStatistics](testerstatistics.md) |
| STO\_CLOSECLOSE | Calculation is based on Close/Close prices | [Price Constants](prices.md) |
| STO\_LOWHIGH | Calculation is based on Low/High prices | [Price Constants](prices.md) |
| STYLE\_DASH | Broken line | [Drawing Styles](drawstyles.md#enum_line_style) |
| STYLE\_DASHDOT | Dash-dot line | [Drawing Styles](drawstyles.md#enum_line_style) |
| STYLE\_DASHDOTDOT | Dash - two points | [Drawing Styles](drawstyles.md#enum_line_style) |
| STYLE\_DOT | Dotted line | [Drawing Styles](drawstyles.md#enum_line_style) |
| STYLE\_SOLID | Solid line | [Drawing Styles](drawstyles.md#enum_line_style) |
| SUNDAY | Sunday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| SYMBOL\_ASK | Ask - best buy offer | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_ASKHIGH | Maximal Ask of the day | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_ASKLOW | Minimal Ask of the day | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_BANK | Feeder of the current quote | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_BASIS | The underlying asset of a derivative | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_BID | Bid - best sell offer | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_BIDHIGH | Maximal Bid of the day | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_BIDLOW | Minimal Bid of the day | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_CALC\_MODE\_CFD | CFD mode - calculation of margin and profit for CFD | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_CFDINDEX | CFD index mode - calculation of margin and profit for CFD by indexes | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_CFDLEVERAGE | CFD Leverage mode - calculation of margin and profit for CFD at leverage trading | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_EXCH\_FUTURES | Futures mode  calculation of margin and profit for trading futures contracts on a stock exchange | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_EXCH\_FUTURES\_FORTS | FORTS Futures mode  calculation of margin and profit for trading futures contracts on FORTS. | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_EXCH\_STOCKS | Exchange mode calculation of margin and profit for trading securities on a stock exchange | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_FOREX | Forex mode - calculation of profit and margin for Forex | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_FUTURES | Futures mode - calculation of margin and profit for futures | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CALC\_MODE\_SERV\_COLLATERAL | Collateral mode - a symbol is used as a non-tradable asset on a trading account. | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_CURRENCY\_BASE | Basic currency of a symbol | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_CURRENCY\_MARGIN | Margin currency | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_CURRENCY\_PROFIT | Profit currency | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_DESCRIPTION | Symbol description | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_DIGITS | Digits after a decimal point | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_EXPIRATION\_DAY | The order is valid till the end of the day | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_EXPIRATION\_GTC | The order is valid during the unlimited time period, until it is explicitly canceled | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_EXPIRATION\_MODE | Flags of allowed order [expiration modes](marketinfoconstants.md#symbol_expiration_mode) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_EXPIRATION\_SPECIFIED | The expiration time is specified in the order | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_EXPIRATION\_SPECIFIED\_DAY | The expiration date is specified in the order | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_EXPIRATION\_TIME | Date of the symbol trade end (usually used for futures) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_FILLING\_FOK | This policy means that a deal can be executed only with the specified volume. If the necessary amount of a financial instrument is currently unavailable in the market, the order will not be executed. The required volume can be filled using several offers available on the market at the moment. | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_FILLING\_IOC | In this case a trader agrees to execute a deal with the volume maximally available in the market within that indicated in the order. In case the order cannot be filled completely, the available volume of the order will be filled, and the remaining volume will be canceled. The possibility of using IOC orders is determined at the trade server. | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_FILLING\_MODE | Flags of allowed order [filling modes](marketinfoconstants.md#symbol_filling_mode) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ISIN | The name of a symbol in the ISIN system (International Securities Identification Number). The International Securities Identification Number is a 12-digit alphanumeric code that uniquely identifies a security. The presence of this symbol property is determined on the side of a trade server. | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_LAST | Price of the last deal | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_LASTHIGH | Maximal Last of the day | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_LASTLOW | Minimal Last of the day | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_MARGIN\_INITIAL | Initial margin means the amount in the margin currency required for opening a position with the volume of one lot. It is used for checking a client's assets when he or she enters the market. | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_MARGIN\_MAINTENANCE | The maintenance margin. If it is set, it sets the margin amount in the margin currency of the symbol, charged from one lot. It is used for checking a client's assets when his/her account state changes. If the maintenance margin is equal to 0, the initial margin is used. | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_OPTION\_MODE | Option type | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_OPTION\_MODE\_EUROPEAN | European option may only be exercised on a specified date (expiration, execution date, delivery date) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_OPTION\_MODE\_AMERICAN | American option may be exercised on any trading day on or before expiry. The period within which a buyer can exercise the option is specified for it | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_OPTION\_RIGHT | Option right (Call/Put) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_OPTION\_RIGHT\_CALL | A call option gives you the right to buy an asset at a specified price | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_OPTION\_RIGHT\_PUT | A put option gives you the right to sell an asset at a specified price | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_OPTION\_STRIKE | The strike price of an option. The price at which an option buyer can buy (in a Call option) or sell (in a Put option) the underlying asset, and the option seller is obliged to sell or buy the appropriate amount of the underlying asset. | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_ORDER\_LIMIT | Limit orders are allowed (Buy Limit and Sell Limit) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ORDER\_MARKET | Market orders are allowed (Buy and Sell) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ORDER\_MODE | Flags of allowed [order types](marketinfoconstants.md#symbol_order_mode) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ORDER\_SL | Stop Loss is allowed | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ORDER\_STOP | Stop orders are allowed (Buy Stop and Sell Stop) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ORDER\_STOP\_LIMIT | Stop-limit orders are allowed (Buy Stop Limit and Sell Stop Limit) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_ORDER\_TP | Take Profit is allowed | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_PATH | Path in the symbol tree | [SymbolInfoString](symbolinfostring.md) |
| SYMBOL\_POINT | Symbol point value | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SELECT | Symbol is selected in Market Watch | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SESSION\_AW | Average weighted price of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_BUY\_ORDERS | Number of Buy orders at the moment | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SESSION\_BUY\_ORDERS\_VOLUME | Current volume of Buy orders | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_CLOSE | Close price of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_DEALS | Number of deals in the current session | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SESSION\_INTEREST | Summary open interest | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_OPEN | Open price of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_PRICE\_LIMIT\_MAX | Maximal price of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_PRICE\_LIMIT\_MIN | Minimal price of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_PRICE\_SETTLEMENT | Settlement price of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_SELL\_ORDERS | Number of Sell orders at the moment | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SESSION\_SELL\_ORDERS\_VOLUME | Current volume of Sell orders | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_TURNOVER | Summary turnover of the current session | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SESSION\_VOLUME | Summary volume of current session deals | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SPREAD | Spread value in points | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SPREAD\_FLOAT | Indication of a floating spread | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_START\_TIME | Date of the symbol trade beginning (usually used for futures) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_LONG | Long swap value | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_SWAP\_MODE | Swap calculation model | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_CURRENCY\_DEPOSIT | Swaps are charged in money, in client deposit currency | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_CURRENCY\_MARGIN | Swaps are charged in money in margin currency of the symbol | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_CURRENCY\_SYMBOL | Swaps are charged in money in base currency of the symbol | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_DISABLED | Swaps disabled (no swaps) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_INTEREST\_CURRENT | Swaps are charged as the specified annual interest from the instrument price at calculation of swap (standard bank year is 360 days) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_INTEREST\_OPEN | Swaps are charged as the specified annual interest from the open price of position (standard bank year is 360 days) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_POINTS | Swaps are charged in points | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_REOPEN\_BID | Swaps are charged by reopening positions. At the end of a trading day the position is closed. Next day it is reopened by the current Bid price +/- specified number of points (parameters SYMBOL\_SWAP\_LONG and SYMBOL\_SWAP\_SHORT) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_MODE\_REOPEN\_CURRENT | Swaps are charged by reopening positions. At the end of a trading day the position is closed. Next day it is reopened by the close price +/- specified number of points (parameters SYMBOL\_SWAP\_LONG and SYMBOL\_SWAP\_SHORT) | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_ROLLOVER3DAYS | Day of week to charge 3 days swap rollover | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_SWAP\_SHORT | Short swap value | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_TICKS\_BOOKDEPTH | Maximal number of requests shown in [Depth of Market](marketbookget.md). For symbols that have no queue of requests, the value is equal to zero. | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TIME | Time of the last quote | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_CALC\_MODE | Contract price calculation mode | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_CONTRACT\_SIZE | Trade contract size | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_TRADE\_EXECUTION\_EXCHANGE | Exchange execution | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_EXECUTION\_INSTANT | Instant execution | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_EXECUTION\_MARKET | Market execution | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_EXECUTION\_REQUEST | Execution by request | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_EXEMODE | Deal execution mode | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_FREEZE\_LEVEL | Distance to freeze trade operations in points | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_MODE | Order execution type | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_MODE\_CLOSEONLY | Allowed only position close operations | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_MODE\_DISABLED | Trade is disabled for the symbol | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_MODE\_FULL | No trade restrictions | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_MODE\_LONGONLY | Allowed only long positions | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_MODE\_SHORTONLY | Allowed only short positions | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_STOPS\_LEVEL | Minimal indention in points from the current close price to place Stop orders | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_TRADE\_TICK\_SIZE | Minimal price change | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_TRADE\_TICK\_VALUE | Value of SYMBOL\_TRADE\_TICK\_VALUE\_PROFIT | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_TRADE\_TICK\_VALUE\_LOSS | Calculated tick price for a losing position | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_TRADE\_TICK\_VALUE\_PROFIT | Calculated tick price for a profitable position | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_VOLUME | Volume of the last deal | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_VOLUME\_LIMIT | Maximum allowed aggregate volume of an open position and pending orders in one direction (buy or sell) for the symbol. For example, with the limitation of 5 lots, you can have an open buy position with the volume of 5 lots and place a pending order Sell Limit with the volume of 5 lots. But in this case you cannot place a Buy Limit pending order (since the total volume in one direction will exceed the limitation) or place Sell Limit with the volume more than 5 lots. | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_VOLUME\_MAX | Maximal volume for a deal | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_VOLUME\_MIN | Minimal volume for a deal | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_VOLUME\_STEP | Minimal volume change step for deal execution | [SymbolInfoDouble](symbolinfodouble.md) |
| SYMBOL\_VOLUMEHIGH | Maximal day volume | [SymbolInfoInteger](symbolinfointeger.md) |
| SYMBOL\_VOLUMELOW | Minimal day volume | [SymbolInfoInteger](symbolinfointeger.md) |
| TENKANSEN\_LINE | Tenkan-sen line | [Indicators Lines](lines.md) |
| TERMINAL\_BUILD | The client terminal build number | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_CODEPAGE | Number of [the code page of the language](codepageusage.md) installed in the client terminal | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_COMMONDATA\_PATH | Common path for all of the terminals installed on a computer | [TerminalInfoString](terminalinfostring.md) |
| TERMINAL\_COMMUNITY\_ACCOUNT | The flag indicates the presence of MQL5.community authorization data in the terminal | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_COMMUNITY\_BALANCE | Balance in MQL5.community | [TerminalInfoDouble](terminalinfodouble.md) |
| TERMINAL\_COMMUNITY\_CONNECTION | Connection to MQL5.community | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_COMPANY | Company name | [TerminalInfoString](terminalinfostring.md) |
| TERMINAL\_CONNECTED | Connection to a trade server | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_CPU\_CORES | The number of CPU cores in the system | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_DATA\_PATH | Folder in which terminal data are stored | [TerminalInfoString](terminalinfostring.md) |
| TERMINAL\_DISK\_SPACE | Free disk space for the MQL5\Files folder of the terminal (agent), MB | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_DLLS\_ALLOWED | Permission to use DLL | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_EMAIL\_ENABLED | Permission to send e-mails using SMTP-server and login, specified in the terminal settings | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_FTP\_ENABLED | Permission to send reports using FTP-server and login, specified in the terminal settings | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_LANGUAGE | Language of the terminal | [TerminalInfoString](terminalinfostring.md) |
| TERMINAL\_MAXBARS | The maximal bars count on the chart | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_MEMORY\_AVAILABLE | Free memory of the terminal (agent) process, MB | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_MEMORY\_PHYSICAL | Physical memory in the system, MB | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_MEMORY\_TOTAL | Memory available to the process of the terminal (agent), MB | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_MEMORY\_USED | Memory used by the terminal (agent), MB | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_MQID | The flag indicates the presence of MetaQuotes ID data for [Push notifications](sendnotification.md) | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_NAME | Terminal name | [TerminalInfoString](terminalinfostring.md) |
| TERMINAL\_NOTIFICATIONS\_ENABLED | Permission to send notifications to smartphone | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_OPENCL\_SUPPORT | The version of the supported OpenCL in the format of 0x00010002 = 1.2.  "0" means that OpenCL is not supported | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_PATH | Folder from which the terminal is started | [TerminalInfoString](terminalinfostring.md) |
| TERMINAL\_PING\_LAST | The last known value of a ping to a trade server in microseconds. One second comprises of one million microseconds | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_SCREEN\_DPI | The resolution of information display on the screen is measured as number of Dots in a line per Inch (DPI). | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_TRADE\_ALLOWED | [Permission to trade](tradepermission.md) | [TerminalInfoInteger](terminalinfointeger.md) |
| TERMINAL\_X64 | Indication of the "64-bit terminal" | [TerminalInfoInteger](terminalinfointeger.md) |
| THURSDAY | Thursday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| TRADE\_ACTION\_DEAL | Place a trade order for an immediate execution with the specified parameters (market order) | [MqlTradeRequest](mqltraderequest.md) |
| TRADE\_ACTION\_MODIFY | Modify the parameters of the order placed previously | [MqlTradeRequest](mqltraderequest.md) |
| TRADE\_ACTION\_PENDING | Place a trade order for the execution under specified conditions (pending order) | [MqlTradeRequest](mqltraderequest.md) |
| TRADE\_ACTION\_REMOVE | Delete the pending order placed previously | [MqlTradeRequest](mqltraderequest.md) |
| TRADE\_ACTION\_SLTP | Modify Stop Loss and Take Profit values of an opened position | [MqlTradeRequest](mqltraderequest.md) |
| TRADE\_RETCODE\_CANCEL | Request canceled by trader | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_CLIENT\_DISABLES\_AT | Autotrading disabled by client terminal | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_CONNECTION | No connection with the trade server | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_DONE | Request completed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_DONE\_PARTIAL | Only part of the request was completed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_ERROR | Request processing error | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_FROZEN | Order or position frozen | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID | Invalid request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID\_EXPIRATION | Invalid order expiration date in the request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID\_FILL | Invalid [order filling type](orderproperties.md#enum_order_type_filling) | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID\_ORDER | Incorrect or prohibited [order type](orderproperties.md#enum_order_type) | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID\_PRICE | Invalid price in the request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID\_STOPS | Invalid stops in the request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_INVALID\_VOLUME | Invalid volume in the request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_LIMIT\_ORDERS | The number of pending orders has reached the limit | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_LIMIT\_VOLUME | The volume of orders and positions for the symbol has reached the limit | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_LOCKED | Request locked for processing | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_MARKET\_CLOSED | Market is closed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_NO\_CHANGES | No changes in request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_NO\_MONEY | There is not enough money to complete the request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_ONLY\_REAL | Operation is allowed only for live accounts | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_ORDER\_CHANGED | Order state changed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_PLACED | Order placed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_POSITION\_CLOSED | Position with the specified [POSITION\_IDENTIFIER](positionproperties.md#enum_position_property_integer) has already been closed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_PRICE\_CHANGED | Prices changed | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_PRICE\_OFF | There are no quotes to process the request | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_REJECT | Request rejected | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_REQUOTE | Requote | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_SERVER\_DISABLES\_AT | Autotrading disabled by server | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_TIMEOUT | Request canceled by timeout | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_TOO\_MANY\_REQUESTS | Too frequent requests | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_RETCODE\_TRADE\_DISABLED | Trade is disabled | [MqlTradeResult](mqltraderesult.md) |
| TRADE\_TRANSACTION\_DEAL\_ADD | Adding a deal to the history. The action is performed as a result of an order execution or performing operations with an account balance. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_DEAL\_DELETE | Deleting a deal from the history. There may be cases when a previously executed deal is deleted from a server. For example, a deal has been deleted in an external trading system (exchange) where it was previously transferred by a broker. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_DEAL\_UPDATE | Updating a deal in the history. There may be cases when a previously executed deal is changed on a server. For example, a deal has been changed in an external trading system (exchange) where it was previously transferred by a broker. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_HISTORY\_ADD | Adding an order to the history as a result of execution or cancellation. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_HISTORY\_DELETE | Deleting an order from the orders history. This type is provided for enhancing functionality on a trade server side. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_HISTORY\_UPDATE | Changing an order located in the orders history. This type is provided for enhancing functionality on a trade server side. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_ORDER\_ADD | Adding a new open order. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_ORDER\_DELETE | Removing an order from the list of the open ones. An order can be deleted from the open ones as a result of setting an appropriate request or execution (filling) and moving to the history. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_ORDER\_UPDATE | Updating an open order. The updates include not only evident changes from the client terminal or a trade server sides but also changes of an order state when setting it (for example, transition from [ORDER\_STATE\_STARTED](orderproperties.md#enum_order_state) to [ORDER\_STATE\_PLACED](orderproperties.md#enum_order_state) or from [ORDER\_STATE\_PLACED](orderproperties.md#enum_order_state) to [ORDER\_STATE\_PARTIAL](orderproperties.md#enum_order_state), etc.). | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_POSITION | Changing a position not related to a deal execution. This type of transaction shows that a position has been changed on a trade server side. Position volume, open price, Stop Loss and Take Profit levels can be changed. Data on changes are submitted in [MqlTradeTransaction](mqltradetransaction.md) structure via OnTradeTransaction handler. Position change (adding, changing or closing), as a result of a deal execution, does not lead to the occurrence of TRADE\_TRANSACTION\_POSITION transaction. | [MqlTradeTransaction](mqltradetransaction.md) |
| TRADE\_TRANSACTION\_REQUEST | Notification of the fact that a trade request has been processed by a server and processing result has been received. Only type field (trade transaction type) must be analyzed for such transactions in [MqlTradeTransaction](mqltradetransaction.md) structure. The second and third parameters of [OnTradeTransaction](ontradetransaction.md) (request and result) must be analyzed for additional data. | [MqlTradeTransaction](mqltradetransaction.md) |
| TUESDAY | Tuesday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| TYPE\_BOOL | bool | [MqlParam](mqlparam.md) |
| TYPE\_CHAR | char | [MqlParam](mqlparam.md) |
| TYPE\_COLOR | color | [MqlParam](mqlparam.md) |
| TYPE\_DATETIME | datetime | [MqlParam](mqlparam.md) |
| TYPE\_DOUBLE | double | [MqlParam](mqlparam.md) |
| TYPE\_FLOAT | float | [MqlParam](mqlparam.md) |
| TYPE\_INT | int | [MqlParam](mqlparam.md) |
| TYPE\_LONG | long | [MqlParam](mqlparam.md) |
| TYPE\_SHORT | short | [MqlParam](mqlparam.md) |
| TYPE\_STRING | string | [MqlParam](mqlparam.md) |
| TYPE\_UCHAR | uchar | [MqlParam](mqlparam.md) |
| TYPE\_UINT | uint | [MqlParam](mqlparam.md) |
| TYPE\_ULONG | ulong | [MqlParam](mqlparam.md) |
| TYPE\_USHORT | ushort | [MqlParam](mqlparam.md) |
| UCHAR\_MAX | Maximal value, which can be represented by uchar type | [Numerical Type Constants](typeconstants.md) |
| UINT\_MAX | Maximal value, which can be represented by uint type | [Numerical Type Constants](typeconstants.md) |
| ULONG\_MAX | Maximal value, which can be represented by ulong type | [Numerical Type Constants](typeconstants.md) |
| UPPER\_BAND | Upper limit | [Indicators Lines](lines.md) |
| UPPER\_HISTOGRAM | Upper histogram | [Indicators Lines](lines.md) |
| UPPER\_LINE | Upper line | [Indicators Lines](lines.md) |
| USHORT\_MAX | Maximal value, which can be represented by ushort type | [Numerical Type Constants](typeconstants.md) |
| VOLUME\_REAL | Trade volume | [Price Constants](prices.md) |
| VOLUME\_TICK | Tick volume | [Price Constants](prices.md) |
| WEDNESDAY | Wednesday | [SymbolInfoInteger](symbolinfointeger.md), [SymbolInfoSessionQuote](symbolinfosessionquote.md), [SymbolInfoSessionTrade](symbolinfosessiontrade.md) |
| WHOLE\_ARRAY | Means the number of items remaining until the end of the array, i.e., the entire array will be processed | [Other Constants](otherconstants.md) |
| WRONG\_VALUE | The constant can be implicitly [cast](casting.md) to any [enumeration](enumeration.md) type | [Other Constants](otherconstants.md) |