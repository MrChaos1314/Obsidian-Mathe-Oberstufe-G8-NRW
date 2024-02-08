---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Statistik bzw. Stochastik|Zurück]]

___
# Definition

>[!hint] Merksätze
>Gegeben ist eine Urliste $x_1,x_2,...,x_n$.
>Die zugehörigen Kenngrößen sind:
>- Der [[Mittelwert]] 
>  $\displaystyle \overline{x}=\frac{1}{n}(x_1+x_2+...+x_n)$
>- Die empirische [[Standardabweichung]] 
>  $\displaystyle s = \sqrt{\frac{1}{n}((x_{1}-\overline{x})^{2} + (x_{2}-\overline{x})^{2}+...+(x_{n}-\overline{x})^{2})}$.
>  
>Wenn eine relative Häufigkeitsverteilung mit den Werten $m_1,m_2,...,m_k,$ und den relativen Häufigkeiten $h_1,h_2,...,h_k,$ vorliegt, so gilt auch
>  
>$\qquad \qquad \qquad \overline{x} \approx m_1\cdot h_1+m_2\cdot h_2+...+m_k\cdot h_k$
>
>und 
>
>$\qquad \qquad \qquad \displaystyle s \approx \sqrt{(m_1-\overline{x})^{2}\cdot h_{1}+(m_2-\overline{x})^{2}\cdot h_{2}+...+(m_k-\overline{x})^{2}\cdot h_{k}+}$.
>
>Bei Messungen charakterisiert die Standardabweichung die Messungsgenauigkeit.
>
>**Gauß'sche Faustregel**
>Nach einer groben Faustregel, die C. F. Gauß entdeckte, weichen **bei zufälligen Messfehlern** ca. 68,3% der Messwerte höchstens um die Standardabweichung $s$ vom Mittelwert $\overline{x}$ ab, sie liegen also im **Standardabweichungs-Intervall** ($s$-Intervall) $[\overline{x}-s; \ \overline{x} +s]$ mit dem Mittelpunkt $\overline{x}$.

<br>

___
# Beispiel

>[!write] Kennwerte aus einer Urliste bestimmen
>- Bestimme **ohne Taschenrechner** überschlagsmäßig die Standardabweichung der Daten aus der Stichprobe:
>  
>  $\qquad \qquad \qquad 5;\ -3;\ 2;\ 4$
>  
>
>  
>- Deute das Ergebnis.

<br>

>[!success]- Lösung
>Man bestimmt zunächst den Mittelwert 
>
>$\displaystyle \overline{x}=\frac{1}{4}(5-3+2+4)=\left(\frac{8}{4}\right)=2$ 
>
>und berechnet dann 
>
>$\displaystyle s = \sqrt{\frac{1}{4}((5-2)^{2} + (-3-2)^{2}+ (2-2)^{2}+ (4-2)^{2})} = \sqrt{\left(\frac{38}{4}\right)= \sqrt{9.5}} \approx 3,...$
>
>Die Standardabweichung ist etwas größer als 3. 
>Je nachdem aus welcher Quelle die Daten stammen, könnte man intuitiv vermuten, dass bei einer größeren Stichprobe viele (ca. 68,3%) der Stichprobenwerte zwischen -1 und 5, also im $s$-Intervall $[-1; \ 5]$ liegen.
>Diese Spekulation ist wegen des sehr kleinen Stichprobenumfangs 4 aber unsicher.

<br>

>[!write] Kennwerte aus einer relativen Häufigkeitsverteilung bestimmen
>Die folgende Abbildung zeigt den Punktespiegel eines Tests, bei dem man 15 Punkte erreichen konnte.
>Spalte C enthält relative Häufigkeiten.
>
>>[!info] Abbildung
>> ![[Pasted image 20231230171807.png|250]]
>
>- Bestimme den Mittelwert und die Standardabweichung.

<br>

>[!success]- Lösung
>$\displaystyle \overline{x}=4\cdot 0.01+5\cdot 0.00+...+15\cdot 0.02=10.6$ 
>
>$\displaystyle s = \sqrt{(4-\overline{x})^{2}\cdot 0.01 + (5-\overline{x})^{2}\cdot 0.00+...+(15-\overline{x})^{2}\cdot 0.02} \approx 1.97$
>

<br>

___
# Annotation

>[!Danger] Nicht beachten
>Wenn keine Annotation: Löschen!