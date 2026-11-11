# BD4 for your AI assistant

BD4 is a relationship CRM for professionals who grow their business through
people they know. This plugin lets you work your BD4 relationships from your AI assistant:
see who BD4 suggests you reach out to today, get an outreach brief for a person,
draft a message in your own voice, and log calls, meetings and notes.

You need a BD4 account. Sign up at [bd4pros.com](https://www.bd4pros.com).

## What's included

**Commands** (Claude and Cursor)

- `/bd4:today`: who BD4 suggests you reach out to today
- `/bd4:brief <name>`: the outreach brief for a person
- `/bd4:log <who and what happened>`: log a call, meeting or note

**Skills** that teach your assistant how to use BD4 the way the app does:

- **daily-five**: work your day in order: today's list, brief, draft, then send or hand off
- **next-best-action**: BD4's ranked suggestions for one contact
- **outreach-brief**: get and adjust the brief before you reach out
- **draft-in-my-voice**: drafts with BD4, using your voice profile and history
- **log-interaction**: record, fix or remove calls, meetings and notes
- **manage-lifecycle**: snooze, reminders, tags, and adding or deleting contacts
- **hotlist-review**: review your hotlist and decide who to contact next

## What it connects to and what it sends

The plugin contains no code. It holds the commands and skills above, which are
text instructions for your assistant, and one connector: the BD4 MCP server at
`https://mcp.bd4pros.com/mcp`.

- **Sign-in.** The first time your assistant uses a BD4 tool, you sign in to BD4 on a
  BD4 page and approve access (OAuth 2.1 with PKCE). To disconnect, uninstall
  the plugin or remove the BD4 connector in your assistant.
- **What your assistant can reach.** Your BD4 data, through the BD4 server's tools:
  your Today list, contacts, outreach briefs, drafts, interactions, reminders,
  tags and hotlist. BD4 only acts on your own account.
- **What gets sent.** Your requests go from your assistant to the BD4 server, and the
  results come back into your conversation. The plugin sends nothing to
  any other service and stores nothing itself.
- **Your control.** Your assistant shows you every draft and asks before it sends an
  email, asks before it changes a contact's tags, and confirms before it
  deletes a contact or a logged interaction.

## Support

Questions or problems: support@bd4pros.com. Privacy policy:
[bd4pros.com/privacy-policy](https://www.bd4pros.com/privacy-policy).
