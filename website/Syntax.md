# Syntax

Kommentare werden mit "//" gemacht. Alles, was danach in der Zeile kommt, ignoriert der Comiler. Wenn man in Kommentaren etwas fett, unterstrichen oder kursiv schreiben will, kann man markdown nutzen. Wenn der Cursor auf dem Wort landet, erscheinen die Zeichen, die man um das Wort herum geschrieben hat. Wenn der Cursor von der Stelle weg geht, wird die Schrift formatiert und die Zeichen unsichtbar.<br/>

Codeblöcke können durch geschweifte Klammern umrandet werden, damit sie von Atom eingeklappt werden können. Syntax: `_Beschreibung_{}`<br/>
Dateien können mit Funktionen, Interfaces, Enums oder Klassen beginnen. Das Erstellen von Klassen ist kein Muss.<br/>
Zu Beginn der Datei wird das Package der Sprache genannt. Syntax: `package einsPackage` Alternativ kann eine "pack.nbt"-Datei erstellt werden, in welcher genauere Informationen (z.B. auch die Code-Version) stehen. Es wir im nbt-Format angegeben, wobei auch einfach leere {}-Klammern reichen würden.<br/>
Packages, Daten und 4f-Dateien werden am Anfang der Datei importiert. Syntax: `import variable = com.ich.bin.ein.package.lul`. Sie können später im Code über die Objektvariable abgerufen werden.
