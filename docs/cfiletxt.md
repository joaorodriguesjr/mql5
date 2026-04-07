CFileTxt



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Files](fileoperations.md) / CFileTxt

[![Previous](previous.png)](cfilebinreadobject.md) 
[![Next](next.png)](cfiletxtopen.md)

CFileTxt

CFileTxt is a class for simplified access to text files.

Description

CFileTxt class provides access to text files.

Declaration

```
   class CFileTxt: public CFile
```

Title

```
   #include <Files\FileTxt.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CFile](cfile.md)            CFileTxt |

Class Methods by Groups

| Open methods |  |
| --- | --- |
| [Open](cfiletxtopen.md) | Opens a text file |
| Write methods |  |
| [WriteString](cfiletxtwritestring.md) | Writes string type variable |
| Read methods |  |
| [ReadString](cfiletxtreadstring.md) | Reads string type variable |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CFile  [Handle](cfilehandle.md), [FileName](cfilefilename.md), [Flags](cfileflags.md), [SetUnicode](cfilesetunicode.md), [SetCommon](cfilesetcommon.md), [Open](cfileopen.md), [Close](cfileclose.md), [Delete](cfiledelete.md), [Size](cfilesize.md), [Tell](cfiletell.md), [Seek](cfileseek.md), [Flush](cfileflush.md), [IsEnding](cfileisending.md), [IsLineEnding](cfileislineending.md), [Delete](cfiledelete.md), [IsExist](cfileisexist.md), [Copy](cfilecopy.md), [Move](cfilemove.md), [FolderCreate](cfilefoldercreate.md), [FolderDelete](cfilefolderdelete.md), [FolderClean](cfilefolderclean.md), [FileFindFirst](cfilefilefindfirst.md), [FileFindNext](cfilefilefindnext.md), [FileFindClose](cfilefilefindclose.md) |