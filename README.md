![Build](https://img.shields.io/github/actions/workflow/status/pkronstrom/nest-driven-development/ci.yml?style=flat-square) ![License](https://img.shields.io/github/license/pkronstrom/nest-driven-development?style=flat-square)

![NDD banner](docs/ndd_banner.png)

# Nest-Driven Development
**The minimum vibable workflow — for developers who let Claude Code do the flying.**

---

You told Claude to handle it. Now you're watching it ask permission for every file touch, losing context between sessions, and wondering if your todos are scattered across six different windows.

NDD is three CLI tools that turn Claude Code into a workflow you can actually walk away from. Approve from your phone. Rewire hooks without restarting. Keep tasks alive across agents and sessions. The flock handles it while you're in the hammock.

---

## The Flock

### [owl-afk](https://github.com/pkronstrom/owl-afk) — Remote Approvals

Your agents keep working while you step away. owl forwards Claude's permission requests to Telegram so you can approve, deny, or set rules from anywhere — no laptop required.

- **Stay in control from anywhere**: Approve or deny tool calls from your phone with one tap
- **Automate the obvious**: Pattern rules silently approve trusted commands so you only see what matters
- **Handle chains cleanly**: Complex bash pipelines broken into individual, approvable steps

### [hawk-hooks](https://github.com/pkronstrom/hawk-hooks) — Hooks On The Fly

Change how Claude behaves without killing your session. hawk manages hooks, prompts, and skills as modular scripts that hot-reload the moment you drop them in.

- **Zero-restart iteration**: Toggle, add, or edit hooks mid-session and see them take effect immediately
- **Write hooks in anything**: Python, JS, Shell, TypeScript — hawk discovers and runs them all
- **One sync, every AI**: Push your prompts and agent files to Claude, Codex, Gemini, and more from one place

### [dodo-tasks](https://github.com/pkronstrom/dodo-tasks) — Todos That Refuse to Go Extinct

Tasks you capture in the middle of a thought actually survive to the project they belong to. dodo routes ideas to the right repo, tracks dependencies across agents, and syncs wherever you keep your notes.

- **Capture without context-switching**: Quick-add a task and dodo figures out which project it belongs to
- **Coordinate multi-agent work**: Graph-based dependency tracking so agents don't step on each other
- **Live where your notes live**: SQLite, Markdown, or Obsidian — your workflow, not ours

---

## Quick Start

```bash
uv tool install git+https://github.com/pkronstrom/owl-afk    # approve from anywhere
uv tool install git+https://github.com/pkronstrom/hawk-hooks # hooks without restarts
uv tool install git+https://github.com/pkronstrom/dodo-tasks # tasks that don't die
```

Each tool is independent — grab one, grab all three.

---

## Why NDD?

Most Claude Code workflow problems come from the same gap: the AI is autonomous, but your tooling isn't built for it. You need approval flows that work when you're not at the keyboard. You need hooks you can change without losing your session. You need tasks that survive the chaos of multi-agent runs.

NDD closes that gap with small, composable tools that stay out of your way until you need them.

*TDD? Try NDD.*

---

## License

MIT — see individual repositories for details.
