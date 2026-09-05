# NOTES — the Selah Serbian rendering (sr.v1)

*The sixty-first chair; the second Cyrillic-home language, and the
first two-alphabet one. Lit 2026-09-05 05:37, sealed ~14:20 the
same day.*

## Burn signature

- Lit 05:37 (commit dd1dd94a), first-hour gate passed 06:05 —
  **Господ/ГОСПОД at the Name's seat: zero from the first hour**,
  the erasure answered before breakfast. Јахве standing at every
  יהוה including the declined forms (Јахвеа/Јахвеу per the
  pre-ruling).
- The relay ended its queue short twice (796 verses at 12:32, 42 at
  12:53) — relit both times without incident; the trailing verses
  and every glean round refilled clean. ~7.3h wall for the main
  burn.
- Models: glm-5.3 bulk; fable-5-hand for the hand verses below.

## The transliteration crux (the two-alphabet chair)

Serbian writes itself in two alphabets, and the model bled the
Latin one all night: census round 1 found **552 Latin-run files**,
and re-renders kept reintroducing them (552 → 147 → 75). The chair
answered with what no other chair has: **Gaj's Latin and Vuk's
Cyrillic map bijectively**, so the bleed was converted, not
re-rendered — **1,015 Latin-Serbian words across 555 files**
transliterated deterministically (kad→кад, izvedoše→изведоше,
Jahveu→Јахвеу), a normalization of script, never a re-glossing.
The sweep also exposed a **new census blind-spot class:
mixed-script welds** — two-letter Latin fragments fused inside
Cyrillic words (Изра+ael, ha, jo), invisible to any 3+-letter-run
regex. An EN_STOP guard kept real English leaks (census class)
from being transliterated into garbage — and produced the night's
best self-caught bug: Serbian **год** ("ever") blocked as English
"god" and left as `кад god` until the hand pass caught it.

## The Ђорђе paradigm, restored

Serbian grammar offers two declensions for a name in -е: the
rails' stem-intact paradigm (Јахвеа, Јахвеу, Јахвеов…) and the
Ђорђе paradigm, which treats final -е as a case ending and elides
it (Јахви, Јахвин, Јахвом). The burn produced both: ~6,300
stem-intact forms against **229 elided** ones. The mapping back is
deterministic (Јахви→Јахвеу, Јахвом→Јахвеом, Јахвин-family→
Јахвеов-family), so the minority paradigm was restored to the
ruled one across 102 files — grammar normalization under the
pre-ruling, riding the shared six-chair case-suffix ratification
(ro+hu+kk+sr+hy+ka) PENDING SCOTT.

## Seal (census, 2026-09-05 ~14:20)

- **Јахве 5,799** (Name-seat verses) · Елохим 2,093 ·
  ⟨את⟩-verses 7,368
- Господ-at-Name 0 · Јехова 0 · пакао-at-Sheol 0 (58 Шеол seats)
- Христос / Месија: **absolute zero**; крст-stem 4 hits all
  lawful collisions (укрсти crossed-hands Gen 48:14, крстачу
  sacrum Lev 3:9…) — **NT-leak zero, fifth consecutive chair.**
- aleph-tav audit **[0 0 0 0]**
- Tekoa independent count: 6,850 יהוה token seats, 6,849 clean
  before repairs; Адонај 452; 282 lowercase господар at human
  seats all lawful (the Ofèl rule holds).

## The lookalike plague (four incidents in one night, two here)

- **Јахвeова** — a Latin *e* inside the Name itself (1 Sam 25:28).
- **ο мени** — a Greek omicron for Serbian о (2 Chr 18:17).
- (Siblings elsewhere tonight: kk's Яһве ×68 files; the hy fork's
  own Latin-y-for-յ test slip.) Same-script and cross-script
  lookalikes are now a standing census blind-spot class; the
  lookalike sweep belongs in every seating groove.

## Hand verses (model: fable-5-hand)

- **The curtain-hook verses again, fifth chair**: Exod 26:32 came
  back with its first six tokens *looped* as the back half; 36:36
  with והויהם for וויהם. Rebuilt on the true surfaces (the species:
  ln Exod 12:3, ro Job 26:13, hu Isa 61:7, kk both hooks, sr both
  hooks).
