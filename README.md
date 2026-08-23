# iris-engine (experimental)

Hosted in-memory torrent-engine runner for https://iris.akeyo.io — opens a cloudflared
tunnel and publishes its signed URL on a p2p discovery floor so the browser can stream
Torrentio titles it cannot fetch itself (browser sandbox has no TCP/DHT).

**EXPERIMENTAL / AT-OWN-RISK.** Serving media from GitHub Actions violates GitHub's
Acceptable Use Policy. This runs OPT-IN, in-memory (no data at rest), rate-limited, and
short-lived. The 24/7 cron pool is disabled by default — dispatch manually to test.
See `server/RUNNER.md`.
