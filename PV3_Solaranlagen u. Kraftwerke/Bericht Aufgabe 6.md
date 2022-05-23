# Aufgabe 6 PV3
#### Name: Azarya A. Ekaputra; 564507
### Aufgabenstellung #6: [Systematische Bestimmung der Messlücken](https://moodle.htw-berlin.de/mod/assign/view.php?id=1174705)
**ZIEL** : Systematische Bestimmen aller Messlücken in den vorhandenen Daten (Weather, WR1-5).

Folgende 10 Parameter sollen automatisiert berechnet werden:

0. Anzahl Soll-Messwerte
1. Anzahl Lücken in Wetterdaten (gesamt)
2. Anzahl Lücken in WR-Daten (gesamt)
3. Anzahl Lücken in Wetterdaten und WR-Daten
4. **Anzahl Lücken in Wetterdaten (zusammenhängend)**
5. **Anzahl Lücken in WR-Daten (zusammenhängend)**
6. **Anzahl Lücken in Wetterdaten am Tag**
7. **Anzahl Lücken in WR-Daten am Tag**
8. Anzahl Lücken in Wetterdaten und WR-Daten (=3.?)
9. Anzahl Lücken in Wetterdaten und WR-Daten am Tag

## Ergebnis
Die Ausführung der Postgresql-Skripte 1-10 ist erforderlich, um die erforderlichen Tabellen zu erstellen.

Die Anzahl an Messlücken auf verschiedene Datentypen (WR gesamt, am Tag; Wetter gesamt, am Tag; usw.) kann aus dem .../sonnja_db/Schemas/pv3/Materialized Views/pv3_data_analysis_mview als .csv Datei zugegriefen werden.

![[Pasted image 20220518121032.png]]

Die deutlich mehr auftretenden Lücken in der Datei "WR-Daten am Tag" im Vergleich zur zusammenhängenden Version lassen sich so erklären, dass das Programm jede Minute schaut, ob Daten vorhanden sind oder nicht. Es bündelt längere Lücken nicht als eine, sondern als mehrfach auftretende Lücken. Dadurch erhält man die Zahl 6625, obwohl man gebündelt nur 40 Lücken hat.

Es gibt verschiedene Gründe, wie es zu Lücken gekommen ist, und es gibt auch Lösungen, wie man diese auffüllen kann. 
- Nach der Sonnenuntergang sollte bei photovoltaischer Anlage kein Strom mehr erwartet und Lücken in dieser Zeit kann mit 0 aufgefüllt werden.
- kurz auftretende Lücken in der Sonnenzeit kann so behoben werden, indem man die benachbarte Daten interpoliert, und so die Lücke eintragen.
- Bei längerem Lückendauer braucht man paar Recherche; man sollte es nach ähnlichem Daten aus anderer Messwerten vergleichen und daraus eine Zusammenhang mit unseren bilden. Interpolation aus letzten vorhandenen Daten kann auch ausgeführt werden.

(In Zusammenarbeit mit Pablo da Costa)