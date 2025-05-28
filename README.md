# Schülerhilfe – Mathematik Arbeitsblätter

Dies ist eine Sammlung von Mathematik-Arbeitsblättern für die Schülerhilfe Aurich. Die Arbeitsblätter sind im LaTeX-Format erstellt und eignen sich zum Ausdrucken für den Unterricht oder die Nachhilfe.

## Inhalt
- **Bruchrechnung (5. Klasse):** Grundrechenarten mit Brüchen, inklusive Textaufgaben
- **Tangentengleichungen:** Aufgaben zum Aufstellen von Tangentengleichungen (weitere Themen können ergänzt werden)

## Struktur
- `main.tex`: Hauptdatei zum Kompilieren der Arbeitsblattsammlung
- `Mathematik/`: Enthält die thematischen Arbeitsblätter als einzelne `.tex`-Dateien
- `build/`: Enthält die generierte PDF-Datei (`main.pdf`) und temporäre LaTeX-Dateien

## Kompilierung
Um die Arbeitsblätter als PDF zu erhalten, führe im Projektordner folgenden Befehl aus:

```
pdflatex -output-directory=build main.tex
```

Das fertige PDF befindet sich dann in `build/main.pdf`.

## Hinweise
- Die Datei `.gitignore` sorgt dafür, dass nur das fertige PDF (`build/main.pdf`) versioniert wird, nicht aber temporäre Dateien.
- Die Arbeitsblätter können beliebig erweitert oder angepasst werden.

---
© Schülerhilfe Aurich, Lars Krönke