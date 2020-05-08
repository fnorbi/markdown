# Háromszög szerkesztés

A háromszög oldalai: $a, b, b$, tehát $s=b+\dfrac{a}{2}$, területe pedig Heron-képlettel:
$$ T = \sqrt{\left(b+\dfrac{a}{2}\right) \cdot\left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4} } = \dfrac{a}{2}\cdot \sqrt{b^2-\dfrac{a^2}{4}} $$

## I. eset: $m_b$ és $r$ adottak
$$
\begin{cases} \dfrac{b m_b}{2} = rs \\ rs= \sqrt{\left(b+\dfrac{a}{2}\right) \cdot\left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4} }  \end{cases}
$$A második egyenletet négyzetre emelve:
$$ r^2 \cdot \left(b+\dfrac{a}{2}\right)^2 = \left(b+\dfrac{a}{2}\right) \cdot\left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4}  $$ egyszerűsítve
$$ r^2 \cdot \left(b+\dfrac{a}{2}\right) = \left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4}  $$ Az első egyenletből pedig
$$ bm_b = r\cdot (2b+a) $$ adódik, ahonnan kifejezve $a$-t:
$$ a = \dfrac{bm_b-2rb}{r} $$ Világos tehát, hogy ha $b$ megszerkeszthető, akkor $a$ is (szerkeszthetőség és algebrai műveletek). Helyettesítve a másik egyenletbe
$$ r^2\cdot \left(b+\dfrac{bm_b-2rb}{2r}\right) = \left(b-\dfrac{bm_b-2rb}{2r}\right)\cdot \left(\dfrac{bm_b-2rb}{2r}\right)^2 $$ Egyszerűsítve $b$-vel:
$$ r^2\cdot \left(1+\dfrac{m_b-2r}{2r}\right) = \left(1-\dfrac{m_b-2r}{2r}\right)\cdot \left(\dfrac{bm_b-2rb}{2r}\right)^2  $$ egyenlet adódik, ami $b$-re másodfokú, tehát $b$ foka 1 vagy 2 lehet csak (mivel van olyan másodfokú polinom, amelynek gyöke). Ebből következően $b$ megszerkeszthető, tehát $a$ is, így a háromszög is.

## I. eset: $R$ és $r$ adottak
$$
\begin{cases} \dfrac{ab^2}{4R} = rs \\ \dfrac{ab^2}{4R}= \dfrac{a}{2}\cdot \sqrt{b^2-\dfrac{a^2}{4} }  \end{cases}
$$ Megint a második egyenlettel kezdve: egyszerűsítve $\dfrac{a}{2}$-vel és négyzetre emelve:
$$ \dfrac{b^4}{4R^2} = b^2-\dfrac{a^2}{4} $$ szorozva $4R^2$-tel:
$$b^4 = 4R^2b^2-R^2a^2 $$ Az első egyenletben szintén elvégezve beszorzást:
$$ ab^2 = 4Rr\cdot \left( b+\dfrac{a}{2} \right) = 4Rrb+2Rra $$ Vagyis az egyenletrendszer
$$
\begin{cases} ab^2 = 4Rrb+2Rra \\ b^4 = 4R^2b^2-R^2a^2  \end{cases}
$$ Az első egyenletből kifejezve $a$-t:
$$ a = \dfrac{4Rrb}{b^2-2Rr} $$ Megint csak jegyezzük meg, hogy ha azt kapnánk, hogy $b$ megszerkeszthető, akkor $a$ is az volna. Helyettesítve a másodikba
$$ b^4 = 4R^2b^2-R^2\cdot \left(\dfrac{4Rrb}{b^2-2Rr}\right)^2 $$ Beszorozva $(b^2-2Rr)^2$-nel:
$$ b^4 \cdot (b^2-2Rr)^2 = 4R^2b^2\cdot (b^2-2Rr)^2-16R^4r^2b^2 $$ Egyszerűsítve $b^2$-nel:
$$ b^2 \cdot (b^2-2Rr)^2 = 4R^2\cdot (b^2-2Rr)^2-16R^4r^2 $$ Kibontva a zárójeleket:
$$ b^2 \cdot (b^4 - 4Rrb^2 + 4R^2r^2) = 4R^2\cdot (b^4-4Rrb^2+4R^2r^2) - 16R^4r^2 $$ Vegyük észre, hogy jobboldalon beszorzás után a konstans kiesik, tehát megint egyszerűsíthetünk $b^2$-tel:
$$b^4 - 4Rrb^2+4R^2r^2=4R^2b^4-16R^3rb^2 $$ A kapott egyenlet $b$-ben negyedfokú, ami még jelenthetné azt, hogy $b$ foka $3$, viszont vegyük észre, hogy sem elsőfokú, sem harmadfokú tag nincs, tehát valójában ez az egyenlet $b^2$-ben másodfokú, tehát $b^2$ foka 1 vagy 2, azaz $b^2$ megszerkeszthető. Innen pedig a tanultak alapján $b$ is, tehát $a$ is, így a háromszög is.

## III. eset: $R$ és $m_b$ adottak
$$\begin{cases} \dfrac{ab^2}{4R} = \dfrac{bm_b}{2} \\ \dfrac{ab^2}{4R}= \dfrac{a}{2}\cdot \sqrt{b^2-\dfrac{a^2}{4} }  \end{cases}$$ A második egyenlet az előzőhöz hasonlóan
$$ b^4=4R^2b^2-R^2a^2 $$ alakban írható. Az első szintén picit rendezve: $ab^2 = 2Rbm_b$. Most csak speciális esettel foglalkozunk, azt fogjuk megmutatni, hogy $R=1$ és $m_b = 1$ esetén nem szerkeszthető meg a háromszög (meggondolndó, hogy ilyen háromszög valóban létezik, bár ez a bizonyítás során is könnyen látható lesz az egyik lépésben). Az egyenletrendszer $R=m_b=1$ esetén:
$$\begin{cases} ab^2 = 2b \\ b^4 = 4b^2-a^2  \end{cases}$$ Ekkor az első egyenletből kifejezve $a$-t:
$$ a= \dfrac{2}{b} $$ helyettesítve a másodikba
$$ b^4 = 4b^2 - \dfrac{4}{b^2} $$ azaz
$$ b^6-4b^4+4=0 $$ Ez $b$-ben hatodfokú, ez még nem mond számunkra eleget $b$ fokáról. Legyen $c=b^2$, ekkor
$$ c^3 - 4c^2 + 4 = 0 $$ Könnyen látható, hogy a kapott, $c$-ben harmadfokú egyenletnek nincs racionális gyöke. Ehhez racionális gyöktesztet kell végeznünk, a lehetséges jelöltek: $1, 2, 4$. Behelyettesítéssel látható, hogy gyik sem gyöke az $x^3-4x^2+4$ polinomnak, tehát mivel nincs racionális gyöke ennek a harmadfokú polinomnak, irreducibilis $\mathbb{Q}$ felett, így $\mathbb{Z}$ felett is. Ez viszont azt jelenti, hogy mivel $c$ gyöke neki, és irreducibilis a polinom, így ez $c$ minimálpolinomja, azaz $c$ foka 3.

És kész is vagyunk, hiszen ekkor $b$ foka nem lehet 

##  Egyéb eset:
Mivel az $\{R,r,m_b\}$ halmaznak 8 részhalmaza van, még további 5 esetről nyilatkozni kell. Nyilvánvaló, hogy ha egyik adat sem adott (üres halmaz), akkor nem lehet megszerkeszteni a háromszöget. Hasonlóan nyilvánvaló, hogy ha már $r$ és $m_b$ is elegendőek voltak a szerkesztéshez, akkor az is jó, ha mindhárom adat rendelkezésünkre áll. A maradék három eset sem izgalmas: egyetlen adat a három közül nem határozza meg egyértelműen a háromszöget, így tehát az nem szerkeszthető meg.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI4NzA4NjkwOCwtNzk4MjUwNzAyLC0xOD
kwMDM0MTEsLTI0MDIzODI3NCw3MzA5OTgxMTZdfQ==
-->