CCloseBuffer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CCloseBuffer

[![Previous](previous.png)](clowbufferrefreshcurrent.md) 
[![Next](next.png)](cclosebufferrefresh.md)

CCloseBuffer

CCloseBuffer is a class for simplified access to close prices of bars in the history.

Description

CCloseBuffer class provides a simplified access to close prices of bars in the history.

Declaration

```
   class CCloseBuffer: public CDoubleBuffer
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayDouble](carraydouble.md)                [CDoubleBuffer](cdoublebuffer.md)                    CCloseBuffer |

Class Methods by Groups

| Data Update |  |
| --- | --- |
| virtual [Refresh](cclosebufferrefresh.md) | Updates the buffer |
| virtual [RefreshCurrent](cclosebufferrefreshcurrent.md) | Updates the current value |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayDouble  [Delta](carraydoubledelta.md), [Type](carraydoubletype.md), [Save](carraydoublesave.md), [Load](carraydoubleload.md), [Reserve](carraydoublereserve.md), [Resize](carraydoubleresize.md), [Shutdown](carraydoubleshutdown.md), [Add](carraydoubleadd.md), [AddArray](carraydoubleaddarray.md), [AddArray](carraydoubleaddarray.md), [Insert](carraydoubleinsert.md), [InsertArray](carraydoubleinsertarray.md), [InsertArray](carraydoubleinsertarray.md), [AssignArray](carraydoubleassignarray.md), [AssignArray](carraydoubleassignarray.md), [At](carraydoubleat.md), operator, [Minimum](carraydoubleminimum.md), [Maximum](carraydoublemaximum.md), [Update](carraydoubleupdate.md), [Shift](carraydoubleshift.md), [Delete](carraydoubledelete.md), [DeleteRange](carraydoubledeleterange.md), [CompareArray](carraydoublecomparearray.md), [CompareArray](carraydoublecomparearray.md), [InsertSort](carraydoubleinsertsort.md), [Search](carraydoublesearch.md), [SearchGreat](carraydoublesearchgreat.md), [SearchLess](carraydoublesearchless.md), [SearchGreatOrEqual](carraydoublesearchgreatorequal.md), [SearchLessOrEqual](carraydoublesearchlessorequal.md), [SearchFirst](carraydoublesearchfirst.md), [SearchLast](carraydoublesearchlast.md), [SearchLinear](carraydoublesearchlinear.md) |
| Methods inherited from class CDoubleBuffer  [Size](cdoublebuffersize.md), [At](cdoublebufferat.md), [SetSymbolPeriod](cdoublebuffersetsymbolperiod.md) |