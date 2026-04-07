CFile



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md) / CFile

[![Previous](previous.png)](fileoperations.md) 
[![Next](next.png)](cfilehandle.md)

CFile

CFile is a base class for CFileBin and CFileTxt classes.

Description

CFile class provides the simplified access to MQL5 API file and folder functions for all of its descendants.

Declaration

```
   class CFile: public CObject
```

Title

```
   #include <Files\File.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CFile  Direct descendants  [CFileBin](cfilebin.md), CFilePipe, [CFileTxt](cfiletxt.md) |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Handle](cfilehandle.md) | Gets file handle |
| [Filename](cfilefilename.md) | Gets file name |
| [Flags](cfileflags.md) | Gets file flags |
| [SetUnicode](cfilesetunicode.md) | Sets/clears the FILE\_UNICODE flag |
| [SetCommon](cfilesetcommon.md) | Sets/clears the FILE\_COMMON flag |
| General methods for files |  |
| [Open](cfileopen.md) | Opens file |
| [Close](cfileclose.md) | Closes file |
| [Delete](cfiledelete.md) | Deletes file |
| [IsExist](cfileisexist.md) | Checks file for existence |
| [Copy](cfilecopy.md) | Copies file |
| [Move](cfilemove.md) | Renames/moves file |
| [Size](cfilesize.md) | Gets file size |
| [Tell](cfiletell.md) | Gets current file position |
| [Seek](cfileseek.md) | Sets current file position |
| [Flush](cfileflush.md) | Flushes data on disk |
| [IsEnding](cfileisending.md) | Checks file for end |
| [IsLineEnding](cfileislineending.md) | Checks line for end |
| General methods for folders |  |
| [FolderCreate](cfilefoldercreate.md) | Creates folder |
| [FolderDelete](cfilefolderdelete.md) | Deletes folder |
| [FolderClean](cfilefolderclean.md) | Clears folder |
| Files and folders search methods |  |
| [FileFindFirst](cfilefilefindfirst.md) | Begins file search |
| [FileFindNext](cfilefilefindnext.md) | Continues file search |
| [FileFindClose](cfilefilefindclose.md) | Closes search handle |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |