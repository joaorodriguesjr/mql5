ResetLastError



[MQL5 Reference](index.md)  /  [Common Functions](common.md) / ResetLastError

[![Previous](previous.png)](printformat.md) 
[![Next](next.png)](resourcecreate.md)

ResetLastError

Sets the value of the predefined variable [\_LastError](_lasterror.md) into zero.

```
void  ResetLastError();
```

Return Value

No return value.

Note

It should be noted that the [GetLastError()](getlasterror.md) function doesn't zero the \_LastError variable. Usually the ResetLastError() function is called before calling a function, after which an [error](errors.md) appearance is checked.

 

Example:

```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
//--- reset the last error code before calling the function,
//--- otherwise, GetLastError() may return the previous error code
   long lres=SymbolInfoInteger("123456",SYMBOL_DIGITS);
   PrintFormat("lres=%d  error=%d",lres,GetLastError());
   lres=SymbolInfoInteger(_Symbol,SYMBOL_DIGITS);
   PrintFormat("lres=%d  error=%d",lres,GetLastError());
   ResetLastError();
   lres=SymbolInfoInteger(_Symbol,SYMBOL_DIGITS);
   PrintFormat("lres=%d  error=%d",lres,GetLastError());
  }
```