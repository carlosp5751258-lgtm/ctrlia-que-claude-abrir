# Which Claude should I open? Claude Code, Desktop, Cowork, claude.ai and the web

🇪🇸 [Leer en español](README.md)

The Spanish version is in the repository root and in [README.md](README.md); the English files are in `en/`.

A table to decide in 30 seconds which Claude product to open: Claude Code in the terminal, the Claude Desktop app (Code
tab), Cowork, the claude.ai chat and Claude Code on the web. For each one: what it's for, where the work runs, what to
install, which systems it runs on and which plan includes it. Plus the decision tree and what each plan includes.

Full page: [ctrlia.dev (EN)](https://ctrlia.dev/en/recetas/que-claude-abrir.html) ·
[ctrlia.dev (ES)](https://ctrlia.dev/recetas/que-claude-abrir.html)

## What's included

- `en/tabla.md`: comparison table, plans (official prices as of 1 Nov 2026) and decision tree, in English.
- `tabla.md` (root): the same in Spanish.

## How to use it

Read it on GitHub or copy it into your team's docs. To find out which account and plan you use Claude Code with:

```bash
claude auth status   # authMethod (claude.ai or API) and subscriptionType
```

It's a **documentary** comparison (official Anthropic sources, 1 Nov 2026), not a performance test. Prices change:
check them at https://claude.com/pricing before paying.

## Tested

With Claude Code **2.1.316** on Linux: `claude auth status` and the `--desktop` and `--cloud` options in `claude --help`.
Cowork, the desktop app on Windows or macOS and an end-to-end cloud session were not tested.

## License

MIT. Copyright (c) 2026 Ctrl+IA (Carlos P.). See [LICENSE](LICENSE).
