---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Exponentialfunktionen|Zurück]]

___
# Definition

>[!hint] Begrenztes Wachstum
>Die Gleichung $f(t)=S-(S-a)\cdot e^{-k\ \cdot \ t}$ mit $k>0$ beschreibt einen begrenzten Wachstumsprozess eines Bestands.
>
>$a=f(0)$ ist der **Anfangsbestand** zum Zeitpunkt $t=0$.
>Der Graph von $f$ nähert sich **asymptotisch** einer **Grenze** S an.
>
>$a>S:$ **begrenzte Abnahme** (Annäherung von oben)
>
>$a<S:$ **begrenzte Zunahme** (Annäherung von unten)
>
>>[!info] Graphische Veranschaulichung
>![[Pasted image 20231230101301.png|550]]

<br>

___
# Beispiel

>[!write] Werte bei Funktion zu begrenztem Wachstum bestimmen
>Die Temperatur von Wasser in einem Glas in Abhängigkeit der Zeit $t$ in Minuten lässt sich durch die Funktion $f$ mit 
>
>$\qquad \qquad \qquad f(t)=35-20e^{-0.15t}$
>
>beschrieben.
>
>- Gebe die Grenze und die Anfangstemperatur an.
>- Begründe anhand des Funktionsterms, dass die Temperatur stets kleiner ist als die Grenze, sich aber asymptotisch der Grenze nähert.
>- Bestimme den Zeitpunkt, zu dem die Wassertemperatur 20°C erreicht.
>- Bestimme den Zeitpunkt, an dem die Wachstumsgeschwindigkeit $\displaystyle 0.75\frac{°C}{min}$ ist.

<br>

>[!success]- Lösung
>![[Begrenztes Wachstum#^c12d69]]

<br>

>[!write] Funktion zu begrenzten Wachstum aufstellen
>Ein heißes Mikrowellenessen kommt mit 85°C aus der Mikrowelle.
>Im Raum herrschen 23°C.
>Nach 5 Minuten ist das Essen noch 65°C warm.
>
>- Stelle eine Funktion auf, welche den Wachstumsprozess beschreibt.

<br>

>[!success]- Lösung
>![[Begrenztes Wachstum#^51001b]]

<br>

___
# Annotation

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Die Grenze $S$ und die Anfangstemperatur $a$ ergeben sich durch einen Vergleich der allgemeinen mit der hier konkret vorgegebenen Funktionsgleichung. | <br>$\begin{align*}f(t)&={\color{red}{S}}-({\color{cyan}{S-a}})\cdot e^{-k\ \cdot \ t} \\ f(t)&= {\color{red}{35}}-{\color{cyan}{20}} \cdot e^{-0.15\ \cdot \ t} \end{align*}$<br>${\color{cyan}{20=S-a=35-a}}$, also ${\color{cyan}{a=15}}$ <br><br>Grenze der Temperatur: 35°C<br><br>Anfangstemperatur: 15°C<br>$\quad$ |
| <br>Der Ausdruck $d(t)=20\cdot e^{-0.15\ \cdot \ t}$ beschreibt die Differenz zwischen der Grenze $S$ und der Temperatur $f(t)$. Die Differenz $d(t)$ ist immer positiv und sie nimmt exponentiell ab. | <br>$f(t)={\color{red}{35}}-20\cdot \color{yellow}{e^{-0.15t}}$<br><br><span style="color:#ff0000">Grenze</span> $\quad$ <br><span style="color:#ffff00">exponentiell abnehmend Differenz zur Grenze</span><br><br>Da die Differenz $d(t)$ von der Grenze $S$ subtrahiert wird, ist die Temperatur $f(t)$ stets kleiner als die Grenze. $d(t)$ strebt für $t \rightarrow \infty$ gegen 0 und $f(t)$ gegen $S$.<br>$\quad$ |
| <br>Setze in der Funktionsgleichung 20 für $f(t)$ ein und löse die Gleichung nach $t$ auf. | <br>$\displaystyle \begin{align*}20&=35-20e^{-0.15t} \qquad \mid -35 \quad \mid \ :(-20) \\ 0.75&=e^{-0.15t} \qquad \qquad \ \quad \mid ln() \quad \mid \ : (-0.15) \\ t&=\frac{ln(0.75)}{-0.15} \approx 1.92\end{align*}$<br><br>Der Zeitpunkt ist etwa 1,92 min (1 min 55s).<br>$\quad$ |
| <br>Bestimme für die Wachstumsgeschwindigkeit die erste Ableitung $f'(t)$ und setze sie gleich 0,75.<br>Löse die Gleichung nach $t$ auf. | <br>$f'(t)=-20\cdot (-0.15) \cdot e^{-0.15}=3e^{-0.15t}$<br><br>$\displaystyle \begin{align*}0.75&=3e^{-0.15t} \qquad \mid :3 \\ ln(0.25)&=e^{-0.15t} \qquad  \ \ \mid ln() \quad \mid : (-0.15) \\ t&=\frac{ln(0.25)}{-0.15} \approx 9.24\end{align*}$<br><br>Der Zeitpunkt ist etwa 9,24 min (9 min 14s).<br>$\qquad$ |

^c12d69

| Vorgehen | Rechnung |
| --- | --- |
| Die Raumtemperatur liefert die Grenze $S=23$ und die Anfangstemperatur $a=85$.<br><br>Wenn man die Werte $S=23$ und $a=85$ in die allgemeine Funktionsgleichung einsetzen erhält man $f(t)=23+62\cdot e^{-k \ \cdot \ t}$.<br><br><br>Setze in diese Gleichung die Angaben $t=5$ und $f(t) =65$ ein und löse die Gleichung nach $k$ auf. | allgemein:<br> $f(t)=S-(S-a)\cdot e^{-k \ \cdot \ t}$<br><br>$t$: Zeit in Minuten <br>$f(t)$: Temperatur in °C<br><br>$f(t)=23-(23-85)\cdot e^{-k \ \cdot \ t}=23+62e^{-k\ \cdot \ t}$<br><br><br><br>$\displaystyle \begin{align*} 65&=23+62e^{-k\ \cdot \ 5} \qquad \mid -23 \quad \mid :62 \\ \\ \frac{21}{32}&=e^{-k\ \cdot \ 5} \qquad \qquad \quad \mid ln() \\ \\ ln(\frac{21}{32})&=-k\cdot 5 \qquad \qquad \quad \mid : (-5) \\ \\ k&=\frac{ln(\frac{21}{32})}{-5} \approx 0.078\end{align*}$<br><br><br><br>$f(t)=23+62e^{-0.078t}$<br>$\quad$ |

^51001b

