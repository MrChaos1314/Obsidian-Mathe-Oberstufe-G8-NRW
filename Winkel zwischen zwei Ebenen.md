---
cssclasses: hide_properties
tags: [Formel]
---

# [[Winkel - Analytische Geometrie|Zurück]]

___
<br>

>[!hint] Definition
>Zwei sich schneidende Ebenen $E_{1}$ und $E_{2}$ können im Querschnitt durch Geraden $g_{1}$ und $g_{2}$ dargestellt werden.
>Diese Geraden schneiden sich und verlaufen orthogonal zur Schnittgerade der Ebenen.
>Den Winkel $\alpha$ zwischen $g_{1}$ und $g_{2}$ bezeichnet man als **Winkel zwischen den Ebenen**.
>Dieser Winkel entspricht dem Winkel $\alpha'$ zwischen zwei Normalenvektoren.
>
>Für den Winkel $\alpha$ zwischen den Ebenen $E_{1}$ und $E_{2}$ mit den Normalenvektoren $\overrightarrow{n}_{1}$ und $\overrightarrow{n}_2$ gilt:
>
>$\qquad \qquad cos(\alpha)=\displaystyle  \frac{\vert \ \overrightarrow{n_1} \cdot \overrightarrow{n_2} \ \vert}{\vert \ \overrightarrow{n_1} \ \vert \cdot \vert \ \overrightarrow{n_2}\ \vert} \qquad (0° \leq \alpha \leq 90°)$
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20240102221707.png|500]]

<br>

___
# Beispiel

>[!write] Aufgabe
>Berechne den Winkel zwischen den Ebenen $E_1$ und $E_2$.
>
>$\qquad \qquad E_{1}:\overrightarrow{x}=\begin{pmatrix}2 \\ -1  \\4\end{pmatrix}+r \begin{pmatrix}1 \\ 1  \\ -1\end{pmatrix}+s \begin{pmatrix}-2 \\ 0  \\ 3\end{pmatrix}$
>
>$\qquad \qquad E_{2}:\overrightarrow{x} \cdot \begin{pmatrix}3 \\ 4  \\ 2\end{pmatrix}=\begin{pmatrix}1 \\ 0  \\1\end{pmatrix} \cdot \begin{pmatrix}3 \\ 4  \\ 2\end{pmatrix}$.

<br>

>[!success]- Lösung
>![[Winkel zwischen zwei Ebenen#^b42773]]

<br>

___
# Annotationen

| Vorgehen | Berechnung |
| --- | --- |
| <br>Bestimme Normalenvektoren beider Ebenen und berechne damit $cos(\alpha)$.<br>Mit der Taste $cos^{-1}$ auf dem Taschenrechner erhält man einen Näherungswert für den Winkel $\alpha$.<br> | <br>$\overrightarrow{n}_{1}=\begin{pmatrix}1 \\ 1  \\ -1\end{pmatrix} \times \begin{pmatrix}-2 \\ 0  \\ 3\end{pmatrix}=\begin{pmatrix}3 \\ -1  \\ 2\end{pmatrix} \quad \quad \overrightarrow{n}_2=\begin{pmatrix}3 \\ 4  \\ 2\end{pmatrix}$<br><br>$\displaystyle cos(\alpha)=\frac{9-4+4}{\sqrt{14} \cdot \sqrt{29}} \approx 0.4467$<br><br>$\alpha \approx cos^{-1}(0.4467)\approx 63.5°$<br>$\quad$ |

^b42773

