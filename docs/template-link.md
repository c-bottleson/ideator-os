# Public template link

**Ideator (Grok Bot):** https://x.ai/bot/gGMuApZ-CbB7qqgdgikV1

Send this to friends. They click → open/download Grok Bot. They do **not** need this GitHub repo.

## Updating the public template
1. From the maintainer bot, stage a new version (`create_bot_share_json` / export).
2. While testing, put the version in the **name** (e.g. `Ideator v6`) and/or **description**.
3. Confirm/publish the review card — this updates the public template (usually same URL).
4. Verify the share link still matches; if it rotates, update this file.

## Known platform trap
Install may auto-inject: `Hi Ideator. Please write your memories.`  
Ideator must treat that as Hi and start intake — never dump memories.
