Other Constants



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Named Constants](namedconstants.md) / Other Constants

[![Previous](previous.png)](enum_pointer_type.md) 
[![Next](next.png)](structures.md)

Other Constants

The CLR\_NONE constant is used to outline the absence of color, it means that the [graphical object](objects.md) or [graphical series](drawstyles.md) of an indicator will not be plotted. This constant was not included into the [Web-color](webcolors.md) constants list, but it can be applied everywhere where the color arguments are required.

The INVALID\_HANDLE constant can be used for checking file handles (see [FileOpen()](fileopen.md) and [FileFindFirst()](filefindfirst.md)).

| Constant | Description | Value |
| --- | --- | --- |
| CHARTS\_MAX | The maximum possible number of simultaneously open charts in the terminal | 100 |
| clrNONE | Absence of color | -1 |
| EMPTY\_VALUE | Empty value in an indicator buffer | DBL\_MAX |
| INVALID\_HANDLE | Incorrect handle | -1 |
| IS\_DEBUG\_MODE | Flag that a mq5-program operates in debug mode | non zero in debug mode, otherwise zero |
| IS\_PROFILE\_MODE | Flag that a mq5-program operates in profiling mode | non zero in profiling mode, otherwise zero |
| NULL | Zero for any types | 0 |
| WHOLE\_ARRAY | Means the number of items remaining until the end of the array, i.e., the entire array will be processed | -1 |
| WRONG\_VALUE | The constant can be implicitly [cast](casting.md) to any [enumeration](enumeration.md) type | -1 |

The EMPTY\_VALUE constant usually corresponds to the values of indicators that are not shown in the chart. For example, for built-in indicator Standard Deviation with a period of 20, the line for the first 19 bars in the history  is not shown in the chart. If you create a handle of this indicator with the [iStdDev()](istddev.md) function and copy it to an array of indicator values for these bars through [CopyBuffer()](copybuffer.md), then these values will be equal to EMPTY\_VALUE.

You can choose to specify for [a custom indicator](customind.md) your own empty value of the indicator, when the indicator shouldn't be drawn in the chart. Use the [PlotIndexSetDouble()](plotindexsetdouble.md) function with the [PLOT\_EMPTY\_VALUE](drawstyles.md#enum_plot_property_double) modifier.

The [NULL](void.md) constant can be assigned to a variable of any simple type or to an object structure or class pointer. The NULL assignment for a string variable means the full deinitialization of this variable.

The WRONG\_VALUE constant is intended for cases, when it is necessary to return value of an [enumeration](enumeration.md), and this must be a wrong value. For example, when we need to inform that a return value is a value from this enumeration. Let's consider as an example some function CheckLineStyle(), which returns the line style for an object, specified by its name. If at style check by ObjectGetInteger() the result is true, a value from [ENUM\_LINE\_STYLE](drawstyles.md#enum_line_style) is returned; otherwise WRONG\_VALUE is returned.

```
void OnStart()
  {
   if(CheckLineStyle("MyChartObject")==WRONG_VALUE)
      printf("Error line style getting.");
  }
//+------------------------------------------------------------------+
//| returns the line style for an object specified by its name       |
//+------------------------------------------------------------------+
ENUM_LINE_STYLE CheckLineStyle(string name)
  {
   long style;
//---
   if(ObjectGetInteger(0,name,OBJPROP_STYLE,0,style))
      return((ENUM_LINE_STYLE)style);
   else
      return(WRONG_VALUE);
  }
```

 

The WHOLE\_ARRAY constant is intended for functions that require specifying the number of elements in processed arrays:

* [ArrayCopy()](arraycopy.md);
* [ArrayMinimum()](arrayminimum.md);
* [ArrayMaximum()](arraymaximum.md);
* [FileReadArray()](filereadarray.md);
* [FileWriteArray()](filewritearray.md).

If you want to specify that all the array values from a specified position till the end must be processed, you should specify just the WHOLE\_ARRAY value.

