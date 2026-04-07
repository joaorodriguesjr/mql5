ChartIndicatorsTotal



[MQL5 Reference](index.md)  /  [Chart Operations](chart_operations.md) / ChartIndicatorsTotal

[![Previous](previous.png)](chartindicatorname.md) 
[![Next](next.png)](chartwindowondropped.md)

ChartIndicatorsTotal

Returns the number of all indicators applied to the specified chart window.

```
int  ChartIndicatorsTotal(
   long  chart_id,      // chart id
   int   sub_window     // number of the subwindow
   );
```

Parameters

chart\_id

[in]  Chart ID. 0 denotes the current chart.

sub\_window

[in]  Number of the chart subwindow. 0 denotes the main chart subwindow.

Return Value

The number of indicators in the specified chart window. To get [error](errorcodes.md) details use the [GetLastError()](getlasterror.md) function.

Note

The function allows going searching through all the indicators attached to the chart. The number of all the windows of the chart can be obtained from the [CHART\_WINDOWS\_TOTAL](enum_chart_property.md#enum_chart_property_integer) property using the [ChartGetInteger()](chartgetinteger.md) function.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get the current chart ID and the number of its subwindows, including the main window
   long chart_id = ChartID();
   int  wnd_total= (int)ChartGetInteger(0,CHART_WINDOWS_TOTAL);
   
//--- iterate over all current chart windows in a loop
   for(int w=0; w<wnd_total; w++)
     {
      //--- get the number of indicators attached to the chart window specified by the loop index
      int ind_total=ChartIndicatorsTotal(chart_id, w);
      
      //--- get the number of indicators attached to the specified chart window
      PrintFormat("Chart ID %I64d, subwindow %d. Attached indicators: %d", chart_id, w, ind_total);
     }
   /*
   result:
   Chart ID 133246248352168439, subwindow 0. Attached indicators: 3
   Chart ID 133246248352168439, subwindow 1. Attached indicators: 2
   Chart ID 133246248352168439, subwindow 2. Attached indicators: 1
   */
  }
```

See also

[ChartIndicatorAdd()](chartindicatoradd.md), [ChartIndicatorDelete()](chartindicatordelete.md), [iCustom()](icustom.md), [IndicatorCreate()](indicatorcreate.md), [IndicatorSetString()](indicatorsetstring.md)