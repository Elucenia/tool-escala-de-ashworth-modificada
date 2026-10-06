<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · de · no clinical/professional/rights approval -->

# Modifizierte Ashworth-Skala

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-de-ashworth-modificada)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Widerstand bei passiver Bewegung (in etwa 1 Sekunde)

`grau`

- `0` — 0 – Keine Erhöhung des Muskeltonus
- `1` — 1 – Leichte Zunahme: kurzer Widerstand und Nachgeben oder minimaler Widerstand am Bewegungsende
- `2` — 2 – Deutlichere Zunahme über den größten Teil des Bewegungsumfangs, das Segment bleibt leicht beweglich
- `3` — 3 – Erhebliche Zunahme: passive Bewegung erschwert
- `4` — 4 – Segment in Beugung oder Streckung starr
- `1p` — 1+ – Leichte Zunahme: kurzer Widerstand gefolgt von minimalem Widerstand auf weniger als der Hälfte des Bewegungsumfangs

## Fassung der Methode

Modifizierte Ashworth/Bohannon–Smith 1987: 0/1/1+/2/3/4; eigene Stufe 1+

## Dokumentierte Formel

Bei entspanntem Patienten in Rückenlage das Segment in etwa 1 Sekunde passiv durch den gesamten Bewegungsumfang bewegen und den Widerstandsgrad wählen. Bohannon und Smith ergänzten 1+ zur ursprünglichen Ashworth-Skala.

## Grenzen und Population

Klinische Einstufung des Widerstands bei passiver Bewegung, getrennt von Muskelkraft. Die ursprüngliche Zuverlässigkeitsstudie untersuchte Ellenbogenbeuger bei Patienten mit intrakranieller Läsion. Diese Leistung lässt sich nicht automatisch auf jedes Gelenk oder jede neurologische Erkrankung übertragen.

## Referenzen

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Keine Tonuszunahme


### 2

Leichte Tonuszunahme in weniger als der Hälfte des Bewegungsumfangs


### 3

Deutliche Tonuszunahme: passive Bewegung schwierig

