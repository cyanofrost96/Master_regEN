## [[pstricks]]
ist eine Package in Latex zum Erstellen von einfachen Diagramme/Koordinatensystem

beispiel Code:
````
\documentclass{standalone}

\usepackage{fontspec}
\usepackage{pstricks}
\usepackage{multido}
\usepackage{pstcol} % for colored lines (optional)

\begin{document}

\begin{pspicture}[showgrid=true](-1, -1)(3, 3)
    \psline[-](0,0)(2,2) % Draw the line from (0,0) to (2,2)
    \psset{linecolor=red} % Uncomment to set the line color to red (optional)
\end{pspicture}

\end{document}
````

Damit es überhaupt laufen kann, muss entweder die LuaLatex oder XeLatex als Compiler ausgewählt werden.