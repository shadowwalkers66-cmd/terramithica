---
title: "TerraMythica Build Roadmap"
tags: [roadmap, project-management]
filed_on: "2026-08-02"
note: "New prospective document — not sourced from a single log. Synthesizes the current state of every folder in this repo into one build plan. Nothing pre-existing was changed to create this."
---

# TerraMythica / *Shadows of the Veil: Awakening of the Emblematic* — Build Roadmap

This is the single entry point for turning everything currently sitting in this
repo into a finished world and a finished novel. It doesn't add new lore — it
maps what already exists, flags what's thin or missing, and sequences the work.

**How to use this doc:** work top to bottom within a phase, but feel free to jump
to whatever section is calling to you creatively. The order here is the order
that unblocks the most downstream work, not a mandatory sequence.

---

## 1. Where things actually stand right now

| Area | Folder | Maturity | Notes |
|---|---|---|---|
| Manuscript | `manuscript/` | 🔴 Early | Full 60-chapter outline exists, but only **Ch. 9 and Ch. 10** are drafted. Chapters 1–8 (the entire setup of Part I) are not yet written. |
| Story Bible | `story-bible/` | 🟢 Strong | Overview, summaries, themes, character roster, plot events, editorial plan, and a large open-questions doc all exist. This is the most developed layer. |
| Magic System | `worldbuilding/magic-system/` | 🟢 Strong | Emblems, power/physics, Fractal Cognition all have substantial drafts (~5,750 words). |
| Geography | `worldbuilding/geography-cartography/` | 🟢 Strong | Layered textual maps + cartography system (~7,000 words) — one of the deepest folders. |
| Creatures / Bestiary | `worldbuilding/creatures-bestiary/` | 🟢 Strong | Spiritwild, general bestiary, and the Nightmares all drafted (~6,650 words). |
| Factions | `worldbuilding/factions-organizations/` | 🟡 Moderate | Order of the Emblematic is well developed; inter-faction dynamics and Luminara politics are thinner sketches. |
| Culture & Society | `worldbuilding/culture-society/` | 🟡 Moderate | Social strata/castes and calendars exist but read as first-pass brainstorms rather than settled canon. |
| Language | `worldbuilding/language/` | 🟡 Moderate | Tongues/scripts and the "Language of Emotion" concept exist; dialect table is a stub. |
| Religion & Cosmology | `worldbuilding/religion-cosmology/` | 🟡 Moderate | One solid document, but it's the *only* document — no cross-links yet to the Fallen Luminaries material in magic-system. |
| Characters | `worldbuilding/characters/` | 🟡 Moderate | Key figures + one council member profile exist, but most named characters in `story-bible/character-roster.md` don't have a matching individual profile yet. |
| Transportation | `worldbuilding/transportation/` | 🟠 Thin | One document (~2,000 words) covering ley-trains/flying caravans/memory ferries — functional but not integrated with geography yet. |
| History & Timeline | `worldbuilding/history-timeline/` | 🔴 Very thin | Only ~500 words. This is the biggest structural gap — nothing else in the world has a firm timeline to hang off of. |
| Economy & Technology | `worldbuilding/economy-technology/` | 🔴 Very thin | Only ~480 words, one fiscal-policy note. No trade, currency, or tech-level canon yet. |
| Artifacts & Weapons | `worldbuilding/artifacts-weapons/` | 🔴 Very thin | ~920 words, compendium-style but skeletal. |
| Media / Prompts | `media/prompts/` | 🟢 Strong | Book-cover and character-illustration prompt libraries are extensive and ready to use. |
| Production | `production/` | 🟢 Strong | Writing-process guide and a cinematic-adaptation concept already exist. |
| Other Projects | `other-projects/` | ⚪ Parked | *Unveiling the Veil* (separate novel), *The Faltering Grid* (sci-fi short), and one stray technical note — intentionally kept out of TerraMythica canon. |

🟢 Strong &nbsp;🟡 Moderate &nbsp;🟠 Thin &nbsp;🔴 Very thin / blocking &nbsp;⚪ Not in scope

**The headline gap:** the *worldbuilding* is significantly ahead of the
*manuscript*. Magic system, geography, and bestiary are genuinely rich. History,
economy, and artifacts are the weak links holding the rest back — and the
novel itself is 8 chapters behind its own outline before it even reaches
the part that's been drafted.

