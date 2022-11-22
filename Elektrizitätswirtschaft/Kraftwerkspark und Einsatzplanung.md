## Ressourcen und Reserven
Reserve < Resource. 
Reserven sind Stoffe die derzeit wirtschaftlich gewinnbar und sicher bis zu wahrscheinlich zu finden sind
Ressource beinhaltet die spekulative und hypothetische Rohstoff-vorkommen.
- Intraday:
- Day-Ahead: 

Kraftwerkauslastung bei unterschiedlichen Preisniveaus
Atomkraftwerke und BraunkohleKW werden fast nie unter 50% geregelt, sogar ausgeschaltet.
AKW arbeitet unter bestimmten Leistungsbändern
Gas und Steinkohle sind gut regelbar und arbeitet immer ab 10% bis zu 80% des maximalen Last.

Leistungsgradient: Wie schnell ein KW die Leistung geregelt werden kann. Gas: 12%/min, Atom: 3-5%/min, Kohle: 4%/min

## Kraftwerkskosten
LCOE und Grenzkosten

### Investitionsberechnung
- Kapitalwertmethode: Gesamteinnahmen und -ausgaben eines Zeitraumes; Auf- und Abzinsung mtieinkalkuliert.
- Annuitätsmethode:
- Zinssatz:
	Preis für geliehenes oder investiertes Kapital
	- Normaler Zinssatz: $i_n$ = Inflation + Rendite + Risikozuschlag
	- Realer Zinssatz: $$i_r = \frac{1+i_n}{1+\ce{inflationsrate}} - 1$$
	- Mittelwerte Renditen wird je nach Regionen abgeschätzt (Tabelle siehe Folien)
	WACC (Weighted Average Cost of Capital)
	$$\ce{WACC}=\frac{E}{G} \cdot i_{EK} + \frac{F}{G} \cdot i_{FK} \cdot (1-s)$$

## Komplexität
Geld und Energiefluss in einem Bilanzkreis

BKV: Bilanzkreisverantwortlicher: müssen Leistung liefern, Last prognosieren, Energie kaufen und verkaufen
Zuständig für ausgeglichene Bilanz zw. Einspeisung und Entnahme, verglichen jede 15 mins. Das Ausgleichen bezieht sich den Strom aus Regelkraftwerken

## Netzbetriebmodi
Überwacher eines Übertragungnetzes

## Diskussion
Anforderungen für SDL bis 2030: EE sollen spannungseinprägend anstatt stromeinprägend arbeiten. Dadurch kann EE auch schwarzstartfähig sein.

Stromteilen sollen für die Energy-shifting und Regelleistung besser ausgestattet werden.

## Regelstatik
$K$: Leistungskennzahl beschreibt wie viele Leistung muss "getätigt" werden von einem KW bei einer Frequenzänderung. Die Steigung $K$ dieser Kennlinie hängt von der Große des KWs und die vereinbarten Steueranteil des KWs (sog. $S$ Droop) Dieser Vorgang heißt auch Primärregelung.

$$K = \frac{\Delta P}{\Delta f} = \frac{P_N}{\Delta f_N}$$
$$S = \frac{\Delta f_N}{f_N}$$

Parallelbetrieb:
Wenn mehrere KWs in einem Strang betrieben werden, dann soll verschiedene Kraftlinie je nach KW-Leistung angepasst gefahren werden ([[Primärregelung]]). Nach bestimmter Zeit wird die Kennlinie des kräftigen KWs nach oben verschoben und die schwächere entlastet ([[Sekundärregelung]]).

Flachere $K$ trägt mehr Leistung zur Freq.stabilität bei (Spitzenlast).

