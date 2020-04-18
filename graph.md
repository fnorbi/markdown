# Gráfok
```latex {cmd=true hide=true}
\documentclass{standalone}
\usepackage{tikz}
\usetikzlibrary{matrix}
\begin{document}
\begin{tikzpicture}
  \matrix (m) [matrix of math nodes,row sep=3em,column sep=4em,minimum width=2em]
  {
     F & B \\
      & A \\};
  \path[-stealth]
    (m-1-1) edge node [above] {$\beta$} (m-1-2)
    (m-1-2) edge node [right] {$\rho$} (m-2-2)
    (m-1-1) edge node [left] {$\alpha$} (m-2-2);
\end{tikzpicture}
\end{document}
```

```latex {cmd=true hide=true}
\begin{tikzpicture}
  \SetGraphUnit{5}
  \Vertex{B}
  \WE(B){A}
  \EA(B){C}
  \Edge[label = 1](A)(B)
  \Edge[label = 2](B)(C)
  \Edge[label = 3](C)(B)
  \Edge[label = 4](B)(A)
  \Loop[dist = 4cm, dir = NO, label = 5](A.west)
  \Loop[dist = 4cm, dir = SO, label = 6](C.east)
  \tikzset{EdgeStyle/.append style = {bend left = 50}}
  \Edge[label = 7](A)(C)
  \Edge[label = 8](C)(A)
\end{tikzpicture}

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMjg4ODY1MzgsLTIwOTQxOTIwNzksNz
MwOTk4MTE2XX0=
-->