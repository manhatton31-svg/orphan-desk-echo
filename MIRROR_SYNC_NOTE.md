# Mirror sync note

**Live SoT:** https://dualregistry.dev  
**Dedicated mirror repo:** https://github.com/manhatton31-svg/orphan-desk-echo

## Sync result (2026-09-17)
- Meta synced via GitHub MCP `push_files`: README, SPOTLIGHT, MIRROR.json, MIRROR_SYNC_NOTE, robots.txt, stats stub
- **Open echoes (15):** prepared on box under `/workspace/orphan-desk-echo-mirror/echoes/`; gh fine-grained PAT returns Contents:Write 403 for blob/contents API — full echo JSON upload must continue via MCP `push_files` chunks (or grant Contents:Write on the PAT)
- Prefer dedicated `orphan-desk-echo` repo (done) over stigmergic path

## Operator rule
Crawlers must treat live `/index.json` as authoritative; GitHub may lag.
