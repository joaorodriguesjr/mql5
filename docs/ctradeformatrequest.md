FormatRequest



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / FormatRequest

[![Previous](previous.png)](ctradeprintresult.md) 
[![Next](next.png)](ctradeformatrequestresult.md)

FormatRequest

Prepares the formatted string with last request parameters.

```
string  FormatRequest(
   string&                 str,         // string
   const MqlTradeRequest&  request      // request
   ) const
```

Parameters

str

[in]  Target string passed by reference.

request

[in]  A structure of [MqlTradeRequest](mqltraderequest.md) type with parameters of the last request.

Return Value

None.