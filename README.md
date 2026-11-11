# BD4 for your AI assistant

Work your BD4 relationships from the AI assistant you already use: see who to
reach out to today, get an outreach brief, draft a message in your own voice,
and log what happened.

You need a BD4 account at [app.bd4pros.com](https://app.bd4pros.com).

## Install

**Claude (web, desktop or mobile):** open **Customize**, choose
**Add > Add marketplace**, and enter `TractionBD/bd4-plugins`. Then install
**bd4** and sign in to BD4 when asked.

**Claude Code:**

```
/plugin marketplace add TractionBD/bd4-plugins
/plugin install bd4@bd4
```

**Codex CLI:**

```
codex plugin marketplace add TractionBD/bd4-plugins
```

Then start `codex`, open `/plugins` and install **bd4**.

**GitHub Copilot CLI:**

```
copilot plugin marketplace add TractionBD/bd4-plugins
copilot plugin install bd4@bd4
```

**Cursor:** until BD4 is listed in the Cursor Marketplace, add the BD4 server
under **Cursor Settings > MCP** with the URL `https://mcp.bd4pros.com/mcp`.
That gives Cursor the BD4 tools; the playbooks below come with the plugin.

**ChatGPT and any other assistant that supports MCP:** add a custom connector
with the URL `https://mcp.bd4pros.com/mcp`. In ChatGPT, full access (including
logging and sending) needs a Business, Enterprise or Edu workspace; Pro
accounts get read-only access in developer mode.

## What you get

- `/bd4:today`: who BD4 suggests you reach out to today
- `/bd4:brief <name>`: the outreach brief for a person
- `/bd4:log <who and what happened>`: log a call, meeting or note

Commands are available in Claude and Cursor. In every assistant, the plugin
also brings BD4's playbooks for your daily list, next best actions, outreach
briefs, drafting in your voice, logging interactions, reminders and your
hotlist. Your assistant always asks before it sends an email or changes a
contact.

## What's in this repo

| Path | Read by |
| --- | --- |
| `plugins/bd4/skills/`, `plugins/bd4/commands/` | Every assistant (shared) |
| `plugins/bd4/.claude-plugin/plugin.json`, `plugins/bd4/.mcp.json` | Claude |
| `plugins/bd4/plugin.json`, `plugins/bd4/mcp.json` | Codex, ChatGPT, GitHub Copilot ([Agent Plugins](https://agent-plugins.org) format) |
| `plugins/bd4/.cursor-plugin/plugin.json` | Cursor |
| `.claude-plugin/marketplace.json` | Claude, GitHub Copilot |
| `.agents/plugins/marketplace.json` | Codex, ChatGPT |
| `.cursor-plugin/marketplace.json` | Cursor |

Support: support@bd4pros.com
