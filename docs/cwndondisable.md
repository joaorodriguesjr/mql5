OnDisable



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / OnDisable

[![Previous](previous.png)](cwndonenable.md) 
[![Next](next.png)](cwndonshow.md)

OnDisable

The virtual handler of the internal "Disable" event (if disabled, it cannot respond to user interaction).

```
virtual bool  OnDisable()
```

Return Value

true - event processed, otherwise - false.

Note

The base class method does nothing and always returns true.