\_RandomSeed



[MQL5 Reference](index.md)  /  [Predefined Variables](predefined.md) / \_RandomSeed

[![Previous](previous.png)](_period.md) 
[![Next](next.png)](_stopflag.md)

\_RandomSeed

Variable for storing the current state when generating pseudo-random integers. \_RandomSeed changes its value when calling [MathRand()](mathrand.md). Use [MathSrand()](mathsrand.md) to set the required initial condition.

x random number received by MathRand() function is calculated in the following way at each call:

```
x=_RandomSeed*214013+2531011;
_RandomSeed=x;
x=(x>>16)&0x7FFF;
```

See also

[MathRand()](mathrand.md), [MathSrand()](mathsrand.md), [Integer types](integer.md)