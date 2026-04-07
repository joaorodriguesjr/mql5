CTerminalInfo



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Trade Classes](tradeclasses.md) / CTerminalInfo

[![Previous](previous.png)](ctradeformatrequestresult.md) 
[![Next](next.png)](cterminalinfobuild.md)

CTerminalInfo

CTerminalInfo is a class for simplified access to the properties of mql5 program environment.

Description

CTerminalInfo class provides access to the properties of mql5 program environment.

Declaration

```
   class CTerminalInfo : public CObject
```

Title

```
   #include <Trade\TerminalInfo.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CTerminalInfo |

Class methods by groups

| Methods for access to the properties of integer type |  |
| --- | --- |
| [Build](cterminalinfobuild.md) | Gets the build number of the client terminal |
| [IsConnected](cterminalinfoisconnected.md) | Gets the information about connection to trade server |
| [IsDLLsAllowed](cterminalinfoisdllsallowed.md) | Gets the information about permission of DLL usage |
| [IsTradeAllowed](cterminalinfoistradeallowed.md) | Gets the information about permission to trade |
| [IsEmailEnabled](cterminalinfoisemailenabled.md) | Gets the information about permission to send e-mails to SMTP server and login, specified in the terminal settings |
| [IsFtpEnabled](cterminalinfoisftpenabled.md) | Gets the information about permission to send trade reports to FTP server and login, specified in the terminal settings |
| [MaxBars](cterminalinfomaxbars.md) | Gets the information about maximum number of bars on chart |
| [CodePage](cterminalinfocodepage.md) | Gets the information about the code page of the language in the client terminal |
| [CPUCores](cterminalinfocpucores.md) | Gets the information about the CPU cores |
| [MemoryPhysical](cterminalinfomemoryphysical.md) | Gets the information about the physical memory (in Mb) |
| [MemoryTotal](cterminalinfomemorytotal.md) | Gets the information about the total memory available for the terminal/agent process (in Mb) |
| [MemoryAvailable](cterminalinfomemoryavailable.md) | Gets the information about the free memory available for the terminal/agent process (in Mb) |
| [MemoryUsed](cterminalinfomemoryused.md) | Gets the information about the memory used by the terminal/agent process (in Mb) |
| [IsX64](cterminalinfoisx64.md) | Gets the information about the type of the client terminal |
| [OpenCLSupport](cterminalinfoopenclsupport.md) | Gets the information about the version of OpenCL supported by video card |
| [DiskSpace](cterminalinfodiskspace.md) | Gets the information about free disk space (in Mb) |
| Methods for access to the properties of string type |  |
| [Language](cterminalinfolanguage.md) | Gets the language of the client terminal |
| [Name](cterminalinfoname.md) | Gets the name of the client terminal |
| [Company](cterminalinfocompany.md) | Gets the company name of the client terminal |
| [Path](cterminalinfopath.md) | Gets the folder of the client terminal |
| [DataPath](cterminalinfodatapath.md) | Gets the data folder of the client terminal |
| [CommonDataPath](cterminalinfocommondatapath.md) | Gets the common data folder of all client terminals, installed on the computer |
| Access to MQL5 API functions |  |
| [InfoInteger](cterminalinfoinfointeger.md) | Gets the value of the property of integer type |
| [InfoString](cterminalinfoinfostring.md) | Gets the value of property of string type |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |