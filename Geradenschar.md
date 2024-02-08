---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Geradenschar
>Enthält der Stützvektor oder der Richtungsvektor einer Geradengleichung einen zusätzlichen reellen Parameter, so handelt es sich um eine ganze Schar von Geraden.

<br>

___
# Beispiel

>[!write] Geradenschar
>Gegeben sind die Geradenschar $g_a$ mit dem Scharparameter $a \in \mathbb{R}$ und die Gerade h.
>
>$\qquad g_{a}:\overrightarrow{x}=\begin{pmatrix}6 \\ 6  \\ 4\end{pmatrix}+r\cdot \begin{pmatrix}-2 \\ 2a  \\ a\end{pmatrix}$,
>
>$\qquad h_{a}:\overrightarrow{x}=\begin{pmatrix}8 \\ 12  \\ 3\end{pmatrix}+s\cdot \begin{pmatrix}2 \\ 2  \\ -1\end{pmatrix}$
>
>- Welchen Punkt P haben alle Geraden der Schar $g_a$ gemeinsam?
>- Für welchen Wert von a liegt der Punkt $Q(4\mid 12 \mid 7)$ auf der Geraden $g_{a}$?
>- Für welchen Wert von a schneiden sich die Geraden $g_{a}$ und h?
>- Welche besondere Lage hat die Gerade $g_{a}$ für $a=0$?
 
<br>

>[!success]- Lösung
>![[Geradenschar#^6102cd]]

<br>

___
# Parallele Geraden

>[!hint] Parallele Geraden
>Die Gleichung $g_{a}: \overrightarrow{x}=\begin{pmatrix}2 \\ a  \\ 0\end{pmatrix}+r\begin{pmatrix}-1 \\ 0  \\ 2\end{pmatrix}$
>beschreibt eine Schar paralleler Geraden, denn alle Geraden $g_a$ haben den gleichen Richtungsvektor.
>Sie unterscheiden sich nur in der y-Koordinate ihres Stützpunktes
>
>>[!info] Grafik
>>![[Pasted image 20240101110739.png|350]]

<br>

___
# Gemeinsamer Stützvektor

>[!hint] Gemeinsamer Stützpunkt
>Die Gleichung $g_{a}:\overrightarrow{x}=\begin{pmatrix}2 \\ 4  \\ 3\end{pmatrix}+r\begin{pmatrix}-1 \\ 1  \\ 2+a\end{pmatrix}$
>beschreibt eine Schar von Geraden, die alle den gleichen Stützpunkt P$(2\mid 4\mid 3)$ haben, um den sie sich aufgrund der veränderlichen z-Koordinate ihres Richtungsvektors drehen.
>
>>[!info] Grafik
>>![[Pasted image 20240101111435.png|350]]

<br>

___
# Annotation

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Man erkennt auf einen Blick, dass alle Geraden $g_a$ den Stützpunkt P$(6\mid 6\mid 4)$ gemeinsam haben, denn dieser Punkt hängt nicht vom Parameter a ab. | <br>Gemeinsamer Punkt der Schargeraden:<br><br>P$(6\mid 6\mid 4)$ liegt für jedes a auf der Geraden $g_a$<br>$\quad$ |
| <br>Wir setzen den Ortsvektor des Punktes Q in die linke Seite der Gleichung von $g_a$ ein.<br>So erhalten wir das rechts aufgeführte lineare Gleichungssystem.<br>Gleichung $I$ liefert zunächst $r=1$.<br>Aus den Gleichungen $II$ bzw. $III$ folgt damit $a=3$.<br>Q liegt also auf $g_3$. | <br>Parameterbestimmung (Q liegt auf $g_a$).<br><br>$\begin{align*}&I:\\& II:\\ &  III:\end{align*}\begin{vmatrix}6-2r = 4 \\6+2ar=12  \\ 4+ar=7\end{vmatrix}$$\Rightarrow$ $\begin{vmatrix}r=1 \\ 6+2a=12  \\ 4+a=7\end{vmatrix}$<br>$\qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad$<br>$a=3;\ r=1$<br><br>Q$(4\mid 12\mid 7)$<br>$\quad$ |
| <br>Wir setzen die rechten Seiten der Geradengleichungen von $g_a$ und h gleich.<br>Wir erhalten ein lineares Gleichungssystem mit den Variablen r und s sowie dem zusätzlichen Parameter a.<br><br>Die Lösung dieses Gleichungssystems ergibt $r=1,\ s=-2$ und $a=1$.<br>Also schneiden sich die Geraden $g_1$ und h.<br>Den Schnittpunkt S erhalten wir z.B., indem wir den Wert $s=-2$ in die Gleichung von h einsetzen.<br>$\quad$ | <br>Schnittpunkt von $g_a$ und h:<br><br>$\begin{align*}&I:\\& II:\\ &  III:\end{align*}\begin{vmatrix}6-2r = 8+2s \\6+2ar=12+2s  \\ 4+ar=3-s\end{vmatrix}$<br><br>$\begin{align*}&II-2\cdot III:\\& In\ I:\\ &  In\  III:\end{align*}\begin{vmatrix}-2 = 6+4s \\6-2r=4  \\ 4+a=5\end{vmatrix}$$\begin{align*}\Rightarrow s&=-2\\ \Rightarrow r&=1 \\ \Rightarrow a&=1 \end{align*}$<br><br>g und h schneiden sich in <br><br>S$(4\mid 8\mid 5)$.<br> |
| <br>Für $a=0$ gilt $x=6-2r,\ y=6$ und $z=4$.<br>Es variiert also nur die x-Koordinate der Geraden.<br>Also liegt sie parallel zu x-Achse. | <br>![[Pasted image 20240101110026.png]]<br>$\quad$ |

^6102cd

