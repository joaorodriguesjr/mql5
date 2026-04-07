InfoString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTerminalInfo](cterminalinfo.md) / InfoString

[![Previous](previous.png)](cterminalinfoinfointeger.md) 
[![Next](next.png)](expertclasses.md)

InfoString

The function returns the value of a corresponding property of the mql5 program environment. The property must be of string type.

```
string  TerminalInfoString(
   int  property_id      // property ID
   );
```

Parameters

property\_id

[in] Identifier of a property. It can be one the values of the enumeration [ENUM\_TERMINAL\_INFO\_STRING](terminalstatus.md#enum_terminal_info_string).

Return Value

Value of string type.

Note

The property value is defined by [TerminalInfoString()](terminalinfostring.md) function.