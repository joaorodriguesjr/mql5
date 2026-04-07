CDoubleBuffer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CDoubleBuffer

[![Previous](previous.png)](crealvolumebufferrefreshcurren.md) 
[![Next](next.png)](cdoublebuffersize.md)

CDoubleBuffer

CDoubleBuffer is a base class for simplified access to data buffers of double type.

Description

The CDoubleBuffer class provides a simplified access to the data of the buffer of double type.

Declaration

```
   class CDoubleBuffer: public CArrayDouble
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayDouble](carraydouble.md)                CDoubleBuffer  Direct descendants  [CCloseBuffer](cclosebuffer.md), [CHighBuffer](chighbuffer.md), [CIndicatorBuffer](cindicatorbuffer.md), [CLowBuffer](clowbuffer.md), [COpenBuffer](copenbuffer.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Size](cdoublebuffersize.md) | Sets buffer size |
| Settings |  |
| [SetSymbolPeriod](cdoublebuffersetsymbolperiod.md) | Sets symbol and period |
| Data Access |  |
| [At](cdoublebufferat.md) | Gets the buffer element |
| Data Update |  |
| virtual [Refresh](cdoublebufferrefresh.md) | Updates the buffer |
| virtual [RefreshCurrent](cdoublebufferrefreshcurrent.md) | Updates the current value |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayDouble  [Delta](carraydoubledelta.md), [Type](carraydoubletype.md), [Save](carraydoublesave.md), [Load](carraydoubleload.md), [Reserve](carraydoublereserve.md), [Resize](carraydoubleresize.md), [Shutdown](carraydoubleshutdown.md), [Add](carraydoubleadd.md), [AddArray](carraydoubleaddarray.md), [AddArray](carraydoubleaddarray.md), [Insert](carraydoubleinsert.md), [InsertArray](carraydoubleinsertarray.md), [InsertArray](carraydoubleinsertarray.md), [AssignArray](carraydoubleassignarray.md), [AssignArray](carraydoubleassignarray.md), [At](carraydoubleat.md), operator, [Minimum](carraydoubleminimum.md), [Maximum](carraydoublemaximum.md), [Update](carraydoubleupdate.md), [Shift](carraydoubleshift.md), [Delete](carraydoubledelete.md), [DeleteRange](carraydoubledeleterange.md), [CompareArray](carraydoublecomparearray.md), [CompareArray](carraydoublecomparearray.md), [InsertSort](carraydoubleinsertsort.md), [Search](carraydoublesearch.md), [SearchGreat](carraydoublesearchgreat.md), [SearchLess](carraydoublesearchless.md), [SearchGreatOrEqual](carraydoublesearchgreatorequal.md), [SearchLessOrEqual](carraydoublesearchlessorequal.md), [SearchFirst](carraydoublesearchfirst.md), [SearchLast](carraydoublesearchlast.md), [SearchLinear](carraydoublesearchlinear.md) |