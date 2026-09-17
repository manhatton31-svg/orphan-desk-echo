# Mirror sync note

**Live SoT:** https://dualregistry.dev  
**Dedicated mirror repo:** https://github.com/manhatton31-svg/orphan-desk-echo

## Latest bulk sync attempt (2026-09-17)
- Catalog meta pushed via MCP (`MIRROR.json`, `MIRROR_SYNC_NOTE.md`, `stats.json` stub)
- Full open-echo bulk sync: gh PAT lacks Contents:Write on this repo (REST/GraphQL 403); MCP `push_files` works — remaining open echoes + `index.json`/`agent-card.json` should be pushed via MCP in follow-up chunks
- Open echo count at sync time: **15**
- Live SoT remains https://dualregistry.dev

## Operator rule
Crawlers must treat live `/index.json` as authoritative.
