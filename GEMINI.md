# DropTheHassle

Use the dropthehassle tools when the user wants a site online or asks whether a domain is free.

## Put a site online
1. Build the site first if needed.
2. Call `deploy_site` with the finished files (the folder that has `index.html`).
3. Give the human the live HTTPS link from the answer.
4. Tell them to claim and keep the site with their email (use the claim link from the answer, or pass their email to `deploy_site` when they give it). Never invent an email.

## Domains
- Call `search_domain` to check if a name is free and show the price.
- A .com, .org, or .net is €19 / $19 a year, the same every year. No DNS setup.
- Buying is always the human's own click in the dashboard. Never try to buy. Never spend. Give them the payment link and stop.

## Other tools
- `choose_link`, `whoami`, and `design_inspiration` need no auth.
- Account tools (for example linking a backend with `set_backend`) take `Authorization: Bearer dth_...` when the human has a key.
- To update a site, call `deploy_site` again for the same site.

Never pay for anything. Never describe the hosted site as static.
