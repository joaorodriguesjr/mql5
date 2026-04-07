OnItemClick



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CListView](clistview.md) / OnItemClick

[![Previous](previous.png)](clistviewonscrolllineup.md) 
[![Next](next.png)](clistviewredraw.md)

OnItemClick

The virtual handler of "ItemClick" (mouse button click) internal event on a specified row of CListView control.

```
virtual bool  OnItemClick()
   const int    index     // index
   )
```

Return Value

true - event processed, otherwise - false.