DatabaseFinalize



[MQL5 Reference](index.md)  /  [Working with databases](database.md) / DatabaseFinalize

[![Previous](previous.png)](databasereadbind.md) 
[![Next](next.png)](databasetransactionbegin.md)

DatabaseFinalize

Removes a request created in [DatabasePrepare(](databaseprepare.md)).

```
void  DatabaseFinalize(
   int  request      // request handle received in DatabasePrepare
   );
```

Parameters

request

[in]  Request handle received in DatabasePrepare().

Return Value

None.

Note

If the handle is invalid, the function sets the ERR\_DATABASE\_INVALID\_HANDLE error. You can check the error using GetLastError().

See also

[DatabasePrepare](databaseprepare.md), [DatabaseExecute](databaseexecute.md)