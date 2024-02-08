---
cssclasses: hide_properties
tags: [Formel]
---

# [[Winkel - Analytische Geometrie|Zurück]]

___
<br>

>[!hint] Definition
>Für den Winkel $\alpha$ zwischen den Vektoren $\overrightarrow{a}$ und $\overrightarrow{b}$ gilt:
>
>$\overrightarrow{a}\cdot \overrightarrow{b}=\vert \  \overrightarrow{a} \ \vert \cdot \vert \ \overrightarrow{b}\ \vert \cdot cos(\alpha)$ bzw. $\displaystyle cos(\alpha ) = \frac{\overrightarrow{a}\cdot \overrightarrow{b}}{\vert \  \overrightarrow{a} \ \vert \cdot \vert \ \overrightarrow{b}\ \vert}$ mit $\displaystyle 0° \leq \alpha \leq 180°$.

<br>

___
# Beispiel

>[!write] Aufgabe
>Berechne den Winkel zwischen $\overrightarrow{a}=\begin{pmatrix}-2 \\ 6  \\ 4\end{pmatrix}$ und $\overrightarrow{b} \begin{pmatrix}3 \\ -1  \\ -1\end{pmatrix}$.

<br>

>[!success]- Lösung
>

<br>

___

# Annotationen

| Vorgehen | Berechnung |
| --- | --- |
| <br>In der Formel für $cos(\alpha)$ steht im Zähler das Skalarprodukt von <br>$\overrightarrow{a}$ und $\overrightarrow{b}$. <br>Das Produkt der Beträge im Nenner ist das Produkt zweier Wurzeln.<br>Berechne mit dem Taschenrechner einen Näherungswert für $cos(\alpha)$.<br>Mit der Taste $cos^{-1}$ erhält man den Wert des Winkels zwischen $\overrightarrow{a}$ und $\overrightarrow{b}$.  | <br>$\displaystyle \begin{align*}cos(\alpha)&=\frac{\overrightarrow{a} \cdot \overrightarrow{b}}{\vert \ \overrightarrow{a} \ \vert \cdot \vert \ \overrightarrow{b} \ \vert}\\ \\ &=\frac{\begin{pmatrix}-2 \\ 6  \\ 4\end{pmatrix} \cdot \begin{pmatrix}3 \\ 1  \\ -1\end{pmatrix}}{\sqrt{(-2)^{2}+6^{2}+4^{2}} \cdot \sqrt{3^{2}+1^{2}+(-1)^{2}}}\\ \\ &=\frac{-6+6-4}{\sqrt{56} \cdot \sqrt{11}}\\ \\ &=\frac{-4}{\sqrt{56} \cdot \sqrt{11}} \approx -0.161\end{align*}$<br><br>$\alpha \approx cos^{-1}(-0.161)\approx 99.3°$<br>$\quad$ |
