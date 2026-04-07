LoadNode



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CTreeNode](ctreenode.md) / LoadNode

[![Previous](previous.png)](ctreenodesavenode.md) 
[![Next](next.png)](ctreenodetype.md)

LoadNode

Reads node data from a file.

```
bool  LoadNode(
   int         file_handle,     // handle
   CTreeNode*  main             // node
   )
```

Parameters

file\_handle

[in] Handle of a binary file that was earlier opened for reading.

main

[in]  Node for data.

Return Value

true - success, otherwise false.