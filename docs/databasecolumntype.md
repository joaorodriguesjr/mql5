DatabaseColumnType



[MQL5 Reference](index.md)  /  [Working with databases](database.md) / DatabaseColumnType

[![Previous](previous.png)](databasecolumnname.md) 
[![Next](next.png)](databasecolumnsize.md)

DatabaseColumnType

Gets a field type by index.

```
ENUM_DATABASE_FIELD_TYPE  DatabaseColumnType(
   int  request,     // request handle received in DatabasePrepare
   int  column       // field index in the request
   );
```

Parameters

request

[in]  Request handle received in [DatabasePrepare()](databaseprepare.md).

column

[in]  Field index in the request. Field numbering starts from zero and cannot exceed [DatabaseColumnsCount()](databasecolumnscount.md) - 1.

Return Value

Return the field type from the [ENUM\_DATABASE\_FIELD\_TYPE](databasecolumntype.md#enum_database_field_type) enumeration. To get the error code, use GetLastError(), the possible responses are:

* ERR\_DATABASE\_INVALID\_HANDLE (5121) invalid request handle;
* ERR\_DATABASE\_NO\_MORE\_DATA (5126)    'column' index exceeds DatabaseColumnsCount() -1.

Note

The value can be obtained only if at least one [DatabaseRead()](databaseread.md) call has been preliminarily made for 'request'.

ENUM\_DATABASE\_FIELD\_TYPE

| ID | Description |
| --- | --- |
| DATABASE\_FIELD\_TYPE\_INVALID | Error getting type, the error code can be obtained using int GetLastError() |
| DATABASE\_FIELD\_TYPE\_INTEGER | Integer type |
| DATABASE\_FIELD\_TYPE\_FLOAT | Real type |
| DATABASE\_FIELD\_TYPE\_TEXT | String type |
| DATABASE\_FIELD\_TYPE\_BLOB | Binary type |
| DATABASE\_FIELD\_TYPE\_NULL | Special NULL type |

See also

[DatabasePrepare](databaseprepare.md), [DatabaseColumnsCount](databasecolumnscount.md), [DatabaseColumnName](databasecolumnname.md)