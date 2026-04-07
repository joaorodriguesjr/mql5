CSpreadBuffer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CSpreadBuffer

[![Previous](previous.png)](cindicators.md) 
[![Next](next.png)](cspreadbuffersize.md)

CSpreadBuffer

CSpreadBuffer is a class for simplified access to spreads of the bars in the history.

Description

The CSpreadBuffer class provides a simplified access to spreads of the bars in the history.

Declaration

```
   class CSpreadBuffer: public CArrayInt
```

Title

```
   #include <Indicators\TimeSeries.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayInt](carrayint.md)                CSpreadBuffer |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Size](cspreadbuffersize.md) | Sets buffer size |
| Settings |  |
| [SetSymbolPeriod](cspreadbuffersetsymbolperiod.md) | Sets symbol and period |
| Data Access |  |
| [At](cspreadbufferat.md) | Gets the buffer element |
| Data Update |  |
| virtual [Refresh](cspreadbufferrefresh.md) | Updates the buffer |
| virtual [RefreshCurrent](cspreadbufferrefreshcurrent.md) | Updates the current value |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayInt  [Type](carrayinttype.md), [Save](carrayintsave.md), [Load](carrayintload.md), [Reserve](carrayintreserve.md), [Resize](carrayintresize.md), [Shutdown](carrayintshutdown.md), [Add](carrayintadd.md), [AddArray](carrayintaddarray.md), [AddArray](carrayintaddarray.md), [Insert](carrayintinsert.md), [InsertArray](carrayintinsertarray.md), [InsertArray](carrayintinsertarray.md), [AssignArray](carrayintassignarray.md), [AssignArray](carrayintassignarray.md), [At](carrayintat.md), operator, Minimum, Maximum, [Update](carrayintupdate.md), [Shift](carrayintshift.md), [Delete](carrayintdelete.md), [DeleteRange](carrayintdeleterange.md), [CompareArray](carrayintcomparearray.md), [CompareArray](carrayintcomparearray.md), [InsertSort](carrayintinsertsort.md), [Search](carrayintsearch.md), [SearchGreat](carrayintsearchgreat.md), [SearchLess](carrayintsearchless.md), [SearchGreatOrEqual](carrayintsearchgreatorequal.md), [SearchLessOrEqual](carrayintsearchlessorequal.md), [SearchFirst](carrayintsearchfirst.md), [SearchLast](carrayintsearchlast.md), [SearchLinear](carrayintsearchlinear.md) |