StringEndsWith



MQL5 Reference > List of MQL5 Constants

StringEndsWith

Searches for a specified substring at the end of a string.

```
bool  StringEndsWith(
   string        string_value,         // string the search for prefix is performed in
   const string  suffix,               // the suffix string, the search for which is performed at the end of the string
   bool          case_sensitive=true   // case sensitive search
   );
```

Parameters

string\_value

[in]  String the search for suffix is performed in.

suffix

[in]  Substring to be present at the end of the string\_value string.

case\_sensitive=true

[in]  Case sensitivity flag. If true, the search for a suffix is case sensitive.

Return Value

In case of successful execution, returns true, otherwise - false. To receive an [error](errorcodes.md) code, the [GetLastError()](getlasterror.md) function should be called.

See also

[StringFind](stringfind.md), [StringSubstr](stringsubstr.md), [StringGetCharacter](stringgetcharacter.md), [StringStartsWith](stringstartswith.md)