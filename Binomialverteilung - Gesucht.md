#GK #Unterthema 

# [[Bernoulli-Experimente|Zurück]]

___
# Inhaltsverzeichnis - Binomialverteilung - Gesucht

- [[Binomialverteilung - Gesucht#Wahrscheinlichkeit P für Trefferanzahl|Wahrscheinlichkeit P für Trefferanzahl]]
- [[Binomialverteilung - Gesucht#Trefferzahl k|Trefferzahl k]]
- [[Binomialverteilung - Gesucht#Trefferwahrscheinlichkeit p|Trefferwahrscheinlichkeit p]]
- [[Binomialverteilung - Gesucht#Bernoullilänge n|Bernoullilänge n]]

___
# Wahrscheinlichkeit P für Trefferanzahl

>[!write] Aufgabentyp
>Ein Anfängersportschütze trifft die Mitte mit einer Wahrscheinlichkeit von 30%.
>Er schießt eine Serie von 20 Schüssen.
>
>_Bestimme mit welcher Wahrscheinlichkeit er_
>- genau fünf Treffer
>- höchstens drei Treffer
>- weniger als acht Treffer
>- mindestens zehn Treffer
>- mehr als 15 Treffer
>- mindestens 8 und höchstens 12 Treffer
>
>hat.

<br>

>[!hint]+ Ansatz
>X: Anzahl der Treffer in der Mitte
>X ist bino. mit 
>$\qquad n=20$ (Kettenlänge) 
>und 
>$\qquad p=0.3$ (Trefferwahrscheinlichkeit)
>
>- $P(X=5)=0.1789$
>- $P(X\leq 3)=0.1071$
>- $P(X< 8)=P(X\leq 7)=0.7723$
>- $P(X\geq 10)=0.0480$
>- $P(X> 15)=P(X\geq 16)=0.$
>- $P(8\leq X \leq 12)=0.1789$

<br>

___
# Trefferzahl k

>[!write] Aufgabentyp
>Alicia behauptet, dass sie einen Würfel so werfen kann, dass er sehr häufig die Augenzahl Sechs zeigt.
>Marie glaubt das nicht und lässt sie 30-mal würfeln.
>
>- Bestimme wievielmal Alicia dabei eine Sechs würfeln muss, damit die Wahrscheinlichkeit, dass dies zufällig geschieht, höchstens 5% ist.

<br>

>[!hint]+ Ansatz
>X: Anzahl der Augenzahl Sechs
>X ist bino. mit 
>$\qquad n=30$ 
>und 
>$\displaystyle \qquad p=\frac{1}{6}$ 
>
>$P(X\geq k)\leq 0.05$
>Lösung durch systematisches Ausprobieren!
>
>$\displaystyle b(k):=binomcdf(30; \ \frac{1}{6}; \ k,30)$
>
>Tabelle:
>![[Binomialverteilung - Gesucht#^658b43]]
>→$k= 10$
>
>Sie muss mindestens 10-mal eine Sechs würfeln.

<br>

___
# Trefferwahrscheinlichkeit p

>[!write] Aufgabentyp
>Eine Glühlampe, die zufällig der Produktion entnommen wird, leuchtet einwandfrei mit der unbekannten Wahrscheinlichkeit $p$.
>
>Jemand entnimmt zufällig 40 Glühbirnen.
>Mit einer Wahrscheinlichkeit von mindestens 90% sollen mindestens 38 Glühlampen dieser Stichprobe einwandfrei sein.
>
>- Bestimme wie groß die Wahrscheinlichkeit für eine einwandfreie Glühbirne mindestens sein muss.

<br>

>[!hint] Ansatz
>X: Anzahl der einwandfreien Glühbirnen
>X ist bino. mit 
>$\qquad n=40$ 
>und 
>$\displaystyle \qquad P(X\geq 38)\geq 0.90$ 
>
>Lösung durch systematisches Ausprobieren!
>
>$\displaystyle b(k):=binomcdf(30; \ p; \ 38,40)$
>
>Tabelle:
>![[Binomialverteilung - Gesucht#^45a53a]]
>→$p= 0.975$
>
>Die Wahrscheinlichkeit für eine einwandfreie Glühbirne muss mindestens 97,5% betragen.

<br>

___
# Bernoullilänge n

>[!write] Aufgabentyp
>Ein Zahnarzt weiß, dass die Wahrscheinlichkeit dafür, bei einem Patienten Karies zu diagnostizieren, etwa 60% beträgt.
>
>- Bestimme wie viele Karteikarten man mindestens zufällig entnehmen muss, wenn dabei mit einer Wahrscheinlichkeit von mindestens 95% mindestens zehn Patienten mit Kariesbefund sein sollen.

<br>

>[!hint] Ansatz
>X: Anzahl der Patienten mit Karies
>X ist bino. mit 
>$\qquad p=0.6$ 
>und 
>$\displaystyle \qquad P(X\geq 10)\geq 0.95$ 
>
>Lösung durch systematisches Ausprobieren!
>
>$\displaystyle b(n):=binomcdf(n; \ 0.6; \ 10,n)$
>
>Tabelle:
>![[Binomialverteilung - Gesucht#^71e36a]]
>→$n= 23$
>
>Man muss 23 Karteikarten entnehmen, damit die Wahrscheinlichkeit zutrifft.

<br>


___
# Annotation

| k | $b(k)\leq 0.05$ |
| ---- | ---- |
| 5 | 0.5757 |
| 10 | 0.0197 |
| 9 | 0.0506 |

^658b43

| p | $b(p)\geq 0.90$ |
| ---- | ---- |
| 0.95 | 0.6767 |
| 0.99 | 0.9925 |
| 0.975 | 0.9221 |
| 0.97 | 0.8822 |

^45a53a

| n | $b(n)\geq 0.95$ |
| ---- | ---- |
| 20 | 0.8725 |
| 25 | 0.9868 |
| 22 | 0.9449 |
| 23 | 0.9651 |

^71e36a

