OnObjectCreate



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWndObj](cwndobj.md) / OnObjectCreate

[![Previous](previous.png)](cwndobjzorder.md) 
[![Next](next.png)](cwndobjonobjectchange.md)

OnObjectCreate

The virtual handler of chart object [CHARTEVENT\_OBJECT\_CREATE](enum_chartevents.md) event.

```
virtual bool  OnObjectCreate()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.