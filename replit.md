# Project Overview

A static website project served via a Node.js HTTP server.

## Architecture

- **Frontend**: Single `index.html` file with all styles inline (Tailwind CSS via CDN)
- **Server**: `serve.mjs` — a minimal Node.js HTTP server that serves static files from the project root

## Running the Project

The server runs on port 5000 at `0.0.0.0`:

```
node serve.mjs
```

## Project Structure

- `index.html` — Main website file
- `serve.mjs` — Static file server (port 5000)
- `brand_assets/` — Logo, color guides, style assets
- `images/` — Image assets
- `videos/` — Video assets
- `structure/` — Additional structural files
- `CLAUDE.md` — Frontend design rules and workflow guidelines

## Deployment

Configured for autoscale deployment running `node serve.mjs`.
