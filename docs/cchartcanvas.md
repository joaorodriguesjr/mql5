CCHARTCANVAS



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md) / CChartCanvas

[![Previous](previous.png)](ccanvaswidth.md) 
[![Next](next.png)](cchartcanvascolorbackground.md)

CChartCanvas

Base class for implementing classes, which are used for drawing charts and their elements.  

Description

This class includes methods for working with the basic elements of any chart: coordinate axes and their marks, chart legend, grid, background, etc. Here you can customize the options for displaying elements: visibility, text color, etc.

Declaration

```
   class CChartCanvas : public CCanvas
```

Title

```
   #include <Canvas\Charts\ChartCanvas.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CCanvas](ccanvas.md)        CChartCanvas  Direct descendants  [CHistogramChart](chistogramchart.md), [CLineChart](clinechart.md), [CPieChart](cpiechart.md) |

Class methods

| Method | Action |
| --- | --- |
| [ColorBackground](cchartcanvascolorbackground.md) | Returns and sets the background color. |
| [ColorBorder](cchartcanvascolorborder.md) | Returns and sets the border color. |
| [ColorText](cchartcanvascolortext.md) | Returns and sets the text color. |
| [ColorGrid](cchartcanvascolorgrid.md) | Returns and sets the grid color. |
| [MaxData](cchartcanvasmaxdata.md) | Returns and sets the maximum amount of data (series) allowed. |
| [MaxDescrLen](cchartcanvasmaxdescrlen.md) | Returns and sets the maximum length of the descriptors. |
| [ShowFlags](cchartcanvasshowflags.md) | Returns and sets the visibility flag of the chart elements. |
| [IsShowLegend](cchartcanvasisshowlegend.md) | Returns and sets the visibility flag of the legend on the chart. |
| [IsShowScaleLeft](cchartcanvasisshowscaleleft.md) | Returns the visibility flag of the scale of values on the left. |
| [IsShowScaleRight](cchartcanvasisshowscaleright.md) | Returns the visibility flag of the scale of values on the right. |
| [IsShowScaleTop](cchartcanvasisshowscaletop.md) | Returns the visibility flag of the scale of values at the top. |
| [IsShowScaleBottom](cchartcanvasisshowscalebottom.md) | Returns the visibility flag of the scale of values at the bottom. |
| [IsShowGrid](cchartcanvasisshowgrid.md) | Returns the visibility flag of the grid on the chart. |
| [IsShowDescriptors](cchartcanvasisshowdescriptors.md) | Returns the visibility flag of the descriptors on the chart. |
| [IsShowPercent](cchartcanvasisshowpercent.md) | Returns the visibility flag of the percentages on the chart. |
| [VScaleMin](cchartcanvasvscalemin.md) | Returns and sets the minimum on the vertical scale of values. |
| [VScaleMax](cchartcanvasvscalemax.md) | Returns and sets the maximum on the vertical scale of values. |
| [NumGrid](cchartcanvasnumgrid.md) | Returns and sets the number of vertical scale divisions when plotting the chart grid. |
| [DataOffset](cchartcanvasdataoffset.md) | Returns and sets the data offset value. |
| [DataTotal](cchartcanvasdatatotal.md) | Returns the total number of data series on the chart. |
| [DrawDescriptors](cchartcanvasdrawdescriptors.md) | Virtual method for drawing descriptors. |
| [DrawData](cchartcanvasdrawdata.md) | Virtual method for drawing data series at the specified index. |
| [Create](cchartcanvascreate.md) | Virtual method that creates a graphical resource. |
| [AllowedShowFlags](cchartcanvasallowedshowflags.md) | Sets the set of allowed visibility flags for chart elements. |
| [ShowLegend](cchartcanvasshowlegend.md) | Sets the visibility flag for the legend. |
| [ShowScaleLeft](cchartcanvasshowscaleleft.md) | Sets the visibility flag for the left scale. |
| [ShowScaleRight](cchartcanvasshowscaleright.md) | Sets the visibility flag for the right scale. |
| [ShowScaleTop](cchartcanvasshowscaletop.md) | Sets the visibility flag for the top scale. |
| [ShowScaleBottom](cchartcanvasshowscalebottom.md) | Sets the visibility flag for the bottom scale. |
| [ShowGrid](cchartcanvasshowgrid.md) | Sets the visibility flag for the grid. |
| [ShowDescriptors](cchartcanvasshowdescriptors.md) | Sets the visibility flag for the descriptors. |
| [ShowValue](cchartcanvasshowvalue.md) | Sets the visibility flag for the values. |
| [ShowPercent](cchartcanvasshowpercent.md) | Sets the visibility flag for the percentages. |
| [LegendAlignment](cchartcanvaslegendalignment.md) | Sets the text alignment for the legend. |
| [Accumulative](cchartcanvasaccumulative.md) | Sets the value accumulation flag for the series. |
| [VScaleParams](cchartcanvasvscaleparams.md) | Sets the parameters for the vertical scale of values. |
| [DescriptorUpdate](cchartcanvasdescriptorupdate.md) | Updates the value of the series descriptor (at the specified position). |
| [ColorUpdate](cchartcanvascolorupdate.md) | Updates the series colors (at the specified position). |
| [ValuesCheck](cchartcanvasvaluescheck.md) | Performs internal calculations for plotting the chart. |
| [Redraw](cchartcanvasredraw.md) | Redraw the chart. |
| [DrawBackground](cchartcanvasdrawbackground.md) | Draws the background. |
| [DrawLegend](cchartcanvasdrawlegend.md) | Redraws the legend. |
| [DrawLegendVertical](cchartcanvasdrawlegendvertical.md) | Draws a vertical legend. |
| [DrawLegendHorizontal](cchartcanvasdrawlegendhorizontal.md) | Draws a horizontal legend. |
| [CalcScales](cchartcanvascalcscales.md) | Calculates the coordinates of the scale. |
| [DrawScales](cchartcanvasdrawscales.md) | Redraws all scales of values. |
| [DrawScaleLeft](cchartcanvasdrawscaleleft.md) | Redraws the left scale of values. |
| [DrawScaleRight](cchartcanvasdrawscaleright.md) | Redraws the right scale of values. |
| [DrawScaleTop](cchartcanvasdrawscaletop.md) | Redraws the top scale of values |
| [DrawScaleBottom](cchartcanvasdrawscalebottom.md) | Redraws the bottom value scale. |
| [DrawGrid](cchartcanvasdrawgrid.md) | Redraw the chart. |
| [DrawChart](cchartcanvasdrawchart.md) | Redraw the chart. |

|  |
| --- |
| Methods inherited from class CCanvas  [CreateBitmap](ccanvascreatebitmap.md), [CreateBitmap](ccanvascreatebitmap.md), [CreateBitmapLabel](ccanvascreatebitmaplabel.md), [CreateBitmapLabel](ccanvascreatebitmaplabel.md), [Attach](ccanvasattach.md), [Attach](ccanvasattach.md), [Destroy](ccanvasdestroy.md), [ChartObjectName](ccanvaschartobjectname.md), [ResourceName](ccanvasresourcename.md), [Width](ccanvaswidth.md), [Height](ccanvasheight.md), [Update](ccanvasupdate.md), [Resize](ccanvasresize.md), [Erase](ccanvaserase.md), [PixelGet](ccanvaspixelget.md), [PixelSet](ccanvaspixelset.md), [LineVertical](ccanvaslinevertical.md), [LineHorizontal](ccanvaslinehorizontal.md), [Line](ccanvasline.md), [Polyline](ccanvaspolyline.md), [Polygon](ccanvaspolygon.md), [Rectangle](ccanvasrectangle.md), [Triangle](ccanvastriangle.md), [Circle](ccanvascircle.md), [Ellipse](ccanvasellipse.md), [Arc](ccanvasarc.md), [Arc](ccanvasarc.md), [Arc](ccanvasarc.md), [Pie](ccanvaspie.md), [Pie](ccanvaspie.md), [FillRectangle](ccanvasfillrectangle.md), [FillTriangle](ccanvasfilltriangle.md), [FillPolygon](ccanvasfillpolygon.md), [FillCircle](ccanvasfillcircle.md), [FillEllipse](ccanvasfillellipse.md), [Fill](ccanvasfill.md), [Fill](ccanvasfill.md), [PixelSetAA](ccanvaspixelsetaa.md), [LineAA](ccanvaslineaa.md), [PolylineAA](ccanvaspolylineaa.md), [PolygonAA](ccanvaspolygonaa.md), [TriangleAA](ccanvastriangleaa.md), [CircleAA](ccanvascircleaa.md), [EllipseAA](ccanvasellipseaa.md), [LineWu](ccanvaslinewu.md), [PolylineWu](ccanvaspolylinewu.md), [PolygonWu](ccanvaspolygonwu.md), [TriangleWu](ccanvastrianglewu.md), [CircleWu](ccanvascirclewu.md), [EllipseWu](ccanvasellipsewu.md), [LineThickVertical](ccanvaslinethickvertical.md), [LineThickHorizontal](ccanvaslinethickhorizontal.md), [LineThick](ccanvaslinethick.md), [PolylineThick](ccanvaspolylinethick.md), [PolygonThick](ccanvaspolygonthick.md), [PolylineSmooth](ccanvaspolylinesmooth.md), [PolygonSmooth](ccanvaspolygonsmooth.md), [FontSet](ccanvasfontset.md), [FontNameSet](ccanvasfontnameset.md), [FontSizeSet](ccanvasfontsizeset.md), [FontFlagsSet](ccanvasfontflagsset.md), [FontAngleSet](ccanvasfontangleset.md), [FontGet](ccanvasfontget.md), [FontNameGet](ccanvasfontnameget.md), [FontSizeGet](ccanvasfontsizeget.md), [FontFlagsGet](ccanvasfontflagsget.md), [FontAngleGet](ccanvasfontangleget.md), [TextOut](ccanvastextout.md), [TextWidth](ccanvastextwidth.md), [TextHeight](ccanvastextheight.md), [TextSize](ccanvastextsize.md), [GetDefaultColor](ccanvasgetdefaultcolor.md), [TransparentLevelSet](ccanvastransparentlevelset.md), [LoadFromFile](ccanvasloadfromfile.md), LineStyleGet, [LineStyleSet](ccanvaslinestyleset.md) |