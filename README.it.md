# Federigo Enriques, *Le superficie algebriche* (1949)

[English](README.md)

L'ultimo libro di Enriques, il trattato sulle superficie algebriche pubblicato dopo la sua morte con una prefazione di
Guido Castelnuovo (Bologna, Nicola Zanichelli, 1949). Questa edizione dà l'intero libro, in italiano, come PDF di
lettura di 374 pagine e come sorgente LaTeX modificabile: la prefazione di Castelnuovo, la prefazione dell'autore,
l'INDICE, l'introduzione e gli undici capitoli.

- [PDF di lettura (A4, 374 pagine)][pdf]
- [Sorgente LaTeX](enriques_superficie_algebriche.tex) (un solo file, pdfLaTeX)
- [Registro delle correzioni](corrections.csv)

È una prima versione. La trascrizione è buona ma non perfetta, e seguiranno altri controlli sulla scansione.

## Come è stata fatta

- **Scansione:** Maxim Leyenson.
- **Trascrizione:** prodotta da IA (OpenAI gpt-6-astra) dalla scansione, novembre 2026. Le letture incerte sono
  segnalate.
- **Edizione:** impaginazione e correzioni prodotte da IA (ChatGPT, modalità Pro): testo continuo, numeri delle pagine
  originali in margine, note dell'autore, collegamenti dall'INDICE alle pagine, note editoriali numerate. Ogni lettura
  segnalata come incerta è stata controllata sulla scansione.
- **Altre correzioni e i controlli descritti sotto:** Claude (Anthropic).

## Come leggerla

- I numeri delle pagine originali sono nel margine interno; l'INDICE vi rimanda.
- Note numerate nel margine esterno:
  - **Dubbio** (119): una lettura che la scansione non decide;
  - **Stampa** (201): un apparente errore di stampa o una svista nell'edizione del 1949. Il testo conserva ciò che è
    stampato; la nota dà la lettura probabilmente intesa.

  Sostituendo `\shownotestrue` con `\shownotesfalse` nel preambolo, queste note scompaiono.
- Le pagine 284–285 mancano nella scansione: la lacuna è segnalata e nulla è stato ricostruito. Parte di p. 186 è
  illeggibile nella scansione e parte di p. 368 è coperta da un altro foglio; in entrambi i punti c'è un avviso. Chi
  può fornire una scansione di queste pagine è pregato di aprire una issue.

## Che cosa è stato controllato

- **Letture incerte.** La trascrizione ne segnalava 251; 132 sono state risolte sulla scansione, le altre 119 portano
  una nota *Dubbio*.
- **Errori di trascrizione.** Ne sono stati corretti 26, ciascuno elencato nel registro (kind `transcription error`).
- **Pagine 1–100,** confrontate per intero con la scansione. Quattro errori di trascrizione non erano segnalati come
  dubbi: p. 18 *dalle* per *delle*; p. 27 *minimo* per *minima*; p. 72 r ≥ 1 per r > 1; p. 80 un apice aggiunto a C₁.
  Sono tutti corretti. A p. 85 la scansione mostra un accento oppure una macchia: si conserva la *è* stampata, con una
  nota *Stampa*.
- **Tre pagine campione** (pp. 161, 313, 388), confrontate parola per parola e formula per formula con la scansione:
  nessun errore.

Il resto del libro (pp. 101–464) è stato finora controllato solo nei punti dubbi e nelle pagine campione, quindi vi
restano alcuni errori di trascrizione non segnalati. È previsto un confronto completo con la scansione.

## Matematica

L'edizione non corregge la matematica di Enriques. I probabili errori di stampa e le sviste sono segnalati in margine
o elencati nel registro (altre 78 proposte, non applicate al testo). È in corso un commento matematico sulle
pp. 1–100; punti ancora da verificare: un segno nel determinante di p. 45 (segnalato in margine come probabile errore
di stampa), la dimensione del sistema lineare nell'esempio di p. 89 e un passaggio dei criteri di equivalenza alle
pp. 97–100.

## Diritti

L'opera originale è di pubblico dominio nell'Unione europea: Federigo Enriques è morto nel 1946 e Guido Castelnuovo,
autore della prefazione, nel 1952. Altrove la situazione può essere diversa. Nella misura in cui deteniamo diritti
sulla trascrizione, sulle correzioni e sulla composizione tipografica prodotte da IA, tali diritti sono dedicati al
pubblico dominio con CC0 1.0. Questa edizione è pubblicata a fini educativi e senza scopo di lucro, e non
rivendichiamo diritti che non deteniamo. Se detenete diritti su quest'opera e vi opponete alla sua pubblicazione qui,
aprite una issue su GitHub e la rimuoveremo.

[pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-06/enriques_superficie_algebriche.pdf
