Chart Representation



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Chart Constants](chartconstants.md) / Chart Representation

[![Previous](previous.png)](enum_chart_position.md) 
[![Next](next.png)](charts_samples.md)

Chart Representation

Price charts can be displayed in three ways:

* as bars;
* as candlesticks;
* as a line.

The specific way of displaying the price chart is set by the function [ChartSetInteger](chartsetinteger.md)(chart\_handle,[CHART\_MODE](enum_chart_property.md), chart\_mode), where chart\_mode is one of the values of the ENUM\_CHART\_MODE enumeration.

ENUM\_CHART\_MODE

| ID | Description |
| --- | --- |
| CHART\_BARS | Display as a sequence of bars |
| CHART\_CANDLES | Display as Japanese candlesticks |
| CHART\_LINE | Display as a line drawn by Close prices |

To specify the mode of displaying volumes in the price chart the function [ChartSetInteger](chartsetinteger.md)(chart\_handle, [CHART\_SHOW\_VOLUMES](enum_chart_property.md), volume\_mode) is used, where volume\_mode is one of values of the ENUM\_CHART\_VOLUME\_MODE enumeration.

 

ENUM\_CHART\_VOLUME\_MODE

| ID | Description |
| --- | --- |
| CHART\_VOLUME\_HIDE | Volumes are not shown |
| CHART\_VOLUME\_TICK | Tick volumes |
| CHART\_VOLUME\_REAL | Trade volumes |

Example:

```
//--- Get the handle of the current chart
   long handle=ChartID();
   if(handle>0) // If it succeeded, additionally customize
     {
      //--- Disable autoscroll
      ChartSetInteger(handle,CHART_AUTOSCROLL,false);
      //--- Set the indent of the right border of the chart
      ChartSetInteger(handle,CHART_SHIFT,true);
      //--- Display as candlesticks
      ChartSetInteger(handle,CHART_MODE,CHART_CANDLES);
      //--- Scroll by 100 bars from the beginning of history
      ChartNavigate(handle,CHART_CURRENT_POS,100);
      //--- Set the tick volume display mode
      ChartSetInteger(handle,CHART_SHOW_VOLUMES,CHART_VOLUME_TICK);
     }
```

See also

[ChartOpen](chartopen.md), [ChartID](chartid.md)