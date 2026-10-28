# MAKE&LEARN workshop course

Context for Claude Code. Read this before changing anything in this repo.

## Who and what

- Owner: Luka Colarič, CS teacher at Šolski center Kranj (ŠC Kranj), Slovenia. Runs the school makerspace MladLab (3D printers, laser cutter, ESP32). Contact: luka.colaric@sckr.si.
- Project: Erasmus+ KA210-VET small-scale partnership **MAKE&LEARN**, 30,000 EUR, 1 Sep 2026 to 30 Nov 2027.
  - Partners: ŠC Kranj (coordinator) and ETŠ Mija Stanimirović, Niš, Serbia.
  - Idea: co-creation. Students and teachers build curriculum-based teaching aids together, preferably from recycled materials, with 3D printing or CNC where it makes sense.
  - Targets: 10 trained teachers, at least 20 classroom-tested aids (10 per school), a public "Digital Blueprint Library", a student competition in Niš (27–28 Oct 2027).
  - Evaluation criteria for aids: clear pedagogical purpose, it works, usable in class.
  - Priorities: innovation in VET, inclusion and diversity, environment and climate.
- This repo: the 3-day teacher training (28–30 Oct 2026, ŠC Kranj, 9.00–12.30 each day), 10 teachers (5 from Kranj, 5 from Niš) working in mixed pairs.

## Repo layout

```
README.md          LiaScript course for participants, Slovenian (slides, quizzes, AI prompts, links to PDF worksheets)
README.sr.md       the same course in Serbian; keep in sync with README.md
liascript-zmore.md separate LiaScript showcase course (all quiz/survey types, code, Python, 3D, embedded PhET/Falstad/ChemCollective/MolView/Ventusky), linked from the README LiaScript slide
vodja.md           facilitator script (times, what to say, answers). Not for participants.
img/               line-art illustrations (art_*.png), photos for the guessing game (foto_*.jpg, credits in README "O tečaju"), QR codes (qr_*.png), app screenshots (shot_*.png)
delovni-listi/     printable A4 worksheets as PDF, 01–12 plus 00_vsi_delovni_listi.pdf
predloga/index.md  copy of the library template (index.sl.md) for reference
CLAUDE.md          this file
```

Course URL once pushed to GitHub:
`https://liascript.github.io/course/?https://raw.githubusercontent.com/<user>/<repo>/main/README.md`

## Schedule (keep README.md, vodja.md and the PPTX in sync)

- Day 1: welcome (3-day overview), intro round and mixed pairs (pair chooses one subject), guessing game in pairs, project + history, idea finding (pain point → "how might we" → Crazy 8s → choose), break, web app with AI (single index.html), publish on GitHub Pages, LiaScript interactive workbook from an existing textbook page or worksheet (README.md in the same repo, links to the app).
- Day 2: yesterday recap (each pair shows its app), what makes a good aid, SCAMPER on a starting point the pair chooses (any teaching aid or a board game), then on their own idea, safety + 3D printing, break, laser with engraved QR code (Inkscape: Extensions → Render → Barcode → QR Code), cardboard prototype, show and tell.
- Day 3: pick up prints, critical friend (I like / I wish / What if), library overview, preparing the material folder (photos renamed, STL, SVG), writing the library page, break, page + classroom action plan (each teacher, required project output), submission to Teams, presentations, what's next + evaluation questionnaire.

Worksheet numbers are fixed and referenced everywhere: 1 Iskanje idej, 2 Crazy 8s, 3 Opis za AI, 4 GitHub Pages, 5 SCAMPER, 6 Prototip, 7 Kritični prijatelj, 8 Stran učila, 9 Akcijski načrt, 10 Markdown in oddaja, 11 20 klasičnih učil, 12 Vprašalnik.

## Writing rules

- Language: the course exists twice, `README.md` (Slovenian, `language: sl`) and `README.sr.md` (Serbian, Latin script, ekavica, `language: hr` because LiaScript has no Serbian UI). They link to each other with the `translation:` header macro and a link on the title slide. Any change to one must be made in the other; same slides, same order, same quiz answers. (As of v1.3.0 README.md was reworked; README.sr.md still has the v1.2.0 flow and needs the same changes.) `liascript-zmore.md` and `vodja.md` stay bilingual / Slovenian.
- Plain, understated language. No em dashes. No marketing tone, no "AI-sounding" phrasing.
- Design: minimal, white background, black text, one blue accent, thin lines. No decorative cards or emoji.
- Facts about the project come only from the Erasmus+ application. Do not invent numbers or dates.
- Historical facts in the guessing game and the 20-aids table must stay accurate. Check before changing years.

## LiaScript conventions used

- Header comment block at the top (author, email, version, comment, logo).
- `#` = day/chapter, `##` = slide, `###` = worksheet sub-page.
- Quizzes: `[( )]`/`[(X)]` single choice, `[[ ]]`/`[[X]]` multiple, `[[answer]]` text, `[[ a | (b) | c ]]` dropdown, solution block between lines of `*`.
- Worksheets: paper work (sheets 1, 2, 5, 6, 7) and collected sheets (9, 12) are linked as PDFs (GitHub blob URLs, so they open in the browser). Only what goes into AI is on screen, as copyable prompt templates: workbook prompt, sheet 3 (aid description), sheet 8 (library page). Survey answers stay in the participant's browser, so never use surveys for anything the facilitator must collect.
- Outputs are independent, not three parts of one aid: web app on GitHub Pages (new digital aid), LiaScript workbook (upgrade of an existing textbook page or worksheet), physical makerspace aid. Same topic optional; a QR code can link physical to digital.
- Thread: brainstorm → idea in 3 sentences → sheet 3 app prompt → `opis.md`; Crazy 8s object sketches → day 2 physical aid; day 3: `opis.md` + "Za učitelja" + physical aid data → library page prompt (page describes the physical aid).
- Images are relative (`img/...`). A paragraph with only images becomes a gallery.
- Facilitator notes and answers live in vodja.md, never in README.md text (except quiz solution blocks).

## Related work

- Teaching aids library: separate Hugo project in `Downloads/MAKE_LEARN_knjiznica` (sl/sr/en, no theme). One folder per aid in `content/ucila/<priimek-ucilo>/` with `index.sl.md`, `index.sr.md`, `index.en.md`, `slike/`, `datoteke/` (files in `datoteke/` are listed automatically). Template in its `predloga-ucila/`. The Erasmus+ co-funding line is in the site footer, so pages do not repeat it. Front matter keys: title, opis, avtorji, sola, predmet, letnik, cas_izdelave, tezavnost, materiali, reciklirano, orodja, naslovna, aplikacija, zvezek, licenca. Workshop participants submit `index.sl.md`; Luka adds sr/en.
- Example web aids built as single-file HTML (RGB challenge, number systems, PC ports, ESP32 pinout, pixel art to binary, phishing detective, name wheel, countdown, big text) are linked from Luka's personal aids index.

## Open tasks

1. Push this folder to a public GitHub repo and check the LiaScript course URL renders every quiz and survey.
2. After Day 1, collect the participants' app links and generate a QR code PNG per pair (Python `qrcode`), sized for laser engraving at 25 mm.
3. Replace YouTube search links with specific videos once chosen.
4. Proofread the Serbian lines with a colleague from Niš.
5. After Day 3, copy each submitted `priimek-ucilo/` folder into the library's `content/ucila/`, add `index.sr.md` and `index.en.md` translations.
6. Optional: add an English version of README.md for the Digital Blueprint Library.
