CIndicator Base Class



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md)  /  [Base classes](cindicators.md) / CIndicator

[![Previous](previous.png)](cpriceseriesmaxvalue.md) 
[![Next](next.png)](cindicatorhandle.md)

CIndicator

CIndicator is a base class for technical indicator classes of the MQL5 standard library.

Description

The CIndicator class provides the simplified access for all of its descendants to general MQL5 API technical indicator functions.

Declaration

```
   class CIndicator: public CSeries
```

Title

```
   #include <Indicators\Indicator.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            [CArrayObj](carrayobj.md)                [CSeries](cseries.md)                    CIndicator  Direct descendants  [CiAC](ciac.md), [CiAD](ciad.md), [CiADX](ciadx.md), [CiADXWilder](ciadxwilder.md), [CiAlligator](cialligator.md), [CiAMA](ciama.md), [CiAO](ciao.md), [CiATR](ciatr.md), [CiBands](cibands.md), [CiBearsPower](cibearspower.md), [CiBullsPower](cibullspower.md), [CiBWMFI](cibwmfi.md), [CiCCI](cicci.md), [CiChaikin](cichaikin.md), CiCustom, [CiDEMA](cidema.md), [CiDeMarker](cidemarker.md), [CiEnvelopes](cienvelopes.md), [CiForce](ciforce.md), [CiFractals](cifractals.md), [CiFrAMA](ciframa.md), [CiGator](cigator.md), [CiIchimoku](ciichimoku.md), [CiMA](cima.md), [CiMACD](cimacd.md), [CiMFI](cimfi.md), [CiMomentum](cimomentum.md), [CiOBV](ciobv.md), [CiOsMA](ciosma.md), [CiRSI](cirsi.md), [CiRVI](cirvi.md), [CiSAR](cisar.md), [CiStdDev](cistddev.md), [CiStochastic](cistochastic.md), [CiTEMA](citema.md), [CiTriX](citrix.md), [CiVIDyA](cividya.md), [CiVolumes](civolumes.md), [CiWPR](ciwpr.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Handle](cindicatorhandle.md) | Gets the indicator's handle. |
| [Status](cindicatorstatus.md) | Gets the status of the indicator. |
| [FullRelease](cindicatorfullrelease.md) | Sets a flag to release the handle. |
| Creation |  |
| [Create](cindicatorcreate.md) | Creates the indicator |
| [BufferResize](cindicatorbufferresize.md) | Sets the new buffer sizes |
| Data Access |  |
| [GetData](cindicatorgetdata.md) | Copies the data from the indicator buffer |
| Data Update Methods |  |
| [Refresh](cindicatorrefresh.md) | Updates the indicator data |
| Finding Min/Max Values |  |
| [Minimum](cindicatorminimum.md) | Gets the index of minimal value in a specified range. |
| [MinValue](cindicatorminvalue.md) | Gets the minimal value in a specified range. |
| [Maximum](cindicatormaximum.md) | Gets the index of maximal value in a specified range. |
| [MaxValue](cindicatormaxvalue.md) | Gets the maximal value in a specified range. |
| Conversion of Enumerations |  |
| [MethodDescription](cindicatormethoddescription.md) | Converts [ENUM\_MA\_METHOD](enum_ma_method.md) into a string |
| [PriceDescription](cindicatorpricedescription.md) | Converts [ENUM\_APPLIED\_PRICE](prices.md#enum_applied_price_enum) into a string |
| [VolumeDescription](cindicatorvolumedescription.md) | Converts [ENUM\_APPLIED\_VOLUME](prices.md#enum_applied_price_enum) into a string |
| Working with chart |  |
| [AddToChart](cindicatoraddtochart.md) | Adds an indicator to the chart |
| [DeleteFromChart](cindicatordeletefromchart.md) | Deletes an indicator from the chart |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |
| Methods inherited from class CArrayObj  [FreeMode](carrayobjfreemode.md), [FreeMode](carrayobjfreemode.md), [Type](carrayobjtype.md), [Save](carrayobjsave.md), [Load](carrayobjload.md), [CreateElement](carrayobjcreateelement.md), [Reserve](carrayobjreserve.md), [Resize](carrayobjresize.md), [Shutdown](carrayobjshutdown.md), [Add](carrayobjadd.md), [AddArray](carrayobjaddarray.md), [Insert](carrayobjinsert.md), [InsertArray](carrayobjinsertarray.md), [AssignArray](carrayobjassignarray.md), [At](carrayobjat.md), [Update](carrayobjupdate.md), [Shift](carrayobjshift.md), [Detach](carrayobjdetach.md), [Delete](carrayobjdelete.md), [DeleteRange](carrayobjdeleterange.md), [Clear](carrayobjclear.md), [CompareArray](carrayobjcomparearray.md), [InsertSort](carrayobjinsertsort.md), [Search](carrayobjsearch.md), [SearchGreat](carrayobjsearchgreat.md), [SearchLess](carrayobjsearchless.md), [SearchGreatOrEqual](carrayobjsearchgreatorequal.md), [SearchLessOrEqual](carrayobjsearchlessorequal.md), [SearchFirst](carrayobjsearchfirst.md), [SearchLast](carrayobjsearchlast.md) |
| Methods inherited from class CSeries  [Name](cseriesname.md), [BuffersTotal](cseriesbufferstotal.md), [BufferSize](cseriesbuffersize.md), [Timeframe](cseriestimeframe.md), [Symbol](cseriessymbol.md), [Period](cseriesperiod.md), [PeriodDescription](cseriesperioddescription.md), [RefreshCurrent](cseriesrefreshcurrent.md) |