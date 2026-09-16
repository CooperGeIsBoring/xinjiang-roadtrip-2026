# Xinjiang Roadtrip Itinerary

Single-file offline itinerary page for a 2026 National Day Xinjiang road trip.

## Files

- `public/index.html`: the public itinerary page.
- `wrangler.jsonc`: Cloudflare Workers Static Assets config.
- `package.json`: deploy helper scripts.

## Deploy

Use Cloudflare Workers, connect this GitHub repository, and deploy with:

```bash
npm install
npm run deploy
```

The published site serves `public/index.html`.
