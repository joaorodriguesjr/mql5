Creating and Deleting Objects



[MQL5 Reference](index.md)  /  [Language Basics](basis.md)  /  [Variables](variables.md) / Creating and Deleting Objects

[![Previous](previous.png)](variable_scope.md) 
[![Next](next.png)](preprosessor.md)

Creating and Deleting Objects

After a MQL5 program is loaded for execution, memory is allocated to each variable according to its type. According to the access level, all variables are divided into two types - [global variables](global.md) and [local variables](local.md). According to the memory class, they can be [input parameters](inputvariables.md) of a MQL5 program, [static](static.md) and automatic. If necessary, each variable is [initialized](initialization.md) by a corresponding value. After being used a variable is unintialized and memory used by it is returned to the MQL5 executable system.

Initialization and Deinitialization of Global Variables

Global variables are initialized automatically right after a MQL5 program is loaded and before any of function is called. During initialization initial values are assigned to variables of [simple](types.md#base_types) types and a constructor (if there is any) is called for objects. [Input variables](inputvariables.md) are always declared at a global level, and are initialized by values set by a user in the dialog during the program start.

Despite the fact that [static](static.md) variables are usually declared at a local level, the memory for these variables is pre-allocated, and initialization is performed right after a program is loaded, the same as for [global](global.md) variables.

The initialization order corresponds to the variable declaration order in the program. Deinitialization is performed in the reverse order. This rule is true only for the variables that were not created by the new operator. Such variables are created and initialized automatically right after loading, and are deinitialized before the program unloading.

Initialization and Deinitialization of Local Variables

If a variable declared on a local level is not a static one, memory is allocated automatically for such a variable. Local variables, as well as global ones, are initialized automatically at the moment when the program execution meets their declaration. Thus the initialization order corresponds to the order of declaration.

Local variables are deinitialized at the end of the program block, in which they were declared, and in the order opposite to their declaration. A program block is a [compound operator](compound.md) that can be a part of selection operator [switch](switch.md), loop operator ([for](for.md), [while](while.md), [do-while](dowhile.md)), [a function body](function.md#function_body) or a part of the [if-else operator](if.md).

Local variables are initialized only at the moment when the program execution meets the variable declaration. If during the program execution the block, in which the variable is declared, was not executed, such a variable is not initialized.

Initialization and Deinitialization of Objects Placed

A special case is that with [object pointers](object_pointers.md), because declaration of a pointer does not entail initialization of a corresponding objects. Dynamically placed objects are initialized only at the moment when the class sample is created by the [new operator](newoperator.md). Initialization of objects presupposes call of a constructor of a corresponding class. If there is no corresponding constructor in the class, its members of a [simple type](types.md#base_types) will not be automatically initialized; members of types [string](stringconst.md), [dynamic array](dynamic_array.md) and [complex object](types.md#complex_types) will be automatically initialized.

Pointers can be declared on a local or global level; and they can be initialized by the empty value of [NULL](void.md) or by the value of the pointer of the same or [inherited](inheritance.md) type. If the new operator is called for a pointer declared on a local level, the delete operator for this pointer must be performed before exiting the level. Otherwise the pointer will be lost and the explicit deletion of the object will fail.

All objects created by the expression of object\_pointer=new Class\_name, must be then deleted by the delete(object\_pointer) operator. If for some reasons such a variable is not deleted by the [delete operator](deleteoperator.md) when the program is completed, the corresponding entry will appear in the "Experts" journal. One can declare several variables and assign a pointer of one object to all of them.

If a dynamically created object has a constructor, this constructor will be called at the moment of the new operator execution. If an object has a destructor, it will be called during the execution of the delete operator.

Thus dynamically placed objects are created only at the moment when the corresponding new operator is invoked, and are assuredly deleted either by the delete operator or automatically by the executing system of MQL5 during the program unloading. The order of declaration of pointers of dynamically created object doesn't influence the order of their initialization. The order of initialization and deinitialization is fully controlled by the programmer.

Dynamic memory allocation in MQL5

When working with dynamic arrays, released memory is immediately returned back to the operating system.

When working with dynamic class objects using the [new operator](newoperator.md), first memory is requested from the class memory pool the memory manager is working with. If there is not enough memory in the pool, memory is requested from the operating system. When deleting the dynamic object using the [delete operator](deleteoperator.md), released memory is immediately returned back to the class memory pool.

Memory manager releases memory back to the operating system immediately after exiting the following event handling functions: [OnInit()](event_fire.md#init), [OnDeinit()](event_fire.md#deinit), [OnStart()](event_fire.md#start), [OnTick()](event_fire.md#newtick), [OnCalculate()](event_fire.md#calculate), [OnTimer()](event_fire.md#timer), [OnTrade()](event_fire.md#trade), [OnTester()](event_fire.md#tester), [OnTesterInit()](event_fire.md#testerinit), [OnTesterPass()](event_fire.md#testerpass), [OnTesterDeinit()](event_fire.md#testerdeinit), [OnChartEvent()](event_fire.md#chartevent), [OnBookEvent()](event_fire.md#bookevent).

Brief Characteristics of Variables

The main information about the order of creation, deletion, about calls of constructors and destructors is given in the below table.

|  | Global automatic variable | Local automatic variable | Dynamically created object |
| --- | --- | --- | --- |
| Initialization | right after a mql5 program is loaded | when the code line where it is declared is reached during execution | at the execution of the new operator |
| Initialization order | in the order of declaration | in the order of declaration | irrespective of the order of declaration |
| Deinitialization | before a mql5 program is unloaded | when execution exits the declaration block | when the delete operator is executed or before a mql5 program is unloaded |
| Deinitialization order | in the order opposite to the initialization order | in the order opposite to the initialization order | irrespective of the initialization order |
| Constructor call | at mql5 program loading | at initialization | at the execution of the new operator |
| Destructor call | at mql5 program unloading | when exiting the block where the variable was initialized | at the execution of the delete operator |
| Error logs | log message in the "Experts" journal about the attempt to delete an automatically created object | log message in the "Experts" journal about the attempt to delete an automatically created object | log message in the "Experts" journal about undeleted dynamically created objects at the unload of a mql5 program |

See also

[Data Types](types.md), [Encapsulation and Extensibility of Types](incapsulation.md),[Initialization of Variables](initialization.md), [Visibility Scope and Lifetime of Variables](variable_scope.md)