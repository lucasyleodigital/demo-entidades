---
name: Web generica per a entitats
description: Demo website for small non-profits, built as the entity's own membership card.
colors:
  cobalt: "#2340a8"
  cobalt-deep: "#172d78"
  cobalt-ink: "#c9d4f7"
  stamp: "#d4322c"
  stamp-text: "#a8231d"
  quota: "#ffd23f"
  paper: "#f7f8fa"
  ground: "#eef1f4"
  ink: "#14171c"
  ink-2: "#4a5160"
  muted: "#5d6677"
  line: "#cdd3dc"
typography:
  display:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(44px, 6.2vw, 84px)"
    fontWeight: 800
    lineHeight: 1.04
    letterSpacing: "-0.025em"
    fontVariation: "'wdth' 112"
  headline:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(34px, 4.4vw, 56px)"
    fontWeight: 800
    lineHeight: 1.04
    letterSpacing: "-0.025em"
    fontVariation: "'wdth' 112"
  title:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 800
    lineHeight: 1.18
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 104"
  body:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.6
  lead:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.6
  typed:
    fontFamily: "Courier Prime, Courier New, monospace"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    letterSpacing: "0.02em"
  button:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: 1
    fontVariation: "'wdth' 105"
rounded:
  tag: "3px"
  slot: "4px"
  mark: "6px"
  btn: "10px"
  card: "14px"
  carnet: "16px"
spacing:
  gutter: "24px"
  max: "1180px"
  sec: "112px"
  sec-mobile: "76px"
  sec-head: "48px"
  grid-gap: "56px"
components:
  button-quota:
    backgroundColor: "{colors.quota}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.btn}"
    padding: "16px 22px"
  button-cobalt:
    backgroundColor: "{colors.cobalt}"
    textColor: "#ffffff"
    typography: "{typography.button}"
    rounded: "{rounded.btn}"
    padding: "16px 22px"
  button-cobalt-hover:
    backgroundColor: "{colors.cobalt-deep}"
  button-stamp:
    backgroundColor: "{colors.stamp}"
    textColor: "#ffffff"
    typography: "{typography.button}"
    rounded: "{rounded.btn}"
    padding: "16px 22px"
  button-line:
    backgroundColor: "transparent"
    textColor: "currentColor"
    typography: "{typography.button}"
    rounded: "{rounded.btn}"
    padding: "16px 22px"
  button-sm:
    padding: "11px 16px"
  card-paper:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "30px"
  ticket:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
  ticket-stub:
    backgroundColor: "{colors.cobalt}"
    textColor: "#ffffff"
    padding: "18px 20px 20px"
  field-typed:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.typed}"
    rounded: "0"
    padding: "6px 2px 8px"
  sticker:
    backgroundColor: "{colors.quota}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tag}"
    padding: "10px 14px"
---

# Design System: Web generica per a entitats

## Overview

**Creative North Star: "The Membership Card"**

The whole site is printed stationery belonging to the entity: a carnet de soci on a cobalt cardstock field, with the entity's own name typed into it. Every section is one more piece of the same desk drawer (a values index card, event tickets with tear-off stubs, stacked join coupons, an enrolment slip, a document folder with a tab, a photo album with mounting corners). Paper sits on cobalt or on cool grey ground, is tilted a degree or two by hand, and casts a soft, deep shadow. Red rubber stamps mark identity and receipt; yellow stickers mark what is paid, offered or worth taking.

Density is generous and civic: large readable type (18px body, 19-21px leads), long section padding (112px), one dominant object per section. The register is warm, practical and slightly handmade, never corporate and never charity-sentimental. The stock NGO page (hero photo of hands, headline, donate button) is the confirmed anti-reference.

Two voices carry all text: Archivo, widened on its width axis, for anything printed (names, headings, buttons); Courier Prime for anything filled in (dates, field values, counts, form input, metadata).

**Key Characteristics:**
- Cobalt cardstock fields alternating with cool grey ground and paper bands.
- Paper objects, slightly rotated, with soft layered shadows; no flat full-bleed photography.
- Red rubber stamp as the identity and confirmation mark, applied once.
- Yellow quota sticker as the single call-to-action color.
- Printed (Archivo expanded) versus typed (Courier Prime) as the core type distinction.
- Perforations, dotted rules and dashed borders as the separator vocabulary.

## Colors

