# fourfoil

...ist eine **objektorientierte Programmiersprache**.
Das Development Kit selbst umfasst den **Compiler** und die mitgelieferten Bibliotheken. fourfoil kann durch den mitgelieferten Compiler in Java-Bytecode kompiliert werden, der dann von der JVM ausgeführt werden kann, oder direkt in eine ausführbare .exe-Datei unter Windows kompiliert werden.
Die Programmiersprache fourfoil dient innerhalb der fourfoil-Technologie vor allem zum Formulieren von Programmen. Diese liegen zunächst als reiner, menschenverständlicher Text vor, dem sogenannten **Quellcode**. Dieser Quellcode ist nicht direkt ausführbar, erst der fourfoil-Compiler, der Teil des Entwicklungswerkzeugs ist, übersetzt ihn in den maschinenverständlichen **Java-Bytecode** bzw. **Maschinencode**.<br/>
Die Sprache ist vor allem dazu da, mit wenig Text, aber dennoch anschaulich und leicht verständlich, kurze Berechnungen, aber auch komplexe Programme ausführen zu können.<br/>
Sie soll Anwendung in der **Frontend-Webentwicklung**, aber auch in der **Spieleentwicklung** finden.<br/>
Der Name der Sprache leitet sich von englisch _four foil_ ab, was "vierblättriges Kleeblatt" bedeutet und eine Anspielung auf den Künstlernamen des Hauptentwicklers @MrKleeblatt ist.<br/>

### Verschiedene Dateiendungen

...lassen sich mit fourfoil assoziieren:<br/>

-   `4f` ist die standardmäßige Dateiendung, die ein in fourfoil geschriebenes Programm signalisiert<br/>
▶ **Programmdatei**
-   `4fon` ist ein der `json`-Dateiendung ähnliches Format, welches ausschließlich ein 4fon-Objekt enthält<br/>
▶ **Objektnotation**
-   `nbt` ist ein von @Notch (Markus Persson) entwickeltes Dateiformat, von @MrKleeblatt erweitert und verfeinert. Die Abkürzung steht für _named binary tag_ und mittlerweile gibt es einen gesamten [wiki-Eintrag](https://wiki.vg/NBT) darüber. Im Gegensatz zum in Minecraft genutzten nbt-Format kann in dem in fourfoil genutzten Format auch der root-compound-tag weggelassen werden.<br/>
▶ **Objektnotation** bzw. **Package-Information**

### Das Alphabet

...der Sprache sieht wie folgt aus:
`qwertzuiopasdfghjklyxcvbnm1234567890 !"§$%&/()=?{[]}\°^<>|,.;:-_+*~#'`

### Reservierte Wörter

...der Sprache sind:

-   import
-   fun
-   object
-   var
-   class
-   delete
-   return
-   switch
-   case
-   if
-   else
-   for
-   while
-   do
-   try
-   catch
-   foreach
-   byte
-   boolean
-   char
-   short
-   int
-   long
-   float
-   double
-   enum
-   public
-   private
-   parent
-   final
-   null
-   System
-   4f
-   const
-   bit
-   other
-   unless
-   list
-   table
-   Interface
-   implements
-   skip
-   Exception
-   throw
-   throws
-   ignore

### Geplant für den Language-support

...in Atom, VSCode und IntelliJ sind:

-   auto-complete
-   Debugger
-   Package-Manager bzw. Build-Management-Tool
-   get-data-Konsole, in der man Daten mal schnell auslesen kann (z.B.: `$x`(liefert alle Infos über die Variable $x), `unicode €` (gibt den Unicode zum Eurozeichen) oder `unicode search Euro` (gibt alle Suchergebnisse zum Unicodezeichen "€")
-   Wenn man eine bestimmte Tastenkombination drückt, soll sich ein Bild öffnen, in dem man sehen kann, wer wie von was erbt (UML?), wobei Interfaces, Klassen und Programmdateien verschiedenfarbig gekennzeichnet werden sollen.

## Syntax

Kommentare werden mit "//" gemacht. Alles, was danach in der Zeile kommt, ignoriert der Comiler. Wenn man in Kommentaren etwas fett, unterstrichen oder kursiv schreiben will, kann man markdown nutzen. Wenn der Cursor auf dem Wort landet, erscheinen die Zeichen, die man um das Wort herum geschrieben hat. Wenn der Cursor von der Stelle weg geht, wird die Schrift formatiert und die Zeichen unsichtbar.<br/>

Codeblöcke können durch geschweifte Klammern umrandet werden, damit sie von Atom eingeklappt werden können. Syntax: `_Beschreibung_{}`<br/>
Dateien können mit Funktionen, Interfaces, Enums oder Klassen beginnen. Das Erstellen von Klassen ist kein Muss.<br/>
Zu Beginn der Datei wird das Package der Sprache genannt. Syntax: `package einsPackage` Alternativ kann eine "pack.nbt"-Datei erstellt werden, in welcher genauere Informationen (z.B. auch die Code-Version) stehen. Es wir im nbt-Format angegeben, wobei auch einfach leere {}-Klammern reichen würden.<br/>
Packages, Daten und 4f-Dateien werden am Anfang der Datei importiert. Syntax: `import variable = com.ich.bin.ein.package.lul`. Sie können später im Code über die Objektvariable abgerufen werden.





# 4fon

```
    {
      name: "iCh BiN lUsTiG", nachname: "lul"
      Attribut_mit_Unterstrich: 42
      Objekt: {
        name: "unterobject"
        parent: $name
      }
    }
```
