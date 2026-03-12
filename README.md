# Self-Evolve Website

Static promo site for `www.self-evolve.club`.

## Local preview

From repo root:

```bash
cd website
python -m http.server 8080
```

Open `http://127.0.0.1:8080`.

## Live data

The site fetches leaderboard data directly from:

- `https://self-evolve.club/api/v1/stats/overview`
- `https://self-evolve.club/api/v1/stats/leaderboard?limit=20`

Make sure API CORS allows browser requests from your website origin.

## Deploy

Deploy the whole `website/` directory as a static site (Vercel/Netlify/Nginx/object storage).
