\_StopFlag



[MQL5 Reference](index.md)  /  [Predefined Variables](predefined.md) / \_StopFlag

[![Previous](previous.png)](_randomseed.md) 
[![Next](next.png)](_symbol.md)

int \_StopFlag

The \_StopFlag variable contains the mql5 program stop flag equal to 0 during normal operation. When the client terminal tries to stop the program, the variable is set to a value other than zero.

To check the state of the \_StopFlag you may also use the [IsStopped()](isstopped.md) function.