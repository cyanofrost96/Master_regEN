#### Diffusionskoeff.
Einheiten:
A/cm2 = As . cm2/s . cm-3/cm
Gesamt Diff.strom :
$$j_{ges}^{diff} = j_s^{drift} + j_{\beta}^{diff}$$
Gesamtstromdichte :
Einstein'sche Gleichung :
$$\frac{D_u}{µe} = \frac{kT}{e}$$
# [Wechselwirkung Strahlung - Materie](file:///D:/Docs/UNI_Master/PV1_PhysikderSolarzellen/WPV1-SS20-Folien-4.pdf)
? : Was passiert wenn Strahlung ein Materie (Halbleiter) trifft?
[[Photoelektrischer Effekt]]
## Absorption und Generation
Licht kann reflektiert, absorbiert und transmittiert werden. Deren Anteil ist von der Material (Spektrale Empfindlichkeit, Brechungsindex) abhängig.
$$I(x) = I_0 \cdot e^{- \alpha \cdot x}$$
- x : Dicke des Materials $\ce{cm}$
- $\alpha$ : Absorptionskoeffizient $\ce{cm^{-1}}$

[Spektraler Verlauf des Absorptionskoeffizienten](https://www.pveducation.org/pvcdrom/pn-junctions/absorption-depth):
Mit höherer Photonenenergie nimmt die Absorption logaritmisch zu; auf I,x Diagramm hat höherer Lichtenergie stärkerer Abfall. Dies erklärt warum bei Tandemzellen das Zellmaterial für energiearmes Licht sich auf der hinteren Seite befindet.
![[Drawing 2022-05-20 10.59.24.excalidraw]]
Silizium hat im Vergleich mit anderen photovoltaischen Materialien einen ziemlich flacheren Absorptionsverlauf, da sie ein indirekter Halbleiter ist.

### Generation
Erzeugung von Elektron - Loch - Paaren
**Erzeugung von Überschussladungsträger**
- Änderung der Gesamtladungsträgerdichte
	$$x = x_0 + \Delta x$$
- Generationsrate
	$$G_x = \frac{dx}{dt} = \frac{\Delta x}{\tau_x}$$
	x kann Elektronen / Löcher sein, relevant bezieht sich dieser x auf der Minoritätsladungsträger.
## Rekombination