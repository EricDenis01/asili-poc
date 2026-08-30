# PROMPT FOR CLAUDE DESIGN — paste everything below this line

Design a premium, single-page proof-of-concept website called **ASILI** — "The Living Archive of African Music" — in desktop (1440) and mobile (390), in light and dark themes. It is a curated platform connecting Africa's musical heritage and contemporary talent with global creative demand: heritage catalogues (tape era, 1958–1995) and contemporary African producers, AI-enriched, rights-cleared, licensable for advertising/TVC, film & TV, games and fashion, with separated stems for DJs and producers.

The design must feel **sleek, premium, classy** — fashion-house minimalism — with **African heritage rendered as museum-grade engravings** and **SaaS/instrument-grade tech touches for the AI**. Never a music-stock-library look, never "world music" pastiche, never sci-fi AI clichés.

---

## 1. CONCEPT — "The Couture Archive"

Three registers, kept strictly separate, each executed perfectly:

1. **The couture shell** (the site): ivory ground, vast negative space, condensed display caps, serif-italic whispers, hairline rules, hairline-boxed buttons, tiny tracked-out uppercase mono micro-labels, one handwritten ink gesture. Reference the visual grammar of too-young.com: a nearly empty hero with a tiny centered caption and one giant edge-to-edge condensed wordmark pinned at the bottom.
2. **The heritage** (the music): African geometric art traditions drawn as fine-line ink engravings on plate paper — like master drawings in a museum catalogue. This replaces all album artwork and photography.
3. **The instrument** (the AI): SaaS-grade data UI at micro scale — monospace type, hairline gauges, boxed badges, a scanline, typing readouts. A lab instrument, not a chatbot and not neon sci-fi.

## 2. DESIGN TOKENS

Palette (light theme is primary; exactly ONE accent color):
- Ivory ground `#F3F0E7`, raised ivory panels `#FAF8F0`
- Warm ink `#16140F` (type, strong borders, the inverse band)
- Hairline `#D8D2C0`
- Bronze `#8A6B2F` — the single accent (active states, data highlights, the scribble, scanline, one accent per engraving)
- Plate paper `#F7F4EB` with plate ink `#1A1712` (fixed in both themes)
- Dark theme: ground `#131109`, type `#EBE6D6`, hairline `#2C2818`, bronze lifts to `#C09A4A`; the rights-holder band inverts (ivory band, ink text)

Hard rules: no gradients, no rounded corners, no colored status colors (no red/green — states use bronze + hairlines), no drop shadows except one soft ambient under the framed instrument panel.

Typography (Google Fonts):
- **Anton** — display: wordmark, section headings, registry titles, prices. Uppercase, tight leading (~1.02).
- **Cormorant Garamond italic** — editorial: section ledes, artist bylines, mood words, the CTA headline.
- **Fragment Mono** — all data/AI/micro-labels: 9–11px, letter-spacing 0.14–0.3em, uppercase.
- **Archivo** 400/500 — body text.
- **Homemade Apple** — handwritten gesture, maximum two uses on the page.

## 3. HERITAGE ART SYSTEM — "engraving plates"

All track/artist artwork is a square or portrait "plate": 1–2px ink line-work on plate paper, an etched border, tiny corner registration cross-ticks, and exactly ONE small bronze diamond accent. Motif family follows the music's region:
- West Africa — bogolan/mudcloth lozenge grids
- Central Africa — Kuba-cloth interlace zigzags
- East Africa — chevron and triangle bands
- Southern Africa — Ndebele stepped frames
- North Africa — eight-point star / zellige radials

Each plate carries a museum caption in mono micro, e.g. `PLATE AS-74-631 · WEST AFRICA · ENGRAVED FROM ¼" MASTER`.

**Dignity rules (never break):** no masks-as-decoration, no animal prints, no safari/sunset imagery, no "tribal" display fonts, no brown-orange "world music" palettes, no Africa-continent-shaped icons. Genre, city and era accuracy always.

## 4. AI / SAAS DESIGN LANGUAGE

