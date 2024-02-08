---
cssclasses: hide_properties
tags: [GK, Unterthema, Fragen]
---

# [[Integralrechnung|Zurück]]

___
# Definition

>[!hint] Definition
>Bei der Untersuchung von **unbegrenzten Flächen** auf einen Inhalt untersucht man Integrale mit einer Variablen und einer festen Grenze wie $\displaystyle \int_1^z f(x)dx$ oder wie $\displaystyle \int_z^3 f(x)dx$ auf einen **Grenzwert** für $z → \pm \infty$ bzw. für $z → c$, falls $f$ für $x=c$ eine Definitionslücke hat.
>
>Existieren die Grenzwerte, schreibt man 
>
>$\qquad \qquad \qquad \displaystyle \lim_{z\ \to \ \infty}\ \int_1^z f(x)dx =\int_1^\infty f(x)dx$
>
>bzw.
>
>$\qquad \qquad \qquad \displaystyle \lim_{z\ \to \ c}\ \int_z^3 f(x)dx =\int_c^3 f(x)dx$

<br>

___
# Beispiel

>[!write] Aufgabe
>Gegeben ist die Funktion $f$ mit 
>
>$\displaystyle f(x)=\frac{2}{\sqrt{x}}$.
>
>Untersuche, ob die Fläche, die vom Graphen von $f$, der $x$-Achse, der $y$-Achse und der Geraden $x=2$ eingeschlossen wird, einen endlichen Inhalt hat.
>
>>[!info] Graphen
>>![[Pasted image 20231228182750.png|550]]
>>

<br>

>[!success]- Lösung
>Es wird eine variable linke Grenze $z$ mit $z>0$ eingeführt.
>Für $z>0$ gilt
>
>$\displaystyle \qquad A(z)= \int_{z}^{2} \left(\frac{2}{\sqrt{x}}\right)dx=\int_{z}^{2} 2x^{-0.5}dx = \left[4x^{0.5}\right]_z^2=\left[4x\sqrt{x}\ \right]_z^2=4\sqrt{2}-4\sqrt{z}$.
>
>Für $z → 0$ strebt $4\sqrt{2}-4\sqrt{z} → 4\sqrt{2}$.
>
>Es gilt also $\displaystyle \lim_{z\ \to \ 0}\ A(z) =4\sqrt{2}$. 
>Die untersuchte Fläche hat den endlichen Inhalt $A=4\sqrt{2}\approx 5.66$.

<br>

>[!write] Aufgabe
>Gegeben ist die Funktion $f$ mit 
>
>$\displaystyle f(x)=\frac{2}{x^2}$.
>
>Berechne den Inhalt der Fläche über dem Intervall $[1; \ z]$.
>
>>[!info] Graphen
>>![[Pasted image 20231228185952.png|550]]

<br>

>[!success]- Lösung
>Um den Inhalt der nach rechts unbegrenzten Fläche zu untersuchen, berechnet man zunächst mit der variablen rechten Grenze $z$ den Inhalt der Fläche über dem Intervall $[1;\ z]$.
>
>$\displaystyle \quad A(z)= \int_{z}^{1} \frac{2}{x^2}dx=\left[-\frac{2}{x}\right]_{1}^{z}=-\frac{2}{z}+2=2-\frac{2}{z}$
>
>Da $A(z) → 2$ für $z → \infty$ gilt, ist der Flächeninhalt der unbegrenzten Fläche vom Graphen $A=2$.
>
 
<br>
%%Fragen wegen der Aufgabe%%
