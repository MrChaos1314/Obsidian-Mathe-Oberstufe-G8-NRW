---
cssclasses: hide_properties
tags: [Regel, GK]
---

# [[Bernoulli-Experimente|Zurück]]

___
# Definition

>[!info] Einführung
>Bei [[Binomialverteilung|Binomialverteilungen]] werden Einzelwahrscheinlichkeiten mit steigendem $n$ schnell klein und damit uninteressant.
>
>Mit der [[Standardabweichung]] lassen sich Umgebungen um den Erwartungswert finden, in denen die Trefferanzahl mit festen Wahrscheinlichkeiten liegt.

<br>

>[!hint] Sigma-Regel
>X sei eine binomialverteilte Zufallsgröße mit den Parametern $n$ und $p$, dem Erwartungswert $\mu =n\cdot p$ und der Standardabweichung $\displaystyle \sigma =\sqrt{n\cdot p \cdot (1-p)}$.
>
>Falls die **Laplace-Bedingung** $\sigma > 3$ erfüllt ist, gelten näherungsweise folgende Wahrscheinlichkeiten, dass die Trefferanzahl in den gegebenen Intervallen liegt.
>
>>[!info] Intervalle
>>![[Pasted image 20231231113322.png|350]]
>>![[Pasted image 20231231113258.png|350]]
>
>$\quad$
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20231230194339.png|450]]
>>
>
>

<br>

>[!hint] Prognose
>Stichprobenergebnisse (Treffer) **außerhalb der 2$\sigma$**-Umgebung bzw. 3$\sigma$-Umgebung sind sehr unwahrscheinlich.
>
>Man spricht dann von **signifikanten** bzw. hochsignifikanten **Abweichungen** vom Erwartungswert $\mu$.
>
>Das bedeutet: 
>Der Ausgang ist so ungewöhnlich, dass vermutlich eine andere Trefferwahrscheinlichkeit als das angenommene $p$ zugrunde lag.

<br>

___
# Beispiel

>[!write] Aufgabe
>Der Anteil an Linkshändern beträgt deutschlandweit etwa 12%.
>
>In einem Tennisverein mit 150 Mitgliedern wird die Anzahl der Linkshänder gezählt.
>
>Gesucht sind Prognosen für die zu erwartende Anzahl an Linkshändern im Verein.
>  
>- Gebe als Prognose ein Intervall um den Erwartungswert an, in dem die Anzahl der Linkshänder im Verein mit einer Wahrscheinlichkeit von mindestens 95% liegt.
>  
>- Die Zählung ergibt 27 Linkshänder.
>  Beurteile diesen Wert.
>  

<br> 

>[!success]- Lösung
>![[Bernoulli-Experimente#^9b509c]]

<br>

___
# Verträglichkeit von p mit einer Stichprobe

# Definition

>[!hint] Definition
>Ein vermuteter Wert für den Parameter p heißt **verträglich mit einer Stichprobe** zur Sicherheitswahrscheinlichkeit von 95%, wenn die Trefferanzahl der Stichprobe im 95%-Intervall von p liegt.

<br>

___
# Beispiel

>[!write] Aufgabe
>Bei der letzten Erhebung lag der Anteil an Vegetariern bei $p=0.06$.
>In einer aktuellen Umfrage von 300 Personen geben 25 Personen an, Vegetarier zu sein.
>- Prüfe, ob der Wert von p bei einer Sicherheitswahrscheinlichkeit von 95% mit der Stichprobe verträglich ist.

<br>

>[!success]- Lösung
>![[Sigma-Regel#^8bb415]]

<br>

___
# Weiteres Beispiel

>[!write] Sigma-Regel anwenden
>Auf einer Kirmes wirbt eine Losbude mit dem Versprechen:
>Jedes dritte Los gewinnt!
>Man ist misstrauisch und kauft 60 Lose, um die Aussage zu testen.
>Darunter sind nur 11 Gewinnlose.
>- Beurteile die Werbung mit Hilfe der Sigma-Regel.

<br>

>[!success]- Ansatz
>Sei X die Anzahl der Gewinnlose und binomialverteilt mit 
>$\qquad n=60$
>und 
>$\displaystyle \qquad p=\frac{1}{3}$.
>
>$E(X)=\mu =n\cdot p=20$
>$\sigma =\sqrt{n\cdot p \cdot (1-p)}=3.65$
>$\sigma > 3$ → Sigma-Regel
>(sinnvolle Sicherheit 95.5% → 2$\sigma$)
>
>$\begin{align*}I&= [\mu -2\sigma ;\ \mu + 2\sigma] \\ &= [12;\ 28]\end{align*}$
>
>95.5% aller Ausgänge liegen in dieser Umgebung, 4.5% außerhalb.
>Das beobachtete Testergebnis liegt linksseitig von der 2$\sigma$-Umgebung (nur ca. 2.25%).
>
>Beurteilung:
>Wahrscheinlich ist die Werbung falsch.
>Der Anteil der Gewinnlose ist vermutlich deutlich geringer als ein Drittel.

<br>

___
# Annotation

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Berechne für $n=300$ und $p=0.06$ das 95%-Intervall (Laplace-Bedingung $\sigma >3$ ist erfüllt). | <br>$\mu =300\cdot 0.06=18 \qquad \qquad \sigma \approx 4.11>3$<br>$\mu -1.96\sigma \approx 9.94; \qquad \qquad \mu +1.96\sigma \approx 26.06$<br>95%-Intervall: $\qquad \qquad [9.94;\ 26.06]$<br>$\quad$ |
| <br>Das Stichprobenergebnis 25 ist im Intervall enthalten.<br>Also ist p verträglich mit der Stichprobe.<br>$\qquad$ | <br>$25\in [9.94;\ 26.06]$<br>$p=0.06$ ist verträglich mit der Stichprobe. |

^8bb415
