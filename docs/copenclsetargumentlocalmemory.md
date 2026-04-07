SetArgumentLocalMemory



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [OpenCL](copencl.md) / SetArgumentLocalMemory

[![Previous](previous.png)](copenclsetargumentbuffer.md) 
[![Next](next.png)](copenclsetbufferscount.md)

SetArgumentLocalMemory

Sets a parameter in local memory for the OpenCL function at the specified index.

```
bool  SetArgumentLocalMemory(
   const int  kernel_index,          // index of the kernel
   const int  arg_index,             // index of the function argument
   const int  local_memory_size      // size of the local memory
   );
```

Parameters

kernel\_index

[in]  Index of the kernel object.

arg\_index

[in]  Index of the function argument.

local\_memory\_size

[in]  Size of the local memory.

Return Value

In case of successful execution, returns true, otherwise - false.