<!-- ELUCENIA technical documentation · indice-de-mentzer · it · no clinical/professional/rights approval -->

# Indice di Mentzer

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/indice-de-mentzer)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Volume corpuscolare medio (MCV)

`vcm`

fL · intervallo: 40–130

### Eritrociti

`hem`

milioni/µL · intervallo: 1–9

## Edizione del metodo

Mentzer 1973: MCV/eritrociti, milioni/µL; regola di screening, non diagnosi

## Formula documentata

Indice di Mentzer = MCV (fL) ÷ eritrociti (milioni/µL).

## Limiti e popolazione

L’indice di Mentzer è una regola di screening nella microcitosi, calcolata con MCV in fL ed eritrociti in milioni/µL, non con la conta grezza per µL. Non conferma carenza di ferro né tratto talassemico. La metanalisi di Hoffmann 2015 ha mostrato che gli indici discriminanti non hanno sensibilità e specificità del 100% e, complessivamente, funzionavano meglio negli adulti che nei bambini. Risultati suggestivi richiedono indagini di conferma; non si presume la stessa accuratezza in tutte le popolazioni.

## Riferimenti

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

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

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Indice < 13: suggerisce tratto talassemico (β o α)

L’indice orienta, ma non diagnostica: confermare con ferritina ed elettroforesi dell’emoglobina (HbA2).


### 2

Indice > 13: suggerisce anemia sideropenica

L’indice orienta, ma non diagnostica: confermare con ferritina ed elettroforesi dell’emoglobina (HbA2).


### 3

Indice = 13: indeterminato

L’indice orienta, ma non diagnostica: confermare con ferritina ed elettroforesi dell’emoglobina (HbA2).

