CAxis



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Scientific Charts](graphics.md) / CAxis

[![Previous](previous.png)](graphplot.md) 
[![Next](next.png)](caxisautoscale.md)

CAxis

CAxis is an auxiliary graphics library class for working with the coordinate axes.

Description

The CAxis class receives and stores various parameters of the coordinate axes. The class implements the ability to auto scale the coordinate axes dynamically.

Declaration

```
   class CAxis
```

Title

```
   #include <Graphics\Axis.mqh>
```

Class methods

| Method | Description |
| --- | --- |
| [AutoScale](caxisautoscale.md) | Get/set the auto-scaling flag |
| [Min](caxismin.md) | Get/set the minimum axis value |
| [Max](caxismax.md) | Get/set the maximum axis value |
| [Step](caxisstep.md) | Get the step value by axis |
| [Name](caxisname.md) | Get/set the axis name |
| [Color](caxiscolor.md) | Get/set the axis color |
| [ValuesSize](caxisvaluessize.md) | Get/set the size of the axis numbers |
| [ValuesWidth](caxisvalueswidth.md) | Get/set the maximum displayed length of the axis numbers |
| [ValuesFormat](caxisvaluesformat.md) | Get/set the format of the axis numbers |
| [ValuesDateTimeMode](caxisvaluesdatetimemode.md) | Get the format of converting a date into a string. |
| [ValuesFunctionFormat](caxisvaluesfunctionformat.md) | Get the pointer to the function defining the format of displaying values on the axis. |
| [ValuesFunctionFormatCBData](caxisvaluesfunctionformatcbdata.md) | Get the pointer to the object that may contain additional data on converting axis values. |
| [NameSize](caxisnamesize.md) | Get/set the font size of the axis name |
| [ZeroLever](caxiszerolever.md) | Get/set the "zero lever" value |
| [DefaultStep](caxisdefaultstep.md) | Get/set the initial step value by axis |
| [MaxLabels](caxismaxlabels.md) | Get/set the maximum amount of numbers on the axis |
| [MinGrace](caxismingrace.md) | Get/set the "tolerance" value for the axis minimum |
| [MaxGrace](caxismaxgrace.md) | Get/set the "tolerance" value for the axis maximum |
| [SelectAxisScale](caxisselectaxisscale.md) | Auto scale the axis. |