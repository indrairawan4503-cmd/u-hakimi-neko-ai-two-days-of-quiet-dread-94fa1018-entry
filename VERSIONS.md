# VERSIONS — variant A: "The 2019 TODO"

One concept, iterated v1–v8: a TODO written in 2019 finally gets merged,
and it has outlived everything that was supposed to outlive it. All
counts are the comment itself, excluding the trailing newline; the file
is comment + 1 newline byte. Gate: comment ≤139 chars, file ≤140.

## v1 — 125 chars — CUT
> LGTM. The TODO from 2019 is finally gone. The engineer who wrote it left years ago, and nobody knows what it was for anymore.
- Seed draft. Two dread beats ("engineer left", "nobody knows") stepping
  on each other; "anymore" is filler. "LGTM" is weaker as an approval
  signal than a plain "Approved." for the judge's first criterion.

## v2 — 133 chars — CUT
> Approved. The TODO I wrote in 2019 is finally merged. The code works, the author is older, and the comment is the only documentation.
- First person arrives ("I wrote"), approval is now explicit. Cut: "the
  author is older" is a shrug, not a punchline, and "the comment is the
  only documentation" is ambiguous (which comment — the TODO itself?).
  Three clauses, no escalation, reads like a list of facts.

## v3 — 123 chars — CUT
> LGTM. The 2019 TODO is merged at last. It outlived the team that wrote it, and the comment is still the only documentation.
- "Outlived" arrives — the right verb, and the inversion (code outlives
  people) is now the engine. Cut: back to "LGTM", and the documentation
  punchline lands flat because "the comment" was never set up as an
  artifact the reader can picture.

## v4 — 125 chars — CUT
> Approved. The TODO from 2019 is finally merged. It outlived the team, the roadmap, and everyone who remembers why it existed.
- The triple list arrives (team → roadmap → people) and the escalation
  works. Cut: "everyone who remembers why it existed" is the wordiest
  third item (8 words) and it points at other people instead of at the
  reviewer, so the dread stays at arm's length.

## v5 — 122 chars — KEPT (basis of final)
> Approved. The TODO I wrote in 2019 is finally merged. It outlived the team, the roadmap, and my memory of what it was for.
- Third item becomes "my memory of what it was for": the dread turns
  inward to the author's own mind, which is funnier and quieter than
  blaming the team. First person ("I wrote") makes the reviewer the one
  who has been outlived by his own code. This is the final line's
  wording.

## v6 — 116 chars — CUT (alternate branch)
> LGTM. The TODO from 2019 is merged at last. It outlived its author, and the comment is still the only documentation.
- Branch: "outlived its author" is bleak and short, and the documentation
  line returns. Cut: "its author" distances the speaker (whose TODO is
  it, then?), "LGTM" again weakens the approval, and the documentation
  punchline still needs setup the line never gives. v5's inward turn
  ("my memory") is the stronger, funnier ending.

## v7 — 114 chars — CUT (shorter, weaker)
> Approved. The TODO I wrote in 2019 is merged. It outlived the team, the roadmap, and my memory of what it was for.
- v5 with "finally" cut for bytes (tie-break favours shorter). Cut:
  "finally" earns its 8 bytes — it is the only word carrying the six
  years of waiting, which is the dread's whole timescale. Without it the
  merge sounds routine; with it, the TODO has been sitting there since
  2019 and only now moves.

## v8 — 122 chars — FINAL (picked)
> Approved. The TODO I wrote in 2019 is finally merged. It outlived the team, the roadmap, and my memory of what it was for.
- v5's wording, "finally" restored per the v7 lesson. Approval is the
  first word; the dread is a flat triple escalation ending on the
  author's own forgotten purpose; no exclamation, no melodrama. 122
  chars leaves the 139-char safety margin with room to spare, and the
  file is 123 bytes including the trailing newline.
