CCurve



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Scientific Charts](graphics.md) / CCurve

[![Previous](previous.png)](ccolorgeneratorreset.md) 
[![Next](next.png)](ccurvetype.md)

CCurve

The CCurve class works with the properties of the curves generated on the chart.

Description

The CCurve class sets, installs and receives the coordinates and various properties of the curves when working with the CGraphic class.

There are three curve plotting modes: dots, lines and histogram. Separate parameters are implemented for each plotting mode in the class.

Declaration

```
   class CCurve : public CObject
```

Title

```
   #include <Graphics\Curve.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CCurve |

Class methods

| Method | Description |
| --- | --- |
| [Type](ccurvetype.md) | Get the curve type |
| [Name](ccurvename.md) | Get the curve name |
| [Color](ccurvecolor.md) | Get the curve color |
| [XMax](ccurvexmax.md) | Get the maximum value of the X function |
| [XMin](ccurvexmin.md) | Get the minimum value of the X function |
| [YMax](ccurveymax.md) | Get the maximum value of the Y function |
| [YMin](ccurveymin.md) | Get the minimum value of the Y function |
| [Size](ccurvesize.md) | Get the number of dots defining a curve |
| [PointsSize](ccurvepointssize.md) | Get/set the linear size of dots defining a curve |
| [PointsFill](ccurvepointsfill.md) | Get/set the flag for filling dots defining a curve |
| [PointsColor](ccurvepointscolor.md) | Get/set the dot filling color |
| [GetX](ccurvegetx.md) | Gets X values of all curve dots to the array |
| [GetY](ccurvegety.md) | Gets Y values of all curve dots to the array |
| [LinesStyle](ccurvelinesstyle.md) | Get/set a line style when plotting a curve using lines |
| [LinesIsSmooth](ccurvelinesissmooth.md) | Get/set the smoothing flag when drawing using lines |
| [LinesSmoothTension](ccurvelinessmoothtension.md) | Get/set the curve smoothing parameter when drawing using lines |
| [LinesSmoothStep](ccurvelinessmoothstep.md) | Get/set the length of the approximating lines for smoothing when plotting by lines |
| [LinesWidth](ccurvelineswidth.md) | Get/set a line width when plotting a curve using lines |
| [HistogramWidth](ccurvehistogramwidth.md) | Get/set the width of columns when plotting using a histogram |
| [CustomPlotCBData](ccurvecustomplotcbdata.md) | Get/set the pointer to the object to be used in the custom curve plotting mode. |
| [CustomPlotFunction](ccurvecustomplotfunction.md) | Get/set the pointer to the function implementing the custom curve plotting mode. |
| [PointsType](ccurvepointstype.md) | Get/set the flag pointing at the type of dots used when plotting a dotted curve. |
| [StepsDimension](ccurvestepsdimension.md) | Get/set the value indicating the dimension used in step-type curve rendering. |
| [TrendLineCoefficients](ccurvetrendlinecoefficients.md) | Get/set trend line ratios for writing them into an array. |
| [TrendLineColor](ccurvetrendlinecolor.md) | Get/set a color of a trend line for a curve. |
| [TrendLineVisible](ccurvetrendlinevisible.md) | Get/set the trend line visibility flag. |
| [Update](ccurveupdate.md) | Update the curve coordinates. |
| [Visible](ccurvevisible.md) | Get/set the flag defining if a function is visible on the chart. |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Compare](cobjectcompare.md) |