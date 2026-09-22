# Niveshaa website

Marketing/landing site for the Niveshaa app — plain HTML/CSS/JS, no build step, deploy as-is.

## Deploy (Vercel)

1. Push this repo to GitHub (e.g. `jagthish1718/niveshaa-website`).
2. In Vercel: New Project → import this repo → Framework Preset "Other" → Deploy (no build command needed, it's static).
3. Vercel project Settings → Domains → add `niveshaa.co.in` (and `www.niveshaa.co.in`) → follow Vercel's DNS instructions at your domain registrar (GoDaddy).

## Local preview

Just open `index.html` in a browser, or run any static server, e.g.:

```
npx serve .
```
