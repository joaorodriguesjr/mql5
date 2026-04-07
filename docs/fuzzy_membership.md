Membership functions



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md) / Membership functions

[![Previous](previous.png)](fuzzy_logic.md) 
[![Next](next.png)](cconstantmembershipfunction.md)

Membership functions

A membership function is a function that allows to calculate the membership degree of a random element of the universal set to a fuzzy set. Consequently, the domain of a membership function should be within the range [0, 1].

In most cases, the membership function is continuous and monotonic.

| Classes of membership functions | Description |
| --- | --- |
| [CConstantMembershipFunction](cconstantmembershipfunction.md) | Class for implementing a membership function as a straight line in parallel with the coordinate axis |
| [CCompositeMembershipFunction](ccompositemembershipfunction.md) | Class for implementing a composition of membership functions |
| [CDifferencTwoSigmoidalMembershipFunction](cdifferenctwosigmoidalmembershipfunction.md) | Class for implementing the membership function in the form of a difference between two sigmoid functions with the A1, A2, C1 and C2 parameters |
| [CGeneralizedBellShapedMembershipFunction](cgeneralizedbellshapedmembershipfunction.md) | Class for implementing a generalized bell-shaped membership function with A, B and C parameters |
| [CNormalCombinationMembershipFunction](cnormalcombinationmembershipfunction.md) | Class for implementing a two-sided Gaussian membership function with the B1, B2, Sigma1 and Sigma2 parameters |
| [CNormalMembershipFunction](cnormalmembershipfunction.md) | Class for implementing a symmetrical Gaussian membership function with the B and Sigma parameters |
| [CP\_ShapedMembershipFunction](cp_shapedmembershipfunction.md) | Class for implementing a pi-shaped membership function with the A, B, C and D parameters |
| [CProductTwoSigmoidalMembershipFunction](cproducttwosigmoidalmembershipfunctions.md) | Class for implementing the membership function in the form of a product of two sigmoid functions with the A1, A2, C1 and C2 parameters |
| [CS\_ShapedMembershipFunction](cs_shapedmembershipfunction.md) | Class for implementing an S-like membership function with the A and B parameters |
| [CTrapezoidMembershipFunction](ctrapezoidmembershipfunction.md) | Class for implementing a trapezoidal membership function with the X1, X2, X3 and X4 parameters |
| [CTriangularMembershipFunction](ctriangularmembershipfunction.md) | Class for implementing a triangle membership function with the X1, X2 and X3 parameters |
| [CSigmoidalMembershipFunction](csigmoidalmembershipfunction.md) | Class for implementing a sigmoid membership function with the A and C parameters |
| [CZ\_ShapedMembershipFunction](cz_shapedmembershipfunction.md) | Class for implementing a z-like membership function with the A and B parameters. |
| [IMembershipFunction](imembershipfunction.md) | Basic class for all membership function classes. |