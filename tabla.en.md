# Which Claude should I open? Table and decision tree

Official Anthropic data as of 1 Nov 2026. Full page: https://ctrlia.dev/en/recetas/que-claude-abrir.html

## Comparison table

| | Claude Code (terminal) | Claude Desktop app (Code tab) | Cowork | claude.ai chat | Claude Code on the web |
| --- | --- | --- | --- | --- | --- |
| What it's for | Agentic coding, automating with `claude -p` | The same with visual diffs, preview and parallel sessions | Knowledge work without a terminal: documents, research, spreadsheets | Chat, search, create files and Artifacts | Long coding tasks that keep going even if you close your laptop |
| Where the work runs | Your machine | Your machine (or SSH, Cloud or WSL environments) | Anthropic's servers, in an isolated environment | Anthropic's servers | Cloud virtual machine run by Anthropic |
| What to install | `claude` (native installer) | The desktop app (bundles the engine) | Nothing extra: the same app, web or mobile | Nothing (web) or the app | Nothing; connect GitHub |
| Systems | macOS, Linux, WSL, Windows | macOS, Windows x64 and ARM64, Linux in beta (Ubuntu and Debian) | Desktop, web and mobile | Web, desktop and mobile | Browser and mobile app |
| Plan | Pro, Max, Ultra, Team, Enterprise or API key | Paid subscription | Pro, Max, Ultra, Team, Enterprise | Free and all | Pro, Max, Ultra, Team; Enterprise with premium seat |

## What each plan includes (official data, 1 Nov 2026)

Prices from [claude.com/pricing](https://claude.com/pricing) as of 1 Nov 2026; check them there before paying.

| Plan | Price | What it includes for coding |
| --- | --- | --- |
| Free | $0 | claude.ai chat only; no Claude Code |
| Pro | $20/month ($17/month billed annually) | Claude Code in terminal, IDE, desktop app, web and mobile, Remote Control, Dispatch, cloud sessions and Cowork |
| Max | $100/month | The same Claude Code features as Pro, with 5 times its usage allowance |
| Ultra | $200/month | The same features; 10 times weekly and no 5-hour limit on verified accounts |
| Team | Standard seat $20/month billed annually or $25 monthly; premium $100 or $125 | Claude Code and Cowork; Remote Control and Channels enabled by an admin; Code Review and analytics dashboard; no Dispatch or computer use |
| Enterprise | $20 per seat/month billed annually, 20 seats minimum, plus usage at API rates | Cloud sessions only with a premium seat or Chat + Claude Code |
| API key (Console) | Pay as you go | CLI and IDE extensions only; no desktop app (except Claude Desktop on 3P), web, mobile or Remote Control |

Ultra is the new name for Max 20x, and Max for Max 5x; besides the usage allowance, the included API credits change. Limit details in [Is Claude Code free?](https://ctrlia.dev/en/recetas/claude-code-precio-gratis.html).

## When to use each one

Ask yourself in this order:

1. **Are you going to change code?** If not: chat (questions) or Cowork (documents, research, multi-step tasks without a terminal).
2. **Is the code on your PC and do you need your tools, local servers or MCP?** Then local Claude Code: terminal if you want every feature and automation; the app's Code tab if you prefer reviewing diffs visually and opening several sessions; VS Code or JetBrains if you don't want to leave your editor.
3. **Is the task long, on GitHub, and do you want to shut your laptop?** Claude Code on the web or `claude --cloud`.
4. **Leaving your desk halfway through a local task?** Remote Control from your phone ([step-by-step guide](https://ctrlia.dev/en/recetas/remote-control-movil.html)).

Combinations that work:

- Plan in the terminal with plan mode and execute in the cloud with `claude --cloud`.
- Start in the terminal and move to the app with `/desktop` to review the changes (requires a claude.ai subscription and works on macOS and Windows x64).
- Launch on the web from your phone and finish locally with `claude --teleport`.

Everything shares the same plan allowance, so more surfaces doesn't mean a higher limit. If you're coming from another tool, see the [Claude Code vs Codex vs Gemini vs Cursor](https://ctrlia.dev/en/recetas/claude-code-vs-codex-gemini-cursor.html) comparison; if you're just starting, the [Start here](https://ctrlia.dev/en/recetas/empieza-aqui.html) route.
