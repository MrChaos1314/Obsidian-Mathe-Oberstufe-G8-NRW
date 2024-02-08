---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Normalenvektor
>Wenn die Gerade g und die Ebene E sich schneiden, kann zusätzlich untersucht werden, ob die Gerade orthogonal zur Ebene liegt.
>Dies ist der Fall, wenn der Richtungsvektor der Geraden zu beiden Spannvektoren der Ebene orthogonal ist.
>Man nennt einen solchen Vektor, der orthogonal zur Ebene E ist, einen **Normalenvektor** der Ebene E.
>
>Kennt man bereits einen Normalenvektor der Ebene E, so kann die gegenseitige Lage der Geraden g und der Ebene E mithilfe des Richtungsvektors $\overrightarrow{u}$ der Geraden g und des Normalenvektors $\overrightarrow{n}$ der Ebene E untersucht werden.
>- Wenn $\overrightarrow{u}$ und $\overrightarrow{n}$ Vielfache voneinander sind, schneidet die Gerade g die Ebene orthogonal (Abb.).
>- Wenn $\overrightarrow{u}$ und $\overrightarrow{n}$ zueinander orthogonal sind, liegt g in E oder g ist parallel zu E.
>  
>>[!info] Abbildung
>>![[Pasted image 20240101173017.png|300]]

<br>

___
# Lagebeziehungen mithilfe des Normalenvektors untersuchen

>[!hint] Lagebeziehungen
>Gegeben sind die Geraden 
>$\qquad \qquad \qquad g:\overrightarrow{x}=\begin{pmatrix}1 \\ 2  \\ 3\end{pmatrix}+ t \cdot \begin{pmatrix}1 \\ 2  \\ 0\end{pmatrix}$ 
>und 
>$\qquad  \qquad \qquad h:\overrightarrow{x}=\begin{pmatrix}2 \\ 3  \\ 5\end{pmatrix}+ t \cdot \begin{pmatrix}4 \\ -2  \\ -4\end{pmatrix}$
>sowie die Ebene
>$\qquad  \qquad \qquad E:\overrightarrow{x}=\begin{pmatrix}2 \\ -4  \\ 2\end{pmatrix}+ r \cdot \begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+s \cdot \begin{pmatrix}2 \\ -2  \\ 3\end{pmatrix}$.
>
>- Bestimmen des Normalenvektors zur Ebene E
>
>Der Vektor $\overrightarrow{n}=\begin{pmatrix}n_1 \\ n_2  \\ n_3\end{pmatrix}$ muss zu den Spannvektoren $\begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}$ und $\begin{pmatrix}2 \\ -2  \\ 3\end{pmatrix}$ orthogonal sein.
>
>Man verwendet das Vektorprodukt: 
>
>$\begin{pmatrix}1 \\ -1  \\ 0\end{pmatrix} \times \begin{pmatrix}1 \\ -3  \\ 4\end{pmatrix}=\begin{pmatrix}2 \\ -1  \\ -2\end{pmatrix}$
>
>$\overrightarrow{n}=\begin{pmatrix}2 \\ -1  \\ -2\end{pmatrix}$
>
>- Lagebeziehung untersuchen
>
>Das Skalarprodukt des Richtungsvektors von g mit $\overrightarrow{n}$ lautet: 
>
>$\begin{pmatrix}1 \\ 2  \\ 0\end{pmatrix}\cdot \begin{pmatrix}2 \\ -1  \\ -2\end{pmatrix}=0$. 
>
>Somit sind die Vektoren zueinander orthogonal.
>Die Gerade g liegt in der Ebene E oder ist parallel zu ihr.
>Die Punktprobe ergibt, dass der Geradenpunkt P$(1\mid 2\mid 3)$ nicht auf der Ebene E liegt.
>Also sind g und E zueinander parallel.
>
>Wegen $\begin{pmatrix}4 \\ -2  \\ -4\end{pmatrix}=2 \cdot \begin{pmatrix}2 \\ -1  \\ -2\end{pmatrix}$ sind die Richtungsvektoren von h und der Normalenvektor $\overrightarrow{n}$ Vielfache voneinander.
>Die Gerade h schneidet die Ebene E orthogonal.
 

<br>

___
