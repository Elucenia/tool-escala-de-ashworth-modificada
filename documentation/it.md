<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · it · no clinical/professional/rights approval -->

# Scala di Ashworth modificata

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-de-ashworth-modificada)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Resistenza al movimento passivo (in circa 1 secondo)

`grau`

- `0` — 0 – Nessun aumento del tono muscolare
- `1` — 1 – Lieve aumento: scatto e rilascio o resistenza minima alla fine dell’arco di movimento
- `2` — 2 – Aumento più marcato nella maggior parte dell’arco, ma il segmento si muove facilmente
- `3` — 3 – Aumento considerevole: movimento passivo difficile
- `4` — 4 – Segmento rigido in flessione o estensione
- `1p` — 1+ – Lieve aumento: scatto seguito da resistenza minima per meno della metà dell’arco

## Edizione del metodo

Ashworth modificata/Bohannon–Smith 1987: 0/1/1+/2/3/4; grado 1+ specifico

## Formula documentata

Con paziente rilassato supino, muovere passivamente il segmento nell’intero arco in circa 1 secondo e scegliere il grado di resistenza. Bohannon e Smith aggiunsero 1+ alla scala originale.

## Limiti e popolazione

Graduazione clinica della resistenza al movimento passivo, distinta dalla forza muscolare. Lo studio originale di affidabilità ha esaminato i flessori del gomito in pazienti con lesione intracranica. Tali prestazioni non possono essere trasferite automaticamente a ogni articolazione o condizione neurologica.

## Riferimenti

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
