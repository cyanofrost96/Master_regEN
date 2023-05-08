Diskretisierung: lineare Annäherung aus mehreren Punkten für eine Funktion.

Falldiskusion: Saitenschwingung
![](NUS_DGL01.excalidraw)
Bedingung zum Erfüllen der DGL:
$x_i, i=0, .., 8 ; y_0=0 , y_8=0$
Annähern einer Funktion stückweise nach einem Parabel
$$c^2 \cdot y'' = -\frac{1}{\mu}f(x_i)$$ 
$$y''(x_i) = \frac{p(x_{i-1})-2p(x_i)+p(x_{i+1})}{h^2}=\frac{y_{i-1}-2y_i-y_{i+1}}{h^2}$$

es gibt von daher 7 unbekannte (insg. 9 plus die Bekannte y_0 und y_8)
wird dann in Matrizen umgewandelt

### Lineare Gleichungssystem
$$\begin{bmatrix}
	\frac{-2c^2}{h^2}&\frac{c^2}{h^2}&0&...&0\cr
	\frac{c^2}{h^2}&\frac{-2c^2}{h^2}&\frac{c^2}{h^2}&...&0\cr
	&&...\cr
	0&...&\frac{c^2}{h^2}&\frac{-2c^2}{h^2}&\frac{c^2}{h^2}\cr
	0&...&0&\frac{c^2}{h^2}&\frac{-2c^2}{h^2}
\end{bmatrix} \cdot
\begin{bmatrix}
	y_1\cr y_2\cr y_3\cr ...\cr y_7
\end{bmatrix} =
\begin{bmatrix}
	\frac{-f_1}{\mu}\cr \frac{-f_2}{\mu}\cr \frac{-f_3}{\mu}\cr ...\cr \frac{-f_7}{\mu}\cr 
\end{bmatrix}$$
in der Gleichung einsetzen und n bis i nachrechnen:
$$\frac{c^2}{h^2} \begin{bmatrix}
	-2&1&0&...&0\cr
	1&-2&1&...&0\cr
	&&...\cr
	0&...&1&-2&1\cr
	0&...&0&1&-2
\end{bmatrix} \cdot
\begin{bmatrix}
	y_1\cr y_2\cr ...\cr y_{n-2}\cr y_{n-1}
\end{bmatrix} = -\frac{1}{\mu}
\begin{bmatrix}
	f_1\cr f_2\cr ...\cr f_{n-2}\cr f_{n-1}\cr 
\end{bmatrix}$$
Es gibt leider Speicherprobleme wenn man so speichert (überall 0-Werten außer die mittlere Diagonale)
tipp: nur die Hauptdiagonale mit der obere- sowie die untere- speichern (Tridiagonalmatrix)

## LR - Zerlegung
Umformatierung bzw. Spalten einer Matrix A in L (links-dreieck) und R (rechts-dreieck) mittels Gaußmatrix P (?).
