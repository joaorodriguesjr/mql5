Structure of the depth of market



[MQL5 Reference](index.md)  /  [Constants, Enumerations and Structures](constants.md)  /  [Data Structures](structures.md) / Order Book Structure

[![Previous](previous.png)](mqlrates.md) 
[![Next](next.png)](mqltraderequest.md)

MqlBookInfo

It provides information about the market depth data.

```
struct MqlBookInfo
  {
   ENUM_BOOK_TYPE   type;            // Order type from ENUM_BOOK_TYPE enumeration
   double           price;           // Price
   long             volume;          // Volume
   double           volume_real;     // Volume with greater accuracy
  };
```

Note

The MqlBookInfo  structure is predefined, thus it doesn't require any declaration and description. To use the structure, just declare a variable of this type.

The DOM is available only for some symbols.

Example:

```
   MqlBookInfo priceArray[];
   bool getBook=MarketBookGet(NULL,priceArray);
   if(getBook)
     {
      int size=ArraySize(priceArray);
      Print("MarketBookInfo about ",Symbol());
     }
   else
     {
      Print("Failed to receive DOM for the symbol ",Symbol());
     }
```

See also

[MarketBookAdd](marketbookadd.md), [MarketBookRelease](marketbookrelease.md), [MarketBookGet](marketbookget.md), [Trade Orders in DOM](enum_trade_request_actions.md), [Data Types](types.md)