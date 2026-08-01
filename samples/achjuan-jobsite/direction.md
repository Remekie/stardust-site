---
_provenance:
  writtenBy: stardust:uplift (freeform-intent route)
  writtenAt: 2026-08-01
  againstInput: "run stardust against this site and get 3 new variations"
  mode: free-directions (user-selected)
  stardustVersion: 0.12.0
  toolkitVersion: "v1.0 (stardust v2)"
---

# Direction — Achjuan Remekie-Hall jobsite

## Resolved intent

Three genuinely different propositions for a one-page hiring surface whose only
job is to make a foreman call a phone number. The user declined Mode A
brand-faithful pinning because the captured identity is substantially composed of
assistant-default moves — so each variant re-picks ground, palette and type deck
from the divergence seed.

## Movements

- register:        brand (design IS the product — personal marketing surface)
- expressive axis: committed (inherited)
- tone:            serious (inherited)
- density:         **moves → 48–56px.** Conversion-verb CTA above fold; captured
                   6rem × 5 short sections reads as whitespace-as-padding.
- distinctiveness: **moves → distinctive.** Free-directions mode.
- ia-fidelity:     reimagined
- audience:        hiring foreman / shutdown coordinator / dispatcher,
                   Edmonton–Nisku–Fort Saskatchewan corridor. On a phone.
                   ~20 seconds. Needs a tappable number and a ticket list.
- constraints:     no-fabricated-content (hard), IA-priority preservation (§8,
                   commercial-conversion trigger — call path stays first-viewport
                   and most prominent in every variant)

## Divergence seed

```
md5("Achjuan Remekie-Hall|2026-08-01") = 8c59ed94735fb1b2f2efd42a6cef6b55
decade   = byte0(140) % 10 = 0  → 1920s
craft    = byte1(89)  % 18 = 17 → Mosaic tile
register = byte2(237) % 17 = 16 → Hospital discharge paperwork
ground   = byte3(148) % 6  = 4  → dark          (variant A)
           byte4(115) % 6  = 1  → stark-white   (variant B)
           byte5(95)  % 6  = 5  → monochrome-tint (variant C)
picked_by: deterministic
```

Cream-family check: **0 of 3 variants hit.** A `#0B1B2E` (L too low), B `#FFFFFF`
(L=100, R−B=0), C `#D9DDE0` (R−B = −7, cool). All pass.

Per §2.5 dimension dominance, each variant lets one seed dimension lead and
matches it to the ground that serves it.

## Variant A — decade-dominant · 1920s cyanotype

Ground: `dark` — blueprint blue-black, deliberately **not** the captured `#151515`
charcoal.
What if: *"the page were the drawing he reads for a living?"*
Captured trait: blueprint interpretation (named 4× in résumé, 1 tile on site).
Type deck: `bauhaus-functional` with the reflex swap Space Grotesk → **Bricolage
Grotesque**; **Martian Mono** for annotations; **Hanken Grotesk** body.
Composition: drafting sheet. Dimension rules, tick marks, callout leaders,
authored isometric spool SVG as hero. The orphan `border-left: 6px` becomes the
structural rule system.
Motion: static.
Stakeholder pitch: *"the trade, rendered in its own visual language."*

## Variant B — register-dominant · clearance record

Ground: `stark-white` — bond paper.
What if: *"the page were his clearance record, not his life story?"*
Captured trait: the ticket set (9 pills buried at the bottom of section 2).
Type deck: `bureaucratic` — **IBM Plex Serif** body, **IBM Plex Mono** field codes,
**IBM Plex Sans Condensed** dense labels. (Plain IBM Plex Sans is reflex-rejected
and is not used.)
Composition: ruled form rows, issue/expiry columns, CLEARED status band, signature
block. Voice pivots third-person CV prose → terse dispatch.
Motion: static.
Stakeholder pitch: *"hand a foreman the paperwork before he asks for it."*

## Variant C — craft-dominant · mosaic tessellation

Ground: `monochrome-tint` — cool concrete slate.
What if: *"the page showed the whole composite instead of apologising for it?"*
Captured trait: multi-trade breadth (5 roles, 2 provinces, flattened to a uniform grid).
Type deck: **Archivo Black** display, **Archivo** body, **Courier Prime** technical.
Composition: weighted tessellation — every trade, ticket and role is a tile sized
by actual weight rather than a uniform cell.
Motion: static.
Stakeholder pitch: *"range as an asset, not a liability."*

## Variant differentiation contract

| Pair | Ground | Type deck | Layout primitive | Section sequence | Total |
|---|---|---|---|---|---|
| A ↔ B | ✓ | ✓ | ✓ | ✓ | 4 |
| A ↔ C | ✓ | ✓ | ✓ | ✓ | 4 |
| B ↔ C | ✓ | ✓ | ✓ | ✓ | 4 |

All pairs clear the ≥2 floor. No variant is defined as "the previous one but
more" — each is anchored to a *different* captured trait, so the C-cliff failure
mode does not apply.

## Anti-toolbox audit

Dropped from the captured build: grain/scanline overlay, dark-by-reflex ground,
uppercase-condensed primary display, Manrope body. Refused during authoring:
sticky top nav (captured site has no nav — not adding one), rotated circular
"CLEARED" stamp in B (§1 motif move — replaced with a rectangular ruled clearance
box), oversized display numerals as section markers (replaced with form field
codes), stat-callout bar (would require fabricated numbers), 45° hazard stripes.

`anti_toolbox_count: 0` claimed hits requiring justification.

Reflex-reject font pre-flight: **0 hits across all three variants.**

## Content sourcing

All content ground-truthed against `updated-resume-copy.txt`. Contact confirmed by
user: `1-647-907-4354` / `achjuankaribe@gmail.com`. Safety tickets limited to the
six certified; CSO / LOTO / FLHA-familiarity removed pending confirmation (see
`uplift-improvements.md` § Integrity finding). No invented stats, dates, employers
or dollar figures. Photo slots reserved as `[data-placeholder]` pending Firefly
org access.
