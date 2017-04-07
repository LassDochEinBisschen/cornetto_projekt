# Django Projekt: Cornetto-Verlag


Eine einfacher Blog erstellt mit dem [Django Framework](https://www.djangoproject.com/).


1. Vorbereitung
  * Installation
  * Git
  * Django Superuser und Datenbank migration



## Vorbereitung


### Installation



Bevor wir überhaupt mit dieser Repository beschäftigen müssen wir erstmal paar dinge Installieren.
Als erstes laden wir uns Python runter ([hier der Download link zu Python](https://www.python.org/downloads/)).
> Wichtiger hinweis: Wir verwenden und arbeiten mit der Version Python 3.

Nun da wir Python runtergeladen und installiert haben , müssen wir jetzt das Modul virtualenv für python installieren.
> Unter Windows müssen wir sicher gehen das Python in PATH existiert. Das ist wichtig weil wir ab jetzt mit der
Windows Commando Zeile (cmd) arbeiten werden. hier eine [einleitung](https://www.johannespetz.de/python-unter-windows-installieren/).

Öffnen wir nun die Commando Zeile und geben folgenden Befehl ein:
`pip install virtualenv`
> pip ist das  Paketverwaltungsprogramm von Python,damit lassen sich module installieren,updaten,entfernen usw.

Als nächstes erstelle einen Projekt ordner und gehe in cmd in dieses Verzeichnes, nun müssen wir eine Virtuelle Umgebung erstellen (genau virtualenv):

`virtualenv <beliebiger Ordner name>`

Jetzt müssen wir die Virtuelle Umgebung aktivieren in dem wir einfach in Windows Commando Zeile folgendens schreiben:

`<beliebiger Ordnername>\Scripts\activate`

Wunderbar wenn es funktioniert hat müssten wir vor unserem prompt das hier sehen:

`(beliebiger Ordner name) C:\User\User>_ `


### Git
