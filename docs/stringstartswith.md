StringStartsWith



MQL5 Reference > List of MQL5 Constants

StringStartsWith

Searches for a specified substring at the beginning of a string.

```
bool  StringStartsWith(
   string        string_value,         // string the search for prefix is performed in
   const string  prefix,               // the prefix string, the search for which is performed at the beginning of the string
   uint          start_pos=0,          // starting position for a search
   bool          case_sensitive=true   // case sensitive search
   );
```

Parameters

string\_value

[in]  String the search for prefix is performed in.

prefix

[in]  Substring the string\_value string should start from.

start\_pos=0

[in]  String position the search for prefix is started from. By default, the search for prefix is performed at the very beginning of the string

case\_sensitive=true

[in]  Case sensitivity flag. If true, the search for a prefix is case sensitive.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

See also

[StringFind](stringfind.md), [StringSubstr](stringsubstr.md), [StringGetCharacter](stringgetcharacter.md), [StringEndsWith](stringendswith.md)