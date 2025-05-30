# Mathematik-Arbeitsblätter – Schülerhilfe

Dies ist eine Sammlung von Mathematik-Arbeitsblättern für die Schülerhilfe, erstellt mit LaTeX. Die Sammlung deckt verschiedene Themen und Klassenstufen ab und eignet sich für Unterricht, Nachhilfe und selbstständiges Üben.

## Inhalt & Struktur

Die Arbeitsblätter sind thematisch sortiert und befinden sich in folgenden Unterordnern:

- `Mathematik/Algebra/` – z.B. lineare Gleichungssysteme, Wurzeln und Logarithmen
- `Mathematik/Analysis/` – z.B. quadratische Funktionen, Tangentengleichungen
- `Mathematik/Bruchrechnung/` – Einführung, Grundrechenarten, Addition bis 1000
- `Mathematik/Geometrie/` – Prismen, Oberflächen, Schrägbilder, Symmetrie

Weitere Fächer (z.B. Englisch) können im Hauptverzeichnis ergänzt werden.

## Kompilierung

Um das Projekt zu kompilieren, erstelle einen Codespace auf dem Branch `main` und führe im Terminal folgende Befehle aus:
```bash
sudo apt update 
sudo apt install -y texlive texlive-science texlive-latex-extra texlive-lang-german latexmk
```

Kompiliere das Hauptdokument mit:
```bash
latexmk -pdf -output-directory=build main.tex
```

Das fertige PDF findest du im Ordner `build/` als `main.pdf`.

> **Hinweis:** Die Datei `MeineDaten.tex` enthält persönliche Angaben (z.B. Name, Schule, Logo) und wird in `main.tex` eingebunden. Passe sie ggf. an.

## Anpassung

- Um ein anderes Arbeitsblatt einzubinden, ändere den `\input{...}`-Befehl in `main.tex`.
- Eigene Arbeitsblätter können in den passenden Unterordnern ergänzt werden.
- Die Ordnerstruktur sorgt für Übersichtlichkeit und thematische Trennung.

## Lizenz

Dieses Projekt ist für den privaten und schulischen Gebrauch bestimmt.

---
Stand: Mai 2025
