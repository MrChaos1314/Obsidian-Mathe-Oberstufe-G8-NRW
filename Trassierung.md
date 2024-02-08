---
cssclasses: hide_properties
tags: [Unterthema]
---

# [[Ganzrationale Funktionen|Zurück]]

___
# Definition

>[!hint] Definition
>Die Linienführung einer Straße oder eines Gleises - die sogenannte Trasse - lässt sich stückweise durch Funktionsgraphen beschreiben.
>
>Es gilt:
>- Der Übergang zwischen den Teilgraphen zweier Funktionen $f$ und $g$ an einer Stelle $a$ heißt **sprungfrei**, wenn $f(a)=g(a)$ gilt.
>  - Er heißt **knickfrei**, wenn zusätzlich $f'(a)=g'(a)$ gilt.
 >- **Krümmungsruckfrei**, wenn auch noch $f''(a)=g''(a)$ gilt.
 >$\quad$
 > ---
>  An der Übergangsstelle $x_0$ gilt für zwei Funktionen $s$ und $t$ allgemein:
>- Versatzfreiheit $\qquad \qquad \qquad \ \ s(x_0) = t(x_0)$
>- Knickfreiheit $\qquad \qquad \qquad \quad \ s'(x_0)=t'(x_0)$
>- Krümmungsruckfreiheit &nbsp; &nbsp; $\quad s''(x_0)=t''(x_0)$

<br>

___
# Beispiel

>[!write]+ Aufgabe
>- **Bestimme** eine **ganzrationale Funktion** **dritten Grades**, deren Graph die beiden Geraden in der Abbildung **knickfrei** verbindet.
>- **Prüfe**, ob die Übergänge auch **krümmungsruckfrei** sind.
>  
>  ![[Pasted image 20231227184430.png|400]]

<br>

>[!success]- Lösung
>![[Trassierung#^a5b1be]]

<br>

___
# Annotation

|  |  |
| ---- | ---- |
| Stelle die allgemeine Funktionsgleichung auf und bilde die Ableitungen | $f(x)=ax^3+bx^2+cx+d$<br>$f'(x)=2ax^2+2bx+x$ $f''(x)=6ax+2b$ |
| Stelle sämtliche Bedingungen auf.<br>Aus den Verbindungspunkten $A({\color{cyan}{0}} \mid 0)$ und $B({\color{orange}{2}}\mid \frac{2}{3})$ ergeben sich zwei Bedingungen.<br> | sprungfrei:<br>$f(0)=0:\qquad \qquad \qquad d=0$<br>$f(2)=\frac{2}{3}:\quad 8a+4b+2c=\frac{2}{3}$ |
| Ermittle die Steigungen der beiden Geraden und setze diese mit $f'({\color{cyan}{0}})$ bzw. $f'({\color{orange}{2}})$ gleich.<br>Somit sind die Übergänge knickfrei. | knickfrei:<br>$f'(0)=0:\qquad \qquad \ \qquad c=0$<br>$f'(2)=1:\qquad \quad 12a+4b=1$ |
| Berechne die Parameter und stelle die Funktionsgleichung auf | $\begin{vmatrix}8a+4b=\frac{2}{3}\\12a+4b=1\end{vmatrix} \Rightarrow \quad a=\frac{1}{12};\ b=0$<br><br>$f(x)=\frac{1}{12}x^3$ |
| Prüfe, ob auch die Werte der zweiten Ableitung an den Verbindungsstellen übereinstimmen. | $f''(0)=0$, d.h. im Ursprung ruckfrei.<br><br>$f''(2)=1 \neq 0$, d.h. im Punkt $B$ nicht ruckfrei.  |

^a5b1be

