CDealInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CDealInfo

[![Previous](previous.png)](cpositioninfocheckstate.md) 
[![Next](next.png)](cdealinfoorder.md)

CDealInfo

CDealInfo is a class for easy access to the deal properties.

Description

CDealInfo class provides access to the deal properties.

Declaration

```
   class CDealInfo : public CObject
```

Title

```
   #include <Trade\DealInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CDealInfo |

Class methods by groups

| Access to integer type properties |  |
| --- | --- |
| [Order](cdealinfoorder.md) | Gets the order by which the deal is executed |
| [Time](cdealinfotime.md) | Gets the time of deal execution |
| [TimeMsc](cdealinfotimemsc.md) | Receives the time of a deal execution in milliseconds since 01.01.1970 |
| [DealType](cdealinfodealtype.md) | Gets the deal type |
| [TypeDescription](cdealinfotypedescription.md) | Gets the deal type as a string |
| [Entry](cdealinfoentry.md) | Gets the deal direction |
| [EntryDescription](cdealinfoentrydescription.md) | Gets the deal direction as a string |
| [Magic](cdealinfomagic.md) | Gets the ID of expert, that executed the deal |
| [PositionId](cdealinfopositionid.md) | Gets the ID of position, in which the deal was involved |
| Access to double type properties |  |
| [Volume](cdealinfovolume.md) | Gets the volume of deal |
| [Price](cdealinfoprice.md) | Gets the deal price |
| [Commision](cdealinfocommision.md) | Gets the amount of commission of the deal |
| [Swap](cdealinfoswap.md) | Gets the amount of swap when position is closed |
| [Profit](cdealinfoprofit.md) | Gets the financial result of deal |
| Access to text properties |  |
| [Symbol](cdealinfosymbol.md) | Gets the name of deal symbol |
| [Comment](cdealinfocomment.md) | Gets the deal comment |
| Access to MQL5 API functions |  |
| [InfoInteger](cdealinfoinfointeger.md) | Gets the value of specified integer type property |
| [InfoDouble](cdealinfoinfodouble.md) | Gets the value of specified double type property |
| [InfoString](cdealinfoinfostring.md) | Gets value of specified string type property |
| Selection |  |
| [Ticket](cdealinfoticket.md) | Gets ticket/selects the deal |
| [SelectByIndex](cdealinfoselectbyindex.md) | Selects the deal by index |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |