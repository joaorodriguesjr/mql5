ChartEvent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CAppDialog](cappdialog.md) / ChartEvent

[![Previous](previous.png)](cappdialogrun.md) 
[![Next](next.png)](cappdialogminimized.md)

ChartEvent

Virtual handler of the control events.

```
virtual bool  ChartEvent(
   const int      id,         // ID
   const long&    lparam,     // parameter
   const double&  dparam,     // parameter
   const string&  sparam      // parameter
   )
```

Parameters

id

[in]  Event ID.

lparam

[in]  Event parameter of [long](integertypes.md#long) type passed by reference.

dparam

[in]  Event parameter of [double](double.md) type passed by reference.

sparam

[in]  Event parameter of [string](stringconst.md) type passed by reference.

Return Value

true - event processed, otherwise - false.