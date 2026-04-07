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
│   ├── 000_contents.md          # Main table of contents
│   ├── function_indices.md      # A-Z index of all functions
│   ├── constant_indices.md      # A-Z index of all constants and enums
│   └── ...                      # Function, class, and example pages
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
| `000_contents.md` | Table of contents with links to all sections |
| `function_indices.md` | Alphabetical index of all MQL5 functions |
| `constant_indices.md` | Alphabetical index of all constants and enums |

## AI Navigation Skill

The `SKILL.md` file provides instructions for AI assistants to navigate the documentation accurately, defining:

- **4 search strategies** — direct lookup, constants/enums, topic-based navigation, and keyword search
- **Accuracy rules** — answers always grounded in actual documentation files, no hallucination
- **Example workflows** — sending orders, adding indicators, querying enums

## License

The MQL5 documentation is property of [MetaQuotes Ltd](https://www.metaquotes.net/). This repository serves as a local reference for study and development purposes.
