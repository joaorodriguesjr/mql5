CArrayObj



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Data Collections](datastructures.md) / CArrayObj

[![Previous](previous.png)](carraystringtype.md) 
[![Next](next.png)](carrayobjfreemode.md)

CArrayObj

CArrayObj class is a class of dynamic array of pointers to instances of CObject and its derived classes.

Description

Class CArrayObj provides the ability to work with a dynamic array of pointers to instances of [CObject](cobject.md) and its derived classes. This allows working both with multidimensional dynamic arrays of primitive data types and with data structures that have more complex organization of data.

The class allows adding/inserting/deleting array elements, performing an array sorting, and searching in a sorted array. In addition, methods of working with files have been implemented.

There are certain [subtleties](carrayobj.md#carrayobjfeatures) of the class CArrayObj.

Declaration

```
   class CArrayObj : public CArray
```

Title

```
   #include <Arrays\ArrayObj.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CArray](carray.md)            CArrayObj  Direct descendants  [CIndicators](cindicators.md), [CSeries](cseries.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [FreeMode](carrayobjfreemode.md) | Gets the flag of memory management |
| [FreeMode](carrayobjfreemodeconst.md) | Sets the flag of memory management |
| Memory control |  |
| [Reserve](carrayobjreserve.md) | Allocates memory to increase the size of the array |
| [Resize](carrayobjresize.md) | Sets a new (smaller) size of the array |
| [Shutdown](carrayobjshutdown.md) | Clears the array with full deallocation of its memory (but not its elements). |
| Creating a new element |  |
| virtual [CreateElement](carrayobjcreateelement.md) | Creates a new array element in the specified position |
| Add methods |  |
| [Add](carrayobjadd.md) | Adds an element to the end of the array |
| [AddArray](carrayobjaddarray.md) | Adds an element to the end of the array |
| [Insert](carrayobjinsert.md) | Inserts an element to the specified position in the array |
| [InsertArray](carrayobjinsertarray.md) | Inserts to an array elements from another array from the specified position |
| [AssignArray](carrayobjassignarray.md) | Copies the elements of one array to another |
| Update methods |  |
| [Update](carrayobjupdate.md) | Changes the element at the specified position array |
| [Shift](carrayobjshift.md) | Moves an item from a given position in the array to the specified offset |
| Delete methods |  |
| [Detach](carrayobjdetach.md) | Gets the element from the specified position and removes it from the array |
| [Delete](carrayobjdelete.md) | Removes the element from the specified array position |
| [DeleteRange](carrayobjdeleterange.md) | Deletes a group of elements from the specified array position |
| [Clear](carrayobjclear.md) | Removes all elements of the array without the release of the array memory |
| Access methods |  |
| [At](carrayobjat.md) | Gets the element from the specified array position |
| Compare methods |  |
| [CompareArray](carrayobjcomparearray.md) | Compares the array with another one |
| Sorted array operations |  |
| [InsertSort](carraystringinsertsort.md) | Inserts an element in a sorted array |
| [Search](carrayobjsearch.md) | Searches for an element equal to the sample in the sorted array |
| [SearchGreat](carrayobjsearchgreat.md) | Searches for an element with a value exceeding the value of the sample in the sorted array |
| [SearchLess](carrayobjsearchless.md) | Searches for an element with a value less than the value of the sample in the sorted array |
| [SearchGreatOrEqual](carrayobjsearchgreatorequal.md) | Searches for an element with a value greater than or equal to the value of the sample in the sorted array |
| [SearchLessOrEqual](carrayobjsearchlessorequal.md) | Searches for an element with a value less than or equal to the value of the sample in the sorted array |
| [SearchFirst](carrayobjsearchfirst.md) | Searches for the first element equal to the sample in the sorted array |
| [SearchLast](carrayobjsearchlast.md) | Searches for the last element equal to the sample in the sorted array |
| Input/output |  |
| [Save](carrayobjsave.md) | Saves data array in the file |
| [Load](carrayobjload.md) | Loads data array from the file |
| [Type](carrayobjtype.md) | Gets the type identifier of the array |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CArray  [Step](carraystep.md), [Step](carraystep.md), [Total](carraytotal.md), [Available](carrayavailable.md), [Max](carraymax.md), [IsSorted](carrayissorted.md), [SortMode](carraysortmode.md), [Clear](carrayclear.md), [Sort](carraysort.md) |

Arrays of the CObject class have practical application (including all classes of the Standard Library).

For example, consider the options for two-dimensional array:

```
#include <Arrays\ArrayDouble.mqh>
#include <Arrays\ArrayObj.mqh>
//---
void OnStart()
  {
   int i,j;
   int first_size=10;
   int second_size=100;
//--- create array
   CArrayObj    *array=new CArrayObj;
   CArrayDouble *sub_array;
//---
   if(array==NULL)
     {
      printf("Object create error");
      return;
     }
//--- create subarrays
   for(i=0;i<first_size;i++)
     {
      sub_array=new CArrayDouble;
      if(sub_array==NULL)
        {
         delete array;
         printf("Object create error");
         return;
        }
      //--- fill array
      for(j=0;j<second_size;j++)
        {
         sub_array.Add(i*j);
        }
      array.Add(sub_array);
     }
//--- create array OK
   for(i=0;i<first_size;i++)
     {
      sub_array=array.At(i);
      for(j=0;j<second_size;j++)
        {
         double element=sub_array.At(j);
         //--- use array element
        }
     }
   delete array;
  }
```

Subtleties

The class has a mechanism to control dynamic memory, so be careful when working with elements of the array.

Mechanism of memory management can be switched on/off using the method FreeMode (bool). By default, the mechanism is enabled.

Accordingly, there are two options for dealing with the CArrayObj class:

1. Mechanism of memory management is enabled. (default)

In this case, CArrayObj takes responsibility for releasing the memory used for the elements after their removal from the array. A custom program should not release the array elements.

Example:

```
   int i;
//--- create an array
   CArrayObj *array=new CArrayObj;
//--- fill array elements
   for(i=0;i<10;i++) array.Add(new CObject);
//--- do something
   for(i=0;i<array.Total();i++)
     {
      CObject *object=array.At(i);
      //--- actions performed with the element
      . . .
     }
//--- remove the array with the elements
   delete array;
```

2. Mechanism of memory management is disabled.

In this case, CArrayObj is not responsible for deallocating of the elements' memory after their removal from the array. Besides, the user program must deallocate the array elements.

Example:

```
   int i;
//--- create an array
   CArrayObj *array=new CArrayObj;
//--- disable the mechanism of memory management
   array.FreeMode(false);
//--- fill array with elements
   for(i=0;i<10;i++) array.Add(new CObject);
//--- do something
   for(i=0;i<array.Total();i++)
     {
      CObject *object=array.At(i);
      //--- actions performed with the element
      . . .
     }
//--- remove array elements
   while(array.Total()) delete array.Detach();
//--- remove empty array
   delete array;
```