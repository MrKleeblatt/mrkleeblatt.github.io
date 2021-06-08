# Syntax

Kommentare werden mit "//" gemacht. Alles, was danach in der Zeile kommt, ignoriert der Comiler. Wenn man in Kommentaren etwas fett, unterstrichen oder kursiv schreiben will, kann man markdown nutzen. Wenn der Cursor auf dem Wort landet, erscheinen die Zeichen, die man um das Wort herum geschrieben hat. Wenn der Cursor von der Stelle weg geht, wird die Schrift formatiert und die Zeichen unsichtbar.  

Codeblöcke können durch geschweifte Klammern umrandet werden, damit sie von Atom eingeklappt werden können. Syntax: `_Beschreibung_{}`  
Dateien können mit Funktionen, Interfaces, Enums oder Klassen beginnen. Das Erstellen von Klassen ist kein Muss.  
Zu Beginn der Datei wird das Package der Sprache genannt. Syntax: `package einsPackage` Alternativ kann eine "pack.nbt"-Datei erstellt werden, in welcher genauere Informationen (z.B. auch die Code-Version) stehen. Es wir im nbt-Format angegeben, wobei auch einfach leere {}-Klammern reichen würden.  
Packages, Daten und 4f-Dateien werden am Anfang der Datei importiert. Syntax: `import com.ein.package` bzw. wenn man das Package / Objekt / die Variable direkt einer Variable zuordnen will `import variable = com.ein.package`. Sie können später im Code über die Objektvariable abgerufen werden.
