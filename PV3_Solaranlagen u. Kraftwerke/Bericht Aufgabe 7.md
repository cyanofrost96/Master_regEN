# Aufgabe 7 PV3
#### Name: Azarya A. Ekaputra; 564507
### Aufgabenstellung #7: [Modellierung mit Polysun](https://moodle.htw-berlin.de/mod/assign/view.php?id=1174706&action=editsubmission)
**Ziel** : Sichere Verwendung der Software Polysun und die Abbildung der PV-Anlage Sonnja mit verschiedenen Varianten. Folgende Varianten sollen modelliert und simuliert werden. Die Ergebnisse sollen miteinander verglichen werden: WR1, WR2, WR3, WR4, WR5

Aufgabe ist es, die 5 PV-Felder in Polysun zu modellieren und simulieren. Erstellen Sie hierzu eine Projektdatei "SonnJA" und für jeden Teilgenerator (WR1-WR5) eine neue Variante. Passen Sie die entsprechenden Wechselrichter und PV-Module an. Verwenden Sie dazu die [Datenblätter](file:///D:/Docs/UNI_Master/PV3_SolaranlageKraftwerke/sonnja_documents). 

Simulieren Sie die Varianten und speichern Sie die Jahreswerte ab (Resultate -> System-Resultate -> Exportieren)

Erstellen Sie eine strukturierte Tabelle aus den CSV-Dateien:
- [ ] 3 Spalten: **Variante (wr1-wr5)**, Jan-Dez, **DC-Leistung, Jahressumme AC-Einspeisung**
- [ ] 6 Zeilen: Je Teilgenerator (WR1-WR5); Summe Sonnja

Verwenden Sie die Wetterdaten: **Meteonorm6 1min**

## Ergebnis
Die verschiedene Variante werden in Polysun simuliert und das jeweilige Ergebnis in unterer Tabelle eingetragen. Zu den genaueren Parametern von den Varianten kann man auf dem [Pad](https://etherpad.wikimedia.org/p/htw-pv3-2022-code) finden.

*in kWh*|$E_{gesDC}$|$E_{gesAC}$
---|---|---
WR1|3338|3118
WR2|3017|2815
WR3|3245|3033
WR4|3316|3158
WR5|3599|3433
Summe|16515|15557
Meine Ergebnisse liegen immer noch im "akzeptablen Bereich", im Vergleich mit denen von den anderen Vorlesungsteilnehmer. Meine Vermutung ist so, dass ich paar Anpassungen auf Polysun nicht richtig eingetragen habe da ich an dem Tag nicht anwesend sein konnte (aufgrund eines Labors).

Die Parametern zu den Varianten (WR1 bis WR5) kann von den folgenden Screenshots wahrgenommen werden.
![[wr1.png|500]]
![[wr2.png|500]]
![[wr3.png|500]]
![[wr4.png|500]]
![[wr5.png|500]]
(in Zusammenarbeit mit Sherwan Haj und Pablo da Costa)