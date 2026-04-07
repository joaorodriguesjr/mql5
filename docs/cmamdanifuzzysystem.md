Mamdani system



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Fuzzy systems](fuzzy_system.md) / Mamdani system

[![Previous](previous.png)](fuzzy_system.md) 
[![Next](next.png)](cmamdanifuzzysystemaggregationmethod.md)

Mamdani system

Output variable values in the Mamdani system are set using fuzzy terms.

Description

Fuzzy logic rule for the Mamdani algorithm can be described as follows:

![fuzzy_mamdani_rule](fuzzy_mamdani_rule.png)

where:

* X = (X1, X2, X3 ... Xn) vector of input variables;
* Y output variable;
* a = (a1, a2, a3 ... an) vector of input variable values;
* d output variable value;
* W rule weight.

Class methods

| Class method | Description |
| --- | --- |
| [AggregationMethod](cmamdanifuzzysystemaggregationmethod.md) | Sets the type of conditions aggregation |
| [Calculate](cmamdanifuzzysystemcalculate.md) | Calculates a fuzzy inference for the system |
| [DefuzzificationMethod](cmamdanifuzzysystemdefuzzificationmethod.md) | Sets defuzzification method type |
| [EmptyRule](cmamdanifuzzysystememptyrule.md) | Creates an empty fuzzy Mamdani rule based on the current system |
| [ImplicationMethod](cmamdanifuzzysystemimplicationmethod.md) | Sets a type of the system implication operator |
| [Output](cmamdanifuzzysystemoutput.md) | Gets the list of fuzzy Mamdani output variables. |
| [OutputByName](cmamdanifuzzysystemoutputbyname.md) | Gets a fuzzy Mamdani output variable by a specified name. |
| [ParseRule](cmamdanifuzzysystemparserule.md) | Creates a fuzzy Mamdani rule based on a specified line. |
| [Rules](cmamdanifuzzysystemrules.md) | Returns the list of fuzzy Mamdani rules. |

|  |
| --- |
| Methods inherited from class CGenericFuzzySystem  Input, AndMethod, AndMethod, OrMethod, OrMethod, InputByName, Fuzzify |