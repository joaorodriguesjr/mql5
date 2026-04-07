CRedBlackTreeNode<T>



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Generic Data Collections](generic.md) / CRedBlackTreeNode<T

[![Previous](previous.png)](cdefaultequalitycomparerhashcode.md) 
[![Next](next.png)](credblacktreenodevalue.md)

CRedBlackTreeNode<T>

CRedBlackTreeNode<T> is a helper class used in implementing the CRedBlackTree<T> class.

Description

The CRedBlackTreeNode<T> class is a node of the CRedBlackTree<T>. Tree navigation methods are implemented in the class.

Declaration

```
   template<typename T>
   class CRedBlackTreeNode
```

Header

```
   #include <Generic\RedBlackTree.mqh>
```

Class Methods

| Method | Description |
| --- | --- |
| [Value](credblacktreenodevalue.md) | Returns and sets a node value |
| [Parent](credblacktreenodeparent.md) | Returns and sets a pointer to the parent node |
| [Left](credblacktreenodeleft.md) | Returns and sets a pointer to the left node |
| [Right](credblacktreenoderight.md) | Returns and sets a pointer to the right node |
| [Color](credblacktreenodecolor.md) | Returns and sets a node color |
| [IsLeaf](credblacktreenodeisleaf.md) | Determines whether the specified node is a leaf |
| [CreateEmptyNode](credblacktreenodecreateemptynode.md) | Creates a new black node with no parent and children, and returns a pointer to it |