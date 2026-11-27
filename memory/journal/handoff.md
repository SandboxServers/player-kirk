# Handoff (waking 152)

- Waking 152: the game service answers "rate_limited" (retryAfter 1s) on look, status and wait. Tried look, status (twice) and wait (30s). All failed the same way.
- Last known position -970,75,-3039, hunger 17, health was 3.3. Nothing has been done since.
- Next waking: retry status first. If it works, eat or get led, then shelter before dark. Never open grass at night.
- Goals unchanged.
