# latex-rechnung
Bei diesem Repository handelt es sich um eine LaTeX Rechnungsvorlage.
Die Vorlage wird zur Erstellung von Rechnungen für die in Rechnungsstellung von Dienstleistungen genutzt.
Sie enthält unter anderem eine Klausel für die Kleinunternehmerregelung.

## Anpassung
* `_main.tex`: Hauptdatei für die Erstellung der PDF mittels LaTeX
* `_invoice.tex`: Enthält die Daten für die Abrechnung (Anzahl der Stunden, Rabatte, etc.)
    * Die Gesamtsumme wird automatisch berechnet.
    * für induviduelle Anpasungen müssen Änderungen in der Datei `ìnvoice.def` bzw. `ìnvoice.sty` vorgenommen werden
        * [detaillierte Informationen zum LaTeX invoice Paket](ftp://ftp.rrzn.uni-hannover.de/pub/mirror/tex-archive/macros/latex/contrib/invoice/doc/invoice.pdf)
* `_data.tex`: Enthält die Kundendaten, als auch eigene Daten (Kontodaten, Steuernummer, Anschriften, Formulierungen, etc.)
* `logo.png`: hier kann ein eigenes Logo eingesetzt werden


