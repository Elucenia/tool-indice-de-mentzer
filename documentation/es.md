<!-- ELUCENIA technical documentation · indice-de-mentzer · es · no clinical/professional/rights approval -->

# Índice de Mentzer

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/indice-de-mentzer)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Volumen corpuscular medio (VCM)

`vcm`

fL · intervalo: 40–130

### Eritrocitos

`hem`

millones/µL · intervalo: 1–9

## Edición del método

Mentzer 1973: VCM/hematíes, millones/µL; regla de cribado, no diagnóstico

## Fórmula documentada

Índice de Mentzer = VCM (fL) ÷ hematíes (millones/µL).

## Límites y población

El índice de Mentzer es una regla de cribado en microcitosis, calculada con VCM en fL y hematíes en millones/µL, no con la cifra bruta por µL. No confirma ferropenia ni rasgo talasémico. El metaanálisis de Hoffmann 2015 mostró que los índices discriminantes no tienen sensibilidad y especificidad del 100% y, en conjunto, rindieron mejor en adultos que en niños. Los resultados sugestivos requieren investigación confirmatoria; no se presume la misma exactitud en todas las poblaciones.

## Referencias

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Índice < 13: sugiere rasgo de talasemia (β o α)

El índice orienta, pero no diagnostica: confirme con ferritina y electroforesis de hemoglobina (HbA2).


### 2

Índice > 13: sugiere anemia ferropénica

El índice orienta, pero no diagnostica: confirme con ferritina y electroforesis de hemoglobina (HbA2).


### 3

Índice = 13: indeterminado

El índice orienta, pero no diagnostica: confirme con ferritina y electroforesis de hemoglobina (HbA2).

