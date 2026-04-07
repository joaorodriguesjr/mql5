Automatic data type conversion



[MQL5 Reference](index.md)  /  [ONNX models](onnx.md) / Automatic data type conversion

[![Previous](previous.png)](onnx_conversion.md) 
[![Next](next.png)](onnx_prepare.md)

Autoconvert input and output values when running ONNX models

The current ONNX version in MQL5 supports only tensors for [input/output](https://onnxruntime.ai/docs/api/python/api_summary.md#data-inputs-and-outputs) values. Tensors are data arrays with the elements of the following data types:

| ONNX type | Corresponds to MQL5 type |
| --- | --- |
| ONNX\_DATA\_TYPE\_BOOL | [bool](boolconst.md) |
| ONNX\_DATA\_TYPE\_FLOAT | [float](double.md) |
| ONNX\_DATA\_TYPE\_UINT8 | [uchar](integertypes.md) |
| ONNX\_DATA\_TYPE\_INT8 | [char](integertypes.md) |
| ONNX\_DATA\_TYPE\_UINT16 | [ushort](integertypes.md) |
| ONNX\_DATA\_TYPE\_INT16 | [short](integertypes.md) |
| ONNX\_DATA\_TYPE\_INT32 | [int](integertypes.md) |
| ONNX\_DATA\_TYPE\_INT64 | [long](integertypes.md) |
| ONNX\_DATA\_TYPE\_FLOAT16 |  |
| ONNX\_DATA\_TYPE\_DOUBLE | [double](double.md) |
| ONNX\_DATA\_TYPE\_UINT32 | [uint](integertypes.md) |
| ONNX\_DATA\_TYPE\_UINT64 | [ulong](integertypes.md) |
| ONNX\_DATA\_TYPE\_COMPLEX64 |  |
| ONNX\_DATA\_TYPE\_COMPLEX128 | [complex](complex.md) |
| ONNX\_DATA\_TYPE\_BFLOAT16 |  |
| ONNX\_DATA\_TYPE\_STRING |  |

 

Only arrays, [vectors and matrices](matrix_vector.md) (we will refer to them as the Data) can be fed into ONNX models as input/output values.

If the parameter types does not match the ONNX model's parameter type, and the [OnnxRun](onnxrun.md) is called without the [ONNX\_NO\_CONVERSION](onnx_structures.md#enum_onnx_flags) flag specified, automatic data conversion will be applied. Autoconversion implies that before running an ONNX model, user Data will be copied into ONNX tensors with the relevant conversion.

When an ONNX model is run without the autoconversion, the model will be calculated using the Data without any additional copying.

IMPORTANT! Autoconversion does not control overflow (truncate), therefore you should carefully monitor the data and the data types input into the ONNX model.

Autoconversion supports the following ONNX types:

* ONNX\_DATA\_TYPE\_BOOL
* ONNX\_DATA\_TYPE\_FLOAT
* ONNX\_DATA\_TYPE\_UINT8
* ONNX\_DATA\_TYPE\_INT8
* ONNX\_DATA\_TYPE\_UINT16
* ONNX\_DATA\_TYPE\_INT16
* ONNX\_DATA\_TYPE\_INT32
* ONNX\_DATA\_TYPE\_INT64
* ONNX\_DATA\_TYPE\_FLOAT16
* ONNX\_DATA\_TYPE\_DOUBLE
* ONNX\_DATA\_TYPE\_UINT32
* ONNX\_DATA\_TYPE\_UINT64
* ONNX\_DATA\_TYPE\_COMPLEX64
* ONNX\_DATA\_TYPE\_COMPLEX128

Unsupported types:

* ONNX\_DATA\_TYPE\_BFLOAT16
* ONNX\_DATA\_TYPE\_STRING

 

Autoconversion Rules by Tensor Types

If the [MQL5 type](types.md) is not included into the list of types supported by the model, running the ONNX model will return the ERR\_ONNX\_NOT\_SUPPORTED error (error code 5802).

Note: During autoconversion, the [color](boolconst.md) type is processed as uint, while [datetime](datetime.md) is processed as long.

 

Autoconversion of input values

| ONNX type (tensor item type) | MQL5 type supported by autoconversion |
| --- | --- |
| ONNX\_DATA\_TYPE\_BOOL | bool, char, uchar, short, ushort, int, color, uint, datetime, long,  folat, double, complex     During conversion, Data elements are checked by a simple comparison against 0 |
| ONNX\_DATA\_TYPE\_FLOAT16 | float, double |
| ONNX\_DATA\_TYPE\_FLOAT | char, uchar, short, ushort, int, color, uint, datetime, long, ulong, float, double |
| ONNX\_DATA\_TYPE\_UINT8 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT8 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_UINT16 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT16 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT32 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT64 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_DOUBLE | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_UINT32 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_UINT64 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_COMPLEX64 | complex |
| ONNX\_DATA\_TYPE\_COMPLEX128 | complex |

 

Autoconversion of output values

| ONNX type (tensor item type) | MQL5 type supported by autoconversion |
| --- | --- |
| ONNX\_DATA\_TYPE\_BOOL | bool, char, uchar, short, ushort, int, color, uint, datetime, long,  folat, double, complex     If the tensor element is zero, then the Data element is set to 0; otherwise, the value is 1 |
| ONNX\_DATA\_TYPE\_FLOAT16 | float, double |
| ONNX\_DATA\_TYPE\_FLOAT | char, uchar, short, ushort, int, color, uint, datetime, long, ulong, float, double |
| ONNX\_DATA\_TYPE\_UINT8 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT8 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_UINT16 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT16 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT32 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_INT64 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_DOUBLE | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_UINT32 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_UINT64 | See ONNX\_DATA\_TYPE\_FLOAT |
| ONNX\_DATA\_TYPE\_COMPLEX64 | complex |
| ONNX\_DATA\_TYPE\_COMPLEX128 | complex |

 

See also

[Type Casting](casting.md)