# Federigo Enriques, *Le superficie algebriche* (1949)

[English](README.md)

L'ultimo libro di Enriques, il suo trattato sulle superficie algebriche, pubblicato dopo la sua morte con una
prefazione di Guido Castelnuovo (Bologna: Nicola Zanichelli, 1949). Questa edizione dà l'intero libro (la prefazione di
Castelnuovo, la prefazione dell'autore, l'indice, l'introduzione e gli undici capitoli) in italiano e in inglese,
ciascuno come testo stampato e come testo corretto, con i sorgenti LaTeX modificabili.

| | come stampato | corretto |
|---|---|---|
| **Italiano** | [PDF][it-pdf] · [LaTeX](enriques_superficie_algebriche.tex) | [PDF][itc-pdf] · [LaTeX](enriques_superficie_algebriche_corretto.tex) |
| **Inglese** | [PDF][en-pdf] · [LaTeX](enriques_superficie_algebriche_EN.tex) | [PDF][enc-pdf] · [LaTeX](enriques_superficie_algebriche_EN_corrected.tex) |

- **Come stampato:** il testo della stampa del 1949, con i suoi refusi e le sviste dell'autore. Nell'italiano i
  probabili refusi e le letture dubbie sono segnalati nel margine.
- **Corretto:** 232 errori corretti: refusi della stampa e sviste dell'autore (lettere, indici, segni, numeri e
  rinvii sbagliati, sviste di calcolo), ciascuno con la modifica minima. Ogni correzione è elencata con la sua ragione
  in [`corrections_corretto.csv`](corrections_corretto.csv) (italiano) e in
  [`corrections_corrected_en.csv`](corrections_corrected_en.csv) (inglese). Le correzioni che riscriverebbero gli
  argomenti di Enriques non sono fatte nel suo testo: le discute il commento.
- **Commento:** un commento matematico all'intero libro (317 pagine, in inglese) è un'opera di accompagnamento a sé:
  [enriques-superficie-algebriche-commentary](https://github.com/KokunoYumeto/enriques-superficie-algebriche-commentary).
- **Come è stata fatta:** [METHODOLOGY.md](METHODOLOGY.md) (in inglese), con i prompt usati e i costi.

## Come è stata fatta

- **Scansione:** Maxim Leyenson.
- **Trascrizione:** prodotta da IA (OpenAI gpt-6-astra) dalla scansione.
- **Edizione:** impaginazione e correzioni prodotte da IA (ChatGPT, modalità Pro); altre correzioni: Claude (Anthropic).
- **Revisioni:** l'intero libro è stato confrontato pagina per pagina con le scansioni, in sei revisioni, da ChatGPT
  (modalità Pro).
- **Questa versione:** i risultati delle revisioni sono stati riportati nel testo (errori di trascrizione corretti,
  letture dubbie risolte, testo corretto) da Claude Opus 5.5. L'inglese è tradotto da IA (Claude Opus 5.5)
  dall'italiano come stampato. Un secondo modello (OpenAI gpt-6-astra) ha confrontato l'inglese con l'italiano; i problemi trovati sono stati valutati e corretti da Claude Opus 5.5.

Nessuna persona ha riletto l'edizione. Restano certamente degli errori: segnalateli con una issue, indicando la pagina.

## Come leggere l'edizione

- I numeri delle pagine originali stanno nel margine interno; l'indice rinvia ad essi.
- Note numerate nel margine esterno dell'edizione italiana:
  - **Dubbio** (51): una lettura che la scansione non decide;
  - **Stampa** (201): un probabile refuso o una svista della stampa del 1949. Il testo come stampato conserva
    ciò che è stampato e la nota dà la lettura probabilmente voluta; nel testo corretto la nota dice **Corretto** dove
    la correzione è stata fatta.

  Sostituendo `\shownotestrue` con `\shownotesfalse` nel preambolo si nascondono queste note. L'inglese non ha note
  nel margine.
- Mancano nella scansione le pagine 284–285. La lacuna è segnalata e nulla è stato ricostruito. Una parte di p. 186 è
  oscurata nella scansione e una parte di p. 368 è coperta da un altro foglio; entrambi i punti hanno un avviso. Se
  potete fornire scansioni di queste pagine, aprite una issue.

## Che cosa è stato controllato

- **L'intero libro,** confrontato pagina per pagina con le scansioni. Le revisioni hanno trovato altri 17 errori di
  trascrizione, ora corretti, e hanno risolto 74 letture dubbie; ne restano aperte 51, con una nota *Dubbio*.
  Ogni modifica è registrata con la sua ragione in [`corrections.csv`](corrections.csv).
- **L'inglese,** confrontato con l'italiano da uno script: ogni formula, ogni segno di pagina e ogni nota sono gli
  stessi. Un secondo modello (OpenAI gpt-6-astra) l'ha confrontato tutto con l'italiano e ha trovato 17 problemi; sono stati tutti corretti, insieme ad altri 20 punti con lo stesso tipo di problema. Nell'inglese corretto valgono 174 delle 232 correzioni; le altre 58 sono sviste di ortografia o di concordanza italiane senza corrispondente in inglese.

## Diritti

L'opera originale è di pubblico dominio nell'Unione europea: Federigo Enriques è morto nel 1946 e Guido Castelnuovo,
autore della prefazione, nel 1952. Altrove la situazione può essere diversa. Nella misura in cui deteniamo diritti
sulla trascrizione, sulla traduzione, sulle correzioni e sulla composizione tipografica prodotte da IA, tali diritti
sono dedicati al pubblico dominio con CC0 1.0. Questa edizione è pubblicata a fini educativi e senza scopo di lucro, e
non rivendichiamo diritti che non deteniamo. Se detenete diritti su quest'opera e vi opponete alla sua pubblicazione
qui, aprite una issue su GitHub e la rimuoveremo.

---

[Sostieni questo lavoro](https://github.com/sponsors/KokunoYumeto)

[it-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche.pdf
[itc-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche_corretto.pdf
[en-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche_EN.pdf
[enc-pdf]: https://github.com/KokunoYumeto/enriques-superficie-algebriche/releases/download/edizione-2026-11-08/enriques_superficie_algebriche_EN_corrected.pdf
