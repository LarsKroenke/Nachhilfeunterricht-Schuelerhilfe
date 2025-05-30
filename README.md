# Mathematik-Arbeitsblätter – Schülerhilfe

Dies ist eine Sammlung von Mathematik-Arbeitsblättern für die Schülerhilfe, erstellt mit LaTeX. Die Sammlung deckt verschiedene Themen und Klassenstufen ab und eignet sich für Unterricht, Nachhilfe und selbstständiges Üben.

## Inhalt

- Grundrechenarten (Addition, Bruchrechnung, gemischte Aufgaben)
- Lineare Gleichungssysteme (2 und 3 Unbekannte)
- Quadratische Funktionen
- Geometrie (Prismen, Oberflächen, Schrägbilder)
- Symmetrie (Punkt- und Achsensymmetrie)
- Wurzeln und Logarithmen
- Tangentengleichungen
- u.v.m.

Die Arbeitsblätter befinden sich im Ordner `Mathematik/` und sind thematisch sortiert.

## Kompilierung

Um das Projekt zu kompilieren, erstelle einen codespace auf den branch `master` und führe im Terminal folgende Befehlee aus:
```bash
sudo apt update 
sudo apt install -y texlive texlive-science texlive-latex-extra
sudo apt-get install latexmk
sudo apt-get install texlive-lang-germa
```

Das fertige PDF findest du, nachdem du das Projekt kompiliert hast, im Ordner `build/` als `main.pdf`.

> **Hinweis:** Die Datei `MeineDaten.tex` enthält persönliche Angaben (z.B. Name, Schule, Logo) und wird in `main.tex` eingebunden. Passe sie ggf. an.

## Anpassung

- Um ein anderes Arbeitsblatt einzubinden, ändere den `\input{...}`-Befehl in `main.tex`.
- Eigene Arbeitsblätter können im Ordner `Mathematik/` ergänzt werden.

## Lizenz

Dieses Projekt ist für den privaten und schulischen Gebrauch bestimmt.

---
Stand: Mai 2025
