# 1. Labor (Herstellung)
## PECVD
Zelle muss aus Oxid gereinigt werden (von HF prozess)
300W als Plasma Power

5nm Schicht (damit das Licht noch bis zum emmiterschicht durchdringen kann)
Vakuumkammer mit verschiedene 'Kammerchen' fürs auftragen von Materials
- Stickstoff : damit die Entspannung und komprimieren kein Wasser bilden
- 

Drück: 1-10 mbar
Temp : 200C

Amorphe Schicht ist besser da Kornbildung Störungen auf der Schichten bildet

Reinigung mit ähnlichem Prozess wie fluidized bed mit SiF silan

4Wafers werden auf einem Brett aufgelegt und wird in Vakuum vorbehalten maßgenau eingeführt. Erst wird es in N2 Kammer reingemacht und da werden die Luft mit N2 ausgetauscht und somit der Druck auf 1mbar reduziert. Danach wird diese mittels mittlere Arm im Vakuumkammer in die anderen Kammer (R1) verschoben, wobei die n-schicht aufgetragen wird.danach geht es in den anderen Kammer (R2). die Zelle wird geflippt und wieder in den Kammer reingeführt. Diesmal geht's zum R1 und dann zu L1. 

## Sensoren
Spannungsensor (plasmabestandig), optische Kabelfaser für spektroskopie, Gassensor (Abgas und doeniergas)

## Messung
Wird nach Lebensdauer der Ladungsträger bestimmt
Kapazität wird gemessen
2-8 ms ist gut
Messung wird auf einem 'Herdplatte' gemacht
1_60: 1906 us
2_61: 1826 us
3_62: 1649 us
4_71: 2287 us
(Anordnung kann falsch sein)
lebensdauer messung wird nur an bestimmte punkt der zelle gemacht, nicht gesamte zelle

## Entsorgung von schädliche Gasen
Fluor nervengas, Silan brennt, NF3
Ventile
SiO4 schädlich
Beim Abgas wird mit Sieb gefiltert
Oder mit Propan brennen
Abwasser muss auch mit dem Wasseraufbereitungslage abgesprochen (hier ist normalerweise basisch/alkalisch)

## HF
3MHz, muss kompensiert werden damit Sachen nicht kaputt gehen (Parasiten Effekt)

## Sputtern
Vertikal gestellt und die Maschine Fahrt quer durch
10e-7 mbar ab 10e-3 mbar wird abgeschaltet
Kammer wird mit Argon befüllt (inert)
Ziel ist es, Front- und Rückkontakt sowie die ITO auftragen
Material Ausbeute: 35% planar kann gedreht werden um eine Ausbeute von 80% zu erreichen
Wenn's zu dick aufgetragen kann es reißen. 

## Siebdruck
Silberpaste wird auf einem Fläche mit Rakel aufgetragen
Auf Heizplatte (210C)

# 2. Labor (Charakteriesierung)
in Analytik 2 gemessen (Leistung, Kennlinie, usw.)
passivieren mit amorphe Si um fehlstellen zu decken, hat aber schlechte leitfahigkeit -> deswegen die ITO.

fehlstellen von reine silizium: nicht verbundene 'Si-händen' verbindet gerne mit andere atomen.

antireflexschicht -> Si nimmt lieber IR licht 1100nm bereich

## TLM
zur Messung von der diodenverhalten : messen von -200mV bis 900mV in 10mV schritte

zur berechnung: d zu R ist linear, mit regression auf x = 0. Widerstand : $2 \cdot R_c + R_{Si}$

## EQE (und spektrale Empfindlichkeit)
Zelle wird mit monochromatischem Licht 300nm bis 1200nm bestrahlt 
wie viele elektron loch paare erzeugt pro photonen mit dem bestimmten Wellenlänge 
kleinere wellenlänge dringt weniger tief ein
EQE hat keine einheit und stellt nur die photonenausbeute dar. Spektrale empfindlichkeit zeigt die erzeugte strom. bei höherer quantenenergie fliegt das elektron zu weit vom leitungsband und wird nur besser, näher zu 1100 nm (da es die bandlücke eines Si is6t)

