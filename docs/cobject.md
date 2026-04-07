Basic Class CObject



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md) / Basic Class CObject

[![Previous](previous.png)](copenclsupportdouble.md) 
[![Next](next.png)](cobjectgetprev.md)

Basic Class CObject

Class CObject is the base class for constructing a MQL5 Standard Library.

Description

Class CObject allows all its descendants to be part of a linked list. Also, a number of virtual methods for further implementation in descendant classes are identified.

Declaration

```
   class CObject
```

Title

```
   #include <Object.mqh>
```

|  |
| --- |
| Inheritance hierarchy    CObject  Direct descendants  [CAccountInfo](caccountinfo.md), [CArray](carray.md), [CChart](cchart.md), [CChartObject](cchartobject.md), [CCurve](ccurve.md), [CDealInfo](cdealinfo.md), CDictionary\_Obj\_Double, CDictionary\_Obj\_Obj, CDictionary\_String\_Obj, [CExpertBase](cexpertbase.md), [CFile](cfile.md), [CHistoryOrderInfo](chistoryorderinfo.md), [CList](clist.md), [COrderInfo](corderinfo.md), [CPositionInfo](cpositioninfo.md), [CString](cstring.md), [CSymbolInfo](csymbolinfo.md), [CTerminalInfo](cterminalinfo.md), [CTrade](ctrade.md), [CTreeNode](ctreenode.md), [CWnd](cwnd.md), ICondition, IExpression, [IMembershipFunction](imembershipfunction.md), INamedValue, IParsableRule |

Class Methods by Groups

| Attributes |  |
| --- | --- |
| [Prev](cobjectgetprev.md) | Gets the value of the previous item |
| [Prev](cobjectsetprev.md) | Sets the value of the previous item |
| [Next](cobjectgetnext.md) | Gets the value of the subsequent element |
| [Next](cobjectsetnext.md) | Sets the next element |
| Compare methods |  |
| virtual [Compare](cobjectcompare.md) | Returns the result of comparison with another object |
| Input/output |  |
| virtual [Save](cobjectsave.md) | Writes object to a file |
| virtual [Load](cobjectload.md) | Reads the object from the file |
| virtual [Type](cobjecttype.md) | Returns the type of object |