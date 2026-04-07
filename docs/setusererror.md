SetUserError



[MQL5 Reference](index.md)  /  [Common Functions](common.md) / SetUserError

[![Previous](previous.png)](setreturnerror.md) 
[![Next](next.png)](sleep.md)

SetUserError

Sets the predefined variable [\_LastError](_lasterror.md) into the value equal to [ERR\_USER\_ERROR\_FIRST](errorcodes.md#err_user_error_first) + user\_error

```
void  SetUserError(
   ushort user_error,   // error number
   );
```

Parameters

user\_error

[in] [Error](errorcodes.md) number set by a user.

Return Value

No return value.

Note

After an error has been set using the SetUserError(user\_error) function, [GetLastError()](getlasterror.md) returns value equal to [ERR\_USER\_ERROR\_FIRST](errorcodes.md#err_user_error_first) + user\_error.

Example:

```
void OnStart()
  {
//--- set error number 65537=(ERR_USER_ERROR_FIRST +1)
   SetUserError(1);
//--- get last error code
   Print("GetLastError = ",GetLastError());
/* 
   Result
   GetLastError = 65537
*/ 
  }
```