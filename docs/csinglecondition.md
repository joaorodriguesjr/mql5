CSingleCondition



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Fuzzy systems rules](fuzzy_rule.md) / CSingleCondition

[![Previous](previous.png)](csugenofuzzyruleconclusion.md) 
[![Next](next.png)](csingleconditionnot.md)

CSingleCondition

The class sets a fuzzy condition expressed by "Fuzzy variable Fuzzy term" pair.

Description

According to a fuzzy condition, one variable corresponds to one term. A fuzzy condition can be described by the following expression: X is a,

where:

* X is a fuzzy variable;
* a  is a fuzzy variable value (fuzzy term).

Declaration

```
   class CSingleCondition : public ICondition
```

Title

```
   #include <Math\Fuzzy\fuzzyrule.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        ICondition            CSingleCondition  Direct descendants  CFuzzyCondition |

Class methods

| Class method | Description |
| --- | --- |
| [Not](csingleconditionnot.md) | Gets and sets the flag indicating whether it is necessary to apply negation to this condition. |
| [Term](csingleconditionterm.md) | Gets and sets a fuzzy term for this condition. |
| [Var](csingleconditionvar.md) | Gets and sets a fuzzy variable for this condition. |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |