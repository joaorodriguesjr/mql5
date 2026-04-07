Align



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md)  /  [CWnd](cwnd.md) / Align

[![Previous](previous.png)](cwndalignment.md) 
[![Next](next.png)](cwndid.md)

Align

Performs control alignment in the specified chart area.

```
virtual bool  Align(
   const CRect*  rect      // pointer
   )
```

Parameters

rect

[in]  Pointer to the object with chart area coordinates.

Return Value

true - successful, otherwise - false.

Note

The alignment parameters must be specified (no alignment by default).