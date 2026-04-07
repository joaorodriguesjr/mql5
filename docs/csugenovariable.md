CSugenoVariable



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Mathematics](mathematics.md)  /  [Fuzzy Logic](fuzzy_logic.md)  /  [Fuzzy systems variables](fuzzy_variable.md) / CSugenoVariable

[![Previous](previous.png)](cfuzzyvariablevalues.md) 
[![Next](next.png)](csugenovariablefunctions.md)

CSugenoVariable

Class for creating fuzzy Sugeno-type variables.  

Description

Fuzzy Sugeno-type variable is different from the general linguistic variable since it is not set by a term set but by a set of linear functions.

Declaration

```
   class CSugenoVariable : public CNamedVariableImpl
```

Title

```
   #include <Math\Fuzzy\sugenovariable.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        INamedValue            INamedVariable                CNamedVariableImpl                    CSugenoVariable |

Class methods

| Class method | Description |
| --- | --- |
| [Functions](csugenovariablefunctions.md) | Gets the list of linear functions of the fuzzy Sugeno variable. |
| [GetFuncByName](csugenovariablegetfuncbyname.md) | Gets the linear function by a specified name. |
| [Values](csugenovariablevalues.md) | Gets the list of linear functions of the fuzzy Sugeno variable. |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CNamedVariableImpl  Name, Name |