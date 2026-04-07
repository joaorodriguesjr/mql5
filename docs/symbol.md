Symbol



[MQL5 Reference](index.md)  /  [Checkup](check.md) / Symbol

[![Previous](previous.png)](mqlinfostring.md) 
[![Next](next.png)](period.md)

Symbol

Returns the name of a symbol of the current chart.

```
string  Symbol();
```

Return Value

Value of the [\_Symbol](_symbol.md) system variable, which stores the name of the current chart symbol.

Note

Unlike Expert Advisors, indicators and scripts, services are not bound to a specific chart. Therefore, [Symbol()](symbol.md) returns an empty string ("") for a service.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get the current chart symbol name
   string name = Symbol();
   
//--- send the obtained data to the journal
   PrintFormat("Current chart symbol name: '%s'", name);
   /*
   result
   Current chart symbol name: 'EURUSD'
   */
  }
```