Custom graphics



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Custom Graphics](canvasgraphics.md) / CCanvas

[![Previous](previous.png)](canvasgraphics.md) 
[![Next](next.png)](ccanvasattach.md)

CCanvas

CCanvas is a class for simplified creation of custom images.

Description

CCanvas provides creation of a graphical resource (with or without binding to a chart object) and drawing graphic primitives.

Declaration

```
   class CCanvas
```

Title

```
   #include <Canvas\Canvas.mqh>
```

|  |
| --- |
| Inheritance hierarchy    CCanvas  Direct descendants  [CChartCanvas](cchartcanvas.md), CFlameCanvas |

Class methods by groups

| Creating |  |
| --- | --- |
| [Attach](ccanvasattach.md) | Attaches the OBJ\_BITMAP\_LABEL object to an instance of the CCanvas class |
| [Create](ccanvascreate.md) | Creates a graphical resource without binding to a chart object |
| [CreateBitmap](ccanvascreatebitmap.md) | Create a graphical resource bound to a chart object |
| [CreateBitmapLabel](ccanvascreatebitmaplabel.md) | Create a graphical resource bound to a chart object |
| [Destroy](ccanvasdestroy.md) | Destroys a graphical resource |
| Properties |  |
| [ChartObjectName](ccanvaschartobjectname.md) | Gets the name of a bound chart object |
| [ResourceName](ccanvasresourcename.md) | Gets the name of a graphical resource |
| [Width](ccanvaswidth.md) | Gets the width of a graphical resource |
| [Height](ccanvasheight.md) | Gets the height of a graphical resource |
| [LineStyleSet](ccanvaslinestyleset.md) | Sets the line style |
| Updates an object on the screen |  |
| [Update](ccanvasupdate.md) | Displays changes on the screen |
| [Resize](ccanvasresize.md) | Resizes a graphical resource |
| Erasing/Filling with color |  |
| [Erase](ccanvaserase.md) | Erases or fills with the specified color |
| Data access |  |
| [PixelGet](ccanvaspixelget.md) | Gets a color of the dot with the specified coordinates |
| [PixelSet](ccanvaspixelset.md) | Sets color of the dot with the specified coordinates |
| Draws primitives |  |
| [LineVertical](ccanvaslinevertical.md) | Draws a vertical line |
| [LineHorizontal](ccanvaslinehorizontal.md) | Draws a horizontal line |
| [Line](ccanvasline.md) | Draws a freehand line |
| [Polyline](ccanvaspolyline.md) | Draws a polyline |
| [Polygon](ccanvaspolygon.md) | Draws a polygon |
| [Rectangle](ccanvasrectangle.md) | Draws a rectangle |
| [Circle](ccanvascircle.md) | Draws a circle |
| [Triangle](ccanvastriangle.md) | Draws a triangle |
| [Ellipse](ccanvasellipse.md) | Draws an ellipse |
| [Arc](ccanvasarc.md) | Draws an ellipse arc |
| [Pie](ccanvaspie.md) | Draws an ellipse sector |
| Draws filled primitives |  |
| [FillRectangle](ccanvasfillrectangle.md) | Draws a filled rectangle |
| [FillCircle](ccanvasfillcircle.md) | Draws a filled circle |
| [FillTriangle](ccanvasfilltriangle.md) | Draws a filled triangle |
| [FillPolygon](ccanvasfillpolygon.md) | Draws a filled polygon |
| [FillEllipse](ccanvasfillellipse.md) | Draws a filled ellipse |
| [Fill](ccanvasfill.md) | Fills an area |
| Draws primitives with antialiasing |  |
| [PixelSetAA](ccanvaspixelsetaa.md) | Draws a pixel |
| [LineAA](ccanvaslineaa.md) | Draws a line |
| [PolylineAA](ccanvaspolylineaa.md) | Draws a polyline |
| [PolygonAA](ccanvaspolygonaa.md) | Draws a polygon |
| [TriangleAA](ccanvastriangleaa.md) | Draws a triangle |
| [CircleAA](ccanvascircleaa.md) | Draws a circle |
| [EllipseAA](ccanvasellipseaa.md) | Draws an ellipse |
| [LineWu](ccanvaslinewu.md) | Draws a line |
| [PolylineWu](ccanvaspolylinewu.md) | Draws a polyline |
| [PolygonWu](ccanvaspolygonwu.md) | Draws a polygon |
| [TriangleWu](ccanvastrianglewu.md) | Draws a triangle |
| [CircleWu](ccanvascirclewu.md) | Draws a circle |
| [EllipseWu](ccanvasellipsewu.md) | Draws an ellipse |
| [LineThick](ccanvaslinethick.md) | Draws a segment of a freehand line having a specified width using antialiasing algorithm. |
| [LineThickVertical](ccanvaslinethickvertical.md) | Draws a vertical segment of a freehand line having a specified width using antialiasing algorithm. |
| [LineThickHorizontal](ccanvaslinethickhorizontal.md) | Draws a horizontal segment of a freehand line having a specified width using antialiasing algorithm. |
| [PolygonSmooth](ccanvaspolygonsmooth.md) | Draws a polygon with a specified width using two antialiasing algorithms |
| [PolygonThick](ccanvaspolygonthick.md) | Draws a polygon with a specified width using antialiasing algorithm |
| [PolylineSmooth](ccanvaspolylinesmooth.md) | Draws a polyline with a specified width using two antialiasing algorithms |
| [PolylineThick](ccanvaspolylinethick.md) | Draws a polyline with a specified width using antialiasing algorithm |
| Text |  |
| [FontSet](ccanvasfontset.md) | Sets font parameters |
| [FontNameSet](ccanvasfontnameset.md) | Sets font name |
| [FontSizeSet](ccanvasfontsizeset.md) | Sets font size |
| [FontFlagsSet](ccanvasfontflagsset.md) | Sets font flags |
| [FontAngleSet](ccanvasfontangleset.md) | Sets font slope angle |
| [FontGet](ccanvasfontget.md) | Gets font parameters |
| [FontNameGet](ccanvasfontnameget.md) | Gets font name |
| [FontSizeGet](ccanvasfontsizeget.md) | Gets font size |
| [FontFlagsGet](ccanvasfontflagsget.md) | Gets font flags |
| [FontAngleGet](ccanvasfontangleget.md) | Gets font slope angle |
| [TextOut](ccanvastextout.md) | Displays text |
| [TextWidth](ccanvastextwidth.md) | Gets the text width |
| [TextHeight](ccanvastextheight.md) | Gets the text height |
| [TextSize](ccanvastextsize.md) | Gets the text size |
| Transparency |  |
| [TransparentLevelSet](ccanvastransparentlevelset.md) | Sets transparency level |
| Input/output |  |
| [LoadFromFile](ccanvasloadfromfile.md) | Reads an image from a BMP file |