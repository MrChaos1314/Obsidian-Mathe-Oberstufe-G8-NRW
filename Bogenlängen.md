---
cssclasses: hide_properties
tags: [Formel, GK, Unterthema]
---

# Definition

>[!hint] Definition
>Ist die Funktion $f$ auf dem Intervall $[a;\ b]$ differenzierbar, so hat der Bogen des Graphen auf diesem Intervall die Bogenlänge:
>
>$\displaystyle \qquad \qquad \qquad l=\int_{a}^{b}\sqrt{1+(f'(x))^2}dx$

<br>

___
# Beispiel

>[!write] Aufgabe
>Berechne die Länge des Bogens zur Funktion $f$ mit 
>
>$\displaystyle \qquad \qquad \qquad f(x)=\frac{2}{3}\sqrt{x^3}$ 
>
>auf dem Intervall $[1;\ 3]$. 

<br>

>[!success]- Lösung
>![[Bogenlängen#^96be52]]

<br>

___
# Annotation

| Schritte | Rechnung |
| ---- | ---- |
| <br>Bestimme die Ableitung von $f$. | <br>$\displaystyle f(x)=\frac{2}{3}x^{(2/3)}$;  $f'(x)=x^{(1/2)}=\sqrt{x}$ <br>$\quad$ |
| <br>Setze das Ergebnis in die Formel ein.<br><br>$\displaystyle G(x)= \frac{2}{3}\sqrt{(1+x)^3}$<br><br>$g(x)=\sqrt{1+x}$.<br>Berechne damit das Integral.<br>Die Länge des Bogens beträgt ca. 3.45 LE. | <br>$\displaystyle \ l=\int_1^3\sqrt{1+(\sqrt{x})^2}\ dx=\int_1^3\sqrt{1+x}\ dx$<br><br>$\displaystyle \quad =\left[\frac{2}{3}\sqrt{(1+x)^3}\right]_1^3$<br><br>$\displaystyle \quad = \frac{2}{3}\sqrt{4^3}-\frac{2}{3}\sqrt{2^3}\approx 3.45$ |

^96be52

