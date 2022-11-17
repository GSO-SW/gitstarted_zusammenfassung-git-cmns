# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
- In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
- Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

:dart: Ziele:
1. Die Arbeit soll nicht im Browser stattfinden. Clonen Sie das Repo und arbeiten Sie lokal.
1. Hier gehts um Teamwork: Ich erwarte häufige Commits (+ häufiges pushen/pullen )

## TODO
- Begriffe definieren und erklären (z.B. repository, branch etc.)
- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)
- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)

## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen)
  - abstract (Methoden)
  - virtual
  - override
  - Polymorphie
- Wie überschreibt man die Methode `virtual string ToString()`?

## Begriffe definieren und erklären ## 
  -Git: 
    Git ist eine Software zur versionsverwaltung bzw. versionskontrolle.

    Git erlaubt mehreren entwicklern gleichzeitig and einem Projekt zu 
    arbeiten indem sie eine Komplette arbeitskopie lokal auf ihrem Rechner
    Vorhanden ist.
    Gleichzeitig ist es möglich die änderungen zu verfolgen und einzusehen.
  -Repository:
    Ein Git-Repository ist ein Aufbewahrungsort. Gleichzeitig ist es eine
    Arbeitskopie von den Entwicklern die an diesem Repository arbeiten,
    die den Vollständigen verlauf der Aenderungen enthält. 
    Alle lokalen Aeanderungen werden auf einem lokalen Repository gespeichtert.
  -Branch:
    Durch Git-Branch koennen arbeitsstaende in seperate Arbeitszweige
    Aufgeteilt werden das sind sogennante "Branches". Sie dienen dazu funktionen getrennt voneinander zu entwickeln.
----
=======
## Locale Repositorie Befehle
- git init	Der Befehl git **Init** iniziiert ein Lokales Git Repository in dem Ordner in dem der Befeht ausgeübt wurde
- git add		git **add** [Datei.xyz] wird benutzt um Dateien an den gearbeitetet wurden in die Staging area (auch bekannt als "the Index") zu verschieben
- git commit	git **commit** fügt die Dateien die in der Staging area sind in das Repositorie ein. -m ist eine Extra option um eine Message dem commit mitzugeben.
		Fals keine message mitgegeben wird wird der Standart Text Editor Geöffnet.
- git merge	
- git log
- git branch
- git checkout
>>>>>>> Michael
