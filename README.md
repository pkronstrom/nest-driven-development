# Nest-Driven Development

![NDD banner](docs/ndd_banner.png)

**The minimum vibable workflow.**

Let the flock handle it. **owl** guards permissions from your hammock. **hawk** rewires hooks mid-flight. **dodo** refuses to let tasks go extinct. **goose** orchestrates multi-agent pipelines. **rook** enforces guardrails so agents stay disciplined. That's Nest-Driven Development — five CLI tools for vibe coding.

---

## The Flock

### [owl-afk](https://github.com/pkronstrom/owl-afk) — Remote Approvals

Approve Claude Code tool calls from your phone via Telegram. AFK but in control.

- **Hammock-ready**: Approve, deny, or add rules from anywhere
- **Pattern rules**: Auto-approve trusted commands (`Bash(git *)`, `Edit(*.py)`)
- **Smart chains**: Handle complex bash chains in one tap

### [hawk-hooks](https://github.com/pkronstrom/hawk-hooks) — Hooks On The Fly

Modular hooks manager for Claude Code. Change hooks without restarting.

- **Auto-discovery**: Drop scripts in, they just work
- **Prompt management**: Custom slash commands and skills
- **Multi-language**: Python, JS, Shell, TypeScript

### [dodo-tasks](https://github.com/pkronstrom/dodo-tasks) — Todos That Refuse to Go Extinct

Smart task tracking for you and your AI agents.

- **Catch flying ideas**: Quick capture, project-aware routing
- **Graph plugin**: Dependency tracking for multi-agent coordination
- **Flexible backends**: SQLite, Markdown, Obsidian

### [goose](https://github.com/pkronstrom/goose) — Pipeline-Driven Multi-Agent Toolkit

Compose LLM-powered workflows from reusable nodes.

- **Pipeline engine**: Define workflows as JSON graphs with conditional branches
- **15+ bundled pipelines**: Research, debate, code review, security audits
- **Multi-provider**: Claude, Codex, Gemini, Perplexity — auto-detects and falls back

### [rook-rules](https://github.com/pkronstrom/rook-rules) — Guardrails for AI Coding Agents

Keep agents disciplined across long sessions.

- **Warn, don't wall**: Soft guidance by default, hard blocks for dangerous actions
- **30+ built-in rules**: Safety, verification discipline, scope control, architecture enforcement
- **Zero-config formatting**: Auto-format after every file edit, no latency impact

---

## Why NDD?

**dodo** — Simple task tracking that scales. No complex tools for simple ideas. Smart repo detection routes todos to the right project automatically. Graph-based dependency tracking for multi-agent coordination. Clean core with AI formatting, Obsidian sync, and more via plugins.

**owl** — AFK permissions and notifications for multiple parallel Claude Code instances via Telegram. Handles concurrent requests and feels snappy. Smart pattern rules auto-approve trusted commands. Recognizes command chains, SSH wrappers, and sudo.

**hawk** — Fast on-the-fly hook toggling without restarting Claude. Quick-add and edit hooks in any language. Syncs prompt and agent files to Claude, Codex, Gemini, and more. Auto-discovery means drop a script in and it just works.

**goose** — Pipeline-driven multi-agent workflows. Define research, debate, code review, and security audit pipelines as composable JSON graphs. 15+ bundled pipelines work out of the box. Multi-provider support auto-detects Claude, Codex, Gemini, and Perplexity.

**rook** — Guardrails that close the feedback loop. Evaluates every tool call against configurable rules — warns on scope creep, blocks dangerous commands, enforces architecture plans, and auto-formats code. Fail-open design means it never breaks your session.

---

## Get Started

```bash
uv tool install git+https://github.com/pkronstrom/owl-afk      # The wise one
uv tool install git+https://github.com/pkronstrom/hawk-hooks   # The sharp one
uv tool install git+https://github.com/pkronstrom/dodo-tasks   # The stubborn one
uv tool install git+https://github.com/pkronstrom/goose        # The orchestrator
uv tool install git+https://github.com/pkronstrom/rook-rules   # The disciplined one
```

Or install the whole flock at once:

```bash
uv tool install git+https://github.com/pkronstrom/owl-afk \
  && uv tool install git+https://github.com/pkronstrom/hawk-hooks \
  && uv tool install git+https://github.com/pkronstrom/dodo-tasks \
  && uv tool install git+https://github.com/pkronstrom/goose \
  && uv tool install git+https://github.com/pkronstrom/rook-rules
```

---

*TDD? Try NDD.*
