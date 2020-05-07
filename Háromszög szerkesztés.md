# Háromszög szerkesztés

A háromszög oldalai: $a, b, b$, tehát $s=b+\dfrac{a}{2}$, területe pedig Heron-képlettel:
$$ T = \sqrt{\left(b+\dfrac{a}{2}\right) \cdot\left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4} } = \dfrac{a}{2}\cdot \sqrt{b^2-\dfrac{a^2}{4}} $$

## I. eset: $m_b$ és $r$ adottak
$$
\begin{cases} \dfrac{b m_b}{2} = rs \\ rs= \sqrt{\left(b+\dfrac{a}{2}\right) \cdot\left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4} }  \end{cases}
$$
A második egyenletet négyzetre emelve:
$$ r^2 \cdot \left(b+\dfrac{a}{2}\right)^2 = \left(b+\dfrac{a}{2}\right) \cdot\left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4}  $$ egyszerűsítve
$$ r^2 \cdot \left(b+\dfrac{a}{2}\right) = \left(b-\dfrac{a}{2}\right)\cdot \dfrac{a^2}{4}  $$ Az első egyenletből pedig
$$ bm_b = r\cdot (2b+a) $$ adódik, ahonnan kifejezve $a$-t:
$$ a = \dfrac{bm_b-2rb}{r} $$ Világos tehát, hogy ha $b$ megszerkeszthető, akkor $a$ is (szerkeszthetőség és algebrai műveletek).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIyMDY5ODU0NSw3MzA5OTgxMTZdfQ==
-->