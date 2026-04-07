shutdown



[MQL5 Reference](index.md)  /  [Python Integration](python_metatrader5.md) / shutdown

[![Previous](previous.png)](mt5login_py.md) 
[![Next](next.png)](mt5version_py.md)

shutdown

Close the previously established connection to the MetaTrader 5 terminal.

```
shutdown()
```

Return Value

None.

Example:

```
import MetaTrader5 as mt5
# display data on the MetaTrader 5 package
print("MetaTrader5 package author: ",mt5.__author__)
print("MetaTrader5 package version: ",mt5.__version__)
 
# establish connection to the MetaTrader 5 terminal
if not mt5.initialize():
    print("initialize() failed")
    quit()
 
# display data on connection status, server name and trading account
print(mt5.terminal_info())
# display data on MetaTrader 5 version
print(mt5.version())
 
# shut down connection to the MetaTrader 5 terminal
mt5.shutdown()
```

See also

[initialize](mt5initialize_py.md), [login\_py](mt5login_py.md), [terminal\_info](mt5terminalinfo_py.md), [version](mt5version_py.md)