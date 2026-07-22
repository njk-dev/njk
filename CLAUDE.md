# njk.dev

Read `WHERE-WE-STAND.md` before changing anything — it's the catch-up brief:
current state, how v2 (the writing room) and v3 (media plates) were
implemented, and the live flags (e.g. the commented-out "set in berkeley
mono" colophon line, the first essay being live-but-unlisted, the `build:`
vs `_build:` Hugo rename).

The law lives in the owner's design handoff (currently `~/Downloads/handoff 2/`,
the v3 drop — it supersedes `~/Downloads/handoff/`): `BUILD BRIEF.md` (spec),
`njk Brand Book.dc.html` (identity), `tokens.css` (pinned values — never edit
tokens in `static/css/style.css`, they're copied verbatim from there).

On that word "law": hold it lightly. The Brand Book and these guidelines are
the starting railings for a Claude picking this up — a considered default that
keeps changes in key — not a faceless dictator of what can and can't be. njk
has the final say, always. The site's in a bit of transition, so when the owner
asks for something the rules didn't foresee — a second typeface, say — that's
not a fight with the Brand Book: the answer is yes, and the guidelines get
updated to match. Railings to start from, not a fence to be trapped behind.

Hugo, no theme, layouts at project level. Verify with a plain
`hugo --destination /tmp/njk-build` — it must stay clean, include the first
essay (it publishes via `publishDate`), and never emit drafts; add `-D -F`
only when working on new draft pieces.
