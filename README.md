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

Aufzählungen erstellt man mit Sternchen (*), Pluszeichen (+) oder Minuszeichen (-). Unterpunkte können durch Einrücken erstellt werden.

### Aufbau (ohne Absätze):

\* Punkt 1

\* Punkt 2

  \* Unterpunkt 1
  
  \* Unterpunkt 2

### Beispiel:
* Punkt 1
* Punkt 2
  * Unterpunkt 1
  * Unterpunkt 2

### Geordnete Aufzählungen

Geordnete Aufzählungen werden mit Nummern erstellt.

### Aubau (ohne Absätze):

\1. Erste Punkt

\2. Zweiter Punkt

Beispiel:

1. Erster Punkt
2. Zweiter Punkt

## Links

Man verwendet eckige Klammern [] für den Linktext und runde Klammern () für die URL.

Beispiel:

\[Linktext](URL)
[HTL Leoben](Htl-leoben.at)

## Quellcode-Angabe

Quellcode kann man mit oder ohne Syntax-Highlighting in Markdown angeben.

### Mit Syntax-Highlighting

Verwende dreifache Backticks (\```) gefolgt von der Programmiersprache:

\```java
print("Hallo, Welt!")
\```
```java
print("Hallo, Welt!")
```

### Ohne Syntax-Highlighting

Verwende Sie einfach dreifache Backticks ohne Angabe einer Sprache:

\```
Hier steht der Quellcode
\```

```
Hier ist der Quellcode
```

## Tabellen

Man erstellt Tabellen in Markdown, indem Sie Zeilen und Spalten mit Pipezeichen (|) trennen. Sie können die Ausrichtung des Textes in den Zellen festlegen.

### Aufbau (ohne Absätze)

\| Spalte 1   | Spalte 2   | Spalte 3   |

\|------------|------------|------------|

\| Inhalt 1   | Inhalt 2   | Inhalt 3   |

\| Zeile 2, 1 | Zeile 2, 2 | Zeile 2, 3 |

\| Zeile 3, 1 | Zeile 3, 2 | Zeile 3, 3 |

### Beispiel

| Spalte 1   | Spalte 2   | Spalte 3   |
|------------|------------|------------|
| Inhalt 1   | Inhalt 2   | Inhalt 3   |
| Zeile 2, 1 | Zeile 2, 2 | Zeile 2, 3 |
| Zeile 3, 1 | Zeile 3, 2 | Zeile 3, 3 |

## Bilder

Fügene ein Bild in Markdown ein, indem man einen Text in eckigen Klammern für den Alternativtext und die URL in runden Klammern angeben.

Beispiel:

\![Alternativer Text](URL des Bildes)

![Max Verstappen](https://search.brave.com/images?q=max%20verstappen)

## Blockzitate

Blockzitate können mit dem Größer-als-Zeichen (>) am Anfang einer Zeile erstellt werden.

Beispiel:

\> Dies ist ein Blockzitat.
> Dies ist ein Blockzitat

## Fußnoten

Man erstellt Fußnoten mit [^1] und definieren Sie die Fußnoten am Ende des Dokuments.

Beispiel:

Das ist ein Text mit einer Fußnote.[^1]

\[^1]: Hier ist die Erklärung der Fußnote.
[^2]: Hier ist die Fußnote.

## Task-Listen

Mann kann Task-Listen erstellen, um Aufgaben zu verfolgen.

Beispiel:

- Unfertige Aufgaben: \- [ ] Aufgabe 1
- Abgeschlossene Aufgaben: \- [x] Aufgabe 2

## Durchgestrichene Absätze

Verwende Wellenlinien (~~) um Text durchzustreichen.

Beispiel:

\~~Durchgestrichener Text\~~
~~Durchgestrichener Text~~

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
<http://htl-leoben.at\>
