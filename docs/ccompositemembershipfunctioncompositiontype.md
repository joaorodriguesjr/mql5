CompositionType



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Membership functions](fuzzy_membership.md)  /  [CCompositeMembershipFunction](ccompositemembershipfunction.md) / CompositionType

[![Previous](previous.png)](ccompositemembershipfunction.md) 
[![Next](next.png)](ccompositemembershipfunctionmembershipfunctions.md)

CompositionType

Sets the composition operator.

```
void  CompositionType(
   MfCompositionType  value      // operator type
   )
```

Parameters

value

[in]  Composition operator type.

Note

The following operator types are available:

* MinMF (minimum of functions)
* MaxMF (maximum of functions)
* ProdMF (product of functions)
* SumMF (sum of functions)