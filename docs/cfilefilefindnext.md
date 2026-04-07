FileFindNext



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md)  /  [CFile](cfile.md) / FileFindNext

[![Previous](previous.png)](cfilefilefindfirst.md) 
[![Next](next.png)](cfilefilefindclose.md)

FileFindNext

Continues file search started by the FileFindFirst() method.

```
bool  FileFindNext(
   int      search_handle,     // search handle
   string&  file_name          // reference
   )
```

Parameters

search\_handle

[in]  Search handle returned by FileFindFirst() method.

file\_name

[in]  The reference to the string the name of the found file is placed into if successful.

Return Value

true - successful, false - there are no files corresponding to the filter.