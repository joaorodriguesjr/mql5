NormalizePrice



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CSymbolInfo](csymbolinfo.md) / NormalizePrice

[![Previous](previous.png)](csymbolinfoinfostring.md) 
[![Next](next.png)](corderinfo.md)

NormalizePrice

Returns the value of price normalized using the symbol properties.

```
double  NormalizePrice(
   double  price   // price
   ) const
```

Parameters

price

[in]  Price.

Return Value

Normalized price.

Note

The symbol should be selected by [Name](csymbolinfoname.md) method.