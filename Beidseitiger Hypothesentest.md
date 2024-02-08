---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Hypothesentests|Zurück]]

___
# Definition

>[!hint] Beidseitiger Hypothesentest
>Der zweiseitige/beidseitige Hypothesentest ist nichts Neues, es werden nur beide Tests zu einem Test zusammengefasst.
>In zahlreichen Fällen ist es sinnvoll, für die Ergebnisse sowohl eine Grenze nach unten wie auch nach oben festzulegen.
>
>**Nullhypothese** $H_0:p=p_0;$ **Alternative** $H_1:p\neq p_0$
>
>Das Signifikanzniveau $\alpha$ wird beim zweiseitigen Test auf beide Seiten zu $\displaystyle \frac{\alpha}{2}$ verteilt und es wird ein unterer und ein oberer Ablehnungsbereich bestimmt.
>
>Dieses Vorgehen wählst du immer dann, wenn nach oben und nach unten keine zu großen Abweichungen vorkommen sollen.

<br>

___
# Beispiel

>[!write] Beidseitiger Test
>Du hast einen Würfel 200-mal geworfen und gezählt, wie oft die Drei gefallen ist.
>- Führe einen beidseitigen Hypothesentest mit einem Signifikanzniveau $\alpha =5$% durch.
>- Gib an, bei welchen Ergebnissen du den Würfel für nicht korrekt hältst.  

<br>

>[!success]- Lösung
>- Definiere die Zufallsvariable X und ihre Verteilung:
>
>X: Anzahl der gewürfelten Dreien
>
>X ist im Extremfall binomialverteilt mit $n=200$ und $\displaystyle p=\frac{1}{6}$
>
>- Schreibe die Nullhypothese $H_0$, die Alternative $H_1$ und das Signifikanzniveau auf:
>
>Nullhypothese $H_0$: $\displaystyle p=\frac{1}{6}$
>Alternative $H_1$: $\displaystyle p\neq \frac{1}{6}$
>Signifikanzniveau $\alpha = 0.05;\ \frac{\alpha }{2}=0.025$
>
>- Linksseitig: 
>  Schreibe die Bedingung für die Grenze $g_1$ des Ablehnungsbereichs auf:
>
$P(X\leq g_1) \leq 0.025$
>
>- Notiere einen Auszug und bestimme das größte $g_1$ mit dem Taschenrechner:
>
>![[Beidseitiger Hypothesentest#^52aff3]]
>$g_1$=22
>
>- Schreibe den linken Ablehnungsbereich auf:
>
>Ablehnungsbereich = ${0;\ 1;...;\ 22}$
>
>- Rechtsseitig:
>  Schreibe die Bedingung für die Grenze $g_2$ des Ablehnungsbereichs auf:
>
>$P(X \geq g_{2})=1-P(X \leq g_{2}-1)\leq 0.025$
>$P(X \leq g_{2}-1) \geq 0.975$
>
>- Berechne mit dem Taschenrechner einen Auszug und bestimme das kleinste $g_2$:
>  
>![[Beidseitiger Hypothesentest#^83b91f]]
>$g_{2}=45$, da $g_{2}-1=44$
>
>- Schreibe den rechten Ablehnungsbereich auf:
>Ablehnungsbereich =${45;\ 46;...;\ 200}$
>
>- Formuliere eine Entscheidungsregel für dein Ergebnis:
>  
>Entscheidungsregel:
>Wenn die Drei weniger als 23-mal oder mehr als 44-mal gewürfelt wird, wird die Nullhypothese verworfen.
>Ansonsten wird die Nullhypothese nicht verworfen und das bedeutet, dass die Korrektheit des Würfels zu 95% gegeben ist.

<br>

___
# Annotation

| $g_1$ | $P(X\leq g_1)$ |
| ---- | ---- |
| 22 | 0.0163 |
| 23 | 0.0269 |

^52aff3

| $g_2-1$ | $P(X\leq g_2-1)$ |
| ---- | ---- |
| 43 | 0.9699 |
| 44 | 0.9801 |
| 45 | 0.9872 |
| 46 | 0.9919 |

^83b91f
