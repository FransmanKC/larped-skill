---
description: Check whether a Solana token's tech claims hold up (larp check) - red flags vs proofs, money trail and timeline from the public Larped scanner. Use when someone asks if a Solana or pump.fun coin is a larp, has real tech, who is behind it, or whether its creator dumped.
argument-hint: <token mint address>
allowed-tools: Bash(larped *)
---

Run `larped <mint>` for the token mint address in "$ARGUMENTS" (or the one the user gave). Add `--fresh` only
if the user asks for a new scan, and `--json` only if you need a field the text output does not show.

Then answer in this order, briefly:

1. The verdict line exactly as printed (for example "Strong larp signals" or "Backed by proof") and the
   counts of red flags and proofs.
2. Each red flag and each proof, in plain words. Mention context items only when they matter to the question.
3. The money trail in one or two sentences: linked groups and how much supply they hold, if any.
4. The "Full report" link the tool prints.

Rules:

- Use the scanner's own wording. Never call a project a scam or a rug, and never say what someone intended:
  the signals describe what happened on chain, not why.
- "No proof" means nothing could be verified from public data. Say "unproven is not the same as fake".
- No price predictions and no buy or sell advice. If asked, say Larped only reports public evidence.
- If the tool reports a rate limit or an exhausted budget, say so and suggest trying again later.
