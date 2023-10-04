# Markdown-Dokumentation

In dieser Dokumentation geht es darum, wie man in Markdown-Dokumenten die Unterschiedlichen Befehle schreiben muss, damit die Datei schön, übersichitlich und leicht verständlich formulitert ist.
(Wenn man ein Zeichen schreiben will, das gleichzeitig allerdings ein Befehl ist, muss man davor einen Backslash machen.)

## Überschriften

Überschriften in Markdown dienen dazu, Textabschnitte zu gliedern und hierarchisch zu strukturieren. Es stehen sechs Ebenen von Überschriften zur Verfügung, die durch das Hinzufügen von Hashtags (#) erstellt werden. Eine Überschrift erster Ebene wird durch ein einzelnes Hashtag erstellt, eine Überschrift zweiter Ebene durch zwei Hashtags, und so weiter. 

Beispiel:

\# Überschrift 1
\## Überschrift 2
\### Überschrift 3

## Trennstriche

Trennstriche können verwendet werden, um Abschnitte oder Elemente voneinander zu trennen. Man verwendet drei aufeinanderfolgende Minuszeichen (---) oder Sterne (***), um einen Trennstrich zu erstellen.

Beispiel:

\---
\***
***

## Hervorgehobene/betonte Wörter

Markdown bietet verschiedene Möglichkeiten, Wörter hervorzuheben oder zu betonen:

- _Kursiv:_ Verwenden Sie ein einzelnes Sternchen (*) oder Unterstrich (_) vor und nach dem Wort.
  Beispiel: \*kursiv\* oder \_kursiv\_

- __Fett:__ Verwenden Sie zwei Sternchen (**) oder Unterstriche (__) vor und nach dem Wort.
  Beispiel: \*\*fett\*\* oder \_\_fett\_\_

## Aufzählungen

### Ungeordnete Aufzählungen

Erstellen Sie ungeordnete Aufzählungen mit Sternchen (*), Pluszeichen (+) oder Minuszeichen (-). Unterpunkte können durch Einrücken erstellt werden.

#### Aufbau (ohne Absätze):

\* Punkt 1

\* Punkt 2

  \* Unterpunkt 1
  
  \* Unterpunkt 2

Beispiel:
* Punkt 1
* Punkt 2
  * Unterpunkt 1
  * Unterpunkt 2

### Geordnete Aufzählungen

Geordnete Aufzählungen werden mit Nummern erstellt.

#### Aubau (ohne Absätze):

\1. Erste Punkt

\2. Zweiter Punkt

Beispiel:

1. Erster Punkt
2. Zweiter Punkt

## Links

Verwenden Sie eckige Klammern [] für den Linktext und runde Klammern () für die URL.

Beispiel:

\[Linktext](URL)

## Quellcode-Angabe

Sie können Quellcode mit oder ohne Syntax-Highlighting in Markdown einbetten.

### Mit Syntax-Highlighting

Verwenden Sie dreifache Backticks (\```) gefolgt von der Programmiersprache:

\```python
print("Hallo, Welt!")
\```

### Ohne Syntax-Highlighting

Verwenden Sie einfach dreifache Backticks ohne Angabe einer Sprache:

\```
Hier steht der Quellcode
\```

## Tabellen

Sie können Tabellen in Markdown erstellen, indem Sie Zeilen und Spalten mit Pipezeichen (|) trennen. Sie können die Ausrichtung des Textes in den Zellen festlegen.

Beispiel:

\[| Spalte 1 | Spalte 2 | Spalte 3 |
\[|:---------|:--------:|---------:|
\[| links    | zentriert| rechts   |

## Bilder

Fügen Sie Bilder in Markdown ein, indem Sie einen Text in eckigen Klammern für den Alternativtext und die URL in runden Klammern angeben.

Beispiel:

\![Alternativer Text](URL des Bildes)

## Blockzitate

Blockzitate können mit dem Größer-als-Zeichen (>) am Anfang einer Zeile erstellt werden.

Beispiel:

\> Dies ist ein Blockzitat.

## Fußnoten

Erstellen Sie Fußnoten mit [^1] und definieren Sie die Fußnoten am Ende des Dokuments.

Beispiel:

Das ist ein Text mit einer Fußnote.[^1]

\[^1]: Hier ist die Erklärung der Fußnote.

## Task-Listen

Sie können Task-Listen erstellen, um Aufgaben zu verfolgen.

Beispiel:

- Unfertige Aufgaben: \- [ ] Aufgabe 1
- Abgeschlossene Aufgaben: \- [x] Aufgabe 2

## Durchgestrichene Absätze

Verwenden Sie Tilden (~~) um Text durchzustreichen.

Beispiel:

\~~Durchgestrichener Text\~~

## Text Highlighting

Text kann mit dem == Zeichen hervorgehoben werden.

Beispiel:

==Hervorgehobener Text==

## Hoch- und Tiefgestellte Zeichen

- Hochgestellt: ^hoch^
- Tiefgestellt: ~tief~

## Deaktivierte URL-Verknüpfungen

URLs können deaktiviert werden, indem sie zwischen Winkelschließklammern (< und >) platziert werden.

Beispiel:

\<http://example.com\>
