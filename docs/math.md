Math Functions



[MQL5 Reference](index.md) / Math Functions

[![Previous](previous.png)](stringformat.md) 
[![Next](next.png)](mathabs.md)

Mathematical Functions

A set of mathematical and trigonometric functions.

Math functions were originally designed to perform relevant operations on scalar values. From this build on, most of the functions can be applied to [matrices and vectors](matrix_vector.md). These include MathAbs, MathArccos, MathArcsin, MathArctan, MathCeil, MathCos, MathExp, MathFloor, MathLog, MathLog10, MathMod, MathPow, MathRound, MathSin, MathSqrt, MathTan, MathExpm1, MathLog1p, MathArccosh, MathArcsinh, MathArctanh, MathCosh, MathSinh, and MathTanh. Such operations imply element-wise handling of matrices or vectors. Example:

```
//---
  matrix a= {{1, 4}, {9, 16}};
  Print("matrix a=\n",a);
  a=MathSqrt(a);
  Print("MatrSqrt(a)=\n",a);
  /*
   matrix a=
   [[1,4]
    [9,16]]
   MatrSqrt(a)=
   [[1,2]
    [3,4]]
  */
```

For [MathMod](mathmod.md) and [MathPow](mathpow.md), the second element can be either a scalar or a matrix/vector of the appropriate size.

| Function | Action |
| --- | --- |
| [MathAbs](mathabs.md) | Returns absolute value (modulus) of the specified numeric value |
| [MathArccos](matharccos.md) | Returns the arc cosine of x in radians |
| [MathArcsin](matharcsin.md) | Returns the arc sine of x in radians |
| [MathArctan](matharctan.md) | Returns the arc tangent of x in radians |
| [MathArctan2](matharctan2.md) | Return the angle (in radians) whose tangent is the quotient of two specified numbers |
| [MathClassify](mathclassify.md) | Returns the type of a real number |
| [MathCeil](mathceil.md) | Returns integer numeric value closest from above |
| [MathCos](mathcos.md) | Returns the cosine of a number |
| [MathExp](mathexp.md) | Returns exponent of a number |
| [MathFloor](mathfloor.md) | Returns integer numeric value closest from below |
| [MathLog](mathlog.md) | Returns natural logarithm |
| [MathLog10](mathlog10.md) | Returns the logarithm of a number by base 10 |
| [MathMax](mathmax.md) | Returns the maximal value of the two numeric values |
| [MathMin](mathmin.md) | Returns the minimal value of the two numeric values |
| [MathMod](mathmod.md) | Returns the real remainder after the division of two numbers |
| [MathPow](mathpow.md) | Raises the base to the specified power |
| [MathRand](mathrand.md) | Returns a pseudorandom value within the range of 0 to 32767 |
| [MathRound](mathround.md) | Rounds of a value to the nearest integer |
| [MathSin](mathsin.md) | Returns the sine of a number |
| [MathSqrt](mathsqrt.md) | Returns a square root |
| [MathSrand](mathsrand.md) | Sets the starting point for generating a series of pseudorandom integers |
| [MathTan](mathtan.md) | Returns the tangent of a number |
| [MathIsValidNumber](mathisvalidnumber.md) | Checks the correctness of a real number |
| [MathExpm1](mathexpm1.md) | Returns the value of the expression MathExp(x)-1 |
| [MathLog1p](mathlog1p.md) | Returns the value of the expression MathLog(1+x) |
| [MathArccosh](matharccosh.md) | Returns the hyperbolic arccosine |
| [MathArcsinh](matharcsinh.md) | Returns the hyperbolic arcsine |
| [MathArctanh](matharctanh.md) | Returns the hyperbolic arctangent |
| [MathCosh](mathcosh.md) | Returns the hyperbolic cosine |
| [MathSinh](mathsinh.md) | Returns the hyperbolic sine |
| [MathTanh](mathtanh.md) | Returns the hyperbolic tangent |
| [MathSwap](mathswap.md) | Change the order of bytes in the [ushort](integertypes.md)/uint/ushort types value |