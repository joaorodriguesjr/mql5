MarketBookGet



[MQL5 Reference](index.md)  /  [Market Info](marketinformation.md) / MarketBookGet

[![Previous](previous.png)](marketbookrelease.md) 
[![Next](next.png)](calendar.md)

MarketBookGet

Returns a structure array [MqlBookInfo](mqlbookinfo.md) containing records of the Depth of Market of a specified symbol.

```
bool  MarketBookGet(
   string        symbol,     // symbol
   MqlBookInfo&  book[]      // reference to an array
   );
```

Parameters

symbol

[in] Symbol name.

book[]

[in] Reference to an array of Depth of Market records. The array can be pre-allocated for a sufficient number of records. If a [dynamic array](dynamic_array.md) hasn't been pre-allocated in the operating memory, the client terminal will distribute the array itself.

Return Value

Returns true in case of success, otherwise false.

Note

The Depth of Market must be pre-opened by the [MarketBookAdd()](marketbookadd.md) function.

Example:

```
   MqlBookInfo priceArray[];
   bool getBook=MarketBookGet(NULL,priceArray);
   if(getBook)
     {
      int size=ArraySize(priceArray);
      Print("MarketBookInfo for ",Symbol());
      for(int i=0;i<size;i++)
        {
         Print(i+":",priceArray[i].price
               +"    Volume = "+priceArray[i].volume,
               " type = ",priceArray[i].type);
        }
     }
   else
     {
      Print("Could not get contents of the symbol DOM ",Symbol());
     }
```

See also

[Structure of Depth of Market](mqlbookinfo.md), [Structures and Classes](classes.md)