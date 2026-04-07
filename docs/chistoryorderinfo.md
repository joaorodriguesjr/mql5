CHistoryOrderInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CHistoryOrderInfo

[![Previous](previous.png)](corderinfoselectbyindex.md) 
[![Next](next.png)](chistoryorderinfotimesetup.md)

CHistoryOrderInfo

CHistoryOrderInfo is a class for easy access to the history order properties.

Description

CHistoryOrderInfo class provides easy access to the history order properties.

Declaration

```
   class CHistoryOrderInfo : public CObject
```

Title

```
   #include <Trade\HistoryOrderInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CHistoryOrderInfo |

Class methods by groups

| Access to integer type properties |  |
| --- | --- |
| [TimeSetup](chistoryorderinfotimesetup.md) | Gets the time of order placement |
| [TimeSetupMsc](chistoryorderinfotimesetupmsc.md) | Receives the time of placing an order in milliseconds since 01.01.1970 |
| [OrderType](chistoryorderinfoordertype.md) | Gets the order type |
| [OrderTypeDescription](chistoryorderinfotypedescription.md) | Gets the order type as a string |
| [State](chistoryorderinfostate.md) | Gets the order state |
| [StateDescription](chistoryorderinfostatedescription.md) | Gets the order state as a string |
| [TimeExpiration](chistoryorderinfotimeexpiration.md) | Gets the time of order expiration |
| [TimeDone](chistoryorderinfotimedone.md) | Gets the time of order execution or cancellation |
| [TimeDoneMsc](chistoryorderinfotimedonemsc.md) | Receives order execution or cancellation time in milliseconds since 01.01.1970 |
| [TypeFilling](chistoryorderinfotypefilling.md) | Gets the type of order execution by remainder |
| [TypeFillingDescription](chistoryorderinfotypefillingdescription.md) | Gets the type of order execution by remainder as a string |
| [TypeTime](chistoryorderinfotypetime.md) | Gets the type of order at the time of the expiration |
| [TypeTimeDescription](chistoryorderinfotypetimedescription.md) | Gets the order type by expiration time as a string |
| [Magic](chistoryorderinfomagic.md) | Gets the ID of expert that placed the order |
| [PositionId](chistoryorderinfopositionid.md) | Gets the ID of position |
| Access to double type properties |  |
| [VolumeInitial](chistoryorderinfovolumeinitial.md) | Gets the initial volume of order |
| [VolumeCurrent](chistoryorderinfovolumecurrent.md) | Gets the unfilled volume of order |
| [PriceOpen](chistoryorderinfopriceopen.md) | Gets the order price |
| [StopLoss](chistoryorderinfostoploss.md) | Gets the order's Stop Loss |
| [TakeProfit](chistoryorderinfotakeprofit.md) | Gets the order's Take Profit |
| [PriceCurrent](chistoryorderinfopricecurrent.md) | Gets the current price by order symbol |
| [PriceStopLimit](chistoryorderinfopricestoplimi.md) | Gets the price of a Limit order |
| Access to text properties |  |
| [Symbol](chistoryorderinfosymbol.md) | Gets the order symbol |
| [Comment](chistoryorderinfocomment.md) | Gets the order comment |
| Access to MQL5 API functions |  |
| [InfoInteger](chistoryorderinfoinfointeger.md) | Gets the value of specified integer type property |
| [InfoDouble](chistoryorderinfoinfodouble.md) | Gets the value of specified double type property |
| [InfoString](chistoryorderinfoinfostring.md) | Gets value of specified string type property |
| Selection |  |
| [Ticket](chistoryorderinfoticket.md) | Gets the ticket/selects the order |
| [SelectByIndex](chistoryorderinfoselectbyindex.md) | Selects the order by index |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |