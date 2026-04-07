CFileBin



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md) / CFileBin

[![Previous](previous.png)](cfilefilefindclose.md) 
[![Next](next.png)](cfilebinopen.md)

CFileBin

CFileBin is a class for simplified access to binary files.

Description

CFileBin class provides access to binary files.

Declaration

```
   class CFileBin: public CFile
```

Title

```
   #include <Files\FileBin.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CFile](cfile.md)            CFileBin |

Class Methods by Groups

| Open methods |  |
| --- | --- |
| [Open](cfilebinopen.md) | Opens a binary file |
| Write methods |  |
| [WriteChar](cfilebinwritechar.md) | Writes char or uchar type variable |
| [WriteShort](cfilebinwriteshort.md) | Writes short or ushort type variable |
| [WriteInteger](cfilebinwriteinteger.md) | Writes int or uint type variable |
| [WriteLong](cfilebinwritelong.md) | Writes long or ulong type variable |
| [WriteFloat](cfilebinwritefloat.md) | Writes float type variable |
| [WriteDouble](cfilebinwritedouble.md) | Writes double type variable |
| [WriteString](cfilebinwritestring.md) | Writes string type variable |
| [WriteCharArray](cfilebinwritechararray.md) | Writes an array of char or uchar type variables |
| [WriteShortArray](cfilebinwriteshortarray.md) | Writes an array of short or ushort type variables |
| [WriteIntegerArray](cfilebinwriteintegerarray.md) | Writes an array of int or uint type variables |
| [WriteLongArray](cfilebinwritelongarray.md) | Writes an array of long or ulong type variables |
| [WriteFloatArray](cfilebinwritefloatarray.md) | Writes an array of float variables |
| [WriteDoubleArray](cfilebinwritedoublearray.md) | Writes an array of double type variables |
| [WriteObject](cfilebinwriteobject.md) | Writes data of the CObject class inheritor instance |
| Read methods |  |
| [ReadChar](cfilebinreadchar.md) | Reads char or uchar type variable |
| [ReadShort](cfilebinreadshort.md) | Reads short or ushort type variable |
| [ReadInteger](cfilebinreadinteger.md) | Reads int or uint type variable |
| [ReadLong](cfilebinreadlong.md) | Reads long or ulong type variable |
| [ReadFloat](cfilebinreadfloat.md) | Reads float type variable |
| [ReadDouble](cfilebinreaddouble.md) | Reads double type variable |
| [ReadString](cfilebinreadstring.md) | Reads string type variable |
| [ReadCharArray](cfilebinreadchararray.md) | Reads an array of char or uchar type variables |
| [ReadShortArray](cfilebinreadshortarray.md) | Reads an array of short or ushort type variables |
| [ReadIntegerArray](cfilebinreadintegerarray.md) | Reads an array of int or uint type variables |
| [ReadLongArray](cfilebinreadlongarray.md) | Reads an array of long or ulong type variables |
| [ReadFloatArray](cfilebinreadfloatarray.md) | Reads an array of float type variables |
| [ReadDoubleArray](cfilebinreaddoublearray.md) | Reads an array of double type variables |
| [ReadObject](cfilebinreadobject.md) | Reads data of the CObject class inheritor instance |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CFile  [Handle](cfilehandle.md), [FileName](cfilefilename.md), [Flags](cfileflags.md), [SetUnicode](cfilesetunicode.md), [SetCommon](cfilesetcommon.md), [Open](cfileopen.md), [Close](cfileclose.md), [Delete](cfiledelete.md), [Size](cfilesize.md), [Tell](cfiletell.md), [Seek](cfileseek.md), [Flush](cfileflush.md), [IsEnding](cfileisending.md), [IsLineEnding](cfileislineending.md), [Delete](cfiledelete.md), [IsExist](cfileisexist.md), [Copy](cfilecopy.md), [Move](cfilemove.md), [FolderCreate](cfilefoldercreate.md), [FolderDelete](cfilefolderdelete.md), [FolderClean](cfilefolderclean.md), [FileFindFirst](cfilefilefindfirst.md), [FileFindNext](cfilefilefindnext.md), [FileFindClose](cfilefilefindclose.md) |