#GK #Unterthema

# [[Hypothesentests|Zurück]]

___
# Definition

>[!hint] Linksseitiger Hypothesentest
>Den **rechtsseitigen** Hypothesentest führst du durch, wenn du testen möchtest, ob eine Stichprobe **zu wenige Treffer** enthält.

<br>

___
# Beispiel

>[!write] Aufgabe
>Du hast einen Würfel 120-mal geworfen und 12-mal eine Fünf erhalten.
>Du hältst den Würfel für gezinkt.
>- Führe einen linksseitigen Hypothesentest mit einem Signifikanzniveau $\alpha =5$% durch.
>- Bestimme den Ablehnungsbereich und gib eine Entscheidungsregel für dein Ergebnis an.  

<br>

>[!success]- Lösung
>- Definiere die Zufallsvariable X und ihre Verteilung:
>
>X: Anzahl der gewürfelten Fünfen
>
>X ist im Extremfall binomialverteilt mit $n=120$ und $\displaystyle p=\frac{1}{6}$
>
>- Schreibe die Nullhypothese $H_0$, die Alternative $H_1$ und das Signifikanzniveau auf:
>
>Nullhypothese $H_0$: $\displaystyle p=\frac{1}{6}$
>Alternative $H_1$: $\displaystyle p<\frac{1}{6}$
>Signifikanzniveau $\alpha = 0.05$
>
>- Schreibe die Bedingung für die Grenze g des Ablehnungsbereichs auf:
>
$P(X\leq g) \leq 0.05$
>
>- Notiere einen Auszug und bestimme das kleinste g mit dem Taschenrechner:
>
>![[Linksseitiger Hypothesentest#^4dd28b]]
>g=12
>
>- Schreibe den Ablehnungsbereich und eine Entscheidungsregel für dein Ergebnis auf:
>
>Ablehnungsbereich = ${0;\ 1;...;\ 12}$
>Da das Ergebnis 12 im Ablehnungsbereich liegt, wird die Hypothese $H_0$ verworfen. 
>
>Entscheidungsregel:
>Wenn bei 120 Würfen höchstens 12-mal eine 5 erscheint, wird die Nullhypothese verworfen und man geht davon aus, dass die Wahrscheinlichkeit für eine 5 kleiner als $\displaystyle \frac{1}{6}$ ist. 
>Ansonsten wird die Nullhypothese nicht verworfen. 

<br>

___
# Annotation

| g | $P(X\leq g)$ |
| ---- | ---- |
| 11 | 0.0139 |
| 12 | 0.0275 |
| 13 | 0.0501 |
| 14 | 0.0847 |

^4dd28b