IS\_PROFILE\_MODE constant  allows changing a program operation for correct data collection in the profiling mode. Profiling allows measuring the execution time of the individual program fragments (usually comprising functions), as well as calculating the number of such calls. Sleep() function calls can be disabled to determine the execution time in the profiling mode, like in this example:

```
//--- Sleep can greatly affect (change) profiling result
if(!IS_PROFILE_MODE) Sleep(100); // disabling Sleep() call in the profiling mode
```

IS\_PROFILE\_MODE constant value is set by the compiler during the compilation, while it is set to zero in conventional mode. When launching a program in the profiling mode, a special compilation is performed and IS\_PROFILE\_MODE is replaced with a non-zero value.

The IS\_DEBUG\_MODE constant can be useful when you need to slightly change the operation of a mql5 program in the debugging mode. For example, in debug mode you may need to display additional debugging information in the terminal log or create additional graphical objects in a chart.

The following example creates a Label object and sets its description and color depending on the script running mode. In order to run a script in the debug mode from MetaEditor, press F5. If you run the script from the browser window in the terminal, then the color and text of the object Label will be different.

Example:

```
//+------------------------------------------------------------------+
//|                                             Check_DEBUG_MODE.mq5 |
//|                      Copyright © 2009, MetaQuotes Software Corp. |
//|                                        https://www.metaquotes.net |
//+------------------------------------------------------------------+
#property copyright "Copyright © 2009, MetaQuotes Software Corp."
#property link      "https://www.metaquotes.net"
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//---
   string label_name="invisible_label";
   if(ObjectFind(0,label_name)<0)
     {
      Print("Object",label_name,"not found. Error code = ",GetLastError());
      //--- create Label
      ObjectCreate(0,label_name,OBJ_LABEL,0,0,0);
      //--- set X coordinate
      ObjectSetInteger(0,label_name,OBJPROP_XDISTANCE,200);
      //--- set Y coordinate
      ObjectSetInteger(0,label_name,OBJPROP_YDISTANCE,300);
      ResetLastError();
      if(IS_DEBUG_MODE) // debug mode
        {
         //--- show message about the script execution mode
         ObjectSetString(0,label_name,OBJPROP_TEXT,"DEBUG MODE");
         //--- set text color to red
         if(!ObjectSetInteger(0,label_name,OBJPROP_COLOR,clrRed))
            Print("Unable to set the color. Error",GetLastError());
        }
      else              // operation mode
        {
         ObjectSetString(0,label_name,OBJPROP_TEXT,"RELEASE MODE");
         //--- set text color to invisible
         if(!ObjectSetInteger(0,label_name,OBJPROP_COLOR,CLR_NONE))
            Print("Unable to set the color. Error ",GetLastError());
        }
      ChartRedraw();
      DebugBreak();    // here termination will occur, if we are in debug mode
     }
  }
```

 

Crypt Methods

The ENUM\_CRYPT\_METHOD enumeration is used to specify the data transformation method, used in [CryptEncode()](cryptencode.md) and [CryptDecode()](cryptdecode.md) functions.

ENUM\_CRYPT\_METHOD

| Constant | Description |
| --- | --- |
| CRYPT\_BASE64 | BASE64 |
| CRYPT\_AES128 | AES encryption with 128 bit key (16 bytes) |
| CRYPT\_AES256 | AES encryption with 256 bit key (32 bytes) |
| CRYPT\_DES | DES encryption with 56 bit key (7 bytes) |
| CRYPT\_HASH\_SHA1 | SHA1 HASH calculation |
| CRYPT\_HASH\_SHA256 | SHA256 HASH calculation |
| CRYPT\_HASH\_MD5 | MD5 HASH calculation |
| CRYPT\_ARCH\_ZIP | ZIP archives |

See also

[DebugBreak](debugbreak.md), [Executed MQL5 program properties](mql5_programm_info.md), [CryptEncode()](cryptencode.md), [CryptDecode()](cryptdecode.md)