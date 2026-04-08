---
name: "MQL5 Reference Documentation Navigation"
description: "Navigate local MQL5 markdown docs to find language references, API signatures, parameters, and behaviors."
---

# MQL5 Documentation Navigation Skill

Always ground answers in actual documentation files. Never rely on training data for signatures, parameter types, or return values.

## 1. Documentation Location

All files are in a **single flat directory**: `<this_skill_directory>/docs/` (resolve to absolute path at runtime). Referred to as `<docs>`.

File types:
- **Index/category pages** (`chart_operations.md`, `trading.md`, `basis.md`) — list functions with links
- **Function/detail pages** (`ordersend.md`, `chartindicatoradd.md`) — signatures, params, return values, notes, examples
- **Master indices** — `function_indices.md` (all functions A-Z) and `constant_indices.md` (all constants/enums A-Z)

## 2. Navigation Strategies

### A: Direct Function Lookup
1. Try `<docs>/<function_lowercase>.md` directly (e.g., `OrderSend` → `ordersend.md`)
2. If not found, `grep_search` on `function_indices.md` for the function name
3. `view_file` the function page

### B: Enum/Constant Lookup
1. `grep_search` on `constant_indices.md` for the enum/constant name
2. Or `grep_search` across all `<docs>/` to find which file defines it
3. `view_file` the result

### C: Topic-Based Navigation
1. `view_file` `<docs>/index.md` (Table of Contents with all section links)
2. `view_file` the relevant category page (contains function table + links)
3. Follow sub-category links if needed; `view_file` the specific function page

### D: Broad Keyword Search
1. `grep_search` on `<docs>/` with `CaseInsensitive: true`, `MatchPerLine: true`
2. `view_file` the identified file

## 3. Document Structure

Each page has:
- **Breadcrumb** at top → use to navigate to parent sections
- **Signature** in a code block with typed parameters
- **Parameters**: `[in]`, `[out]`, `[in][out]` markers
- **Return Value**: return type and error conditions
- **Note**: critical behavioral details — async behavior, edge cases. **Always read this.**
- **See Also**: related functions — **always check when giving comprehensive answers**

## 4. Answering Rules

- **Always read the doc file** before stating any API detail
- **Quote the exact signature** — do not paraphrase parameter types or order
- If not found in docs, say so explicitly rather than guessing
- Include full signature, behavioral notes, enum values, and See Also references
- Provide code examples following the doc's patterns

## 5. Common Pitfalls

- Many chart functions are async — mention `ChartRedraw()` when needed
- Trade functions require "Allow live trading" enabled
- Indicator handles must be created before use and released with `IndicatorRelease()`
- Array indexing direction in timeseries — mention `ArraySetAsSeries()` when relevant
