CGenericFuzzyRule



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Fuzzy systems rules](fuzzy_rule.md) / CGenericFuzzyRule

[![Previous](previous.png)](cconditionsop.md) 
[![Next](next.png)](cgenericfuzzyruleconclusion.md)

CGenericFuzzyRule

Base class for both types of fuzzy rules.

Declaration

```
   class CGenericFuzzyRule : public IParsableRule
```

Title

```
   #include <Math\Fuzzy\fuzzyrule.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        IParsableRule            CGenericFuzzyRule  Direct descendants  [CMamdaniFuzzyRule](cmamdanifuzzyrule.md), [CSugenoFuzzyRule](csugenofuzzyrule.md) |

Class methods

| Class method | Description |
| --- | --- |
| [Conclusion](cgenericfuzzyruleconclusion.md) | Gets and sets the fuzzy rule conclusion |
| [Condition](cgenericfuzzyrulecondition.md) | Gets and sets the 'if' condition (set of conditions) for a fuzzy rule |
| [CreateCondition](cgenericfuzzyrulecreatecondition.md) | Creates a condition for a fuzzy rule by specified parameters |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |