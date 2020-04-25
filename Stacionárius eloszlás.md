### Stacionárius eloszlás

A lánc irrecubilis, pozitív rekurrens, ezért egyértelműen létezik stacionárius eloszlása. A gráf véges, egyszerű, összefüggő, és mivel az átmenetvalószínűségek azonosak, tekinthető irányítatlannak.

Ekkor a 2. feladat alapján: $\pi_i = \frac{d_i}{D}$. A gráf $2$-reguláris, vagyis $\forall d_i = 2$, ezért 
$$D = \sum\limits_{n=1}^8 d_i = 8\cdot 2 = 16. $$ Vagyis $\forall \pi_i = \frac{2}{16} = \frac{1}{8}$. A stacionárius eloszlás 
$$\pi = \left(\dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}, \dfrac{1}{8}\right).$$

### Átlagos visszatérési idő

Tétel volt előadáson, hogy ha a lánc irreducibilis, pozitív rekurrens, akkor 
$$\pi_i = \frac{1}{m_i} \hspace{1cm} \Rightarrow  \hspace{1cm}  m_1 = \dfrac{1}{\pi_1} = \dfrac{1}{\frac{1}{8}} = 8.$$ Várhatóan 8 lépés alatt fog visszatérni a kiindulási helyre, ha a bal felső sarokból indul.

### Határeloszlás

Kérdés: $\lim\limits_{n\to \infty} p_i^{(n)}$ létezik-e, és függ-e a kezdeti eloszlástól?

Mivel a lánc pozitív rekurrens, de nem aperiodikus, ezért **szerintem** nem létezik határeloszlás.

Precízebben: ???
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMDQ2MDI0NzYsMjc1MDg3NDYzLC03MT
k4MTE3MDksOTExMTg1MDc1LC0xODI1MjI0MDcyLDM2MDIwOTQ0
Nyw3MzA5OTgxMTZdfQ==
-->