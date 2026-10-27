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
README.md          LiaScript course for participants (slides + worksheets as surveys + quizzes)
vodja.md           facilitator script (times, what to say, answers). Not for participants.
img/               line-art illustrations (art_*.png), QR codes (qr_*.png), app screenshots (shot_*.png)
delovni-listi/     printable A4 worksheets as PDF, 01–12 plus 00_vsi_delovni_listi.pdf
predloga/index.md  Hugo page template for the teaching aids library
CLAUDE.md          this file
```

Course URL once pushed to GitHub:
`https://liascript.github.io/course/?https://raw.githubusercontent.com/<user>/<repo>/main/README.md`

## Schedule (keep README.md, vodja.md and the PPTX in sync)

- Day 1: guessing game (obscure historical aids), intro pairs, project + history, idea finding (pain point → "how might we" → Crazy 8s → choose), break, LiaScript workbook with AI, web app with AI (single index.html), publish on GitHub Pages.
- Day 2: yesterday recap with printed QR codes to each pair's app, what makes a good aid, SCAMPER (with printed cards of classic aids), safety + 3D printing, break, laser with engraved QR code (Inkscape: Extensions → Render → Barcode → QR Code), cardboard prototype, show and tell.
- Day 3: critical friend (I like / I wish / What if), library + markdown + template, writing the library page, break, page + classroom action plan (each teacher, required project output), submission to Teams, presentations, what's next + evaluation questionnaire.

Worksheet numbers are fixed and referenced everywhere: 1 Iskanje idej, 2 Crazy 8s, 3 Opis za AI, 4 GitHub Pages, 5 SCAMPER, 6 Prototip, 7 Kritični prijatelj, 8 Stran učila, 9 Akcijski načrt, 10 Markdown in oddaja, 11 20 klasičnih učil, 12 Vprašalnik.

## Writing rules

- Language: Slovenian first, Serbian (Latin script, ekavica) on the line below in italics. Keep both short.
- Plain, understated language. No em dashes. No marketing tone, no "AI-sounding" phrasing.
- Design: minimal, white background, black text, one blue accent, thin lines. No decorative cards or emoji.
- Facts about the project come only from the Erasmus+ application. Do not invent numbers or dates.
- Historical facts in the guessing game and the 20-aids table must stay accurate. Check before changing years.

## LiaScript conventions used

- Header comment block at the top (author, email, version, comment, logo).
- `#` = day/chapter, `##` = slide, `###` = worksheet sub-page.
- Quizzes: `[( )]`/`[(X)]` single choice, `[[ ]]`/`[[X]]` multiple, `[[answer]]` text, `[[ a | (b) | c ]]` dropdown, solution block between lines of `*`.
- Worksheets are surveys: `[[___]]` one line, `[[___ ___ ___]]` three lines, `[(1)] label` single choice, `[[x]] label` checkbox. Surveys have no correct answer.
- Images are relative (`img/...`). A paragraph with only images becomes a gallery.
- Facilitator notes and answers live in vodja.md, never in README.md text (except quiz solution blocks).

## Related work

- Teaching aids library: Hugo site (sl/sr/en). One page bundle per aid: `priimek-ucilo/index.md`, `slike/`, `datoteke/`. Template in `predloga/index.md`. The Erasmus+ credit line at the bottom is required.
- Example web aids built as single-file HTML (RGB challenge, number systems, PC ports, ESP32 pinout, pixel art to binary, phishing detective, name wheel, countdown, big text) are linked from Luka's personal aids index.

## Open tasks

1. Push this folder to a public GitHub repo and check the LiaScript course URL renders every quiz and survey.
2. After Day 1, collect the participants' app links and generate a QR code PNG per pair (Python `qrcode`), sized for laser engraving at 25 mm.
3. Replace YouTube search links with specific videos once chosen.
4. Proofread the Serbian lines with a colleague from Niš.
5. After Day 3, convert teacher submissions from Teams into Hugo page bundles, add sr/en translations, keep the Erasmus+ line.
6. Optional: add an English version of README.md for the Digital Blueprint Library.
