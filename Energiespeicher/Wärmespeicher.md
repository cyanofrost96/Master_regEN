## Sensible WS
bsp: siehe Folie (entwickelt; Stand 2018. typischer Wert: 10MWh; 0,6kWh/m2.K; Medium: Thermoöl)

### Fluidenspeicher
Es gibt außer Wasserkollektoren auch Luftkollektoren in der Form von funktionierender Halle

### Zusammenhang zw. Kosten, Kapa., und Schüttdichte
Wegen der höhen Kosten des Thermoöls werden in dem Speicher auch günstige Feststoffe als Kostenminderung reingeschüttet. Das Verhältnis zwischen den beiden Stoffen verändert die Gesamtkosten und die Speicherdichte.

Spezifische Kosten: $$K_{kosten} = \psi \cdot K_{V,s} + (1-\psi_s) \cdot K_{V,Öl}$$
Speicherkapazität: $$K_Q = c_{p,s} \cdot \rho_s \cdot \psi_s + c_{p,Öl} \cdot \rho_{Öl} \cdot (1-\psi_s)$$
*ist einfach eine lineare Gleichung von 0 bis 100% mit die jeweilige Vergleichspreis sowie -kapa berechnet*

### Erdsondenspeicher
tonreichhaltige Boden kann mit U-formiges Rohr senkrecht eingesteckt (erstmal gebohrt)und genutzt als WS bzw. KS. Als Medium wird Betonit-Sand-Zementmischung verwendet, wobei für die Wärmeträger entweder Wasser oder Öl.

### weitere sensible WS in Entwicklung
eutektische Salzmischungen als Speichermedium

## PCM Speicher
*eng.: Phase Changing Material*
Diese Speicherart nutzt die Phasenübergangsenthalpie eines Materials als Speicher aus.

bsp.: Heißwasser- und Dampfspeicher (mit Gleichdruckspeicher); für die kurzfristige Erhöhung des Dampfmassenstromes eines Kreislaufes verwendet

Eisspeicher bzw. Slurries als Kältespeicher.

## Warmwasserkollektor
- Schwimmbadkollektor : hat anfänglich kein Verlust (da die Strahlung direkt in das Medium gelangen)
- Flachkollektor: fängt mit 80% Effizienz wegen optische Verlust (Glas) und sinkt quadratisch je nach Wärmedämmung des Kollektors. 
	- Eher für Trinkwasser
- Vakuumrohren: verhält wie Flachkollektor aber hat flacheres Absinken wegen geringer Verlust höhere Temperaturdifferenz durch Vakuumdämmung
	- kann auch für Heizung verwendet werden

Ziel von dem Simulationslabor : Wärmeverbrauch in Sommermonaten nur mit EE bereitstellen.
Stillstand / Stagnation: wenn der Speicher voll ist; Folge: Wasser im Tank kann verdampfen und Überdruck wird dann entstehen.

ST-Regler soll so ausgelegt werden: 
- Temperatur von dem Kollektor und Speicher messen
- Nur einschalten wenn $\ce{T_K > T_S}$ , sonst ausschalten (auch bei zu höhen Speichertemp.)

Low-Flow: <25 m³/h für geringe Verwirbelung. Schichtenspeicher möglich! Dadurch kann der beste Rücklauf für den besten Wirkungsgrad ausgesucht.