CreateCondition



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Fuzzy systems rules](fuzzy_rule.md)  /  [CGenericFuzzyRule](cgenericfuzzyrule.md) / CreateCondition

[![Previous](previous.png)](cgenericfuzzyrulecondition.md) 
[![Next](next.png)](fuzzy_variable.md)

CreateCondition

Creates a condition for a fuzzy rule by specified parameters.

```
CFuzzyCondition*  CreateCondition(
   CFuzzyVariable*  var,      // fuzzy variable
   CFuzzyTerm*      term,     // fuzzy term
   )
```

Parameters

var

 [in]  Fuzzy variable.

term

 [in]  Fuzzy term.

Return Value

Fuzzy rule status.

CreateCondition

Creates a condition for a fuzzy rule by specified parameters.

```
CFuzzyCondition*  CreateCondition(
   CFuzzyVariable*  var,      // fuzzy variable
   CFuzzyTerm*      term,     // fuzzy term
   bool             not,      // flag indicating whether it is necessary to apply negation to a condition
   )
```

Parameters

var

 [in]  Fuzzy variable.

term

 [in]  Fuzzy term.

not

 [in]  Flag indicating whether it is necessary to apply negation to a condition.

Return Value

Fuzzy rule status.

CreateCondition

Creates a condition for a fuzzy rule by specified parameters.

```
CFuzzyCondition*  CreateCondition(
   CFuzzyVariable* var,      // fuzzy variable
   CFuzzyTerm*     term,     // fuzzy term
   bool            not,      // flag indicating whether it is necessary to apply negation to a condition
   HedgeType       hedge     // condition bundle type
   )
```

Parameters

var

 [in]  Fuzzy variable.

term

 [in]  Fuzzy term.

not

 [in]  Flag indicating whether it is necessary to apply negation to a condition.

hedge

 [in]  Condition bundle type.

Return Value

Fuzzy rule status.