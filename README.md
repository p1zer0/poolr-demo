# POOLR — Text to clip plan and SRT

[Try the interactive example without signing in](https://poolr-creator-preflight.robust-isle-8072.chatgpt.site/demo) · [Get the Creator Preflight Kit](https://poolr-creator-preflight.robust-isle-8072.chatgpt.site/)

A small, fixed three-scene example: select 15, 30 or 45 seconds, preview timed subtitles and download the example as JSON or SRT. Open index.html locally; no installation or API key is needed. Nothing is uploaded.

The full Creator Preflight Kit lets you plan and edit your own projects offline, estimate costs using your own rates and export JSON/SRT. Three scene recipes are included. Online workflows and private preferences are an optional beta for verified kit buyers.

**19 EUR once, no subscription.** The kit is in English. Purchases are currently available to residents of Germany. The full kit is sold under its separate buyer license and is not included in this repository.

This is planning and subtitle tooling, not video rendering or audio synchronization. No reach or income is promised.

## SRT-Untertitel kostenlos prüfen — ohne Upload

[Öffne den kostenlosen SRT-Check](https://poolr-creator-preflight.robust-isle-8072.chatgpt.site/untertitel-pruefen). Füge bis zu 60 Untertitel beziehungsweise 16.000 Zeichen ein. Die Prüfung läuft im Browser; der Text wird nicht hochgeladen oder gespeichert. Zeitformat, nicht aufsteigende Zeiten und Überschneidungen werden geprüft. Ein Hinweis auf mehr als 20 Zeichen pro Sekunde ist ein Prüfwert, keine allgemeingültige Lesbarkeitsnorm.

**Ein konkreter Fehler:** In [diesem Beispiel](examples/overlap.srt) endet die erste Zeile bei 3,000 Sekunden; die zweite beginnt schon bei 2,500 Sekunden. Der Check meldet die Überschneidung. [Die korrigierte Variante](examples/non-overlapping.srt) zeigt eine spätere Startzeit. Ob diese Verschiebung zum gesprochenen Text passt, musst du an deiner Tonspur prüfen.

[Kurzanleitung: drei Untertitel-Prüfungen](subtitle-check-guide.txt)

Wenn du zusätzlich Szenen und Kosten planen sowie JSON/SRT exportieren möchtest, sieh dir [das feste Clip-Plan-Beispiel](https://poolr-creator-preflight.robust-isle-8072.chatgpt.site/demo) an. Das optionale Offline-Kit kostet einmalig **19 €**, ist **auf Englisch** und wird derzeit an Personen mit Wohnsitz in **Deutschland** verkauft. Es erstellt keine fertigen Videos.

## What is public here

- index.html: the standalone interactive fixed example
- sample.json and sample.srt: the 30-second example output
- LICENSE: MIT license for these sample files only

Seller details, support, privacy and purchase terms are available at the [storefront](https://poolr-creator-preflight.robust-isle-8072.chatgpt.site/).
