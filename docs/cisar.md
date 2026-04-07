CiSAR



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md) / CiSAR

[![Previous](previous.png)](cimatype.md) 
[![Next](next.png)](cisarsarstep.md)

CiSAR

CiSAR is a class intended for using the Parabolic Stop And Reverse System technical indicator.

Description

CiSAR class provides the creation, setup, and access to the data of the Parabolic Stop And Reverse System indicator.

Declaration

```
   class CiSAR: public CIndicator
```

Title

```
   #include <Indicators\Trend.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                [CSeries](cseries.md)                    [CIndicator](cindicator.md)                        CiSAR |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [SarStep](cisarsarstep.md) | Returns the step of price increment |
| [Maximum](cisarmaximum.md) | Returns the maximum value of the step |
| Create Methods |  |
| [Create](cisarcreate.md) | Creates the indicator |
| Data Access Methods |  |
| [Main](cisarmain.md) | Returns the buffer data |
| Input/output |  |
| virtual [Type](cisartype.md) | Virtual identification method |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |
| Methods inherited from class CSeries  [Name](cseriesname.md), [BuffersTotal](cseriesbufferstotal.md), [BufferSize](cseriesbuffersize.md), [Timeframe](cseriestimeframe.md), [Symbol](cseriessymbol.md), [Period](cseriesperiod.md), [PeriodDescription](cseriesperioddescription.md), [RefreshCurrent](cseriesrefreshcurrent.md) |
| Methods inherited from class CIndicator  [Handle](cindicatorhandle.md), [Status](cindicatorstatus.md), [FullRelease](cindicatorfullrelease.md), Redrawer, [Create](cindicatorcreate.md), [BufferResize](cindicatorbufferresize.md), [BarsCalculated](cindicatorbarscalculated.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [Minimum](cindicatorminimum.md), [MinValue](cindicatorminvalue.md), [Maximum](cindicatormaximum.md), [MaxValue](cindicatormaxvalue.md), [Refresh](cindicatorrefresh.md), [AddToChart](cindicatoraddtochart.md), [DeleteFromChart](cindicatordeletefromchart.md), [MethodDescription](cindicatormethoddescription.md), [PriceDescription](cindicatorpricedescription.md), [VolumeDescription](cindicatorvolumedescription.md) |