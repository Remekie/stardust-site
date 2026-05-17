<!-- stardust:provenance
  writtenBy: stardust:direct
  writtenAt: 2026-05-16T00:00:00Z
  againstPhrase: "the cans are the hero. high contrast — black and white with one pop of color that shifts per event type. tactile and physical, make it feel like you're already at the party. the voice is already right, the design needs to catch up. booking is the only conversion goal — every section earns the scroll toward it. keep the logo and star motif, ditch the Wix whitespace. this is a premium experience product that happens to be affordable, design for the premium not the price."
  readArtifacts:
    - stardust/current/PRODUCT.md
    - stardust/current/DESIGN.md
    - stardust/current/_brand-extraction.json
    - stardust/current/pages/home.json
    - stardust/current/pages/about.json
    - stardust/current/pages/inspiration.json
    - stardust/current/pages/contact.json
  stardustVersion: 0.2.0
-->

# Direction — Poptop Cocktails

## User phrase (verbatim)

> "the cans are the hero. high contrast — black and white with one pop of color
> that shifts per event type. tactile and physical, make it feel like you're
> already at the party. the voice is already right, the design needs to catch up.
> booking is the only conversion goal — every section earns the scroll toward it.
> keep the logo and star motif, ditch the Wix whitespace. this is a premium
> experience product that happens to be affordable, design for the premium
> not the price."

## Dimensional reading

| Dimension | Value | Movement | Source |
|-----------|-------|----------|--------|
| register | brand | pinned | phrase: "booking is the only conversion goal" |
| expressive axis | drenched | strong move → | phrase: "design needs to catch up", "high contrast", "tactile and physical" |
| tone | energetic-premium | move → | phrase: "feel like you're already at the party" + "design for the premium not the price" |
| density | balanced | move ← from airy | phrase: "ditch the Wix whitespace", "every section earns the scroll" |
| distinctiveness | singular | strong move → | the Pour color system is identity-level, not a style preference |
| audience | event hosts 25–42, Edmonton, Instagram-first | inherited + confirmed | captured site: @poptopinc; "Currently Serving Edmonton & Community" |
| constraints | logo+star motif · booking-only CTA · one Pour per event type | pinned | explicit in phrase |

## IA-fidelity

**`reimagined`** — the brief prescribes a new home page section structure
(hero → offer → event types → how it works → social proof → booking CTA).
This is not "keep the structure"; it is a structural redesign within a clear
editorial brief.

Variants at prototype time (A/B/C) may move sections within the brief's spine.
Booking CTA band is locked on every page regardless of variant.

## Divergence seed

| Dimension | Value | How picked |
|-----------|-------|------------|
| Decade | 1950s | deterministic: MD5("Poptop Cocktails2026-05-16") byte[0]=202 mod 10 |
| Craft | Plaster cast | deterministic: byte[1]=34 mod 18 |
| Register | Zine | deterministic: byte[2]=89 mod 17 |
| Ground | stark-white | computed pale-gray → designer override: brief mandates B&W |

### Seed interpretation

**1950s** — Mid-century poster design: bold, graphic, flat color, confident
hierarchy. Type as the structural element, not as decoration.

**Plaster cast** — Physical weight and dimension. Solid fills rather than
thin outlines. The design has presence you can feel — the opposite of Wix's
weightless whitespace.

**Zine** — Direct, punchy, DIY-confident. No apologies. The voice the brand
already has; now the design matches it.

**stark-white** (override) — The "Label" ground: the face of the can is white.
The site reads the same way: clean ground, ink-black type, one pop of event color.

## Design system

**Palette:**
- Can (`#0D0D0D`) — the vessel. Ink-black.
- Label (`#FCFCFC`) — the face. Page ground.
- Pour (`#C8A96E` default/wedding) — the event's identity. Shifts per event type.
- Rim (`#D4D4D4`) — structural quiet.

**Pour color map:** wedding=champagne, corporate=electric blue, mocktail=bright green,
birthday=coral, his-hers=violet, baby-shower=mandarin orange.

**Typography:** Bricolage Grotesque 800 (display) / Hanken Grotesk 400 (body).
Deck: bauhaus-functional, Space Grotesk substituted per reflex-reject rule.

**Motifs:**
- Star (★) from logo: inline, label-size, section eyebrow ornament. One per section.
- Can as hero: product photography IS the image system. No lifestyle stock.
- Alternating Can/Label section grounds: the alternation IS the layout rhythm.

## Anti-toolbox audit

1 hit · 2 off-toolbox moves · 0 rationalizations removed by self-audit.

**Hit:** Dark hero section (Can ground).
**Justification:** The brief mandates "high contrast — black and white". The dark
hero is prescribed, not reflexive. Overall site ground is Label (white); only
hero and CTA band flip to Can. Content-aware, not dark-mode-by-default.

**Off-toolbox moves:**
1. Pour color system — event-type CSS variable. Cannot transfer to non-events
   brands. Requires a product with discrete named categories and a B&W ground.
2. Can/Label/Pour naming — role names from the product's own components.
   Only makes sense for a canned-beverage brand.

## Assumptions (no clarifying questions needed)

1. **Audience equal across event types** — the Pour system implies equal treatment.
   Wedding as default Pour is a visual choice (weddings are the hero event in
   the inspiration gallery), not a marketing priority decision.
2. **Edmonton-local for now** — contact page confirms this; no expansion targeting
   needed in the redesign.
3. **IA-fidelity: reimagined** — the brief provides the home section structure;
   that IS a reimagining. Treated as explicit, not inferred.

## Pages directed

All 4 pages → `directed`. The section spine above applies to home and about.
Inspiration and contact carry their own IA priorities per DESIGN.json.

## Recommended next

```
/stardust prototype home
```

Home page has the most complex brief (6-section spine + Pour system + social proof).
Approve home before running about, inspiration, and contact.
