Object Delete Operator delete



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Operators](operators.md) / Object Delete Operator delete

[![Previous](previous.png)](newoperator.md) 
[![Next](next.png)](function.md)

Object Delete Operator delete

The delete operator deletes an object created by the [new](newoperator.md) operator, calls the corresponding class destructor and frees up memory occupied by the object. A real descriptor of an existing object is used as an operand. After the delete operation is executed, the [object descriptor](object_pointers.md) becomes invalid.

Example:

```
      //--- delete figure
      delete m_shape;
      m_shape=NULL;
      //--- create a new figure
      NewShape();
```

See also

[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md), [Creating and Deleting Objects](object_live.md)