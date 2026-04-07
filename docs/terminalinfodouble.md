TerminalInfoDouble



[MQL5 Reference](index.md)  /  [Checkup](check.md) / TerminalInfoDouble

[![Previous](previous.png)](terminalinfointeger.md) 
[![Next](next.png)](terminalinfostring.md)

TerminalInfoDouble

Returns the value of a corresponding property of the mql5 program environment.

```
double  TerminalInfoDouble(
   int  property_id      // identifier of a property
   );
```

Parameters

property\_id

[in] Identifier of a property. Can be one of the values of the [ENUM\_TERMINAL\_INFO\_DOUBLE](terminalstatus.md#enum_terminal_info_double) enumeration.

Return Value

Value of double type.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get the build number of the running terminal and its "64-bit terminal" property
   int  build = TerminalInfoInteger(TERMINAL_BUILD);
   bool x64   = TerminalInfoInteger(TERMINAL_X64);
   
//--- print the obtained terminal data in the journal
   PrintFormat("MetaTrader 5 %s build %d", (x64 ? "x64" : "x32"), build);
   /*
   result:
   MetaTrader 5 x64 build 4330
   */
  }
```