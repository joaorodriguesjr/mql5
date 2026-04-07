MarketBookRelease



[MQL5 Reference](index.md)  /  [Market Info](marketinformation.md) / MarketBookRelease

[![Previous](previous.png)](marketbookadd.md) 
[![Next](next.png)](marketbookget.md)

MarketBookRelease

Provides closing of Depth of Market for a selected symbol, and cancels the subscription for receiving notifications of the DOM changes.

```
bool  MarketBookRelease(
   string  symbol      // symbol
   );
```

Parameters

symbol

[in] Symbol name.

Return Value

The true value if closed successfully, otherwise false.

Note

Normally, this function must be called from the [OnDeinit()](ondeinit.md) function, if the corresponding [MarketBookAdd()](marketbookadd.md) function has been called in the [OnInit()](oninit.md) function. Or it must be called from the class destructor, if the corresponding MarketBookAdd() function has been called from the class constructor.

Example:

```
#define SYMBOL_NAME "GBPUSD"
 
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- open the market depth for SYMBOL_NAME symbol
   if(!MarketBookAdd(SYMBOL_NAME))
     {
      PrintFormat("MarketBookAdd(%s) failed. Error ", SYMBOL_NAME, GetLastError());
      return;
     }
 
//--- send the message about successfully opening the market depth to the journal
   PrintFormat("The MarketBook for the '%s' symbol was successfully opened and a subscription to change it was received", SYMBOL_NAME);
   
//--- wait 2 seconds
   Sleep(2000);
   
//--- upon completion, unsubscribe from the open market depth
//--- send the message about successfully unsubscribing from the market depth or about the error to the journal
   ResetLastError();
   if(MarketBookRelease(SYMBOL_NAME))
      PrintFormat("MarketBook for the '%s' symbol was successfully closed", SYMBOL_NAME);
   else
      PrintFormat("Error %d occurred when closing MarketBook using the '%s' symbol", GetLastError(), SYMBOL_NAME);
      
   /*
   result:
   The MarketBook for the 'GBPUSD' symbol was successfully opened and a subscription to change it was received
   MarketBook for the 'GBPUSD' symbol was successfully closed
   */
  }
```

See also

[Structure of Depth of Market](mqlbookinfo.md), [Structures and Classes](classes.md)