- **Fabricated-⟨את⟩ insertions**: Ps 139:13, Isa 38:21, Ps 31:14 —
  extra את tokens invented into the spine (deleted, glosses
  realigned); Amos 4:11 a fabricated extra token מ未有 (CJK inside
  a "Hebrew" surface). Job 40:26 and Neh 11:31 empty spines rebuilt
  (Neh 11:31 also read *Витлејем* for בית אל — Beth-El restored).
- **Gen 23:13 token-order rotation** (the ms class): את/מתי/ואקברה
  shuffled; restored. Exod 30:19 gloss column slipped one seat;
  realigned.
- **Pronoun-את → ти** (ninth-chair hand class): the Ezek 16
  sisters (16:45 ×2, 16:48), Ezek 22:24, Ezek 28:14 ("Ти" the
  cherub), Neh 9:6 ("Ти сам"), Prov 7:4 (fifth chair), Zech 9:11,
  Jer 2:27. **Dan 3:12** — יתהון "⟨את⟩ њих", eighth chair.
  אל-as-marker → ка (Esther 1:22, Lev 15:14); כל → сву (Isa 13:5).
- **CJK garbage, 6 files**: 丈夫 welded for муж (Num 5:29), ⟨犬⟩
  at אל (Lev 8:1), ⟨码⟩/⟨淺⟩/⟨那个⟩ supplied-garbage, a marks-field
  annotation leak (Exod 29:1). Gen 29:26 carried a baked
  `system_еррор` string.
- 17 doubled-marker files normalized (⟨⟨→⟨); ascii <> brackets →
  ⟨⟩; a Russian leak (<тогда>) removed; Шауљ→Шаул ×4; two שאול
  (Saul) tokens glossed as punctuation restored.

## Tekoa (witness-word survey, class-A only)

**7 class-A, all repaired** — the cleanest witness floor of the
Cyrillic chairs:

- **One flow-assembly leak** (kk's class, but a single verse here
  vs kk's 23): Micah 4:13's flow welded "господару" over the token's
  clean Адону; restored.
- **Three divine-אדני displacements** → Адонај family (Gen 18:3,
  Ezra 10:3, Isa 21:8 — against the chair's own 452 Адонај norm).
- **One Бог at an אלהים seat** (2 Kgs 8:11 "човек Божји" →
  Елохимов) — the only one in the store.
- **Two Name-seat gloss rotations** (Lev 17:2 יהוה glossed
  "говорећи"; 1 Kgs 12:22 empty) — members of a 33-verse
  gloss-rotation class, all re-rendered.
- **Lawful, kept**: the nine compound-Name explanatory parens
  (Ел Шадај, Ел Рои, Ел Елион…); 270/271 lowercase бог at pagan
  seats; 282 господар at human seats; крст collisions.

## Open questions (PENDING SCOTT)

1. **Digraphia**: should a Latin-script Serbian *lens* exist
   (automatic, via the same bijection), and what is the front-door
   posture for Latin-Serbian readers?
2. **Paren-shadows: 3,705 files / 1,830 instances / 747 forms**
   ((Мојсије) 284, (Египат) 235, (Давид) 142) — between kk's 1,644
   and hu's 4,225; one posture ruling governs ms/kk/hu/sr. Special
   case: **Исус Навин** as Joshua's church-Serbian shadow in 85
   verses — the very word the rails reject for משיח, lawful as
   Joshua's Serbian name, repeated past first-encounter.
3. **Case-suffix ratification** — six chairs now (ro Elohimul, hu
   1,092, kk spectrum, sr Ђорђе restorations, hy enclitic -ը/-ն,
   ka ergative -მ); one ruling settles all.
4. **Машијах drift**: 25 Машијах vs 14 помазаник at משיח (adjacent
   verses split: 1 Sam 24:7/24:11); Lev 4-6 adjectival помазани
   lawful. Consistency call.
5. **Isa 6:3**: Цеваот's paren renders the D1-rejected form
   (Господар војски) and is not first-occurrence.
6. **⟨את⟩ flow arithmetic**: ~1,185 token-column markers do not
   reach the flow string — no prior-chair baseline; flagged for the
   seat gate.

## Cruxes

- The second Cyrillic-home chair proved the polarity discipline is
  a groove, not an experiment — the erasure word never touched the
  Name's seat, from the first hour to the seal.
- The two-alphabet language was met with a bijection, not a
  battle. Script is a lens; the words underneath never changed.
- The Name declined in two paradigms and the rails' one won —
  quietly, deterministically, 229 restorations without one
  re-render.
