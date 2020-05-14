# 2AHET-BasicMathOperations

--- 

In den nächsten Projekten werden wir uns mit Windows-Forms Applikationen beschäftigen.

Dabei sollen einerseits das Erstellen von Win-Forms-Apps und das Programmieren eines GUIs im Vordergrund stehen, aber gleichzeitig auch die bisher erworbenen Programmierkenntnisse zur Anwendung kommen.

---

## Projektbeschreibung


Es soll ein WinForms-Programm entworfen werden, welches in Anlehnung an einen Taschenrechner einfache mathematische Rechnung ausführt.

## Anforderungen

### Formulardesign

Die Gestaltung des Formulars soll im Wesentlichen der Vorgabe entsprechen, wie sie als Screenshot auf dem AIIT-Kanal zu sehen ist. Die verwendeten Steuerelemente sind *Labels*, 
*TextBoxes* und *Buttons*.

### Datentypen

Die Eingaben für *Zahl 1* und *Zahl 2* sollen ganzzahlige Werte sein. Der Datentyp der Ausgabe des Ergebnisses ergibt sich aus der entsprechenden mathematischen Operation.

### Funktionialität

* Durchführung der Berechnungen und Ausgabe der Ergebnisse über das vorgesehen Label für
  * die vier Grundrechnungsarten (Basic)
  * die zusätzlichen Operationen *Wurzel* und *Potenz* (Advanced)
* Abfangen von Fehleingaben durch ein geeignetes Exception-Handling:
  * Eingabe nicht numerischer Werte (Basic)
  * Division durch Null (Advanced)
  * In allen Fällen von Fehleingaben soll eine MessageBox angezeigt werden

### Sonstige Anforderungen

* Der Text Ergebnis soll durch entsprechenden Text der Rechenoperation (*Summe*, *Differenz*, *Produkt*, *Quotient*) ersetzt werden.
* Der *Clear*-Button soll sämtliche Ein- u. Ausgabewerte löschen und den Focus auf *Zahl 1* setzen.