gerät hat 2% messfehler

## IU Kennlinie
Sonnensimulator! muss STC folgen, zelle ird auf einem gekühlte unterlage gelegt.
die Bestrahlung wird mittels Referenzzelle angepasst (zertifikat ist auch drauf)
1. mit 2 strahler blau und halogen
2. mit verschiedene LEDs

Kontakt: tobias.haenel@helmholtz-berlin.de

Zellentesttyp: SHJ 5inch 12c

gerät hat 1% messfehler

## Reflexion
Gerätbeschreibung hinzu.
misst in 5nm schritte, 250 bis 1500 nm
muss erst mit weißer Probe geeicht werden.
Licht muss mittig treffen.
gerät laufen lassen und hat man am ende den Reflexionsverlauf1

## Photoluminesenz
wird wie LED betrieben, ausgestrahlene Licht wird von IR kamera aufgenommen
Zelle wird mit LED bestrahlt
kamera lässt nur >850nm durch
beleuchtet für 1/8 ms
am rand gibt's viele fehlstellen und 2. reihe gibt's eine linie an flecken -> konnte wegen mechanischen stress (pinzetten, sputtern gehäuse)
die flecken an 2. reihe kommt immer wieder vor

Rückseite ist gold da es dünnere ITO aufgetragen ist (Rückseite hat genug kontaktgitter) 

die 'bestrahlung' einer referenzzelle und die base-folie wird noch mitgeteilt, Ränder sind benachteiligt

# Vorbereitungsfragen
• Was unterscheidet die PECVD von der konventionellen CVD?
	PECVD - plasma enhanced chemical vapour deposition; ist eine chemische Material-auftragen-methode, die durch die Verwendung von Plasma verbessert wird. CVD (chemical vapour deposition) ist eine Ablagerung von soliden Materialien aus gasphasigem Zustand.

• Mit welchen Prozessparametern lässt sich die Deposition von a-Si:H Schichten mittels PECVD steuern?

• Bitte erläutern Sie den Unterschied zwischen Planar- und Rohrkathoden beim Sputtern. Geben Sie bitte für beide Methoden jeweils einen wichtigen Vorteil an.

• Warum ist die Oberfläche des Wafers zwischen den Silberkontakten in Abbildung 6 blau?
	Es liegt daran, dass die Zelle mit Anti-reflex Schicht aus TCO beschichtet wird. Die Dicke dieser Schicht wird so ausgewählt, dass sie möglichst mehr von dem langwelligen Spektrum absorbiert wird. Der kurzwellige Spektrum wird die meisten reflektiert und deswegen sieht die Oberfläche blau aus.

• Bitte schätzen Sie die offene Klemmspannung eines SHJ c-Si Modules bestehend aus 60 Solarzellen ab. 
	eine SHJ Zelle liefert 620 bis 640 mV, 60x sind 37,2 bis 38,4 V.

- Wie wird der Kurzschlussstrom des gesamten Moduls von der Kurzschlussstromdichte der einzelnen Solarzellen beeinflusst?

• Bitte erläutern Sie die 2- und 4-Spitzen Messmethode. Warum wird die 4-Spitzen Messmethode bevorzugt angewendet?

• Bitte skizzieren Sie den Zusammenhang zwischen Kurzschlussstrom und Leerlaufspannung als Funktion der Bestrahlungsstärke. Erläutern Sie ganz kurz die Form der Kurven.

• Bitte erläutern Sie, mit welchen Methoden die Reflexion an der Solarzellenoberfläche reduziert werden kann.
	durch Ätzen (Strukturieren des Oberfläche) und Sputtern von Antireflexschicht auf der Oberfläche der Zelle werden einkommende Lichtpartikeln weniger reflektiert, da der reflektierte Anteil durch destruktiver Interferenz gelöscht wird. Somit steigt die absorbierte sowie transmittierte Anteile.

• Bitte skizzieren Sie die Absorption als Funktion der Eindringtiefe als auch als Funktion der Wellenlänge.

• Bitte erläutern Sie, welche Messmethoden verwendet werden müssen, um die interne Quanteneffizienz zu ermitteln.
