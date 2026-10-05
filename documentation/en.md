<!-- ELUCENIA technical documentation · indice-de-mentzer · en · no clinical/professional/rights approval -->

# Mentzer index

[conditions, sources and permissions](https://elucenia.org/en/tools/indice-de-mentzer)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Mean corpuscular volume (MCV)

`vcm`

fL · range: 40–130

### Red blood cells

`hem`

million/µL · range: 1–9

## Method edition

Mentzer 1973: MCV/red cells, millions/µL; screening rule, not diagnosis

## Documented formula

Mentzer index = MCV (fL) ÷ red cells (millions/µL).

## Limits and population

Mentzer index is a screening rule in microcytosis, calculated with MCV in fL and red blood cells in millions/µL, not the raw count per µL. It does not confirm iron deficiency or thalassemia trait. The Hoffmann 2015 meta-analysis showed that discriminant indices do not have 100% sensitivity and specificity and, collectively, performed better in adults than in children. Suggestive results require confirmatory investigation; identical accuracy in every population is not assumed.

## References

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
