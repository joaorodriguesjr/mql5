PositionGetSymbol



[MQL5 Reference](index.md)  /  [Trade Functions](trading.md) / PositionGetSymbol

[![Previous](previous.png)](positionstotal.md) 
[![Next](next.png)](positionselect.md)

PositionGetSymbol

Returns the symbol corresponding to the open position and automatically selects the position for further working with it using functions [PositionGetDouble](positiongetdouble.md), [PositionGetInteger](positiongetinteger.md), [PositionGetString](positiongetstring.md).

```
string  PositionGetSymbol(
   int  index      // Number in the list of positions
   );
```

Parameters

index

[in]  Number of the position in the list of open positions.

Return Value

Value of the [string](stringconst.md) type. If the position was not found, an empty string will be returned. To get an [error code](errorcodes.md), call the [GetLastError()](getlasterror.md) function.

Note

For the "netting" interpretation of positions ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_NETTING](accountinformation.md#enum_account_info_integer) and [ACCOUNT\_MARGIN\_MODE\_EXCHANGE](accountinformation.md#enum_account_info_integer)), only one [position](positionproperties.md) can exist for a [symbol](symbol.md) at any moment of time. This position is a result of one or more [deals](dealproperties.md). Do not confuse positions with valid [pending orders](orderproperties.md), which are also displayed on the Trading tab of the Toolbox window.

If individual positions are allowed ([ACCOUNT\_MARGIN\_MODE\_RETAIL\_HEDGING](accountinformation.md#enum_account_info_integer)), multiple positions can be open for one symbol.

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- get the number of open positions on the account
   int total=PositionsTotal();
   for(int i=0; i<total; i++)
     {
      //--- get position symbol by i loop index
      ResetLastError();
      string symbol=PositionGetSymbol(i);
      
      //--- if the position symbol is successfully received, then the position at the i index becomes selected automatically
      //--- and we can obtain its properties using PositionGetDouble, PositionGetInteger and PositionGetString
      if(symbol!="")
        {
         ENUM_POSITION_TYPE type=(ENUM_POSITION_TYPE)PositionGetInteger(POSITION_TYPE);
         PrintFormat("Position symbol at index %d: %s, position type: %s", i, symbol, StringSubstr(EnumToString(type), 14));
        }
      else
        {
         PrintFormat("PositionGetSymbol(%d) failed. Error %d", i, GetLastError());
         continue;
        }
     }
   /*
   result:
   Position symbol at index 0: GBPUSD, position type: SELL
   Position symbol at index 1: EURUSD, position type: BUY
   */
  }
```

See also

[PositionsTotal()](positionstotal.md), [PositionSelect()](positionselect.md), [Position Properties](positionproperties.md)