A blue-stationery palette: one saturated cobalt carries the surfaces, a rubber-stamp red and a sticker yellow are the only accents, everything else is cool paper and ink.

### Primary
- **Cardstock Cobalt** (cobalt): the hero field, the join section, the enrolment-slip band, ticket stubs, the brand mark, secondary buttons, icons on paper and the focused-field underline. It is a surface color first, not a text accent.
- **Deep Cobalt** (cobalt-deep): the carnet's top band, the featured news card, the closing offer section, and the hover state of cobalt buttons.
- **Cobalt Ink** (cobalt-ink): secondary text on cobalt surfaces (leads, dates, paragraphs). Never used on paper.

### Secondary
- **Rubber Stamp Red** (stamp): the stamp graphics, the stamp-red submit button, the "today" marker dot and rule in the agenda, the first (soonest) ticket stub, contact icons, invalid-field underline and the text caret.
- **Stamp Text Red** (stamp-text): the darker red used whenever red is small text on paper (list numerals, relative dates, news dates, error messages), so it stays legible.

### Tertiary
- **Quota Yellow** (quota): the primary call-to-action button, the PAGAT sticker on the carnet, the PDF sticker, check icons and the giant date numeral on deep cobalt, link color in the demo bar, text selection and the focus outline.

### Neutral
- **Card Paper** (paper): every paper object (carnet, values card, coupons, enrolment slip, document card, contact card) and the agenda and album bands.
- **Cool Ground** (ground): page background, ticket bodies, sticky header (at 94% opacity with blur).
- **Ink** (ink): body text on paper, the demo bar and footer background, pressed language toggle.
- **Ink Two** (ink-2): secondary text on paper: section leads, labels, metadata, nav links.
- **Muted Grey** (muted): placeholder content and the dotted rule under typed card values.
- **Rule Grey** (line): header border, section borders, list dividers, language-toggle border.

### Named Rules
**The Two Inks Rule.** Red appears in two strengths: stamp for graphics, fills and large marks; stamp-text for any red text on paper. Never set small text in stamp red on paper.

**The Sticker Rule.** Yellow is for what the visitor can take or has paid: the main CTA, the PAGAT box, a document sticker, check marks. It is never a section background and never body text on paper.

**The Cobalt Is Cardstock Rule.** Cobalt is a surface you place paper on. Sections alternate cobalt, deep cobalt, ground and paper; paper objects sit on top. Text on cobalt is white or cobalt-ink only.

## Typography

**Display Font:** Archivo variable (weight 100-900, width 62-125%), self-hosted, with system-ui fallback
**Body Font:** Archivo at normal width
**Label/Mono Font:** Courier Prime 400/700, self-hosted, with Courier New fallback

**Character:** a widened grotesque that reads like a card printer's type, paired with a typewriter face that reads like someone filled the card in by hand at the association's desk.

### Hierarchy
- **Display** (800, clamp(44px, 6.2vw, 84px), 1.04, width 112%): the entity name in the hero only. Steps down to clamp(36px, 4.4vw, 60px) for names over 22 characters and clamp(30px, 3.2vw, 44px) over 42, so personalised long names never break the layout.
- **Headline** (800, clamp(34px, 4.4vw, 56px), 1.04, width 112%, -0.025em): section titles. Balanced wrapping. Scaled down inside the enrolment slip to clamp(30px, 3.4vw, 42px).
- **Title** (800, 21-30px, 1.18-1.2, width 104%): card titles: ticket titles (21px), news items (23px), coupon titles (30px), contact card (26px).
- **Body** (400, 18px, 1.6): running text. Leads at 19-21px in ink-2 or cobalt-ink, held to 30-62ch.
- **Typed** (Courier Prime 400/700, 15-19px): dates, times, relative days, field values on the carnet, value descriptions on the values card, form input, document metadata.
- **Label** (700, 14px, 0.02em): form labels in ink-2. On the carnet only, field labels are 600 uppercase at 0.08em tracking, as printed card captions.
- **Numeral** (800, width 112-125%, line-height 0.8-0.9): oversized day numbers on ticket stubs (54px) and the featured news card (clamp(90px, 11vw, 150px), quota yellow).

### Named Rules
**The Printed and Typed Rule.** Archivo is what the entity printed; Courier Prime is what was filled in. Dates, times, counts, values and user input are typed. Names, headings and buttons are printed. Do not swap them.

