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

**Stromdichte im Echten**
$$j = j_0 \cdot (\ce{exp}(\frac{U}{m \cdot U_T})-1)$$
m ist das Idealitätsfaktor; 1 = ideal, 1..2 = real

**Temperaturabhägigkeit**

## Solarzelle
Ist ein pn-Übergang mit Kontakten (d.h. die Elektronen wird nicht gesättigt)
Kennlinie einer SZ:
$$j = j_k-j_0(\ce{exp}(\frac{u}{u_T}-1))$$
**Kurzschlussstrom**: 
$j_k$ : Kurzschlussstromdichte, ist proportional zur Bestrahlungsstärke
Strom ist von folgenden Parametern abhängig:
- Temperatur
- Absorptionskoeffizient
- Bandlücke
- Rekombinationsrate
- Spektraleempfindlichkeit

**Leerlaufsspannung**: $j=0$
$$U_{(j=0)} = V_{oc} = U_T \cdot \ce{ln}(\frac{j_k}{j_0})$$
Bei reale Solarzelle noch mit $m$ (Idealitätsfaktor) multiplizieren 

$V_{oc}$ ist von folgenden Parametern abhängig: 
- $I_{sc}$ : proportional
- $E$ ; proportional
- Bandlücke ; größere Lücke -> höhere Spannung 
- Dotierung ; verändert die Fermi-Energie, höhere Dotierung -> größere Bandverbiegung
- Temperatur

Höhe Leerlaufsspannung erfördert kleines $j_0$

### Leistung

### Fullfaktor

$$FF = \frac{j_{mpp} \cdot U_{mpp}}{j_{sc} \cdot U{oc}}$$
### Wirkungsgrad
Stellt dar, wie viel Sonnenlicht in elektrische Energie umgewandelt wird.
$$\eta = \frac{P_mpp}{E \cdot A}$$
Der ist von spektrale Empfindlichkeit des Materials abhängig

### Externe Quantenausbeute
Zeigt, wie viel (prozentual) Elektron mit dem bestimmten spektral eines Lichtes angeregt werden.
Licht mit höher und niedriger Frequenz werden rausgefiltert, da sie entweder nur an der Oberfläche anregt (und dann schnell wieder rekombinieren), oder geht zu tief rein (rotes Licht), und werden nicht mehr absorbiert.

Verbesserungen an Rekombination an der Oberfläche kann man mit a-si passivierung machen.

### Einfluss der Grenzflächen
**Sammelwahrscheinlichkeit**: 
Mit welchem Wahrscheinlichkeit werden Ladungsträger an den Kontakten eingesammelt?
Transport zum pn-übergang, Trennung an pn-übergang, Transport zum Kontakten
Diffusionslänge bzw. Lebensdauer, Geschwindigkeit der Rekombination an der Grenzfläche.

Bei kürzerer Diffusionslänge bringen die Grenzfläche kein Einfluss, nur bei längeren. Der Einfluss ist -> höherer Rekombinationsgeschwindigkeit an der Oberfläche.

Passivierung, chemisch: mit $\ce{SiO_2}$, $\ce{Si_2N_4}$, oder a-Si
Feldpassivierung: Back Surface Field

Solarzelle mit Al-BSF: 
Al schicht an der Rückseite + Kontaktfeuern : Al atomen diffundieren in die Solarzelle rein, erzeugt ein hochdotiertes p-Schicht. Dieser Schicht verhindert dass Elektronen an p-Seite zurück fließen.

An der Vorderseite diffundieren die Ag-Kontaktfingern durch ARC und die n-Schicht, welche einen hochdotierten n-''Punkten'' in der n-Schicht bilden.

PERC (passivated emitter and rear contact)
Anstatt ein Al-blech, hat man hier punktformig die Al in die p-Schicht angebracht, welche auch punktformige p+-Dotierung erzeugt.