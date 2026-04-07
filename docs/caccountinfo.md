CAccountInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CAccountInfo

[![Previous](previous.png)](tradeclasses.md) 
[![Next](next.png)](caccountinfologin.md)

CAccountInfo

CAccountInfo is a class for easy access to the currently opened trade account properties.

Description

CAccountInfo class provides easy access to the currently opened trade account properties.

Declaration

```
   class CAccountInfo : public CObject
```

Title

```
   #include <Trade\AccountInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CAccountInfo |

Class methods by groups

| Access to integer type properties |  |
| --- | --- |
| [Login](caccountinfologin.md) | Gets the account number |
| [TradeMode](caccountinfotrademode.md) | Gets the trade mode |
| [TradeModeDescription](caccountinfotrademodedescription.md) | Gets the trade mode as a string |
| [Leverage](caccountinfoleverage.md) | Gets the amount of given leverage |
| [StopoutMode](caccountinfostopoutmode.md) | Gets the mode of stop out setting |
| [StopoutModeDescription](caccountinfostopoutmodedescription.md) | Gets the mode of stop out setting as a string |
| [TradeAllowed](caccountinfotradeallowed.md) | Gets the flag of trade allowance |
| [TradeExpert](caccountinfotradeexpert.md) | Gets the flag of automated trade allowance |
| [LimitOrders](caccountinfolimitorders.md) | Gets the maximal number of allowed pending orders |
| [MarginMode](caccountinfomarginmode.md) | Gets margin calculation mode |
| [MarginModeDescription](caccountinfomarginmodedescription.md) | Gets margin calculation mode as a string |
| Access to double type properties |  |
| [Balance](caccountinfobalance.md) | Gets the balance of account |
| [Credit](caccountinfocredit.md) | Gets the amount of given credit |
| [Profit](caccountinfoprofit.md) | Gets the amount of current profit on account |
| [Equity](caccountinfoequity.md) | Gets the amount of current equity on account |
| [Margin](caccountinfomargin.md) | Gets the amount of reserved margin |
| [FreeMargin](caccountinfofreemargin.md) | Gets the amount of free margin |
| [MarginLevel](caccountinfomarginlevel.md) | Gets the level of margin |
| [MarginCall](caccountinfomargincall.md) | Gets the level of margin for deposit |
| [MarginStopOut](caccountinfomarginstopout.md) | Gets the level of margin for Stop Out |
| Access to text properties |  |
| [Name](caccountinfoname.md) | Gets the client name |
| [Server](caccountinfoserver.md) | Gets the trade server name |
| [Currency](caccountinfocurrency.md) | Gets the deposit currency name |
| [Company](caccountinfocompany.md) | Gets the company name that serves an account |
| Access to MQL5 API functions |  |
| [InfoInteger](caccountinfointeger.md) | Gets the value of specified integer type property |
| [InfoDouble](caccountinfodouble.md) | Gets the value of specified double type property |
| [InfoString](caccountinfostring.md) | Gets the value of specified string type property |
| Additional methods |  |
| [OrderProfitCheck](caccountinfoorderprofitcheck.md) | Gets the evaluated profit based on the parameters passed |
| [MarginCheck](caccountinfomargincheck.md) | Gets the amount of margin required to execute trade operation |
| [FreeMarginCheck](caccountinfofreemargincheck.md) | Gets the amount of free margin left after execution of trade operation |
| [MaxLotCheck](caccountinfomaxlotcheck.md) | Gets the maximal possible volume of trade operation |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |