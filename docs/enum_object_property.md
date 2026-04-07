Object Properties



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Objects Constants](objectconstants.md) / Object Properties

[![Previous](previous.png)](obj_rectangle_label.md) 
[![Next](next.png)](enum_anchorpoint.md)

Object Properties

Graphical objects can have various properties depending on the object type. Values of object properties are set up and received by corresponding [functions for working with graphical objects](objects.md).

All objects used in technical analysis are bound to the time and price coordinates: trendline, channels, Fibonacci tools, etc. But there is a number of auxiliary objects intended to improve the user interface that are bound to the always visible part of a chart (main chart windows or indicator subwindows):

| Object | ID | X/Y | Width/Height | Date/Price | [OBJPROP\_CORNER](enum_object_property.md#enum_object_property_integer) | [OBJPROP\_ANCHOR](enum_object_property.md#enum_object_property_integer) | [OBJPROP\_ANGLE](enum_object_property.md#enum_object_property_double) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Text | [OBJ\_TEXT](obj_text.md) |  |  | Yes |  | Yes | Yes |
| Label | [OBJ\_LABEL](obj_label.md) | Yes | Yes (read only) |  | Yes | Yes | Yes |
| Button | [OBJ\_BUTTON](obj_button.md) | Yes | Yes |  | Yes |  |  |
| Bitmap | [OBJ\_BITMAP](obj_bitmap.md) |  | Yes (read only) | Yes |  | Yes |  |
| Bitmap Label | [OBJ\_BITMAP\_LABEL](obj_bitmap_label.md) | Yes | Yes (read only) |  | Yes | Yes |  |
| Edit | [OBJ\_EDIT](obj_edit.md) | Yes | Yes |  | Yes |  |  |
| Rectangle Label | [OBJ\_RECTANGLE\_LABEL](obj_rectangle_label.md) | Yes | Yes |  | Yes |  |  |

The following designations are used in the table:

* X/Y coordinates of anchor points specified in pixels relative to a chart corner;
* Width/Height objects have width and height. For "read only", the width and height values are calculated only once the object is rendered on chart;
* Date/Price anchor point coordinates are specified using the date and price values;
* OBJPROP\_CORNER defines the chart corner relative to which the anchor point coordinates are specified. Can be one of the 4 values of the [ENUM\_BASE\_CORNER](enum_basecorner.md#enum_base_corner) enumeration;
* OBJPROP\_ANCHOR defines the anchor point in object itself and can be one of the 9 values of the [ENUM\_ANCHOR\_POINT](enum_anchorpoint.md#enum_anchor_point) enumeration. Coordinates in pixels are specified from this very point to selected chart corner;
* OBJPROP\_ANGLE defines the object rotation angle counterclockwise.

The functions defining the properties of graphical objects, as well as [ObjectCreate()](objectcreate.md) and [ObjectMove()](objectmove.md) operations for creating and moving objects along the chart are actually used for sending commands to the chart. If these functions are executed successfully, the command is included in the common queue of the chart events. Visual changes in the properties of graphical objects are implemented when handling the queue of the chart events.

Thus, do not expect an immediate visual update of graphical objects after calling these functions. Generally, the graphical objects on the chart are updated automatically by the terminal following the change events - a new quote arrival, resizing the chart window, etc. Use [ChartRedraw()](chartredraw.md) function to forcefully update the graphical objects.

For functions [ObjectSetInteger()](objectsetinteger.md) and [ObjectGetInteger()](objectgetinteger.md)

ENUM\_OBJECT\_PROPERTY\_INTEGER

| Identifier | Description | Property Type |
| --- | --- | --- |
| OBJPROP\_COLOR | Color | color |
| OBJPROP\_STYLE | Style | [ENUM\_LINE\_STYLE](drawstyles.md#enum_line_style) |
| OBJPROP\_WIDTH | Line thickness | int |
| OBJPROP\_BACK | Object in the background | bool |
| OBJPROP\_ZORDER | Priority of a graphical object for receiving events of clicking on a chart ([CHARTEVENT\_CLICK](enum_chartevents.md)). The default zero value is set when creating an object; the priority can be increased if necessary. When objects are placed one atop another, only one of them with the highest priority will receive the CHARTEVENT\_CLICK event. | long |
| OBJPROP\_FILL | Fill an object with color (for OBJ\_RECTANGLE, OBJ\_TRIANGLE, OBJ\_ELLIPSE, OBJ\_CHANNEL, OBJ\_STDDEVCHANNEL, OBJ\_REGRESSION) | bool |
| OBJPROP\_HIDDEN | Disable the display of a graphical object in the client terminal [object list](https://www.metatrader5.com/en/terminal/help/charts_advanced/charts_objects_list#objects) called by the Charts \ Objects \ Object List command. This prevents accidental deletion of MQL5 program service objects by a user. In addition to hiding the object from the list, the property disables the ability to delete it using the Charts \ Objects \ Delete Last command.     The value of 'true' hides the object. By default, hidden objects are those that display calendar events and trading history, as well as those [created from an MQL5 program](objectcreate.md). Click "List all" to see them in the object list and access their properties. | bool |
| OBJPROP\_SELECTED | Object is selected | bool |
| OBJPROP\_READONLY | Ability to edit text in the Edit object | bool |
| OBJPROP\_TYPE | Object type | [ENUM\_OBJECT](enum_object.md)   r/o |
| OBJPROP\_TIME | Time coordinate | datetime   modifier=number of anchor point |
| OBJPROP\_SELECTABLE | Object availability | bool |
| OBJPROP\_CREATETIME | Time of object creation | datetime    r/o |
| OBJPROP\_LEVELS | Number of levels | int |
| OBJPROP\_LEVELCOLOR | Color of the line-level | color   modifier=level number |
| OBJPROP\_LEVELSTYLE | Style of the line-level | [ENUM\_LINE\_STYLE](drawstyles.md#enum_line_style) modifier=level number |
| OBJPROP\_LEVELWIDTH | Thickness of the line-level | int      modifier=level number |
| OBJPROP\_ALIGN | Horizontal text alignment in the "Edit" object (OBJ\_EDIT) | [ENUM\_ALIGN\_MODE](enum_object_property.md#enum_align_mode) |
| OBJPROP\_FONTSIZE | Font size | int |
| OBJPROP\_RAY\_LEFT | Ray goes to the left | bool |
| OBJPROP\_RAY\_RIGHT | Ray goes to the right | bool |
| OBJPROP\_RAY | A vertical line goes through all the windows of a chart | bool |
| OBJPROP\_ELLIPSE | Showing the full ellipse of the Fibonacci Arc object ([OBJ\_FIBOARC](enum_object.md)) | bool |
| OBJPROP\_ARROWCODE | Arrow code for the Arrow object | uchar |
| OBJPROP\_TIMEFRAMES | Visibility of an object at timeframes | set of flags [flags](visible.md) |
| OBJPROP\_ANCHOR | Location of the anchor point of a graphical object | [ENUM\_ARROW\_ANCHOR](enum_anchorpoint.md#enum_arrow_anchor) (for OBJ\_ARROW),  [ENUM\_ANCHOR\_POINT](enum_anchorpoint.md) (for OBJ\_LABEL, OBJ\_BITMAP\_LABEL and OBJ\_TEXT) |
| OBJPROP\_XDISTANCE | The distance in pixels along the X axis from the binding corner (see [note](enum_object_property.md#distance_fixedsize)) | int |
| OBJPROP\_YDISTANCE | The distance in pixels along the Y axis from the binding corner (see [note](enum_object_property.md#distance_fixedsize)) | int |
| OBJPROP\_DIRECTION | Trend of the Gann object | [ENUM\_GANN\_DIRECTION](enum_gann_direction.md) |
| OBJPROP\_DEGREE | Level of the Elliott Wave Marking | [ENUM\_ELLIOT\_WAVE\_DEGREE](enum_elliot_wave_degree.md) |
| OBJPROP\_DRAWLINES | Displaying lines for marking the Elliott Wave | bool |
| OBJPROP\_STATE | Button state (pressed / depressed) | bool |
| OBJPROP\_CHART\_ID | ID of the "Chart" object ([OBJ\_CHART](enum_object.md)). It allows working with the properties of this object like with a normal chart using the functions described in [Chart Operations](chart_operations.md), but there some [exceptions](enum_object_property.md#objprop_chart_id_exception). | long   r/o |
| OBJPROP\_XSIZE | The object's width along the X axis in pixels. Specified for  OBJ\_LABEL (read only), OBJ\_BUTTON, OBJ\_CHART, OBJ\_BITMAP, OBJ\_BITMAP\_LABEL, OBJ\_EDIT, OBJ\_RECTANGLE\_LABEL objects. | int |
| OBJPROP\_YSIZE | The object's height along the Y axis in pixels. Specified for  OBJ\_LABEL (read only), OBJ\_BUTTON, OBJ\_CHART, OBJ\_BITMAP, OBJ\_BITMAP\_LABEL, OBJ\_EDIT, OBJ\_RECTANGLE\_LABEL objects. | int |
| OBJPROP\_XOFFSET | The X coordinate of the upper left corner of the [rectangular visible area](enum_object_property.md#visual_rectangle) in the graphical objects "Bitmap Label" and "Bitmap" (OBJ\_BITMAP\_LABEL and OBJ\_BITMAP). The value is set in pixels relative to the upper left corner of the original image. | int |
| OBJPROP\_YOFFSET | The Y coordinate of the upper left corner of the [rectangular visible area](enum_object_property.md#visual_rectangle) in the graphical objects "Bitmap Label" and "Bitmap" (OBJ\_BITMAP\_LABEL and OBJ\_BITMAP). The value is set in pixels relative to the upper left corner of the original image. | int |
| OBJPROP\_PERIOD | Timeframe for the Chart object | [ENUM\_TIMEFRAMES](enum_timeframes.md) |
| OBJPROP\_DATE\_SCALE | Displaying the time scale for the Chart object | bool |
| OBJPROP\_PRICE\_SCALE | Displaying the price scale for the Chart object | bool |
| OBJPROP\_CHART\_SCALE | The scale for the Chart object | int   value in the range 05 |
| OBJPROP\_BGCOLOR | The background color for  OBJ\_EDIT, OBJ\_BUTTON, OBJ\_RECTANGLE\_LABEL | color |
| OBJPROP\_CORNER | The corner of the chart to link a graphical object | [ENUM\_BASE\_CORNER](enum_basecorner.md) |
| OBJPROP\_BORDER\_TYPE | Border type for the "Rectangle label" object | [ENUM\_BORDER\_TYPE](enum_object_property.md#enum_border_type) |
| OBJPROP\_BORDER\_COLOR | Border color for the OBJ\_EDIT and OBJ\_BUTTON objects | color |

When using [chart operations](chart_operations.md) for the "Chart" object ([OBJ\_CHART](enum_object.md)), the following limitations are imposed:

* It cannot be closed using [ChartClose()](chartclose.md);
* Symbol/period cannot be changed using the [ChartSetSymbolPeriod()](chartsetsymbolperiod.md) function;
* The following properties are ineffective CHART\_SCALE, CHART\_BRING\_TO\_TOP, CHART\_SHOW\_DATE\_SCALE and CHART\_SHOW\_PRICE\_SCALE ([ENUM\_CHART\_PROPERTY\_INTEGER](enum_chart_property.md#enum_chart_property_integer)).

 

You can set a special mode of image display for [OBJ\_BITMAP\_LABEL](enum_object.md) and [OBJ\_BITMAP](enum_object.md) objects. In this mode, only part of an original image (at which a rectangular visible area is applied) is displayed, while the rest of the image becomes invisible. The size of this area should be set using the properties OBJPROP\_XSIZE and OBJPROP\_YSIZE. The visible area can be "moved" only within the original image using the properties OBJPROP\_XOFFSET and OBJPROP\_YOFFSET.

 

For the fixed-sized objects: [OBJ\_BUTTON](obj_button.md), [OBJ\_RECTANGLE\_LABEL](obj_rectangle_label.md), [OBJ\_EDIT](obj_edit.md) and [OBJ\_CHART](obj_chart.md), properties OBJPROP\_XDISTANCE and OBJPROP\_YDISTANCE set the position of the top left point of the object relative to the chart corner (OBJPROP\_CORNER), from which the X and Y coordinates will be counted in pixels.

 

For functions [ObjectSetDouble()](objectsetdouble.md) and [ObjectGetDouble()](objectgetdouble.md)

ENUM\_OBJECT\_PROPERTY\_DOUBLE

| Identifier | Description | Property Type |
| --- | --- | --- |
| OBJPROP\_PRICE | Price coordinate | double    modifier=number of anchor point |
| OBJPROP\_LEVELVALUE | Level value | double    modifier=level number |
| OBJPROP\_SCALE | Scale (properties of Gann objects and Fibonacci Arcs) | double |
| OBJPROP\_ANGLE | Angle.  For the objects with no angle specified, created from a program, the value is equal to [EMPTY\_VALUE](otherconstants.md) | double |
| OBJPROP\_DEVIATION | Deviation for the Standard Deviation Channel | double |

 

For functions [ObjectSetString()](objectsetstring.md) and [ObjectGetString()](objectgetstring.md)

ENUM\_OBJECT\_PROPERTY\_STRING

| Identifier | Description | Property Type |
| --- | --- | --- |
| OBJPROP\_NAME | Object name | string |
| OBJPROP\_TEXT | Description of the object (the text contained in the object) | string |
| OBJPROP\_TOOLTIP | The text of a tooltip. If the property is not set, then the tooltip generated automatically by the terminal is shown. A tooltip can be disabled by setting the "\n" (line feed) value to it | string |
| OBJPROP\_LEVELTEXT | Level description | string    modifier=level number |
| OBJPROP\_FONT | Font | string |
| OBJPROP\_BMPFILE | The name of BMP-file for Bitmap Label. See also [Resources](resources.md) | string    modifier: 0-state ON, 1-state OFF |
| OBJPROP\_SYMBOL | Symbol for the Chart object | string |

 

For the OBJ\_RECTANGLE\_LABEL object ("Rectangle label") one of the three design modes can be set, to which the following values of ENUM\_BORDER\_TYPE correspond.

ENUM\_BORDER\_TYPE

| Identifier | Description |
| --- | --- |
| BORDER\_FLAT | Flat form |
| BORDER\_RAISED | Prominent form |
| BORDER\_SUNKEN | Concave form |

 

For the OBJ\_EDIT object ("Edit") and for the [ChartScreenShot()](chartscreenshot.md) function, you can specify the horizontal alignment type using the values of the ENUM\_ALIGN\_MODE enumeration.

ENUM\_ALIGN\_MODE

| Identifier | Description |
| --- | --- |
| ALIGN\_LEFT | Left alignment |
| ALIGN\_CENTER | Centered (only for the Edit object) |
| ALIGN\_RIGHT | Right alignment |

Example:

```
#define  UP          "\x0431"
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//---
   string label_name="my_OBJ_LABEL_object";
   if(ObjectFind(0,label_name)<0)
     {
      Print("Object ",label_name," not found. Error code = ",GetLastError());
      //--- create Label object
      ObjectCreate(0,label_name,OBJ_LABEL,0,0,0);           
      //--- set X coordinate
      ObjectSetInteger(0,label_name,OBJPROP_XDISTANCE,200);
      //--- set Y coordinate
      ObjectSetInteger(0,label_name,OBJPROP_YDISTANCE,300);
      //--- define text color
      ObjectSetInteger(0,label_name,OBJPROP_COLOR,clrWhite);
      //--- define text for object Label
      ObjectSetString(0,label_name,OBJPROP_TEXT,UP);
      //--- define font
      ObjectSetString(0,label_name,OBJPROP_FONT,"Wingdings");
      //--- define font size
      ObjectSetInteger(0,label_name,OBJPROP_FONTSIZE,10);
      //--- 45 degrees rotation clockwise
      ObjectSetDouble(0,label_name,OBJPROP_ANGLE,-45);
      //--- disable for mouse selecting
      ObjectSetInteger(0,label_name,OBJPROP_SELECTABLE,false);
      //--- draw it on the chart
      ChartRedraw(0);                                      
     }
  }
```