---

## 2. Build order — four phases

### Phase 1 — Shore up the load-bearing gaps (do this first)
These three folders are thin *and* everything else quietly depends on them.

1. **`worldbuilding/history-timeline/`** — Build an actual timeline: when did
   the Veil form, when did the Luminaries fall, when was the Order founded,
   how long before the novel's present day. Almost every other domain
   (religion, factions, geography) references past events informally; this
   is where those references should anchor.
2. **`worldbuilding/economy-technology/`** — Decide the tech ceiling
   (Fractal Cognition implies a science+magic hybrid society — how far does
   that go?), currency, trade routes tied to the transportation network
   already drafted.
3. **`worldbuilding/artifacts-weapons/`** — Expand from compendium stub to a
   real reference: which artifacts appear in the current manuscript chapters,
   which Emblems have signature weapons, what the Nightmares corrupt or covet.

### Phase 2 — Close the open questions that block character/plot work
`story-bible/open-questions.md` already has ~10 categories of unanswered
worldbuilding questions (cosmology, Emblems, Fallen Luminaries, culture,
geography, factions, character motives, religion, future/myth). Work through
them in this priority order, since manuscript chapters 1–8 need these answers:

1. **The Emblems** (origin, inheritance, cost of use) — directly needed to
   write Damion's awakening in Ch. 1–4.
2. **The Fallen Luminaries / Nightmares** — needed for Ch. 7 ("The First
   Nightmare").
3. **The Order of the Emblematic** (already the strongest faction doc — mainly
   needs the founding-era answers from Phase 1's timeline work) — needed for
   Ch. 5.
4. Everything else in `open-questions.md` (culture, religion, future/myth) can
   trail behind and get answered as the manuscript reaches those chapters.

### Phase 3 — Fill the manuscript gap
- Draft **Chapters 1–8** (Part I setup — Damion's birth/mark, Luminara
  upbringing, first Veil encounter, the Mark awakening, meeting the Order,
  meeting Lila/Zane/Nyxia/Gideon, the first Nightmare, the Order's mission
  beginning). These are unblocked by Phase 2 items 1–3 above.
- Reconcile `manuscript/excerpts/luminara-opening.md` — check whether it
  should become (or feed) Chapter 1, since it's the largest single prose file
  in the repo and covers the same setting as the opening chapters.
- Once Ch. 1–10 form a continuous draft, revisit `story-bible/editorial-plan.md`
  for the next editing pass.

### Phase 4 — Depth and polish passes
- Build individual character profiles (matching `worldbuilding/characters/`
  format) for every named entry in `story-bible/character-roster.md` that
  doesn't have one yet.
- Flesh out `culture-society/`, `language/`, and `religion-cosmology/` from
  "first-pass brainstorm" to settled canon — these matter most from Part II
  onward, not for Ch. 1–10, so they can run in parallel with Phase 3.
- Cross-link folders: religion ↔ Fallen Luminaries, geography ↔ transportation,
  history ↔ factions. Right now each domain was filed independently from its
  own log(s) and doesn't reference sibling folders yet.
- Decide the fate of `other-projects/` — keep parked here, or split into its
  own repo, per the original filing notes.

---

## 3. Standing items (not phase-locked)

- **Media**: `media/prompts/` is ready to generate cover art and character
  art on demand — pull from there whenever a character or scene in the
  manuscript needs a visual.
- **Production**: `production/writing-process-guide.md` and
  `production/cinematic-script-adaptation.md` are reference material to dip
  into anytime, not sequential tasks.
- **Duplicates / stray files**: already resolved and documented in the root
  `README.md` (duplicate logs, the `.mg` extension, the stray root-level
  image). No outstanding cleanup there.

---

## 4. Quick links

- Start here for orientation: [`story-bible/overview.md`](story-bible/overview.md),
  [`story-bible/character-roster.md`](story-bible/character-roster.md)
- Full open-question backlog: [`story-bible/open-questions.md`](story-bible/open-questions.md)
- Full chapter outline: [`manuscript/outline.md`](manuscript/outline.md)
- Filing/provenance details for every file: [`README.md`](README.md)
