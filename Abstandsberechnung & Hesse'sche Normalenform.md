#GK #Unterthema

# [[Analytische Geometrie|Zurück]]

___
# Inhaltsverzeichnis - Abstandberechnung & Hesse'sche Normalenform

- [[Abstandsberechnung & Hesse'sche Normalenform#Abstand Punkt-Ebene|Abstand Punkt-Ebene]]
- [[Abstandsberechnung & Hesse'sche Normalenform#Hesse'sche Normalenform|Hesse'sche Normalenform]]
- [[Abstandsberechnung & Hesse'sche Normalenform#Abstand Punkt-Gerade|Abstand Punkt-Gerade]]
- [[Abstandsberechnung & Hesse'sche Normalenform#Abstand windschiefer Geraden|Abstand windschiefer Geraden]]


___
# Erläuterung 

>[!info] Erläuterung 
>Bei den Abständen bei den folgenden "Problemen" wird stets der kürzeste Abstand gesucht.

<br>

___
# Abstand Punkt-Ebene

## Beispiel

>[!write] Abstand eines Punktes von einer Ebene bestimmen
> Berechne den Abstand des Punktes R$(9\mid -3\mid 2)$ zur Ebene $E:3x_{1}+x_{2}-2x_{3}=-12$.

<br>

>[!success]- Lösung
>Schreibe Lösung

<br>

>[!write] Punkt mit vorgegebenem Abstand bestimmen
> Gegeben ein Quadrat ABCD, das in der Ebene $E:2x_{1}+x_{2}+2x_{3}=9$ liegt.
> Der Punkt M$(4\mid 1\mid 0)$ ist der Mittelpunkt des Quadrats.
> - Bestimme den Punkt S so, dass ABCDS eine senkrechte Pyramide mit der Höhe 6 ist.
>
>>[!info] Graphik
>>![[Pasted image 20240102132405.png]]

<br>

>[!success]- Lösung
>Es gibt zwei Lösungen.
>Man findet die Spitze $S_{1}$ und $S_{2}$, indem man von M aus 6 LE in Richtung des Normalenvektors bzw. in die entgegengesetzte Richtung geht.
>
>Es gilt:
>$\displaystyle \vert \ \overrightarrow{n} \ \vert=\left\vert \ \begin{pmatrix}2 \\ 1  \\ 2\end{pmatrix} \ \right\vert =3$, also hat $\overrightarrow{n}_{0}=\frac{1}{3} \cdot \begin{pmatrix}2 \\ 1  \\ 2\end{pmatrix}$ die Länge 1.
>
>$\displaystyle \overrightarrow{OS}_{1}=\overrightarrow{OM}+6 \cdot \overrightarrow{n}_{0}=\begin{pmatrix}4 \\ 1  \\ 0\end{pmatrix}+6 \cdot \frac{1}{3} \cdot \begin{pmatrix}2 \\ 1  \\ 2\end{pmatrix}=\begin{pmatrix}8 \\ 3  \\ 4\end{pmatrix}$
>
>bzw.
>
>$\displaystyle \overrightarrow{OS}_{2}=\overrightarrow{OM}-6 \cdot \overrightarrow{n}_{0}=\begin{pmatrix}4 \\ 1  \\ 0\end{pmatrix}-2 \cdot \begin{pmatrix}2 \\ 1  \\ 2\end{pmatrix}=\begin{pmatrix}0 \\ -1  \\ -4\end{pmatrix}$
>
>Man erhält $S_{1}(8\mid 3\mid 4)$ und $S_{2}(0\mid -1\mid -4)$.

<br>

___
# Hesse'sche Normalenform

## Definition

>[!hint] Hesse'sche Normalenform
>Sei E eine Ebene durch den Punkt P und mit Normalenvektor $\overrightarrow{n}$.
>Für den Abstand eines Punktes A zur Ebene E gilt:
>
>$\displaystyle \qquad \qquad d(A,E)=\frac{1}{\vert \ \overrightarrow{n} \ \vert}\ \vert \ \overrightarrow{n} \cdot \overrightarrow{OA}- \overrightarrow{n} \cdot \overrightarrow{OP} \ \vert$
>
>Ist $\overrightarrow{n} \cdot \overrightarrow{x}- \overrightarrow{n} \cdot \overrightarrow{OP}=0$ eine Normalengleichung einer Ebene E, so heißt $\frac{1}{\vert \ \overrightarrow{n} \ \vert}\ ( \ \overrightarrow{n} \cdot \overrightarrow{x}- \overrightarrow{n} \cdot \overrightarrow{OP})=0$ **Hesse'sche Normalenform** (HNF) der Ebene E.
>
>>[!attention] Hinweis
>>Der Vektor $\overrightarrow{n}_{0}=\frac{1}{\vert \ \overrightarrow{n} \ \vert}\ \overrightarrow{n}$ hat die Länge 1 und heißt **Normaleneinheitsvektor** der Ebene.

<br>

>[!write] Abstand eines Punktes zu einer Ebene
>Berechne den Abstand des Punktes A$(9\mid -3\mid 2)$ zur Ebene $E:-3x_{1}-x_{2}+2x_{3}=12$.

<br>

>[!success] Lösung
>![[Abstandsberechnung & Hesse'sche Normalenform#^9c72bb]]

<br>

___
# Abstand Punkt-Gerade

>[!info] Aufhabe zum Verständnis des Abstandsproblem
>Eine vereinfachte Darstellung der Problematik ist in der Abbildung zu sehen.
>Das Flugzeug befindet sich bezogen auf das eingezeichnete Koordinatensystem im Steigflug längs der Geraden 
>
>$g:\overrightarrow{x}=\begin{pmatrix}1 \\1  \\ 0\end{pmatrix}+t \cdot \begin{pmatrix}2 \\ 3  \\ 1\end{pmatrix}$ (1 Koordinateneinheit = 1 km).
>
>Es soll untersucht werden, ob das Flugzeug einen Sicherheitsabstand von 500m zur Kirchenturmspitze mit den Koordinaten R$(1\mid 2\mid 0.08)$ einhält.
>
>>[!info] Abbildung
>>![[Pasted image 20240102143008.png]]

<br>

>[!hint] Hilfsebene zur Bestimmung des Abstandes
>Man betrachtet die Hilfsebene
>$E:2x_{1}+3x_{2}+x_{3}=0.08$, die orthogonal zur Geraden g ist und durch den Punkt R geht.
>Der Punkt F ist dann der Schnittpunkt der Geraden g mit der Hilfsebene E und hat die Koordinaten F$(1.44\mid 1.66\mid 0.22)$.
>
>Damit ist $\vert \ \overrightarrow{FR} \ \vert=\sqrt{0.3228} \approx 0.573$.
>Das Flugzeug kommt also nicht näher als 573m. 
>Der Sicherheitsabstand wird eingehalten.
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20240102143516.png|350]]

<br>

>[!hint] Orthogonalität zur Bestimmung des Abstandes
>Wenn man für F den allgemeinen Geradenpunkt $F_{t}(1+2t\mid 1+3t \mid t)$ einsetzt, führt die Orthogonalitätsbedingung $\overrightarrow{FR} \cdot \overrightarrow{u}=0$ auf die Gleichung $\begin{pmatrix}1-(1+2t) \\ 2-(1+3t)  \\ 0.08-t\end{pmatrix} \cdot \begin{pmatrix}2 \\ 3  \\ 1\end{pmatrix}=0$ bzw. 
>$-2t \cdot 2+(1-3t) \cdot 3 + (0.08-t) \cdot 1=0$ mit der Lösung $t=0.22$. Also hat F die Koordinaten F$(1.44\mid 1.66\mid 0.22)$.
>
>Damit ist $\vert \ \overrightarrow{FR} \ \vert=\sqrt{0.3228} \approx 0.573$.
>Das Flugzeug kommt also nicht näher als 573m. 
>Der Sicherheitsabstand wird eingehalten.
>

<br>

>[!hint]- Abstandbestimmung als Extremwertproblem
>![[Pasted image 20240102150601.png]]

<br>

## Beispiel

>[!write] Flächeninhalt eines Dreiecks bestimmen
>Berechne den Flächeninhalt des Dreiecks ABC mit A$(2\mid -3\mid 5)$, B$(4\mid 3\mid 3)$ und C$(-2\mid 0\mid 6)$.
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20240102150959.png|250]]

<br>

>[!success]- Lösung
>Formel - Flächeninhalt eines Dreiecks: $\displaystyle A=\frac{1}{2} \cdot g \cdot h$
>
>Die Höhe des Dreiecks lamm als Abstand des Punktes A zur Geraden durch die Punkte B und C betrachtet werden.
>Zur Berechnung stellt man zunächst die Geradengleichung für die Gerade $g_{BC}$ auf.
>
>$g_{BC}:\overrightarrow{x}=\overrightarrow{OB}+ t \cdot \overrightarrow{CB} = \begin{pmatrix}4 \\ 3  \\3\end{pmatrix}+ t \cdot \begin{pmatrix}6 \\ 3  \\ -3\end{pmatrix}$.
>
>Die Abstandsberechnung wird mit der Methode der Hilfsebene durchgeführt:
>- Ansatz für die Hilfsebene orthogonal zu $g:6x_{1}+3x_{2}-3x_{3}=d$.
>  Einsetzen der Koordinaten von B liefert $d=6 \cdot 2+3 \cdot (-3)-3 \cdot 5=-12$ und somit $E:6x_{1}+3x_{2}-3x_{3}=-12$.
>- Einsetzen von g in E liefert:
>  $6 \cdot (4+6t)+3 \cdot (3+3t)-3 \cdot (3-3t) = -12$
>  und damit $\displaystyle t=-\frac{2}{3}$.
>- $\vert \ \overrightarrow{FA} \ \vert =\left\vert \ \begin{pmatrix}2-0 \\ -3-1  \\ 5-5\end{pmatrix} \ \right\vert=\left\vert \ \begin{pmatrix}2 \\ -4  \\ 0\end{pmatrix} \ \right\vert=\sqrt{2^{2}+(-4)^{2}+0^{2}=\sqrt{20}\approx}4.47$.
>  Der Abstand des Punktes A zur Geraden $g_BC$ und damit die Höhe des Dreiecks ABC beträgt $\sqrt{20}\approx4.47$.
>  Die Länge der Grundseite beträgt: $\vert \ \overrightarrow{BC} \ \vert =\left\vert \ \begin{pmatrix}6 \\ 3  \\ -3\end{pmatrix} \ \right\vert=\sqrt{36+9+9}=\sqrt{54}\approx 7.35$.
>  Somit ergibt sich für den Flächeninhalt: $A\approx 0.5 \cdot 7.35 \cdot 4.47 \approx 16.43$ FE.

<br>

___
# Abstand windschiefer Geraden

## Verfahren

>[!hint] Hilfsebene
>Wenn zwei Geraden 
>
>$\qquad \qquad g:\overrightarrow{x}=\overrightarrow{p}+s \cdot \overrightarrow{u}$
>und
>$\qquad \qquad g:\overrightarrow{x}=\overrightarrow{q}+t \cdot \overrightarrow{v}$
>
>windschief sind, gibt es eine Ebene E, sodass 
>- die Gerade g in der Ebene E liegt und
>- die geraden h parallel zur Ebene E ist.
>
>Der Abstand der Geraden g und h ist dann gleich dem Abstand eines beliebigen Punktes von h zur Ebene E.
>Der Normalenvektor von E ist orthogonal zu den Richtungsvektoren von g und h.
>Deshalb kann man aus den Gleichungen
>$\qquad \qquad \overrightarrow{u} \cdot \overrightarrow{n}=0$
>und 
>$\qquad \qquad \overrightarrow{v} \cdot \overrightarrow{n}=0$
>einen Normalenvektor für E bestimmen.
>
>Eine Gleichung der Ebene E ist 
>$(\ \overrightarrow{x}-\overrightarrow{p}\ \ ) \cdot \overrightarrow{n}=0$ bzw. $n_{1}\cdot x_{1}+n_{2} \cdot x_{2}+n_{3} \cdot x_{3}=d$.
>
>Dabei ist $d= \overrightarrow{n} \cdot \overrightarrow{p}$ stellt den Ortsvektor eines Punktes der Ebenen dar.
>Da die Gerade h parallel zu Ebene E ist, kann nun mithilfe des Punktes B auf der Geraden g der Abstand zur Ebene E berechnet werde.
>Hierzu stellt man die zu E orthogonale Gerade durch den Punkt B auf (Lotgerade durch B), bestimmt den Lotfußpunkt F der Lotgeraden mit der Ebene E und berechnet den Betrag des Vektors $\overrightarrow{BF}$.
>
>>[!info] Graphische Darstellung 
>>![[Pasted image 20240102160225.png|550]]

<br>

>[!hint] Orthogonalität
>Die Strecke $\overline{GH}$ ist die kürzeste Verbindungsstrecke zwischen der Geraden g und h.
>Deshalb ist $\overline{GH}$ sowohl das Lot vom Punkt G auf die Gerade h als auch das Lot vom Punkt H auf die Gerade g.
>Man sagt, die Strecke $\overline{GH}$ ist das gemeinsame Lot der windschiefen Geraden g und h.
>Für die Lotfußpunkte G und H gilt:
>$\qquad \qquad \overrightarrow{GH}\ \bot \ g$
>und 
>$\qquad \qquad \overrightarrow{GH}\ \bot \ h$.
>
>Um den Abstand der windschiefen Geraden g und h zu berechnen, bestimmt man diese Punkte G und H.
>Hierzu kann man so vorgehen:
>
>Man bezeichnet mit $G_s$ die Punkte der Geraden $g:\overrightarrow{x}=\overrightarrow{p} +s \cdot \overrightarrow{u}$ und mit $H_{t}$ die Punkte der Geraden $h:\overrightarrow{x}=\overrightarrow{q} +t \cdot \overrightarrow{v} \quad (s, t \in \mathbb{R})$.
>Damit gilt
>$\qquad G_{s}(p_{1}+s \cdot \overrightarrow{u_{1}}\mid p_{2}+s \cdot \overrightarrow{u_{2}} \mid p_{3}+s \cdot \overrightarrow{u_{3}})$ 
>und
>$\qquad H_{t}(q_{1}+t \cdot \overrightarrow{v_{1}}\mid q_{2}+t \cdot \overrightarrow{v_{2}} \mid q_{3}+t \cdot \overrightarrow{v_{3}})$.
>
>Nun bestimmt man s und t so, dass $\overrightarrow{G_{s}H_{t}}\ \bot \ g$ und $\overrightarrow{G_{s}H_{t}}\ \bot \ h$.
>
>Der Vektor $\overrightarrow{G_{s}H_{t}}$ ist also orthogonal zum Richtungsvektor $\overrightarrow{u}$ der Geraden g und zum Richtungsvektor $\overrightarrow{v}$ der Geraden h.
>Daraus folgt das LGS 
>$\qquad \qquad \overrightarrow{G_{s}H_{t}} \cdot \overrightarrow{u}=0$
>und
>$\qquad \qquad \overrightarrow{G_{s}H_{t}} \cdot \overrightarrow{v}=0$
>Mit der Lösung des LGS kann man die Koordinaten der gesuchten Punkte G und H berechnen.
>

<br>

>[!hint] Abstand windschiefer Geraden mit dem Lotfußpunktverfahren
>Der Abstand d($g_{1},g_{2}$) zweier windschiefer Geraden 
>$\qquad \qquad g_{1}:\overrightarrow{x}=\overrightarrow{OP}_{1}+r\ \overrightarrow{v}_{1}$
>und
>$\qquad \qquad g_{2}:\overrightarrow{x}=\overrightarrow{OP}_{2}+r\ \overrightarrow{v}_{2}$
>lässt sich wie folgt berechnen.
>- Parameter r und s ermitteln, sodass Verbindungsvektor $\overrightarrow{X_{r}X_{s}}$ senkrecht zu $\overrightarrow{v_{1}}$ und $\overrightarrow{v_{2}}$ ist.
>- r und s in $\overrightarrow{X_{r}X_{s}}$ einsetzen und die Lotfußpunkte $F_{1}$ und $F_{2}$ ermitteln.
>- Der Abstand ist gleich der Länge des Vektors $\overrightarrow{F_{1}F_{2}}$, also $d(g_{1},g_{2})=\vert\overrightarrow{F_{1}F_{2}} \vert$.

<br>

>[!w] Beispiel
>Die Geraden 
>$\qquad \qquad g_{1}:\overrightarrow{x}=\begin{pmatrix}-2 \\ -7  \\ 9\end{pmatrix}+r \begin{pmatrix}2 \\ 3  \\ -4\end{pmatrix}$
>und
>$\qquad \qquad g_{1}:\overrightarrow{x}=\begin{pmatrix}29 \\ -9  \\ -5\end{pmatrix}+s \begin{pmatrix}-1 \\ 0  \\ 4\end{pmatrix}$
>
>sind windschief zueinander.
>- Bestimme den Abstand der Geraden und gebe die Koordinaten der Fußpunkte des gemeinsamen Lotes an.

<br>

>[!success] Lösung
>![[Abstandsberechnung & Hesse'sche Normalenform#^5238a0]]

<br>

___
# Annotation

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Mit $\overrightarrow{OA}$ als Stützvektor und einem Normalenvektor von E als Richtungsvektor ergibt sich eine Gleichung der Lotgeraden. | <br>Lotgerade:<br>$g:\overrightarrow{x}=\begin{pmatrix}9 \\ -3  \\ 2\end{pmatrix}+t \begin{pmatrix}3 \\ 1  \\ -2\end{pmatrix}$<br>$\quad$ |
| <br>Das Einsetzen der Koordinaten von g in die Koordinatengleichung von E liefert die Schnittbedingung.<br>Löse nach t auf.<br>Setze t in die Geradengleichung ein und berechne so den Ortsvektor des Lotfußpunktes F.<br>$\quad$ | <br>Lotfußpunkt:<br>$3(9+3t)+(-3+t)-2(2-2t)=-12$<br><br>$\displaystyle 20+14t=-12 \iff t=-\frac{16}{7}$<br><br>$\displaystyle \overrightarrow{OF}=\begin{pmatrix}9 \\ -3  \\ 2\end{pmatrix}-\frac{16}{7} \begin{pmatrix}3 \\ 1  \\ -2\end{pmatrix}=\frac{1}{7}\begin{pmatrix}15 \\ -37  \\ 46\end{pmatrix}$<br> |
| <br>Berechne den Betrag von $\overrightarrow{AF}$ und mit den Abstand von A zur Ebene E. | <br>Abstand:<br>$\displaystyle \begin{align*} d(A,E)&=\vert \ \overrightarrow{AF} \ \vert \ =\ \vert \ \overrightarrow{OF} - \overrightarrow{OA}\ \vert \\ &=\ \left \vert \ \begin{pmatrix}9 \\ -3  \\ 2\end{pmatrix}-\frac{16}{7} \begin{pmatrix}3 \\ 1  \\ -2\end{pmatrix} - \begin{pmatrix}9 \\ -3  \\ 2\end{pmatrix} \  \right \vert \\ &= \frac{16\sqrt{4}}{7} \approx 8.6\end{align*}$<br>$\quad$ |

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Stelle eine Normalengleichung auf und forme diese so um, dass die rechte Seite null ist.<br><br>Dividiere die Gleichung durch den Betrag des Normalenvektors.<br> | <br>$\begin{pmatrix}-3 \\ -1  \\ 2\end{pmatrix} \cdot \overrightarrow{x}=12 \quad \left\vert \ \begin{pmatrix}-3 \\ -1  \\ 2\end{pmatrix}\ \right\vert = \sqrt{14}$<br><br><br>Hesse'sche Normalenform:<br><br>$\displaystyle \frac{1}{\vert \ \sqrt{14} \ \vert}\ \left[ \ \begin{pmatrix}-3 \\ -1  \\ 2\end{pmatrix} \cdot \overrightarrow{x}- 12\right]=0$<br>$\quad$ |
| <br>Den Abstand des Punktes A zur Ebene E erhält man, indem die Koordinaten von A in die Hesse'sche Normalenform einsetzen und Betragsstriche ergänzen. | <br>Abstand berechnen:<br><br>$\displaystyle d(A,E)=\frac{1}{\vert \ \sqrt{14} \ \vert}\ \left\vert \ \begin{pmatrix}-3 \\ -1  \\ 2\end{pmatrix} \cdot \begin{pmatrix}9 \\ -3  \\ 2\end{pmatrix}- 12 \ \right\vert = \frac{32}{\sqrt{14}} \approx 8.6$<br><br>Der Abstand beträgt rund $8.6$ LE.<br>$\quad$ |

^9c72bb

| Vorgehen | Berechnung |
| ---- | ---- |
| Bilde den Verbindungsvektor $\overrightarrow{X_{r}X_{s}}$ zwischen beliebigen Punkten<br><br>$\qquad \qquad \overrightarrow{X}_{r}=\begin{pmatrix}-2+2r \\ -7+3r  \\ 9-4r\end{pmatrix}$<br>und <br>$\qquad \qquad \overrightarrow{X}_{s}=\begin{pmatrix}29-s \\ -9  \\ -5+4s\end{pmatrix}$<br><br>der Geraden $g_1$ bzw. $g_2$.<br>Setze das Skalarprodukt von $\overrightarrow{X_{r}X_{s}}$ mit dem Richtungsvektor von $g_1$ und mit dem von $g_2$ jeweils gleich null.<br>Es ergibt sich ein Gleichungssystem mit 2 Gleichungen 2 Variablen.<br>Ermittle die Lösung<br>$\quad$ | <br>Parameter bestimmen:<br>$\overrightarrow{X_{r}X_{s}}=\overrightarrow{X}_{s} \ -\overrightarrow{X}_r=\begin{pmatrix}31-2r-s \\ -2-3r  \\ -14+4r+4s\end{pmatrix}$<br><br>$\begin{pmatrix}31-2r-s \\ -2-3r  \\ -14+4r+4s\end{pmatrix} \cdot \begin{pmatrix}2 \\ 3 \\ -4\end{pmatrix}=0$<br><br>Gleichung I: $-29r-18s=-112$<br><br><br>$\begin{pmatrix}31-2r-s \\ -2-3r  \\ -14+4r+4s\end{pmatrix} \cdot \begin{pmatrix}-1 \\ 0 \\ 4\end{pmatrix}=0$<br><br>Gleichung II: $\quad18r+17s=87$<br>Lösung: $\qquad \qquad r=2$ und $s=3$ |
| <br>Setze $r=2$ und $s=3$ in den Verbindungsvektor ein und berechne dem gemeinsamen Lotvektor.<br><br> | <br>Lotvektor und Fußpunkte bestimmen:<br><br>$\overrightarrow{X_{2}X_{3}}=\begin{pmatrix}31-2\cdot 2-3 \\ -2-3\cdot 2  \\ -14+4\cdot 2+4\cdot 3\end{pmatrix}=\begin{pmatrix}24 \\ -8  \\ 6\end{pmatrix}$<br><br>$\overrightarrow{OF}_{1}=\begin{pmatrix}-2 \\ -7  \\ 9\end{pmatrix}+2\cdot \begin{pmatrix}2 \\ 3  \\ -4\end{pmatrix}=\begin{pmatrix}2 \\ -1  \\ 1\end{pmatrix} \qquad F_{1}(2\mid -1\mid 1)$<br><br>$\overrightarrow{OF}_{2}=\begin{pmatrix}29 \\ -9  \\ -5\end{pmatrix}+3\cdot \begin{pmatrix}-1 \\ 0  \\ 4\end{pmatrix}=\begin{pmatrix}26 \\ -9  \\ 7\end{pmatrix} \qquad F_{1}(26\mid -9\mid 7)$<br>$\quad$ |
| <br>Berechne den Betrag des gemeinsamen Lotvektors $\overrightarrow{X_{2}X_{3}}$. | <br>Abstand berechnen:<br><br>$\displaystyle d(g_1,g_2) =\ \left \vert \ \begin{pmatrix}24 \\ -8  \\ 6\end{pmatrix} \  \right \vert \\ = \sqrt{676} =26$<br>$\quad$ |

^5238a0

