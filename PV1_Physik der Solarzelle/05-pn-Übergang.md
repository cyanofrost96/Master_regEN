# [pn-Übergang](https://smile.hsu-hh.de/Auswahl.html?1) 
stationären Zustand an der Kontaktfläche zw. negativ und positiv dotierten Kristall.
Wegen Dichteunterschied diffundieren Elektronen aus der n-Seite auf der p-Seite, welche dadurch einen elektrischen Feld bilden sog. Raumladungszone RLZ (da jetzt die p-Seite negativ geladen ist und die n-Seite positiv).
- Ladungsaustausch durch Diffusion
- Ausbildung der Raumladungszone
- Bandstruktur: Fermi-level der p-Seite liegt nah oberhalb des Valenzbandes und von der n-Seite nah unterhalb des Leitungsbandes
![[Drawing 2022-06-10 10.50.22.excalidraw|600]]
Diffusionsstrom und Driftsstorm suchen immer nach Gleichgewicht
Breite der RLZ : w; Bandverbiegung -> Diffusionsspannung : $\ce{U_d}$ 
$$U_d = U_T \cdot ln(\frac{N_A \cdot N_D}{n_i^2})$$
$$U_T = \frac{k}{e} \cdot T$$
im nichtentarteten Halbleiter: $eU_d$ < $E_g$ (Bandverbiegung soll kleiner als Bandlücke)
mit steigendem Temperatur sollte die Diffusionsspannung steigen, aber da die intrinsische Ladungsträger auch steigt (sogar quadratisch), sinkt doch die $U_d$
[[../Begriffe/Intrinsische Ladungsträger]] :
$$n_i = \sqrt{N_c \cdot N_v \cdot \ce{exp}(-\frac{E_g}{k \cdot T})}$$
Breite der RLZ:
$$w = \sqrt{\frac{2 \cdot E_c \cdot E_v}{e}\cdot U_D(\frac{1}{N_A}+\frac{1}{N_D})}$$
unter normalen Zustand ist RLZ viel kürzer als Diffusionslänge ($L_D$) -> bei Rekombination und Generation wird RLZ vernachlässigt.

### pn Übergang mit Vorspannung (Diodenverhalten)
Bezeichnungen: 
- **U < 0** : 
  Sperrrichtung (p-Seite wird negativ geladen und n-Seite positiv). Bandverbiegung wird vergrößert. RLZ wird dicker. Dadurch gibt's weniger Diffusionsstrom aber die Minorität kann über den Übergang rückwärts "fallen", unabhängig von U
- **U > 0** : 
  Durchlassrichtung (andersrum wie Sperrrichtung). Bandverbiegung wird verringert. RLZ wird schmaler. Dadurch passiert eher Diffusionsstrom des Majoritätsladung und exponentielle Zunahme des Diffusionsstromes mit steigender U

**Stromdichte** 
$$j = \frac{I}{A} = j_0 \cdot (exp(\frac{U}{U_T})-1)$$
$$j_0 = e \cdot (\frac{D_N}{L_n \cdot N_A}+\frac{D_P}{L_p \cdot N_D}) \cdot n_i^2$$
$j_0$ ist von der Materialeigenschaften ($L_n, L_p$), Dotierkonzentration($N_A, N_D$) und Temperatur($n_i^2$) 

### Abweichung von idealen Verhalten
höhere Sperrspannung verbreitet die RLZ, Generation von Elektron-Loch-Paare wird nicht vernachlässigbar 

#### Stromdichte im Echten
$$j = j_0 \cdot (\ce{exp}(\frac{U}{m \cdot U_T})-1)$$
m ist das Idealitätsfaktor; 1 = ideal, 1 .. 2 = real

#### Temperaturabhängigkeit der IU-Kennlinie
in Sperrrichtung: $j_0 \equiv n_i^2$, wobei $n_i \equiv T^{3/2} \cdot \ce{exp}(-\frac{E_g}{2kT})$
Anstieg von 6K führt zu Verdopplung von $j_0$
$$j = j_0 \cdot (\ce{exp}(\frac{U}{U_T})-1)-j_L$$
#### Photospannung
- ohne Beleuchtung: 
	