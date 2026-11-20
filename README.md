# WortKompass – Version 0.14

Deutschsprachiges Worträtsel mit fünf oder sechs Buchstaben. Für Smartphones, Tablets und PCs, kostenfrei über GitHub Pages.

## Spiel

- 5 Buchstaben: 6 Versuche
- 6 Buchstaben: **Leicht** 7 Versuche oder **Mittel** 6 Versuche
- Tägliches Rätsel (identisch für alle bei gleicher Wortlänge) und beliebig viele freie Spiele
- Ä, Ö, Ü sowie ß als eigener Buchstabe
- Freiwilliger Spitzname, Statistik ausschließlich im jeweiligen Browser
- Export der Wortlisten als CSV

## Zentrale Pflege der Wörter

Die vier im Browser geladenen Listen liegen im Verzeichnis [wortlisten](./wortlisten):

| Datei | Bedeutung |
| --- | --- |
| [loesungen-5.txt](./wortlisten/loesungen-5.txt) | 5-Buchstaben-Lösungen für **neue freie Spiele** |
| [loesungen-6.txt](./wortlisten/loesungen-6.txt) | 6-Buchstaben-Lösungen für **neue freie Spiele** |
| [ratewoerter-5.txt](./wortlisten/ratewoerter-5.txt) | Zulässige 5-Buchstaben-Ratewörter |
| [ratewoerter-6.txt](./wortlisten/ratewoerter-6.txt) | Zulässige 6-Buchstaben-Ratewörter |

Jede Datei enthält **ein Wort pro Zeile**. In GitHub die Datei öffnen → Stiftsymbol (Edit this file / Datei bearbeiten) → ändern → Commit changes (Änderungen übernehmen). Nach der automatischen Pages-Veröffentlichung und einem Neuladen werden die Listen für alle Geräte aktualisiert.

**Achtung:** Neue Lösungswörter müssen auch als Ratewörter aufgeführt werden. Falsche oder zu kurze Einträge werden von der App beim Laden gefiltert. Für neue Tagesrätsel ist eine gesonderte Versionierung vorgesehen, damit nicht unterschiedliche Spieler am gleichen Tag unterschiedliche Lösungen bekommen.

**Wichtig:** Wortlistenänderungen innerhalb der App gelten weiterhin ausschließlich lokal. Nur Änderungen im GitHub-Repository gelten für alle.

## Veröffentlichung

GitHub Pages: **Settings / Einstellungen → Pages / Seiten → Deploy from a branch / Bereitstellung von einem Branch → main / Hauptzweig → / (root) / Wurzel**.

Adresse: https://johannheinrichkruse.github.io/WortKompass/

## Herkunft, Lizenz und Qualität

[WORTLISTEN-QUELLEN.md](./WORTLISTEN-QUELLEN.md) beschreibt die beiden CC0-Datensammlungen, Herkunft, Normalisierung und bekannte Qualitätsgrenzen.

Die Ratewörterbücher sind erweitert, aber nicht vollständig: korrekte Beugungsformen und weitere Wörter können fehlen. Eine endgültige Wörterbuch-Einzelprüfung ist offen.

## Daten

Spielername, Statistik und Spielstände verbleiben im Browser. Keine Registrierung und kein Server mit personenbezogenen Spielständen. Daten werden nicht zwischen Geräten synchronisiert.
