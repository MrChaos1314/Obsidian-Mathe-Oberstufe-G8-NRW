#GK #Unterthema 

# [[Analytische Geometrie|Zurück]]

___
# Übersicht

>[!hint] Übersicht
>Wenn zwei Ebenen sich schneiden, so entsteht eine Schnittgerade.
>Die Schnittbedingung hat nie eine eindeutige Lösung.
>Zur Lageuntersuchung werden Normalenvektoren verglichen und gemeinsame Punkte bestimmt.
>Ein gemeinsamer Punkt muss beide Ebenengleichungen erfüllen.
>
>>[!info] Graphische Zusammenfassung
>>![[Pasted image 20240102171430.png]]

<br>

___
# Beide Ebenen in Koordinatenform

>[!write] Beide Ebenen in Koordinatenform
> Ermittle die gegenseitige Lage von 
> $\qquad \qquad E_{1}:-2x_{1}+x_{2}-5x_{3}=15$
> und 
> $\qquad \qquad E_{2}$.
> 
> - $E_{2}: 3x_1+7x_{2}-x_{3}=37$
> - $E_{2}: -6x_1+3x_{2}-15x_{3}=45$
> - $E_{2}: 4x_1-2x_{2}+10x_{3}=7$

<br>

>[!success]- Lösung
>![[Lagebeziehung von Ebenen#^473f36]]

<br>

___
# Eine Ebene in Parameterform, die andere in Koordinatenform

>[!write] Beide Ebenen in Koordinatenform
> Ermittle die gegenseitige Lage von 
> $\qquad \qquad E_{1}:\overrightarrow{x}=\begin{pmatrix}3 \\ 1\\ -4\end{pmatrix}+r \begin{pmatrix}1 \\ -3  \\ 1\end{pmatrix}+s \begin{pmatrix}2 \\ 4  \\ 0\end{pmatrix}$
> und 
> $\qquad \qquad E_{2}$.
> 
> - $E_{2}: -2x_{1}+x_{2}-5x_{3}=15$
> - $E_{2}: 3x_1+7x_{2}-x_{3}=37$

<br>

>[!success]- Lösung
>![[Lagebeziehung von Ebenen#^0671e2]]

<br>

___
# Beide Ebenen in Parameterform

>[!write] Beide Ebenen in Koordinatenform
> Ermittle die gegenseitige Lage der Ebenen 
> 
> $\qquad \qquad E_{1}:\overrightarrow{x}=\begin{pmatrix}3 \\ 1\\ -4\end{pmatrix}+r \begin{pmatrix}1 \\ -3  \\ -1\end{pmatrix}+s \begin{pmatrix}2 \\ 4  \\ 0\end{pmatrix}$
> und 
> $\qquad \qquad E_{2}:\overrightarrow{x}=\begin{pmatrix}8 \\ 2\\ 1\end{pmatrix}+k \begin{pmatrix}3 \\ -1  \\ 2\end{pmatrix}+l \begin{pmatrix}4 \\ -1  \\ 5\end{pmatrix}$.

<br>

>[!success]- Lösung
>![[Lagebeziehung von Ebenen#^2da8d5]]

<br>

___
# Annotation

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Die beiden Koordinatengleichungen bilden ein LGS.<br>Bringe es in Zeilenstufenform.<br>Eine Variable ist frei wählbar.<br>Also schneiden sich die Ebenen in einer Geraden.<br><br><br>Schreibe die allgemeine Lösung als Vektor und ermittle so eine Gleichung der Schnittgeraden. | <br>Gleichungssystem aufstellen:<br><br>$\left(\begin{array}{ccc\|c}-2&1&-5&15 \\ 3&7&-1&37\end{array}\right) \underrightarrow{ZSF} \left(\begin{array}{ccc\|c}-2&1&-5&15 \\ 0&1&-1&7\end{array}\right)$<br><br>eine Variable frei wählbar<br>L=${(-4-2t\mid 7+t\mid t);\ t\in \mathbb{R}}$<br><br>Schnittgerade bestimmen:<br><br>$g:\begin{pmatrix}x_1 \\ x_2  \\ x_3\end{pmatrix}=\begin{pmatrix}-4-2t \\ 7+t  \\ t\end{pmatrix}=\begin{pmatrix}-4 \\ 7  \\ 0\end{pmatrix}+t \cdot \begin{pmatrix}-2 \\ 1  \\ 1\end{pmatrix}$<br>$\quad$ |
| <br>Stelle mit den Koordinatengleichungen ein LGS auf.<br>Beim Umformen entsteht eine Nullzeile.<br>Also sind zwei Variablen frei wählbar, d.h., die Ebenen sind identisch | <br>Gleichungssystem aufstellen:<br><br>$\left(\begin{array}{ccc\|c}-2&1&-5&15 \\ -6&3&-15&45\end{array}\right) \underrightarrow{ZSF} \left(\begin{array}{ccc\|c}-2&1&-5&15 \\ 0&0&0&0\end{array}\right)$<br><br>zwei Variablen frei wählbar<br>$E_1$ und $E_2$ sind identisch.<br>$\quad$ |
| <br>Bringe das LGS der beiden Koordinatengleichungen in Zeilenstufenform.<br>Es entsteht eine Widerspruchszeile.<br>Also haben $E_{1}$ und $E_2$ keine gemeinsamen Punkte. | <br>Gleichungssystem aufstellen:<br><br>$\left(\begin{array}{ccc\|c}-2&1&-5&15 \\ 4&-2&10&7\end{array}\right) \underrightarrow{ZSF} \left(\begin{array}{ccc\|c}-2&1&-5&15 \\ 0&0&0&37\end{array}\right)$<br><br>keine Lösung<br>$E_1$ und $E_2$ sind echt parallel zueinander.<br>$\quad$ |

^473f36

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Setze die Koordinaten von $E_1$ in die Koordinatengleich von $E_2$ ein.<br>Es ergibt sich eine Gleichung mit zwei Parametern.<br>Beim Zusammenfassen verschwinden die Variablen und es ergibt sich eine Gleichung, die für alle r und s erfüllt ist.<br>Also sind alle Punkte von $E_1$ auch gemeinsame Punkte.<br>$\quad$ | <br>Koordinaten von $E_1$:<br>$x_1=3+r+2s; \ \ x_2=1-3r+4s; \ \ x_3=-4-r$<br><br>Einsetzen in $E_2$:<br>$\begin{align*}-2(3+r+2s)+(1-3r+4s)-5(-4-r)&=15 \\ -6-2r-4s+1-3r+4s+20+5r&=15 \\ 15&=15 \text{ (gilt allgemein)}\end{align*}$<br><br>$E_1$ und $E_2$ sind identisch. |
| <br>Setze die Koordinaten von $E_1$ in die Koordinatengleichung von $E_2$ ein.<br>Löse die Gleichung nach r auf.<br>Beim Umstellen bleiben die Variablen erhalten.<br>Setze $r=-1+2s$ in die Parametergleichung von $E_1$ ein und bestimme so die Gleichung der Schnittgeraden g. | <br>Koordinaten von $E_1$ in $E_2$ einsetzen:<br><br>$\begin{align*}3(3+r+2s)+7(1-3r+4s)-(-4-r)&=37\end{align*}$<br><br>$r=-1+2s \qquad \qquad E_{1}$ und $E_2$ schneiden sich.<br><br><br>Schnittgerade bestimmen:<br><br>$\begin{align*}g:\overrightarrow{x}&= \begin{pmatrix}3 \\ 1  \\ -4\end{pmatrix}+(-1+2s) \cdot \begin{pmatrix}1 \\ -3  \\ -1\end{pmatrix} +s \cdot \begin{pmatrix}2 \\ 4  \\ 0\end{pmatrix}\\ \\ &= \begin{pmatrix}2 \\ 4  \\ -3\end{pmatrix}+ s \cdot \begin{pmatrix}4 \\ -2  \\ -2\end{pmatrix}\end{align*}$<br>$\quad$ |

^0671e2

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Setze die Ebenengleichungen gleich und erzeuge so ein lineares Gleichungssystem. | <br>Parametergleichungen gleichsetzen:<br><br>$\begin{pmatrix}3 \\ 1\\ -4\end{pmatrix}+r \begin{pmatrix}1 \\ -3  \\ -1\end{pmatrix}+s \begin{pmatrix}2 \\ 4  \\ 0\end{pmatrix}= \begin{pmatrix}8 \\ 2\\ 1\end{pmatrix}+k \begin{pmatrix}3 \\ -1  \\ 2\end{pmatrix}+l \begin{pmatrix}4 \\ -1  \\ 5\end{pmatrix}$<br>$\quad$ |
| <br>Bringe das LGS in Zeilenstufenform.<br>Die Lösung enthält eine frei wählbare Variable.<br>Somit schneiden sich $E_1$ und $E_2$ in einer Geraden.<br>$\quad$ | <br>Lineares Gleichungssystem lösen:<br><br>$\left(\begin{array}{cccc\|c}1&2&-3&-4&5 \\ -3&4&1&1&1 \\ -1&0&-2&-5&5\end{array}\right) \underrightarrow{ZSF} \left(\begin{array}{cccc\|c}1&2&-3&-4&5 \\ 0&10&-8&11&16 \\ 0&0&1&2&-2 \end{array}\right)$<br><br> |
| <br>Setze $k=-2l-2$ in die Gleichung von $E_2$ ein und bestimme so die Gleichung der Schnittgerade g.<br>Das Einsetzen von $r=-l-1$ und $\displaystyle s=-\frac{1}{2}l$ in $E_1$ ist aufwändiger, liefert aber ebenfalls die Gleichung von g.<br>$\quad$ | <br>Schnittgerade bestimmen:<br><br>$\begin{align*}g:\overrightarrow{x}&= \begin{pmatrix}8 \\ 2  \\ 1\end{pmatrix}+(-2l-2) \cdot \begin{pmatrix}3 \\ -1  \\ 2\end{pmatrix} +l \cdot \begin{pmatrix}4 \\ -1  \\ 5\end{pmatrix}\\ \\ &= \begin{pmatrix}2 \\ 4  \\ -3\end{pmatrix}+ l \cdot \begin{pmatrix}-2 \\ 1  \\ 1\end{pmatrix}\end{align*}$ |

^2da8d5
