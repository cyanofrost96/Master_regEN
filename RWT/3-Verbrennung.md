# Grundlage:
Bereitstellung von Hochtemp.wärme, reagiert mit Luft bzw. Sauerstoff.
eine thermochemische Energieumwandlung in $CO_2$ und $H_2O$.

## [[Brennwert]] $H_s$ und [[Heizwert]] $H_i$
Reaktionswärme bei isobar-isothermer Reaktion. Nach der Reaktion beträgt die Temp. bei 25°

Typische Einheiten dafür sind: $kJ/mol$, $MJ/kg$, $MJ/m^3$

bsp. Wasser: -241,6 kJ/mol für Heizwert und - (noch zu Googlen)

### Zusammenhang zw. trocken / feucht u. Brenn- / Heizwert

Zusammenhang von beiden:
	$$H_{s,t} = H_{i,t}+\Delta^{LV}h \cdot \frac{m_{H_2O}}{m_{tb}}$$
	$$H_{s,t} = H_{i,t}+ 22 \cdot H'$$

Zusammenhang zw. trocken und feuchtem Brennwert:
	$H_s = (1-W) \cdot H_{s,t}$

## Brennstoffgemischen
Die Komponenten werden nach der Massenanteil bzw. Volumanteil  gewichtet und gemittelt.

Näherungsgleichungen und -tabelle sind vorhanden für meist verwendete Brennstoffen (in Abhängigkeit der Elementarzusammensetzung)
- nach Boie:
	Heizwert:
		$H_{i,t} = 34,8\cdot C'+93,9\cdot H'+10,5\cdot S'+6,3\cdot N'-10,8\cdot O'$
	Brennwert:
		$H_{i,t} = 34,8\cdot C'+(93,9+22)\cdot H'+10,5\cdot S'+6,3\cdot N'-10,8\cdot O'$
$m_b \cdot H_i = m_{tB} \cdot H_{i,t} - m_W \cdot \Delta^{LV}h$

Heizwert, feucht:
	$$H_i = (1-W)H_{i,t} - 2,44 \cdot W \frac{MJ}{kg}$$

### Massen- und Energiebilanz Heizkessel
besteht aus einem Brennraum und die Wärmeübertragung
Input: Massenstrom des Brennstoffs und Luftströme.
stoffgebundene Energieströme sind Enthalpieströme
Output: Nutzwärme, Verlustwärme, Massenstrom des erschöpften Brennstoffs

Massenbilanz:
	$$\dot m_{Luft} + \dot m_{Brennstoff} = \dot m_{Gas} + \dot m_{Asche}$$
	Luftzahl bezieht sich auf $$\lambda = \frac{\dot m_L}{\dot m_B}$$
Energiebilanz:
	$$\dot H_L + \dot H_B = \dot Q_{Nutz} + \dot Q_{v,ges}$$
Wirkungsgrad:
	$$\eta_K = \frac{\dot Q_{Nutz}}{\dot H_B} = 1-\frac{\dot Q_{v,ges}}{\dot H_B}$$
	$$\dot Q_{Nutz} = \dot H_B - \dot H_G - \dot Q_{verl} - \dot H_A$$
	
## Verluste im Verbrennungsprozess
### Verluste beim Wärmeübertrager
$$\Delta E_{V,WÜ}=(\frac{T_{mH} \cdot T_u}{T_{mH}}-\frac{T_{mK} - T_u }{T_{mK}}) \cdot \dot Q$$
H : Heizkessel ; K : Kältemittel
**Indizes zur Vorlesungsfolien:** 
	adV: adiabatische Verbrennung
	G: Gas
	m: Mittel(-temperatur, -energie, usw.)
	U: Umgebung
	$c_{pv}$ : 

## Brennwertnutzung
## Luftgrad berechnen
beim verbrennungsprozess wird der Wirkungsgrad sinken wenn man zu viel bzw. zu wenig luft in die Reaktion mitbringt. Deswegen ist es wichtig eine saubere Verbrennung zu gewährleisten mit eine vorherige Rechnung
$M_L + 1 = A + M_G$ 
$M_L = \frac{\dot m_L}{\dot m_B}$
$M_G = \frac{\dot m_G}{\dot m_B}$
$M_L$ ist eine wichtige Kenngröße für Effizienz der Verbrennung und resultiert sich aus stöchiometrischem Sauerstoffbedarf.
### Mindestluftbedarf
Die normlae Luft setzt sich aus mehrere Gasen zusammen;
Stoffmengenanteil $x_{N_2}=0,79$ und $x_{O_2}=0,21$. Massenanteil der Sauerstoff beträgt: $\xi_{N_2}=0,232$.
Aufgrund dessen beträgt der Mindestluft bedarf (bezüglich der Masse) $=4,31$.
Infolgedessen für einen normalen Verbrennungsprozess wird $11,5C$ an Sauerstoff verbraucht.

**Für gasförmige Brennstoffe**
$$L_{min}=\frac{V_{tl,min}}{V_B}$$
Absolute Feuchte beschreibt wie viel Wasser im Vergleich zur trockenen Luft.
$X=\frac{M_W}{M_{tL}}$, im Winter beträgt es 2 $\frac{g}{kg}$ und Sommer $=9\frac{g}{kg}$. $X$ ist einheitslos

**Luftüberschuss $\lambda$** (Luftzahl)
benötigt bei aller Verbrennung da nicht alle Molekülen direkt im Kontakt sind. (wie Sicherheitsgrad)
$$\lambda = \frac{M_L}{M_{L,min}}$$und ist auch einheitslos. Verschiedene Feuerungsart benötigt auch andere Luftzahl. Diese beeinflusst wie gut die Molekülen in einer Verbrennung zusammenwirkt.
