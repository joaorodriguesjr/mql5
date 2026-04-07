History Data Structure



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Data Structures](structures.md) / History Data Structure

[![Previous](previous.png)](mqlparam.md) 
[![Next](next.png)](mqlbookinfo.md)

MqlRates

This structure stores information about the prices, volumes and spread.

```
struct MqlRates
  {
   datetime time;         // Period start time
   double   open;         // Open price
   double   high;         // The highest price of the period
   double   low;          // The lowest price of the period
   double   close;        // Close price
   long     tick_volume;  // Tick volume
   int      spread;       // Spread
   long     real_volume;  // Trade volume
  };
```

 

Example:

```
void OnStart()
  {
   MqlRates rates[];
   int copied=CopyRates(NULL,0,0,100,rates);
   if(copied<=0)
      Print("Error copying price data ",GetLastError());
   else Print("Copied ",ArraySize(rates)," bars");
  }
```

See also

[CopyRates](copyrates.md), [Access to timeseries](series.md)