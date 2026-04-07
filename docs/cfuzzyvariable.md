CFuzzyVariable



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Fuzzy systems variables](fuzzy_variable.md) / CFuzzyVariable

[![Previous](previous.png)](fuzzy_variable.md) 
[![Next](next.png)](cfuzzyvariableaddterm.md)

CFuzzyVariable

Class for creating general fuzzy variables.  

Description

Here, a fuzzy variable is created with the following parameters:

* maximum variable value;
* minimum variable value;
* fuzzy variable name;
* term set (set of all possible values, which a linguistic variable is capable of receiving).

Declaration

```
   class CFuzzyVariable : public CNamedVariableImpl
```

Title

```
   #include <Math\Fuzzy\fuzzyvariable.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        INamedValue            INamedVariable                CNamedVariableImpl                    CFuzzyVariable |

Class methods

| Class method | Description |
| --- | --- |
| [AddTerm](cfuzzyvariableaddterm.md) | Adds a single fuzzy term to a fuzzy variable. |
| [GetTermByName](cfuzzyvariablegettermbyname.md) | Gets a fuzzy term by a specified name. |
| [Max](cfuzzyvariablemax.md) | Gets and sets a maximum value for a fuzzy variable. |
| [Min](cfuzzyvariablemin.md) | Gets and sets a minimum value for a fuzzy variable. |
| [Terms](cfuzzyvariableterms.md) | Gets and sets a list of fuzzy terms for the given fuzzy variable. |
| [Values](cfuzzyvariablevalues.md) | Gets and sets a list of fuzzy terms for the given fuzzy variable. |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CNamedVariableImpl  Name, Name |