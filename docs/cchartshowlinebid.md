ShowLineBid



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Price Charts](cchart.md) / ShowLineBid

[![Previous](previous.png)](cchartshowohlc.md) 
[![Next](next.png)](cchartshowlineask.md)

ShowLineBid (Get Method)

Gets the value of "ShowLineBid" property.

```
bool  ShowLineBid() const
```

Return Value

Value of "ShowLineBid" property of the char, assigned to the class instance. If there is no chart assigned, it returns false.

ShowLineBid (Set Method)

Sets new value for "ShowLineBid" property.

```
bool  ShowLineBid(
   bool  show      // property value
   )
```

Parameters

show

[in]  New value for "ShowLineBid" property.

Return Value

true - successful, false - cannot change the property.