---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Analytische Geometrie|Zurück]]

___
# Definition

>[!hint] Parametergleichung einer Ebene
>Ist A ein Punkt einer Ebene E und sind $\overrightarrow{u}$ und $\overrightarrow{v}$ zwei nicht kollineare Vektoren in Richtung der Ebene, dann lässt sich die Ebene beschreiben durch die Parametergleichung
>
>$\qquad \qquad \qquad \overrightarrow{x}=\overrightarrow{OA}+r \cdot \overrightarrow{u}+s \cdot \overrightarrow{v} \qquad (r, s \in \mathbb{R},\ \overrightarrow{u} \neq \overrightarrow{o},\ \overrightarrow{v} \neq \overrightarrow{o}\ \ )$.
>
>- Der **Stützvektor** $\overrightarrow{OA}$ oder auch $\overrightarrow{p}$ &nbsp; ist der Ortsvektor des **Stützpunktes** A.
>- $\overrightarrow{u}$ und $\overrightarrow{v}$ sind **Richtungsvektoren** der Ebene, sind nicht zueinander parallel und heißen **Spannvektoren**.
>- Für jedes Wertepaar der **Parameter** r und s erhält man den Ortsvektor $\overrightarrow{x}$ eines Punktes X der Ebene.
>
>Die Parametergleichung einer Ebene ist nicht eindeutig bestimmt.
>Als Stützpunkt kann man jeden Punkt der Ebene wählen und als Richtungsvektor zwei beliebige nicht kollineare Vektoren, deren Vektorpfeil sich in die Ebene legen lassen.
>
>>[!info] Grafik
>>![[Pasted image 20240101135312.png|450]]

<br>

___
# Beispiel

>[!write] Ebene durch drei Punkte
>Prüfe, ob die Punkte A$(1\mid -5\mid 1)$, B$(3\mid 1\mid 0)$ und C$(0\mid 4\mid -8)$ eine Ebene aufspannen.
>Falls ja, gebe eine Parametergleichung der Ebene an.

<br>

>[!success]- Lösung
>![[Ebenen#^e3a525]]

<br>

>[!write] Punktprobe
>Prüfe, ob der Punkt in der Ebene 
>
>$E: \overrightarrow{x}=\begin{pmatrix}2 \\ 0  \\ -5\end{pmatrix}+r \begin{pmatrix}-1 \\ 2  \\ 1\end{pmatrix}+s \begin{pmatrix}3 \\ -1  \\ -1\end{pmatrix}$
>liegt.
>
>- P$(-4\mid 7\mid -1)$

<br>

>[!success]- Lösung
>![[Ebenen#^7e3463]]

<br>

___
# Annotation

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Bilde die beiden Richtungsvektoren $\overrightarrow{AB}$ und $\overrightarrow{AC}$ und prüfe, ob diese kollinear sind. | <br>$\overrightarrow{AB}=\begin{pmatrix}3-1 \\ 1+5  \\ 0-1\end{pmatrix}=\begin{pmatrix}2 \\ 6  \\ -1\end{pmatrix}$<br><br>$\overrightarrow{AC}=\begin{pmatrix}0-1 \\ 4+5  \\ -8-1\end{pmatrix}=\begin{pmatrix}-1 \\ 9  \\ -9\end{pmatrix}$<br>$\quad$ |
| <br>Sind $\overrightarrow{AB}$ und $\overrightarrow{AC}$ nicht kollinear, so legen die Punkte A, B und C eine Ebene fest.<br>$\quad$ | <br>$\overrightarrow{AC}$ ist kein Vielfaches von $\overrightarrow{AB}$, also sind die beiden Vektoren nicht kollinear.<br> |
| <br>Wähle zum Beispiel als Stützpunkt den Punkt A und $\overrightarrow{AB}$ und $\overrightarrow{AC}$ als Richtungsvektoren.<br>Stelle damit die Parametergleichung der Ebene auf.<br>$\quad$  | <br>$\begin{align*}E:\overrightarrow{x}&= \overrightarrow{OA}+r \cdot \overrightarrow{AB}+ s \cdot \overrightarrow{AC} \\ &= \begin{pmatrix}1 \\ -5  \\ 1\end{pmatrix}+r \begin{pmatrix}2 \\ 6  \\ -1\end{pmatrix}+s \begin{pmatrix}-1 \\ 9  \\ -9\end{pmatrix} \end{align*}$ |

^e3a525

| Vorgehen | Rechnung |
| ---- | ---- |
| P liegt in E, wenn $\overrightarrow{OP}$ Ortsvektor eines Ebenenpunktes ist:<br>$\overrightarrow{OP}=\overrightarrow{OA}+r \cdot \overrightarrow{u}+s \cdot \overrightarrow{v}$<br>Es ergibt sich ein lineares Gleichungssystem aus drei Gleichungen für r und s.<br>Bringe das LGS auf Zeilenstufenform und prüfe, ob es lösbar ist.<br> | <br>$\begin{pmatrix}-4 \\ 7  \\ -1\end{pmatrix}=\begin{pmatrix}2 \\ 0  \\ -5\end{pmatrix}+r\begin{pmatrix}-1 \\ 2  \\ 1\end{pmatrix}+s\begin{pmatrix}3 \\ -1  \\ -1\end{pmatrix}$<br><br>$\left(\begin{array}{cc \| c}-1&3&-6 \\ 2&-1&7  \\ 1&-1&4\end{array}\right)$ $\underrightarrow{ZSF}$ $\left(\begin{array}{cc \| c}-1&3&-6 \\ 0&5&-5  \\ 0&0&0\end{array}\right)$<br><br>Das LGS ist lösbar, P liegt in E.<br>$\quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad$ |
| <br>Zur Probe kann man r und s berechnen und in die Ebenengleichung einsetzen. | <br>Probe mit $r=3$ und $s=-1$:<br><br>$\begin{pmatrix}-4 \\ 7  \\ -1\end{pmatrix}=\begin{pmatrix}2 \\ 0  \\ -5\end{pmatrix}+3 \cdot \begin{pmatrix}-1 \\ 2  \\ 1\end{pmatrix} + (-1) \cdot \begin{pmatrix}3 \\ -1  \\ -1\end{pmatrix}$<br>$\quad$ |

^7e3463
