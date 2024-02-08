---
cssclasses: hide_properties
tags: [Formel]
---

>[!hint] Definition
>Als **Winkel zwischen einer Ebene und einer Geraden** bezeichnet man den Winkel zwischen der Geraden und ihrer senkrechten Projektion in die Ebene.
>
>Der Normalenvektor $\overrightarrow{n}$ legt die Richtung der Ebene E fest.
>Die Richtung der Geraden g wird durch den Richtungsvektor $\overrightarrow{u}$ beschrieben.
>Der Winkel $\alpha$ zwischen E und g ergänzt sich mit dem Winkel zwischen $\overrightarrow{n}$ und der Geraden zu 90°.
>
>Es gilt: $\displaystyle \qquad cos(90°-\alpha )= \frac{\vert \ \overrightarrow{n} \cdot \overrightarrow{u} \ \vert}{\vert \ \overrightarrow{n} \ \vert \cdot \vert \ \overrightarrow{u}\ \vert}$.
>
>Mit $cos(90°-\alpha)=sin(\alpha )$ ergibt sich eine Formel für $\alpha$
>
>
>Für den Winkel zwischen einer Ebene E mit dem Normalenvektor $\overrightarrow{n}$ und einer Geraden g mit dem Richtungsvektor $\overrightarrow{u}$ gilt:
>
>$\qquad \qquad \displaystyle sin(\alpha )=\frac{\vert \ \overrightarrow{n} \cdot \overrightarrow{u} \ \vert}{\vert \ \overrightarrow{n} \ \vert \cdot \vert \ \overrightarrow{u} \ \vert} \qquad (0° \leq \alpha \leq 90°)$
>
>
>
>>[!info]- Graphische Darstellung
>>![[Pasted image 20240102210138.png]]
>>![[Pasted image 20240102210652.png]]

<br>

___
# Beispiel

>[!write] Aufgabe
>Berechne den Winkel zwischen der Ebene E und der Geraden g.
>
>$\qquad \qquad E:x_{1}-2x_{2}+x_{3}=5$
>
>$\qquad \qquad g:\overrightarrow{x}=\begin{pmatrix}2 \\ 1  \\5\end{pmatrix}+t \begin{pmatrix}0 \\ 1  \\ -1\end{pmatrix}$.

<br>

>[!success]- Lösung
>![[Winkel zwischen einer Ebene und einer Geraden#^6cacf0]]

<br>

___
# Annotationen

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Lese aus der Koordinatengleichung der Ebene einen Normalenvektor $\overrightarrow{n}$ ab und berechne damit $sin(\alpha)$.<br><br><br><br><br>Mit der Taste $sin^{-1}$ auf dem Taschenrechner erhält man einen Näherungswert für den Winkel $\alpha$<br> | <br>$\overrightarrow{n}=\begin{pmatrix}1 \\ -2  \\ 1\end{pmatrix} \qquad \overrightarrow{u}=\begin{pmatrix}0 \\ 1  \\ -1\end{pmatrix}$<br><br>$sin(\alpha)=\frac{\vert \ \overrightarrow{u} \cdot \overrightarrow{v} \ \vert}{\vert \ \overrightarrow{u} \ \vert \cdot \vert \ \overrightarrow{v} \ \vert}=\frac{\vert \ 1 \cdot 0-2 \cdot 1+1 \cdot (-1) \ \vert}{\sqrt{6} \cdot \sqrt{2}} \approx 0.866$<br><br>$\alpha \approx sin^{-1}(0.866)\approx 30°$<br><br>Der Winkel zwischen E und g beträgt etwa 30°.<br>$\quad$ |

^6cacf0

