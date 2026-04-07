CString



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Strings](stringoperations.md) / CString

[![Previous](previous.png)](stringoperations.md) 
[![Next](next.png)](cstringstr.md)

CString

CString is a class for simplified access to the variables of string type.

Description

CString class provides simplified access to MQL5 API functions working with string variables.

Declaration

```
   class CString: public CObject
```

Title

```
   #include <Strings\String.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CString |

Class Methods by Groups

| Data access methods |  |
| --- | --- |
| [Str](cstringstr.md) | Gets a string |
| [Len](cstringlen.md) | Gets length of a string |
| [Copy](cstringcopy.md) | Copies a string copy |
| Fill methods |  |
| [Fill](cstringfill.md) | Fills a string |
| [Assign](cstringassign.md) | Assigns a string |
| [Append](cstringappend.md) | Appends a string |
| [Insert](cstringinsert.md) | Inserts a string |
| Compare methods |  |
| [Compare](cstringcompare.md) | Compares strings |
| [CompareNoCase](cstringcomparenocase.md) | Performs a case insensitive string comparison |
| Substring methods |  |
| [Left](cstringleft.md) | Gets a substring from the left |
| [Right](cstringright.md) | Gets a substring from the right |
| [Mid](cstringmid.md) | Gets a substring from the middle |
| Trim/delete methods |  |
| [Trim](cstringtrim.md) | Trims a string from the left and from the right |
| [TrimLeft](cstringtrimleft.md) | Trims a string from the left |
| [TrimRight](cstringtrimright.md) | Trims a string from the right |
| [Clear](cstringclear.md) | Clears a string |
| Convert methods |  |
| [ToUpper](cstringtoupper.md) | Converts a string to uppercase. |
| [ToLower](cstringtolower.md) | Converts a string to lowercase. |
| [Reverse](cstringreverse.md) | Reverses a string |
| Search methods |  |
| [Find](cstringfind.md) | Searches a substring left to right |
| [FindRev](cstringfindrev.md) | Searches a substring right to left |
| [Remove](cstringremove.md) | Deletes a substring |
| [Replace](cstringreplace.md) | Replaces a substring |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md) |