**The Width Axis Rule.** Headings and numerals widen (font-stretch 104-125%); body text stays at 100%. Widening is how the type signals "printed on a card".

## Layout

A centred column of max 1180px with 24px gutters. Each section is one fixed moment with a single dominant object, padded 112px top and bottom (76px under 760px), with a section header held to 62ch and 48px below it (36px on mobile).

Two-column grids are asymmetric (1fr / 1.05fr hero, 1.1fr / .9fr about, .85fr / 1.15fr join, 1.25fr / 1fr news, 1.2fr / .8fr close) with 48-64px gaps, and collapse to one column at 900px. The hero fills min(100dvh - 110px, 820px).

Signature layouts: the agenda is a four-column ticket grid that becomes a horizontal scroll-snap strip (cards 260px to 78%) under 1000px; the join section pins its intro and stacks sticky coupons that offset 30px each (18px on mobile); the album is a six-column collage on 120px rows with mixed spans, two columns on mobile. The header nav collapses to a dropdown under 1060px.

## Elevation & Depth

Depth is physical paper on a desk: soft, deep, negative-spread drop shadows tinted toward ink or navy, combined with small rotations. No hard offset shadows, no glows. Flat surfaces (tickets, list rows, sections) rely on tonal contrast between ground, paper and cobalt instead.

### Shadow Vocabulary
- **Card lift** (`box-shadow: 0 30px 50px -34px rgba(20,30,70,.55), 0 6px 14px -8px rgba(20,30,70,.25)`): paper cards resting on ground (values card, document card).
- **Held object** (`box-shadow: 0 2px 0 rgba(255,255,255,.6) inset, 0 40px 70px -30px rgba(0,0,0,.45), 0 10px 22px -10px rgba(0,0,0,.3)`): the carnet on cobalt.
- **Stacked coupon** (`box-shadow: 0 30px 60px -28px rgba(0,0,0,.45), 0 8px 18px -10px rgba(0,0,0,.3)`): paper on cobalt in the join stack; the enrolment slip uses a single `0 40px 80px -40px rgba(0,0,0,.5)`.
- **Sticker** (`box-shadow: 0 2px 4px rgba(0,0,0,.18)` to `0 3px 6px rgba(0,0,0,.18)`): small yellow stickers lifted off the paper.
- **CTA press** (`box-shadow: 0 10px 24px -12px rgba(0,0,0,.4)`): the yellow quota button only.

### Named Rules
**The Hand-Placed Rule.** Paper objects carry a small rotation (-3deg carnet, 1.2deg values card, -1deg document, -1.5 to 1deg coupons, -4 to -3deg stickers, -1.4 to 1.2deg photo slots). Rotations reset to 0 on mobile, except stickers and stamps.

**The Stamp Lands Once Rule.** The stamp animates in exactly once per trigger (on load for the carnet, on submit for the slip) with a press from 1.9x scale and blur to rest at 0.9 opacity, followed by a 3px thud of the card. Nothing else on the page uses an entrance flourish of that weight.

## Shapes

Two radii carry the system: 14px for every card and container, 10px for buttons, toggles and the skip link. The carnet itself is 16px at an ID-card aspect ratio (1.586). Small paper bits go sharper: 6px brand mark and photo frame, 4px album slots and the document card's tab corner, 3px stickers and quota boxes. Form fields have no box at all.

Recurring forms: circular perforation notches (18px) cut into tickets at the stub line; dashed tear lines between stubs and bodies; a dotted underline for every typed value and input; a pill-shaped punch slot at the top of the carnet; a folder tab on the document card; black triangular photo corners on album slots; the circular double-ring stamp with text set on a path.

## Components

### Buttons
Chunky, printed, and lifted 2px on hover.
- **Shape:** gently rounded (10px), 2px border, icon gap 10px, Archivo 700 17px widened to 105%.
- **Quota (primary):** yellow with ink text and the CTA press shadow, 16px 22px. The one main action per viewport (Fes-te soci, Vull una web així). Hover lightens to #ffdb63.
- **Cobalt:** cobalt with white text, hover to deep cobalt. Used on paper (header CTA, coupon actions).
- **Stamp:** stamp red with white text. Reserved for submitting the enrolment slip.
- **Line:** transparent with a currentColor border; secondary action on cobalt (hero) and ticket sign-up on ground.
- **Small:** 11px 16px at 15px.
- **Hover / Focus:** translate -2px on hover, +1px on active, 0.2s on the expo-out ease. Focus is a 3px quota-yellow outline offset 3px, site-wide.

