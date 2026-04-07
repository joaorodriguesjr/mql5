RowState



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CListView](clistview.md) / RowState

[![Previous](previous.png)](clistviewredraw.md) 
[![Next](next.png)](clistviewcheckview.md)

RowState

Changes the state of the specified row of the CListView control.

```
bool  RowState(
   const int   index      // index
   const bool  select     // state
   )
```

Parameters

index

[in]  Row index.

select

[in]  Row state.

Return Value

true - successful, otherwise - false.