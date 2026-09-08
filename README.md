# P-Konto-Bescheinigung – Online-Formular

Interaktive, browserbasierte Ausfüllhilfe für die **Bescheinigung nach § 903 Abs. 1 ZPO** über die gemäß §§ 902 und 904 ZPO von der Pfändung nicht erfassten Beträge auf einem Pfändungsschutzkonto (P-Konto).

**Live-Version:** wird nach dem Deploy hier verlinkt (GitHub Pages).

## Funktionen

- Bildet alle Abschnitte der Musterbescheinigung ab (I. Bescheinigende Stelle, II. Kontoinhaber:in, III. pfändungsfreier Betrag, IV. weitere laufende Geldleistungen, V. einmaliger Freibetrag).
- Rechnet den **monatlichen Gesamtfreibetrag** und den **einmaligen Freibetrag** automatisch aus den angehakten Positionen zusammen.
- Grundfreibetrag und Erhöhungsbeträge (§ 899, § 902 ZPO) sind als editierbare Felder hinterlegt (Stand 01.07.2024: 1.500,00 € / 561,43 € / 312,78 €) – da sich diese Beträge jährlich zum 01.07. ändern, bitte vor Gebrauch mit dem aktuellen Wert abgleichen und ggf. anpassen.
- Alle Eingaben werden **ausschließlich lokal im Browser** (`localStorage`) zwischengespeichert. Es gibt kein Backend, keine Datenbank und keine Übertragung an einen Server – die Seite ist eine reine statische HTML-Datei.
- Druckansicht / "Als PDF speichern" über den Browser-Druckdialog, inkl. Unterschriftszeile.

## Nutzung

Einfach die Seite öffnen, ausfüllen, bei Bedarf über "Drucken / als PDF speichern" ausdrucken oder als PDF sichern und unterschreiben/stempeln.

## Hinweis zur Quelle

Die inhaltliche Struktur folgt der Musterbescheinigung der Arbeitsgemeinschaft Schuldnerberatung der Verbände (AG SBV) vom 21.09.2021, in Absprache mit der Deutschen Kreditwirtschaft (DK), Stand 01.07.2024. Diese Vorlage steht unter der [CC BY-ND 3.0 DE Lizenz](https://creativecommons.org/licenses/by-nd/3.0/de/) (Namensnennung, keine Bearbeitung). Dieses Repository enthält **keine Kopie des Originaldokuments**, sondern eine eigenständig programmierte, interaktive Ausfüllhilfe auf Basis der darin definierten gesetzlichen Positionen (§§ 902, 903, 904 ZPO). Für den offiziellen Wortlaut und bei Zweifeln an der Aktualität der Beträge sollte zusätzlich das Originalformular herangezogen werden.

## Lokal öffnen / entwickeln

Die Seite besteht aus einer einzigen Datei (`index.html`, HTML/CSS/JS inline, keine Abhängigkeiten). Einfach im Browser öffnen oder z. B. mit `python3 -m http.server` lokal ausliefern.

---
🤖 Erstellt mit [Claude Code](https://claude.com/claude-code)
