FormatRequestResult



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / FormatRequestResult

[![Previous](previous.png)](ctradeformatrequest.md) 
[![Next](next.png)](cterminalinfo.md)

FormatRequestResult

Prepares the formatted string with results of the last request execution.

```
string  FormatRequestResult(
   string&                 str,         // string
   const MqlTradeRequest&  request,     // request
   const MqlTradeResult&   result       // result
   ) const
```

Parameters

str

[in]  Target string passed by reference.

request

[in]   A structure of [MqlTradeRequest](mqltraderequest.md) type with parameters of the last request.

result

[in]   A structure of [MqlTradeResult](mqltraderesult.md) type with results of the last request.

Return Value

None.