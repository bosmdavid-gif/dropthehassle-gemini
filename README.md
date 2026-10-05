# DropTheHassle for Gemini CLI

[DropTheHassle](https://dropthehassle.com) lets your AI put the site it built online on a free HTTPS link, check whether a domain is free, and point the human at buying .com / .org / .net for €19 / $19 a year with no DNS.

The agent never spends money. Buying a domain is always the human's own click. Unclaimed sites stay available until the human claims and keeps them with their email.

## Install

```
gemini extensions install https://github.com/bosmdavid-gif/dropthehassle-gemini
```

Then ask Gemini CLI to put your site online or to check if a domain is free.

## What it does

- Connects to the hosted MCP at `https://dropthehassle.com/mcp` (streamable HTTP).
- Loads short agent instructions (`GEMINI.md`) so Gemini uses `deploy_site`, `search_domain`, and related tools correctly.
- Free tools with no auth: `search_domain`, `deploy_site`, `whoami`, `choose_link`, `design_inspiration`.
- Account tools accept `Authorization: Bearer dth_...` when you have a DropTheHassle key.
- Optional local stdio alternative: `npx -y dropthehassle-mcp` (MIT).

## Gallery / topics

Public repo with root `gemini-extension.json` and the `gemini-cli-extension` topic, as required by the [Gemini CLI extensions gallery](https://geminicli.com/extensions/).

Site: https://dropthehassle.com · Privacy: https://dropthehassle.com/privacy · Terms: https://dropthehassle.com/terms

License: MIT
