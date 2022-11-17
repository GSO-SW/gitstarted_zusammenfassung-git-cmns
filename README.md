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


--Begriffe definieren und erklären--

----

## git Befehle für die Arbeit mit entfernten Repositories:
'git clone' wird verwendet, um ein vorhandenes repository,
ob lokal, oder remote repository zu klonen/kopieren,
dieses auf dem lokalen Rechner zu speichern und das repository als Ziel festzulegen.
Dadurch ist 'git init' nicht notwendig.

'git revert' ist ein Befehl, um kommits "rückgängig" machen zu können.
dadurch wird ein neues commit erstellt, welches die Änderungen des
reverteten commits ignoriert.

Mit 'git push' kann man ein lokales repository in ein remote remote
hochladen. Genauer gesagt überträgt man die commits in das remote repository.
man kann 2 argumente übergeben. Das erste ist des remote repository's Verweis, das zweite der branch.

'git fetch' ist so ziemlich das Gegenteil von 'git push'.
Es werden commits in das lokale repository heruntergeladen.

'git pull' ist eine erweiterung von 'git fetch'.
Der Befehl lässt vom remote repository in das lokale kopieren,
kombiniert hier jedoch die änderungen via. merge.
## git Befehle für die Arbeit mit entfernten Repositories: (ENDE)