- **Instrument panel** (the AI analysis card): hairline oscilloscope waveform; a six-axis "emotional print" polar chart (axes: Joy, Tension, Nostalgia, Sensuality, Power, Serenity) drawn in hairlines with bronze dots; 1px gauges with a 3px bronze fill for Energy and Danceability; mono readouts `BPM 119 · KEY E MINOR · INSTR TENOR SAX · BARITONE SAX · TRUMPET`; a boxed badge `AI ANALYSIS · v2.4`; the analysis paragraph appears with a typing cursor.
- **Ambient tech:** a slow 1px bronze scanline sweeping vertically across the hero wordmark (~7s loop); a rotating mono status line under the hero caption, cycling real tracks: `● ANALYSING — "KAXEXE" · LUANDA 1973 · 112 BPM · D MAJOR`; a `● LIVE` tick on the dashboard.
- Motion overall: few, slow, precise — scanline, typing readout, 12px scroll-reveals (~0.7s), an 80s-loop genre ticker. Everything needs a reduced-motion fallback.
- Never: glassmorphism, neon glows, particles, sparkle icons, robot/chatbot imagery.

## 5. VOICE & COPY RULES

Confident, editorial, short — crate-digger authority in couture cadence. Use this founding language verbatim where it fits: "connecting Africa's musical heritage and contemporary talent with global creative demand" · "quality, cultural relevance and artistic value" · "discover, explore, license and collaborate" · "advanced genre and mood taxonomy" · "cleared tracks with stems, ready to drop into your project" · "TVC and film". **Never use the word "marketplace"** — say living archive, platform, catalogue, registry, destination. Keep transparency concrete: 50/50 split, quarterly payouts, you approve every deal.

## 6. PAGE STRUCTURE & CONTENT (use this real content — no lorem ipsum)

### 6.1 Top bar
Left: `ASILI` (Anton, small). Right, mono micro links: ANALYSIS · REGISTRY · STEMS · LICENSING · RIGHTS HOLDERS · STORY, plus a hairline-boxed button `REQUEST ACCESS`.

### 6.2 Hero (~92vh, nearly empty)
- Centered micro-caption: `CONNECTING AFRICA'S MUSICAL HERITAGE & CONTEMPORARY TALENT WITH GLOBAL CREATIVE DEMAND`
- Handwritten bronze scribble below it: `est. 1958 — now.`
- Rotating analysing status line (see §4)
- Bottom: giant edge-to-edge `ASILI` wordmark (Anton) with the bronze scanline sweeping it
- Under the wordmark, a hairline-divided 4-column stat strip:
  `1,204 WORKS / ingested & enriched` · `17 COUNTRIES / heritage & contemporary` · `1958 — NOW / tape era to this week` · `100% CLEARED / stems on every track`

### 6.3 Genre ticker
Slow mono micro ticker with bronze ◆ separators: HIGHLIFE ◆ SOUKOUS ◆ ETHIO-JAZZ ◆ MBALAX ◆ ZAMROCK ◆ BENGA ◆ TAARAB ◆ MBAQANGA ◆ GNAWA ◆ WASSOULOU ◆ CHIMURENGA ◆ MAKOSSA ◆ JUJU ◆ BUBBLEGUM ◆ AFROBEAT ◆ SEMBA ◆ KIZOMBA ◆ KUDURO ◆ AMAPIANO ◆ ALTÉ ◆ DESERT ROCK ◆ 3-STEP ◆ COUPÉ-DÉCALÉ

### 6.4 THE INTELLIGENCE (section label: "THE INTELLIGENCE")
- H2: `EVERY REEL, READ DEEPLY.`
- Serif italic lede: "Our AI listens the way a supervisor does — then goes further. Mood and emotion, tempo and key, energy and instrumentation: an advanced taxonomy that turns thousands of hours of tape into a searchable instrument. **Type a feeling, get a record.**"
- Featured-track switcher (mono text tabs), then the **instrument panel**, two columns:
  - Left: engraving plate + caption + hairline archive fields table (RECORDED / LABEL / SOURCE / DURATION / RIGHTS)
  - Right: Anton track title, serif byline, AI badge, waveform, emotional print, gauges, mood words in serif italic ("— defiant — hypnotic — simmering — righteous"), typing analysis text, and `SUGGESTED PLACEMENT` line
- Featured track example (use fully): **Ìjọba Kò Gbọ́** — Ayọ Okunola & the Surulere Express — Afrobeat · Lagos, Nigeria 1974 · Apapa Records · 119 BPM · E minor · 11:42 · energy 85 · danceability 88 · moods: defiant, hypnotic, simmering, righteous · analysis: "A slow-boil one-chord vamp built on a skeletal tenor-guitar ostinato and clipped horn stabs, withholding the full brass theme until past the four-minute mark before erupting into chanted call-and-response. Raw desk mix with audible room bleed gives it a charged, documentary-era grit." · placement: "Protest montage, gritty street-culture documentary" · rights: "Master + publishing · pre-cleared"

