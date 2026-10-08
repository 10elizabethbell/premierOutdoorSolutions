# Premier Outdoor Solutions — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/premierOutdoorSolutions · **Built:** 2026-10-08 from Muse brief of 2026-10-08 (FB group post "JUNK REMOVAL — NOW SERVING THE AREA!")

## What's built
- **World:** "Get your space back." Deep green ground (their logo's black, made non-black), logo lime as the only action color, a cleared off-white "floor" for the content sections. System font, heavy uppercase.
- **Signature:** a heap of hand-drawn junk (boxes, bags, chairs, mattress, tire, lamp, TV, dresser, armchair, brush bundles) with soft physics along the hero's bottom edge. Mouse or finger shoves it. Flick something up fast, or off a side, and it's **HAULED!** (it spins away, then replacement junk drops in). Autumn leaves (yard debris) drift over it on layered sines and scatter from the pointer. A second, smaller pile sits under the closing section. Section dividers are the logo's three speed stripes, rippling, with the next section's color filling under the middle stripe.
- **Sections:** top bar with logo · hero (headline, pitch, Messenger button, "What we take", logo roundel sitting on the pile) · What we take (5 service rows, each opens Messenger with the service prefilled, plus a "Heavy lifting included" band) · **Ask for a free estimate** builder (chips for what, town, when → composes the message, opens Messenger, copy fallback) · How it works (three big lines: Snap a picture. / Message us. / We haul it.) + their three promises · close (who they help, logo + name, actions, area) · footer with "Demo one-pager — free sample."
- **Contact:** everything goes to `https://m.me/61572063225847` (their page's Messenger; checked that it resolves to a Messenger thread). Prefilled text uses `?text=`. A sticky bottom bar on phones shows once the hero buttons scroll away.
- Tunables are named at the top of each block: `makePile` config (counts, sizes, push radius/force, carry, haul height, respawn, leaves, wind) and the seam constants (`SPEED`, `SWELL`, `RIPPLE`, `GAP`).

## Assumptions I made
- **Area = "Middlesex County, NJ area"**: inferred from where they posted ("Businesses in Middlesex County, NJ") plus "NOW SERVING THE AREA". No towns named. The page says "Not sure if we cover your town? Ask us."
- **Colors** come from their logo (black roundel, lime, white). I swapped the black for deep green per house rule.
- **Logo** = their Facebook profile image. It reads "JUNK REMOVAL" with a truck, not the business name, so the name is set as a wordmark beside it.
- **Service sub-lines** ("Couches, chairs, dressers", "Branches, brush, bagged leaves", etc.; mattresses deliberately left out until the owner confirms them) are my plain-language examples of their verbatim service names. They're the ones to check with the owner first.
- **"We carry it out. You point."** and the How-it-works step copy are my wording built on "Heavy lifting included", "Flexible scheduling" and "send a picture".
- "Takes about 30 seconds" (under the form heading) echoes Muse's suggested hook and describes filling in the form, not their response time.
- Prefilled messages say "I can send a photo" / "I'll send a photo in the chat", never "photo attached", since m.me can't attach anything.
- Placeholder town in the form is "e.g. Edison" (a Middlesex town, used only as a hint).

## Placeholders and gaps
- **No phone or email.** The page says "Estimates go through Facebook Messenger for now" (no promise of a phone line). Once there's a number, add `tel:` + `sms:` buttons (text-to-book module) beside Messenger.
- No work photos, before/afters, reviews, hours, prices. The page says nothing about any of them. The drawn junk pile carries the visuals instead.
- The post's attached promo image wasn't obtainable (og:image of the group post is just the group banner).

## Questions for the owner
- Phone number? Do you take texts?
- Which towns do you cover?
- Hours / days you work?
- Owner's first name (for "Hi <name>" copy and a face/about line)?
- Any job photos, especially before/after cleanouts?
- Anything you *don't* take (paint, tires, appliances, hazardous)?
- Is "Premier Outdoor Solutions" doing other outdoor work too (the name suggests landscaping)? If so, which services?

## Ideas not built (yours to pick)
- From the finish review: hauled items could arc into the logo truck's bed (desktop); leaves could land and settle on the heap; the closing pile could do something different from the hero pile (a second beat).
- **Runner-up world:** leaf-blower sweep. The hero is covered in leaves and debris you blow clear with your finger to reveal the headline. Better if they turn out to do outdoor/yard work too.
- A brush display face matching the logo's "JUNK" lettering for one headline word (house style says system font; craft floor wanted a sourced face).
- Truck drives in and the hauled items fly into its bed instead of fading out.
- Real photo intake: a file input that previews the photo and explains "attach this in Messenger". A true upload needs a backend (Formspree-style) plus their email.
- Before/after slider once they have photos; a reviews strip once they have reviews.
- `book.html` booking form page once there's a phone number.

## Not verified
- The `m.me/…?text=` prefill: Messenger supports it on some clients; if it's ignored, the chat still opens (the copy button covers it).
- Real-device touch feel (tested with simulated touch in headless Chrome), the Facebook in-app browser specifically, clipboard there.
- Frame rate on older phones (phone pile = 16 + 12 items, 9 + 6 leaves).
