CTreeDetach



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md)  /  [CTree](ctree.md) / Detach

[![Previous](previous.png)](ctreeinsert.md) 
[![Next](next.png)](ctreedelete.md)

Detach

Detaches a specified node from a tree.

```
bool  Detach(
   CTreeNode*  node      // node
   )
```

Parameters

node

[in]  Node pointer to detach.

Return Value

true - success, otherwise false.

Note

After detachment, the node pointer is not released. The tree is balanced.