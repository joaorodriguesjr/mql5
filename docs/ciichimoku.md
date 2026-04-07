CiIchimoku



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Trend Indicators](trendindicators.md) / CiIchimoku

[![Previous](previous.png)](cienvelopestype.md) 
[![Next](next.png)](ciichimokutenkansenperiod.md)

CiIchimoku

CiIchimoku is a class intended for using the Ichimoku Kinko Hyo technical indicator.

Description

CiIchimoku class provides the creation, setup, and access to the data of the Ichimoku Kinko Hyo indicator.

Declaration

```
   class CiIchimoku: public CIndicator
```

Title

```
   #include <Indicators\Trend.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                [CSeries](cseries.md)                    [CIndicator](cindicator.md)                        CiIchimoku |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [TenkanSenPeriod](ciichimokutenkansenperiod.md) | Returns the TenkanSen period |
| [KijunSenPeriod](ciichimokukijunsenperiod.md) | Returns the KijunSen period |
| [SenkouSpanBPeriod](ciichimokusenkouspanb.md) | Returns the SenkouSpanB period |
| Create |  |
| [Create](ciichimokucreate.md) | Creates the indicator |
| Data Access |  |
| [TenkanSen](ciichimokutenkansen.md) | Returns the buffer element of the TenkanSen line |
| [KijunSen](ciichimokukijunsen.md) | Returns the buffer element of the KijunSen line |
| [SenkouSpanA](ciichimokusenkouspana.md) | Returns the buffer element of the SenkouSpanA line |
| [SenkouSpanB](ciichimokusenkouspanb.md) | Returns the buffer element of the SenkouSpanB line |
| [ChinkouSpan](ciichimokuchinkouspan.md) | Returns the buffer element of the ChikouSpan line |
| Input/output |  |
| virtual [Type](ciichimokutype.md) | Virtual identification method |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |
| Methods inherited from class CSeries  [Name](cseriesname.md), [BuffersTotal](cseriesbufferstotal.md), [BufferSize](cseriesbuffersize.md), [Timeframe](cseriestimeframe.md), [Symbol](cseriessymbol.md), [Period](cseriesperiod.md), [PeriodDescription](cseriesperioddescription.md), [RefreshCurrent](cseriesrefreshcurrent.md) |
| Methods inherited from class CIndicator  [Handle](cindicatorhandle.md), [Status](cindicatorstatus.md), [FullRelease](cindicatorfullrelease.md), Redrawer, [Create](cindicatorcreate.md), [BufferResize](cindicatorbufferresize.md), [BarsCalculated](cindicatorbarscalculated.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [Minimum](cindicatorminimum.md), [MinValue](cindicatorminvalue.md), [Maximum](cindicatormaximum.md), [MaxValue](cindicatormaxvalue.md), [Refresh](cindicatorrefresh.md), [AddToChart](cindicatoraddtochart.md), [DeleteFromChart](cindicatordeletefromchart.md), [MethodDescription](cindicatormethoddescription.md), [PriceDescription](cindicatorpricedescription.md), [VolumeDescription](cindicatorvolumedescription.md) |