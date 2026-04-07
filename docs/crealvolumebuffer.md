CRealVolumeBuffer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CRealVolumeBuffer

[![Previous](previous.png)](ctickvolumebufferrefreshcurrent.md) 
[![Next](next.png)](crealvolumebuffersize.md)

CRealVolumeBuffer

CRealVolumeBuffer is a class for simplified access to real volumes of bars in the history.

Description

CTickVolumeBuffer class provides a simplified access to real volumes of bars in the history.

Declaration

```
   class CRealVolumeBuffer: public CArrayLong
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayLong](carraylong.md)                CRealVolumeBuffer |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Size](crealvolumebuffersize.md) | Sets buffer size |
| Settings |  |
| [SetSymbolPeriod](crealvolumebuffersetsymbolperi.md) | Sets symbol and period |
| Data Access |  |
| [At](crealvolumebufferat.md) | Gets the buffer element |
| Data Update |  |
| virtual [Refresh](crealvolumebufferrefresh.md) | Updates the buffer |
| virtual [RefreshCurrent](crealvolumebufferrefreshcurren.md) | Updates the current value |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayLong  [Type](carraylongtype.md), [Save](carraylongsave.md), [Load](carraylongload.md), [Reserve](carraylongreserve.md), [Resize](carraylongresize.md), [Shutdown](carraylongshutdown.md), [Add](carraylongadd.md), [AddArray](carraylongaddarray.md), [AddArray](carraylongaddarray.md), [Insert](carraylonginsert.md), [InsertArray](carraylonginsertarray.md), [InsertArray](carraylonginsertarray.md), [AssignArray](carraylongassignarray.md), [AssignArray](carraylongassignarray.md), [At](carraylongat.md), operator, Minimum, Maximum, [Update](carraylongupdate.md), [Shift](carraylongshift.md), [Delete](carraylongdelete.md), [DeleteRange](carraylongdeleterange.md), [CompareArray](carraylongcomparearray.md), [CompareArray](carraylongcomparearray.md), [InsertSort](carraylonginsertsort.md), [Search](carraylongsearch.md), [SearchGreat](carraylongsearchgreat.md), [SearchLess](carraylongsearchless.md), [SearchGreatOrEqual](carraylongsearchgreatorequal.md), [SearchLessOrEqual](carraylongsearchlessorequal.md), [SearchFirst](carraylongsearchfirst.md), [SearchLast](carraylongsearchlast.md), [SearchLinear](carraylongsearchlinear.md) |