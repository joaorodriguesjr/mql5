StringToUpper



[MQL5 Reference](index.md)  /  [String Functions](strings.md) / StringToUpper

[![Previous](previous.png)](stringtolower.md) 
[![Next](next.png)](stringtrimleft.md)

StringToUpper

Transforms all symbols of a selected string into capitals.

```
bool  StringToUpper(
   string&  string_var      // string to process
   );
```

Parameters

string\_var

[in][out]  String.

Return Value

In case of success returns true, otherwise - false. To get the [error code](errorcodes.md) call [GetLastError()](getlasterror.md).

Example:

```
void OnStart()
  {
//--- define the source string in lowercase
   string text=" - this string, written in lowercase, must be written in uppercase";
//--- Display the source string in the log
   Print("Source line:\n", text);
//--- convert all string characters to uppercase and display the result in the log
   if(StringToUpper(text))
      Print("The original string after using the StringToUpper() function:\n", text);
      
   /*
   Result
   Source line:
    - this string, written in lowercase, must be written in uppercase
   The original string after using the StringToUpper() function:
    - THIS STRING, WRITTEN IN LOWERCASE, MUST BE WRITTEN IN UPPERCASE
   */
  }
```

See also

[StringToLower](stringtolower.md), [StringTrimLeft](stringtrimleft.md), [StringTrimRight](stringtrimright.md)