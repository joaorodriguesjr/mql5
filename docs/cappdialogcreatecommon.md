CreateCommon



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CAppDialog](cappdialog.md) / CreateCommon

[![Previous](previous.png)](cappdialoginifileext.md) 
[![Next](next.png)](cappdialogcreateexpert.md)

CreateCommon

Common initialization method.

```
bool  CreateCommon(
   const long    chart,      // chart ID
   const string  name,       // name
   const int     subwin,     // chart subwindow
   )
```

Parameters

chart

[in]  ID of the chart, at which the control is created.

name

[in]  Unique name of the control.

subwin

[in]  Subwindow of the chart, at which the control is created.

Return Value

true - successful, otherwise - false.