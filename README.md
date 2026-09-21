# NOX — Standalone

A free-tier, no-paid-API build of the NOX interface. Runs as a single static `index.html` — no backend, no server, no build step.

## What's real in this build

- **AI Engine** — calls Groq's free-tier API (Llama 3.3 70B) directly from your browser. Add a free key via the Settings button in the sidebar (get one at console.groq.com/keys, no card required). The key is stored only in your browser's localStorage.
- **Crypto** — live BTC/ETH/SOL/XRP/DOGE/ADA prices pulled directly from Crypto.com's public market-data API. No key, no auth, refreshes every 20 seconds.
- **Memory** — directive history persists in localStorage across sessions on this device.

## What's honestly not connected

- **Hardware Link** — no physical lab hardware reports to this yet.
- **Git / code execution** — a static page can't run commands or touch a repo. That needs a real dev runtime (Claude Code, a CI pipeline, etc.), not a webpage.

## Running it

Just open `index.html` in a browser, or enable GitHub Pages on this repo (Settings → Pages → deploy from `main` / root) for a public URL.

Built with help from Claude.
