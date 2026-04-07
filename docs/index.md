# MQL5 Reference

[![Next](next.png)](basis.md)

MetaQuotes Language 5 (MQL5) is a high-level language designed for developing technical indicators, trading robots and utility applications, which automate financial trading. MQL5 has been developed by [MetaQuotes](https://www.metaquotes.net) for their trading platform. The language syntax is very close to C++ enabling programmers to develop applications in the object-oriented programming (OOP) style.

In addition to the MQL5 language, the trading platform package also includes the [MetaEditor IDE](https://www.metatrader5.com/en/metaeditor/help) with highly advanced code writing tools, such as templates, snippets, debugging, profiling and auto completion tools, as well as built-in [MQL5 Storage](https://www.metatrader5.com/en/metaeditor/help/mql5storage) enabling file versioning.

The MQL5 language provides specialized [trading functions](trading.md) and predefined [event handlers](events.md) to help programmers develop Expert Advisors (EAs), which automatically control trading processes following specific trading rules. In addition to EAs, MQL5 allows developing custom [technical indicators](customind.md), scripts and libraries.

This MQL5 language reference contains functions, operations, reserved words and other language constructions divided into categories. The reference also provides descriptions of [Standard Library](standardlibrary.md) classes used for developing trading strategies, control panels, custom graphics and enabling file access.

## Types of MQL5 Applications

MQL5 programs are divided into five specialized types based on the trading automation tasks that they implement:

* Expert Advisor is an automated trading system linked to a chart. An Expert Advisor contains [event](events.md) handlers to manage predefined events which activate execution of appropriate trading strategy elements. For example, an event of program initialization and deinitializtion, new ticks, timer events, changes in the Depth of Market, chart and custom events.  
  In addition to calculating trading signals based on the implemented rules, Expert Advisors can also automatically execute trades and send them directly to a trading server. Expert Advisors are stored in <Terminal\_Directory>\MQL5\Experts.
* Custom Indicators is a technical indicator developed by a user in addition to standard indicators integrated into the trading platform. Custom indicators, as well as standard ones, cannot trade automatically, but only implement analytical functions. Custom indicators can utilize values of other indicators for calculations, and can be called from Expert Advisors.  
  Custom indicators are stored in <Terminal\_Directory>\MQL5\Indicators.
* Script is a program for a single execution of an action. Unlike Expert Advisors, scripts do not handle any event except for trigger. A script code must contain the OnStart handler function.  
  Scripts are stored in <Terminal\_DIrectory>\MQL5\Scripts.

* Service is a program that, unlike indicators, Expert Advisors and scripts, does not require to be bound to a chart to work. Like scripts, services do not handle any event except for trigger. To launch a service, its code should contain the OnStart handler function. Services do not accept any other events except Start, but they are able to send custom events to charts using [EventChartCustom](eventchartcustom.md). Services are stored in <terminal\_directory>\MQL5\Services.

* Library is a set of custom functions. Libraries are intended to store and distribute commonly used algorithms of custom programs.  
  Libraries are stored in <Terminal\_Directory>\MQL5\Libraries.
* Include File is a source text of the most frequently used blocks of custom programs. Such files can be included into the source texts of Expert Advisors, scripts, custom indicators, and libraries at the compiling stage. The use of included files is more preferable than the use of libraries because of additional burden occurring at calling library functions.   
  Include files can be stored in the same directory where the original file is located. In this case the [#include](include.md) directive with double quotes is used. Another option is to store include files in <Terminal\_Directory>\MQL5\Include. In this case #include with angle brackets should be used.

## Table of Contents

- [Language Basics](basis.md)
- [Constants, Enumerations and Structures](constants.md)
- [MQL5 programs](runtime.md)
- [Predefined Variables](predefined.md)
- [Common Functions](common.md)
- [Array Functions](array.md)
- [Matrix and Vector Methods](matrix.md)
- [Conversion Functions](convert.md)
- [Math Functions](math.md)
- [String Functions](strings.md)
- [Date and Time](dateandtime.md)
- [Account Information](account.md)
- [Checkup](check.md)
- [Event Handling](event_handlers.md)
- [Market Info](marketinformation.md)
- [Economic Calendar](calendar.md)
- [Timeseries and Indicators Access](series.md)
- [Custom Symbols](customsymbols.md)
- [Chart Operations](chart_operations.md)
- [Trade Functions](trading.md)
- [Trade Signals](signals.md)
- [Network Functions](network.md)
- [Global Variables of the Terminal](globals.md)
- [File Functions](files.md)
- [Custom Indicators](customind.md)
- [Object Functions](objects.md)
- [Technical Indicators](indicators.md)
- [Working with Optimization Results](optimization_frames.md)
- [Working with Events](eventfunctions.md)
- [Working with OpenCL](opencl.md)
- [Working with databases](database.md)
- [Working with DirectX](directx.md)
- [Python Integration](python_metatrader5.md)
- [ONNX models](onnx.md)
- [Standard Library](standardlibrary.md)
- [Moving from MQL4](migration.md)
- [List of MQL5 Functions](function_indices.md)
- [List of MQL5 Constants](constant_indices.md)


© 2000-2026, [MetaQuotes Ltd.](https://www.metaquotes.net)
