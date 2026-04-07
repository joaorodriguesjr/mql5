IMembershipFunction



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Membership functions](fuzzy_membership.md) / IMembershipFunction

[![Previous](previous.png)](cz_shapedmembershipfunctiongetvalue.md) 
[![Next](next.png)](imembershipfunctiongetvalue.md)

IMembershipFunction

Basic class for all membership function classes.

Declaration

```
   class CZ_ShapedMembershipFuncion : public IMembershipFunction
```

Title

```
   #include <Math\Fuzzy\membershipfunction.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        IMembershipFunction  Direct descendants  [CCompositeMembershipFunction](ccompositemembershipfunction.md), [CConstantMembershipFunction](cconstantmembershipfunction.md), [CDifferencTwoSigmoidalMembershipFunction](cdifferenctwosigmoidalmembershipfunction.md), [CGeneralizedBellShapedMembershipFunction](cgeneralizedbellshapedmembershipfunction.md), [CNormalCombinationMembershipFunction](cnormalcombinationmembershipfunction.md), [CNormalMembershipFunction](cnormalmembershipfunction.md), [CP\_ShapedMembershipFunction](cp_shapedmembershipfunction.md), [CProductTwoSigmoidalMembershipFunctions](cproducttwosigmoidalmembershipfunctions.md), [CS\_ShapedMembershipFunction](cs_shapedmembershipfunction.md), [CSigmoidalMembershipFunction](csigmoidalmembershipfunction.md), [CTrapezoidMembershipFunction](ctrapezoidmembershipfunction.md), [CTriangularMembershipFunction](ctriangularmembershipfunction.md), [CZ\_ShapedMembershipFunction](cz_shapedmembershipfunction.md) |

Class methods

| Class method | Description |
| --- | --- |
| [GetValue](imembershipfunctiongetvalue.md) | Calculates the value of the membership function by a specified argument. |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |