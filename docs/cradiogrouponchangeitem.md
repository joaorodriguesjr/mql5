OnChangeItem



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CRadioGroup](cradiogroup.md) / OnChangeItem

[![Previous](previous.png)](cradiogrouponscrolllineup.md) 
[![Next](next.png)](cradiogroupredraw.md)

OnChangeItem

The virtual handler of the control "ChangeItem" (item change) event.

```
virtual bool  OnChangeItem(
   const int  index      // index
   )
```

Parameters

index

[in]  Index of the changed item.

Return Value

true - event processed, otherwise - false.