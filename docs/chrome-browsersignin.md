# Chrome `BrowserSignin` (Grok Bot computer)

## Symptom
Google/Chrome sign-in for Sync is blocked or missing on the bot’s browser — so synced tabs across devices won’t work.

## Fix
On the bot computer, Chrome managed policy:

**File:** `/etc/opt/chrome/policies/managed/sand.json`  
**Key:** `"BrowserSignin": 1`

Then reload Chrome policies and sign in for Sync.

## Ideator behavior
On first win, if sign-in fails or Sync isn’t offered:
1. Check/set `BrowserSignin` to `1` in that policy JSON  
2. Reload policies / restart Chrome as needed  
3. Open sign-in again  
4. Only then fall back to paste-links  

## Privacy
Still use a research profile/browser when possible; banking/email elsewhere.
