## LT-Statistik
Bestimmung der LT-Dichte: nach der Konzentration von:

### Zustandsdichte $g(E)$
***Wie viel Plätze stehen der Elektronen / Löcher zur Verfügung?***
$$g_{C/V}(E) = \frac{4 \pi (2m_{n/p}^*)^{3/2}}{h^3} \cdot \sqrt{|E-E_{c/v}|}$$
### [Besetzungswahrscheinlichkeit](https://smile.hsu-hh.de/app10/default1.html?lang=1) $f(E)$ 
***Mit welcher Wahrscheinlichkeit werden diese Plätze besetzt werden?***
Verteilungsfunktion nach Fermi. 
Elektronen befinden sich unter (0K / niedrigerem Temperatur) auf den untersten Band, und die Besetzungsmöglichkeit von den höheren Energiebänder sind 0% / geringer Wahrscheinlichkeit. Mit steigendem Temperatur steigt die Besetzungswahr. der oberen Energiebänder und somit sinkt die Wahr. der unteren.

![](Besetzungswahrsch.excalidraw|350)

$$f(E) = \frac{1}{1+\ce{exp} \left(\frac{E-E_F}{kT}\right)}$$
$kT \: \ce{bei} \: T=300\ce{K} \rightarrow 26 \: \ce{meV}$
Die Formel gibt die Wahrscheinlichkeit an, mit der eine Energie Zustand E besetzt ist.
**Grenzfälle :**
- $E < E_F$ : $f(E) \rightarrow 1$ 
- $E = E_F$ : $f(E) = 0,5$
- $E>E_F$ : $f(E) \rightarrow 0$ 

### LT-Konzentration $n(E)$
$$n(E) / p(E) = g_{C/V}(E) \cdot f(E)$$
Ladungsträgerverteilung (Elektronen im Leitungsband $n(E)$ / Löcher in Valenzband $p(E)$) ergibt sich aus der Zustandsdichte $g_c(E)$ und Besetzungswahrscheinlichkeit $f(E)$

Quantitative Bestimmung der Ladungsträgerdichte:
$$n/p \quad = \quad \int_{E_C}^{E_C^{max}} n(E)\:dE \quad = \quad N_{C/V} \cdot \ce{exp} \left(-\frac{|E_{C/V}-E_F|}{kT}\right)$$
$$N_{C/V} = 2\cdot \left(\frac{2\pi \cdot m_{n/p}^* \cdot kT}{h^2}\right)^{3/2}$$
Bsp.: Si, $T=300\ce{K}$, $m_n^*=1,18m_e$ $\rightarrow N_c = 3,22e19 \: \ce{cm^{-3}}$ 

### intrinsische Ladungsträgerdichte $n_i$
$$n_i = n = p = \sqrt{n\cdot p}$$Massenwirkungsgesetz (chem.) gilt universell für dotierte Halbleiter
$$n_i^2 = N_C \cdot \ce{exp} \left(-\frac{E_C-E_F}{kT}\right) \cdot N_V \cdot \ce{exp} \left(-\frac{E_F-E_V}{kT}\right)$$
$$n_i = \sqrt{N_C\cdot N_V \cdot \ce{exp} \left(-\frac{E_g}{kT}\right)}$$
Bsp.: Si, 300K, $E_g = 1,12 eV \rightarrow n_i = 1e10 \: \ce{cm^{-3}}$ 

Bei kleinerer Bandlücke ist das Material leitfähiger (haben mehr Ladungsträgerkonz.)
Temperaturzunahme führt zur kleinerer Bandlücke
Der intrinsische Ladungsträger nimmt mit steigendem Temperatur exponentiell zu.

## Dotierung
Es gibt dazu zwei Akteuren:
- **Donator** : "Spenden" Elektronen; Erzeugt n-Typ
	  Bringt der Energieniveau des Bandstrukturs höher $\rightarrow$ freies Elektron
- **Akzeptor** : "Nimmt" Elektronen an; Erzeugt p-Typ
	  Bringt der Energieniveau des Bandstrukturs runter $\rightarrow$ freies Loch
Zusätzliche Energieniveaus in der Bandlücke (nahe des Band)
### Ionisationswahrsch.
### Entartung

## Transportmech.
