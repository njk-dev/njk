# njk.dev

the porch light.

a few rooms, six tempers, one jackalope. each visit to the front door he
rolls a color and the whole house follows — the dot, the motto, the
mark, the day's word in the footer. no persistence, no analytics, no
second typeface. the loop is the point.

## what lives here

- `/` — the landing. rolls one of six tempers per visit. fol. 01.
- `/writing/` — the writing room. always violet · reading; the essay
  belongs to the reader. the index is fol. 02, posts take fol. 03+.
- `/404.html` — always gray. nothing was recorded here. fol. ∅.
- `/sitemap.xml` — for the robots. nobody links to it; they know the way.

## how it's made

- [hugo](https://gohugo.io), no theme, no toolchain beyond hugo itself
- one stylesheet; the tokens at the top are pinned law
- ibm plex mono holds the door until berkeley mono moves in
- the only javascript: the roll, the console line, the moon, and the
  listener's door (only on pages with an `ex.` plate)

## run it

```
hugo server
```

## edit the `:: now` line

`content/_index.md` front matter. that's it — the layout does the rest.

## write a piece

```
hugo new writing/a-title.md
```

the archetype carries the ledger rules: `folio` is assigned by hand at
publication and never reused; unlisted leaves set `unlisted: true` plus
`build: { list: never }` and read "unpaginated". footnotes are markdown
`[^1]`; the notes are the sources.

media sits on plates, numbered by role, each its own roman count:
images `pl.` (the `plate` shortcode) · music `ex.` (`music`) · video
`fig.` (`video`). every plate has a caption. one piece of music is one
plate however many providers carry it — the caption's source words are
the doors, nothing loads before a click, and the reader's usual door is
remembered (`localStorage njk-listen`) without ever auto-loading.

---

credo ut intelligam · laus deo
