CLExecutionStatus



[MQL5 Reference](index.md)  /  [Working with OpenCL](opencl.md) / CLExecutionStatus

[![Previous](previous.png)](clexecute.md) 
[![Next](next.png)](database.md)

CLExecutionStatus

Returns the OpenCL program execution status.

```
int  CLExecutionStatus(
   int   kernel            // handle to a kernel of an OpenCL program
   );
```

Parameters

kernel

[in]  Handle to a kernel of the OpenCL program.

Return Value

Returns the OpenCL program status. The value can be one of the following:

* CL\_COMPLETE=0 program complete,
* CL\_RUNNING=1 running,
* CL\_SUBMITTED=2 submitted for execution,
* CL\_QUEUED=3 queued,
* -1 (minus one) error occurred when executing CLExecutionStatus().