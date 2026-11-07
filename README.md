# Federigo Enriques, *Le superficie algebriche* (1949)

[Italiano](README.it.md)

Enriques's last book, his treatise on algebraic surfaces, published after his death with a preface by Guido
Castelnuovo (Bologna: Nicola Zanichelli, 1949). This edition gives the whole book (Castelnuovo's preface, the author's
preface, the table of contents, the introduction and the eleven chapters) in Italian and in English, each as the text
as printed and as a corrected text, with editable LaTeX.

| | as printed | corrected |
|---|---|---|
| **Italian** | [PDF][it-pdf] · [LaTeX](enriques_superficie_algebriche.tex) | [PDF][itc-pdf] · [LaTeX](enriques_superficie_algebriche_corretto.tex) |
| **English** | [PDF][en-pdf] · [LaTeX](enriques_superficie_algebriche_EN.tex) | [PDF][enc-pdf] · [LaTeX](enriques_superficie_algebriche_EN_corrected.tex) |

- **As printed:** the text of the 1949 print, with its misprints and the author's slips. In the Italian, apparent
  misprints and doubtful readings are marked in the margin.
- **Corrected:** 232 errors corrected: misprints of the print and slips of the author (wrong letters, indices,
  signs, numbers, references, and slips of calculation), each with the smallest change. Every correction is listed with
  its reason in [`corrections_corretto.csv`](corrections_corretto.csv) (Italian) and
  [`corrections_corrected_en.csv`](corrections_corrected_en.csv) (English). Corrections that would rewrite Enriques's
  arguments are not made in his text; the commentary discusses them.
- **Commentary:** a mathematical commentary on the whole book (317 pages) is a separate companion:
  [enriques-superficie-algebriche-commentary](https://github.com/KokunoYumeto/enriques-superficie-algebriche-commentary).
- **How it was made:** [METHODOLOGY.md](METHODOLOGY.md), with the prompts used and the costs.

## How it was made

- **Scan:** Maxim Leyenson.
- **Transcription:** AI-transcribed by OpenAI gpt-6-astra from the scan.
- **Edition:** AI-produced typesetting and corrections by ChatGPT (Pro mode); further corrections by Claude (Anthropic).
- **Audits:** the whole book audited page by page against the scans, in six audits, by ChatGPT (Pro mode).
- **This version:** the audits' findings carried into the text (transcription errors corrected, doubtful readings
  settled, the corrected text) by Claude Opus 5.5. The English is AI-translated by Claude Opus 5.5 from the Italian
  as printed. A second model (OpenAI gpt-6-astra) read the English against the Italian; the problems it found were judged and fixed by Claude Opus 5.5.

No human has proofread the edition. Errors certainly remain: please report them as issues, with the page.

## Reading the edition

- The original page numbers stand in the inner margin; the table of contents links to them.
- Numbered notes in the outer margin of the Italian edition:
  - **Dubbio** (51): a reading the scan does not settle;
  - **Stampa** (201): an apparent misprint or slip of the 1949 print. The text as printed keeps what is
    printed, and the note gives the likely intended reading; in the corrected text the note reads **Corretto** where
    the correction was made.

  Changing `\shownotestrue` to `\shownotesfalse` in the preamble hides these notes. The English has no margin notes.
- Pages 284–285 are missing from the scan. The gap is marked, and nothing has been reconstructed. Part of p. 186 is
  obscured in the scan and part of p. 368 is covered by another leaf; both places carry a notice. If you can supply
  scans of these pages, please open an issue.

## What has been checked

- **The whole book,** audited page by page against the scans. The audits found 17 further transcription errors, now
  corrected, and settled 74 of the doubtful readings; 51 remain open and carry a *Dubbio* note. Every change is
  recorded with its reason in [`corrections.csv`](corrections.csv).
- **The English,** checked against the Italian by script: every formula, page marker and footnote is the same.
  A second model (OpenAI gpt-6-astra) read all of it against the Italian and found 17 problems; all were fixed, together with 20 further places with the same kind of problem. In the corrected English, 174 of the 232 corrections apply; the other 58 are Italian spelling or agreement slips with no English counterpart.

## Rights

The original work is in the public domain in the European Union: Federigo Enriques died in 1946 and Guido
Castelnuovo, author of the preface, in 1952. Its status elsewhere may differ. Where we hold rights, in the AI-produced
transcription, translation, corrections and typesetting, they are dedicated to the public domain under CC0 1.0. This
edition is published for educational, non-profit purposes, and we claim no rights we do not hold. If you hold rights
in this work and object to its publication here, please open a GitHub issue and we will take it down.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)

[it-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche.pdf
[itc-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche_corretto.pdf
[en-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche_EN.pdf
[enc-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche_EN_corrected.pdf
