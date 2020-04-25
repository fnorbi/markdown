# 1. feladat



### Stacionárius eloszlás

A lánc irrecubilis, pozitív rekurrens, ezért egyértelműen létezik stacionárius eloszlása. A gráf véges, egyszerű, összefüggő, és mivel az átmenetvalószínűségek azonosak, tekinthető irányítatlannak.

Ekkor a 2. feladat alapján: $\mu_i = \frac{d_i}{D}$. A gráf $2$-reguláris, vagyis $\forall d_i = 2$, ezért 
$$D = \sum\limits_{n=1}^8 d_i = 8\cdot 2 = 16. $$ Vagyis $\forall \mu_i = \frac{2}{16} = \frac{1}{8}$. A stacionárius eloszlás 
$$\mu = \left(\dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}\right).$$

### Átlagos visszatérési idő

Tétel volt előadáson, hogy ha a lánc irreducibilis, pozitív rekurrens, akkor 
$$\mu_i = \pi_i = \frac{1}{m_i} \hspace{1cm} \Rightarrow  \hspace{1cm}  m_1 = \dfrac{1}{\mu_1} = \dfrac{1}{\frac{1}{8}} = 8.$$ Várhatóan 8 lépés alatt fog visszatérni a kiindulási helyre, ha a bal felső sarokból indul.

### Határeloszlás

Kérdés: $\lim\limits_{n\to \infty} p_i^{(n)}$ létezik-e, és függ-e a kezdeti eloszlástól?

Mivel a lánc pozitív rekurrens, de nem aperiodikus, ezért nem létezik határeloszlás.

**Precízebben**:

Tekintsük a $p_i^{(n)}$ sorozat $p_i^{(2n)}$ és $p_i^{(2n+1)}$ részsorozatát. Bármely $i$ esetén minden $n$-re $p_i^{(2n)}=0$ vagy $p_i^{(2n+1)}=0$ teljesül.^[Hiszen bárhonnan is indult a lánc, minden $i$ állapotba vagy csak páros, vagy csak páratlan sok lépés után kerülhet.]

Vagyis a $p_i^{(n)}$ sorozatnak van olyan részsorozata, ami konstans $0$, annak persze határértéke is $0$. Ha tehát $\exists \lim\limits_{n\to \infty} p_i^{(n)} = q_i$, akkor $q_i = 0$ teljesül $\forall i$-re. Ezért ha létezik határeloszlás, akkor az csakis a $q=(0,0,0,0,0,0,0,0)$ lehet. Ez viszont nem eloszlás, tehát azt kaptuk, hogy nem létezik határeloszlás.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMwNjMxMDg0MSw2NjY4ODQxMjUsMjAwOD
I2MDA4MSw3MTY1MDgzMzMsLTIzMTU2MTA4MywtNzQ5NDE0NjI4
LC0xMzA0NjAyNDc2LDI3NTA4NzQ2MywtNzE5ODExNzA5LDkxMT
E4NTA3NSwtMTgyNTIyNDA3MiwzNjAyMDk0NDcsNzMwOTk4MTE2
XX0=
-->