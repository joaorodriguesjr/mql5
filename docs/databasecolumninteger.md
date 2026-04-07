DatabaseColumninteger



[MQL5 Reference](index.md)  /  [Working with databases](database.md) / DatabaseColumnInteger

[![Previous](previous.png)](databasecolumntext.md) 
[![Next](next.png)](databasecolumnlong.md)

DatabaseColumnInteger

Gets the int type value from the current record.

```
bool  DatabaseColumnInteger(
   int   request,     // request handle received in DatabasePrepare
   int   column,      // field index in the request
   int&  value        // the reference to the variable for receiving the value
   );
```

Parameters

request

[in]  Request handle received in [DatabasePrepare()](databaseprepare.md).

column

[in]  Field index in the request. Field numbering starts from zero and cannot exceed [DatabaseColumnsCount()](databasecolumnscount.md) - 1.

value

[out]  Reference to the variable for writing the field value.

Return Value

Return true if successful, otherwise false. To get the error code, use GetLastError(), the possible responses are:

* ERR\_DATABASE\_INVALID\_HANDLE (5121) invalid request handle;
* ERR\_DATABASE\_NO\_MORE\_DATA (5126)   'column' index exceeds DatabaseColumnsCount() -1.

Note

The value can be obtained only if at least one [DatabaseRead()](databaseread.md) call has been preliminarily made for 'request'.

To read the value from the next record, call [DatabaseRead()](databaseread.md) preliminarily.

See also

[DatabasePrepare](databaseprepare.md), [DatabaseColumnsCount](databasecolumnscount.md), [DatabaseColumnType](databasecolumntype.md), [DatabaseColumnName](databasecolumnname.md)