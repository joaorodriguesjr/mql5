CSeries



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CSeries

[![Previous](previous.png)](cindicatorbufferrefreshcurrent.md) 
[![Next](next.png)](cseriesname.md)

CSeries

CSeries is a base class for an access to the timeseries data of the Standard Library.

Description

CSeries class provides the simplified access to all the MQL5 API general functions related to working with the series data for all its descendants (timeseries and indicator classes).

Declaration

```
   class CSeries: public CArrayObj
```

Title

```
   #include <Indicators\Series.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                CSeries  Direct descendants  [CIndicator](cindicator.md), [CiRealVolume](cirealvolume.md), [CiSpread](cispread.md), [CiTickVolume](citickvolume.md), [CiTime](citime.md), [CPriceSeries](cpriceseries.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Name](cseriesname.md) | Gets the name of timeseries or indicator |
| [BuffersTotal](cseriesbufferstotal.md) | Gets the number of buffers of timeseries or indicator |
| [Timeframe](cseriestimeframe.md) | Gets the timeframe flag of timeseries or indicator |
| [Symbol](cseriessymbol.md) | Gets the symbol of timeseries or indicator |
| [Period](cseriesperiod.md) | Gets the period of timeseries or indicator |
| [RefreshCurrent](cseriesrefreshcurrent.md) | Sets/resets the flag of updating the current data |
| Data Access |  |
| virtual [BufferResize](cseriesbufferresize.md) | Sets buffer size of timeseries or indicator |
| Data Update |  |
| virtual [Refresh](cseriesrefresh.md) | Update the data of timeseries or indicator |
| [PeriodDescription](cseriesperioddescription.md) | Transforms [ENUM\_TIMEFRAMES](enum_timeframes.md) into a string |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Type](carrayobjtype.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |