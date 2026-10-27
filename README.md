# Endo Logbook Builder

A step-by-step web form that fills the Saint Joseph University endodontic clinical logbook and downloads it as a Word file. Works on phones and computers.

**Use it:** open the GitHub Pages site for this repository (Settings → Pages shows the address).

## What it does

- One logbook section per screen, with Back / Next and a section menu.
- Dental chart (FDI numbering) to pick the tooth.
- File number checked against the `xx/xxxxxx` format.
- Preset answers for common entries (medical history, anesthesia, isolation with clamp number, irrigation with NaOCl %, obturation, sealer, pain management…), or write your own.
- Final diagnosis built from the pulpal and periradicular selections.
- Fills the original logbook template: chosen boxes become ☒, answers replace the writing lines, and empty fields keep their blank lines. Clinical Case Documentation and the Evaluation Grid stay blank.
- Answers are saved only in your own browser. Nothing is uploaded.

## Files

- `index.html` – the complete app (template embedded). This is what GitHub Pages serves.
- `src/app.html` – app source with a placeholder for the template.
- `src/template.docx` – the blank logbook template, with extra "checked box" list styles.
- `src/build.py` – embeds the template into the app: run `python3 src/build.py` after editing the source.
