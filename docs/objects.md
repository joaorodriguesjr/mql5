Object Functions



[MQL5 Reference](index.md) / Object Functions

[![Previous](previous.png)](plotindexgetinteger.md) 
[![Next](next.png)](objectcreate.md)

Object Functions

This is the group of functions intended for working with graphic objects relating to any specified chart.

The functions defining the properties of graphical objects, as well as [ObjectCreate()](objectcreate.md) and [ObjectMove()](objectmove.md) operations for creating and moving objects along the chart are actually used for sending commands to the chart. If these functions are executed successfully, the command is included in the common queue of the chart events. Visual changes in the properties of graphical objects are implemented when handling the queue of the chart events.

Thus, do not expect an immediate visual update of graphical objects after calling these functions. Generally, the graphical objects on the chart are updated automatically by the terminal following the change events - a new quote arrival, resizing the chart window, etc. Use [ChartRedraw()](chartredraw.md) function to forcefully update the graphical objects.

| Function | Action |
| --- | --- |
| [ObjectCreate](objectcreate.md) | Creates an object of the specified type in a specified chart |
| [ObjectName](objectname.md) | Returns the name of an object of the corresponding type in the specified chart (specified chart subwindow) |
| [ObjectDelete](objectdelete.md) | Removes the object with the specified name from the specified chart (from the specified chart subwindow) |
| [ObjectsDeleteAll](objectdeleteall.md) | Removes all objects of the specified type from the specified chart (from the specified chart subwindow) |
| [ObjectFind](objectfind.md) | Searches for an object with the specified ID by the name |
| [ObjectGetTimeByValue](objectgettimebyvalue.md) | Returns the time value for the specified object price value |
| [ObjectGetValueByTime](objectgetvaluebytime.md) | Returns the price value of an object for the specified time |
| [ObjectMove](objectmove.md) | Changes the coordinates of the specified object anchor point |
| [ObjectsTotal](objectstotal.md) | Returns the number of objects of the specified type in the specified chart (specified chart subwindow) |
| [ObjectGetDouble](objectgetdouble.md) | Returns the double value of the corresponding object property |
| [ObjectGetInteger](objectgetinteger.md) | Returns the integer value of the corresponding object property |
| [ObjectGetString](objectgetstring.md) | Returns the string value of the corresponding object property |
| [ObjectSetDouble](objectsetdouble.md) | Sets the value of the corresponding object property |
| [ObjectSetInteger](objectsetinteger.md) | Sets the value of the corresponding object property |
| [ObjectSetString](objectsetstring.md) | Sets the value of the corresponding object property |
| [TextSetFont](textsetfont.md) | Sets the font for displaying the text using drawing methods (Arial 20 used by default) |
| [TextOut](textout.md) | Transfers the text to the custom array (buffer) designed for creation of a graphical [resource](resourcecreate.md) |
| [TextGetSize](textgetsize.md) | Returns the string's width and height at the current [font settings](textsetfont.md) |

Every graphical object should have a name unique within one [chart](chart_operations.md), including its subwindows. Changing of a name of a graphic object generates two events: event of deletion of an object with the old name, and event of creation of an object with a new name.

After an object is created or an [object property](enum_object_property.md) is modified it is recommended to call the [ChartRedraw()](chartredraw.md) function, which commands the client terminal to forcibly draw a chart (and all [visible](visible.md) objects in it).