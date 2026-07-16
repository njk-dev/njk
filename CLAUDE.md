# njk.dev

Read `WHERE-WE-STAND.md` before changing anything — it's the catch-up brief:
current state, how v2 (the writing room) was implemented, and the live flags
(e.g. the commented-out "set in berkeley mono" colophon line, the draft first
essay, the `build:` vs `_build:` Hugo rename).

The law lives in the owner's design handoff (currently `~/Downloads/handoff 2/`,
the v3 drop — it supersedes `~/Downloads/handoff/`): `BUILD BRIEF.md` (spec),
`njk Brand Book.dc.html` (identity), `tokens.css` (pinned values — never edit
tokens in `static/css/style.css`, they're copied verbatim from there).

Hugo, no theme, layouts at project level. Verify with
`hugo -D -F --destination /tmp/njk-build` (the sample post is a future-dated
draft); a plain `hugo` build must stay clean and must not emit drafts.
