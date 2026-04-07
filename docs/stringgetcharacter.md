StringGetCharacter



[MQL5 Reference](index.md)  /  [String Functions](strings.md) / StringGetCharacter

[![Previous](previous.png)](stringfind.md) 
[![Next](next.png)](stringinit.md)

StringGetCharacter

Returns value of a symbol, located in the specified position of a string.

```
ushort  StringGetCharacter(
   string  string_value,     // string
   int     pos               // symbol position in the string
   );
```

Parameters

string\_value

[in]  String.

pos

[in]  Position of a symbol in the string. Can be from 0 to [StringLen](stringlen.md)(text) -1.

Return Value

Symbol code or 0 in case of an error. To get the [error code](errorcodes.md) call [GetLastError()](getlasterror.md).

Example:

```
void OnStart()
  {
//--- delete all comments on the chart
   Comment("");
//--- declare a string, from which we will obtain the values of symbol codes and remember the string length
   string message = "The script demonstrates the operation of the StringGetCharacter() function";
   int    length  = StringLen(message);
//--- declare a string variable, to which we will add the obtained symbols from the demo string
   string text    = "";
//--- in the loop by the demo string length
   for(int i=0; i<length; i++)
     {
      //--- wait 1/10 seconds
      Sleep(100);
      //--- get a symbol from a string located at the loop index in the demo string
      ushort char_code=StringGetCharacter(message, i);
      //--- add a symbol to the displayed string and display the resulting string as a chart comment
      text+=ShortToString(char_code);
      Comment(text);
     }
//--- wait two seconds and remove the comment from the chart
   Sleep(2000);
   Comment("");
   
   /*
   Result: the demo string appears on the screen character by character
   The script demonstrates the operation of the StringGetCharacter() function
   */
  }
```

See also

[StringSetCharacter](stringsetcharacter.md), [StringBufferLen](stringbufferlen.md), [StringLen](stringlen.md), [StringFill](stringfill.md), [StringInit](stringinit.md), [StringToCharArray](stringtochararray.md), [StringToShortArray](stringtoshortarray.md)