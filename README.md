# BrightDoor for Grok Bot and Cursor

[BrightDoor](https://brightdoor.ai) builds and runs websites for owner-run businesses. This plugin connects [Grok Bot](https://x.ai/bot) or Cursor to your BrightDoor business, so you can ask about your leads and stats and suggest changes to your site.

## What it can do

- **Read:** your business profile, published pages, approved answers, reviews, and posts.
- **Stats:** visitors, Google and Bing search, rankings, whether AI assistants name you, speed, uptime, form stats, and your monthly report.
- **Leads:** list and open leads; move a lead, set a follow-up, or add a note, each with Undo.
- **Suggest:** changes to your hours, services, wording, and questions, and new posts. Every suggestion waits for your OK in BrightDoor. Nothing publishes on its own.

It can never publish, approve, pay, or delete. What it can do depends on the switches you pick when you sign in, and you can change them or turn it off any time under Settings, Connected apps.

## How it connects

- `mcp.json` points at BrightDoor's MCP server, `https://app.brightdoor.ai/api/mcp`.
- You sign in with your BrightDoor account. There is no key in this plugin.
- `skills/brightdoor/SKILL.md` tells the agent how to use the tools and the rules it must follow.

## Try it

Copy this folder to `~/.cursor/plugins/local/brightdoor`, then reload Cursor or Grok Bot.

## Help

Questions go to BrightDoor support from your account, or see [brightdoor.ai](https://brightdoor.ai).

© BrightDoor AI LLC
