# Angepasste Startseite

Diese Startseite basiert auf **Start Page Tab** von [Tacoz](https://addons.mozilla.org/en-US/firefox/addon/start-page-tab/). Die bearbeitete Seite liegt in `index.html` und `index.js` im Hauptordner dieses Projekts. Die gleichnamigen Dateien unter `img/` sind ältere Kopien und werden von der Startseite nicht geladen.

## Funktionen

- Farben, Hintergrund und Schriftart lassen sich in den Einstellungen ändern. Du kannst eine Google Font oder eine auf deinem Gerät installierte Schrift angeben.
- Der Stundenplan hat zehn Stunden pro Wochentag. Die Fächer werden in den Einstellungen eingetragen; rechts unten erscheinen die aktuelle und die folgenden Stunden.
- Einstellungen und Fächer werden im jeweiligen Browser gespeichert. Eine andere Person kann die Seite mit eigenen Einstellungen verwenden.

## Starten und weitergeben

Öffne `index.html` direkt im Browser. Dafür ist kein Live Server nötig. Wenn die Seite auf jedem neuen Firefox-Tab erscheinen soll, veröffentliche die **Dateien dieses Hauptordners** als statische Webseite und trage deren Adresse in einer Erweiterung zur Anpassung neuer Tabs ein. Die Original-Erweiterung von Mozilla enthält diese Änderungen nicht.

Gib beim Teilen dieses Projekts auch `README.md`, `LICENSE`, `index.html`, `index.js` und die benötigten Dateien aus `img/` weiter. Installierte Schriften müssen auf dem Gerät der anderen Person ebenfalls vorhanden sein; Google Fonts werden über das Internet geladen.

## Stundenzeiten

Die im Code eingestellten Zeitfenster orientieren sich an den [veröffentlichten Sprechstunden der HTL Dornbirn](https://www.htldornbirn.at/schule/lehrpersonen). Sie sind keine von der Schule veröffentlichte vollständige Stundentafel.

| Stunde | Zeit |
| --- | --- |
| 1 | 07:55–08:45 |
| 2 | 08:45–09:35 |
| 3 | 09:50–10:40 |
| 4 | 10:40–11:30 |
| 5 | 11:30–12:20 |
| 6 | 12:20–13:10 |
| 7 | 13:10–14:00 |
| 8 | 14:00–14:50 |
| 9 | 15:00–15:50 |
| 10 | 15:50–16:40 |

## Lizenz, Ursprung und Änderungen

Die [Original-Erweiterung bei Mozilla](https://addons.mozilla.org/en-US/firefox/addon/start-page-tab/) nennt **Tacoz** als Urheber und ist als **GNU General Public License v3.0 only (GPL-3.0-only)** gekennzeichnet. Der [ursprüngliche Quellcode](https://github.com/tms-h/startpage) ist hier verlinkt. Der vollständige Lizenztext steht in [LICENSE](LICENSE). Die Bearbeitungen dieser Fassung werden ebenfalls unter GPL-3.0-only weitergegeben.

**Änderungshinweis vom 17. September 2026:** Gegenüber dem Original wurden die freie Schriftwahl, der Stundenplan mit zehn Stunden für Montag bis Freitag sowie die Eingabe und die Anzeige des Stundenplans ergänzt beziehungsweise überarbeitet. Die Hinweise stehen auch am Anfang von `index.html` und `index.js`.

Bei einer Weitergabe müssen der Lizenztext, der Hinweis auf den ursprünglichen Urheber und der Hinweis auf die Änderungen erhalten bleiben.
