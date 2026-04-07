---
name: "MQL5 Reference Documentation Navigation"
description: "A skill to navigate the local MQL5 markdown documentation to find precise language references, API signatures, parameters, and behaviors."
---

# MQL5 Documentation Navigation Skill

This skill provides instructions for searching and retrieving precise technical information from the local MQL5 reference documentation. The goal is to **always ground answers in the actual documentation files**, avoiding hallucination or reliance on training data for API signatures, parameter types, return values, and behavioral notes.

## 1. Documentation Location

The MQL5 documentation is available locally in markdown format inside the `docs/` directory, relative to this SKILL.md file:

```
<this_skill_directory>/docs/
```

Where `<this_skill_directory>` is the directory containing this SKILL.md file (resolve it to an absolute path at runtime).

This directory is referred to as `<docs>` throughout this document.

All documentation files reside in a **single flat directory** — there are no subdirectories. Files are a mix of:
- **Category/index pages** (e.g., `chart_operations.md`, `trading.md`, `basis.md`) — listing functions/topics with links.
- **Function/detail pages** (e.g., `ordersend.md`, `chartindicatoradd.md`) — containing signatures, parameters, return values, notes, and examples.
- **Master indices** — `function_indices.md` (all functions A-Z) and `constant_indices.md` (all constants/enums A-Z).

## 2. Navigation Strategies

Use the strategy that best matches what you already know about the query. Start with the most direct approach and fall back to more exploratory ones.

### Strategy A: Direct Function Lookup (You know or suspect the function name)

This is the **fastest path**. Use it when you know or can guess the function name (e.g., user asks about `OrderSend`, `iMA`, `ArrayResize`).

1. **Try direct file access first.** Function page filenames are the lowercase function name + `.md`. Use `view_file` on:
   `<docs>/<function_name_lowercase>.md`
   Example: For `OrderSend` → `<docs>/ordersend.md`

2. **If the file doesn't exist**, search the master function index:
   Use `grep_search` on `<docs>/function_indices.md` with the function name as query.
   This file is an alphabetical table of **every MQL5 function** with columns: Function | Action | Section. The function name links to its documentation file.

3. **Read the function page** with `view_file` to extract the full signature, parameters, return value, and notes.

### Strategy B: Direct Constant/Enum Lookup (You know the enum or constant name)

When the query involves an enum (e.g., `ENUM_TIMEFRAMES`, `ENUM_ORDER_TYPE`) or a constant:

1. Use `grep_search` on `<docs>/constant_indices.md` with the enum/constant name as query.
   This file lists **every MQL5 constant and enum** alphabetically with links to their definition pages.

2. Alternatively, use `grep_search` across the entire `<docs>/` directory to find which file defines or references the enum/constant.

3. Read the relevant file with `view_file`.

### Strategy C: Topic-Based Navigation (You don't know the exact function name)

When the user describes a task or concept (e.g., "How do I place a trade?" or "How do I draw on the chart?"):

1. **Start from the Table of Contents.** Read `<docs>/000_contents.md` with `view_file`.
   This lists all major documentation sections with links to their category pages. Example entries:
   - `[Chart Operations](chart_operations.md)` — for chart manipulation
   - `[Trade Functions](trading.md)` — for trading operations
   - `[Technical Indicators](indicators.md)` — for built-in indicators
   - `[Language Basics](basis.md)` — for syntax, types, operators, OOP
   - `[Constants, Enumerations and Structures](constants.md)` — for all enums/structs

2. **Read the relevant category page** with `view_file`. Category pages contain:
   - A table mapping each function name to a short description of its action
   - Links to the individual function detail pages
   - Sometimes introductory notes with important behavioral context (e.g., async behavior of chart functions)

3. **For deeply nested topics**, category pages may link to sub-category pages. Follow the links. Examples:
   - `basis.md` → `types.md` → `integertypes.md` (for integer type details)
   - `constants.md` → `chartconstants.md` → `enum_chart_property.md` (for chart property enums)
   - `standardlibrary.md` → category-specific class pages

4. **Read the specific function/topic page** with `view_file` to get the precise details.

