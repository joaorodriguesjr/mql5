# MQL5 Reference Documentation

Complete MQL5 language reference in Markdown format, with an AI navigation skill for precise documentation lookup.

## About

This repository contains the official **MQL5** (MetaQuotes Language 5) reference documentation converted from CHM to Markdown, enabling offline access and AI tool integration. MQL5 is the language used to develop automation programs on the **MetaTrader 5** platform, including:

- **Expert Advisors** — automated trading robots
- **Custom Indicators** — personalized technical analysis
- **Scripts** — one-time operation execution
- **Services** — background processes without chart binding

## Repository Structure

```
mql5/
├── docs/              # MQL5 documentation in Markdown (~4500 files)
│   ├── index.md                 # Main table of contents
│   ├── function_indices.md      # A-Z index of all functions
│   ├── constant_indices.md      # A-Z index of all constants and enums
│   └── ...                      # Function, class, and example pages
├── include/           # MQL5 Standard Library (source code)
│   ├── Trade/                   # Trading classes (CTrade, CPositionInfo, etc.)
│   ├── Indicators/              # Technical indicator classes
│   └── ...                      # Other Object-Oriented implementations
├── SKILL.md           # AI navigation skill
└── README.md
```

## Documentation

The `docs/` directory contains the complete language reference, organized in a flat directory with:

- **Function pages** (e.g., `ordersend.md`, `chartindicatoradd.md`) — signatures, parameters, return values, and examples
- **Category pages** (e.g., `trading.md`, `chart_operations.md`) — function indexes grouped by topic
- **General indexes** — `function_indices.md` and `constant_indices.md` for alphabetical lookup

### Entry Points

| File | Description |
|------|-------------|
| `index.md` | Table of contents with links to all sections |
| `function_indices.md` | Alphabetical index of all MQL5 functions |
| `constant_indices.md` | Alphabetical index of all constants and enums |

## Standard Library Source

The `include/` directory contains the official **MQL5 Standard Library** source code (`.mqh` files). This provides the implementation layer for developers who prefer Object-Oriented Programming (OOP) over procedural calls.

> [!NOTE]
> While `include/` contains the source code for high-level classes (like `CTrade`), the **built-in language functions** (like `OrderSend()` or `iRSI()`) and constants are part of the terminal core and their source code is not public. Documentation for these native features is exclusively available in the `docs/` folder.

## AI Navigation Skill

The `SKILL.md` file provides instructions for AI assistants to navigate the documentation accurately, defining:

- **4 search strategies** — direct lookup, constants/enums, topic-based navigation, and keyword search
- **Accuracy rules** — answers always grounded in actual documentation files, no hallucination
- **Example workflows** — sending orders, adding indicators, querying enums

## License

The MQL5 documentation is property of [MetaQuotes Ltd](https://www.metaquotes.net/). This repository serves as a local reference for study and development purposes.
