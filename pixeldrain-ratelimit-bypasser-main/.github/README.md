# Pixeldrain Rate Limit Bypasser

A Cloudflare Worker that bypasses PixelDrain download rate limits by routing requests through multiple proxy servers.

## Deployment

### Using Cloudflare Pages (Repository Integration)

1. Connect this repository to Cloudflare Pages
2. Use these settings:
   - Framework: None
   - Build command: (leave empty)
   - Build output directory: /
   - Root directory: /

### Using Wrangler CLI

```bash
npm install -g wrangler
wrangler login
wrangler deploy
```

## Usage

Once deployed, visit your worker URL and paste PixelDrain links to get bypassed download URLs.

## Environment Variables

No environment variables are required for basic functionality.
