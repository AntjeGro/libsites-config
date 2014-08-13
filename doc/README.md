Dieses Verzeichnis enthält die Dokumentation zur Konfiguration der
GBV-Standortverwaltung. Zum Aktualisieren der Dokumentation werden pandoc,
XeTeX, KOMA-script und einige andere LaTeX-pakete benötigt:

    sudo apt-get install pandoc texlive-xetex texlive-latex-recommended textlive-latex-extra texlive-fonts-recommended

Außerdem muss das git-Submodule `vzgspec` vorhanden sein:

    git submodule update --init

Zum Aktualisieren der MediaWiki-Version der Dokumentation kann das Script
`../bin/mediawiki-upload` verwendet werden, dass eine Konfigurationsdatei
`mediawiki.json` voraussetzt.
