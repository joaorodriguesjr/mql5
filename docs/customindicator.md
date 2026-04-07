Custom indicators



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Indicators](technicalindicators.md) / Custom indicators

[![Previous](previous.png)](cibwmfitype.md) 
[![Next](next.png)](cicustomnumbuffers.md)

CiCustom

CiCustom is a class intended for using the custom technical indicators.

Description

CiCustom class provides the creation, setup, and access to the data of a custom indicator.

Declaration

```
   class CiCustom: public CIndicator
```

Title

```
   #include <Indicators\Custom.mqh>
```

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [NumBuffers](cicustomnumbuffers.md) | Sets the number of buffers |
| [NumParams](cicustomnumparams.md) | Gets the number of parameters used when creating an indicator |
| [ParamType](cicustomparamtype.md) | Gets the type of the specified parameter |
| [ParamLong](cicustomparamlong.md) | Gets the value of the specified parameter of integer type |
| [ParamDouble](cicustomparamdouble.md) | Gets the value of the specified parameter of double type |
| [ParamString](cicustomparamstring.md) | Gets the value of the specified parameter of string type |
| Input/output |  |
| virtual [Type](cicustomtype.md) | Virtual identification method |