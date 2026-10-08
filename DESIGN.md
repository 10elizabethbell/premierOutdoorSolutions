---
name: Premier Outdoor Solutions
description: Junk removal pitch page. A shove-able heap of junk on a deep green ground, a cleared paper floor for the content.
colors:
  lime: "#6fd43f"
  lime-hi: "#8be35f"
  lime-ink: "#0c1f12"
  leaf-green: "#2f7a1f"
  ground: "#12261d"
  ground-2: "#183326"
  paper: "#f1efe6"
  paper-2: "#e6e3d6"
  card-white: "#ffffff"
  ink: "#13241c"
  ink-soft: "#43574b"
  on-dark: "#f4f6f1"
  on-dark-soft: "#b8cbbd"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(46px, 13.2vw, 104px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(38px, 10vw, 72px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  statement:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(30px, 8.6vw, 64px)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(20px, 5.6vw, 28px)"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.45
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.1
  roster:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(28px, 8vw, 52px)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  heading:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(26px, 7.4vw, 44px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  card-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(26px, 7vw, 36px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(22px, 6vw, 34px)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.02em"
  micro:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.06em"
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 800
    letterSpacing: "0.04em"
rounded:
  bubble-tail: "4px"
  focus: "6px"
  input: "12px"
  card: "14px"
  panel: "22px"
  pill: "999px"
  round: "50%"
spacing:
  gap-sm: "8px"
  gap: "12px"
  stack: "22px"
  gutter: "20px"
  gutter-wide: "32px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.lime-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.lime-hi}"
    textColor: "{colors.lime-ink}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "56px"
  button-secondary-on-paper:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    height: "56px"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  input:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.input}"
    padding: "0 14px"
    height: "52px"
  input-focus:
    backgroundColor: "{colors.card-white}"
  quote-card:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "22px 18px"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    padding: "12px 2px"
    height: "68px"
  service-go:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.round}"
    size: "40px"
  service-go-hover:
    backgroundColor: "{colors.leaf-green}"
  heavy-callout:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.card}"
    padding: "16px 18px"
  sticky-bar:
    backgroundColor: "{colors.ground}"
    padding: "10px 14px"
---

# Design System: Premier Outdoor Solutions

## Overview

**Creative North Star: "Get Your Space Back"**

The page is the job. A heap of hand-drawn junk sits on a deep green ground and physically reacts to a finger or cursor; fling a piece high enough or off a side and it is hauled away with a "HAULED!" tag, then replaced. Between the heaps, content sits on a cleared off-white "floor". Everything else stays plain and heavy: one lime action color, big white uppercase type, pill buttons, ruled lists.

Phone first and Messenger first. Every surface ends in the lime "Message for a free estimate" button, and a sticky copy of it follows the reader on phones whenever no other copy is on screen.

**Key Characteristics:**
- Deep green ground (the logo's black, made non-black), lime as the single action color.
- Heavy (900) uppercase system type with tight negative tracking.
- Physics junk pile with drifting leaves as the signature, top and bottom of the page.
- Section changes marked by the logo's three speed stripes, rippling.
- Soft, downward, green-black shadows; pills and circles, no sharp corners.

## Colors

Two grounds (deep green, paper) and one loud green that changes shade depending on which ground it stands on.

### Primary
- **Logo Lime** (lime): every primary button, the emphasized word in headlines (`em`), the last line of statement stacks, focus rings on dark, seam stripes on dark, scrollbar, text selection.
- **Lime Flash** (lime-hi): primary button hover and the "HAULED!" canvas tag.
- **Lime Ink** (lime-ink): text and icons on lime only.
- **Leaf Green** (leaf-green): lime's stand-in on paper, where lime fails contrast. Secondary-button border, focus ring, input focus border, service arrow hover, seam stripes on paper, "Copied." confirmation.

### Neutral
- **Deep Ground** (ground): page background, hero, close, footer, sticky bar (at 94% with 10px blur).
- **Ground Two** (ground-2): the How It Works band, one step lighter than ground so the seams read.
- **Cleared Floor** (paper): the What We Take section; also chip and input fill inside the quote card.
- **Swept Paper** (paper-2): service row hover, chip and input borders.
- **Card White** (card-white): the quote builder card and focused inputs; the only pure white surface.
- **Ink** (ink) / **Ink Soft** (ink-soft): text on paper; ink also fills the "go" circles, selected chips, the heavy-lifting callout, and the 2px service rules.
- **On Dark** (on-dark) / **On Dark Soft** (on-dark-soft): text on the green grounds; soft for pitch, notes, footer.

**The Lime Swap Rule.** Lime lives on the green grounds; on paper or white it becomes Leaf Green. The one exception is the lime primary button, which carries its own lime-ink text on any ground.

**The No-Black Rule.** The ground is never black (house rule from PRODUCT.md). Darks are green-tinted.

## Typography

**Display Font:** system UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif). Same stack for everything; no webfonts (PRODUCT.md constraint).

**Character:** Heavy, loud, plain-spoken. Weight and case do the branding; the face stays native and fast.

### Hierarchy
- **Display** (900, clamp 46-104px, lh .95): the hero headline only. One word inside it goes lime.
- **Headline** (900, clamp 38-72px, lh .95): section titles.
- **Statement** (900, clamp 30-64px, lh 1.02): stacked one-line-per-span lists (the three steps, the "who" list at clamp 28-52px). The last line goes lime.
- **Promise** (800, clamp 22-34px, lh 1): the three promises; the middle one goes lime.
- **Title** (900, clamp 20-28px, lh 1.05): service rows; quote card heading runs larger (clamp 26-36px).
- **Body** (400, 17px, lh 1.55): pitch and ledes, capped at 34-44ch.
- **Body Small** (15px): sub-lines under titles, notes, footer (14px).
- **Label** (800, 15px, +.04em, uppercase): form legends and field labels. A 13px uppercase variant (+.04 to .06em) is used for the "Your message" preview label and the "Go on, shove it" pile hint.

**The Heavy Caps Rule.** Every h1-h3 is 900 weight, uppercase, -.02em tracking, line-height .95, `text-wrap: balance`. Small text under a heavy title drops to 500 sentence case.

**The Last Line Lime Rule.** Stacked statements color exactly one line or word lime (the payoff), never more.

## Layout

Phone first, one breakpoint. Base styles are the phone; `min-width: 760px` adds the desktop layout. Content sits in a centered container (1180px max) with 20px gutters on phones and 32px from 760px.

- **Hero:** single column on phones (headline, pitch, stacked full-width buttons capped at 440px, contact note, then the pile). At 760px it becomes a 1.25fr / .75fr grid with the large logo roundel on the right, sunk into the pile; buttons go side by side.
- **What We Take:** service list then quote card on phones; at 760px a 1.1fr / .9fr grid with the quote card sticky at top 24px.
- **How It Works:** promises stack on phones, three auto columns at 760px.
- **Close:** two columns at 760px ("who" list left, logo + actions right), with its own smaller pile underneath.
- **Pile height** is set per section with a `--pile-h` variable: hero 178px phone / 250px desktop, close 150px / 210px. The section reserves that much bottom padding so the pile never covers text.
- **Rhythm:** sections pad 28-40px on phones, 40-64px on desktop. Inside them, 12px between buttons, 14px between headline and pitch, 22px before action groups.
- The footer reserves `96px + safe-area` bottom padding on phones so the sticky bar never covers it.

## Elevation & Depth

Mostly flat color fields separated by seams; depth only where something is physically "lifted": buttons, the quote card, the logo roundels, the junk itself. All shadows are soft, pulled in with negative spread, and fall downward.

### Shadow Vocabulary
- **Lift** (`0 10px 28px -12px rgba(6,20,12,.55)`, token `--shadow`): the heavy-lifting callout and the closing logo.
- **Button** (`0 10px 22px -12px rgba(4,14,8,.7)`): primary buttons.
- **Panel** (`0 18px 40px -20px rgba(19,36,28,.45)`): the quote card on paper.
- **Roundel** (`0 18px 30px -16px rgba(0,0,0,.7)`, desktop `0 30px 60px -30px`): the hero logo.
- **Bar** (`0 -10px 24px -14px rgba(0,0,0,.6)`): the sticky bar, cast upward.
- **Sprite** (canvas `rgba(4,14,8,.42)`, blur 8% of size, offset 4% x / 7% y): every junk sprite.

**The Soft Drop Rule.** Shadows blur and fall down. Never hard-edged, never offset sideways as a graphic device.

## Shapes

Round everything that is touched: pill buttons and chips (999px), circular "go" arrows and logo roundels (50%). Containers get generous corners: inputs 12px, callout 14px, quote card 22px. The message preview is a chat bubble (14px with a 4px bottom-left corner). Lists are not boxed; they are ruled with 2px ink lines top and bottom.

## Components

### Buttons
- **Shape:** full pill, 56px tall (46px in the desktop top bar), 2px lime border on both variants, 800 weight 17px, icon 22px with a 10px gap. Full-width on phones; `nowrap` from 760px.
- **Primary:** lime fill, lime-ink text, Button shadow. The only fill a call to action uses.
- **Secondary:** transparent with lime border and on-dark text; on paper the border becomes leaf-green and text ink.
- **Hover (hover-capable devices only):** lift 2px; primary goes lime-hi, secondary gets a 12% lime wash. **Active:** scale .97. Ease `cubic-bezier(.2,.9,.3,1)`, 180ms.
- **Focus:** 3px lime outline, 3px offset (leaf-green on paper).

### Service Rows
A ruled list, not cards. Each row is a 68px-min link: title-style service name with a 15px sentence-case sub-line, and a 40px ink circle with an arrow at the right. Hover: row fills paper-2, name slides right 10px, circle slides left 6px and turns leaf-green (250ms, same ease). Tapping a row opens Messenger prefilled with that service.

### Heavy-Lifting Callout
Ink block, 14px corners, Lift shadow, a 44px lime lifting icon, a 19px 900 uppercase line and a 15px note.

### Quote Builder
- **Card:** card-white, 22px corners, Panel shadow, 22px/18px padding (30px/28px and sticky at 760px).
- **Chips:** 44px pill labels over hidden checkboxes/radios; paper fill, 2px paper-2 border, 700 15px. Selected: ink fill, paper text. Focus: 3px leaf-green outline. Active: scale .96.
- **Input:** 52px tall, 12px corners, paper fill, 2px paper-2 border; focus swaps border to leaf-green and fill to white (no outline).
- **Preview:** a live chat bubble of the composed message (paper, 15px, pre-wrap) under a 13px uppercase label.
- **Actions:** primary "Send in Messenger" plus secondary "Copy message"; the note below doubles as the polite live region for copy results.

### Seams
The logo's three speed stripes, used as every section divider. An inline SVG (viewBox 1440x80, stretched) 56px tall on phones, 80px from 760px. Three 3px round-capped strokes: outer two in the accent (lime on dark, leaf-green going to paper), middle one in the text color at reduced opacity. The next section's color fills beneath the middle stripe, so the stripe is the edge.

Tuning constants (seam script):
- `SPEED` 1.0: overall tempo.
- `SWELL` [10, 5]: amplitudes of the two shared swells, viewBox units.
- `RIPPLE` 3.2: per-stripe wobble.
- `GAP` 11: spacing between stripes (centered on y 40).
- Each seam is phase-offset by its index so no two ripple alike.

### Junk Pile (signature)
A canvas behind the bottom of the hero and the close. Junk sits in a heap that breathes slightly, scatters from the pointer (mouse hover or touch), and is hauled when flung. A faint lime radial glow sits under the hero pile as the no-JS still.

**Config (`makePile` defaults; close section overrides in brackets):**
- `phoneCount` 16 [12], `deskCount` 40 [26]: items in the heap.
- `phoneSize` [42, 64] [38-56], `deskSize` [56, 96] [50-84]: sprite size range in px. Mattress and brush draw 1.25x.
- `gravity` 2000 px/s².
- `pushRadius` [76, 120]: pointer reach, phone / desktop.
- `pushForce` 2600: outward shove.
- `carry` 1.4: share of pointer velocity passed into items (the fling).
- `haulHeight` [190, 290] [150, 220]: rise above the floor (while still moving up faster than 300px/s) that counts as hauled. Shoving an item past either side edge also hauls it.
- `respawn` 1.6s: delay before replacement junk drops in from 150px (phone) / 240px (desktop) above the floor and fades in over .35s.
- `leaves` [9, 22] [6, 14]: drifting leaves, phone / desktop.
- `wind` 26 px/s: leaf drift.

Phone vs desktop is decided by canvas width under 760px. Items keep a "home" x and spring back to it when they've drifted more than 30px near the floor, so the heap reforms. Side walls hold items unless shoved out at more than 350px/s.

**Sprites:** drawn once per size into an offscreen canvas, solid-shaded with a single linear gradient and a Sprite shadow. Types: box (x3 weight), bag (x2), chair, mattress, tire, lamp, brush bundle, TV, dresser, armchair. Palette is earthy and muted (cardboard #c48b52, wood #8a5a33 / #b07a48, bag charcoal #465350, rust armchair #b65a3f, cream mattress #f1ecdf) so lime stays the only loud color.

**Leaves:** 9-16px almond shapes with a midrib, in five autumn tones (#7fb83a, #a2a83c, #c47e34, #b85a2c, #5c9a2c) at 90% opacity; they flutter (scale-y flip), drift right with the wind, and spring away from the pointer.

**Haul feedback:** a 900-weight lime-hi "HAULED!" (17px phone / 20px desktop) rises 50px and fades over 1.1s; the item spins, shrinks and fades. The first haul hides the "Go on, shove it" hint.

**Performance and motion:** one shared requestAnimationFrame loop; each pile and seam runs only while within 80px of the viewport. Canvas resolution is capped at 2x. With `prefers-reduced-motion`, every canvas and seam paints one settled frame and stays still.

### Sticky Phone Bar
Phones only (hidden from 760px). A fixed bottom bar with one full-width primary button, ground at 94% with 10px backdrop blur, Bar shadow, safe-area padding. It slides up (350ms, the standard ease) only when the hero buttons, the closing buttons and the quote "Send" button are all off screen, so there is never more than one Messenger button competing in view.

### Top Bar
46px logo roundel with a 2px 50%-lime ring, the business name in 900 uppercase 15px with a lime 12px "Junk removal" line under it. The compact "Free estimate" button appears only from 760px.

## Do's and Don'ts

### Do:
- **Do** make lime (on dark) or leaf-green (on paper) the only accent in any view, and end each section with the lime Messenger button.
- **Do** set headings in the system stack at 900, uppercase, -.02em, with one lime word or line as the payoff.
- **Do** separate sections with the three-stripe seam, filling with the next section's color.
- **Do** keep tap targets at 44px or taller (chips 44, inputs 52, rows 68, buttons 56).
- **Do** tune the pile through `makePile` config and the seam constants rather than editing the physics.
- **Do** honor `prefers-reduced-motion` with a still, settled frame for anything that moves.

### Don't:
- **Don't** use a black ground; darks are green-tinted (#12261d family).
- **Don't** put lime text or lime strokes on paper or white; swap to leaf-green.
- **Don't** add a second accent color to the UI. Earthy and autumn colors belong to the junk and leaves only.
- **Don't** box services into cards; they are ruled rows with an arrow circle.
- **Don't** use hard-edged or sideways-offset shadows.
- **Don't** let the pile cover text: any section with a pile must reserve `--pile-h` of bottom padding.
