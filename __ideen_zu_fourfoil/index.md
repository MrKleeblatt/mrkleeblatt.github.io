# fourfoil

fourfoil ist eine *funktionale Programmiersprache* mit ähnlichen Strukturen und Konzepten aus der *Objektorientierung*, die jedoch auf eine sehr eigene und speziellere Art unf Weise implementiert wurden.
Das Development Kit selbst umfasst den *Compiler*, den *Interpreter* und die mitgelieferten *Bibliotheken*. fourfoil kann durch den mitgelieferten Compiler in eine ausführbare .exe-Datei unter Windows kompiliert werden ( Unterstützung für weitere Betriebssysteme folgt), oder vom fourfoil-Interpreter interpretiert werden. Sollte fourfoil zur Webentwicklung genutzt werden, wird ein Teil des Codes in Webassembly kompiliert.
<br/>
Die Programmiersprache fourfoil dient zum Formulieren von Programmen. Diese liegen zunächst als reiner, menschenverständlicher Text vor, dem sogenannten *Quellcode*. Dieser Quellcode ist nicht direkt ausführbar, erst der fourfoil-Compiler, der Teil des Entwicklungswerkzeugs ist, übersetzt ihn in den maschinenverständlichen *Maschinencode* bzw. wird er vom fourfoil-Interpreter interpretiert.
<br/>
Die Sprache ist vor allem dazu da, mit wenig Text, aber dennoch anschaulich und leicht verständlich, kurze Berechnungen, aber auch komplexe Programme ausführen zu können. Sie soll Anwendung in der *Webentwicklung*, aber auch in der *Spieleentwicklung* finden, da sie unter Anderem schnell sein soll, ähnlich wie Programmiersprachen wie z.B. C oder C++, aber dennoch einige neue Feutures bekommen. Was fourfoil jedoch komplett fremd bleibt, ist Objektorientierung.
<br/>

Der Name der Sprache leitet sich von englisch *four foil* ab, was "vierblättriges Kleeblatt" bedeutet und eine Anspielung auf den Künstlernamen des Hauptentwicklers @MrKleeblatt [MrKleeblatt](https://www.github.com/MrKleeblatt) ist.
<br/><br/>


### Das Alphabet
Das Alphabet der Sprache besteht aus:
<br/>
`qwertzuiopasdfghjklyxcvbnm1234567890 !"§$%&/()=?{[]}\°^<>|,.;:-_+*~#'`
<br/>


### Reservierte Wörter
Reservierte Wörter der Sprache sind:
```
import, fun, object, var, class, delete, return, switch, case, if, else, for, while, do, try, catch, foreach, byte, bool, char, short, int, long, float, double, enum, public, private, parent, final, null, 4f, const, bit, other, list, table, interface, implements, skip, exception, throw, throws, ignore, lambda
```
<br/>
<br/>


### Dateiendungen
Verschiedene Dateiendungen lassen sich mit fourfoil assoziieren.
<br/>
Nähere Informationen gibt es auf der Seite _[Dateiformate](dateiformate/dateiformate.md)_.

- `4f` ist die standardmäßige Dateiendung, die ein in fourfoil geschriebenes Programm signalisiert ▶ **Programmdatei**
- `4fon` ist ein der `json`-Dateiendung ähnliches Format, welches ausschließlich ein 4fon-Objekt enthält ▶ **Objektnotation**
- `nbt` ist ein von @Notch (Markus Persson) entwickeltes Dateiformat, von @MrKleeblatt erweitert und verfeinert. Die Abkürzung steht für _named binary tag_ und mittlerweile gibt es einen gesamten [wiki-Eintrag](https://wiki.vg/NBT) darüber. Im Gegensatz zum in Minecraft genutzten nbt-Format kann in dem in fourfoil genutzten Format auch der root-compound-tag weggelassen werden.
▶ **Objektnotation** bzw. **Package-Information**
<br/>


### Geplant für den Language-support
...in Atom, VSCode und IntelliJ sind:
- auto-complete
- Debugger
- Package-Manager bzw. Build-Management-Tool
- get-data-Konsole, in der man Daten mal schnell auslesen kann (z.B.: `$x`(liefert alle Infos über die Variable $x), `unicode €` (gibt den Unicode zum Eurozeichen) oder `unicode search Euro` (gibt alle Suchergebnisse zum Unicodezeichen "€")
- Wenn man eine bestimmte Tastenkombination drückt, soll sich ein Bild öffnen, in dem man sehen kann, wer wie von was erbt (UML?), wobei Interfaces, Klassen und Programmdateien verschiedenfarbig gekennzeichnet werden sollen.

## Die Dokumentation
- zur **Syntax** finden Sie **[hier](syntax.md)**
- zu in fourfoil genutzten **Dateiendungen** finden Sie **[hier](dateiformate/)**
- zu Klassen, Methoden und Objekten des **4fdk** finden Sie **[hier](fdk.md)**
