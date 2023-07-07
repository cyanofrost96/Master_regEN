[Folie](https://mega.nz/file/mNliQLyQ#SMFUmhyxsQ6i2FrNfJMonOHzW_bd0s3VmH709eFxa1s)
## Maximaler $\eta$
- Thermodynamische $\eta$
	  Carnot Wirkungsgrad $\eta_c = 1 - \frac{T_0}{T_{Sun}}$ = 95%
	  realistische Zwischenabsorber (Schwarzkörper) $\eta = (1-\frac{T_c^4}{T_{Sun}^4}) \cdot \eta_c$ = 85% 
- [Shockley - Queisser Limit](https://pubs.aip.org/aip/jap/article/32/3/510/505950/Detailed-Balance-Limit-of-Efficiency-of-p-n)
	  für Halbleiter mit Bandlücke unter idealisierten Bedingungen:
	  für Si; AM1,5 $\eta_{SQ,max}$= 32,7%

## Verlustmechanismen
- Rekombinationsverluste: Strahlreko. (Emission), Grenzflächenreko., SRH-Reko.
- elektrische Verluste: Serien- und Parallelwiderstand
  **Lösungen :**
	  - Serienwiderstand: Transportverluste im Halbleiter (Basis, gering Dotiert und dick; Emitter, hoch dotiert aber dünn), Kontaktwiderstand, Kontaktgitterwiderstand. Diese müssen optimiert werden.
	  - Parallelwiderstand: Leckströme an der Kanten des Wafers isolieren / abmachen, Leckströme durch die pn-Übergang führt zu einer lokalen Kurzschluss.
	  - [Optimierung der Kontaktfingerbreite und -abstand](https://www.pveducation.org/pvcdrom/design-of-silicon-cells/optimization-of-finger-spacing): Geringe Schichtdicke der Emitter führt zu höhere Widerstand, dafür legt man noch eine hochdotierte (n+) Emitter drauf damit die Leitfähigkeit sich bessert. Oder mehrere Kontaktfinger, damit die e- nicht so weit weg fahren muss.
- optische Verluste: Reflexion ([Brechungsindex](03-Optik)), Kontaktfinger/Verschattung, Transmissionsverlust, parasitäre Absorption (Licht wird da Absorbiert an Teilen die nicht gewollt sind)
  **Lösungen :**
	- Dicke der ARC anpassen : Dicke $d$ der ARC für destruktive Interferenz der Reflexion + konstruktive Int. des eindringenden Lichts $$d = \frac{k \cdot \lambda}{4n}; \quad k = 1, 3, 5, ..$$
	- Texturierung : Funktioniert nur mit mono-Si (1 0 0). Nach Ätzen erhält man wegen [[../Begriffe/Anisotropie|Anisotropie]] ein Textur von (1 1 1). Somit hat ein Licht die Chance (nachdem ersten Treffen mit der Oberfläche) nochmal in dem benachbarten Pyramide ins Material einzudringen. Andere Methode ist der Rückkontakt auch zu texturieren damit das im Wafer eingefangene Licht noch mehrmals innendrin reflektiert wird. Der gewinkelte Lichteinfall führt auch zur [Totalreflexion](https://www.pveducation.org/pvcdrom/design-of-silicon-cells/light-trapping).
	- Kontaktgitter irgendwo anders legen. (Rückseite)
	- KG hochkant legen, damit die abschattete Fläche kleiner ist aber die die Leitfähigkeit gleich bleibt, dafür größere Kontaktwiderstand. 
	- KG abrunden, damit das einfallende Licht gegen der abgerundete Fläche in Wafer reflektiert.
	- [Burried Contacts](https://www.pveducation.org/pvcdrom/manufacturing-si-cells/buried-contact-solar-cells), KG wird teilweise in Wafer gegraben (mittels Laser/Ätzen) - geringere Kontaktwiderstand und Abschattung.
	- Feinere KG aber mit mehrere Anzahl.

Warum Halbleiter für SZ geeignet sind? Lebensdauer ist da länger / Rekombination ist langsamer.

Optimierung von elektrischen und optischen Verlusten
