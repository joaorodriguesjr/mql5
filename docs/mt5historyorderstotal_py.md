history\_orders\_total



[MQL5 Reference](index.md)  /  [Python Integration](python_metatrader5.md) / history\_orders\_total

[![Previous](previous.png)](mt5positionsget_py.md) 
[![Next](next.png)](mt5historyordersget_py.md)

history\_orders\_total

Get the number of orders in trading history within the specified interval.

```
history_orders_total(
   date_from,    // date the orders are requested from
   date_to       // date, up to which the orders are requested
   )
```

Parameters

date\_from

[in]  Date the orders are requested from. Set by the 'datetime' object or as a number of seconds elapsed since 1970.01.01. Required unnamed parameter.

date\_to

[in]  Date, up to which the orders are requested. Set by the 'datetime' object or as a number of seconds elapsed since 1970.01.01. Required unnamed parameter.

Return Value

Integer value.

Note

The function is similar to [HistoryOrdersTotal](historyorderstotal.md).

Example:

```
from datetime import datetime
import MetaTrader5 as mt5
# display data on the MetaTrader 5 package
print("MetaTrader5 package author: ",mt5.__author__)
print("MetaTrader5 package version: ",mt5.__version__)
 
# establish connection to MetaTrader 5 terminal
if not mt5.initialize():
    print("initialize() failed, error code =",mt5.last_error())
    quit()
 
# get the number of orders in history
from_date=datetime(2020,1,1)
to_date=datetime.now()
history_orders=mt5.history_orders_total(from_date, datetime.now())
if history_orders>0:
    print("Total history orders=",history_orders)
else:
    print("Orders not found in history")
 
# shut down connection to the MetaTrader 5 terminal
mt5.shutdown()
```

See also

[history\_orders\_get](mt5historyordersget_py.md), [history\_deals\_total](mt5historydealstotal_py.md)