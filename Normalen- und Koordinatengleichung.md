---
cssclasses: hide_properties
tags: [GK, Unterthema, Fragen]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Definition
>Jede Ebene E lässt sich beschreiben durch
>
>- eine **Normalengleichung** $(\overrightarrow{x}-\overrightarrow{p})\cdot \overrightarrow{n}=0$
>  mit einem Stützvektor $\overrightarrow{p}$ und einem Normalenvektor $\overrightarrow{n},$ mit $\overrightarrow{n} \neq \overrightarrow{o}$.
>
>- eine **Koordinatengleichung** $ax_{1}+bx_{2}+cx_{3}=d$, wobei $d=\overrightarrow{p} \cdot \overrightarrow{n}$, bei der mindestens einer der Koeffizienten a, b, c ungleich null ist.
>
>Ist $ax_{1}+bx_{2}+cx_{3}=d$ eine Koordinatengleichung der Ebene E, so ist $\begin{pmatrix}a \\ b  \\ c\end{pmatrix}$ ein **Normalenvektor** der Ebene E.

<br>

___
# Beispiel

>[!write] Normalengleichung und Koordinatengleichung aufstellen
>Eine Ebene durch P$(4\mid 1\mid 3)$ hat den Normalenvektor $\overrightarrow{n}=\begin{pmatrix}2 \\ -1  \\ 5\end{pmatrix}$.
>
>- Gebe eine Normalengleichung der Ebene an.
>- Bestimme aus der Normalengleichung eine Koordinatengleichung der Ebene
>- Liegt der Punkt A$(1\mid 1\mid 1)$ in der Ebene?

<br>

>[!success]- Lösung
>- Einsetzen von $\overrightarrow{p}=\overrightarrow{OP}$ und $\overrightarrow{n}$ in $(\overrightarrow{x}-\overrightarrow{p})\cdot \overrightarrow{n}=0$ ergibt:
>
>Ebenengleichung in Normalenform: $\displaystyle \left[\overrightarrow{x}-\begin{pmatrix}4 \\ 1  \\ 3\end{pmatrix}\right]\cdot \begin{pmatrix}2 \\ -1  \\ 5\end{pmatrix}=0$.
>
>- Mit dem Normalenvektor $\overrightarrow{n}=\begin{pmatrix}2 \\ -1  \\ 5\end{pmatrix}$ ergibt sich für die Koordinatengleichung der Ansatz $E:2x_{1}-1x_{2}+5x_{3}=d$ mit $d=\overrightarrow{p} \cdot \overrightarrow{n}$.
>
>Den Wert für d berechnet man, indem man für $x_{1}, x_{2}$ und $x_{3}$ die Koordinaten des Punktes P$(4\mid 1\mid 3)$:
>$d=2 \cdot 4-1 \cdot 1 + 5 \cdot 3= 22$
>Koordinatengleichung: $E:2x_{1}-1x_{2}+5x_{3}=22$.
>
>- $2 \cdot 1-1 \cdot 1 + 5 \cdot 1= 6 \neq 22$. Der Punkt A liegt nicht in der Ebene.

<br>

>[!write] Aufstellen einer Koordinatengleichung
>Die Punkte A$(1.2\mid 2.6\mid 3.3)$, B$(1.1\mid 0\mid 1.5)$ und C$(0\mid 1.7\mid 1.99)$ legen eine Ebene E fest.
>- Bestimme eine Koordinatengleichung dieser Ebene E.

<br>

>[!success]- Lösung
>Man setzt in die Koordinatengleichung $ax_{1}+bx_{2}+cx_{3}=d$ nacheinander die Koordinaten der Punkte A, B und C ein.
>Man erhält das folgende LGS:
>
>$\begin{align*}1.2a+2.6b+3.3c-d&=0 \\ 1.1a+0+1.5c-d&=0 \\ 0+1.7b+1.9c-d&=0\end{align*}$
>
>Gerundet erhält man $1c-1.17d=0$.
>Wählt man $d=1$, ist $c\approx 1.17, b\approx -0.79$ und $a\approx -0.69$.
>Man erhält die Koordinatengleichung als Näherungslösung:
>$-0.69x_{1}-0.79x_{2}+1.17x_{3}\approx 1$.

<br>


>[!write] Von der Parametergleichung zur Koordinatengleichung
>Die Ebene E kann mit der Parametergleichung $E: \overrightarrow{x}=\begin{pmatrix}2 \\ 1  \\ 5\end{pmatrix}+r \cdot \begin{pmatrix}1 \\ -1  \\ 0\end{pmatrix} +s \cdot \begin{pmatrix}1 \\ -3  \\ 4\end{pmatrix}$ beschrieben werden.
>- Bestimme eine Koordinatengleichung von E.

<br>

>[!success]- Lösung
>Ein Normalenvektor $\overrightarrow{n}=\begin{pmatrix}n_1 \\ n_2  \\ n_3\end{pmatrix}$ muss zu den Spannvektoren $\begin{pmatrix}1 \\ -1  \\ 0\end{pmatrix}$ und $\begin{pmatrix}1 \\ -3  \\ 4\end{pmatrix}$ orthogonal sein, also ist 
>
>$\begin{pmatrix}1 \\ -1  \\ 0\end{pmatrix} \times \begin{pmatrix}1 \\ -3  \\ 4\end{pmatrix}=\begin{pmatrix}-4 \\ -4  \\ -2\end{pmatrix}$
>
>Ansatz für die Koordinatengleichung: $E: -4x_{1}-4x_{2}-2x_{3}=d$.
>Man berechnet d indem man für $x_{1}, x_{2}$ und $x_3$ die Koordinaten des Stützvektors von E einsetzt:
>$d=-4 \cdot 2-4 \cdot 1-2 \cdot 5=-22$.
>Koordinatengleichung: $E:-4x_{1}-4x_{2}-2x_{3}=-22$

<br>%%Fragen%%

___
# Übersicht besonderer Ebenen

>[!info] Übersicht
>![[Pasted image 20240102123943.png]]

<br>
