# Festkörperphysik
die Folie zur Vorlesung ist [hier](file:///D:/Docs/UNI_Master/PV1_PhysikderSolarzellen/WPV1-SS21-Folien-2-Festkörperphysik.pdf)
## [Kristallstruktur](https://de.wikipedia.org/wiki/Kristallstruktur)
? Was ist ein Kristall ?
- 3 dimensionale periodisches Auftreten von gleichbleibendem Struktureinheiten (Elementarzelle)
- Fernordnung: mikroskopisches Eigenschaften entsprechen Makro Eigenschaften
- [[Anisotropie]]: Eigenschaften sind richtungsabhängig. [[Millersche Indizes]] ist die Beschreibung für die entsprechende "Richtung"en. Abstand zum nächsten Nachbaratomen sind ungleich.

### [[Kristallinität]]
Grundsätzlich gibt es 3 Arten: [[monokristallin]], [[multikritallin]], und [[amorph]]

### Gittertypen
Es gibt 7 [Kristallgitter-Strukturen](https://www.chemie-schule.de/KnowHow/Kristallgitter): triklin, monoklin, orthorhombisch, tetragonal, trigonal, hexagonal, kubisch
Gitter + Basis -> Kristallstruktur
Basis besteht aus mind. 2 Atomen
Gitterkonstante ($a, b, \alpha$) gibt an, wie weit ist der Abstand zu den Nachbaratomen.
[[Silizium]] hat eine Gitterkonstante von 5,431 $10^{-10}$ m; besteht aus 8 Eckatome, 6 Ebenenatome, und 4 innere Atome

## Bandstruktur
[[Bohrsches Atommodell]] ist der Basis zum Bändermodell.
Die Energie einer elektromagnetischen Welle wird mit Planck'sches Wirkungsquantum erklärt.
Nach Einstein: $$ E = h \cdot \nu = h \cdot \frac{c}{\lambda}$$
	E = Energie eines Lichtteilchens in eV; 1 eV = $1,602\cdot 10^{-19}$ Joule
	h = Plancksche Zahl; $6,626 \cdot 10^{-34}$ Js
	$\nu$ = Frequenz der EM-Welle in Hz
	c = $3 \cdot 10^6$ m/s
	k = Wellenzahl bzw. Boltzmann-konstante in 1/cm = $\frac{2\pi}{\lambda}$
**!Rechenhilfe**: $\frac{1240}{\lambda}$ = eV, $\lambda$ soll in nm angegeben sein.
Festkörper -> Aufspaltung des Energieniveaus nach Pauli-Prinzip

Hier gibt es das Valenzband, das höchste vollbesetzte Energieband darstellt sowie Leitungsband, das höhere Band wo die Elektronen frei zu den anderen Atomen wandern können. 

## Halbleiter
Differenz zwischen Valenzband und Leitungsband soll unter 5eV liegen. 
In sich kann [[photoelektrischer Effekt]] stattfinden.
In[[direkter Halbleiter]] ist ein Eigenschaft von Gitterkristallen, wobei es bei der Absorption von Licht eines Atoms auch beeinflussen kann. Durch die Schwingung des Gitters (namens Phononen bzw. Impuls) wird die nötige Lichtenergie entweder erleichtert oder erschwert.

### Wellen-Teilchen-Dualismus
Eigenschaft eines Licht bzw. Elektronen, die nicht nur als Teilchen sondern auch als Welle verhalten können. Als Teilchen haben sie die Eigenschaften von ($E$ Energie, $m$ Masse, $p$ Impuls). Als Welle ($\nu$ Frequenz, $\lambda$ Periode, $k$ Wellenzahl)
nach De Broglie: $$p = \frac{h}{2\pi}\cdot k$$
reduzierte Plancksche Zahl: $\hbar = \frac{h}{2\pi} = 10^{-34}$
Bandstruktur im Impulsraum
Die Formel nach der zusammenfügen der Impulsformel: $$E = \frac{m_e}{2} \cdot v^2 = \frac{m_e}{2} \cdot (\frac{p}{m_e})^2 = \frac{p^2}{2m_e}$$
$$E(k) = \frac{\hbar^2}{2m_e} \cdot k^2$$
![[Bandstruktur im Impulsraum.excalidraw|400]]
freie Elektronen im Vakuum
Elektronen in Festkörper: Wechselwirkungen mit Gitteratomen und freien Ladungsträgern. Dadurch gibt es ein angepasste effektive Masse $m^*$. (Dispersionsrelation)
Die effektive Masse wird aus der zweite Ableitung der Funktion E(k) berechnet.
$$E''(k) = E(k) \cdot \frac{\delta^2}{\delta k^2} = \frac{\hbar^2}{m_e^2}$$
somit ergibt sich:
$$m_e^*=\frac{\hbar}{\frac{\delta^2E}{\delta k^2}}$$
Je höher die Krümmung der Parabel desto geringer die effektive Masse der Elektron (Umgekehrt proportional)

beispiel für Silizium:
$$m_{negativ}^* = 1,18 \cdot m_e$$
$$m_{positiv}^* = 0,81 \cdot m_e$$


>[!extras]
>- [Zeitkristall](https://de.wikipedia.org/wiki/Zeitkristall#:~:text=Ein%20Zeitkristall%20ist%20ein%20Quantensystem,periodischen%20Zustand%20eines%20konventionellen%20Kristalls): 4-dimensionales Kristall