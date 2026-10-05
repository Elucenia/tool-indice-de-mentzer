<!-- ELUCENIA technical documentation · indice-de-mentzer · fr · no clinical/professional/rights approval -->

# Indice de Mentzer

[conditions, sources et autorisations](https://elucenia.org/fr/outils/indice-de-mentzer)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Volume globulaire moyen (VGM)

`vcm`

fL · intervalle: 40–130

### Hématies

`hem`

millions/µL · intervalle: 1–9

## Édition de la méthode

Mentzer 1973 : VGM/hématies, millions/µL ; règle de dépistage, pas diagnostic

## Formule documentée

Indice de Mentzer = VGM (fL) ÷ hématies (millions/µL).

## Limites et population

L’indice de Mentzer est une règle de dépistage en cas de microcytose, calculée avec le VGM en fL et les hématies en millions/µL, et non avec le nombre brut par µL. Il ne confirme ni une carence en fer ni un trait thalassémique. La méta-analyse de Hoffmann 2015 a montré que les indices discriminants n’ont pas une sensibilité et une spécificité de 100% et, globalement, fonctionnaient mieux chez les adultes que chez les enfants. Un résultat suggestif exige des investigations confirmatoires ; la même exactitude n’est pas présumée dans toutes les populations.

## Références

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
