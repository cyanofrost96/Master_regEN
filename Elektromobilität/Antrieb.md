fast alle E-Autos haben Hinterradantrieb, sogar allrad antrieb weil die Motoren im Vergleich zum Verbrenner deutlich kleiner sind. Zum Energiesparen wird ein Motor ausgeschaltet falls es nicht schnell beschleunigt werden muss.

## Synchronmaschine
Synchronmaschine haben allgemein höhere Leistungsdichte und arbeitet bei geringer Leistung effizienter
kann in alle 4 Quadranten (Motor/Generator, unter-/übererregt) betrieben werden.
$U_1$ bzw $f_1$(Ausgangsspannung und -frequanz von dem Umrichter wird durch das Treten des Gaspedals eingestellt)

Kippmoment; Maximaler Drehmoment eines Synchronmaschine
Arbeitsbereich ist zwischen -90° bis 90°
Formel für den Drehmoment
$$M=\frac{m \cdot U_1 \cdot U_P}{2 \pi \cdot n_1 \cdot X_d} \cdot sin(\theta)$$
typischer SM hat steigende Effizient mit höherer Leistung und geht ab dem Kipppunkt direkt runter

### PMSM
*permanent Magnet Synchronmaschine*
$U_f$ proportional zu $n$ , und  $U_f$ proportional zu $I_F$
Nachteile ist dass der Motor trotzdem er ausgeschaltet ist noch Strom bezieht, materialabhängig

### FESM
*Fremderregte Synchronmaschine*
hat weitere Regelungsfreiheitsgrad für die Magnetisierung ($U_P$)
Nachteile ist dass es größer und schwerer

## ASM
Effizient aber nur bei höhere Leistung.

## BLDC
*Brushless DC*
durch Rechtecksignalen gesteuert, eher für kleinere Motoren mit höhe Drehzahl verwendet (geringer Reibungsverlust bei höher Drehzahl)

### *Exkurs*: Statorwicklung effizienter machen
Nutfüllfaktor erhöhen; Nut im Stator sind die Lücken für die Kupferwicklung. Sie müssen vor dem Eisenstück elektrisch isoliert werden.

*Skineffekt*: bei Wechselstrom mit höherer Freq. werden die Elektronen wegen Eigeninduktion nach außen gedrängt.

*Schleppverluste*: Verlust beim nur drehenden Motor (Ohne Last oder Leistung). Bei PMS muss Kupplung eingebaut werden (mechanische Trennung). ASM hat kein Schleppverlust weil die ohne Versorgungsspannung stromlos dreht.
