# Agent Crafting Table

A collection of standalone, drop-in components for building personal AI ops agents with Claude Code and Cursor.

Each repo is a focused tool you can pick and pull into your own agent without taking the whole stack.

---

## Starter Kits

| Repo | Description |
|---|---|
| [claude-code-claw](https://github.com/Agent-Crafting-Table/claude-code-claw) | Full agent starter kit — Claude Code CLI, Docker, Discord, cron, memory, identity layer |
| [cursor-claw](https://github.com/Agent-Crafting-Table/cursor-claw) | Full agent starter kit — Cursor runtime edition |

---

## Discord Integration

| Repo | Description |
|---|---|
| [fleet-discord](https://github.com/Agent-Crafting-Table/fleet-discord) | Multi-session Claude Code fleet sharing one Discord bot — peer routing, busy isolation, self-respawn |
| [discord-reply-watchdog](https://github.com/Agent-Crafting-Table/discord-reply-watchdog) | Drop-in plugin that reminds the agent to reply if 90s pass without a `discord:reply` call |
| [discord-streaming](https://github.com/Agent-Crafting-Table/discord-streaming) | Discord plugin with Tier-2 progress streaming — `post_update` edits a working message, `reply` pings when done |

---

## Memory & Knowledge

| Repo | Description |
|---|---|
| [agent-knowledge-base](https://github.com/Agent-Crafting-Table/agent-knowledge-base) | SQLite FTS5 knowledge base CLI — `add/search/list/tags` for fast exact-fact retrieval |
| [agent-skills](https://github.com/Agent-Crafting-Table/agent-skills) | Skill library management — indexed markdown skills, invocation tracking, failure flagging |
| [auto-memory-extract](https://github.com/Agent-Crafting-Table/auto-memory-extract) | Automated memory consolidation — scans daily notes, extracts decisions and learnings, deduplicates into reference files |

---

## Scheduling & Autonomy

| Repo | Description |
|---|---|
| [cron-framework](https://github.com/Agent-Crafting-Table/cron-framework) | Subagent cron scheduler — schedule, score, auto-resolve |
| [evolution-loop](https://github.com/Agent-Crafting-Table/evolution-loop) | Closed-loop prompt refinement — detect failures, propose variants, human approves |
| [autonomous-dev-agents-system](https://github.com/Agent-Crafting-Table/autonomous-dev-agents-system) | Multi-agent pipeline for autonomous software development — PRD → TRD → code |

---

## Safety & Guards

| Repo | Description |
|---|---|
| [injection-scan](https://github.com/Agent-Crafting-Table/injection-scan) | Deterministic prompt injection scanner — 60+ patterns, exit codes 0/1/2 (clean/suspicious/blocked) |
| [activity-guard](https://github.com/Agent-Crafting-Table/activity-guard) | Rolling-window rate limiter — tracks git commits, pushes, API calls, Discord posts across sessions |

---

## Monitoring & Infra

| Repo | Description |
|---|---|
| [claude-code-session-monitor](https://github.com/Agent-Crafting-Table/claude-code-session-monitor) | Real-time web UI for monitoring multiple Claude Code sessions — streaming tmux panes via SSE |
| [mcp-self-reload](https://github.com/Agent-Crafting-Table/mcp-self-reload) | Zero-downtime code rolls for bun-based MCP plugins — inherited stdio, no connection drop |

---

> All components are MIT licensed and designed to work standalone or together.
> Mix and match what your agent needs.