### 6.5 THE REGISTRY (the catalogue — a list, not a card grid)
- H2: `DIG FOUR DECADES — AND THIS WEEK.`
- Serif lede: "A curated selection of heritage recordings and contemporary African productions, chosen for **quality, cultural relevance and artistic value** — researched, rights-identified and enriched, so an international audience can discover, explore, license and collaborate."
- Filters as mono text toggles (active = bronze underline): REGION: ALL WEST CENTRAL EAST SOUTHERN NORTH · ERA: ALL '58–'69 '70S '80S–'95 NEW · MOOD: ALL HYPNOTIC ROMANTIC BROODING BUOYANT NOCTURNAL RAW FESTIVE DEFIANT WARM
- Count line: `SHOWING 27 OF 27 RECORDINGS — PROOF-OF-CONCEPT SAMPLE OF THE FULL CATALOGUE`
- Rows: index number (mono, bronze when active) · Anton title with serif-italic artist beneath · right-aligned mono meta (CITY, COUNTRY YEAR / genre in bronze · BPM · key). Sample rows:

| # | Title — Artist | Meta |
|---|---|---|
| 001 | Ìjọba Kò Gbọ́ — Ayọ Okunola & the Surulere Express | LAGOS, NIGERIA 1974 · AFROBEAT · 119 BPM · E MINOR |
| 002 | Ayé Ń Yí — Chief Bọ́lá Ọṣúnwálé & His Rainbow Rhythm Aces | IBADAN, NIGERIA 1979 · JUJU · 108 BPM · G MAJOR |
| 003 | Ɔdɔ Refrɛ Me — Osei Kwame & the Meridian Dance Band | ACCRA, GHANA 1963 · DANCE-BAND HIGHLIFE · 102 BPM · F MAJOR |
| 004 | Jàmm Rekk — Ibrahima Mbaye et l'Étoile de Médina | DAKAR, SENEGAL 1982 · MBALAX · 128 BPM · D MINOR |
| 005 | Sinjiya — Mariam Diakité | BAMAKO, MALI 1978 · WASSOULOU · 84 BPM · G MINOR |
| 006 | Nzela Na Ngai — Orchestre Super Lipopo | KINSHASA, DR CONGO 1976 · SOUKOUS/RUMBA · 134 BPM · A MAJOR |
| 007 | Yelelit Guzo (Night Journey) — Dawit Mengesha Sextet | ADDIS ABABA, ETHIOPIA 1971 · ETHIO-JAZZ · 96 BPM · C MINOR |
| 008 | Mahaba ya Bahari — Bi Mwanaisha Salum & Nyota za Pwani | STONE TOWN, ZANZIBAR 1968 · TAARAB · 84 BPM · G MINOR |
| 009 | Copperbelt Woman — Mukuba Lightning | KITWE, ZAMBIA 1976 · ZAMROCK · 112 BPM · E MINOR |
| 010 | Jaiva Tonight — Thandi V | SOWETO, SOUTH AFRICA 1987 · BUBBLEGUM SYNTH-POP · 116 BPM · F MINOR |
| 011 | Layl El Bhar — Maâlem Brahim Zouani | ESSAOUIRA, MOROCCO 1979 · GNAWA · 102 BPM · A MINOR |
| 012 | Kaxexe — Elias Kanda e os Astros do Prenda | LUANDA, ANGOLA 1973 · SEMBA · 112 BPM · D MAJOR |
| 013 | Noite da Ilha — Lúcia Mavinga | LUANDA, ANGOLA 1988 · KIZOMBA · 92 BPM · B MINOR |
| 014 | Emakhaya (Log Drum Prayer) — Sgubhu Avenue feat. Nolwazi K | PRETORIA, SOUTH AFRICA 2023 · AMAPIANO · 112 BPM · C# MINOR |
| 015 | Ehad n Agadez — Taghlamt Assouf | AGADEZ, NIGER 2022 · TUAREG DESERT ROCK · 132 BPM · E MINOR |
| 016 | Batida do Musseque — DJ Zango & Puto Fogo | LUANDA, ANGOLA 2023 · KUDURO · 140 BPM · F MINOR |

