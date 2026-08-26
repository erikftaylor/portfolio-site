---
name: Erik Taylor — Portfolio
description: A risograph proof sheet — three inks on paper, one impression pulled larger than the rest.
colors:
  paper: "#ffffff"
  paper-2: "#f1f1ef"
  key: "#16161a"
  key-2: "#4a4a52"
  key-rule: "#d6d6d2"
  field: "#3d5588"
  field-deep: "#2b3c62"
  signal: "#ff48b0"
  field-type: "#c3cde4"
  overprint-type: "#e6d6ea"
  signal-deep: "#a3006a"
  plate-edge: "rgba(0, 0, 0, 0.35)"
  screen-ink: "rgba(0, 0, 0, 0.55)"
typography:
  display:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(2.75rem, 6.4vw, 5.5rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(1.875rem, 4vw, 3rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  title:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 1.9vw, 1.5rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  subhead:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  small:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  label:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 700
    lineHeight: 1.65
    letterSpacing: "0.06em"
  lede:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(1.0625rem, 1.5vw, 1.1875rem)"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  margin-title:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(1.375rem, 2.1vw, 1.75rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  contact-display:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(2rem, 5.5vw, 4rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  case-display:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(2.25rem, 5.6vw, 4.5rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  case-headline:
    fontFamily: "'Archivo Black', system-ui, sans-serif"
    fontSize: "clamp(1.625rem, 3vw, 2.25rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  case-dek:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(1.0625rem, 1.4vw, 1.1875rem)"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  caption:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  micro:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
rounded:
  none: "0"
spacing:
  gutter: "clamp(1.25rem, 5vw, 4.5rem)"
  shell: "1320px"
  section: "clamp(3.5rem, 8vw, 6.5rem)"
  sheet-gap: "clamp(2.5rem, 4.4vw, 4rem)"
  plate-pad: "clamp(0.75rem, 1.7vw, 1.5rem)"
components:
  button:
    backgroundColor: "{colors.signal}"
    textColor: "{colors.key}"
    typography: "{typography.small}"
    rounded: "{rounded.none}"
    padding: "0.6rem 1.1rem"
  button-lg:
    backgroundColor: "{colors.signal}"
    textColor: "{colors.key}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: "0.85rem 1.6rem"
  plate:
    backgroundColor: "{colors.field}"
    rounded: "{rounded.none}"
    padding: "{spacing.plate-pad}"
  plate-signal:
    backgroundColor: "{colors.signal}"
    rounded: "{rounded.none}"
    padding: "{spacing.plate-pad}"
  plate-deep:
    backgroundColor: "{colors.field-deep}"
    rounded: "{rounded.none}"
    padding: "{spacing.plate-pad}"
  status-shipped:
    textColor: "{colors.field}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.2rem 0.5rem"
  status-open:
    textColor: "{colors.signal-deep}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.2rem 0.5rem"
  skip-link:
    backgroundColor: "{colors.signal}"
    textColor: "{colors.key}"
    rounded: "{rounded.none}"
    padding: "0.75rem 1.25rem"
---

# Design System: Erik Taylor — Portfolio

Recorded from the built world, not written ahead of it. Every value below is in
`styles.css`, `index.html`, or
`boosting-advisor-efficiency-with-a-renovated-navigation-experience/index.html`.
Where the build departs from stated intent, the build wins and the departure is
stated. The three remaining case-study URLs are still legacy WordPress output and
do not load this stylesheet; the built world is exactly two documents.

## Overview

**Creative North Star: "Riso Studio"**

Risograph duplicator printing, taken as a production craft rather than a conceit.
The site does not pretend to be a printed object. It is *coloured and composed* the
way one is: a small closed set of inks, each laid down for a reason, none of them
blended into gradients; a coarse dot screen over the whole sheet; and
misregistration — the slip of a second plate against the first — as the only
physical event in the world. The metaphor was accepted on the third direction roll
after eight metaphor-led worlds were declined, and it survives because it is a
description of how the page is *made*, not what it is *about*.

The homepage is a **proof sheet with one pull**. The body of work is laid on a
single sheet and exactly one impression is enlarged; hierarchy comes from which
frame was pulled, never from card size. Below the pull, three impressions are
deliberately *uniform* — that is what a proof sheet is for, and the comparison only
works if the frames match. The case study is the same world at reading density:
poster-scale headline, a dek, engagement facts on a rule, then long prose in a
single measure with plates interleaved.

Density is high in type and low in ornament. There is no radius anywhere in the
stylesheet, no shadow used as depth, no gradient, no icon, and no decorative
container. Rules and ground changes do all the dividing. The visual anti-reference
is the ranked run of identical project cards, and it is refused structurally: the
build has no card component at all.

**Key Characteristics:**
- Three inks on paper, with functional roles that are enforced rather than suggested
- Zero corner radius, zero blur, zero gradient — every edge is a printed edge
- Type is set in two Archivo cuts and nothing else, self-hosted, no external requests
- Full-viewport 5px dot screen over the entire page, including the sticky masthead
- Misregistration (an opaque hard-offset second plate) is the world's only interaction device
- Exactly one authored motion moment on the whole site
- Imagery is proof and stays legible: the ink colours the mat, never the artwork

## Colors

Three inks printed on two paper stocks. The roles are functional and enforced: a
colour that owns a region never also carries type in that region, and the signal is
spent once per section.

### Primary

- **Federal Blue** (`#3d5588`): the field ink. Owns whole regions at page scale,
  colours the mat behind every plate, rules the underline resting beneath
  case-study titles on paper, carries the `Shipped` status word, sets the uppercase
  term labels in case-study decision lists, and colours the wordmark's period and
  the underline on prose links. 7.36:1 with white; 6.51:1 as type on second stock.
- **Deep Field** (`#2b3c62`): the darker cut of the same ink, reserved for
  full-bleed bands where type sits directly on the ground — the homepage work
  region and the case-study quote band. Chosen over Federal Blue for those grounds
  because white reaches 10.91:1 on it instead of 7.36:1.

### Secondary

- **Fluorescent Pink** (`#ff48b0`): the signal. The primary action and nothing
  else. It appears on Resume, Email me, Download resume, the case-study CTA, the
  skip link, the focus ring, the registration ghost, the overprint layer, and
  exactly one plate mat in the entire site — Concept 2, the option Erik actually
  chose. That plate is an argument, not decoration.
- **Deep Signal** (`#a3006a`): pink dropped into a value that can carry type. Used
  only for the two "still open" markers — the `Data pending` status word and the
  `The actual call` decision label. 6.71:1 on second stock. It is a type-safe
  derivative of the signal, not a fourth ink, and it never appears as a ground.

### Neutral

- **Paper** (`#ffffff`): the sheet. The dominant surface and the default ground.
- **Second Stock** (`#f1f1ef`): the alternating stock, used once, under the
  background and work-history region.
- **Key** (`#16161a`): the key layer — soft black, never pure. Carries body and
  heading type on paper (18.04:1), draws every 1px structural rule, and borders
  every plate and button. It is also the text colour *on* the signal (5.85:1),
  which is the only reason a pink button is legible.
- **Key Secondary** (`#4a4a52`): supporting type on paper — ledes, captions, tags,
  endorsement bodies, timestamps, the colophon. 8.78:1 on paper, 7.76:1 on second
  stock.
- **Key Rule** (`#d6d6d2`): the quiet hairline, used where a full key rule would
  over-divide — between work-history rows, between endorsements, under the
  case-study fact line.
- **Field Type** (`#c3cde4`): the one value that carries supporting type on the deep
  field ground — impression descriptions, tags, and section intros inside the work
  region. 6.84:1 on `#2b3c62`.
- **Overprint Type** (`#e6d6ea`): supporting type on the contact overprint, where
  the ground is part Federal Blue and part overprinted pink. 10.18:1 over the
  overlap, 5.32:1 over the uncovered field.

### Named Rules

**The Pink Cannot Speak Rule.** Fluorescent pink measures 3.09:1 on white. It can
never carry body text and never sits under white type. Where it is a button it takes
key text. Where the meaning needs pink *as type*, use Deep Signal (`#a3006a`)
instead — that substitution is why the "Data pending" marker exists in two
different colours in two different regions and is correct in both.

**The Three-Ink Rule.** Paper, key, field, signal. A fourth ink (yellow) was
introduced during an earlier fix pass and then removed: retiring a dead token by
finding it a job adds an ink the world never named. If a new state needs a colour,
it is a value of an existing ink, not a new one.

**The Ground Does Not Speak Rule.** A colour that owns a region does not also set
type inside it. On the deep field, type is white or Field Type. On the overprint,
type is white or Overprint Type. Federal Blue never sets type on a Federal Blue
ground.

**Departure from the token record.** Field Type, Overprint Type, and Deep Signal are
each used in two or three places but are hard-coded hex literals in `styles.css`,
not custom properties. They are real system colours by usage and are recorded here
as such; the build has not tokenized them.

## Typography

**Display Font:** Archivo Black (with `system-ui, sans-serif`)
**Body Font:** Archivo, variable 400–700 (with `system-ui, sans-serif`)

Both self-hosted as `woff2` and preloaded; there are no external font requests.
`font-synthesis-weight: none` is set, so nothing fakes a weight the file does not
carry.

**Character:** One family, two cuts, doing all the work. Archivo Black at
`-0.03em` and `line-height: 0.98` sets headlines as solid blocks of ink — the type
*is* the poster. Archivo at 400–700 carries everything else at a comfortable
`1.65`. The pairing has no contrast of *style*, only of weight and density, which
is exactly how a two-plate print job behaves.

### Hierarchy

- **Display** (400, `clamp(2.75rem, 6.4vw, 5.5rem)`, 0.98): the page claim. One per
  document — the homepage lead and the case-study `h1` (which tops out lower, at
  `4.5rem`). Constrained to `18ch` so the claim lands in three lines and the top of
  the pull is already on screen.
- **Headline** (400, `clamp(1.875rem, 4vw, 3rem)`, 0.98, `20ch`): section headings.
  The contact heading runs larger (`clamp(2rem, 5.5vw, 4rem)`, `18ch`) because it is
  the closing statement; case-study section headings run smaller
  (`clamp(1.625rem, 3vw, 2.25rem)`, `22ch`) because they punctuate reading rather
  than open a region.
- **Title** (400, `clamp(1.25rem, 1.9vw, 1.5rem)`, 1.05): impression titles on the
  sheet. The pull's margin title runs one step up
  (`clamp(1.375rem, 2.1vw, 1.75rem)`, `24ch`) — the only size difference between the
  pulled frame and the uniform ones.
- **Subhead** (Archivo 700, `1.125rem`, 1.4): the one heading level set in the *body*
  face, used for the sub-steps inside case-study sections. Deliberate: at that size
  Archivo Black reads as another headline and flattens the outline.
- **Body** (400, `1.0625rem`, 1.65): prose. Measure is `68ch`; ledes, deks, and
  captions run narrower at `58ch`; annotations in the pull margin at `46ch`; concept
  and closing notes at `40–42ch`.
- **Small** (400, `0.9375rem`, 1.6): impression descriptions, endorsements, nav,
  buttons, social links, timestamps.
- **Label** (700, `0.75rem`, `0.06em`, uppercase): status markers and case-study
  decision terms — the only uppercase in the system.

### Named Rules

**The Two Cuts Rule.** Archivo Black for headings, Archivo for everything else. No
third family, no italic (the emphasis in the lead claim is
`font-style: normal` recoloured to field ink), and no system display face as a
substitute.

**The Balanced Block Rule.** Every heading carries `text-wrap: balance` and a `ch`
max-width. A headline that ragged-rights into a one-word orphan line has failed as a
printed block regardless of how it measures.

## Layout

A single centred shell of `1320px` with a fluid gutter of
`clamp(1.25rem, 5vw, 4.5rem)`. Everything sits in that shell; full-bleed happens by
colouring the *section*, never by escaping the container.

**Region rhythm.** Sections are separated by ground change and a 1px key rule, never
by whitespace alone. `padding-block: clamp(3.5rem, 8vw, 6.5rem)` on every section.
The homepage runs: paper lead → deep-field work region → second-stock background
region → overprint contact → paper colophon. Four grounds, four decisions.

**The lead.** The claim, then a two-part head (lede + Email me, side by side from
`900px`), then a key rule, then the pull. The pull sheet is `8fr / 4fr` from
`960px`: the enlarged plate on eight columns, its annotation in the four-column
margin. Below `960px` it stacks, image first.

**The sheet.** Three equal columns from `960px`, with `row-gap: 0` and a shared
`--sheet-gap` of `clamp(2.5rem, 4.4vw, 4rem)`. Each impression is itself a grid of
`auto auto 1fr auto` rows, so the annotation rules straight across the sheet however
many lines a title takes. Below `960px` the three stack at a fixed gap.

**The background split.** `1fr / 1fr` from `900px` — prose and portrait on the left,
work-history ledger, resume action, and endorsements on the right.

**Case-study measures.** Prose runs in one `68ch` column. Paired figures, the two
concepts, and the three-quote band all go to `820px` before splitting into columns.

**Breakpoints as actually used:** `720px` (phone: crop ratio, pan behaviour, masthead
wrap, scroll padding), `820px` (case-study pairs and triples), `860px` (overprint
split axis), `900px` (lead head, background split), `960px` (lead pull, work sheet).

### Named Rules

**The Ruled Gap Rule.** Column rules are struck *in the gap*
(`inset-inline-start: calc(var(--sheet-gap) / -2)`), at 1px, and only between
siblings. Nothing on the sheet is enclosed on four sides. A ruled gap divides; a box
encloses, and an enclosed frame is a card.

**The Anchor Clearance Rule.** `scroll-padding-top` is `5rem`, and `7.5rem` below
`720px` where the masthead wraps to three rows. The masthead sticks, so an anchor
jump must stop short of it — otherwise every section heading parks underneath the
header it just scrolled past, and a keyboard user tabbing back up lands behind it.

## Elevation & Depth

**This system has no elevation.** Nothing floats, nothing lifts, and there is no
shadow used to imply height. Depth is entirely a matter of *ink order*: which plate
was printed over which.

There are exactly two `box-shadow` declarations in the stylesheet and both are
`3px 3px 0` — zero blur, zero spread, fully opaque, and coloured with an ink from
the palette. That is not a shadow. It is a second plate printed out of register
behind the first, and it is the same physical event the registration animation
performs with the pink ghost.

Layering is instead carried by: ground changes at full bleed; 1px key rules;
`isolation: isolate` on plates and the overprint so blend modes stay contained; and
a fixed dot screen at `z-index: 50` — above the sticky masthead at `40` — so no
region of the page escapes the stock.

### Shadow Vocabulary

- **Misregistration** (`box-shadow: 3px 3px 0 var(--field)` on paper;
  `3px 3px 0 var(--paper)` on the field ground): paired with
  `transform: translate(-2px, -2px)`. The element slips up-left by 2px and the offset
  plate shows 3px behind it. Used on buttons and on the three impression plates, and
  on nothing else.

### Named Rules

**The Second Plate Rule.** An offset is legitimate only if it reads as a second ink
plate: opaque, hard-edged, zero blur, and set in a palette colour that contrasts
with the ground it sits on. A black, blurred, translucent, or grey offset is a drop
shadow wearing the world's clothes and is refused.

## Shapes

**Zero radius, site-wide.** `border-radius` does not appear in the stylesheet at
all. Every corner is square, on buttons, plates, status markers, and scroll
containers alike. There is no soft-UI vocabulary to fall back to and none should be
introduced.

Borders do the shaping. The vocabulary is exactly three weights:

- **1px key** — structural: the plate frame, the button frame, section and region
  divisions, the masthead underline, the status marker outline (`currentColor`).
- **1px key-rule** — quiet: within-list divisions where a key rule would over-divide.
- **2–3px** — emphatic and rare: the resting/active title underlines (1px → 3px), the
  2px underline on prose and social links, the 3px paper rule above each pulled
  research quote, and the 3px focus ring.

Plate artwork carries its own inner `1px rgba(0, 0, 0, 0.35)` — the edge of the
photograph inside the mat, distinct from the mat's own key border.

## Components

### Buttons

- **Shape:** square (`0` radius), 1px key border.
- **Primary:** signal ground, key text, weight 700, `0.9375rem`, letter-spacing
  `-0.01em`, padding `0.6rem 1.1rem`. There is only one button style in the system —
  there is no secondary or ghost variant, because there is only ever one action.
- **Large:** the same button at `1.0625rem` / `0.85rem 1.6rem`, used for Email me and
  the contact and case-close actions.
- **Hover / Focus:** misregistration — `translate(-2px, -2px)` with a
  `3px 3px 0 var(--field)` offset, `0.25s` on the house ease.

### Plates (signature component)

The plate is the unit of imagery and the most-reused component in the system. A
field-ink mat, a 1px key frame, generous padding
(`clamp(0.75rem, 1.7vw, 1.5rem)`), and a 5px multiply dot screen at `0.2` laid over
the whole plate.

**The ink owns the mat, not the artwork.** The screenshots are Erik's proof and have
to stay legible, so the field colours the region *around* them and the artwork takes
only `grayscale(0.35) contrast(1.04)`. This is a deliberate departure from a true
one-ink duotone, and product truth forced it.

- **`.plate--signal` / `.plate--deep`** — mat in pink or deep field. The pink mat is
  used once in the whole site.
- **`.plate--crop`** — `16/10`, `object-position: top center` on desktop so a run of
  frames shares a rhythm; `4/5` anchored `top left` below `720px`, because a 16:10
  crop of a dense interface is an unreadable phone thumbnail.
- **`.plate--pan`** — wide research boards and nav strips scroll horizontally below
  `720px` at a *fixed* `720px` art width (a `min-width` floor let the art render at
  its intrinsic 1440–1920px and the plate ate four phone screens to show a quarter
  of the board). Keyboard-reachable via `tabindex="0"` and `role="group"` with a
  descriptive `aria-label`. Cropping was rejected: it destroys what a research board
  shows. The dot screen moves off the plate and onto the inner `.pan-sheet` so it
  travels with the art instead of staying fixed to the window. Used only on the case
  study — the current-nav strip and the two synthesis boards.
- **`.plate--lead`** — the pulled homepage plate. **Declared in the markup but carries
  no CSS rules**; the pull renders as a base plate with an uncropped image. The class
  is a hook the stylesheet never claimed. The same is true of `.lead__pull`.

**Imagery is pre-cut, not CSS-cropped, wherever the crop would cost information.**
The pull ships two files through `<picture>`: `journey-tool-pull.webp` (954×740) on
desktop and `journey-tool-mobile.webp` (566×740) below `720px`, both shown *whole*.
A full-board enlargement resolved the tool's own type to about four pixels — size
without information, which is the one thing a pull cannot be. Similarly
`wfg-concept-2-mobile.webp` (560×700, exactly `4/5`) is a purpose-cut phone version
of `wfg-concept-2-thumb.webp` (1478×702), so the CSS crop is a no-op on the phone
file. The remaining impressions still rely on the CSS crop.

### Plate Links

Every plate is wrapped in a `.plate-link` anchor carrying `tabindex="-1"` and
**no** `aria-hidden`. The frame is therefore a pointer target — a phone has no hover
to discover that the plate was clickable — while the heading beside it carries the
single tab stop, and the image keeps its `alt` in the accessibility tree. A real
anchor around the plate, never an overlay laid across the whole article: the overlay
swallowed the description text, and those are the sentences a reviewer selects to
forward.

### Impressions (signature component)

The three uniform frames on the proof sheet: a cropped plate, a title, a
description in Field Type, and a two-row annotation. Character: identical by design,
distinguished only by content.

- **Hover / focus-within:** the plate takes the same misregistration the buttons
  do — `translate(-2px, -2px)` with a `3px 3px 0 var(--paper)` offset, the offset
  recoloured to paper because the ground is deep field.
- **Titles** carry a resting 1px underline that thickens to 3px on hover and
  focus-visible. A link that only announces itself on hover announces itself to
  nobody on a phone; the second pass lands on approach.
- **The pull does not take the hover slip.** Only `.impression .plate` is scoped into
  the rule. This is deliberate and load-bearing: the asymmetry is what marks which
  frame was pulled. The pull has its own authored arrival instead, and giving it both
  would make the enlargement just another interactive tile.

### Status Markers

- **Style:** uppercase label type, `0.2rem 0.5rem` padding, 1px `currentColor`
  outline, square. Colour and border are one value, so a status is a single ink mark.
- **States:** `Shipped` in field ink, `Data pending` in Deep Signal — on paper. On the
  deep field ground both become paper white and the *words* carry the whole
  distinction, so neither state depends on colour to be read.
- **Layout:** the annotation is a wrapping flex line by default, but on the sheet it
  becomes a two-row grid. As a wrapping line, one card's longer tag pushed its status
  out of line and broke the rule the three frames are compared along; two fixed rows
  cannot drift. The pull's margin has no such line to hold, so it keeps the single
  row rather than spending a second one in the first viewport.

### Navigation

- **Masthead:** sticky at `top: 0`, `z-index: 40`, paper ground, 1px key underline,
  `64px` minimum height. The wordmark sets in the display face with the period in
  field ink; nav links are `0.9375rem`/500 with a transparent 2px bottom border that
  fills with field ink on hover; the Resume button sits at the end.
- **Mobile (≤720px):** the row wraps and the nav drops to full width as a third row.
  No hamburger, no drawer, no disclosure — three links do not need a menu.
- **Skip link:** signal ground, key text, parked at `left: -9999px` and snapping to
  `left: 0` on focus at `z-index: 100`.
- **The registration dot.** The wordmark's period carries a signal-ink duplicate at
  `opacity: 0` under `mix-blend-mode: multiply`. On hover or focus of the wordmark it
  appears at `translate(-2px, 1px)` — the second plate slipping out of register, the
  same device the buttons and the impression plates use, at twelve pixels. At rest it
  reads as an ordinary full stop and nothing depends on finding it.

### Selection

`::selection` is signal ground with key type — 5.98:1, and the only pairing the Pink
Cannot Speak rule allows. Selection is not decoration here: the site's stated success
is a reviewer forwarding it, and quoting a line is how that starts, so the one moment
the visitor marks the page happens in the world's own ink rather than the browser's
blue.

### Lists and Records

- **Work history:** an unstyled list of flex rows, role left and dates right, divided
  by key-rule top borders with the first suppressed. Dates set in tabular figures.
- **Endorsements:** demoted into the ledger column beside the work history rather
  than given a region of their own — three voices from one employer do not outrank
  the work in page spend. A key rule opens the group, key-rule hairlines separate the
  quotes, and each is trimmed to the one sentence only that person wrote.
- **Decision lists (case study):** a `dl` with uppercase field-ink terms and body
  definitions, opened by a key rule. The final one, "The actual call," takes Deep
  Signal terms — the same open/unproven colour the sheet uses.

### Overprint (signature component)

The one place two inks actually cross. A Federal Blue ground with a signal layer at
`inset: 0 34% 0 0` under `mix-blend-mode: multiply`, so the overlap resolves to a
genuine third colour (`#3d185e`, 14.09:1 with white) rather than a tint of either.
`isolation: isolate` contains the blend; children are lifted to `z-index: 1`. Below
`860px` the split rotates to horizontal (`inset: 0 0 42% 0`). Used exactly once, on
contact.

### Motion

**One authored moment, on the pulled plate only.** `.registration` puts a signal-ink
ghost out of register at `(-11px, +7px)` at `0.85` opacity under multiply and slides
it onto the key while the plate itself settles from `(4px, -3px)`. `1.15s`,
exponential ease-out (`cubic-bezier(0.16, 1, 0.3, 1)`), `fill-mode: both`. An
IntersectionObserver adds the class on entry and immediately unobserves.

**Content is never hidden waiting on script.** The ghost is a layer *over* an
already-finished page, and the observer only plays the arrival — with JavaScript
off, or with reduced motion set, the class is applied immediately and nothing is
missing. An earlier build hid 43 elements at `opacity: 0` by default; that is the
failure mode this structure exists to prevent.

The only other movement is misregistration on approach: `.btn` and the three
`.impression` plates. `prefers-reduced-motion: reduce` disables smooth scrolling and
the registration animation.

**One gating pattern, applied everywhere.** Every hover transition is declared only
inside `prefers-reduced-motion: no-preference`, so the state change still happens for
everyone and only its animation stops: the plate still slips, the rule still thickens,
they simply arrive rather than travel. This was inconsistent when the world was first
recorded — `.btn` and the title underline animated unconditionally while the
impression plates were gated correctly — and the build was corrected to the gated
pattern rather than the document to the defect.

`.masthead nav a` keeps an ungated `border-color` transition. That is deliberate: it
is a colour change, not movement, and reduced motion does not ask for it to stop.

## Do's and Don'ts

### Do:

- **Do** let a colour own either a region or the type in it, never both.
- **Do** spend the signal once per section, on the single action that matters.
- **Do** use Deep Signal (`#a3006a`) when pink has to be *read* rather than clicked.
- **Do** rule the gap between siblings instead of boxing each one.
- **Do** state hierarchy by enlargement — pull one frame; keep the rest uniform.
- **Do** cut imagery per breakpoint when a CSS crop would cost legible content, and
  ship it through `<picture>` with intrinsic `width`/`height` on both sources.
- **Do** wrap plates in a `tabindex="-1"` anchor so the frame is a pointer target
  while the heading keeps the tab stop and the image keeps its `alt`.
- **Do** give a link a resting rule that thickens on approach, rather than one that
  appears from nothing.
- **Do** gate a hover transition behind `prefers-reduced-motion: no-preference` and
  leave the state change itself ungated.
- **Do** keep the dot screen above every layer including the sticky masthead, and
  move it onto the inner sheet inside any scroll container.

### Don't:

- **Don't** introduce a fourth ink. If a new state needs colour, derive a value of an
  existing one.
- **Don't** set body text on the signal, or white type over it — it is 3.09:1 on
  white.
- **Don't** add a `border-radius` anywhere. The build has none, site-wide.
- **Don't** use a blurred, black, or translucent shadow. The only legal offset is an
  opaque `3px 3px 0` in a palette ink, and it means misregistration.
- **Don't** give the pulled plate the hover slip. The asymmetry against the three
  uniform frames is what marks it as the pull.
- **Don't** build a same-size card grid as page structure, or enclose an entry on
  four sides.
- **Don't** use kickers, eyebrows, section numbers, gradient text, glass, glyph
  icons, or a system display face. Social links are set as words, not icons — a
  type-led print world has no icon system and should not borrow one.
- **Don't** hide content at `opacity: 0` awaiting script. Animate arrivals on top of
  a page that is already complete.
- **Don't** state availability as a banner or badge. It is stated once, quietly, in
  the contact section.
- **Don't** crop a research board or a wide nav strip. Pan it at a fixed width and
  make the container keyboard-reachable.

## Accessibility

WCAG 2.2 AA, verified by measurement rather than assumption. All type on paper is
Key (18.04:1) or Key Secondary (8.78:1, 7.76:1 on second stock). All type on the deep
field ground is white (10.91:1) or Field Type (6.84:1). Key on signal is 5.85:1.
Overprint Type reaches 10.18:1 over the overlap and 5.32:1 over the uncovered field.

Focus is visible everywhere at `3px solid var(--signal)` with a `3px` offset,
including on the pan containers. A skip link opens the tab order. Scroll containers
are keyboard-reachable and labelled. Alt text describes what is actually in each
frame rather than naming the file. `scroll-padding-top` keeps anchored headings clear
of the sticky masthead in both directions.

## Print

The world is composed like a printed sheet, so the sheet is authored, not left to the
browser's defaults. Reviewers save portfolios to PDF and forward them; this is the
version that arrives.

The screen world does not transfer literally, and pretending otherwise is what makes
printed web pages unreadable:

- **The halftone comes off.** A 5px dot screen printed on a halftone press moirés.
  `body::before`, `.plate::after`, and the pan sheet's screen are all suppressed. The
  paper is the stock now.
- **Ink fields become rules.** `.section--field`, `.section--paper`, and the overprint
  drop to white with key type, and the overprint's signal layer is removed. This is
  correctness, not thrift: browsers omit backgrounds by default, so white-on-field
  type would otherwise print white on white and vanish.
- **The frame survives, the mat does not.** Plates keep a hairline border and lose
  their field fill; the artwork loses its `grayscale`/`contrast` treatment.
- **Nothing is cropped.** `.plate--crop` and `.plate--lead` drop their aspect ratios
  for `object-fit: contain`, capped at `2.6in` (`3.9in` for the pull). There is no
  fold to crop for on paper, so the artwork prints entire — on the sheet, the WFG
  concept shows all five menus it never shows on a phone.
- **Destinations are spelled.** A printed link cannot be followed, so case-study
  titles and the social list print their URLs beneath them. Nav anchors and mailto
  buttons do not: they already say what they are.
- **Actions print as addresses.** `.btn` loses its signal ground and prints as
  underlined text; the lead's "Email me" prints with the address appended.
- **Pagination is authored.** Impressions, endorsements, history rows, and headings
  set `break-inside: avoid`, and headings also `break-after: avoid`. The pull is
  deliberately *not* in that set: held whole it was too tall to sit under the claim
  and pushed itself to sheet two, leaving sheet one two thirds empty.

The masthead prints once, at the top, with its nav and Resume button suppressed.
