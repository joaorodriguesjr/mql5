CPriceSeries



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CPriceSeries

[![Previous](previous.png)](cseriesperioddescription.md) 
[![Next](next.png)](cpriceseriesbufferresize.md)

CPriceSeries

CPriceSeries is a base class for access to the price data.

Description

CSeries class provides the simplified access to MQL5 API general functions for working with price data to all its descendants.

Declaration

```
   class CPriceSeries: public CSeries
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                [CSeries](cseries.md)                    CPriceSeries  Direct descendants  [CiClose](ciclose.md), [CiHigh](cihigh.md), [CiLow](cilow.md), [CiOpen](ciopen.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| virtual [BufferResize](cpriceseriesbufferresize.md) | Sets size of the series buffer |
| Data Access |  |
| virtual [GetData](cpriceseriesgetdata.md) | Gets the specified series buffer element |
| Data Update |  |
| virtual [Refresh](cpriceseriesrefresh.md) | Updates timeseries data |
| Search for Extreme Values |  |
| virtual [MinIndex](cpriceseriesminindex.md) | Gets the index of minimal value in the specified range |
| virtual [MinValue](cpriceseriesminvalue.md) | Gets the minimal value in the specified range |
| virtual [MaxIndex](cpriceseriesmaxindex.md) | Gets the index of maximal value in the specified range |
| virtual [MaxValue](cpriceseriesmaxvalue.md) | Gets the maximal value in the specified range |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Type](carrayobjtype.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |
| Methods inherited from class CSeries  [Name](cseriesname.md), [BuffersTotal](cseriesbufferstotal.md), [BufferSize](cseriesbuffersize.md), [Timeframe](cseriestimeframe.md), [Symbol](cseriessymbol.md), [Period](cseriesperiod.md), [PeriodDescription](cseriesperioddescription.md), [RefreshCurrent](cseriesrefreshcurrent.md) |