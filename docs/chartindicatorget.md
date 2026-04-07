ChartIndicatorGet



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartIndicatorGet

[![Previous](previous.png)](chartindicatordelete.md) 
[![Next](next.png)](chartindicatorname.md)

ChartIndicatorGet

Returns the handle of the indicator with the specified short name in the specified chart window.

```
int  ChartIndicatorGet(
   long           chart_id,              // Chart ID
   int            sub_window             // The number of the subwindow
   const string   indicator_shortname    // Short name of the indicator
   );
```

Parameters

chart\_id

[in]  Chart ID. 0 means the current chart.

sub\_window

[in]  The number of the chart subwindow. 0 means the main chart window.

const indicator\_shortname

[in]  The short name if the indicator, which is set in the [INDICATOR\_SHORTNAME](customindicatorproperties.md#enum_customind_property_string) property using the [IndicatorSetString()](indicatorsetstring.md) function. To get the short name of an indicator, use the [ChartIndicatorName()](chartindicatorname.md) function.

Return Value

Returns an indicator handle if successful, otherwise returns [INVALID\_HANDLE](otherconstants.md). To get information about [the error](errorcodes.md), call the [GetLastError()](getlasterror.md) function.

Note

The indicator handle obtained using the ChartIndicatorGet() function increases the internal indicator usage counter. The terminal runtime system keeps all indicators, whose counter is greater than zero, loaded. Therefore, the indicator handle that is no longer needed should be immediately and explicitly released using [IndicatorRelease()](indicatorrelease.md) in the same program that received it, as shown in the example below. Otherwise, it will be impossible to find the abandoned handle and release it from another program correctly.

When creating an indicator, be careful forming its short name, which is written in the [INDICATOR\_SHORTNAME](customindicatorproperties.md#enum_customind_property_string) property using the [IndicatorSetString()](indicatorsetstring.md) function. It is recommended that a short name should contain the values of input parameters of the indicator, since the indicator is identified in the [ChartIndicatorGet()](chartindicatorget.md) function based on its short name.

Another way to identify the indicator is to get a list of its parameters for a given handle using the [IndicatorParameters()](indicatorparameters.md) function and then to analyze the obtained values.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
   //--- The number of windows on the chart (at least one main window is always present)
   int windows=(int)ChartGetInteger(0,CHART_WINDOWS_TOTAL);
   //--- Check all windows
   for(int w=0;w<windows;w++)
     {
      //--- the number of indicators in this window/subwindow
      int total=ChartIndicatorsTotal(0,w);
      //--- Go through all indicators in the window
      for(int i=0;i<total;i++)
        {
         //--- get the short name of an indicator
         string name=ChartIndicatorName(0,w,i);
         //--- get the handle of an indicator
         int handle=ChartIndicatorGet(0,w,name);
         //--- Add to log
         PrintFormat("Window=%d,  index=%d,  name=%s,  handle=%d",w,i,name,handle);
         //--- You should obligatorily release the indicator handle when it is no longer needed
         IndicatorRelease(handle);
        }
     }
  }
```

See also

[ChartIndicatorAdd()](chartindicatoradd.md), [ChartIndicatorName()](chartindicatorname.md), [ChartIndicatorsTotal()](chartindicatorstotal.md), [IndicatorParameters()](indicatorparameters.md)