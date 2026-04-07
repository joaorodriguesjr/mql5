Color



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md)  /  [CRedBlackTreeNode<T](credblacktreenode.md)/

[![Previous](previous.png)](credblacktreenoderight.md) 
[![Next](next.png)](credblacktreenodeisleaf.md)

Color (Get method)

Returns a node color.

```
ENUM_RED_BLACK_TREE_NODE_TYPE Color();
```

Return Value

Returns a node color.

Color (Set method)

Sets the node color.

```
void Color(
   ENUM_RED_BLACK_TREE_NODE_TYPE  clr     // node color
   );
```

Parameters

clr

[in]  Node color.

Note

The color of the node is set using a value from ENUM\_RED\_BLACK\_TREE\_NODE\_TYPE. It can be of two types:

* RED\_BLACK\_TREE\_NODE\_RED the red color of the node;
* RED\_BLACK\_TREE\_NODE\_BLACK the black color of the node.