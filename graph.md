# Gráfok
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
eyJoaXN0b3J5IjpbLTkwNDkxNjQyOCwtMjA5NDE5MjA3OSw3Mz
A5OTgxMTZdfQ==
-->