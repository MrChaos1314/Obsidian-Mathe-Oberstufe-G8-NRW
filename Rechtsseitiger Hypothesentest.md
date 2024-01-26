#GK #Unterthema 

# [[Hypothesentests|Zurück]]

___
# Definition

>[!hint] Definition
>Den **rechtsseitigen** Hypothesentest führst du durch, wenn du testen möchtest, ob eine Stichprobe **zu vielen Treffer** enthält.

<br>

___
# Beispiel

>[!write] Aufgabe
>Du hast einen Würfel 120-mal geworfen und 27-mal eine Zwei erhalten.
>- Führe einen rechtsseitigen Hypothesentest mit einem Signifikanzniveau $\alpha =5$% durch.
>- Bestimme den Ablehnungsbereich und gib eine Entscheidungsregel für dein Ergebnis an.  

<br>

>[!success]- Lösung
>- Definiere die Zufallsvariable X und ihre Verteilung:
>
>X: Anzahl der gewürfelten Zweien
>
>X ist im Extremfall binomialverteilt mit $n=120$ und $\displaystyle p=\frac{1}{6}$
>
>- Schreibe die Nullhypothese $H_0$, die Alternative $H_1$ und das Signifikanzniveau auf:
>
>Nullhypothese $H_0$: $\displaystyle p=\frac{1}{6}$
>Alternative $H_1$: $\displaystyle p>\frac{1}{6}$
>Signifikanzniveau $\alpha = 0.05$
>
>- Schreibe die Bedingung für die Grenze g des Ablehnungsbereichs auf:
>
$P(X\geq g)=1-P(X\leq g-1)\leq 0.05$
$P(X\leq g-1)\geq 0.95$
>
>- Notiere einen Auszug und bestimme das kleinste g mit dem Taschenrechner:
>
>![[Rechtsseitiger Hypothesentest#^9254d9]]
>g=28
>
>- Schreibe den Ablehnungsbereich und eine Entscheidungsregel für dein Ergebnis auf:
>
>Ablehnungsbereich = ${28;\ 29;...;\ 120}$
>Da das Ergebnis 27 nicht im Ablehnungsbereich liegt, wird die Hypothese $H_0$ nicht verworfen. 
>
>Entscheidungsregel:
>Wenn bei 120 Würfen mindestens 28-mal eine 2 erscheint, wird die Nullhypothese verworfen und man geht davon aus, dass die Wahrscheinlichkeit für eine 2 größer als $\displaystyle \frac{1}{6}$ ist. 
>Ansonsten wird die Nullhypothese nicht verworfen. 

<br>

___
# Annotation

| g-1 | $P(X\leq g-1)$ | g | $P(X\geq g)$ |
| ---- | ---- | ---- | ---- |
| 25 | 0.9081 | 26 | 0.0920 |
| 26 | 0.9403 | 27 | 0.0597 |
| 27 | 0.9627 | 28 | 0.0373 |
| 28 | 0.9777 | 29 | 0.0223 |

^9254d9

