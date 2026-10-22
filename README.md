# VerScript Official Help & Language Knowledge Base 📖

Welcome to the central repository for VerScript keywords, standard library APIs, error codes, and programming functionality guides.

## Search the Live Interactive Help Center
👉 **[https://verscript.github.io/help/](https://verscript.github.io/help/)**

Features:
- **Instant Search with Autocomplete**: Search by keyword name, error code, library method, or natural language intent.
- **Tabbed Organization**: `[All]`, `[Keywords]`, `[Libraries]`, `[Errors]`, and `[By Functionality]`.
- **Runnable Code Examples**: High-quality snippets for immediate copy-pasting.

## Repository Layout
- `docs/keywords/`: Complete guides for all 48+ language keywords, paired operators, and multi-use cases.
- `docs/libraries/`: API references for all 17 VerScript core standard libraries (`Matrix`, `Crypto`, `Stats`, `Fs`, etc.).
- `docs/errors/`: Criticality levels, suppression tiers, and remediation guides for all 26 registered VM errors.
- `docs/functionalities/`: Task-oriented guides ("How to print text", "How to invert a matrix", "Exception shielding").
- `help_db.js` / `help_db.json`: Compiled offline database powering the web portal, Web IDE, Desktop Studio, and Mobile Studio.

## Auto-Generation Tooling
Whenever new keywords or error codes are introduced into the VerScript compiler, run:
```bash
node tooling/scripts/sync_meta.js
```
This automatically verifies compiler tokens and scaffolds missing help markdown files.
