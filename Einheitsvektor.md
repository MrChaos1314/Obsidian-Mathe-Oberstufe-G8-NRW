---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Definition
>Um den Einheitsvektor eines beliebig langen Vektors zu ermitteln, muss man nur
>- die Länge und
>- die Komponenten des Vektors (x, y)
>
>kennen.
>Betrachtet man die Abbildung, so ist klar, dass ein Vektor mit der Länge 5 sich aus 5 Einheitsvektoren zusammen setzen lässt.
>Ein Vektor mit der Länge 6 lässt sich aus 6 Einheitsvektoren zusammen setzen, usw.
>
>>[!info] Abbildung
>>![[Pasted image 20240101202317.png|250]]
>
>
>Um nun den Einheitsvektor zu berechnen zu können müssen nur die einzelnen Komponenten (x,y) durch den Betrag des Vektors (=Länge) dividiert werden.
>
>$\overrightarrow{a}=\begin{pmatrix}4 \\ 3  \end{pmatrix}$
>$\vert \ \overrightarrow{a}\ \vert \ =\sqrt{4^{2}+3^{2}}=\sqrt{16+9}=\sqrt{25}=5$
>$\displaystyle \overrightarrow{e}_{a}=\begin{pmatrix}\frac{4}{\vert \ \overrightarrow{a}\ \vert \ } \\ \frac{3}{\vert \ \overrightarrow{a}\ \vert \ }\end{pmatrix}=\begin{pmatrix}\frac{4}{5} \\ \frac{3}{5} \end{pmatrix}=\begin{pmatrix}0.8 \\ 0.6 \end{pmatrix}$

<br>

___
# Beispiel

>[!write] Aufgabe
>Berechne vom Richtungsvektor $\overrightarrow{a}\begin{pmatrix}0 \\ -8  \\ 6\end{pmatrix}$ den Einheitsvektor $\overrightarrow{a}_0$ 

<br>

>[!success]- Lösung
>$\displaystyle \begin{align*} \overrightarrow{a}_{0}&=\frac{1}{\vert \ \overrightarrow{a}\ \vert \ } \cdot \overrightarrow{a}\\ \\ \overrightarrow{a}_{0} &=\frac{1}{\sqrt{x^{2}+y^{2}+z^{2}}} \cdot  \begin{pmatrix} x \\ y  \\ z \end{pmatrix} \\  \\  \overrightarrow{a}_{0}&=\frac{1}{\sqrt{0^{2}+(-8)^{2}+6^{2}}} \cdot    \begin{pmatrix}0 \\ -8  \\ 6\end{pmatrix}\\  \\  \overrightarrow{a}_{0}&=\frac{1}{\sqrt{0+64+36}} \cdot  \begin{pmatrix}0 \\ -8  \\ 6\end{pmatrix}=\frac{1}{\sqrt{100}} \cdot  \begin{pmatrix}0 \\ -8  \\ 6\end{pmatrix}\\  \\  \overrightarrow{a}_{0}&=\frac{1}{10} \cdot \begin{pmatrix}0 \\ -8  \\ 6\end{pmatrix}=\begin{pmatrix}0:10 \\ -8:10  \\ 6:10\end{pmatrix}=\begin{pmatrix}0 \\ -0.8  \\ 0.6\end{pmatrix}\end{align*}$

<br>
