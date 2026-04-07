Loss



[MQL5 Reference](index.md)  /  [Matrix and Vector Methods](matrix.md)  /  [Machine learning](matrix_machine_learning.md) / Loss

[![Previous](previous.png)](matrix_derivative.md) 
[![Next](next.png)](matrix_lossgradient.md)

Loss

Compute the value of the loss function.

```
double vector::Loss(
  const vector&       vect_true,     // vector of true values
  ENUM_LOSS_FUNCTION  loss,          // loss function
   ...                               // additional parameter
   );
 
 
double matrix::Loss(
  const matrix&       matrix_true,   // matrix of true values
  ENUM_LOSS_FUNCTION  loss,          // loss function
   );
 
 
double matrix::Loss(
  const matrix&       matrix_true,   // matrix of true values
  ENUM_LOSS_FUNCTION  loss,          // loss function
  ENUM_MATRIX_AXIS    axis,          // axis
   ...                               // additional parameter
   );
```

Parameters

vect\_true/matrix\_true

 [in] Vector or matrix of true values.

loss

[in]  Loss function from the [ENUM\_LOSS\_FUNCTION](matrix_enumerations.md#enum_loss_function) enumeration.

axis

[in] [ENUM\_MATRIX\_AXIS](matrix_enumerations.md#enum_matrix_axis) enumeration value (AXIS\_HORZ horizontal axis, AXIS\_VERT vertical axis).

...

[in]  Additional parameter 'delta' can only be used by the Hubert loss function (LOSS\_HUBER)

Return Value

double value.

 

How the 'delta' parameter is used in the Hubert loss function (LOSS\_HUBER)

```
   double delta = 1.0;
   double error = fabs(y - x);
   if(error<delta)
      loss = 0.5 * error^2;
   else
      loss = 0.5 * delta^2 + delta * (error - delta);
```

 

Note

A neural network aims at finding the algorithms that minimize the error on the training sample, for which the loss function is used.

The value of the loss function indicates by how much the value predicted by the model deviates from the real one.

Different loss functions are used depending on the problem. For example, Mean Squared Error ([MSE](matrix_enumerations.md#enum_loss_function)) is used for regression problems, and Binary Cross-Entropy ([BCE](matrix_enumerations.md#enum_loss_function)) is used for binary classification purposes.

 

Example of calling the Hubert loss function:

```
   vector y_true = {0.0, 1.0, 0.0, 0.0};
   vector y_pred = {0.6, 0.4, 0.4, 0.6};
   double loss=y_pred.Loss(y_true,LOSS_HUBER);
   Print(loss);
   double loss2=y_pred.Loss(y_true,LOSS_HUBER,0.5);
   Print(loss2);
 
/* Result
   0.155
   0.15125
*/
```