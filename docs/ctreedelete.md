CTreeDelete



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CTree](ctree.md) / Delete

[![Previous](previous.png)](ctreedetach.md) 
[![Next](next.png)](ctreeclear.md)

Delete

Deletes a specified node from a tree.

```
bool  Delete(
   CTreeNode*  node      // node
   )
```

Parameters

node

[in]  Node pointer to delete.

Return Value

true - success, otherwise false.

Note

After deletion, a node pointer is released. The tree is balanced.