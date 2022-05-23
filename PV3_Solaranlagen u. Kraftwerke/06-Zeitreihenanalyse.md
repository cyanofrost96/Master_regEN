# Übersicht
heute wird Überlappungen zwischen Branchen versucht zu lösen.
## to do Liste:
- [x] Allgemeines
- [x] Merge-Konflikten Lösen
- [x] PyCharm

### Merge Conflict (GitHub)
Github verfügt über eigene einfache "merge conflict" Tool, die auf Veränderungen bei gleich gebliebenen Zeilen aufmerken und auflisten kann. Die Änderungen werden markiert und kann einzeln ausgewählt werden, welche am aktuellsten ist und "gemerged" werden soll.
Falls der Conflict zu groß ist (neue Zeilen werden hinzugefügt oder gelöscht, Textposition umgetauscht), wird bessere "merge conflict" Tool wie [Meld](file:///c:/Meld/Meld.exe) nötig.

Für eine fließende Merge-Arbeit soll ein lokalen Branch für die conflicted Branch mit der befehl `git merge <origin/branch-name>` gezogen. Der neue Branch kann auf Meld geöffnet werden und mit den original Daten verglichen werden. Mit Meld kann bis zu 3 Daten auf einmal verglichen werden und somit die Conflicten behoben.

`git commit -am "hier Commit-Message"` = *-a* commit alles was im Folder befindet; *-am* commit mit folgende Commit Message

### PyCharm
Create new Project mit vorhandenen Interpreter [d_py38_pv3vis](file:///c:/Anaconda3/envs/d_py38_pv3vis)/python.exe erstellen. Beim erfolgreichen Erstellen steht auf dem "select interpreter" Feld "python 3.8 d_py38_pv3vis"
updates von GitHub wird nicht direkt in PyCharm "gültig", die gemeinte Daten werden mit roter Schrift versehen, und muss erst durch das "rechts klicken -> Git -> Add" hinzufügen.

Es wird von Ludwig das File main.py erstellt und auf dem Branch `feature-38-python-main` hochgeladen. Diese muss erst in unserem lokalen Folder gepullt werden und auf PyCharm geöffnet. Problem hier ist dass man das Programm (noch) nicht ausführen kann.

Um dieses zu beheben muss ein neue Configuration erstellt werden. Geh auf oben rechts "Add Configuration" und füge neue Config unter der Name "htw-pv3", als Python Interpreter nochmal d_py38_pv3vis. 
	Falls es nicht da ist, geh auf File -> Settings -> Project: python -> Python Interpreter. hier kann man die Directory zu unserem d_py38_pv3vis envs hinzufügen.
Script path (hier dein main.py location!) und Working Directory (hier dein htw-pv3/weather-data/python Folder) muss noch hinzugefügt werden.