DatabaseColumnsCount



[MQL5 Reference](index.md)  /  [Working with databases](database.md) / DatabaseColumnsCount

[![Previous](previous.png)](databasetransactionrollback.md) 
[![Next](next.png)](databasecolumnname.md)

DatabaseColumnsCount

Gets the number of fields in a request.

```
int  DatabaseColumnsCount(
   int  request      // request handle received in DatabasePrepare
   );
```

Parameters

request

[in]  Request handle received in [DatabasePrepare()](databaseprepare.md).

Return Value

Number of fields or -1 in case of an error. To get the error code, use GetLastError(), the possible responses are:

* ERR\_DATABASE\_INVALID\_HANDLE (5121) - invalid request handle.

Note

There is no need to call the [DatabaseRead()](databaseread.md) function to get the number of fields of a request created in DatabasePrepare(). For the remaining DatabaseColumnXXX() functions, DatabaseRead() should be preliminarily called.

See also

[DatabasePrepare](databaseprepare.md), [DatabaseFinalize](databasefinalize.md), [DatabaseClose](databaseclose.md)