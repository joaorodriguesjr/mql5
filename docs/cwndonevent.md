OnEvent



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / OnEvent

[![Previous](previous.png)](cwnddestroy.md) 
[![Next](next.png)](cwndonmouseevent.md)

OnEvent

Chart event handler.

```
virtual bool  OnEvent(
   const int      id,         // ID
   const long&    lparam,     // event parameter
   const double&  dparam,     // event parameter
   const string&  sparam      // event parameter
   )
```

Parameters

id

[in]  Event ID.

lparam

[in]  Event parameter of [long](integertypes.md#long) type, passed by reference.

dparam

[in]  Event parameter of [double](double.md) type, passed by reference.

sparam

[in]  Event parameter of [string](stringconst.md) type, passed by reference.

Return Value

true - event has been processed, otherwise - false.