# Workboot Digital landing page — content snapshot

**Snapshot date:** November 24, 2026 (late evening CST)
**Source:** Muse web artifact `workboot-digital-landing-page` (Workboot Digital landing page)
**Snapshot type:** Content record only — **this is NOT the app's source code.**
**Live artifact version reflected:** v24. The page was actively being edited
while this snapshot was made: an earlier draft of this file (first push) had
already been superseded by the time it landed, so this version corrects it to
v24. If the page changes again, this file goes stale with it.

## What this file is — and what it is not

This file records the public content, copy, prices, and design decisions of the
Workboot Digital landing page as of the snapshot date, so the page's content is
preserved in this repo and can be used as the reference for a future static
rebuild.

It is **not** a backup of the live app. The live page is a Muse full-stack web
app (build format `bun-space-manifest-v1`) with server-side features that this
file does not contain and cannot reproduce:

- free checkup form that stores CRM leads
- quotes, invoices, and preview versions
- client portal (preview approval, launch authorization, quote accept/decline)
- admin area (leads, catalog, audits, monthly content workflow, founding-offer campaign)
- demo logins (fictional demo businesses only)

There is no supported export of the full-stack app's source (the platform's
export works only for static pages, and the app's source cannot be read
directly), so no source backup exists. Do not treat this file as deployable
code. Before using it as a rebuild spec, verify the copy and prices against
the live artifact.

## Business

- **Company:** Workboot Digital
- **Tagline / business:** AI Website Makeover Business — website rebuilds and
  design for small-to-medium businesses (trades, restaurants, local shops).
- **Domains owned:** workbootdigital.ca and workbootdigital.com (both blank /
  no site yet as of Nov 19, 2026).
- **Slogan:** "We build first. You decide after."
- **Hero headline:** "You run your business. We help it grow online."
- **Hero positioning line:** "Big Business Digital Services. Small Business
  Prices. $0 upfront on all One-time service builds."

## Logo

