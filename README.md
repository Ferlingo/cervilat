# Cervilat

Landing page for [cervilat.com](https://cervilat.com) — a small halal smoked-sausage factory in Saudi Arabia.

Static HTML. Publish directory is the repo root.

```bash
npx netlify deploy --prod --dir .
```

Custom domain: `cervilat.com` (DNS at Cloudflare). Point the Netlify site at that domain, then add the Netlify load-balancer records in Cloudflare.
