# Koine Lab · Experimental Biblical Greek Toolkit

Koine Lab is an experimental, data-rich learning environment for Biblical Greek. The entire project was produced in a single one-shot session by GPT-5-Codex, bootstrapping a working Vite + React application from the SBLGNT morphology dataset bundled in this repository.

> ⚠️ **Status:** experimental proof of concept. Expect unfinished edges, sparse polish, and follow-up refactors.

## Why This Exists

- Demonstrate how far an autonomous GPT-5-Codex build can go in one pass when supplied with a rich corpus (SBLGNT morphology JSON).
- Prototype an immersive alternative to grammar-translation study that blends spaced repetition, morphology exploration, and contextual reading.


## Feature Highlights

- **Vocabulary Lab** – SM-2 spaced repetition, seeded from SBLGNT frequency data, with local persistence via Zustand.
- **Morphology Explorer** – Corpus-wide filtering by part of speech, case, tense, voice, mood, and book coverage using the bundled JSON data.
- **Immersive Reader** – Passage reader with hover scaffolding, morphology + gloss overlays, and configurable highlights.
- **Practice Studio** – Alternates morphology parsing and lexical recognition drills that pull real tokens from the selected corpus slice.
- **Analytics Dashboard** – Coverage ladders, review streaks, and high-value lemma surfacing to keep progress visible.

All tools consume static assets generated from `sblgnt_json/`, enabling deployments to GitHub Pages or any static host.


## Credits

- **Generator:** GPT-5-Codex (one-shot experimental build).
- **Corpus:** SBLGNT morphology JSON (included under `sblgnt_json/`).
- **Stack:** Vite, React 19, TypeScript, Tailwind CSS, TanStack Query, Zustand.
 
- **SBL Greek New Testament (SBLGNT)**:
  - Text: [https://github.com/LogosBible/SBLGNT](https://github.com/LogosBible/SBLGNT)
  - Paragraph Divisions: [https://github.com/aaronshaf/sblgnt](https://github.com/aaronshaf/sblgnt)
- **MORPHGNT**:
  - Morphological and Lexical Data: [https://github.com/morphgnt/sblgnt](https://github.com/morphgnt/sblgnt)
- **Lexham English Bible English–Greek Reverse Interlinear New Testament**:
  - *Used with permission.*
  - Available at: [https://www.sblgnt.com/download/](https://www.sblgnt.com/download/)
- **Additional Resources**:
  - [Greek New Testament](https://github.com/jcuenod/greek-new-testament) by [jcuenod](https://github.com/jcuenod)
  - [Awesome Bible Data](https://github.com/jcuenod/awesome-bible-data) by [jcuenod](https://github.com/jcuenod)
  - [MACULA Greek](https://github.com/Clear-Bible/macula-greek) by [Clear-Bible](https://github.com/Clear-Bible)
  - [SBLGNT Add-ons](https://github.com/eliranwong/SBLGNT-add-ons/tree/master) by [eliranwong](https://github.com/eliranwong)
  - [Missing data for John 7:53-8:11](https://gist.github.com/chadwhitacre/21497c4d0a7326dccfed79798cfb9dc8) by [chadwhitacre](https://gist.github.com/chadwhitacre)