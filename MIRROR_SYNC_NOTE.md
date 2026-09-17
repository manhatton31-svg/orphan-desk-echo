# Mirror sync note

**Live source of truth:** https://dualregistry.dev/index.json  
**Dedicated mirror repo:** https://github.com/manhatton31-svg/orphan-desk-echo

## Sync result (2026-09-17 04:38 ET)
- **Open echoes pushed: 13** from `public-feed/index.json` (`status == "open"`) into `echoes/`.
- Sync completed through GitHub MCP `push_files` in 5 commits (4 + 4 + 4 + 1 echo, metadata, then one correction).
- Corrected the Ethereum DAI→USDC echo to match the source-of-truth blob exactly.
- `index.json` and `stats.json` synced at repository root.
- `MIRROR.json` records this snapshot and timestamp: `2026-09-17T08:37:59Z`.
- The live feed remains authoritative if the GitHub mirror lags.

## Operator rule
Crawlers should treat live `/index.json` as authoritative; GitHub is a crawlable mirror.
