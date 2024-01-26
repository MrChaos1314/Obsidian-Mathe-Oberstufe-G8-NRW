#GK #Unterthema #Fragen 

# [[Hypothesentests|Zurück]]

___
# Fehler 1. Art

>[!hint] Definition
>Beim Testen mit Binomialverteilung wird die Nullhypothese akzeptiert oder verworfen.
>Dabei können Fehlentscheidungen vorkommen.
>Wenn die Nullhypothese verworfen wird, obwohl sie richtig ist, spricht man von einem **Fehler 1. Art**.

<br>

>[!write] Beispiel
>Kruse Fragen

<br>

>[!success]- Lösung 
>Kruse Fragen

<br>

___
# Fehler 2. Art

>[!hint] Definition
>Beim Testen mit Binomialverteilung wird die Nullhypothese akzeptiert oder verworfen.
>Dabei können Fehlentscheidungen vorkommen.
>Wenn die Nullhypothese akzeptiert wird, obwohl sie falsch ist, spricht man von einem **Fehler 2. Art**.
>
>Die Wahrscheinlichkeit für den Fehler 2. Art kann man nur berechnen, wenn die tatsächliche Trefferwahrscheinlichkeit bekannt ist.
>
>Wenn man den Annahmebereich von $H_{0}$ vergrößert, um die Wahrscheinlichkeit für den Fehler 1. Art zu verkleinern, dann wird die Wahrscheinlichkeit für den Fehler 2. Art vergrößert.
>Wenn man den Stichprobenumfang erhöht, kann man gleichzeitig die Wahrscheinlichkeit für den Fehler 1. Art und die Wahrscheinlichkeit für den Fehler 2. Art verkleinern.
>
>>[!Attention]- Realisierbarkeit
>>In realen Testsituationen kann eine Vergrößerung der Stichprobe mit zu hohen Kosten verbunden sein. 
>>Außerdem besteht die Gefahr, dass unbedeutende Unterschiede signifikant werden.

<br>

>[!write] Beispiel
>Du greifst dir bei dem gleichen Obsthändler wie bei der Aufgabe zum Fehler 1. Art zwei Dutzend Äpfel aus dem Korb und hast nur 8 angeschlagene darunter.
>Daher glaubst du seiner Aussage.
>Der Obsthändler hat aber gelogen, in Wirklichkeit ist ein Drittel aller Äpfel angeschlagen.
>- Bestimme die Wahrscheinlichkeit des dabei möglichen Fehlers 2. Art und beschreibe die Bedeutung des Fehlers.

<br>

>[!success]- Lösung 
>- Gib den Ablehnungsbereich der ursprünglichen Behauptung an:
>
>Ablehnungsbereich = ${10;\ 11;...;\ 24}$
>
>- Notiere die Werte der tatsächlichen Binomialverteilung:
>
>X ist tatsächlich binomialverteil mit 
>$\qquad n=24$
>und
>$\displaystyle \qquad p=\frac{1}{3}$.
>
>- Bestimme mit diesen Werten die Wahrscheinlichkeit, ein Ergebnis außerhalb des ursprünglichen Ablehnungsbereichs zu erhalten:
>
>$P(X\leq 9)\approx 0.7462$
>Die Wahrscheinlichkeit des Fehlers 2. Art liegt bei 74.62%.
>
>- Beschreibe die Bedeutung des Fehlers:
>
>Der Fehler 2. Art gibt an, wie wahrscheinlich es ist, ein Ergebnis zu erhalten, aufgrund dessen man dem Obsthändler glaubt (da es im ursprünglichen Annahmebereich liegt), auch wenn er gelogen hat.

<br>

___
# Fehlerwahrscheinlichkeit

