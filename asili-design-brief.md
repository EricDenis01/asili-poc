# ASILI — Design Brief for Claude Design

*(Working title: "Asili" — Swahili for origin/root. Positioning line: "The Living Archive of African Music.")*

---

## 1. What we're building

A curated digital platform that **connects Africa's musical heritage and contemporary talent with global creative demand**. It brings together older, under-discovered African catalogues (tape era, ~1958–1995) and contemporary African producers — AI-enriched, rights-cleared, and licensable for advertising/TVC, film & TV, games and fashion, with separated stems for DJs, producers and sampling.

**Deliverable from this brief:** a premium proof-of-concept website design (desktop + mobile, light + dark), strong enough to put in front of catalogue partners (rights holders) and international creative buyers.

A working v1 mockup already exists as a reference build — treat it as a starting point to elevate, not a constraint.

## 2. Business context (from the founding brief)

- Four-step model: **(1) Agreement & rights** — transparent 50/50 revenue share with rights holders, licensing rates set by usage, medium and territory (indicative: online ad sync from ~€500); **(2) AI enrichment** — audio analysis and metadata: mood, genre, era, BPM, key, instrumentation, built on an advanced genre/mood taxonomy; **(3) Platform curation** — highlights, easy search and filtering, and the cultural context of artists and catalogues ("a destination, not a track list"); **(4) International sales & market validation** — active outreach to advertising, film, TV, games and fashion; rights holders approve every deal; transparent per-license tracking and quarterly payouts.
- Pilot catalogue partner: **Sintonia** (Luanda, Angola) — 20,000+ Angolan compositions, original recordings from the 1960s on (semba, kizomba, kuduro, African jazz). **Angolan repertoire must be visible in demo content.**
- North star: *"Reactivate Africa's musical heritage, create new economic opportunities for rights holders and artists, and put African music further into the global creative spotlight."*

## 3. Audiences

1. Music supervisors and agencies (advertising/TVC, film & TV) — primary buyers
2. Game audio directors (adaptive audio, loops, stems)
3. Fashion houses (runway edits, campaign films)
4. DJs and producers (edits, flips, cleared sampling)
5. **Rights holders** — labels' vaults, families, estates; for them the design must radiate trust and control
6. Meta-audience: partners and investors viewing the proof of concept

## 4. Competitive frame

- **biblo.tv** — "Africa's most innovative sync label"; bold typography, mood-first search, stems on every track.
- **syncallmusic.com** — "The Home of African Sound"; broad African licensing marketplace with metadata enrichment.
- Neither owns these four differentiators — the design must make them unmissable:
  1. Heritage + cultural context (curated destination, editorial storytelling)
  2. Deep AI analysis (musimap-style emotional/mood intelligence)
  3. Stems on every track
  4. Radical rights-holder transparency (50/50, approvals, live tracking)

## 5. Primary aesthetic reference

**too-young.com** (music supervision house for fashion/luxury):
- Vast negative space on an ivory ground; near-monochrome
- One giant, edge-to-edge condensed wordmark
- Tiny tracked-out uppercase micro-labels; hairline rules; hairline-boxed buttons
- A single handwritten ink gesture ("Est. 2010.") as the only human mark

Secondary tone references: luxury-house lookbooks; museum exhibition catalogues (engraved plates with captions); scientific instrument panels.

## 6. Design concept — "The Couture Archive"

Three registers, kept strictly separate and each done perfectly:

1. **The couture shell** (the site itself): ivory, condensed display caps, serif-italic whispers, hairlines, extreme whitespace. Sleek, premium, classy.
2. **The heritage** (the music): African geometric art traditions rendered as fine-line museum engravings — ink on plate paper. Never colorful "ethnic" pastiche.
3. **The instrument** (the AI): SaaS-grade data UI at micro scale — mono type, gauges, badges, scanlines, typing readouts. Lab instrument, not sci-fi.

## 7. Visual language

### Palette (light theme is primary)
| Token | Value | Use |
|---|---|---|
| Ivory ground | `#F3F0E7` | page |
| Raised ivory | `#FAF8F0` | cards/panels |
| Warm ink | `#16140F` | type, strong borders, inverse band |
| Hairline | `#D8D2C0` | rules, dividers |
| Bronze | `#8A6B2F` | THE single accent |
| Plate paper | `#F7F4EB` / ink `#1A1712` | engravings (fixed in both themes) |

Dark theme: ink ground `#131109`, ivory type `#EBE6D6`, bronze lifts to `#C09A4A`; the rights-holder band inverts to ivory-on-ink→ink-on-ivory.

Rules: one accent color only; status/states expressed with bronze + hairlines (no red/green); no gradients; no rounded corners; no drop shadows except one soft ambient under framed instrument panels.

### Typography
- **Display:** Anton (Druk-adjacent condensed caps) — wordmark, section headings, registry titles, prices. Tight leading (~1.02).
- **Editorial:** Cormorant Garamond italic — section ledes, artist bylines, mood words, the CTA ("Hear it first.").
- **Data/AI:** Fragment Mono — micro-labels at 9–11px, letter-spacing 0.14–0.3em, uppercase.
- **Body:** Archivo 400/500.
- **Gesture:** Homemade Apple (handwriting) — maximum two uses per page (hero "est. 1958 — now.", footer tagline "every sound has an origin.").

### Heritage art system (the "engraving plates")
Geometric textile/architectural traditions mapped to regions, drawn as 1–2px ink line engravings on plate paper, with an etched border, corner registration ticks, and exactly one small bronze diamond accent per plate:
- **West Africa** — bogolan/mudcloth lozenge grids
- **Central Africa** — Kuba-cloth interlace zigzags
- **East Africa** — chevron and triangle bands
- **Southern Africa** — Ndebele stepped frames
- **North Africa** — eight-point star / zellige radials

