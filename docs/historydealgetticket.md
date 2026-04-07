HistoryDealGetTicket



[MQL5 Reference](index.md)  /  [Trade Functions](trading.md) / HistoryDealGetTicket

[![Previous](previous.png)](historydealstotal.md) 
[![Next](next.png)](historydealgetdouble.md)

HistoryDealGetTicket

The function selects a deal for further processing and returns the deal ticket in history. Prior to calling HistoryDealGetTicket(), first it is necessary to receive the history of deals and orders using the [HistorySelect()](historyselect.md) or [HistorySelectByPosition()](historyselectbyposition.md) function.

```
ulong  HistoryDealGetTicket(
   int  index      // ticket deal
   );
```

Parameters

index

[in]  Number of a deal in the list of deals

Return Value

Value of the [ulong](integertypes.md) type. If the function fails, 0 is returned.

Note

Do not confuse [orders](orderproperties.md), [deals](dealproperties.md) and [positions](positionproperties.md). Each deal is the result of the execution of an order, each position is the summary result of one or more deals.

Example:

```
void OnStart()
  {
   ulong deal_ticket;            // deal ticket
   ulong order_ticket;           // ticket of the order the deal was executed on
   datetime transaction_time;    // time of a deal execution 
   long deal_type ;              // type of a trade operation
   long position_ID;             // position ID
   string deal_description;      // operation description
   double volume;                // operation volume
   string symbol;                // symbol of the deal
//--- set the start and end date to request the history of deals
   datetime from_date=0;         // from the very beginning
   datetime to_date=TimeCurrent();// till the current moment
//--- request the history of deals in the specified period
   HistorySelect(from_date,to_date);
//--- total number in the list of deals
   int deals=HistoryDealsTotal();
//--- now process each trade
   for(int i=0;i<deals;i++)
     {
      deal_ticket=               HistoryDealGetTicket(i);
      volume=                    HistoryDealGetDouble(deal_ticket,DEAL_VOLUME);
      transaction_time=(datetime)HistoryDealGetInteger(deal_ticket,DEAL_TIME);
      order_ticket=              HistoryDealGetInteger(deal_ticket,DEAL_ORDER);
      deal_type=                 HistoryDealGetInteger(deal_ticket,DEAL_TYPE);
      symbol=                    HistoryDealGetString(deal_ticket,DEAL_SYMBOL);
      position_ID=               HistoryDealGetInteger(deal_ticket,DEAL_POSITION_ID);
      deal_description=          GetDealDescription(deal_type,volume,symbol,order_ticket,position_ID);
      //--- perform fine formatting for the deal number
      string print_index=StringFormat("% 3d",i);
      //--- show information on the deal
      Print(print_index+": deal #",deal_ticket," at ",transaction_time,deal_description);
     }
  }
//+------------------------------------------------------------------+
//| Returns the string description of the operation                  |
//+------------------------------------------------------------------+
string GetDealDescription(long deal_type,double volume,string symbol,long ticket,long pos_ID)
  {
   string descr;
//---
   switch(deal_type)
     {
      case DEAL_TYPE_BALANCE:                  return ("balance");
      case DEAL_TYPE_CREDIT:                   return ("credit");
      case DEAL_TYPE_CHARGE:                   return ("charge");
      case DEAL_TYPE_CORRECTION:               return ("correction");
      case DEAL_TYPE_BUY:                      descr="buy"; break;
      case DEAL_TYPE_SELL:                     descr="sell"; break;
      case DEAL_TYPE_BONUS:                    return ("bonus");
      case DEAL_TYPE_COMMISSION:               return ("additional commission");
      case DEAL_TYPE_COMMISSION_DAILY:         return ("daily commission");
      case DEAL_TYPE_COMMISSION_MONTHLY:       return ("monthly commission");
      case DEAL_TYPE_COMMISSION_AGENT_DAILY:   return ("daily agent commission");
      case DEAL_TYPE_COMMISSION_AGENT_MONTHLY: return ("monthly agent commission");
      case DEAL_TYPE_INTEREST:                 return ("interest rate");
      case DEAL_TYPE_BUY_CANCELED:             descr="cancelled buy deal"; break;
      case DEAL_TYPE_SELL_CANCELED:            descr="cancelled sell deal"; break;
     }
   descr=StringFormat("%s %G %s (order #%d, position ID %d)",
                      descr,  // current description
                      volume, // deal volume
                      symbol, // deal symbol
                      ticket, // ticket of the order that caused the deal
                      pos_ID  // ID of a position, in which the deal is included
                      );
   return(descr);
//---
  }
```

See also

[HistorySelect()](historyselect.md), [HistoryDealsTotal()](historydealstotal.md), [HistoryDealSelect()](historydealselect.md), [Deal Properties](dealproperties.md)