(Continue the pattern to 27 rows if needed; Angolan repertoire must stay visible.)

### 6.6 STEMS (label: "STEM SEPARATION")
- H2: `PULL THE TAPE APART.`
- Lede: "Source separation tuned for tape-era recordings lifts vocals, drums, bass and melodic instruments out of mono masters — clean, labelled, key-matched. **What was frozen on reel-to-reel for fifty years is now yours to rearrange.**"
- A hairline-framed mixer: header with circular outline play button, track "COPPERBELT WOMAN / Mukuba Lightning · Kitwe, Zambia, 1976" and `112 BPM · E MINOR · 4 STEMS`; four lanes (VOCALS / DRUMS & PERC / BASS / GUITARS & HORNS), each: mono label + `24-BIT WAV · KEY-MATCHED`, a hairline oscilloscope trace, boxed MUTE and SOLO buttons (pressed = ink fill). A thin bronze playhead. Footer: "Preview updates as you mute and solo. Stems export as 24-bit WAV, tempo-mapped and tagged for your DAW." + boxed `DOWNLOAD STEMS`.

### 6.7 WHO DIGS HERE
- H2: `ONE ARCHIVE. FIVE DOORS IN.`
- Five columns, each with a short bronze tick above an Anton micro-heading:
  - ADVERTISING — "Sounds no competitor has touched, cleared for global campaigns in days — with a real story behind every track to match your brand's."
  - FILM & TV — "Period-authentic recordings and contemporary scores with verified chain of title, so sync clearance never stalls your edit."
  - GAMES — "Stems, loops, and precise BPM and key data built for adaptive audio engines — soundtrack living worlds with living music."
  - FASHION — "Runway and campaign selections curated by mood and era, from 1970s Accra brass to Johannesburg's midnight piano."
  - DJS & PRODUCERS — "Legally cleared stems and samples from heritage masters — build on the source, and the originators share in every royalty."
- Below, three serif-italic-led columns: "Cleared before you ask." / "Built for the booth." / "Sample at the source." (short paragraphs on instant clearance, edit licensing, sample clearance with provenance).

### 6.8 HOW A CATALOGUE JOINS
- H2: `FROM VAULT TO THE WORLD.`
- Four hairline rows, numbered 01–04 in bronze Anton:
  1. AGREEMENT & RIGHTS — "Every catalogue journey starts with a clear, plain-language agreement: we verify ownership and chain of title together and set the terms of our 50/50 partnership. You retain ownership of your masters at all times — we earn the right to represent them."
  2. AI ENRICHMENT — "We digitize and restore every recording to modern broadcast standards, then our AI pipeline maps each track's mood, genre, BPM, key and instrumentation. A box of unlabeled reels becomes a searchable catalogue any music supervisor can navigate in seconds."
  3. CURATION & CONTEXT — "Our editors research each recording's history and write the cultural context that gives it meaning — the scene, the city, the moment it captured. Tracks are placed into curated collections where the right buyers actually discover them."
  4. INTERNATIONAL SALES — "We pitch your catalogue to advertising agencies, studios, game developers and fashion houses worldwide — and you approve every license before it is signed. Payouts arrive quarterly, with a per-license statement showing exactly who used what, where, and for how much."

### 6.9 LICENSING
- H2: `TRANSPARENT RATES. NO MYSTERY.`
- Lede: "Pricing scales with usage, medium and territory — published up front, so a bedroom producer and a global agency both know exactly where they stand."
- Three hairline-divided tier columns (Anton names, bronze mono prices, serif audience line, ◆ feature lists, boxed CTA):
  - CRATE — from €150 / track — producers, beatmakers and DJs (stems, one-release clearance, tempo-mapped WAV, automatic royalty split)
  - SCREEN — from €500 / use — brands and agencies, online video & social (marked `MOST LICENSED`; worldwide web+social 1-year, instant license + cue sheet, AI-matched alternates, stems included)
  - MARQUEE — from €3,500 / quote — supervisors placing TVC, broadcast, film and global campaigns (all-media rights, dedicated clearance specialist 48h, early vault access, custom delivery)
- Footnote (mono micro): `RATES ARE INDICATIVE AND SCALE BY CAMPAIGN SIZE, DURATION, TERRITORY AND MEDIA · EVERY LICENSE SPLITS 50/50 WITH THE RIGHTS HOLDER · CUSTOM QUOTES IN 48H`

