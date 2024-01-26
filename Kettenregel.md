#Regel  #TBD 

# Definition

>[!hint] Kettenregel
>Haben die Funktionen $u$ und $v$ die Ableitungen $u'$ und $v'$, dann hat die Verkettung $f$ mit 
>
>$\qquad \qquad f(x)=u(v(x))$ 
>
>die Ableitung 
>
>$f'(x)=u'(v(x))\cdot v'(x)$.
>
>Für verkettete Funktionen der Form $f(x)=e^{v(x)}$ gilt insbesondere:
>
>$\qquad \qquad f'(x)=e^{v(x)}\cdot v'(x)$

<br>

___
# Beispiel

>[!write] Aufgabe
>Berechne die Ableitung von $f$ mit 
>
>$\qquad \qquad f(x)=(x^{3}-9x)^{6}$ 

<br>

>[!success]- Lösung
>![[Kettenregel#^695b4e]]

<br>

___
# Annotation

| Vorgehen | Berechnung |
| --- | --- |
| <br>Der Term $(x^3-9x)^6$ ist eine Potenz von $\color{cyan}{x^{3}-9x}$.<br><br><br>Wähle die Funktion zu $\color{cyan}{x^{3}-9x}$ als innere Funktion $v$ und die Potenzfunktion als äußere Funktion $u$.<br><br>Bestimme ihre Ableitung und wende die Kettenregel an. | <br>${\color{cyan}{v(x)=x^{3}-9x}} \qquad \qquad u(x)=x^{6}$<br>$v'(x)=x^{3}-9x \qquad \qquad u'(x)=x^{6}$<br><br>$\begin{align*}f'(x)&= u'({\color{cyan}{v(x)}} \cdot v'(x) \\ \\ &= u'({\color{cyan}{x^{3}-9x}}) \cdot (3x^{2}-9) \\ \\ &=6({\color{cyan}{x^{3}-9x}})^5 \cdot (3x^{2}-9) \end{align*}$<br>$\quad$ |

^695b4e

