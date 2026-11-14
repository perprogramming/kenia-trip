# AGENTS.md – Hinweise für KI-Agenten

Dieses Dokument beschreibt, wie KI-Agenten (z. B. Claude) bei der Planung dieser Kenia-Reise mithelfen sollen.

## Kontext

Vier Erwachsene planen eine Kenia-Reise 2027 (ca. zwei Wochen, Samstag bis Samstag).
Die Planung wird schrittweise in diesem Repository aufgebaut.

## Sprache

**Alle Ausgaben und Dateien auf Deutsch.** Auch wenn eine Frage auf Englisch gestellt wird,
bitte auf Deutsch antworten und Dateien auf Deutsch befüllen.

## Aufgaben für Agenten

- Neue Informationen in die passenden Dateien eintragen (siehe Dateistruktur weiter unten)
- Offene Fragen als `- [ ] Frage: ...` in `README.md` oder der jeweiligen Datei ergänzen
- Keine Annahmen über Budget, Vorlieben oder Reiseziele machen, die nicht explizit genannt wurden
- Bei Unsicherheiten nachfragen, statt zu raten

## Planungsprinzipien

1. **Schrittweise vorgehen** – erst Grundgerüst, dann Details
2. **Nichts doppelt erfassen** – jede Information hat eine Heimatdatei
3. **Entscheidungen festhalten** – einmal Entschiedenes als `[x]` markieren
4. **Quellen nennen** – bei Recherchen (Preise, Visa, Impfungen) Quelle und Datum angeben

## Dateistruktur

| Datei | Inhalt |
|---|---|
| `README.md` | Übersicht für Menschen |
| `CLAUDE.md` | Einstiegspunkt für Claude Code |
| `AGENTS.md` | Diese Datei – Hinweise für Agenten |
| `reisende.md` | Details zu den Reisenden (Pässe, Wünsche) |
| `reiseziele.md` | Orte, Route, Tagesplanung |
| `unterkunft.md` | Lodges, Hotels, Camps |
| `budget.md` | Kostenübersicht und Budgetrahmen |
| `packliste.md` | Packliste für Safari und Küste |
| `docs/` | Öffentliche Webseite (GitHub Pages) |

Dateien, die noch nicht existieren, werden angelegt, sobald das Thema relevant wird.

## Webseite (GitHub Pages)

Die Reiseplanung wird als Webseite unter https://perprogramming.github.io/kenia-trip/ veröffentlicht.

- Alle HTML-Dateien liegen im Ordner `docs/`
- Startseite: `docs/index.html`
- Neue Inhalte (Reiseziele, Unterkunft, etc.) bekommen je eine eigene Unterseite in `docs/`
- Die Webseite soll übersichtlich und mobilfreundlich sein
- Sprache der Webseite: Deutsch
- Beim Ergänzen von Planungsinhalten immer auch die entsprechende Seite in `docs/` aktualisieren
