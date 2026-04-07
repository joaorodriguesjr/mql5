Remove



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CRedBlackTree<T](credblacktree.md)/

[![Previous](previous.png)](credblacktreeclear.md) 
[![Next](next.png)](credblacktreeremovemin.md)

Remove

Removes the occurrence of the specified element from a redblack tree.

The version that removes an element with the specified value.

```
bool Remove(
   T  value                        // the element value
   );
```

The version that removes an element by a pointer to a node.

```
bool Remove(
   CRedBlackTreeNode<T>*  node     // the element node
   );
```

Parameters

item

[in] The value of the element to be deleted.

*node

[in] The node of the element to be deleted.

Return Value

Returns true on successful, or false otherwise.