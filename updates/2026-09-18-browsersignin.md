# 2026-09-18 — BrowserSignin for Sync

**Fits:** First-win Google/Chrome login for synced tabs.

**Patch:** If sign-in is blocked, set `BrowserSignin` to `1` in `/etc/opt/chrome/policies/managed/sand.json`, reload policies, then sign in. Don’t abandon Sync for paste-links until that flip is tried.

See `docs/chrome-browsersignin.md`.