>[!hint] Definition
>Die Wahrscheinlichkeiten für Fehler 1. und 2. Art hängen vom tatsächlichen Wert von p ab und setzen die Gültigkeit bzw. Ungültigkeit der Nullhypothese voraus.
>
>Die maximale Irrtumswahrscheinlichkeit $a$ für Fehler 1. Art wird durch die Vorgabe des Signifikanzniveaus kontrolliert.
>
>Falls $H_0$ nicht zutrifft, bewirkt eine Reduktion des Signifikanzniveaus eine Vergrößerung der Wahrscheinlichkeit $\beta$ für Fehler 2. Art.
>
>Indem der Stichprobenumfang n hinreichend vergrößert wird, kann $\beta$ unter Einhaltung eines gesetzten Signifikanzniveaus reduziert werden. 

<br>

>[!write] Aufgabe
>Eine Notebookreihe fällt dadurch auf, dass häufig ein bestimmter Chip auf dem Mainboard überhitzt.
>Um die Ausfallwahrscheinlichkeit p abschätzen zu können, testet der Hersteller die Vorgabe $H_{0}:p\leq 0.01$ bei 200 Chips auf dem Signifikanzniveau 5%.
>- Der Ablehnungsbereich lautet $A=[6;\ 200]$.
>  Bestimme die maximale Irrtumswahrscheinlichkeit.
>- Erläutere im Sachzusammenhang die Bedeutung von Fehlern 2. Art.
>  Später stellt sich heraus, dass 3% aller Notebooks der Reihe defekte Chips aufweisen.
>- Bestimme, wie groß die Wahrscheinlichkeit einer Fehlentscheidung gewesen ist.
>- Untersuche, ob eine Stichprobengröße von 500 Chips ausgereicht hätte, um beide Fehlerwahrscheinlichkeiten von vornherein auf höchstens 10% zu begrenzen.

<br>

>[!success]- Lösung
>![[Fehler#^96e91a]]

<br>

___
# Annotation

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Die Irrtumswahrscheinlichkeit entspricht der Wahrscheinlichkeit des Ablehnungsbereichs für den Grenzwert $p=0.01$. | <br>X: Anzahl defekter Chips<br>X ist für den Test binomialverteilt mit dem größtmöglichen Wert der Nullhypothese <br>$\qquad p=0.01$<br>und <br>$\qquad n=200$.<br><br>$P(X\geq 6)=1-P(X\leq)\approx 1.6$%<br>$\quad$ |
| <br>Ein Fehler 2. Art passiert dann, wenn $H_0$ nicht zutrifft, durch den Test aber nicht abgelehnt wird. | <br>Die Nullhypothese trifft nicht zu, wird aber nicht abgelehnt:<br>Es gilt also $p>0.01$, aber es sind höchstens fünf Chips defekt.<br>$\quad$ |
| <br>Da die Nullhypothese wegen $0.03>0.01$ falsch ist, kann es nur einen Fehler 2. Art geben.<br><br>Berechne also, mit welcher Wahrscheinlichkeit das Stichprobenergebnis für $p=0.03$ außerhalb des Ablehnungsbereichs liegt. | <br>Y: Anzahl defekter Chips<br>Y ist binomialverteilt mit <br>$\quad n=200$<br>und <br>$\quad p=0.03$<br><br>Möglich ist nur der Fehler 2. Art:<br>$\beta =P(Y\leq 5)\approx 44.3$%<br><br>$\quad$ |
| <br>Berechne zunächst den Ablehnungsbereich für die neue Testsituation: 500 Chips auf dem Signifikanzniveau 10%.<br><br><br>Berechne anschließend für den realen Wert $p=0.03$ die Wahrscheinlichkeit für Fehler 2. Art. | <br>Z: Anzahl defekter Chips (passend zu $H_{0}$)<br><br>Für den Ablehnungsbereich folgt <br>$A = [9;\ 500]$ <br><br>W: Anzahl defekter Chips (Realität);<br>W ist binomialverteilt mit <br>$\quad n=500$<br>und <br>$\quad p=0.03$.<br><br>Fehler 2. Art: <br>$\qquad \beta=P(W\leq 8)\approx 3.5$%<br>Die Stichprobengröße genügt.<br>$\quad$  |

^96e91a

