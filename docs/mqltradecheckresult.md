Request Check Result Structure



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Data Structures](structures.md) / Request Check Result Structure

[![Previous](previous.png)](mqltraderequest.md) 
[![Next](next.png)](mqltraderesult.md)

The Structure of Results of a Trade Request Check (MqlTradeCheckResult)

Before [sending](ordersend.md) a [request](mqltraderequest.md) for a [trade operation](enum_trade_request_actions.md) to a trade server, it is recommended to check it. The check is performed using the [OrderCheck()](ordercheck.md) function, to which the checked request and a variable of the MqlTradeCheckResult structure type are passed. The check result will be written to this variable.

```
struct MqlTradeCheckResult
  {
   uint         retcode;             // Reply code
   double       balance;             // Balance after the execution of the deal
   double       equity;              // Equity after the execution of the deal
   double       profit;              // Floating profit
   double       margin;              // Margin requirements
   double       margin_free;         // Free margin
   double       margin_level;        // Margin level
   string       comment;             // Comment to the reply code (description of the error)
  };
```

Description of Fields

| Field | Description |
| --- | --- |
| retcode | [Return code](enum_trade_return_codes.md) |
| balance | Balance value that will be after the execution of the trade operation |
| equity | Equity value that will be after the execution of the trade operation |
| profit | Value of the floating profit that will be after the execution of the trade operation |
| margin | Margin required for the trade operation |
| margin\_free | Free margin that will be left after the execution of the trade operation |
| margin\_level | Margin level that will be set after the execution of the trade operation |
| comment | Comment to the reply code, error description |

See also

[Trade Request Structure](mqltraderequest.md), [Structure for Current Prices](mqltick.md), [OrderSend](ordersend.md), [OrderCheck](ordercheck.md)