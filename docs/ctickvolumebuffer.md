CTickVolumeBuffer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CTickVolumeBuffer

[![Previous](previous.png)](ctimebufferrefreshcurrent.md) 
[![Next](next.png)](ctickvolumebuffersize.md)

CTickVolumeBuffer

CTickVolumeBuffer is a class for simplified access to tick volumes of bars in the history.

Description

The CTickVolumeBuffer class provides a simplified access to tick volumes of bars in the history.

Declaration

```
   class CTickVolumeBuffer: public CArrayLong
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayLong](carraylong.md)                CTickVolumeBuffer |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Size](ctickvolumebuffersize.md) | Sets buffer size |
| Settings |  |
| [SetSymbolPeriod](ctickvolumebuffersetsymbolperi.md) | Sets symbol and period |
| Data Access Methods |  |
| [At](ctickvolumebufferat.md) | Gets the buffer element by index |
| Data Update Methods |  |
| virtual [Refresh](ctickvolumebufferrefresh.md) | Updates the buffer |
| virtual [RefreshCurrent](ctickvolumebufferrefreshcurrent.md) | Updates the current value |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayLong  [Type](carraylongtype.md), [Save](carraylongsave.md), [Load](carraylongload.md), [Reserve](carraylongreserve.md), [Resize](carraylongresize.md), [Shutdown](carraylongshutdown.md), [Add](carraylongadd.md), [AddArray](carraylongaddarray.md), [AddArray](carraylongaddarray.md), [Insert](carraylonginsert.md), [InsertArray](carraylonginsertarray.md), [InsertArray](carraylonginsertarray.md), [AssignArray](carraylongassignarray.md), [AssignArray](carraylongassignarray.md), [At](carraylongat.md), operator, Minimum, Maximum, [Update](carraylongupdate.md), [Shift](carraylongshift.md), [Delete](carraylongdelete.md), [DeleteRange](carraylongdeleterange.md), [CompareArray](carraylongcomparearray.md), [CompareArray](carraylongcomparearray.md), [InsertSort](carraylonginsertsort.md), [Search](carraylongsearch.md), [SearchGreat](carraylongsearchgreat.md), [SearchLess](carraylongsearchless.md), [SearchGreatOrEqual](carraylongsearchgreatorequal.md), [SearchLessOrEqual](carraylongsearchlessorequal.md), [SearchFirst](carraylongsearchfirst.md), [SearchLast](carraylongsearchlast.md), [SearchLinear](carraylongsearchlinear.md) |