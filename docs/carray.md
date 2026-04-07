CArray



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArray

[![Previous](previous.png)](datastructures.md) 
[![Next](next.png)](carraystep.md)

CArray

CArray class is the base class of a dynamic array of variables.

Description

Class CArray is intended to operate on dynamic arrays of variables: memory allocation, sorting, and working with files.

Declaration

```
   class CArray : public CObject
```

Title

```
   #include <Arrays\Array.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CArray  Direct descendants  [CArrayChar](carraychar.md), [CArrayDouble](carraydouble.md), [CArrayFloat](carrayfloat.md), [CArrayInt](carrayint.md), [CArrayLong](carraylong.md), [CArrayObj](carrayobj.md), [CArrayShort](carrayshort.md), [CArrayString](carraystring.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Step](carraystep.md) | Gets the increment size of the array |
| [Step](carraystepbool.md) | Sets the increment size of the array |
| [Total](carraytotal.md) | Gets the number of elements in the array |
| [Available](carrayavailable.md) | Gets the number of free elements of the array that are available without additional memory allocation |
| [Max](carraymax.md) | Gets the maximum possible size of the array without memory reallocation |
| [IsSorted](carrayissorted.md) | Gets the flag of array being sorted using specified sorting mode |
| [SortMode](carraysortmode.md) | Gets the sorting mode for an array |
| Clear methods |  |
| [Clear](carrayclear.md) | Deletes all of the array elements without memory release |
| Sort methods |  |
| [Sort](carraysort.md) | Sorts an array to the specified option |
| Input/output |  |
| virtual [Save](carraysave.md) | Saves data array in a file |
| virtual [Load](carrayload.md) | Loads data array from a file |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Type](cobjecttype.md), [Compare](cobjectcompare.md) |