### Cards / Containers
- **Corner Style:** 14px.
- **Background:** paper on ground or cobalt; deep cobalt for the featured news card.
- **Shadow Strategy:** card lift on ground, stacked coupon or held object on cobalt (see Elevation).
- **Border:** none on paper; demo notes use a 1.5px dashed grey border on transparent.
- **Internal Padding:** 30-40px; 48px 52px for the enrolment slip; 22-30px on mobile.

### Inputs / Fields
- **Style:** no box. Transparent, Courier Prime 19px, 2px dotted grey bottom rule, 0 radius. Textareas show ruled lines every 34px. Selects use a drawn chevron.
- **Focus:** the rule turns solid cobalt and the field takes a 5% cobalt wash; outline suppressed in favour of that.
- **Error:** bottom rule turns stamp red and a stamp-text message appears below at 14px. Checkboxes use cobalt accent-color at 20px.

### Navigation
Sticky 68px header on ground at 94% with saturate-blur and a rule-grey bottom border. Brand mark is a small cobalt card (46 x 32px, 6px radius) with the entity initials and a red punched ring at its corner, followed by the entity name truncated at 30ch. Links are Archivo 500 15px in ink-2, 8px radius hover chip in a light cool grey. The CA/ES toggle is a bordered 10px segmented control; the pressed language is ink with white text. Under 1060px the links drop into a full-width ground panel at 18px.

### Carnet de soci (signature)
The ID card: paper, 16px radius, 1.586 ratio, rotated -3deg, with a deep-cobalt band (widened uppercase title, yellow typed member number), a dashed photo frame, typed fields on dotted rules (entity name printed instead, two lines max), and a row of quota boxes by year with the first covered by a tilted yellow PAGAT sticker. The stamp sits bottom right with multiply blend and an ink-texture mask. Sizes are container-query relative (cqw) so it scales as one object.

### Ticket (signature)
Agenda event: ground body, 14px radius, cobalt stub with a big widened day numeral and spaced uppercase month, dashed tear line, perforation notches on both edges. The soonest ticket's stub is stamp red. Meta rows pair Phosphor icons with typed text; relative days in stamp-text.

### Coupon (signature)
Join option: paper with a 112px tinted stub (76px on mobile) holding a 46px Phosphor icon behind a dashed tear border, body with a 30px title, short paragraph and a small cobalt button. Coupons stack as sticky cards.

### Stamp (signature)
Circular double-ring rubber stamp in SVG: 6px outer ring, 3px inner ring, ring text on a path at 17px with 3 letter-spacing, centred initials or word in Archivo 800. Rotated -12 to -14deg, 0.9 opacity, multiply blend, masked with the ink texture.

## Do's and Don'ts

### Do:
- **Do** set every date, time, count, field value and user input in Courier Prime; set names, headings and buttons in widened Archivo.
- **Do** place paper objects (paper, 14px radius, soft negative-spread shadow) on cobalt or ground, with a rotation of 3deg or less.
- **Do** keep one quota-yellow primary button per viewport; use cobalt for actions on paper and stamp red only for submitting.
- **Do** use stamp-text (#a8231d) for any red text on paper, and white or cobalt-ink for any text on cobalt.
- **Do** separate with the stationery vocabulary: perforation notches, dashed tear lines, dotted value rules, 1.5px rule-grey dividers.
- **Do** wrap every animation in prefers-reduced-motion: no-preference, and gate scroll-driven effects behind @supports (animation-timeline: view()).
- **Do** use Phosphor regular icons, never emojis.

### Don't:
- **Don't** build the stock NGO page: hero photo of hands, headline and a donate button.
- **Don't** fire the stamp more than once per trigger or use it as decoration on every section; it marks identity, receipt or the studio sign-off.
- **Don't** put boxed, bordered inputs on paper; fields are dotted underlines.
- **Don't** add hard offset shadows, glows or gradients on cards; depth is soft paper shadow and tone.
- **Don't** lift the carnet's uppercase field-caption style into eyebrow labels above section headings; uppercase tracking belongs to printed card parts (carnet captions, ticket month, sticker).
- **Don't** use quota yellow as a section background or as body text on paper.
