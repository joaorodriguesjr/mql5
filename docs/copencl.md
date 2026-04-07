OpenCL



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md) / OpenCL

[![Previous](previous.png)](csugenofuzzysystemrules.md) 
[![Next](next.png)](copenclbuffercreate.md)

Class for working with OpenCL programs

The COpenCL class is a wrapper to facilitate working with the [OpenCL functions](opencl.md). In some cases, use of the GPU allows to substantially increase the speed of computations.

Examples of class use for calculations based on float and double values can be found in the corresponding subdirectories of the MQL5\Scripts\Examples\OpenCL\ folder. The source codes of the OpenCL programs are located in MQL5\Scripts\Examples\OpenCL\Double\Kernels and MQL5\Scripts\Examples\OpenCL\Float\Kernels subdirectories.

* MatrixMult.mq5 - example of matrix multiplication using global and local memory
* BitonicSort.mq5 - example of parallel sorting of array elements in GPU
* FFT.mq5 - example of fast Fourier transform calculation
* Wavelet.mq5 - example of wavelet transform of data using the Morlet wavelet.

It is recommended to write the source code for OpenCL in separate CL files, which can later be included in the MQL5 program using the [resource variables](resources.md#resourcevariables).

Declaration

```
   class COpenCL
```

Title

```
   #include <OpenCL\OpenCL.mqh>
```

Class methods

| Name | Description |
| --- | --- |
| [BufferCreate](copenclbuffercreate.md) | Creates an OpenCL buffer at the specified index |
| [BufferFree](copenclbufferfree.md) | Deletes buffer at the specified index |
| [BufferFromArray](copenclbufferfromarray.md) | Creates a buffer at the specified index from an array of values |
| [BufferRead](copenclbufferread.md) | Reads an OpenCL buffer at the specified index into an array |
| [BufferWrite](copenclbufferwrite.md) | Writes an array of values into buffer at the specified index |
| [Execute](copenclexecute.md) | Executes the OpenCL kernel with the specified index |
| [GetContext](copenclgetcontext.md) | Returns handle of the OpenCL context |
| [GetKernel](copenclgetkernel.md) | Returns handle of the kernel object at the specified index |
| [GetKernelName](copenclgetkernelname.md) | Returns name of the kernel object at the specified index |
| [GetProgram](copenclgetprogram.md) | Returns handle of the OpenCL program |
| [Initialize](copenclinitialize.md) | Initializes the OpenCL program |
| [KernelCreate](copenclkernelcreate.md) | Creates an entry point into the OpenCL program at the specified index |
| [KernelFree](copenclkernelfree.md) | Removes an OpenCL start function at the specified index |
| [SetArgument](copenclsetargument.md) | Sets a parameter for the OpenCL function at the specified index |
| [SetArgumentBuffer](copenclsetargumentbuffer.md) | Sets an OpenCL buffer as a parameter of the OpenCL function at the specified index |
| [SetArgumentLocalMemory](copenclsetargumentlocalmemory.md) | Sets a parameter in local memory for the OpenCL function at the specified index |
| [SetBuffersCount](copenclsetbufferscount.md) | Sets the number of buffers |
| [SetKernelsCount](copenclsetkernelscount.md) | Sets the number of kernel objects |
| [Shutdown](copenclshutdown.md) | Unloads the OpenCL program |
| [SupportDouble](copenclsupportdouble.md) | Checks if floating point data types are supported on the device |