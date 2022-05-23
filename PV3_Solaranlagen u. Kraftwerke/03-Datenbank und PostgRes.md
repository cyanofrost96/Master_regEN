# Übersicht
Diesmal wird es über die typische Datenbank zur Verarbeitung einer Solarsimulation erklärt
# Datenbank
Darunter stehen 3 wichtige Constraints:
	1. Name der Spalte
	2. Datentyp (länge)
	3. Metadata / maximale Länge (Einheit des Systems wie Leistung)

Zu der Vorlesung werden pgAdmin und PostgreSQL verwendet.
pgAdmin ist ein User-Managementsystem (GUI) zu dem Datenbank PostgreSQL

Die Motivation, Datenbank zu nutzen ist eine organizierte Sammlung an Daten zu schaffen.
## PostgreSQL
Zur Vereinfachung werden die Datenbankname, Username sowie Passwort als "postgres" benannt.

Mit dem Server 14 (aktuellste) verbinden und dazu wird das Passwort gefragt. *PV3#2022*
Die Codes befindet sich unter "SQL" Tab zu den geraden ausgewählten Bereich an der linken Browser Folderliste.

Unter File "Login/Group Roles" und "postgres" (also unser Username) befindet sich die Rollenzuweisung der User. Darunter stehen wie; SUPERUSER, INHERIT, REPLICATION, usw.

Zum Ausführen der Code: geh auf Tools -> Query Tools. Danach wird ein neuen Tab namens @PostgreSQL 14 geöffnet und da kann man die Codes aus dem Skript auf Github Repo [/weather-daten](https://github.com/htw-pv3/weather-data/tree/master/postgresql) kopieren und mit F5 ausführen. Als Ergebnis werden neue Liste auf dem linken Fenster zu finden 

Grundsätzlich funktioniert SQL wie trnsys.
### Anzeigen der Datenbank
Zum Anzeigen des Inhalts wie bei Excel wird ...

#### Skript 01_User Management
Hier werden die Rolle der User zugewiesen.
#### Skript 02_Database Setup
Man muss neue Database unter den Namen "sonnja_db" erstellen und erst da kann die Codes aus dem Skript ausgeführt werden.
Zuerst werden Extension installiert !bitte nur unter sonnja_db machen, nicht auf dem Standard "postgres"
#### Skript 03_Schema Setup
Eingliederung der Sequences wird mit diesem Skript ausgeführt. !Beim erstellen neuer Schema immer die linke Leiste refreshen!
#### Skript 04_Logbuch erstellen
hier werden die Funktion für die Verlaufdaten der Simulation bzw. in tabellarischer Format erstellt.
#### Skript 05_
Hier muss Import data zum Skript auf dem Ordnerpfad; `C:\data\pv3_data_2015\` hervorgerufen und dazu muss ja den Ordner erst erstellt werden.

### SQL Befehlliste
###### Löschen der vorherigen Tabelle
Zu aller erst sollen die vorherige Tabelle mit dem gleichen Dateiname gelöscht, bevor die neue erstellt wird.
```
DROP TABLE IF EXIST "Name der Tabelle" CASCADE;
```
###### Erstellen neuer Tabelle
```
CREATE TABLE "Name der Tabelle" (
	"Inhalt der Tabelle mit "SPALTE" und die "EINHEITEN" mit Tab getrennt
) ;
```
###### Kommentieren
man kann ein Kommentar im Codes hinterlassen indem man diese Funktion verwendet; 
```
/* "hier dein Kommentar" */
```
### SQL
*eng. (Structured Query Language)* ist eine Quasi-Programmiersprache und läuft nur von oben nach unten (keine Schleife). Da werden nur Datenbank gültig. 

## Bezug mit [[02-Github|Github]]
Wetterdaten aus dem Repo [htw-pv3/wetter-daten](https://github.com/htw-pv3/weather-data) sollen runterladen werden (mittels GitBash)