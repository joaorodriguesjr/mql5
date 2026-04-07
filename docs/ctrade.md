CTrade



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CTrade

[![Previous](previous.png)](cdealinfoselectbyindex.md) 
[![Next](next.png)](ctradeloglevel.md)

CTrade

CTrade is a class for easy access to the trade functions.

Description

CTrade class provides easy access to the trade functions.

Declaration

```
   class CTrade : public CObject
```

Title

```
   #include <Trade\Trade.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CTrade  Direct descendants  CExpertTrade |

Class methods by groups

| Setting parameters |  |
| --- | --- |
| [LogLevel](ctradeloglevel.md) | Sets logging level |
| [SetExpertMagicNumber](ctradesetexpertmagicnumber.md) | Sets the expert ID |
| [SetDeviationInPoints](ctradesetdeviationinpoints.md) | Sets the allowed deviation |
| [SetTypeFilling](ctradesettypefilling.md) | Sets filling type of the order |
| [SetTypeFillingBySymbol](ctradesettypefillingbysymbol.md) | Sets filling type of the order according to the specified symbol settings |
| [SetAsyncMode](ctradesetasyncmode.md) | Sets asynchronous mode for trade operations |
| [SetMarginMode](ctradesetmargingmode.md) | Sets margin calculation mode in accordance with the current account settings |
| Operations with orders |  |
| [OrderOpen](ctradeorderopen.md) | Places a pending order with specified parameters |
| [OrderModify](ctradeordermodify.md) | Modifies the pending order parameters |
| [OrderDelete](ctradeorderdelete.md) | Deletes a pending order |
| Operations with positions |  |
| [PositionOpen](ctradepositionopen.md) | Opens a position with specified parameters |
| [PositionModify](ctradepositionmodify.md) | Modifies position parameters by the specified symbol or position ticket |
| [PositionClose](ctradepositionclose.md) | Closes a position for the specified symbol |
| [PositionClosePartial](ctradepositionclosepartial.md) | Partially closes a position on a specified symbol or having a specified ticket |
| [PositionCloseBy](ctradepositioncloseby.md) | Closes a position with the specified ticket by an opposite position |
| Additional methods |  |
| [Buy](ctradebuy.md) | Opens a long position with specified parameters |
| [Sell](ctradesell.md) | Opens a short position with specified parameters |
| [BuyLimit](ctradebuylimit.md) | Places a pending order of the Buy Limit type with specified parameters |
| [BuyStop](ctradebuystop.md) | Places a pending order of the Buy Stop type with specified parameters |
| [SellLimit](ctradeselllimit.md) | Places a pending order of the Sell Limit type with specified parameters |
| [SellStop](ctradesellstop.md) | Places a pending order of the Sell Stop type with specified parameters |
| Access to the last request parameters |  |
| [Request](ctraderequest.md) | Gets the copy of the last request structure |
| [RequestAction](ctraderequestaction.md) | Gets the trade operation type |
| [RequestActionDescription](ctraderequestactiondescription.md) | Gets the trade operation type as string |
| [RequestMagic](ctraderequestmagic.md) | Gets the magic number of the Expert Advisor |
| [RequestOrder](ctraderequestorder.md) | Gets the order ticket used in the last request |
| [RequestSymbol](ctraderequestsymbol.md) | Gets the name of the symbol used in the last request |
| [RequestVolume](ctraderequestvolume.md) | Gets the trade volume (in lots) used in the last request |
| [RequestPrice](ctraderequestprice.md) | Gets the price used in the last request |
| [RequestStopLimit](ctraderequeststoplimit.md) | Gets the price of  pending order of Stop Limit type used in the last request |
| [RequestSL](ctraderequestsl.md) | Gets the Stop Loss price of the order used in the last request |
| [RequestTP](ctraderequesttp.md) | Gets the Take Profit price of the order used in the last request |
| [RequestDeviation](ctraderequestdeviation.md) | Gets the maximum allowable price deviation of the order used in the last request |
| [RequestType](ctraderequesttype.md) | Gets the type of the order used in the last request |
| [RequestTypeDescription](ctraderequesttypedescription.md) | Gets the type of the order (as string) used in the last request |
| [RequestTypeFilling](ctraderequesttypefilling.md) | Gets the filling type of the order used in the last request |
| [RequestTypeFillingDescription](ctraderequesttypefillingdescri.md) | Gets the filling type of the order (as string) used in the last request |
| [RequestTypeTime](ctraderequesttypetime.md) | Gets the validity period of the order used in the last request |
| [RequestTypeTimeDescription](ctraderequesttypetimedescripti.md) | Gets the validity period of the order (as string) used in the last request |
| [RequestExpiration](ctraderequestexpiration.md) | Gets the expiration time of the order used in the last request |
| [RequestComment](ctraderequestcomment.md) | Gets the comment of the order used in the last request |
| [RequestPosition](ctraderequestrequestposition.md) | Gets position ticket |
| [RequestPositionBy](ctraderequestrequestpositionby.md) | Gets opposite position ticket |
| Access to the last request checking results |  |
| [CheckResult](ctradecheckresult.md) | Gets the copy of the structure of the last request check result. |
| [CheckResultRetcode](ctradecheckresultretcode.md) | Gets the value of the retcode field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultRetcodeDescription](ctradecheckresultretcodedescription.md) | Gets the string description of the retcode field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultBalance](ctradecheckresultbalance.md) | Gets the value of the balance field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultEquity](ctradecheckresultequity.md) | Gets the value of the equity field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultProfit](ctradecheckresultprofit.md) | Gets the value of the floating profit after executing a trading operation. |
| [CheckResultMargin](ctradecheckresultmargin.md) | Gets the value of the margin field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultMarginFree](ctradecheckresultmarginfree.md) | Gets the value of the margin\_free field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultMarginLevel](ctradecheckresultmarginlevel.md) | Gets the value of the margin\_level field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| [CheckResultComment](ctradecheckresultcomment.md) | Gets the value of the comment field of [MqlTradeCheckResult](mqltradecheckresult.md) type, filled while checking the request correctness |
| Access to the last request execution results |  |
| [Result](ctraderesult.md) | Gets the copy of the structure of the last request result |
| [ResultRetcode](ctraderesultretcode.md) | Gets the code of request result |
| [ResultRetcodeDescription](ctraderesultretcodedescription.md) | Gets the code of request result as a string |
| [ResultDeal](ctraderesultdeal.md) | Gets the deal ticket |
| [ResultOrder](ctraderesultorder.md) | Gets the order ticket |
| [ResultVolume](ctraderesultvolume.md) | Gets the volume of deal or order |
| [ResultPrice](ctraderesultprice.md) | Gets the price, confirmed by broker |
| [ResultBid](ctraderesultbid.md) | Gets the current bid price (the requote) |
| [ResultAsk](ctraderesultask.md) | Gets the current ask price (the requote) |
| [ResultComment](ctraderesultcomment.md) | Gets the broker comment |
| Auxiliary methods |  |
| [PrintRequest](ctradeprintrequest.md) | Prints the last request parameters into journal |
| [PrintResult](ctradeprintresult.md) | Prints the results of the last request into journal |
| [FormatRequest](ctradeformatrequest.md) | Prepares the formatted string with last request parameters |
| [FormatRequestResult](ctradeformatrequestresult.md) | Prepares the formatted string with results of the last request execution |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |