# Titel : Abwärmenutzung PEM Elektrolyseur für niedertemperaturige Verbraucher
[Link zum Cloudspeicher](https://mega.nz/folder/qIEjXb4S#LAwIo18I73PyouUojZee0Q)
# 1 Einleitung
## 1.1 Einführung in das Thema
Kurze Historie und die Entwicklung über Elektrolyseur und die Ideen über eine "konzentrierende grüne H2 Anlage". Warum Elektrolyseuren noch nicht in große Maßen gebaut sind.

HTEL auch in Betrachtung bringen.

EL Hersteller kontaktieren.
## 1.2 Problemstellung und Zielsetzung
Verfügbare Energie aus Windpark und PV-Park, Verlauf über ein Tag und über das Jahr (saisonal)
## 1.3 Ideen und Methodik
Verbesserung der relativ geringen eta durch Wärmenutzung in verschiedenen Bereichen. Auch eine Möglichkeit weitere Kategorien in Thema Sektorkopplung zu verbinden, bsp. Agrikultur und Wärme.
# 2 Grundlagen
## 2.1 Elektrolyseuranlage
ein Beispielanlage aus der Firma [H-TEC Systems](https://www.h-tec.com/fileadmin/user_upload/produkte/produktseiten/ME450-1400/spec-sheet/H-TEC-Datenblatt-ME450-DE-23-08.pdf)
## 2.2 Abwärmenutzung
[Industrielle Abwärmenutzung](https://www.isi.fraunhofer.de/content/dam/isi/dokumente/cce/2013/Kurzstudie_Abwaermenutzung.pdf) Konzepte und pro/kontra von Abwärmenutzung (in industriellen Bereichen)

Laut einer Studie aus Fraunhofer Institut zur industriellen Abwärmenutzung solle es klar sein, wozu die Abwärme hingeführt wird, sonst wird es als Energieeffizienzmaßnahme von der Bedeutung abweicht. Dazu gelten die folgende fünf Kriterien zum Nachdenken bevor es mit der Planung anfängt. (Dimensionierung, Steuerung, Temperaturniveau, Isolation, Alternativen)
Ansonsten sagt Fraunhofer Institut erfahrungsgemäß auch, dass solche Projekte nur zögerlich umgesetzt, da viele Hemmnisse und Risiken besteht. Beispiele davon sind unzureichende Informationen von der Verbraucherseite oder Kapital vom Projektplaner. Von daher müssen die folgende Faktoren vor dem Einsetzen klar sein; Amortisationszeit, Anlagengröße, Umweltwirkungen, Erschließbarkeit
## 2.2 Wärmepumpe
## 2.3 Wärmetransport
Abwärmenutzung in Nahwärmenetz, [was ist Nahwärmenetz?](https://www.naturstrom.de/Energieprojekte/Buergerenergie/Markt_Erlbach/Nahwaerme_NATURSTROM_FAQ.pdf)
Zur Transport sind mind. zwei Technicken erförderlich:
- Rohrleitung :
	Wärme verliert sich immer Richtung außen, beeinflusst durch Wand-, Isolationsstärke des Rohres, sowie Strömungsgeschwindigkeit des Fluids.
	[Formel: Verlust beim Transport](http://www.fernwaermeleitungen.com/waermeverlust.html) und Berechnung in excel implementiert. Quelle beinhaltet auch typische Leitungsgroße und deren U-Wert.
	Beispiel: [H-75+75 Rohr](https://www.boesken.de/installation/nah-und-fernwaermeleitungen/isoplus/isopex-doppelrohr-heizung/19998/isopex-doppelrohr-heizung-typ-h-75-75-da-2-x-75-da-200-aus-kunststoff-6-bar)
	Dazu gibt es ein [Druckverlustdiagramm](https://www.sbz-monteur.de/gut-zu-wissen/optimierung-von-heizungsanlagen-rohrnetzberechnung-teil-1), das die Druckgefälle mit bestimmter Strömungsgeschwindigkeit und Rohrdurchmesser darstellt
	
- Wärmeübertrager
## 2.4 Trnsys (und andere Simulationsprogramme)
Kurze Erklärung über die Sim.programme, was einzugeben und was sind zu erwarten.
# 3 Methodik
## Verbrauch
Wie groß der Wärmeverbrauch der Häuser in [Krickow](https://maps.app.goo.gl/qbnyBZMkbCnfNZM19), [Zachow](https://maps.app.goo.gl/631nETm14yyN9XmH7) und [Groß Nemerow](https://maps.app.goo.gl/eTwfeeDyoKfrVNpn9)
Erstmal von dem durchschnittlichen Wärmeverbrauch 
## nutzbare Abwärmeenergie
aus der Elektrolyseuranlage. Weil es von den Anlage 
## Anwendungen der Abwärme
- Wärmeverbrauch der Häuser in den Ortschaften nähe Anlageort.
- Trocknungsanlage für den Sommermonaten als Ausgleichssenke.
	  recherche über wie läuft eine Maschine, mit Nahwärme als Quelle
- Fischzuchtanlage
	  hier müss noch recherchiert werden ob es als Wärmestabilisator agieren kann oder nicht
-  Aquifere Speicher [1aq](https://www.adlershof.de/fileadmin/user_upload/Projektflyer_GeoFern.pdf)
## Simulationsdaten & -ideen
Standort-, Verbrauch-, Energiequelledaten wird hier erklärt. Wie wird die Simulation durchgeführt, was sind die wichtige Eckdaten und die Ideen (bezogen auf der Fischzucht und Gemüseanbau)
# 4 Ergebnisse
## Simulationsergebnisse
Simulation, Grafik und Tabelle erklären
## Wärmekapazität und Wirkungsgrade
Große der verfügbare Wärme für Nahwärmenetz und Große der Fischzucht / Gemüseanbau
## Gesamt-eta-Verbesserung für die Anlage
Wie viel höher wird der Wirkungsgrad betragen nach jeweilige Umsetzungen der Ideen.
# 5 Fazit