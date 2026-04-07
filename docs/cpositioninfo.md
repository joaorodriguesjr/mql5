CPositionInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CPositionInfo

[![Previous](previous.png)](chistoryorderinfoselectbyindex.md) 
[![Next](next.png)](cpositioninfotime.md)

CPositionInfo

CPositionInfo is a class for easy access to the open position properties.

Description

CPositionInfo class provides easy access to the open position properties.

Declaration

```
   class CPositionInfo : public CObject
```

Title

```
   #include <Trade\PositionInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CPositionInfo |

Class methods by groups

| Access to integer type properties |  |
| --- | --- |
| [Time](cpositioninfotime.md) | Gets the time of position opening |
| [TimeMsc](cpositioninfotimemsc.md) | Receives the time of  position opening in milliseconds since 01.01.1970 |
| [TimeUpdate](cpositioninfotimeupdate.md) | Receives the time of position changing in seconds since 01.01.1970 |
| [TimeUpdateMsc](cpositioninfotimeupdatemsc.md) | Receives the time of position changing in milliseconds since 01.01.1970 |
| [PositionType](cpositioninfopositiontype.md) | Gets the position type |
| [TypeDescription](cpositioninfotypedescription.md) | Gets the position type as a string |
| [Magic](cpositioninfomagic.md) | Gets the ID of expert, that opened the position |
| [Identifier](cpositioninfoidentifier.md) | Gets the ID of position |
| Access to double type properties |  |
| [Volume](cpositioninfovolume.md) | Gets the volume of position |
| [PriceOpen](cpositioninfopriceopen.md) | Gets the price of position opening |
| [StopLoss](cpositioninfostoploss.md) | Gets the price of position's Stop Loss |
| [TakeProfit](cpositioninfotakeprofit.md) | Gets the price of position's Take Profit |
| [PriceCurrent](cpositioninfopricecurrent.md) | Gets the current price by position symbol |
| [Commission](cpositioninfocommission.md) | Gets the amount of commission by position |
| [Swap](cpositioninfoswap.md) | Gets the amount of swap by position |
| [Profit](cpositioninfoprofit.md) | Gets the amount of current profit by position |
| Access to text properties |  |
| [Symbol](cpositioninfosymbol.md) | Gets the name of position symbol |
| [Comment](cpositioninfocomment.md) | Gets the comment of the position |
| Access to MQL5 API functions |  |
| [InfoInteger](cpositioninfoinfointeger.md) | Gets the value of specified integer type property |
| [InfoDouble](cpositioninfoinfodouble.md) | Gets the value of specified double type property |
| [InfoString](cpositioninfoinfostring.md) | Gets the value of specified string type property |
| Selection |  |
| [Select](cpositioninfoselect.md) | Selects the position |
| [SelectByIndex](cpositioninfoselectbyindex.md) | Selects the position by index |
| [SelectByMagic](cpositioninfoselectbymagic.md) | Selects a position with the specified symbol name and magic number |
| [SelectByTicket](cpositioninfoselectbyticket.md) | Selects the position by ticket |
| State |  |
| [StoreState](cpositioninfostorestate.md) | Saves the position parameters |
| [CheckState](cpositioninfocheckstate.md) | Checks the current parameters against the saved parameters |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |