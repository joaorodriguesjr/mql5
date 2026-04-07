Array Functions



[MQL5 Reference](index.md) / Array Functions

[![Previous](previous.png)](zeromemory.md) 
[![Next](next.png)](arraybsearch.md)

Group of Functions for Working with Arrays

[Arrays](variables.md#array_define) are allowed to be maximum four-dimensional. Each dimension is indexed from 0 to dimension\_size-1. In a particular case of a one-dimensional array of 50 elements, calling of the first element will appear as array[0], of the last one - as array[49].

| Function | Action |
| --- | --- |
| [ArrayBsearch](arraybsearch.md) | Returns index of the first found element in the first array dimension |
| [ArrayCopy](arraycopy.md) | Copies one array into another |
| [ArrayCompare](arraycompare.md) | Returns the result of comparing two arrays of [simple types](types.md#base_types) or custom structures without [complex objects](types.md#complex_types) |
| [ArrayFree](arrayfree.md) | Frees up buffer of any dynamic array and sets the size of the zero dimension in 0. |
| [ArrayGetAsSeries](arraygetasseries.md) | Checks direction of array indexing |
| [ArrayInitialize](arrayinitialize.md) | Sets all elements of a numeric array into a single value |
| [ArrayFill](arrayfill.md) | Fills an array with the specified value |
| [ArrayIsSeries](arrayisseries.md) | Checks whether an array is a timeseries |
| [ArrayIsDynamic](arrayisdynamic.md) | Checks whether an array is dynamic |
| [ArrayMaximum](arraymaximum.md) | Search for an element with the maximal value |
| [ArrayMinimum](arrayminimum.md) | Search for an element with the minimal value |
| [ArrayPrint](arrayprint.md) | Prints an array of a simple type or a simple structure into journal |
| [ArrayRange](arrayrange.md) | Returns the number of elements in the specified dimension of the array |
| [ArrayResize](arrayresize.md) | Sets the new size in the first dimension of the array |
| [ArrayInsert](arrayinsert.md) | Inserts the specified number of elements from a source array to a receiving one starting from a specified index |
| [ArrayRemove](arrayremove.md) | Removes the specified number of elements from the array starting with a specified index |
| [ArrayReverse](array_reverse.md) | Reverses the specified number of elements in the array starting with a specified index |
| [ArraySetAsSeries](arraysetasseries.md) | Sets the direction of array indexing |
| [ArraySize](arraysize.md) | Returns the number of elements in the array |
| [ArraySort](arraysort.md) | Sorting of numeric arrays by the first dimension |
| [ArraySwap](arrayswap.md) | Swaps the contents of two dynamic arrays of the same type |
| [ArrayToFP16](arraytofp16.md) | Copies an array of type float or double into an array of type [ushort](integertypes.md#ushort) with the given format |
| [ArrayToFP8](arraytofp8.md) | Copies an array of type float or double into an array of type [uchar](integertypes.md#uchar) with the given format |
| [ArrayFromFP16](arrayfromfp16.md) | Copies an array of type [ushort](integertypes.md#ushort) into an array of float or double type with the given format |
| [ArrayFromFP8](arrayfromfp8.md) | Copies an array of type [uchar](integertypes.md#uchar) into an array of float or double type with the given format |