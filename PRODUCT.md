# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Hand-authored static HTML/CSS in this repository. Confirmed 2026-08-06: WordPress is
being dropped, not restyled.

The current files are Simply Static output from a WordPress install running the Salient
theme and WPBakery (`js_composer_salient`) — generated artifacts, not source. There is no
authoring scaffold in the repo today. The rebuild replaces them with files Erik edits
directly.

Deployment is already configured and stays: Cloudflare Workers Static Assets via
`wrangler.toml` (`directory = "."`, `not_found_handling = "404-page"`), promoted manually
with `npm run upload` then `npm run promote`. There is deliberately no `deploy` script.

## Users

Primary: **hiring managers and design directors** evaluating Erik Taylor for a full-time
product design role. They arrive from LinkedIn (the site's own copy says "If you're here
because of LinkedIn — this is the longer version of that"), typically mid-screen, giving
the site a short first pass before deciding whether to read a case study or forward him on.

The incumbent site also addresses Product Designers, Product Managers, and Developers
through a hero audience switcher. Those are secondary and unconfirmed as targets; the
hiring-manager path leads.

## Product Purpose

Get Erik hired. Success is a hiring manager or design director reaching out, or forwarding
the site to someone who will. Everything on the surface serves that decision.

## Positioning

Erik's case studies are built around **the decision and the bet**, not the process. Each
one names a fork, the option he chose, the tradeoff he accepted, and — critically — whether
the data has validated it yet. The advisor-navigation study states outright that agents
resisted the better concept and that the bet "won't be provable until full rollout data
comes in." The journey-map study frames itself as "a week of build time against months of
manual audit."

This is the thing a generic portfolio cannot copy: most portfolios present process as
inevitable and outcomes as proven. Erik shows judgment under uncertainty and admits what is
still open. Preserve that framing — it is the product.

Second, he works at the AI × design intersection as a practitioner, not a commentator:
prompt-to-prototype workflows, research synthesis, and a journey-map generator he actually
built and shipped solo in 8 weeks.

## Operating Context

Reviewers are comparing many candidates quickly, often on a phone or a second monitor,
often mid-meeting. The resume is a parallel artifact some reviewers want before they read
anything else. LinkedIn is the dominant referrer.

## Capabilities and Constraints

- Single-page site with anchor navigation — Home, What I Deliver, Case Studies, My
  Background, Testimonials, Contact — plus 8 sub-pages (4 case studies, 2 Pantheon Project
  pages, Convergence Strategy Group, WFG home sandbox).
- Current build weighs 561MB across 8,284 files; 505MB of that is `wp-content/uploads`.
  Under Cloudflare's 20,000-file and 25MiB-per-file asset limits, so it deploys — but
  nearly all of it is theme, plugin, and resized-derivative dead weight the rebuild sheds.
- The homepage is a single 156KB HTML file of WPBakery-generated markup.
- **Known defects in the incumbent, to be fixed, not carried forward:**
  - Contact link is `href="http://erikftaylor@gmail.com/"` — a malformed `mailto:` that
    resolves to nothing.
  - "Solution Oveview" (missing `r`) in the advisor-navigation case study.
  - Hero claims "8+ years" and "15+ years" in adjacent lines.
- **Currently freelancing (confirmed 2026-08-06).** This is the present-tense anchor that
  replaces Tovuti in all copy: Erik is a freelance product designer. Ridgeframe Strategies
  and his co-founder still stay off this surface by his decision, so the site says
  "freelance" without naming the firm.
- **The six-role audience switcher is removed (confirmed 2026-08-06).** For Everyone,
  Hiring Managers, Product Designers, Product Managers, Design Directors, and Developers
  collapse into one positioning statement aimed at the hiring manager. Do not rebuild the
  switcher; the six near-paraphrased pitch lines retire with it.
- **The resume ships as a hosted PDF (confirmed 2026-08-06),** replacing the Google Docs
  link. Erik confirms the document is final. The PDF itself is an asset he must supply; it
  is not in the repository yet.
- **Employment status (confirmed 2026-08-06):** Erik is no longer at Tovuti LMS. All
  present-tense Tovuti copy in the incumbent is stale and must be rewritten, including
  "currently shipping at Tovuti LMS" and "April 2026 is a strange time to be doing this
  work."
- **Availability:** open to work, stated quietly. Availability belongs in the contact
  section only — no banner, no badge, no urgency device.
- **Tenure claim:** lead with **15+ years**, counted from IBM in 2008 across copywriting,
  team lead, and design roles. The "8+ years" line is retired so the two never appear
  together. One claim only.
- **Ridgeframe Strategies is deliberately off this surface.** Erik's consultancy and his
  co-founder are not mentioned and should not be added. Consequence accepted knowingly: the
  period after Tovuti goes unexplained here.

## Brand Commitments

- Name and title: Erik Taylor, product designer, Denver-based.
- Live external properties, all confirmed present in the incumbent: LinkedIn, X, Instagram,
  and Threads (all `@erikftaylor`), `erikftaylor.com`, and `erikftaylor.gumroad.com` where
  he publishes checklists and frameworks for designers.
- Resume is currently a Google Docs link, surfaced twice as "Download Resume."
- Voice in the incumbent copy is plain, direct, and admits uncertainty — "This one's still
  open," "a bet the data hasn't fully validated yet." That voice is an asset and survives
  the redesign.
- **Standing design preference (confirmed 2026-08-06):** no conceptual conceit. The site is
  a portfolio, not a metaphor for something else, and it is judged on craft, typography,
  and composition rather than on a clever mapping. Eight metaphor-led worlds were offered
  across two rounds and declined; a craft-led production world was then accepted on the
  third. Read this as "no conceit," never as "no visual world" — the distinction is
  between adopting a material craft and pretending the site is another object.
- **Craft bar:** design-engineer portfolios of the rauno.me / paco.me class — obsessive
  detail, restrained palette, interactions that reward inspection without gating content.
  That level of finish is the standard the build is measured against.

## Evidence on Hand

Real, verified in the repository — none of this needs inventing:

- **Four case studies** with genuine depth: the journey-map generator (solo, 8 weeks), the
  agent-portal personalization decision, the WFG navigation tradeoff, and the IBM Digital
  Sellers Guidebook adoption problem. Each carries a problem statement, key decisions with
  explicit tradeoffs, process, and honest status.
- **Verbatim research quotes** from real usability sessions, e.g. "I like the other one
  better. People will have negative reaction to change."
- **Three named testimonials**, all from Transamerica: Adam Reed (Design Lead), Joseph Pham
  (UX Designer), Richard Bogdon (Director, Digital Marketing).
- **Work history**: Tovuti LMS 2025–2026; Transamerica 2020–2024; IBM Product Owner / UX
  Designer 2017–2020; IBM Team Lead 2010–2017; IBM Copywriter 2008–2010.
- 474 original images under `wp-content/uploads`.

**Absences that must never be filled with invention:** the case studies state plainly that
their metrics are not yet realized and their bets not yet validated. Do not convert
research-backed *goals* into achieved outcomes, and do not attach numbers to any of them.
The honesty is the differentiator; fabricating results would destroy the exact quality that
makes the work credible.

## Product Principles

1. **The bet is the story.** Lead with the decision, the tradeoff, and its open status —
   never with a process diagram.
2. **Unproven stays unproven.** Goals are labeled as goals. No invented metrics, no implied
   outcomes.
3. **One honest claim beats two impressive ones.** Where the incumbent hedged with
   overlapping numbers, state a single defensible fact.
4. **Weight is a design failure.** A 561MB portfolio for a designer who writes about
   reducing friction is an argument against him. The rebuild must be demonstrably light.
5. **The work outranks the interface.** A reviewer should reach real case-study substance
   fast; nothing decorative may delay it.

## Accessibility & Inclusion

Target **WCAG 2.2 AA**. Carried from Erik's professional standard — he audits other
organizations against it — and not separately renegotiated for this site. It is also a
credibility floor here specifically: design directors reviewing a UX portfolio will notice
contrast, focus, and keyboard failures, and a finding on his own site costs more than a
design flaw would.