Used as: track artwork ("plates" with museum captions, e.g. `PLATE AS-74-631 · WEST AFRICA · ENGRAVED FROM ¼" MASTER`), artist portrait placeholders, and sparing section ornaments.

**Dignity rules (hard):** no masks-as-decoration, no animal prints, no safari/sunset imagery, no "tribal display fonts", no brown-orange "world music" palettes. Genre, geography and era accuracy always — the heritage is treated like a museum treats a master drawing.

### AI / SaaS design language
- **Instrument panel** per track: hairline oscilloscope waveform; six-axis "emotional print" polar chart (Joy / Tension / Nostalgia / Sensuality / Power / Serenity); hairline gauges for energy/danceability with bronze fill; mono readouts (BPM · KEY · INSTR); boxed badge `AI ANALYSIS · v2.4`; the analysis paragraph types itself with a cursor.
- **Ambient tech:** a slow 1px bronze scanline sweeping the hero wordmark; a rotating mono status line (`ANALYSING — "KAXEXE" · LUANDA 1973 · 112 BPM · D MAJOR`); `● LIVE` ticks on the dashboard.
- Everything data-related = Fragment Mono inside hairline frames. **Never:** glassmorphism, neon glows, particles, "AI sparkle" icons, chatbot imagery.

### Motion
Few, slow, precise: scanline sweep (~7s), typing readout, 12px scroll-reveals (~0.7s), genre ticker (80s loop). Every animation has a `prefers-reduced-motion` fallback.

## 8. Voice & copy rules

- Confident, editorial, short. Crate-digger authority in couture cadence.
- Use the founding lingo verbatim where possible: "connecting Africa's musical heritage and contemporary talent with global creative demand" · "quality, cultural relevance and artistic value" · "discover, explore, license and collaborate" · "advanced genre and mood taxonomy" · "cleared tracks with stems, ready to drop into your project" · "TVC and film".
- **Never say "marketplace."** Say: living archive, platform, catalogue, registry, destination.
- Transparency claims stay concrete: 50/50, quarterly payouts, you approve every deal.

## 9. Page architecture (single-page PoC)

1. **Hero** — near-empty ivory; centered micro-caption (the founding line); handwritten "est. 1958 — now."; rotating ANALYSING status; giant edge-to-edge ASILI with scanline; four stat columns (1,204 works / 17 countries / 1958–now / 100% cleared, stems).
2. **Genre ticker** — mono micro caps, bronze ◆ separators (Highlife … Semba, Kizomba, Kuduro, Amapiano…).
3. **The Intelligence** — instrument panel with featured-track switcher.
4. **The Registry** — the catalogue as couture-credits rows (no thumbnails): index number, Anton title + serif artist, right-aligned mono meta (city, year, genre in bronze, BPM, key). Filters as tiny text toggles: REGION / ERA / MOOD. Clicking a row loads it into the instrument.
5. **Stems** — four-lane hairline mixer (Vocals, Drums & perc, Bass, Guitars & horns), MUTE/SOLO, thin bronze playhead.
6. **Who digs here** — five buyer doors (Advertising, Film & TV, Games, Fashion, DJs & Producers) + three serif-led use cases (Cleared before you ask / Built for the booth / Sample at the source).
7. **How a catalogue joins** — rows 01–04 (Agreement & rights, AI enrichment, Curation & context, International sales).
8. **Licensing** — Crate from €150 / Screen from €500 (most licensed) / Marquee from €3,500; note: indicative, scales by usage, medium, territory; every license splits 50/50.
9. **Rights holders** — full-bleed inverse ink band; headline "Bring us your catalogue. Keep your control."; dashboard mock: per-license table (fee / your share / PAID / TO APPROVE), 50/50 split bar, next payout.
10. **Cultural context** — three artist spotlights with portrait-format engraving plates.
11. **Story + ethics** — "From vault to living archive" + bronze-framed "The source gets paid."
12. **CTA + footer** — serif italic "Hear it first.", underline email input, boxed button; footer with handwritten tagline and the placeholder-content disclaimer.

Phase-2 screens (optional concepts welcome): track detail page, search results, licensing checkout, rights-holder dashboard app, artist page, FR/PT localization.

## 10. Content truths & constraints

- All artist names, tracks, labels and dashboard figures in the PoC are **fictional placeholders**; genres, cities and eras are real. A visible disclaimer must remain.
- A 27-track sample catalogue with full metadata exists (incl. Angolan semba, kizomba, kuduro) and should be used as real content — no lorem ipsum.
- Currency: euros. Prices always marked indicative.
- No real partner names/logos without approval.
- Accessibility: AA contrast in both themes, visible focus states, reduced-motion variants, real text (never type-as-image).

## 11. Deliverables requested

1. Desktop (1440) and mobile (390) designs of the one-page PoC
2. Light and dark themes
3. Component sheet with states (hover, active, focus, muted stem lane, PAID / TO APPROVE pills)
4. The five regional engraving-plate styles as a reusable illustration system
5. Optional: track-detail page and rights-holder dashboard concepts

## 12. Success criteria

- Reads as premium/fashion-grade within 3 seconds — would sit comfortably next to too-young.com
- African heritage feels honored and specific, never costumed
- The AI reads as precision instrumentation, not gimmickry
- A rights holder would trust it with their masters; a music supervisor would want to search it
