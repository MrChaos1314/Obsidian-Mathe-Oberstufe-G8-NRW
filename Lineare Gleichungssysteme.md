#Wiederholung-EF #Unterthema 

# [[Ganzrationale Funktionen|Zurück zu ganzrationalen Funktionen]]

___
# Inhaltsverzeichnis - Lineares Gleichungssysteme

- [[Lineare Gleichungssysteme#Gleichsetzungsverfahren|Gleichsetzungsverfahren]]
- [[Lineare Gleichungssysteme#Einsetzungsverfahren|Einsetzungsverfahren]]
- [[Lineare Gleichungssysteme#Additionsverfahren|Additionsverfahren]]
- [[Lineare Gleichungssysteme#Gauß-Verfahren|Gauß-Verfahren]]
- [[Lineare Gleichungssysteme#Beispiel - Gauß-Verfahren als LGS und Matrix|Beispiel - Gauß-Verfahren als LGS und Matrix]]
- [[Lineare Gleichungssysteme#Unterbestimmte lineare Gleichungssysteme|Unterbestimmte lineare Gleichungssysteme]]
- [[Lineare Gleichungssysteme#Überbestimmte lineare Gleichungssysteme|Überbestimmte lineare Gleichungssysteme]]

___
# Verfahren des LGSs - Zwei Variablen

## Gleichsetzungsverfahren

>[!hint]+ Gleichsetzungsverfahren
>$(1)$ $2x+4y=6$
>$(2)$ $5x+3y=1$
>
>$(1)$ $y=-\frac{1}{2}x+\frac{3}{2}$
>$(2)$ $y=-\frac{5}{3}x+\frac{1}{3}$
>
>gleichsetzen
>
>- $-\frac{1}{2}x+\frac{3}{2}=-\frac{5}{3}x+\frac{1}{3}$
>
>Auflösen nach $x$ liefert: 
>- $x=-1$
>
>Einsetzen von $x=-1$ in $(1)$: 
>- $2*(-1)+4y=6$
>  
>Auflösen nach $y$ liefert:
> 
>- $y=2$ 
>
>Die Lösung des LGS lautet: 
>- $x=-1$ und $y =2$
>  
>Probe durch Einsetzen in $(2)$: 
>- $5*(-1)+3*2=1$

<br>

## Einsetzungsverfahren

>[!hint]+ Einsetzungsverfahren
>$(1)$ $2x+4y=6$
>$(2)$ $5x+3y=1$
>
>$(1)$ $y=-\frac{1}{2}x+\frac{3}{2}$
>$(2)$ $5x+3y=1$
>
>einsetzen
>
>- $5x+3*(-\frac{1}{2}x+\frac{3}{2})=1$
>
>Auflösen nach $x$ liefert: 
>- $x=-1$
>
>Einsetzen von $x=-1$ in $(1)$: 
>- $2*(-1)+4y=6$
>  
>Auflösen nach $y$ liefert:
> 
>- $y=2$ 
>
>Die Lösung des LGS lautet: 
>- $x=-1$ und $y =2$
>  
>Probe durch Einsetzen in $(2)$: 
>- $5*(-1)+3*2=1$
>

<br>

## Additionsverfahren

>[!hint]+ Additionsverfahren
>$(1)$ $2x+4y=6 | *3$
>$(2)$ $5x+3y=1 | *3$
>
>$(1)$ $6x+12y=18$
>$(2)$ $-20x-12y=-4$
>
>addieren
>
>- $-14x=14$
>
>Auflösen nach $x$ liefert: 
>- $x=-1$
>
>Einsetzen von $x=-1$ in $(1)$: 
>- $2*(-1)+4y=6$
>  
>Auflösen nach $y$ liefert:
> 
>- $y=2$ 
>
>Die Lösung des LGS lautet: 
>- $x=-1$ und $y =2$
>  
>Probe durch Einsetzen in $(2)$: 
>- $5*(-1)+3*2=1$

<br>

___
# [[Analytische Geometrie|Zurück zu Analytische Geometrie]]

___
# Gauß-Verfahren

![[Pasted image 20231227021932.png|200]]

<br>

>[!hint] Wissen
>Die folgenden Umformungen ändern die Lösungsmenge eines linearen Gleichungssystems nicht.
>- Zwei Gleichungen werden vertauscht.
>- Eine Gleichung wird mit einer Zahl $c\neq 0$ multipliziert.
>- Eine Gleichung wird durch die Summe/Differenz dieser Gleichung mit einer anderen Gleichung ersetzt.
>
>Ein lineares Gleichungssystem kann keine, genau eine oder unendlich viele Lösungen haben.
>Die Art der Lösungsmenge erkennt man an der Zeilenstufenform:
>- Es gibt eine Widerspruchszeile → keine Lösung
>- Keine Widerspruchszeile und die Anzahl der verbliebenen Gleichungen ist gleich der Anzahl der Variablen → eindeutige Lösung 
>- Keine Widerspruchszeile und mehr Variablen als Gleichung (ohne Nullzeile) → unendlich viele Lösungen

<br>

___
# Beispiel - Gauß-Verfahren als LGS und Matrix

>[!write] Aufgabe
>Bestimme die Lösung des linearen Gleichungssystems.
>
>$\qquad \qquad \qquad \begin{vmatrix}&\ &8y\ +\ &3z &=-1 \\ &-2x\ +\ &6y\ +\ &3z&=-3  \\ &x\ +\ &y \ -\ &z&=-4\end{vmatrix}$

<br>

>[!success]- Lösung
>![[Pasted image 20240101113038.png]]

<br>

>[!write] Aufgabe
>Bestimme die Lösungsmenge des linearen Gleichungssystems.
>
>a) $\qquad \qquad \qquad \begin{vmatrix}&\ &8y\ +\ &3z &=-1 \\ &-2x\ +\ &6y\ +\ &3z&=-3  \\ &x\ +\ &y \ -\ &z&=-4\end{vmatrix}$
>
>b) $\qquad \qquad \qquad \begin{vmatrix}&\ &8y\ +\ &3z &=-1 \\ &-2x\ +\ &6y\ +\ &3z&=-3  \\ &x\ +\ &y \ -\ &z&=-4\end{vmatrix}$

<br>

>[!success]- Lösung
>![[Pasted image 20240101115802.png]]

<br>

___
# Unterbestimmte lineare Gleichungssysteme

>[!hint] Definition
>Ein lineares Gleichungssystem mit weniger Gleichungen als Variablen heißt **unterbestimmt**.
>Ein unbestimmtes LGS kann nie eindeutig lösbar sein.
>

<br>

>[!write] Beispiele
>$\begin{align*}x_{1}+x_{2}+x_{3}&=1\\ x_{1}+x_{2}+x_{3}&=2\end{align*}$
>
>Das LGS hat keine Lösung.
>
>--- 
>
>$\begin{align*}x_{1}+x_{2}+x_{3}&=1\\ x_{1}+x_{2}+x_{3}&=1\end{align*}$
>
>Das LGS hat unendlich viele Lösungen.

<br>

___
# Überbestimmte lineare Gleichungssysteme

>[!hint] Definition
>Ein lineares Gleichungssystem mit mehr Gleichungen als Variablen heißt **überbestimmt**.
>Es kann nur erfüllbar sein, wenn in der Zeilenstufe mindestens so viele Gleichungen entfallen (Nullzeilen), dass die Anzahl der Gleichungen nicht mehr größer ist als die der Variablen.

<br>

>[!write] Beispiele
>$\begin{align*}x_{1}+x_{2}&=1\\ x_{1}+x_{2}&=2\\x_{1}+x_{2}&=3 \end{align*}$
>
>Das LGS hat keine Lösung.
>
>--- 
>
>$\begin{align*}x_{1}+x_{2}&=1\\ x_{1}-x_{2}&=1\\ 2x_{1}+2x_{2}&=2\end{align*}$
>
>Das LGS hat genau eine Lösung:
>
>$x_{1}=1;\ x_{2}=0$
>
>---
>
>$\begin{align*}x_{1}+x_{2}&=1\\ 2x_{1}+2x_{2}&=2\\ 3x_{1}+3x_{2}&=3\end{align*}$
>
>Das LGS hat unendlich viele Lösungen.

