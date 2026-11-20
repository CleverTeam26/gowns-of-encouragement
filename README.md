# Gowns of Encouragement — Homepage Rebuild Kit

Everything produced so far for the gownsofencouragement.net homepage rebuild, in one place.
Last updated: 20 Nov 2026.

## Live design canvas (editable)

https://claude.ai/artifact/Dx5S6ztNWPqKTBVgDeMEDJ

Desktop and phone artboards. The Day/Glow toggle, texture filters and "Add" buttons are clickable.
This is the master version; the files in this folder are copies of it.

## What's in this folder

| Folder | Contents | How to use it |
|---|---|---|
| `01-diagnosis/` | `goe-homepage-diagnosis.html`: the conversion review, including what to keep, what to fix, the priority order and the pre-launch checklist | Open in any browser. Prints cleanly to PDF. |
| `02-homepage-mockup/` | `goe-homepage-mockup.html` plus an `images/` folder | Open the HTML in a browser. Keep the `images/` folder next to it or the photos won't show. Standalone copy of the desktop artboard. |
| `03-site-images-original/` | All 16 images pulled from the current site, at original size (about 19 MB in total) | Source files. Renamed by product; the caption strips are still on them. |
| `04-design-canvas-source/` | `Main.dc.html`, `Mobile.dc.html`, `canvas.json` | Backup of the canvas source. They only render inside the design canvas. Their images point to canvas uploads, not this folder. |

## Image notes

- `02-homepage-mockup/images/` holds web-ready copies: 13 WebP files, 860 KB in total, down from about 19 MB. The "ITEM 0X OF 12 …" caption strip baked into each product photo has been cropped off.
- Duplicates on the current site:
  - `goe-black-herringbone-glow.jpg`, `goe-charcoal-herringbone-glow.jpg` and `goe-grey-herringbone-glow.jpg` are the same photo.
  - `goe-grey-herringbone-alt.jpg` is the same as `goe-grey-herringbone-day.jpg`.
- No glow photo exists for Rust-Brown Cable-Knit, Olive Green Bobble, Ivory Honeycomb or Golden Mustard Basket-Weave. The mockup shows "Glow photo needed" on those.
- The hero's day and glow photos show different throws: ivory by day, teal at night.
- `goe-story-champagne-throw.jpg` shows a starry design and a "Luminous Dreams" gift box that aren't in the catalog.
- The photos appear AI-generated. Real product photography, especially of the actual glow, is the biggest remaining upgrade.

## Still to supply (placeholders in the mockup)

- [ ] Real Google reviews: 3 quotes, plus the actual rating and review count
- [ ] Shipping promise and processing time
- [ ] How long the glow lasts, and how long it needs to charge
- [ ] Care and washing instructions
- [ ] Return terms for the 100-night trial
- [ ] Bulk price per item, minimum quantity, custom-order lead time
- [ ] Holiday order-by date
- [ ] Real response time for enquiries
- [ ] Photos: a gown being delivered (mission), Jinetta's portrait, glow shots for the 4 throws above, a 6–8 second lights-off video
- [ ] One real mission number or partner name

## Before launch (outside the homepage design)

- [ ] Connect real checkout (Shopify, or Stripe Checkout or Payment Links). The current checkout is simulated.
- [ ] Start with an empty bag. The current build pre-loads an item.
- [ ] Remove the invented reviews and unsupported claims ("30,000+ reviews", "patented", "Zero Shed 100%")
- [ ] Point the canonical tag at gownsofencouragement.net, and add product schema and a share image
- [ ] Test that every form actually delivers
- [ ] Add GA4 and a Meta pixel with add-to-bag, checkout and lead events
- [ ] Fix the social links so they point to the real profiles
