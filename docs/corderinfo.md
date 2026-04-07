COrderInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / COrderInfo

[![Previous](previous.png)](csymbolinfonormalizeprice.md) 
[![Next](next.png)](corderinfoticket.md)

COrderInfo

COrderInfo is a class for easy access to the pending order properties.

Description

COrderInfo class provides access to the pending order properties.

Declaration

```
   class COrderInfo : public CObject
```

Title

```
   #include <Trade\OrderInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        COrderInfo |

Class methods by groups

| Access to integer type properties |  |
| --- | --- |
| [Ticket](corderinfoticket.md) | Gets the ticket of an order, previously selected for access |
| [TimeSetup](corderinfotimesetup.md) | Gets the time of order placement |
| [TimeSetupMsc](corderinfotimesetupmsc.md) | Receives the time of placing an order in milliseconds since 01.01.1970 |
| [OrderType](corderinfoordertype.md) | Gets the order type |
| [OrderTypeDescription](corderinfotypedescription.md) | Gets the order type as a string |
| [State](corderinfostate.md) | Gets the order state |
| [StateDescription](corderinfostatedescription.md) | Gets the order state as a string |
| [TimeExpiration](corderinfotimeexpiration.md) | Gets the time of order expiration |
| [TimeDone](corderinfotimedone.md) | Gets the time of order execution or cancellation |
| [TimeDoneMsc](corderinfotimedonemsc.md) | Receives order execution or cancellation time in milliseconds since 01.01.1970 |
| [TypeFilling](corderinfotypefilling.md) | Gets the type of order execution by remainder |
| [TypeFillingDescription](corderinfotypefillingdescription.md) | Gets the type of order execution by remainder as a string |
| [TypeTime](corderinfotypetime.md) | Gets the type of order at the time of the expiration |
| [TypeTimeDescription](corderinfotypetimedescription.md) | Gets the order type by expiration time as a string |
| [Magic](corderinfomagic.md) | Gets the ID of expert that placed the order |
| [PositionId](corderinfopositionid.md) | Gets the ID of position |
| Access to double type properties |  |
| [VolumeInitial](corderinfovolumeinitial.md) | Gets the initial volume of order |
| [VolumeCurrent](corderinfovolumecurrent.md) | Gets the unfilled volume of order |
| [PriceOpen](corderinfopriceopen.md) | Gets the order price |
| [StopLoss](corderinfostoploss.md) | Gets the order's Stop Loss |
| [TakeProfit](corderinfotakeprofit.md) | Gets the order's Take Profit |
| [PriceCurrent](corderinfopricecurrent.md) | Gets the current price by order symbol |
| [PriceStopLimit](corderinfopricestoplimit.md) | Gets the price of a Limit order |
| Access to text properties |  |
| [Symbol](corderinfosymbol.md) | Gets the name of order symbol |
| [Comment](corderinfocomment.md) | Gets the order comment |
| Access to MQL5 API functions |  |
| [InfoInteger](corderinfoinfointeger.md) | Gets the value of specified integer type property |
| [InfoDouble](corderinfoinfodouble.md) | Gets the value of specified double type property |
| [InfoString](corderinfoinfostring.md) | Gets value of specified string type property |
| State |  |
| [StoreState](corderinfostorestate.md) | Saves the order parameters |
| [CheckState](corderinfocheckstate.md) | Checks the current parameters against the saved parameters |
| Selection |  |
| [Select](corderinfoselect.md) | Selects an order by ticket for further access to its properties |
| [SelectByIndex](corderinfoselectbyindex.md) | Selects an order by index for further access to its properties |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |