# Info zur Latex-Vorlage

## Tools (Linux)
* ./clean - Löscht von Latex erzeugte Dateien
* ./build - Erzeugt die Bibliographie, Glossar, die fertige PDF-Datei und die fertige DVI-Datei

## Problembehebung
* biber, biblatex und makeglossaries müssen installiert sein
* den Befehl "makeglossaries index" ausführen um das Abkürzungsverzeichnis zu erstellen
* den Befehl "biber index" ausführen um die Bibliographie zu erzeugen
* sollte das Inhaltsverzeichnis nach dem Erzeugen nich aktuell sein, dann
das Programm (./build, pdflatex oder latex) einfach nochmal ausführen
