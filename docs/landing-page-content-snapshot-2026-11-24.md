# Workboot Digital landing page — content snapshot

**Snapshot date:** November 24, 2026 (late evening CST)
**Source:** Muse web artifact `workboot-digital-landing-page` (Workboot Digital landing page)
**Snapshot type:** Content record only — **this is NOT the app's source code.**

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
- The orange arrow is part of the logo and was NOT recoloured in the Nov 24
  box-colour change below.

## Colour scheme (as of Nov 24, 2026)

- **Default (locked in Nov 24): Light & clean** — white background, navy
  text, electric blue + orange accents. The page loads in this scheme on every
  visit and after a reload.
- **Colour scheme picker:** still on the page with all four schemes; a
  visitor's pick is remembered on their device (localStorage), with Light &
  clean as the default when nothing is picked.
- **Other schemes:** (1) Charcoal — dark navy + electric blue + orange (the
  original default); (2) Deep teal & lime — dark teal background, bright lime
  accent, white text; (3) Warm slate & amber — warm dark slate background,
  amber/orange accent, soft white text.
- **Nov 24 box-colour change (Light & clean theme only):** the orange-filled
  boxes/banners are now light blue `#1d6fd6` (the same blue as the buttons)
  with white text — the top demo banner, the hero "$0 preview" panel, and the
  "$0 obligation" four-step panel in One-Time Services. White on `#1d6fd6` is
  readable for the bold panel text. Other colour schemes were not changed.

## Page structure

1. **Header** — picked logo + slogan "We build first. You decide after."
2. **Hero** — headline, positioning line, and the $0 preview offer:
   "See your preview first — $0 upfront, $0 commitment. Just send site
   details."
3. **ONE-TIME SERVICES** — directly below the hero. Heading: "See it before
   you pay for it." Every one-time service works the same way (see "$0 preview
   model" below). Tap any service card to open its own info page with a
   plain-English description, before-and-after, and benefits.
4. **Service info pages** — one per service, including the FlowRight Plumbing
   before-and-after on the Website Makeover info page.
5. **Buy-stage monthly upsell** — monthly plans offered after a one-time
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
  build history, picked logo, pricing, and the Nov 24 theme edits).
- Live artifact: Muse web artifact slug `workboot-digital-landing-page`.
- Repo: mattcwork3-ui/workbootdigital. Branch for this snapshot:
  `backup/landing-page-content-2026-11-24`.
