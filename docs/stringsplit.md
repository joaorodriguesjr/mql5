StringSplit



[MQL5 Reference](index.md)  /  [String Functions](strings.md) / StringSplit

[![Previous](previous.png)](stringsetcharacter.md) 
[![Next](next.png)](stringsubstr.md)

StringSplit

Gets substrings by a specified separator from the specified string, returns the number of substrings obtained.

```
int  StringSplit(
   const string   string_value,       // A string to search in
   const ushort   separator,          // A separator using which substrings will be searched
   string         & result[]          // An array passed by reference to get the found substrings
   );
```

Parameters

string\_value

[in]  The string from which you need to get substrings. The string will not change.

pos

[in]  The code of the separator character. To get the code, you can use the [StringGetCharacter()](stringgetcharacter.md) function.

result[]

[out]  An array of strings where the obtained substrings are located.

Return Value

The number of substrings in the result[] array. If the separator is not found in the passed string, only one source string will be placed in the array.

If string\_value is empty or NULL, the function will return zero. In case of an error the function returns -1. To get the [error](errorcodes.md) code, call the [GetLastError()](getlasterror.md) function.

Example:

```
string to_split="_life_is_good_"; // A string to split into substrings
   string sep="_";                // A separator as a character
   ushort u_sep;                  // The code of the separator character
   string result[];               // An array to get strings
   //--- Get the separator code
   u_sep=StringGetCharacter(sep,0);
   //--- Split the string to substrings
   int k=StringSplit(to_split,u_sep,result);
   //--- Show a comment 
   PrintFormat("Strings obtained: %d. Used separator '%s' with the code %d",k,sep,u_sep);
   //--- Now output all obtained strings
   if(k>0)
     {
      for(int i=0;i<k;i++)
        {
         PrintFormat("result[%d]=\"%s\"",i,result[i]);
        }
     }
```

See also

[StringReplace()](stringreplace.md), [StringSubstr()](stringsubstr.md), [StringConcatenate()](stringconcatenate.md)