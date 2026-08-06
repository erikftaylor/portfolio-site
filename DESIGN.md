# Design

Recorded from the built world after the finish review, not written ahead of it.
Everything below is in `styles.css` and the two rebuilt documents; where the build
departs from the original intent, the build wins and the departure is stated.

## World

**Riso Studio** — risograph duplicator printing. Chosen on the third direction roll
(seed key `0b11d1a3`) after Erik declined eight metaphor-led worlds. It is a
*production craft*, not a conceit: the site does not pretend to be a printed
object, it is coloured and composed the way one is.

Surfaces: homepage is **Persuade**, case-study pages are **Read**.

## Ink

Three inks on paper. Roles are functional and enforced — a colour that owns a
region never also carries type, and the signal is spent once per section.

| Token | Value | Role |
|---|---|---|
| `--paper` | `#ffffff` | The sheet. Dominant surface. |
| `--paper-2` | `#f1f1ef` | Second stock, for alternating sections. |
| `--key` | `#16161a` | The key layer. **Every character of type on the site.** |
| `--key-2` | `#4a4a52` | Secondary type. 8.4:1 on paper. |
| `--key-rule` | `#d6d6d2` | Hairline rules on paper. |
| `--field` | `#3d5588` | Federal Blue. Owns whole regions and plate mats. 7.4:1 with white. |
| `--field-deep` | `#2b3c62` | Deep field for full-bleed bands. |
| `--signal` | `#ff48b0` | Fluorescent Pink. Primary action only. |

**The pink rule that governs everything:** fluorescent pink measures ~3.1:1 on
white. It can never carry body text and never sits under white type. Where it is a
button it takes `--key` text (5.98:1). It appears on: Resume, Email me, Download
resume, the case-study CTA, the skip link, the focus ring, and exactly one plate
mat — Concept 2, the option Erik chose. Nothing else.

A fourth ink (yellow) was introduced during fixes and then removed: retiring a dead
token by finding it a job adds an ink the world never named.

## Type

Self-hosted, no external requests.

- **Archivo Black** — all headings. `letter-spacing: -0.03em`, `line-height: 0.98`,
  `text-wrap: balance`. Display tops out at `6rem`.
- **Archivo** (variable 400–700) — body, labels, UI, tabular figures.

Body is `1.0625rem / 1.65`. Prose measure is `68ch`; the hero lede and captions run
narrower at `58ch`.

## Plates

A plate is the unit of imagery. The ink owns the **mat**, not the artwork — the
screenshots are Erik's proof and have to stay legible, so the field colours the
region around them and the artwork takes only `grayscale(0.35) contrast(1.04)`.
This is a deliberate departure from a true one-ink duotone, and product truth
forced it.

- `.plate` — field mat, key hairline border, dot screen at `opacity: 0.2` multiply.
- `.plate--signal` / `.plate--deep` — mat in pink or deep field.
- `.plate--crop` — `16/10` on desktop for run rhythm; `4/5` anchored `top left`
  under 720px, because a 16:10 crop of a dense interface is an unreadable phone
  thumbnail.
- `.plate--pan` — wide research boards and nav strips scroll horizontally under
  720px at a fixed `720px` art width, keyboard-reachable via `tabindex="0"` and
  `role="group"`. Cropping was rejected: it destroys what a research board shows.
  The dot screen lives on the inner `.pan-sheet` so it travels with the art.

## The sheet

`body::before` runs the 5px dot screen fixed across the entire viewport at
`opacity: 0.055`, `z-index: 50` — above the sticky masthead, so no region of the
page escapes the stock.

## Overprint

`.overprint` is the one place two inks actually cross: a `--field` ground with a
`--signal` layer at `inset: 0 34% 0 0` under `mix-blend-mode: multiply`. The
overlap resolves to a genuine third colour (~`#3d185e`, 14:1 with white) rather
than a tint. It stacks to a horizontal split under 860px. Used once, on contact.

## Motion

**One authored moment**, on the hero plate only. `.registration` puts a signal-ink
ghost out of register at `(-11px, +7px)` under multiply; it slides onto the key
while the plate settles from `(4px, -3px)`. Exponential ease-out
(`cubic-bezier(0.16, 1, 0.3, 1)`).

Content is **never** hidden waiting on script — the ghost is a layer over an
already-finished page, and the IntersectionObserver only plays the arrival. An
earlier build hid 43 elements at `opacity: 0` by default; that is the failure mode
this structure exists to prevent.

The only other movement is `.btn:hover` — a 2px translate with a `3px 3px 0` field
offset. That is misregistration, the world's own device, not a drop shadow.

`prefers-reduced-motion` disables both and smooth scrolling.

## Accessibility

WCAG 2.2 AA. All type is key or key-2 on paper, or white on field. Skip link,
visible focus rings at 3px offset, keyboard-reachable scroll containers, honest
alt text describing what is actually in each frame.

## Anti-patterns this world refuses

No kickers or eyebrows. No same-size card grid as page structure. No section
numbers. No gradient text, glass, glyph icons, or system display faces. Social
links are set as words, not icons — a type-led print world has no icon system and
should not borrow one.
