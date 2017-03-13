When Sysadmins Ruled the Earth
==============================

Theaterstück des c-atre collectivdrama nach einer Kurzgeschichte von Cory Doctorow.

„When Sysadmins Ruled the Earth“ ist eine postapokalyptische Science Fiction-Kurzgeschichte von Cory Doctorow. Sie wurde in der Kurzgeschichten- und Novellensammlung „Overclocked: Stories of the Future Present“ (Thunder’s Mouth Press, ISBN 1-56025-981-7) 2007 veröffentlicht.

[CC BY-NC-SA 2.5](https://creativecommons.org/licenses/by-nc-sa/2.5)

Hier das Orginal zum Download: [http://craphound.com/overclocked/download/](http://craphound.com/overclocked/download/)

Die hier veröffentlichte Version wurde vom c-atre collectivdrama ins deutsche übersetzt und als Bühnenstück umgearbeitet. 

## Dokumente erstellen
Zum Erstellen der auf [unserer Webseite](https://c-atre.de/produktionen/when-sysadmins-rule-the-earth/data/) Dokumente verwenden wir [Pandoc](http://johnmacfarlane.net/pandoc/) und das Tool `ebook-convert` des E-Book-Managers [Calibre](http://calibre-ebook.com/) (zum erstellen von MOBI- aus EPUB-Datein). Beide Programme sind für alle gängigen Betriebssysteme verfügbar.

Für Menschen die mit dem Build-Tool `make` vertraut sind stellen wir eine Makefile bereit. Damit könnt ihr den Text umwandeln in

* eine **HTML-Webseite**,

```bash
make html
```

* ein **EPUB-E-Book**,

```bash
make epub
```

* ein **MOBI-E-Book** oder

```bash
make mobi
```

* ein **PDF-Dokument** (hierzu wird [LibreOffice](https://de.libreoffice.org/) benötigt).

```bash
make pdf
```

Außerdem können alle Dokumententypen gleichzeitig erstellt werden:

```bash
make
```