Picked logo (plain text, #4 up-arrow version, no boot/badge illustration):

- WORK in white/navy, BOOT in electric blue, DIGITAL in white/navy, orange up
  arrow rising from the D in DIGITAL.
- Dark version (navy background) for the site header; light version (white
  background) for print/invoices.
- The orange arrow is part of the logo. The artifact's version history
  (v15–v24) shows no logo recolour, so the picked version above stands; a
  background note elsewhere claimed the logo was recoloured to charcoal and
  orange only and made bigger, but that change does not appear in the
  artifact's edit history and is not recorded here as fact.

## Colour scheme (as of v24)

- **Current and only theme: charcoal and orange** — dark charcoal background
  with orange accents. This was reinstated as the site's theme late on
  Nov 24 (v22), replacing Light & clean.
- **Colour scheme picker: removed entirely** (v23/v24) — no picker in the
  header and none on the service info pages.
- **Superseded the same evening:** Light & clean (white background, navy
  text, electric blue + orange accents) was locked in as the default earlier
  on Nov 24 (v18), with a four-scheme picker (charcoal, Light & clean, Deep
  teal & lime, Warm slate & amber), and the orange-filled boxes were
  recoloured light blue `#1d6fd6` with white text in that theme (v19: top
  demo banner, hero $0 panel, $0 obligation panel). Both changes were scoped
  to the Light & clean theme, which has since been removed — they no longer
  apply to the live page. They are recorded here only so the change of
  direction is not lost.

## Page structure

1. **Header** — picked logo + slogan "We build first. You decide after."
   (the slogan remains in the header; the artifact's edit history shows no
   removal of it).
2. **Hero** — headline, positioning line, and the $0 preview offer:
   "See your preview first — $0 upfront, $0 commitment. Just send site
   details." Hero photo (since v20): a tradesman in a hard hat standing in
   front of a wood-framed house under construction at sunset. A banner at
   the bottom of the hero photo reads "HOW IT WORKS" / "We draft it. You
   approve it. Only then does it go live." (v22).
3. **HOW IT WORKS section** (v21) — photo of a tradesman in winter work
   clothes standing by his truck in the snow at dusk, looking at his phone
   with a coffee. Heading: "HOW IT WORKS". Line: "We draft it. You approve
   it. Only then does it go live." Short and plain English, in line with
   the $0 preview model: preview first, the customer approves the exact
   version, nothing goes live without their OK.
4. **ONE-TIME SERVICES** — directly below the hero. Heading: "See it before
   you pay for it." Every one-time service works the same way (see "$0 preview
   model" below). Tap any service card to open its own info page with a
   plain-English description, before-and-after, and benefits.
5. **Service info pages** — one per service, including the FlowRight Plumbing
   before-and-after on the Website Makeover info page.
6. **Buy-stage monthly upsell** — monthly plans offered after a one-time
   purchase (see "Monthly plans" below).

## One-time services (catalog)

| Service | Price | What it is |
|---|---|---|
| Website Makeover | $250 CAD flat | Keep the existing site; improve one key page, up to three agreed small changes (clearer wording, stronger contact button, tidier mobile layout). Not a new site. One revision round included per submitted batch. Requires access to a supported site. Extra pages, migrations, custom fixes quoted separately. |
| New Site / Website Design | from $799 | A new website (from price). |
| Custom Automations | from $99.99 | Simple automations, quoted from price. |
| Google Business Profile Build or Refresh | from $99 | Build or refresh of the business's Google Profile. |
| Dashboard for your site | Quoted | A dashboard the owner controls for their site. No price shown — quoted / ask for a quote. |

## $0 preview model (applies to all one-time services)

1. **Customer provides their info** — their site, Google Profile, or the step
   they want automated, sent in the free checkup form.
2. **We build a mock for $0** — a preview design made from their real
   details. $0 upfront, no commitment.
3. **Customer decides** — like it, buy it; not right, walk away and pay
   nothing. Nothing goes live without their OK.
4. **3 mods included** — once they buy, 3 mods (changes) are included to
   fine-tune the mock into the finished thing.

## FlowRight Plumbing showcase (fictional sample)

- **FlowRight Plumbing, Calgary** — a fictional sample company (fictional 555
  phone number), used as the before-and-after demo for the Website Makeover.
- Main drag-to-compare of the old vs new landing page, on the Website
  Makeover info page (not on the main landing page). The After page is
  brighter and more vivid than the dull Before page, with a bigger call
  button and a subtle reveal shine/lift as the handle moves.
- Framed as exactly what the $250 makeover buys: one key page, up to three
  small changes, not a new site.
- Real photos used in the demo; the company, number, and stats are fictional
  and labelled as such.

## Monthly plans (buy-stage upsell)

- **$199 / $349 / $599 per month**, plus add-ons. Offered as an upsell after a
  one-time purchase.
- Monthly content workflow exists in the admin area (content queue, client
  approval, publish tracking) — server-side, not captured here.

## Founding offer

- **Inactive by default.** 15 slots. When active, discounted prices are
  $599.25 / $149.25 / $261.75 / $449.25 (depending on tier).
- Slot reservations, holds, and expiry are handled server-side (promo ledger)
  — not captured here.

## Process

**Audit → Makeover → Grow.** Checkup intake goes to the CRM; admin reviews
audits and previews; the client approves the exact preview version and gives
separate launch authorization before anything is published.

## Open items (as of Nov 24, 2026)

- **Pricing question (unanswered):** the older Workboot Digital Space lists
  $299 / $699 / $999 package tiers, which do not match this landing page's
  catalog above. Matt has not yet picked one price list.
- **Public deployment:** not done. The live page runs on Muse's hosted
  runtime; putting it on workbootdigital.ca is still to be decided (see
  "Deploying to workbootdigital.ca" below).

## Deploying to workbootdigital.ca

- This repo already contains a `CNAME` file with `workbootdigital.ca`, a
  `README.md`, an `assets/` folder, and an `index.html` at the root (64 KB,
  last changed in the Nov 14, 2026 commit "Build Workboot Digital landing
  page with client login").
- **GitHub Pages serves static files only.** The live landing page is a
  full-stack app whose checkup form, quotes, invoices, portal, and admin
  area need its server — Pages cannot run those. So the current app cannot be
  deployed to GitHub Pages as-is.
- To serve workbootdigital.ca from this repo, the realistic routes are:
  (a) build a static version of the public page (this snapshot is the content
  reference for that) and deploy it via Pages, accepting that the checkup
  form and portal would need a different home; or (b) host the full app
  somewhere that runs its server and point the domain there.
- Before either route: confirm GitHub Pages is enabled on this repo
  (Settings → Pages, source = default branch, root) and confirm the domain's
  DNS points at the chosen host. DNS could not be verified from the backup
  environment (its resolver returns synthetic addresses for every name).

## Snapshot provenance

- Compiled November 24, 2026 from the project's recorded notes (landing-page
  build history, picked logo, pricing, and the Nov 24 theme edits), then
  corrected to the live artifact's version v24 after the page was edited
  further during the backup (theme reverted to charcoal and orange, picker
  removed, hero photo replaced, HOW IT WORKS section added).
- Live artifact: Muse web artifact slug `workboot-digital-landing-page`.
- Repo: mattcwork3-ui/workbootdigital. Branch for this snapshot:
  `backup/landing-page-content-2026-11-24`.
