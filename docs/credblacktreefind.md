Find



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CRedBlackTree<T](credblacktree.md)/

[![Previous](previous.png)](credblacktreeremovemax.md) 
[![Next](next.png)](credblacktreefindmin.md)

Find

Searches for the occurrence of a specified value in a redblack tree.

```
CRedBlackTreeNode<T>* Find(
   T  value     // the search value
   );
```

Parameters

value

[in]  The searched value.

Return Value

Returns a pointer to the found node containing the search value on success, or NULL otherwise.