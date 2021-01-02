sdprint v1.4

benötigt wird Dotnet 2.0

Installation
Kopieren der sdprint.exe in ein Verzeichniss

Aufruf über UNC möglich

sdprint speichert unter im Homeverzeichnis (LW:\Benutzer\Benutzername
eine sdprint.store Datei.

Die sdprint.store Datei enthält den Name des Standarddruckers.

sdprint beendet sich automatisch nach 10 Sekunden.

Der Standarddrucker kann über die Dropdownbox in sdprint 
gewechselt werden.

Über das X kann sdprint ohnen Speicherung beendet werden.

Wenn keine sdprint.store Datei vorhanden ist z.B. beim ersten
Aufruf muss sdprint über den Button "Sichern und beenden" beendet
werden.

-S, --SILENT
Mit dem Parameter -s oder --silent kann sdprint im Silent Modus gestartet
werden. Es setzt den Drucker der in der store Datei hinterlegt ist und 
beendet sich selbstständig.

-W:<sekunden>, --WAIT:<sekunden>
Mit dem Parameter -w:<sekunden> oder --wait:<sekunden> wartet das Programm
nach dem ausführen die angegebenen Sekunden bis aktiv wird.


