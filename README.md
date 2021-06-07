[eins Link lul](https://google.com)
```JS
var variable = 0;
let x = 'Das hier ist JavaScript-Code'
```
`wie in Discord`
**fett** _kursiv_ ~~durchgestrichen~~
> Zitat



<!------------------------------------------------------------------------------------->

# fourfoil

...ist eine **objektorientierte Programmiersprache**.
Das Development Kit selbst umfasst den **Compiler** und die mitgelieferten Bibliotheken. fourfoil kann durch den mitgelieferten Compiler in Java-Bytecode kompiliert werden, der dann von der JVM ausgeführt werden kann, oder direkt in eine ausführbare .exe-Datei unter Windows kompiliert werden.
Die Programmiersprache fourfoil dient innerhalb der fourfoil-Technologie vor allem zum Formulieren von Programmen. Diese liegen zunächst als reiner, menschenverständlicher Text vor, dem sogenannten Quellcode. Dieser Quellcode ist nicht direkt ausführbar, erst der fourfoil-Compiler, der Teil des Entwicklungswerkzeugs ist, übersetzt ihn in den maschinenverständlichen Java-Bytecode bzw. Maschinencode.\n
Die Sprache ist vor allem dazu da, mit wenig Text, aber dennoch anschaulich und leicht verständlich, kurze Berechnungen, aber auch komplexe Programme ausführen zu können.\n
Sie soll Anwendung in der Frontend-Webentwicklung, aber auch in der Spieleentwicklung finden.\n
\n
Der Name der Sprache leitet sich von englisch *four foil* ab, was "vierblättriges Kleeblatt" bedeutet und eine Anspielung auf den Künstlernamen des Hauptentwicklers @MrKleeblatt ist.\n

Verschiedene Dateiendungen lassen sich mit fourfoil assoziieren:\n
- ``4f`` ist die standardmäßige Dateiendung, die ein in fourfoil geschriebenes Programm signalisiert
- ``4fon`` ist ein der ``json``-Dateiendung ähnliches Format, welches ausschließlich ein 4fon-Objekt enthält
- ``nbt`` ist ein von @Notch (Markus Persson) entwickeltes Dateiformat, von @MrKleeblatt erweitert und verfeinert. Die Abkürzung steht für *named binary tag* und mittlerweile gibt es einen gesamten [wiki-Eintrag](https://wiki.vg/NBT)

```
{
  name: "iCh BiN lUsTiG"
  Attribut_mit_Unterstrich: 42
  Objekt: {
    name: "unterobject"
    parent: $name
  }
  ...
}
```

Geplant für den Language-support in Atom sind:
- Language Support; auto-complete; GetData-Konsole, in der man Daten mal schnell auslesen kann (z.B.: ``x=?``, ``unicode €`` oder ``unicode search Euro``
- Wenn man eine bestimmte Tastenkombination drückt, soll sich ein Bild öffnen, in dem man sehen kann, wer wie von was erbt (UML?), wobei Interfaces, Klassen und Programmdateien verschiedenfarbig gekennzeichnet werden sollen.
