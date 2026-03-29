# Nest-Driven Development

![NDD banner](docs/ndd_banner.png)

**The minimum vibable workflow.**

You're running three Claude Code instances, approving tool calls one by one, losing track of tasks across repos, and hoping the agent doesn't silently go off the rails. Sound familiar?

Let the flock handle it. **owl** guards permissions from your hammock. **hawk** rewires hooks mid-flight. **dodo** refuses to let tasks go extinct. **goose** orchestrates multi-agent pipelines. **rook** enforces guardrails so agents stay disciplined. That's Nest-Driven Development — five CLI tools for agentic coding.

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

### [goose](https://github.com/pkronstrom/goose-scripts) — Pipeline-Driven Multi-Agent Toolkit

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

## Get Started

```bash
uv tool install git+https://github.com/pkronstrom/owl-afk      # The wise one
uv tool install git+https://github.com/pkronstrom/hawk-hooks   # The sharp one
uv tool install git+https://github.com/pkronstrom/dodo-tasks   # The stubborn one
uv tool install git+https://github.com/pkronstrom/goose-scripts # The orchestrator
uv tool install git+https://github.com/pkronstrom/rook-rules   # The disciplined one
```

Then try it out:

```bash
dodo add "ship the new feature"   # Track a task
owl status                        # See your approval queue
hawk list                         # Check active hooks
```

Or install the whole flock at once:

```bash
uv tool install git+https://github.com/pkronstrom/owl-afk \
  && uv tool install git+https://github.com/pkronstrom/hawk-hooks \
  && uv tool install git+https://github.com/pkronstrom/dodo-tasks \
  && uv tool install git+https://github.com/pkronstrom/goose-scripts \
  && uv tool install git+https://github.com/pkronstrom/rook-rules
```

---

## License

MIT

---

*TDD? Try NDD.*
