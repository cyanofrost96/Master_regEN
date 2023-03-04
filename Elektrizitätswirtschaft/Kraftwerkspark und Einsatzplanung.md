## Nomenklatur Energie
deutscher Primärenergieverbrauch: bleibt sein 1990 bei 14905 PJ (4140 TWh) soll bis 2030 auf 10066 PJ sowie in 2050 auf 7190 PJ reduziert.

## Ressourcen und Reserven
Reserve < Resource. 
Reserven sind Stoffe die derzeit wirtschaftlich gewinnbar und sicher bis zu wahrscheinlich zu finden sind
Ressource beinhaltet die spekulative und hypothetische Rohstoff-vorkommen.
- Intraday:
- Day-Ahead: 

Kraftwerkauslastung bei unterschiedlichen Preisniveaus
Atomkraftwerke und BraunkohleKW arbeiten fast nie unter 50% (sondern immer über 50%), entweder so oder ausgeschaltet.
AKW arbeitet unter bestimmten Leistungsbändern (aufgrund seiner Trägheit beim regeln)
Gas und Steinkohle sind gut regelbar und arbeitet immer ab 10% bis zu 80% des maximalen Last.

Leistungsgradient: Wie schnell ein KW die Leistung geregelt werden kann. Gas: 12%/min, Atom: 3-5%/min, Kohle: 4%/min

## Verfügbarkeit von Kraftwerken
- Arbeitsverfügbarkeit: Bezieht sich auf dessen technischen Gründen und der betrieblichen Zustand (reduziert durch Wartung, u.a)
- Zeitverfügbarkeit: Maß für die zeitliche Einsatzfähigkeit (reduziert durch Regelung und Bereitschaft)

## Einsatzbereiche von KW
- Grundlast: mehr als 4000 h/a
- Mittellast: zw. 1500 bis 4000 h/a
- Spitzenlast: unter 1500 h/a
Sie werden von der; Alter der Anlage, Wärmeauskopplung, Preise, Wartungsarbeit und -aufwand und Folgekosten beeinflusst.

## Kraftwerkskosten
- Gestehung: abhängig von der Anlagentyp
- Investor und Betreiber: Qualität, Wartung und Finanzierung
- Äußere Bedingungen: Liberalisierung, Geopolitik, Umwelt und Steuerliche Gesetz, Akzeptanz, Wettbewerb, Standort und Bedarf

**LCOE** und Grenzkosten
$$LCOE=\frac{I_0+\Sigma^n_{t=1}\frac{A_t}{(1+i)^t}}{\Sigma^n_{t=1}\frac{M_t}{(1+i)^t}}$$
Startup Investments + jährliche laufende kosten durch die jährliche erzeugte Energiemenge (alles bezüglich der Verzinsung / Inflation)
- **LCOE** : dient als einen Vergleich von Erzeugertechologien ohne Berücksichtigung auf der Verbrauchszeitpunkt / Bereitstellung
- **Grenzkosten** : Vergleich aufm kurzfristigen Einsatz des Kraftwerkes

## Investitionsberechnung
- Kapitalwertmethode : Gesamteinnahmen und -ausgaben eines Zeitraumes; Auf- und Abzinsung miteinkalkuliert.
  $$I_x=I_0 \cdot (1+i)^{-1}$$
  wobei $I_x$ : der tatsächliche Geldwert im x-te Folgejahr.
- Annuitätsmethode : Die Folge variabler Ausgaben wird jährlich umgerechnet innerhalb eines Betrachtungszeitraumes
- Zinssatz :
	Preis für geliehenes oder investiertes Kapital
	- Normaler Zinssatz: $i_n$ = Inflation + Rendite + Risikozuschlag
	- Realer Zinssatz: $$i_r = \frac{1+i_n}{1+\ce{inflationsrate}} - 1$$
	- Mittelwerte Renditen wird je nach Regionen abgeschätzt (Tabelle siehe Folien)
	WACC (Weighted Average Cost of Capital) : Mischzins aus Eigen- und Fremdkapital
	$$\ce{WACC}=\frac{E}{G} \cdot i_{EK} + \frac{F}{G} \cdot i_{FK} \cdot (1-s)$$
## Kraftwerkeinsatz
- Dispatch: Planung des KWeinsatzes, sowie des kostenoptimierten Fahrplans (zeitlich und regional, welche ein- bzw. ausgefahren müssen)
- Redispatch: Engpassmanagement, kurzfristige Fahrplananpassung von mehreren KWen. Hier müssen die Übertragungskapa., An- und Ausfahrtrampen, Stillstandzeiten, Mindestleistungsgrenzen, Teillastverhalten, Wartungszeiten u. a. betriebliche Einschränkungen

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

totale Leistungszahl $K_E = 1/K$, in Sommer beträgt diese 16 GW/Hz und Winter 18 GW/Hz

Kosteneinschätzung eines Akku-betriebene RegelKW:
10MW; 10MWh (5 mio. + 500k€  Umrichter) = 5,5 mio€
mit Ladezyklen von 3k VLZ = 30 GWh Energie sind bereitgestellt.

Kosten: 0,183 €/kWh (ohne Selbstälterung mitberechnet) vergl. 3-6ct/kW/h

Einteilung $\ce{P_{Regel}}$ und Bereitstellung: neg. (-) : mehr Last, geringer Erzeugung; pos.(+): andersrum.

Last wird unter 47,5 Hz von KWs getrennt, damit es nicht zum Schwarzstart gegangen ist.

Residuallast: min. Leistungsbedarf - EE

Versorgungsqualität
SAIDI - Nichtverfügbarkeit / min
SAIFI - Häufigkeit der Unterbrechungen / min
CAIDI - 

Anreizregulierung: Maß für das Geld was der Erzeuger bekommt