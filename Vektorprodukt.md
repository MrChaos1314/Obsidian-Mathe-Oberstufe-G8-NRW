---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Vektorprodukt
>Lotvektor:
>Ein Lotvektor ist ein Vektor, der orthogonal auf etwas steht, wie bspw. auf einem anderen Vektor.
>
>$\qquad \qquad \overrightarrow{a} \times \overrightarrow{b}= \begin{pmatrix}a_1 \\ a_2  \\ a_3\end{pmatrix} \times \begin{pmatrix}b_1 \\ b_2  \\ b_3\end{pmatrix}=\begin{pmatrix}a_2b_{3}-a_{3}b_{2} \\ a_3b_{1}-a_{1}b_{3}  \\ a_1b_{2}-a_{2}b_{1}\end{pmatrix}$ 
>
>heißt **Vektorprodukt** von $\overrightarrow{a}$ und $\overrightarrow{b}$.
>
>Sind $\overrightarrow{a} \neq \overrightarrow{O}$ und $\overrightarrow{b} \neq \overrightarrow{O}$ nicht kollinear, so ist der Vektor $\overrightarrow{a} \times \overrightarrow{b}$ orthogonal zu
> $\overrightarrow{a}$ und zu $\overrightarrow{b}$.

<br>

___
# Beispiel

>[!write] Aufgabe
>Ermittle einen Vektor mit ganzzahligen Koordinaten von möglichst kleinem Betrag, der zu $\overrightarrow{a}=\begin{pmatrix}3 \\ 2  \\ -4\end{pmatrix}$ und zu $\overrightarrow{b}=\begin{pmatrix}1 \\ -2  \\ 2\end{pmatrix}$ orthogonal ist. 
>Mach die Probe.

<br>

>[!success]- Lösung
>![[Vektorprodukt#^9aae21]]

<br>

___
# Annotation

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Berechne das Vektorprodukt mithilfe der Definition.<br>Der Ergebnisvektor hat ganzzahlige Koordinaten und ist orthogonal zu $\overrightarrow{a}$ und $\overrightarrow{b}$. | <br>$\begin{align*}\begin{pmatrix}3 \\ 2  \\ -4\end{pmatrix} \times \begin{pmatrix}1 \\ -2  \\ 2\end{pmatrix} &=\begin{pmatrix}2 \cdot 2-(-4) \cdot (-2) \\ (-4) \cdot 1 - 3 \cdot 2  \\ 3 \cdot (-2)-2 \cdot 1\end{pmatrix} \\ \\ &= \begin{pmatrix}-4 \\ -10  \\ -8\end{pmatrix}\end{align*}$<br><br><br>$\quad$ |
| <br>"Kürze" seine Koordinaten möglichst weit.<br> | <br>$\overrightarrow{n}=\begin{pmatrix}2 \\ 5  \\ 4\end{pmatrix}$<br>$\qquad$ |
| <br>Überprüfe zur Probe, ob die Skalarprodukte von $\overrightarrow{a}$  &nbsp; und &nbsp;  $\overrightarrow{b}$  &nbsp; mit &nbsp; $\overrightarrow{n}$ &nbsp; jeweils 0 ergeben. | <br>$\overrightarrow{a} \cdot \overrightarrow{n}=\begin{pmatrix}3 \\ 2  \\ -4\end{pmatrix} \cdot \begin{pmatrix}2 \\ 5 \\ 4\end{pmatrix}=6+10-16=0$<br><br>$\overrightarrow{b} \cdot \overrightarrow{n}=\begin{pmatrix}1 \\ -2  \\ 2\end{pmatrix} \cdot \begin{pmatrix}2 \\ 5 \\ 4\end{pmatrix}=2-10+8=0$<br>$\qquad$ |

^9aae21