### Strategy D: Broad Keyword Search (Exploring or unclear topic)

When you cannot determine the relevant category or function:

1. Use `grep_search` on the `<docs>/` directory with a relevant keyword.
   - Use `CaseInsensitive: true` for broader matching.
   - Use `MatchPerLine: true` to see context around matches.
   - Results will show which files contain the term, helping you identify the right page.

2. Once a relevant file is identified, use `view_file` to read it fully.

## 3. Understanding Document Structure

Each documentation page follows a consistent structure:

- **Breadcrumb navigation** at the top: `[MQL5 Reference](index.md) / [Section](section.md) / Page Title`
  → Use this to understand the page's place in the hierarchy and navigate to parent sections.

- **Function signature** in a code block (for function pages):
  ```
  return_type  FunctionName(
     type1  param1,    // description
     type2  param2     // description
     );
  ```

- **Parameters section**: Each parameter listed with `[in]`, `[out]`, or `[in][out]` markers and a description.

- **Return Value section**: Describes what the function returns and error conditions.

- **Note section**: Contains critical behavioral details — async behavior, edge cases, thread-safety, platform-specific notes. **Pay special attention to this section.**

- **Example section**: Code block with a complete usage example.

- **See Also section**: Links to related functions. **Use this to discover related functionality** the user might need. Always check these links when providing comprehensive answers.

## 4. Formulating Answers

When answering MQL5 queries based on this documentation:

### Accuracy Rules
- **ALWAYS read the actual documentation file** before providing API details. Never rely on training data alone for function signatures, parameter types, or return values.
- **If you cannot find the information** in the documentation, explicitly tell the user that the specific topic was not found in the local reference, rather than guessing.
- **Quote the exact signature** from the documentation. Do not paraphrase parameter types or orders.

### Content Guidelines
- **Provide the full function signature** with parameter types and descriptions.
- **Highlight behavioral notes**: Async behaviors (e.g., `ChartSetInteger` requires `ChartRedraw()`), error codes, return value meanings.
- **Include the "See Also" references** to guide the user to related functions they may need.
- **Provide clean, well-commented code examples** using the patterns from the documentation examples.
- **When dealing with enums**, always list the relevant enum values and their meanings from the documentation.

### Common Pitfalls to Address
- Many chart functions are **asynchronous** — always mention when `ChartRedraw()` may be needed.
- Trade functions require the **"Allow live trading"** checkbox to be enabled.
- Indicator handles must be **created before use** and often need to be **released** with `IndicatorRelease()`.
- Array indexing direction matters in timeseries — mention `ArraySetAsSeries()` when relevant.

## 5. Example Workflows

### Example 1: "How do I send a market order?"

1. You recognize this is about trading → **Strategy A**: try `<docs>/ordersend.md` directly.
2. Read the file to get the `OrderSend()` signature and parameters.
3. Notice it requires an `MqlTradeRequest` struct → search for `mqltraderequest.md`.
4. Check the "See Also" section for `OrderSendAsync()`, `OrderCheck()`.
5. Provide the signature, explain the request structure, and give a complete example.

### Example 2: "How do I add an indicator to a chart programmatically?"

1. Not sure of the exact function → **Strategy C**: read `<docs>/000_contents.md`.
2. Find `[Chart Operations](chart_operations.md)` in the table of contents.
3. Read `<docs>/chart_operations.md` → find `ChartIndicatorAdd` in the function table.
4. Read `<docs>/chartindicatoradd.md` for the full signature, parameters, and example.
5. Note from the docs: indicator and chart must share the same symbol and timeframe.

### Example 3: "What are the possible order types?"

1. This is about an enum → **Strategy B**: search `<docs>/constant_indices.md` for `ORDER_TYPE`.
2. Find the link to the enum definition page.
3. Read the page to list all `ENUM_ORDER_TYPE` values and their descriptions.

### Example 4: "How do I use the for loop in MQL5?"

1. This is about language syntax → **Strategy C**: read `<docs>/000_contents.md`.
2. Find `[Language Basics](basis.md)`.
3. Read `<docs>/basis.md` → find link to `[Operators](operators.md)`.
4. Navigate to the `for` loop page from there.
