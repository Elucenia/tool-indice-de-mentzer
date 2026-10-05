<!-- ELUCENIA technical documentation · indice-de-mentzer · de · no clinical/professional/rights approval -->

# Mentzer-Index

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/indice-de-mentzer)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Mittleres korpuskuläres Volumen (MCV)

`vcm`

fL · Bereich: 40–130

### Erythrozyten

`hem`

Millionen/µL · Bereich: 1–9

## Fassung der Methode

Mentzer 1973: MCV/Erythrozyten, Millionen/µL; Screeningregel, keine Diagnose

## Dokumentierte Formel

Mentzer-Index = MCV (fL) ÷ Erythrozyten (Millionen/µL).

## Grenzen und Population

Der Mentzer-Index ist eine Screeningregel bei Mikrozytose, berechnet mit MCV in fL und Erythrozyten in Millionen/µL, nicht mit der unskalierten Anzahl pro µL. Er bestätigt weder Eisenmangel noch einen Thalassämie-Trägerstatus. Die Metaanalyse von Hoffmann 2015 zeigte, dass diskriminierende Indizes keine Sensitivität und Spezifität von 100% aufweisen und insgesamt bei Erwachsenen besser abschnitten als bei Kindern. Hinweisende Ergebnisse erfordern bestätigende Untersuchungen; eine identische Genauigkeit in allen Populationen wird nicht vorausgesetzt.

## Referenzen

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
