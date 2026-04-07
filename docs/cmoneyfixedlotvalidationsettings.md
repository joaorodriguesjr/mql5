ValidationSettings



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strategy Modules](expertclasses.md)  /  [Money Management Classes](samplemmclasses.md)  /  [CMoneyFixedLot](cmoneyfixedlot.md) / ValidationSettings

[![Previous](previous.png)](cmoneyfixedlotlots.md) 
[![Next](next.png)](cmoneyfixedlotcheckopenlong.md)

ValidationSettings

Checks the settings.

```
virtual bool  ValidationSettings()
```

Return Value

true - successful, otherwise - false.

Note

Checks if the predefined fixed lot falls within the range of allowed values and is multiple of change step.