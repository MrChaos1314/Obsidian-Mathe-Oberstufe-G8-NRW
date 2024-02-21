---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Integralrechnung|Zurück]]

___
# Inhaltverzeichnis - Das Integral - Approximation von Flächen

- [[Das Integral - Approximation von Flächen#Stammfunktion|Stammfunktion]]
- [[Das Integral - Approximation von Flächen#Definition - Integral|Definition - Integral]]
- [[Das Integral - Approximation von Flächen#Hauptsatz der Differenzial- und Integralrechnung|Hauptsatz der Differenzial- und Integralrechnung]]
- [[Das Integral - Approximation von Flächen#Flächeninhalte - Berechnung|Flächeninhalte - Berechnung]]

___
# [[Stammfunktion]]

![[Stammfunktion]]

<br>

___
# Definition - Integral

>[!hint] Definition - Integral
>- $f$ sei eine Funktion auf dem Intervall $[a;\ b],\ n$ die Anzahl der Teilintervalle und $U_n$ bzw. $O_n$ einer Unter- bzw. Obersumme von orientierten Rechtecksflächen.
>- Dann heißt der Grenzwert $\lim\limits_{n \to \infty} \ U_n =\lim\limits_{n \to \infty} \ O_n$ **Integral** der Funktion $f$ zwischen den Grenzen $a$ und $b$.
>- Man schreibt dafür $\displaystyle \int_a^b f(x)dx$ (lies: Integral von $f(x)$ von $a$ bis $b$). 
>
>>[!Info]
>>![[Pasted image 20231228103427.png|250]]
>
>&nbsp;
>
>>[!Info]- Tiefergehende Erläuterung
>>![[Pasted image 20231228103937.png|650]]

<br>

___
# Hauptsatz der Differenzial- und Integralrechnung

>[!hint] Hauptsatz
>Für eine stetige Funktion $f$ auf dem Intervall $[a;\ b]$ gilt:
>
>$\displaystyle \qquad \qquad \int_a^b f(x)dx =F(b) - F(a)$
>
>wobei $F$ eine beliebige Stammfunktion von $f$ auf $[a;\ b]$ ist.
>
>>[!info]- Zusatzinfo
>>Funktion $F$ nennt man Flächeninhaltsfunktion.


## Vorgehen

>[!info] Vorgehen
>- Um eine Stammfunktion $F$ zu bestimmen, muss man "rückwärts ableiten" (Synonyme: ~~aufleiten~~, integrieren), damit $F'(x)=f(x)$.
>- Bei der Berechnung eines Integrals wie $\displaystyle \int_1^3 x^2dx$ mit dem Hauptsatz wird zunächst eine [[Stammfunktion]] F bestimmt, z.B. $F(x)=\frac{1}{3}x^3$.
>- Anschließend werden die Funktionswerte $F(3)$ und $F(1)$ berechnet und dann ihre Differenz gebildet.
>- Für dieses Verfahren verwendet man die folgende Schreibweise:
>
>$\qquad \qquad \qquad \displaystyle \int_1^3 x^2dx =\left[\frac{1}{3}x^3\right]_1^3 =\frac{1}{3}3^3-\frac{1}{3}1^3=8\frac{2}{3}$
>

<br>

## Beispiel

>[!write] Aufgabe
> Skizziere mithilfe des Graphen der Funktion $f$ den Graphen einer möglichen Stammfunktion $F$ und erläutere dein Vorgehen.
> 
> >[!Info] Graph
> >![[Pasted image 20231228131244.png|550]]

<br>

>[!success]- Lösung
>- Für $x<-2$ steigt der Graph von $F$ streng monoton, denn $F'(x)=f(x)>0$.
>- Für $-2<x<2$ fällt der Graph von $F$ streng monoton, denn $F'(x)=f(x)<0$.
>- Für $x>2$ steigt der Graph von $F$ streng monoton, denn $F'(x)=f(x)>0$.
>- Bei den Nullstellen von $f$ hat der Graph von $F$ waagerechte Tangenten; wegen der Vorzeichenwechsel sogar Extrema.
>- Der y-Wert des Tiefpunkts von $F$ ist etwas kleiner als $-2.5$, denn die gelb gefärbte Fläche im Graphen ist etwa 2 FE groß, die grün gefärbte etwas größer als $0.5$ FE.
>  
>>[!Info]+ Möglicher Graph
>>![[Pasted image 20231228132244.png|550]]

<br>

___
# Flächeninhalte - Berechnung

>[!write] Aufgabe - Teilweise unterhalb/oberhalb der x-Achse 
> Gegeben ist die Funktion $f$ mit
> 
> $\qquad \qquad \qquad f(x)=x^2-2x$
> 
> Berechne den Inhalt der Fläche, die vom Graphen von $f$, der x-Achse und den Geraden $x=-1$ und $x=3$ eingeschlossen wird.
> 
> >[!Info] Graph
>> ![[Pasted image 20231228143312.png|550]]

<br>

>[!success]- Lösung
>![[Das Integral - Approximation von Flächen#^b534b1]]

<br>

>[!write] Aufgabe - Zwei Graphen (nicht schneidend) 
> Gegeben sind zwei Funktionen $f$ und $g$ mit
> 
> $\qquad \qquad \qquad f(x)=-0.1x^2+1.5$
> 
> $\qquad \qquad \qquad g(x)=2$
> 
> Berechne den Inhalt A der Fläche, die von den Graphen der Funktionen $f$ und $g$, der y-Achse und der Geraden $x=3$ begrenzt wird.
> 
> >[!Info] Graph
>> ![[Pasted image 20231228150535.png|550]]

<br>

>[!success]- Lösung
>
>$\displaystyle \int_{0}^3 -0.1x^2+1.5\ dx = \left[ \frac{-0.1}{3}x^3+1.5x \right]_{0}^3=3.6-0=3.6$
>
>$\displaystyle \int_{0}^3 2\ dx = \left[ 2x \right]_{0}^3=6-0=6$
>
>$G(x)-F(x)=A$
>
>$6-3.6=2.4$
>

<br>

>[!write] Aufgabe - Zwei Graphen (schneidend) 
> Gegeben sind die Funktionen $f$ und $g$ mit
> 
> $\qquad \qquad \qquad f(x)=x^3-6x^2+9x$
> 
> $\qquad \qquad \qquad g(x)=-\frac{1}{2}x^2+2x$
> 
> Berechne den Inhalt A dieser Flächen.
> 
> >[!Info] Graph
>> ![[Pasted image 20231228152728.png|550]]

<br>

>[!success]- Lösung
>![[Das Integral - Approximation von Flächen#^9d6612]]


<br>

___
# Annotation

| Schritte | Rechnung |
| ---- | ---- |
| <br><br><br>Berechne die Nullstellen | <br>$f(x)=x^2-2x$<br><br>$\begin{align} x^2-2x&=0 \\ x\cdot (x-2)&=0 \\ \\ x_1&=0 \\ x_2&=2 \end{align}$<br><br>Da Intervallgrenzen -1 und 3 sind, liegen die zu berechnenden Intervalle zwischen:<br><br>$[-1;\ 0];\ [0;\ 2];\ [2;\ 3]$<br>$\quad$ |
| <br>Stammfunktion bilden | <br>$F(x)=\frac{1}{3}^3-x^2$<br>$\quad$ |
| <br>Integral berechnen <br>-> jeweils im Intervall zwischen zwei Nullstellen | <br>$\displaystyle \int_{-1}^0 x^2-2x \ dx= \left[ \frac{1}{3}x^3-x^2 \right]_{-1}^0=\frac{4}{3}$<br><br>$\displaystyle \int_{0}^2 x^2-2x \ dx = \left[ \frac{1}{3}x^3-x^2 \right]_{-1}^0=-\frac{4}{3}$<br><br>$\displaystyle \int_{2}^3 x^2-2x \ dx = \left[ \frac{1}{3}x^3-x^2 \right]_{-1}^0=\frac{4}{3}$<br>$\quad$ |
| <br>Alle Ergebnisse addieren<br>(Gesamte Fläche = alles <br>Positiv)<br> | <br><br>$\frac{4}{3}+\frac{4}{3}+\frac{4}{3}=\frac{12}{3}=4$<br><br>$\quad$ |
| <br>Antwortsatz | <br>Der Flächeninhalt beträgt 4 FE<br>$\quad$ |

^b534b1

| Schritte | Rechnung |
| ---- | ---- |
| <br>Integral jeweiliger Funktion berechnen<br><br>Integrale voneinander entsprechend subtrahieren, sodass gewünschte Fläche/gewünschtes Integral resultiert.<br><br>In diesem Fall für A1 erst Integral von $f$ für $I[0;\ 2]$ berechnen, dann das gleiche mit $g$ und anschließend $f - g$ berechnen.<br> | <br>$\qquad f(x)=x^3-6x^2+9x$<br> <br> $\qquad g(x)=-\frac{1}{2}x^2+2x$<br><br><br><br>$\displaystyle \int_0^2 [\ f(x)-g(x)\ ]\ dx=3.\overline{33}$<br><br>$\quad$ |
| <br>Das gleiche wie in Schritt 3 dann für Intervall $I[2;\ 3.5]$.<br> | <br>$\displaystyle \int_2^{3.5} [\ g(x)-f(x)\ ]\ dx=1.54688$<br>$\quad$ |
| <br>A1 und A2 zusammenrechnen; gewünschte Fläche zwischen den beiden Graphen entsteht. | <br>$A_1 + A_2 = 3.\overline{ 33} + 1.54688 = 4.88021$<br><br>$\quad$ |

^9d6612

