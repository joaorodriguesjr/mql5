Runtime Errors



[MQL5 Reference](index.md)  /  [MQL5 programs](runtime.md) / Runtime Errors

[![Previous](previous.png)](imports.md) 
[![Next](next.png)](testing.md)

Runtime Errors

The executing subsystem of the client terminal has an opportunity to save the [error code](errorcodes.md) in case it occurs during a MQL5 program run. There is a predefined variable [\_LastError](_lasterror.md) for each executable MQL5 program.

Before starting the [OnInit](oninit.md) function, the \_LastError variable is reset. In case an erroneous situation occurs during calculations or in the process of internal function calls, the \_LastError variable accepts a corresponding error code. The value stored in this variable can be obtained using the [GetLastError()](getlasterror.md) function.

There are several critical errors in case of which a program is terminated immediately:

* division by zero
* going beyond array boundary
* using an incorrect [object pointer](object_pointers.md)