Chart Operations



[MQL5 Reference](index.md) / Chart Operations

[![Previous](previous.png)](custombookadd.md) 
[![Next](next.png)](chartapplytemplate.md)

Chart Operations

Functions for setting chart properties ([ChartSetInteger](chartsetinteger.md), [ChartSetDouble](chartsetdouble.md), [ChartSetString](chartsetstring.md)) are asynchronous and are used for sending update commands to a chart. If these functions are executed successfully, the command is included in the common queue of the chart events. Chart property changes are implemented along with handling of the events queue of this chart.

Thus, do not expect an immediate update of the chart after calling asynchronous functions. Use the [ChartRedraw()](chartredraw.md) function to forcedly update the chart appearance and properties.

| Function | Action |
| --- | --- |
| [ChartApplyTemplate](chartapplytemplate.md) | Applies a specific template from a specified file to the chart |
| [ChartSaveTemplate](chartsavetemplate.md) | Saves current chart settings in a template with a specified name |
| [ChartWindowFind](chartwindowfind.md) | Returns the number of a subwindow where an indicator is drawn |
| [ChartTimePriceToXY](charttimepricetoxy.md) | Converts the coordinates of a chart from the time/price representation to the X and Y coordinates |
| [ChartXYToTimePrice](chartxytotimeprice.md) | Converts the X and Y coordinates on a chart to the time and price values |
| [ChartOpen](chartopen.md) | Opens a new chart with the specified symbol and period |
| [ChartClose](chartclose.md) | Closes the specified chart |
| [ChartFirst](chartfirst.md) | Returns the ID of the first chart of the client terminal |
| [ChartNext](chartnext.md) | Returns the chart ID of the chart next to the specified one |
| [ChartSymbol](chartsymbol.md) | Returns the symbol name of the specified chart |
| [ChartPeriod](chartperiod.md) | Returns the period value of the specified chart |
| [ChartRedraw](chartredraw.md) | Calls a forced redrawing of a specified chart |
| [ChartSetDouble](chartsetdouble.md) | Sets the double value for a corresponding property of the specified chart |
| [ChartSetInteger](chartsetinteger.md) | Sets the integer value (datetime, int, color, bool or char) for a corresponding property of the specified chart |
| [ChartSetString](chartsetstring.md) | Sets the string value for a corresponding property of the specified chart |
| [ChartGetDouble](chartgetdouble.md) | Returns the double value property of the specified chart |
| [ChartGetInteger](chartgetinteger.md) | Returns the integer value property of the specified chart |
| [ChartGetString](chartgetstring.md) | Returns the string value property of the specified chart |
| [ChartNavigate](chartnavigate.md) | Performs shift of the specified chart by the specified number of bars relative to the specified position in the chart |
| [ChartID](chartid.md) | Returns the ID of the current chart |
| [ChartIndicatorAdd](chartindicatoradd.md) | Adds an indicator with the specified handle into a specified chart window |
| [ChartIndicatorDelete](chartindicatordelete.md) | Removes an indicator with a specified name from the specified chart window |
| [ChartIndicatorGet](chartindicatorget.md) | Returns the handle of the indicator with the specified short name in the specified chart window |
| [ChartIndicatorName](chartindicatorname.md) | Returns the short name of the indicator by the number in the indicators list on the specified chart window |
| [ChartIndicatorsTotal](chartindicatorstotal.md) | Returns the number of all indicators applied to the specified chart window. |
| [ChartWindowOnDropped](chartwindowondropped.md) | Returns the number (index) of the chart subwindow the Expert Advisor or script has been dropped to |
| [ChartPriceOnDropped](chartpriceondropped.md) | Returns the price coordinate of the chart point the Expert Advisor or script has been dropped to |
| [ChartTimeOnDropped](charttimeondropped.md) | Returns the time coordinate of the chart point the Expert Advisor or script has been dropped to |
| [ChartXOnDropped](chartxondropped.md) | Returns the X coordinate of the chart point the Expert Advisor or script has been dropped to |
| [ChartYOnDropped](chartyondropped.md) | Returns the Y coordinate of the chart point the Expert Advisor or script has been dropped to |
| [ChartSetSymbolPeriod](chartsetsymbolperiod.md) | Changes the symbol value and a period of the specified chart |
| [ChartScreenShot](chartscreenshot.md) | Provides a screenshot of the chart of its current state in a GIF, PNG or BMP format depending on specified extension |