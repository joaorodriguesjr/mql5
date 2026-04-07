Drawing Styles



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Indicator Constants](indicatorconstants.md) / Drawing Styles

[![Previous](previous.png)](lines.md) 
[![Next](next.png)](customindicatorproperties.md)

Drawing Styles

When creating [a custom indicator](customind.md), you can specify one of 18 types of graphical plotting (as displayed in the main chart window or a chart subwindow), whose values are specified in the ENUM\_DRAW\_TYPE enumeration.

In one custom indicator, it is permissible to use any [indicator building/drawing types](indicators_examples.md). Each construction type requires specification of one to five [global arrays](global.md) for storing data necessary for drawing. These data arrays must be bound with indicator buffers using the [SetIndexBuffer()](setindexbuffer.md) function. The type of data from [ENUM\_INDEXBUFFER\_TYPE](customindicatorproperties.md#enum_indexbuffer_type_enum) should be specified for each buffer.

Depending on the drawing style, you may need one to four value buffers (marked as INDICATOR\_DATA). If a style admits dynamic alternation of colors (all styles contain COLOR in their names), then you'll need one more buffer of color (indicated type INDICATOR\_COLOR\_INDEX). The color buffers are always bound after value buffers corresponding to the style.

ENUM\_DRAW\_TYPE

| ID | Description | Data buffers | Color buffers |
| --- | --- | --- | --- |
| [DRAW\_NONE](draw_none.md) | Not drawn | 1 | 0 |
| [DRAW\_LINE](draw_line.md) | Line | 1 | 0 |
| [DRAW\_SECTION](draw_section.md) | Section | 1 | 0 |
| [DRAW\_HISTOGRAM](draw_histogram.md) | Histogram from the zero line | 1 | 0 |
| [DRAW\_HISTOGRAM2](draw_histogram2.md) | Histogram of the two indicator buffers | 2 | 0 |
| [DRAW\_ARROW](draw_arrow.md) | Drawing arrows | 1 | 0 |
| [DRAW\_ZIGZAG](draw_zigzag.md) | Style Zigzag allows vertical section on the bar | 2 | 0 |
| [DRAW\_FILLING](draw_filling.md) | Color fill between the two levels | 2 | 0 |
| [DRAW\_BARS](draw_bars.md) | Display as a sequence of bars | 4 | 0 |
| [DRAW\_CANDLES](draw_candles.md) | Display as a sequence of candlesticks | 4 | 0 |
| [DRAW\_COLOR\_LINE](draw_color_line.md) | Multicolored line | 1 | 1 |
| [DRAW\_COLOR\_SECTION](draw_color_section.md) | Multicolored section | 1 | 1 |
| [DRAW\_COLOR\_HISTOGRAM](draw_color_histogram.md) | Multicolored histogram from the zero line | 1 | 1 |
| [DRAW\_COLOR\_HISTOGRAM2](draw_color_histogram2.md) | Multicolored histogram of the two indicator buffers | 2 | 1 |
| [DRAW\_COLOR\_ARROW](draw_color_arrow.md) | Drawing multicolored arrows | 1 | 1 |
| [DRAW\_COLOR\_ZIGZAG](draw_color_zigzag.md) | Multicolored ZigZag | 2 | 1 |
| [DRAW\_COLOR\_BARS](draw_color_bars.md) | Multicolored bars | 4 | 1 |
| [DRAW\_COLOR\_CANDLES](draw_color_candles.md) | Multicolored candlesticks | 4 | 1 |

 

To refine the display of the selected drawing type identifiers listed in ENUM\_PLOT\_PROPERTY are used.

For functions [PlotIndexSetInteger()](plotindexsetinteger.md) and [PlotIndexGetInteger()](plotindexgetinteger.md)

ENUM\_PLOT\_PROPERTY\_INTEGER

| ID | Description | Property type |
| --- | --- | --- |
| PLOT\_ARROW | Arrow code for style DRAW\_ARROW | uchar |
| PLOT\_ARROW\_SHIFT | Vertical shift of arrows for style DRAW\_ARROW | int |
| PLOT\_DRAW\_BEGIN | Number of initial bars without drawing and values in the DataWindow | int |
| PLOT\_DRAW\_TYPE | Type of graphical construction | [ENUM\_DRAW\_TYPE](drawstyles.md#enum_draw_type) |
| PLOT\_SHOW\_DATA | Sign of display of construction values in the DataWindow | bool |
| PLOT\_SHIFT | Shift of indicator plotting along the time axis in bars | int |
| PLOT\_LINE\_STYLE | Drawing line style | [ENUM\_LINE\_STYLE](drawstyles.md#enum_line_style) |
| PLOT\_LINE\_WIDTH | The thickness of the drawing line | int |
| PLOT\_COLOR\_INDEXES | The number of colors | int |
| PLOT\_LINE\_COLOR | The index of a buffer containing the drawing color | color       modifier = index number of colors |

For the function [PlotIndexSetDouble()](plotindexsetdouble.md)

ENUM\_PLOT\_PROPERTY\_DOUBLE

| ID | Description | Property type |
| --- | --- | --- |
| PLOT\_EMPTY\_VALUE | An empty value for plotting, for which there is no drawing | double |

For the function [PlotIndexSetString()](plotindexsetstring.md)

ENUM\_PLOT\_PROPERTY\_STRING

| ID | Description | Property type |
| --- | --- | --- |
| PLOT\_LABEL | The name of the indicator graphical series to display in the DataWindow. When working with complex graphical styles requiring several indicator buffers for display, the names for each buffer can be specified using ";" as a separator. Sample code is shown in [DRAW\_CANDLES](draw_candles.md) | string |

5 styles can be used for drawing lines in custom indicators. They are valid only for the line thickness 0 or 1.

ENUM\_LINE\_STYLE

| ID | Description |
| --- | --- |
| STYLE\_SOLID | Solid line |
| STYLE\_DASH | Broken line |
| STYLE\_DOT | Dotted line |
| STYLE\_DASHDOT | Dash-dot line |
| STYLE\_DASHDOTDOT | Dash - two points |

 

To set the line drawing style and the type of drawing, the [PlotIndexSetInteger()](plotindexsetinteger.md) function is used. For the Fibonacci extensions the thickness and drawing style of levels can be indicated using the [ObjectSetInteger()](objectsetinteger.md) function.

Example:

```
#property indicator_chart_window
#property indicator_buffers 1
#property indicator_plots   1
//--- indicator buffers
double         MABuffer[];
//+------------------------------------------------------------------+
//| Custom indicator initialization function                         |
//+------------------------------------------------------------------+
void OnInit()
  {
//--- Bind the Array to the indicator buffer with index 0
   SetIndexBuffer(0,MABuffer,INDICATOR_DATA);
//--- Set the line drawing
   PlotIndexSetInteger(0,PLOT_DRAW_TYPE,DRAW_LINE);
//--- Set the style line
   PlotIndexSetInteger(0,PLOT_LINE_STYLE,STYLE_DOT);
//--- Set line color
   PlotIndexSetInteger(0,PLOT_LINE_COLOR,clrRed);
//--- Set line thickness
   PlotIndexSetInteger(0,PLOT_LINE_WIDTH,1);
//--- Set labels for the line
   PlotIndexSetString(0,PLOT_LABEL,"Moving Average");
//---
  }
//+------------------------------------------------------------------+
//| Custom indicator iteration function                              |
//+------------------------------------------------------------------+
int OnCalculate(const int rates_total,
                 const int prev_calculated,
                 const datetime &time[],
                 const double &open[],
                 const double &high[],
                 const double &low[],
                 const double &close[],
                 const long &tick_volume[],
                 const long &volume[],
                 const int &spread[])
  {
//--- 
   for(int i=prev_calculated;i<rates_total;i++)
     {
      MABuffer[i]=close[i];
     }
//--- return value of prev_calculated for next call
   return(rates_total);
  }
```

```

```