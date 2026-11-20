# WortKompass V0.14 – Quellen, Lizenz und Qualitätsstand

## Wortlisten

Die vier Dateien im Verzeichnis `wortlisten/` sind aus folgenden Beständen zusammengeführt, bereinigt und normalisiert:

1. Bisherige WortKompass-Listen (Version 0.13, selbst zusammengestellte redaktionelle Arbeitsliste, noch nicht vollständig lexikografisch belegt).
2. YNodd/Wortliste_deutsch, Datei `Wortliste_deutsch.csv`, Blob-SHA `44fc034085d68baa5454b058746714d489a28c30`:
   https://github.com/YNodd/Wortliste_deutsch
   Quelle ist der deutsche Wortschatz des Lëtzebuerger Online Dictionnaire (LOD). Repository-Lizenz: CC0 1.0. 
   Der amtliche LOD-Datensatz wird auf data.public.lu ebenfalls unter CC0 veröffentlicht:
   https://data.public.lu/en/datasets/letzebuerger-online-dictionnaire-lod-linguistesch-daten/
3. dys2p/wordlists-de, Datei `de-7776-v1.txt`:
   https://github.com/dys2p/wordlists-de
   Lizenzwahl laut Repository: Unlicense, CC0 1.0 oder BSD-3-Clause. Für dieses Projekt CC0 1.0 gewählt.
4. Manuell geprüfte und gemeldete Wörter aus den Spieltests, insbesondere EINEN, EIBEN, GÄNSEN, STOẞEN, RASTER, BRÜSTE u.a.

## Regeln

- Jede Datei: ein Wort pro Zeile, UTF-8, Großbuchstaben, 5 bzw. 6 Zeichen.
- Ä, Ö, Ü und ẞ sind eigene Buchstaben. Die Normalform verwendet ẞ (großes ß).
- Jeder Lösungsbegriff wird auch als Ratewort akzeptiert.
- Lösungswörter: gebräuchliche Begriffe, einschließlich ausgewählter Pluralformen. Die bestehende Auswahl ist noch nicht vollständig einzeln geprüft.
- Ratewörter: größerer Wortbestand, einschließlich geeigneter Beugungsformen, soweit enthalten.
- Fantasiewörter werden durch den festen Wortbestand zurückgewiesen, ohne einen Versuch zu verbrauchen.
- Bei GitHub-Änderungen sorgfältig prüfen: Ein bloßes Wortmuster beweist keine lexikografische Gültigkeit.

## Tagesrätsel & Updates

- Das aktuelle Tagesrätsel wird aus der fest eingebauten Version-0.13-Lösungsliste bestimmt, um bereits laufende Tagesrätsel nicht durch Sortierung oder Ergänzung der externen Listen zu ändern.
- Die externen Lösungslisten wirken auf neue freie Spiele. Die externen Ratewortlisten wirken nach Laden auf beide Spielmodi.
- Bestehende Browser-Statistik und gespeicherte Spiele werden beibehalten.
- Aus Sicherheitsgründen nutzt die App bei Ladefehlern weiterhin die ältere eingebettete Grundliste.
- Zum Aktualisieren im Browser Seite neu laden; bei Bedarf Browsercache aktualisieren.

## Einschränkungen

Die Wortbestände sind ein wesentlich vergrößerter, nicht vollständig lexikografisch geprüfter Arbeitsbestand. Auch echte Wörter können noch fehlen, und seltene oder fehlerhafte Altformen können vorkommen.
CC0-Hinweise der Quellen minimieren Lizenzrisiken, stellen jedoch keine Rechtsgarantie für alle im Projekt enthaltenen oder von Dritten abgeleiteten Daten dar.
Programmcode: bislang keine eigene Open-Source-Lizenz festgelegt; die Datensatz-Lizenzen regeln nicht automatisch den Programmcode.

## Quellenstand

Stand: November 2026. Quellen werden bei einer weiteren Versionierung mit Änderungsnachweis aktualisiert.
