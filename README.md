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
  - Git: 

    Git ist eine Software zur versionsverwaltung bzw. versionskontrolle.
    Git erlaubt mehreren entwicklern gleichzeitig and einem Projegkt zu 
    arbeiten indem sie eine Komplette arbeitskopie lokal auf ihrem Rechner
    Vorhanden ist.
    Gleichzeitig ist es möglich die änderungen zu verfolgen und einzusehen.

  - Repository:

    Ein Git-Repository ist ein Aufbewahrungsort. Gleichzeitig ist es eine
    Arbeitskopie von den Entwicklern die an diesem Repository arbeiten,
    die den Vollständigen verlauf der Aenderungen enthält. 
    Alle lokalen Aeanderungen werden auf einem lokalen Repository gespeichtert.

  - Branch:

    Durch Git-Branch koennen arbeitsstaende in seperate Arbeitszweige
    Aufgeteilt werden das sind sogennante "Branches". Sie dienen dazu funktionen getrennt voneinander zu entwickeln.

  - Commit:

    Der Befehl Git-Commit wird verwendet um den Status eines Projekts zu erfassen. Der gegenwärtige status eines Projekts wird dadurch als eine version in Git gespeichert.

  - Merge:

    Merge der Befehlt git merge wird genutzt um veränderte änderungen aus verschiedenen Branches zusammen zu führen.

 - Push: 
  
    Push also der Befehlt (git-Push) wird genutz um lokale änderung auf 
    ein remote Repositroy zu senden.
  

----

## Locale Repositorie Befehle
- git init	Der Befehl git **Init** iniziiert ein Lokales Git Repository in dem Ordner in dem der Befeht ausgeübt wurde
- git add		git **add** [Datei.xyz] wird benutzt um Dateien an den gearbeitetet wurden in die Staging area (auch bekannt als "the Index") zu verschieben
- git commit	git **commit** fügt die Dateien die in der Staging area sind in das Repositorie ein. -m ist eine Extra option um eine Message dem commit mitzugeben.
		Fals keine message mitgegeben wird wird der Standart Text Editor Geöffnet.
- git merge	
- git log
- git branch
- git checkout

## git Befehle für die Arbeit mit entfernten Repositories:
  - 'git clone' wird verwendet, um ein vorhandenes repository,
	ob lokal, oder remote repository zu klonen/kopieren,
	dieses auf dem lokalen Rechner zu speichern und das repository als Ziel festzulegen.
	Dadurch ist 'git init' nicht notwendig.

  -	'git revert' ist ein Befehl, um kommits "rückgängig" machen zu können.
	dadurch wird ein neues commit erstellt, welches die Änderungen des
	reverteten commits ignoriert.

  - Mit 'git push' kann man ein lokales repository in ein remote remote
	hochladen. Genauer gesagt überträgt man die commits in das remote repository.
	man kann 2 argumente übergeben. Das erste ist des remote repository's Verweis, das zweite der branch.

  - 'git fetch' ist so ziemlich das Gegenteil von 'git push'.
	Es werden commits in das lokale repository heruntergeladen.

  - 'git pull' ist eine erweiterung von 'git fetch'.
	Der Befehl lässt vom remote repository in das lokale kopieren,
	kombiniert hier jedoch die änderungen via. merge.

## Fachbegriffe OOP mit beispielen

  - abstract(klassen)
	Abstrakte Klassen sind Klassen, mit dem bloßen Zweck, erbbar zu sein.
	Sprich: Instanzen, bzw. Objekte dieser Klasse sind nicht erzeugbar.
	Ein gutes Beispiel dafür wäre eine Klasse 'Lebewesen'.
	Alles, was sich bewegen, sich fortplanzen und wachsen kann, nennt man Lebewesen.
	Sache ist jeodch, dass es 'das Lebewesen' nicht als Objekt/Materie,
	sondern nur als eine Idee, ein Konzept, oder halt eine Abstraktion.
	Es gibt vieles, was ein Lebewesen IST. Deswegen kann man von der Klasse 'Lebewesen'
	erben, und evtl. von der Erbenden Klasse Objekte erstellen.
	
  - abstract(methoden)
	Abstrakte Methoden sind ähnlich zu Abstrakten Klassen.
	Diese muss man in erbenden Klassen überschreiben, bzw. definieren.
	Das könnte man gebrauchen, wenn zwar alle erbenden Klassen eine Methode brauchen,
	sie aber von Klasse zu Klasse variieren könnte.
	
  - virtual
  
  - override
    Override kann man bei Methoden anwenden, um sie zu überschreiben,
	falls die "standard-Methode" nicht zur Klasse passen sollte.
	Das kann man bei Vererbungen wie z.B. Von Mensch zu Männlich&Weiblich.
	Beide können eine Methode haben, wo die Zeichenkette "Ich bin ein Mensch."
	ausgegeben wird. Mit override kann man aber festlegen, dass das männliche Geschlecht
	"Ich bin ein Mann." und das weibliche Geschlecht "Ich bin eine Frau." als Methodenausgabe hat.
	
  - Polymorphie
  - Wie überschreibt man die Methode "virtual string ToString()"?