---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Definition
>Gegeben ist eine Gerade $g:\overrightarrow{x}=\overrightarrow{p}+t \cdot \overrightarrow{u}$ und eine Ebene $E:\overrightarrow{x}=\overrightarrow{q}+r \cdot \overrightarrow{v}+s \cdot \overrightarrow{w}$.
>Falls die Gleichung $\overrightarrow{p}+t \cdot \overrightarrow{u}=\overrightarrow{q}+r \cdot \overrightarrow{v}+s \cdot \overrightarrow{w}$
>- genau eine Lösung hat, **schneiden** sich die Gerade g und die Ebene E.
>- keine Lösung hat, sind die Gerade g und die Ebene E **zueinander parallel**.
>- unendlich viele Lösungen hat, **liegt** die Gerade g **in der Ebene E**.
>
> 
>>[!info] Graphische Darstellung
>>  ![[Pasted image 20240101151009.png]]

<br>

___
# Beispiel

>[!write] Lage von Geraden zu einer Ebene bestimmt
>Untersuche die Lagebeziehungen der Ebene E zu den drei Geraden $g_{1}, g_{2}$ und $g_3$.
>
>$E:\overrightarrow{x}=\begin{pmatrix}1 \\ 2  \\ 3\end{pmatrix}+r \cdot \begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+ s \cdot \begin{pmatrix}0 \\ 1  \\ 0\end{pmatrix}$
>
>$g_{1}:\overrightarrow{x}=\begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+t \cdot \begin{pmatrix}2 \\ 1  \\ 0\end{pmatrix}$
>
>$g_{2}:\overrightarrow{x}=\begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+t \cdot \begin{pmatrix}1 \\ 1  \\ 1\end{pmatrix}$
>
>$g_{3}:\overrightarrow{x}=\begin{pmatrix}2 \\ 2  \\ 4\end{pmatrix}+t \cdot \begin{pmatrix}1 \\ 1  \\ 1\end{pmatrix}$

<br>

>[!success]- Lösung
>Um die gemeinsamen Punkte zu ermitteln, löst man die Vektorgleichung $\overrightarrow{x_{g}}=\overrightarrow{x_{E}}$.
>
>$\overrightarrow{x_{g_{1}}}=\overrightarrow{x_{E}}$
>
>$\overrightarrow{x}=\begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+t \cdot \begin{pmatrix}2 \\ 1  \\ 0\end{pmatrix}=\begin{pmatrix}1 \\ 2  \\ 3\end{pmatrix}+r \cdot \begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+ s \cdot \begin{pmatrix}0 \\ 1  \\ 0\end{pmatrix}$
>
>Also:
>Mithilfe des GTR erhält man die Lösung $t=-1$ und kann damit den Durchstoßpunkt D$(-1\mid -1\mid 1)$ berechnen.
>
>
>$\overrightarrow{x_{g_{2}}}=\overrightarrow{x_{E}}$
>
>$\overrightarrow{x}=\begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+t \cdot \begin{pmatrix}1 \\ 1  \\ 1\end{pmatrix}=\begin{pmatrix}1 \\ 2  \\ 3\end{pmatrix}+r \cdot \begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+ s \cdot \begin{pmatrix}0 \\ 1  \\ 0\end{pmatrix}$
>
>Also:
>Der GTR liefert, dass es keine Lösung gibt.
>Die Gerade $g_{2}$ liegt parallel zur Ebene E.
>
>
>$\overrightarrow{x_{g_{3}}}=\overrightarrow{x_{E}}$
>
>$\overrightarrow{x}=\begin{pmatrix}2 \\ 2  \\ 4\end{pmatrix}+t \cdot \begin{pmatrix}1 \\ 1  \\ 1\end{pmatrix}=\begin{pmatrix}1 \\ 2  \\ 3\end{pmatrix}+r \cdot \begin{pmatrix}1 \\ 0  \\ 1\end{pmatrix}+ s \cdot \begin{pmatrix}0 \\ 1  \\ 0\end{pmatrix}$
>
>Also:
>Der GTR liefert unendlich viele Lösungen.
>Mit $t=c3$ erhält man als Lösung die Gerade $g_{3}$.
>Die Gerade $g_{3}$ liegt in der Ebene E.

<br>

