StringToDouble



[MQL5 Reference](index.md)  /  [Conversion Functions](convert.md) / StringToDouble

[![Previous](previous.png)](stringtocolor.md) 
[![Next](next.png)](stringtointeger.md)

StringToDouble

The function converts string containing a symbol representation of number into number of double type.

```
double  StringToDouble(
   string  value      // string
   );
```

Parameters

value

[in]  String containing a symbol representation of a number.

Return Value

Value of double type.

 

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- string to convert
   string str = "12345.54321";
//--- convert the input string as a real number into a double type variable
   double converted=StringToDouble(str);
//--- display the resulting number accurate to 8 decimal places in the journal
   PrintFormat("The string '%s' is converted to the real number %.8f", str, converted);
   /*
   result:
   The string '12345.54321' is converted to the real number 12345.54321000
   */
  }
```

See also

[NormalizeDouble](normalizedouble.md), [Real types (double, float)](double.md), [Typecasting](casting.md)