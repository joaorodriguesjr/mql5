CiAlligator



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Bill Williams Indicators](bwindicators.md) / CiAlligator

[![Previous](previous.png)](ciactype.md) 
[![Next](next.png)](cialligatorjawperiod.md)

CiAlligator

CiAlligator is a class intended for using the Alligator technical indicator.

Description

CiAlligator class provides the creation, setup, and access to the data of the Alligator indicator.

Declaration

```
   class CiAlligator: public CIndicator
```

Title

```
   #include <Indicators\BillWilliams.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                [CSeries](cseries.md)                    [CIndicator](cindicator.md)                        CiAlligator |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [JawPeriod](cialligatorjawperiod.md) | Returns the averaging period for the Jaws line |
| [JawShift](cialligatorjawshift.md) | Returns the horizontal shift of the Jaws line |
| [TeethPeriod](cialligatorteethperiod.md) | Returns the averaging period for the Teeth line |
| [TeethShift](cialligatorteethshift.md) | Returns the horizontal shift of the Teeth line |
| [LipsPeriod](cialligatorlipsperiod.md) | Returns the averaging period for the Lips line |
| [LipsShift](cialligatorlipsshift.md) | Returns the horizontal shift of the Lips line |
| [MaMethod](cialligatormamethod.md) | Returns the averaging method |
| [Applied](cialligatorapplied.md) | Returns the price type or handle to apply |
| Create |  |
| [Create](cialligatorcreate.md) | Creates the indicator |
| Data Access |  |
| [Jaw](cialligatorjaw.md) | Returns the buffer data of the Jaws line buffer |
| [Teeth](cialligatorteeth.md) | Returns the buffer data of the Teeth line buffer |
| [Lips](cialligatorlips.md) | Returns the buffer data of the Lips line buffer |
| Input/output |  |
| virtual [Type](cialligatortype.md) | Virtual identification method |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |
| Methods inherited from class CSeries  [Name](cseriesname.md), [BuffersTotal](cseriesbufferstotal.md), [BufferSize](cseriesbuffersize.md), [Timeframe](cseriestimeframe.md), [Symbol](cseriessymbol.md), [Period](cseriesperiod.md), [PeriodDescription](cseriesperioddescription.md), [RefreshCurrent](cseriesrefreshcurrent.md) |
| Methods inherited from class CIndicator  [Handle](cindicatorhandle.md), [Status](cindicatorstatus.md), [FullRelease](cindicatorfullrelease.md), Redrawer, [Create](cindicatorcreate.md), [BufferResize](cindicatorbufferresize.md), [BarsCalculated](cindicatorbarscalculated.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [GetData](cindicatorgetdata.md), [Minimum](cindicatorminimum.md), [MinValue](cindicatorminvalue.md), [Maximum](cindicatormaximum.md), [MaxValue](cindicatormaxvalue.md), [Refresh](cindicatorrefresh.md), [AddToChart](cindicatoraddtochart.md), [DeleteFromChart](cindicatordeletefromchart.md), [MethodDescription](cindicatormethoddescription.md), [PriceDescription](cindicatorpricedescription.md), [VolumeDescription](cindicatorvolumedescription.md) |