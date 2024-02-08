---
cssclasses: hide_properties
tags: [Mathe, GK, Regel, Formel, TBD]
---

# [[Das Integral - Approximation von Flächen|Zurück]]

___
# Definition

>[!hint] Definition
>$\quad$
>Eine Funktion $F$ heißt **Stammfunktion** zu einer Funktion $f$ auf einem Intervall $I$, wenn für alle $x\in I$ gilt: 
>
>$\qquad \qquad \qquad F'(x)=f(x)$.
>
**Satz:**
Sind $F$ und $G$ Stammfunktionen von $f$ auf einem Intervall $I$, dann gibt es eine Konstante $c\in R$, sodass für alle $x\in I$ gilt: 
>
$\qquad \qquad \qquad F(x)=G(x)+c$.
>
>**Zusammengesetzte Funktionen:**
>Sind G und H Stammfunktionen von g und h, so gilt für zusammengesetzte Funktionen:
>
>![[Stammfunktion#^05289e]]
>$\quad$


<br>

___
# Regeln

| Regel | Formel |
| ---- | ---- |
| Potenzregel |  $\displaystyle F(x) = \int x^n dx = \frac{1}{n+1}x^{n+1}+c$ |
| Faktorregel | $\displaystyle F(x) = \int a \cdot f(x) dx= a \cdot \int f(x)dx$ |
| Summenregel | $\displaystyle F(x) = \int (f(x)+g(x)) dx = \int f(x) dx + \int g(x) dx$ |
| Differenzregel | $\displaystyle F(x) = \int (f(x)- g(x)) dx = \int f(x) dx - \int g(x) dx$ |
| Partielle Integration | TBD |
| Logarithmische Integration | TBD |

^9ffbc5



___
# Annotation

| Funktion $f$ | Stammfunktion $F$ | Beispiel |
| ---- | ---- | ---- |
| $f(x)=g(x)+h(x)$ | $F(x)=G(x)+H(x)$ | $f(x)=x^2+x^4$<br>$F(x)=\frac{1}{3}x^3+\frac{1}{5}x^5$ |
| $f(x)=c\cdot g(x)$ | $f(x)=c\cdot G(x)$ |  |

^05289e

