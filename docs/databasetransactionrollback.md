DatabaseTransactionRollback



[MQL5 Reference](index.md)  /  [Working with databases](database.md) / DatabaseTransactionRollback

[![Previous](previous.png)](databasetransactioncommit.md) 
[![Next](next.png)](databasecolumnscount.md)

DatabaseTransactionRollback

Rolls back transactions.

```
bool  DatabaseTransactionRollback(
   int  database      // database handle received in DatabaseOpen
   );
```

Parameters

database

[in]  Database handle received in [DatabaseOpen()](databaseopen.md).

Return true if successful, otherwise false. To get the error code, use GetLastError(), the possible responses are:

* ERR\_INTERNAL\_ERROR (4001)                      critical runtime error;
* ERR\_INVALID\_PARAMETER (4003)                sql parameter contains an empty string;
* ERR\_NOT\_ENOUGH\_MEMORY (4004)            insufficient memory;
* ERR\_WRONG\_STRING\_PARAMETER (5040)   error converting a request into a UTF-8 string;
* ERR\_DATABASE\_INTERNAL (5120)               internal database error;
* ERR\_DATABASE\_INVALID\_HANDLE (5121)     invalid database handle;
* ERR\_DATABASE\_EXECUTE (5124)                  request execution error.

Note

DatabaseTransactionRollback() call cancels all transactions executed after calling the DatabaseTransactionBegin() function. The DatabaseTransactionRollback() function is necessary for rolling back changes in a database in case errors occur when executing a transaction.

See also

[DatabaseExecute](databaseexecute.md), [DatabasePrepare](databaseprepare.md), [DatabaseTransactionBegin](databasetransactionbegin.md), [DatabaseTransactionCommit](databasetransactioncommit.md)