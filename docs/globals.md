Global Variables of the Terminal



[MQL5 Reference](index.md) / Global Variables of the Terminal

[![Previous](previous.png)](sendnotification.md) 
[![Next](next.png)](globalvariablecheck.md)

Global Variables of the Client Terminal

There is a group set of functions for working with global variables.

Global variables of the client terminal should not be mixed up with variables declared in the [global scope](global.md) of the mql5 program.

Global variables are kept in the client terminal for 4 weeks since the last access, then they will be deleted automatically. An access to a global variable is not only setting of a new value, but reading of the global variable value, as well.

Global variables of the client terminal are accessible simultaneously from all mql5 programs launched in the client terminal.

| Function | Action |
| --- | --- |
| [GlobalVariableCheck](globalvariablecheck.md) | Checks the existence of a global variable with the specified name |
| [GlobalVariableTime](globalvariabletime.md) | Returns time of the last accessing the global variable |
| [GlobalVariableDel](globalvariabledel.md) | Deletes a global variable |
| [GlobalVariableGet](globalvariableget.md) | Returns the value of a global variable |
| [GlobalVariableName](globalvariablename.md) | Returns the name of a global variable by its ordinal number in the list of global variables |
| [GlobalVariableSet](globalvariableset.md) | Sets the new value to a global variable |
| [GlobalVariablesFlush](globalvariablesflush.md) | Forcibly saves contents of all global variables to a disk |
| [GlobalVariableTemp](globalvariabletemp.md) | Sets the new value to a global variable, that exists only in the current session of the terminal |
| [GlobalVariableSetOnCondition](globalvariablesetoncondition.md) | Sets the new value of the existing global variable by condition |
| [GlobalVariablesDeleteAll](globalvariablesdeleteall.md) | Deletes global variables with the specified prefix in their names |
| [GlobalVariablesTotal](globalvariablestotal.md) | Returns the total number of global variables |