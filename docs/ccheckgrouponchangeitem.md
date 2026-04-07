OnChangeItem



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CCheckGroup](ccheckgroup.md) / OnChangeItem

[![Previous](previous.png)](ccheckgrouponscrolllineup.md) 
[![Next](next.png)](ccheckgroupredraw.md)

OnChangeItem

The virtual handler of the control "ChangeItem" (item change) internal event.

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