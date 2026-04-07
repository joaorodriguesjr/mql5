SetTypeFillingBySymbol



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md)  /  [CTrade](ctrade.md) / SetTypeFillingBySymbol

[![Previous](previous.png)](ctradesettypefilling.md) 
[![Next](next.png)](ctradesetasyncmode.md)

SetTypeFillingBySymbol

Sets [filling](orderproperties.md#enum_order_type_filling) type of the order according to the specified symbol settings.

```
bool  SetTypeFillingBySymbol(
   const string   symbol      // symbol name
   )
```

Parameters

symbol

[in] Name of the symbol, in which [SYMBOL\_FILLING\_MODE](marketinfoconstants.md#symbol_filling_mode) contains allowed order filling policies.

Return Value

true successful execution, false failed to define the filling policy.

Note

If [SYMBOL\_FILLING\_FOK](marketinfoconstants.md#symbol_filling_mode) and [SYMBOL\_FILLING\_IOC](marketinfoconstants.md#symbol_filling_mode) filling policies are allowed for a symbol simultaneously, the [ORDER\_FILLING\_FOK](orderproperties.md#enum_order_type_filling) value is set for the order.