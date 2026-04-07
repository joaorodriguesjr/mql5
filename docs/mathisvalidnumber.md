MathIsValidNumber



[MQL5 Reference](index.md)  /  [Math Functions](math.md) / MathIsValidNumber

[![Previous](previous.png)](mathtan.md) 
[![Next](next.png)](mathexpm1.md)

MathIsValidNumber

It checks the correctness of a real number.

```
bool  MathIsValidNumber(
   double  number      // number to check
   );
```

Parameters

number

[in]  Checked numeric value.

Return Value

It returns true, if the checked value is an acceptable real number. If the checked value is a plus or minus infinity, or "not a number" (NaN), the function returns false.

Example:

```
   double abnormal=MathArcsin(2.0);
   if(!MathIsValidNumber(abnormal)) Print("Attention! MathArcsin(2.0) = ",abnormal);
```

See also

[Real types (double, float)](double.md)