# Federigo Enriques, *Le superficie algebriche* (1949)

[Italiano](README.it.md)

Enriques's last book, his treatise on algebraic surfaces, published after his death with a preface by Guido
Castelnuovo (Bologna: Nicola Zanichelli, 1949). This edition gives the whole book in Italian, as a 374-page reader PDF
and as editable LaTeX: Castelnuovo's preface, the author's preface, the table of contents (INDICE), the introduction
and the eleven chapters.

- [Reader PDF (A4, 374 pages)][pdf]
- [LaTeX source](enriques_superficie_algebriche.tex) (one file, pdfLaTeX)
- [Correction ledger](corrections.csv)

This is a first version. The transcription is good but not perfect, and more checking against the scan will follow.

## How it was made

- **Scan:** Maxim Leyenson.
- **Transcription:** AI-transcribed by OpenAI gpt-6-astra from the scan, November 2026. Readings the model was unsure
  of are marked.
- **Edition:** AI-produced typesetting and corrections by ChatGPT (Pro mode): continuous text, the original page
  numbers in the margin, the author's footnotes, links from the INDICE to the pages, and numbered editorial notes.
  Every reading marked as doubtful was checked against the scan.
- **Further corrections and the checks described below:** Claude (Anthropic).

## Reading the edition

- The original page numbers stand in the inner margin; the INDICE links to them.
- Numbered notes in the outer margin:
  - **Dubbio** (119): a reading the scan does not settle;
  - **Stampa** (201): an apparent misprint or slip in the 1949 printing. The text keeps what is printed; the note gives
    the likely intended reading.

  Changing `\shownotestrue` to `\shownotesfalse` in the preamble hides these notes.
- Pages 284–285 are missing from the scan. The gap is marked, and nothing has been reconstructed. Part of p. 186 is
  obscured in the scan and part of p. 368 is covered by another leaf; both places carry a notice. If you can supply
  scans of these pages, please open an issue.

## What has been checked

- **Doubtful readings.** The transcription marked 251 readings as doubtful. 132 were settled against the scan; the
  other 119 carry a *Dubbio* note.
- **Transcription errors.** 26 have been corrected; each is listed in the ledger (kind `transcription error`).
- **Pages 1–100,** compared in full with the scan. Four transcription errors there had not been marked as doubtful:
  p. 18 *dalle* for *delle*; p. 27 *minimo* for *minima*; p. 72 r ≥ 1 for r > 1; p. 80 a prime added to C₁. All four
  are corrected. On p. 85 the scan shows either an accent or a speck; the printed *è* is kept, with a *Stampa* note.
- **Three sample pages** (pp. 161, 313, 388), compared word for word and formula for formula with the scan: no errors.

The rest of the book (pp. 101–464) has so far been checked only at the marked doubts and on the sample pages, so some
unmarked transcription errors remain there. A full comparison with the scan is planned.

## Mathematics

The edition does not correct Enriques's mathematics. Suspected misprints and slips are noted in the margin or listed
in the ledger (78 further proposals, not applied to the text). A mathematical commentary on pp. 1–100 is in progress;
points it raises that are still being checked: a sign in the determinant on p. 45 (noted in the margin as a probable
misprint), the dimension of the linear system in the example on p. 89, and a step in the equivalence criteria on
pp. 97–100.

## Rights

The original work is in the public domain in the European Union: Federigo Enriques died in 1946 and Guido
Castelnuovo, author of the preface, in 1952. Its status elsewhere may differ. Where we hold rights, in the AI-produced
transcription, corrections and typesetting, they are dedicated to the public domain under CC0 1.0. This edition is
published for educational, non-profit purposes, and we claim no rights we do not hold. If you hold rights in this work
and object to its publication here, please open a GitHub issue and we will take it down.

[pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-06/enriques_superficie_algebriche.pdf
