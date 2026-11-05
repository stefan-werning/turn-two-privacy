# Turn Two – Datenschutzerklärung / Privacy Policy

Statische GitHub-Pages-Seite mit der Datenschutzerklärung für die Android-App
**Turn Two** (`eu.aifiles.turntwo`). Sie wird im Google-Play-Store-Formular als
Datenschutz-URL eingetragen.

- Deutsch: <https://stefan-werning.github.io/turn-two-privacy/>
- English: <https://stefan-werning.github.io/turn-two-privacy/privacy-en.html>

## Veröffentlichen

1. Repository `turn-two-privacy` auf GitHub anlegen (öffentlich, ohne README).
2. `git push -u origin main`.
3. Unter *Settings → Pages* als Source **„GitHub Actions"** wählen.
   Der Workflow `.github/workflows/pages.yml` veröffentlicht danach jeden Push
   auf `main` automatisch; ein Push lässt sich auch manuell unter *Actions*
   neu starten.
4. Nach ein bis zwei Minuten sind beide URLs erreichbar.

Änderungen an der Erklärung: die betroffene HTML-Datei bearbeiten, committen und
pushen. GitHub Pages baut die Seite automatisch neu.

## Hinweise für „Datensicherheit" in der Play Console

Die Angaben müssen zur tatsächlichen App passen; diese Übersicht ist nur eine
Gedächtnisstütze:

| Bereich | In Turn Two |
|---|---|
| Personenbezogene Daten | Name (Spielername), optional Avatar-Emoji |
| Nachrichten | Chat-Nachrichten zwischen Mitspielern |
| App-Aktivität | Partien, Züge, Ergebnisse, Freundesliste |
| Geräte- oder andere IDs | Firebase Installation ID (nur bei aktivem Push) |
| Standort, Kontakte, Fotos, Gesundheit, Zahlungen | nicht erhoben |
| Werbung, Analyse, Tracking | nicht vorhanden |
| Datenweitergabe zu Werbezwecken | keine |
| Verschlüsselung bei der Übertragung | ja (TLS) |
| Löschung | per E-Mail an support@ai-files.eu (Abschnitt 12) |

Firebase Cloud Messaging ist ein Auftragsverarbeiter für den Versand der
Push-Nachrichten, kein Werbedienst.
