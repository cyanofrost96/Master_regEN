## Stationäre GLS
Nullstelle-n in einer Funktion f(x) suchen:
- Aussuchen zweier x-Werten wobei die y-Werten einmal negativ und positiv bilden. Dazwischen muss die Funktion durch den Nullpunkt gehen. Iteration: Teilen der Intervalle bis die Nullpunkt ungefähr gefunden ist.

## Newton Verfahren für skalare GL
Eine Iteration um eine Nullstelle einer Funktion zu "schätzen"
- Anstatt die richtigen Nullstelle zu finden, kann man auch den Anstieg an dem "Angriffspunkt" lösen und deren Nullstelle zu finden. Der x-Wert dieser Nullstelle wird nochmal in der ersten Ableitung gerechnet und deren Nullstelle gesucht. Diese ist wiederzuholen bis die Nullstelle ungefähr gefunden ist.
Die Iterationsfunktion :
$$x = x_0 - \frac{f(x_0)}{f'(x_0)}$$
### Konvergenz Newton Verfahren
Probleme :
- x_Schätz muss ziemlich nah genug an der Nullstelle.
- wenn der Anstieg an irgendeinem untersuchtem Bereich = 0 ist, dann funktioniert das Verfahren nicht mehr.
- kann dummerweise in eine Schleife geraten.
- kann stattdessen in die andere Richtung gehen.

## Mehrdimensionale DGL
*partielle Ableitungen, Jacobi-Matrix, Linearisierung*
reellwertige mehrvariablen Funktion
$$ f(x_1,x_2,..,x_n) = \begin{bmatrix} x_1 \cr x_2 \cr .. \cr x_n\end{bmatrix}$$
### Partielle Ableitung
Anstieg einer mehrdimensionalen Funktion bezüglich der Achse mit dem es abgeleitet wird. D.h.: wenn nach x abgeleitet wird, zeigt die Ableitungsfunktion die Steigung basiert auf einem Schnitt entlang der x-Achse.

### Jacobi-Matrix
$$Df|_x = \begin{bmatrix} \end{bmatrix}, \quad \triangledown f = \begin{bmatrix} \frac{df}{dx_1}|_x \\ \frac{df}{dx_2}|_x \\ .. \\ \frac{df}{dx_n}|_x\end{bmatrix}$$
### Tangentialebene
$$T(x,y)=f(x_0,y_0)$$
$$t(x) = f(x_0)+\frac{df}{dx}|_x \cdot(x-x_0)$$

## Newton Verfahren für GLS