### 6.10 RIGHTS HOLDERS (full-bleed inverse ink band)
- H2: `BRING US YOUR CATALOGUE. KEEP YOUR CONTROL.`
- Lede: "A label's vault, a family estate, one artist's life work: we digitize and restore every recording, enrich it with world-class metadata, clear the rights and sell licenses on five continents. Nothing is signed without you. **Your masters stay yours; we put them to work.**"
- Four trust points (◆): transparent per-license tracking · 50/50 share, no hidden deductions · you approve every deal · quarterly payouts with full statements.
- Beside it, a hairline **dashboard mock**: header `RIGHTS HOLDER DASHBOARD · Q3 2026` + `● LIVE`; table columns TRACK/USE · TERRITORY · FEE · YOUR SHARE · STATUS with rows: Nzela Na Ngai (streaming campaign, beverage brand, EU, €4,200 / €2,100, PAID) · Jaiva Tonight (fashion film, worldwide, €790 / €395, PAID) · Sinjiya (documentary feature, N. America, €1,500 / €750, TO APPROVE); a 50/50 split bar (bronze vs dim); footer `NEXT PAYOUT · OCT 15, 2026` with `€3,245` in bronze Anton.

### 6.11 CULTURAL CONTEXT
- H2: `NOT A TRACK LIST. A DESTINATION.`
- Lede: "Every catalogue arrives with its story — the scenes, cities and lives behind the sound — researched with rights holders and presented alongside the music."
- Three spotlight cards, portrait engraving plate + bronze mono origin line + Anton name + short story:
  - KWESI AMANKWAH & HIS COASTLINE DANCE BAND — Accra, Ghana · 1967–1979 — highlife bandleader; master tapes presumed lost in 1980, recovered from a family storeroom in Osu and restored.
  - ZEWDITU GETAHUN — Addis Ababa, Ethiopia · 1971–1977 — tezeta voice of Addis nightlife; cut only nine sides before curfews silenced the clubs; digitized here for the first time.
  - KATLEGO "KAT MOTION" DLAMINI — Soweto, Johannesburg · 2019–present — amapiano producer, gospel-schooled voicings over log-drum bass; cleared stems fuel edits from Lagos to London.

### 6.12 STORY + ETHICS
- H2: `FROM VAULT TO LIVING ARCHIVE.` — two paragraphs: reels rescued from defunct label vaults, radio archives, family storerooms; archival-grade digitization; contemporary producers publish directly into the archive; goal: "reactivate Africa's musical heritage, create new economic opportunities for rights holders and artists, and put African music further into the global creative spotlight."
- Bronze-framed box, serif italic title: **"The source gets paid."** — "Every license splits revenue back to the original artists, their families and their estates — tracked transparently, paid quarterly. Nothing enters the archive without documented provenance and consent from rights holders. This is repatriation by royalty statement, not extraction with better branding."

### 6.13 CTA + FOOTER
- Centered label `PROOF OF CONCEPT`, huge serif italic `Hear it first.`, one line of copy, an underline email input + boxed ink-filled `REQUEST ACCESS`, and mono micro `SUPERVISORS · AGENCIES · LABELS · ESTATES · DJS · PRODUCERS`.
- Footer: Anton `ASILI` + handwritten bronze "every sound has an origin." + mono nav + mandatory disclaimer: `PROOF-OF-CONCEPT MOCKUP · ALL ARTIST NAMES, TRACKS, LABELS AND FIGURES ARE FICTIONAL PLACEHOLDER CONTENT FOR DEMONSTRATION · GENRES, ERAS AND MUSICAL CONTEXTS ARE REAL · "ASILI" IS A WORKING TITLE`

## 7. DELIVERABLES

1. Desktop (1440) + mobile (390) of the full page
2. Light + dark themes
3. Component sheet with states: link hover, boxed-button hover/fill, filter active, registry row hover/active, muted stem lane, MUTE/SOLO pressed, PAID / TO APPROVE pills, focus states
4. The five regional engraving-plate styles as a reusable illustration system

## 8. SUCCESS CRITERIA

- Reads premium/fashion-grade within three seconds — would sit next to too-young.com without embarrassment
- African heritage feels honored and specific, never costumed
- The AI reads as precision instrumentation, not gimmickry
- A rights holder would trust it with their masters; a music supervisor would want to search it
