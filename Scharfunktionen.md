---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Zusammengesetzte Funktionen|Zurück]]

___
# Beispiel

>[!write] Aufgabe
>Gegeben ist die Funktionenschar $f_a$ mit 
>
>$\qquad \qquad \qquad f_a(x)=(x+a)\cdot e^{-x},\ a \in \mathbb{R}$.
>
>- Zeige, dass $F_a$ mit 
>  $\qquad \qquad \qquad F_a(x)=(-x-a-1)\cdot e^{-x}$
>  eine Stammfunktion von $f$ ist.
>- Der Graph von $f_a$ schließt für $x\ge 0$ mit der $x$-Achse ein nach rechts unbeschränktes Flächenstück ein.
>  Bestimme $a$ so, dass der Flächeninhalt dieses Stücks 2 FE beträgt.

<br>

>[!success]- Lösung
>![[Scharfunktionen#^4eadbf]]

<br>

___
# Annotation

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Leite $F_a$ mithilfe der Produktregel ab.<br>Beachte die Verkettung bei $e^{-x}$. | <br>$\begin{align*}F'_{\ a}(x)&= (-1)\cdot e^{-x}+(-x-a-1)\cdot e^{-x}\cdot (-1) \\ &= e^{-x} \cdot (x+a) \\ &= f_a(x)\end{align*}$<br><br>(gilt allgemein)<br>$\quad$ |
| <br>Berechne zunächst die Nullstelle mithilfe des Satzes vom Nullprodukt.<br><br>Berechne das bestimmte Integral zwischen der Nullstelle $-a$ und einem Wert $u> -a$.<br><br>Bestimme den Grenzwert für $u \rightarrow \infty$.<br><br>Ermittle anschließend $a$ so, dass der Grenzwert dem gewünschten Flächeninhalt entspricht. | <br>$f_a(x)=(x+a)\cdot e^{-x}=0  \qquad (e^{-x} \neq 0)$<br>Einzige Nullstelle bei $x=-a$.<br><br><br>$\displaystyle \begin{align*}\int_{-a}{u}f(x)\ dx&= [(-x-a-1)\cdot e^{-x}]_{-a}^{u} \\ &= (-u-a-1)\cdot e^{-u}-(-1)\cdot e^{a} \qquad \mid u \rightarrow \infty \\ \\ &= 0+1\cdot e^{a} \\ &= e^{a}\end{align*}$<br><br>$e^{a}=2$ für $a=ln(2)\approx 0.6931$<br>Der Flächeninhalt beträgt 2 FE für $a=ln(2)$. |

^4eadbf

