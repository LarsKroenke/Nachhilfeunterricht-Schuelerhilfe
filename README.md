# Arbeitsblätter – Schülerhilfe

Dies ist eine Sammlung von Arbeitsblättern für die Schülerhilfe, erstellt mit LaTeX. Die Sammlung deckt verschiedene Themen und Klassenstufen ab und eignet sich für Unterricht, Nachhilfe und selbstständiges Üben.

## Inhalt & Struktur

Die Arbeitsblätter sind thematisch und nach Fächern sortiert:

- `Mathematik/Algebra/` – z.B. lineare Gleichungssysteme, Terme, Logarithmen
- `Mathematik/Analysis/` – z.B. quadratische Funktionen, Tangentengleichungen
- `Mathematik/Bruchrechnung/` – Einführung, Grundrechenarten, Aufgabenblätter
- `Mathematik/Geometrie/` – Prismen, Oberflächen, Schrägbilder, Symmetrie, Satz des Pythagoras
- `Mathematik/Grundrechenarten/` – Addition, Subtraktion (bis 1000)
- `Mathematik/Erklärungen/` – Kurze Zusammenfassungen und Erklärungen
- `Chemie/` – z.B. Stöchiometrie, Säuren und Basen
- `Englisch/` – z.B. Zeitformen, Reading Comprehension

Weitere Fächer und Themen können ergänzt werden. Die Ordnerstruktur sorgt für Übersichtlichkeit und thematische Trennung.

## Kompilierung

Um das Projekt zu kompilieren, installiere die nötigen Pakete (z.B. in einem Codespace oder lokal):

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

## Anpassung & Erweiterung

- Um ein anderes Arbeitsblatt einzubinden, ändere den `\input{...}`-Befehl in `main.tex`.
- Eigene Arbeitsblätter können in den passenden Unterordnern ergänzt werden.
- Die Ordnerstruktur bitte beibehalten, um Übersichtlichkeit zu gewährleisten.
- Für neue Fächer einfach einen neuen Unterordner im Hauptverzeichnis anlegen.

## Hinweise

- Die Datei `.gitignore` sorgt dafür, dass nur relevante Dateien versioniert werden.
- Leere Ordner werden durch `.keep`-Dateien erhalten.
- TikZ wird für Visualisierungen genutzt (z.B. in Geometrie-Aufgaben).

## Lizenz

Dieses Projekt ist für den privaten und schulischen Gebrauch bestimmt.

---
Stand: Mai 2025
