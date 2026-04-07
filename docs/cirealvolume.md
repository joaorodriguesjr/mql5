CiRealVolume



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Timeseries classes](timeseries.md) / CiRealVolume

[![Previous](previous.png)](citickvolumerefresh.md) 
[![Next](next.png)](cirealvolumecreate.md)

CiRealVolume

CiRealVolume is a class designed for access to real volumes of the bars in the history.

Description

CiRealVolume class provides an access to real volumes of the bars in the history.

Declaration

```
   class CiRealVolume: public CSeries
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                [CSeries](cseries.md)                    CiRealVolume |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cirealvolumecreate.md) | Creates a series |
| [BufferResize](cirealvolumebufferresize.md) | Sets buffer size |
| Data Access |  |
| [GetData](cirealvolumegetdata.md) | Gets the series data |
| Data Update |  |
| [Refresh](cirealvolumerefresh.md) | Updates the series data |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Type](carrayobjtype.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |
| Methods inherited from class CSeries  [Name](cseriesname.md), [BuffersTotal](cseriesbufferstotal.md), [BufferSize](cseriesbuffersize.md), [Timeframe](cseriestimeframe.md), [Symbol](cseriessymbol.md), [Period](cseriesperiod.md), [PeriodDescription](cseriesperioddescription.md), [RefreshCurrent](cseriesrefreshcurrent.md) |