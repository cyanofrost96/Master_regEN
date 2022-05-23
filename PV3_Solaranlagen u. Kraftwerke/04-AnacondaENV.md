# Übersicht
###### to do Liste:
- [x] Jupyter Notebook - kennenlernen; Hinweise: [python-setup-environment](https://github.com/htw-pv3/weather-data/blob/master/python/pv3_python_0_setup_environment.txt)
- [x] Branch auf Github für die Aufgabe erstellen
- [x] Conda-Environment erstellen und löschen
- [x] ENV aktivieren

## Anaconda ENV
ist ein angepasste Umgebung für Python-Programmierung .
#### Installationsvorgang
1. geh auf cmd mit Admin-Zugang und Git Bash
2. neue lokale Branch auf [weather-data Repo](https://github.com/htw-pv3/weather-data) namens `local-run-python` mit Git Bash erstellen 
3. cmd auf dem [python](file:///D:/git/github/htw-pv3/weather-data/python)-Ordner zuweisen
	- zur Sicherheit muss die Conda bzw. python Version mit `conda --version`  bzw. `python --version` Befehl gecheckt werden.
	- Falls nicht dann muss unter Systemumgebungsvariablen den Installationspfad zur `Anaconda3` bzw. `Anaconda3/Scripts` für %Path% zugewiesen werden.
		- mit `echo %path%` kann man alle Pfade zu den Umgebungsvariablen checken
4. Conda ENV erstellen `conda env create -f requirements.yml`
	- Bei einer erfolgreichen Erstellung wird cmd ne laange Prozessbar zeigen (dauert paar Minuten)
	- falls so eine Errormeldung kommt:
	   ```Collecting package metadata (repodata.json): failed``` 
		1. Firewall ausgeschalten
		2. Diese [Lösung](https://stackoverflow.com/questions/50125472/issues-with-installing-python-libraries-on-windows-condahttperror-http-000-co) probieren
5. Es wird nach Aktivierung gefragt, gibt `conda activate d_py38_pv3vis` ein.
	- auf der Console wird vor dem Directory die Conda ENV`(d_py38_pv3vis)` stehen. 
6. Löschen des Environments
	1. erstmal deaktivieren `conda deactivate`
	2. und dann löschen `conda remove --name d_py38_pv3vis --all`

Die ENV auf dem PC befindet sich [hier](file:///C:/Anaconda3/envs).
Ansonsten kann das ENV manuell mit Befehlen auf cmd erstellt werden. (Erklärung findet man auf [python-setup-environment](https://github.com/htw-pv3/weather-data/blob/master/python/pv3_python_0_setup_environment.txt) unter ## Manuell)

##### Befehlliste
- Installieren eines Pakets `conda install "paketname"`
- Deinstallation eines Pakets `conda remove --name "ENV-name" "paketname"`
- Aktivieren eines Environments `activate "ENV-name"`
- Alle installierte Paket prüfen `conda list`

## [[05-Jupyter Notebook|Jupyter Notebook]]
tippe `jupyter notebook` auf cmd (sicherstellen dass du dich im Directory mit dem richtigen ENV befindest!). Öffne es am besten auf Google Chrome.
Jupyter sollte man möglichst nicht auf gitHub hochgeladen werden. Wenn dann sollte die immer gecleared (Kernel -> Restart & Clear Output) oder mit nur einer automatisierten Programmlinie erst gespeichert sein.