Fuzzy terms



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md) / Fuzzy terms

[![Previous](previous.png)](csugenovariablevalues.md) 
[![Next](next.png)](cfuzzytermmembershipfunction.md)

CFuzzyTerm (fuzzy terms)

Class for implementing fuzzy terms.

Description

A term is any element of a term set.  A term is defined by two components:

* fuzzy term name;
* membership function.

Declaration

```
   class CFuzzyTerm : public CNamedValueImpl
```

Title

```
   #include <Math\Fuzzy\fuzzyterm.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        INamedValue            CNamedValueImpl                CFuzzyTerm |

Class methods

| Class method | Description |
| --- | --- |
| [MembershipFunction](cfuzzytermmembershipfunction.md) | Gets a membership function for the fuzzy term. |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CNamedValueImpl  Name, Name |