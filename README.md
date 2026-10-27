# Endo Logbook Builder

A step-by-step web form that fills the Saint Joseph University endodontic clinical logbook and downloads it as a Word file. Works on phones and computers.

**Open the app:** https://amsaleh1998-spec.github.io/Endo-Logbook/

## What it does

- One logbook section per screen, with Back / Next and a section menu.
- Dental chart (FDI numbering) to pick the tooth.
- File number checked against the `xx/xxxxxx` format.
- Final diagnosis filled in from the pulpal and periradicular selections (editable).
- Clinical Case Documentation: choose a photo for each radiograph (preoperative, working length, master cone, postoperative, follow-up); each one goes into its box in the Word table.
- Fills the original logbook template: chosen boxes become ☒, answers replace the writing lines, and empty fields keep their blank lines. The Evaluation Grid stays blank.
- Answers and photos are saved only in your own browser. Nothing is uploaded.

## Files

- `index.html` – the complete app (template embedded). This is what GitHub Pages serves.
- `src/app.html` – app source with a placeholder for the template.
- `src/template.docx` – the blank logbook template, with extra "checked box" list styles.
- `src/build.py` – embeds the template into the app: run `python3 src/build.py` after editing the source.
