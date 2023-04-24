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