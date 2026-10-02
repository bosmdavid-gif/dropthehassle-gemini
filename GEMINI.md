# DropTheHassle

Use the dropthehassle tools when the user wants their site online ("put my site online", "make it live", "share a link").

- Build first if needed. Then call deploy_site with the finished files (the folder with index.html).
- Without an account, ask the user for their email and pass it as email. Never make one up.
- Give the user the live link and the claim link from the answer. The claim link keeps the site on their account.
- To update, call deploy_site again for the same site.
- Own domain: search_domain shows if a name is free and the price. A .com is €19 / $19 a year, the same every year. The user buys it in the dashboard. You never buy.
- Got a server part too? Keep it on AWS, Google Cloud, DigitalOcean or your own server, and your AI links it to your site in one step (set_backend, needs the user's account).
- Never buy anything without asking. When something costs money, give the user the payment link and let them pay.
