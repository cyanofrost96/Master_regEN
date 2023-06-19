### Skalare Anfangswertproblem
Zeitliche Rahmen wird jetzt zu betrachten; hier wird erst die Anfangszustand nach Zeit aufzupassen.
$$\begin{bmatrix}

\end{bmatrix}$$
$$\ddot{\ce{y}} = c^2 D \:\ce{y} + \frac{1}{µ}\:\ce{f}$$
Richtungsfeld
Algol: Für bestimmte Rahmen (x / t) in bestimmte Schrittlänge die Richtungsfeldfunktion berechnen und die Funktion "folgen". Wenn die Zeitschritte zu groß ist, dann könnte die Funktion zwischen der Konvergenzlinie pendeln.
$$\ce{y}'(t) = \ce{f}(t,\ce{y}(t))$$
$t_0 : y_0 = 1$
$t_1 : y_1 = y_0 + m \cdot \Delta t$
$\quad \; \; y_1 = y_0 + f(t_0, y_0) \cdot h$ 
die Iteration führt zu einer Funktion :
$$y_{i+1} = y_i + h \cdot f(t_i,y_i)$$
