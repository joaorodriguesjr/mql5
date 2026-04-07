DatabaseClose



[MQL5 Reference](index.md)  /  [Working with databases](database.md) / DatabaseClose

[![Previous](previous.png)](databaseopen.md) 
[![Next](next.png)](databaseimport.md)

DatabaseClose

Closes a database.

```
void  DatabaseClose(
   int  database      // database handle received in DatabaseOpen
   );
```

Parameters

database

[in]  Database handle received in [DatabaseOpen()](databaseopen.md).

Return Value

None.

Note

After calling DatabaseClose, all [handles of requests](databaseprepare.md)  to the database are automatically removed and become invalid.

If the handle is invalid, the function sets the ERR\_DATABASE\_INVALID\_HANDLE error. You can check the error using GetLastError().

See also

[DatabaseOpen](databaseopen.md), [DatabasePrepare](databaseprepare.md)