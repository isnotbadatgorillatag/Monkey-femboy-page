# Monkey-femboy-page

A small Cloudflare Workers static site for the fictional/satirical Daily Primate article about a Minecraft-playing monkey.

## Deploy

Install Wrangler, authenticate with Cloudflare, then run:

```bash
npx wrangler login
npx wrangler deploy
```

The Worker serves the files in `public/` through the `ASSETS` binding.

## Important

The article is deliberately labeled **FICTION / SATIRE**. The institute, researchers, monkey study, and results are fictional and should not be presented as a real scientific report.
