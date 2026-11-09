---
description: Get the outreach brief for a person
argument-hint: <person's name>
---

Prepare an outreach brief for: $ARGUMENTS

Find the person (from `get_today`, or `search_contacts` if they are not on
today's list). If several match, ask which one. Then follow the
outreach-brief skill: call `get_outreach_brief`, read it in short form, and
offer to draft the message.
