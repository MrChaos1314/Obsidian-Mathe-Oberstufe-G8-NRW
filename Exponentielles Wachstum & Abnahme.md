---
cssclasses: hide_properties
tags: [GK, Unterthema, Fragen]
---

# [[Exponentialfunktionen|Zurück]]

___
# Definition

>[!hint] Definition
>**Exponentielles Wachstum** bzw. exponentielles Abnahme liegt vor, wenn ein Bestand von einem Zeitschritt zum nächsten um den gleichen **Wachstumsfaktor $a$** zu- bzw. abnimmt.
>Den Abstand zum Zeitpunkt $t$ kann man dann mithilfe einer Funktion $f$ mit
>
>$\qquad \qquad \qquad f(t)=f(0)\cdot a^t$
>
>bestimmen.
>
>Mit $k=ln(a)$ gilt auch 
>
>$\qquad \qquad \qquad f(t)=f(0)\cdot k \cdot e^{kt}$.
>
>Die Ableitung $f'$ mit 
>
>$\qquad \qquad \qquad f'(t)=f(0)\cdot k \cdot e^{kt}$ 
>
>beschreibt die Wachstumsgeschwindigkeit des Bestandes zum Zeitpunkt $t$.
>
>
>Man nennt die Zeit, in der sich der Anfangsbestand verdoppelt bzw. halbiert, **Verdopplungszeit $T_V$** bzw. **Halbwertszeit $T_H$**.
>Weil $f(T_V)=f(0)\cdot e^{k\ \cdot \ T_{V}}=2\cdot f(0)$, erhält man $e^{k\ \cdot \ T_{V}}=2$, also $\displaystyle T_{v}=\frac{ln(2)}{k}$ bei $k>0$.
>Entsprechend ergibt sich $\displaystyle T_{H}=\frac{ln(\frac{1}{2})}{k}$ bei exponentieller Abnahme ($k<0$).

<br>

___
# Beispiel

>[!write] Werte bestimmen
>Auf einer Insel leben 1000 Tiere, die sich exponentiell vermehren. 
>Die Anzahl der Tiere in Abhängigkeit zur Zeit t in Jahren kann durch die Funktion $f$ mit 
>
>$\displaystyle \qquad \qquad \qquad f(t)=1000\cdot e^{0.14t}$
>
>beschrieben werden.
>
>- Bestimme den Bestand nach 3 Jahren und nach 7 Monaten.
>- Bestimme den Zeitpunkt $t$, zu dem der Bestand von 5000 Tieren erreicht wird.
>- Berechne die Verdopplungszeit und erkläre die Bedeutung im Sachzusammenhang.

<br>

>[!success]- Lösung
>![[Exponentielles Wachstum & Abnahme#^81da2b]]

<br>


>[!write] Wachstumsfunktion aufstellen
>Einem Patienten werden 5 mg eines Medikaments verabreicht. Das Medikament wird vom Körper exponentiell abgebaut. 
>Stelle eine Funktionsgleichung mit der Basis $e$ auf, die die Menge des Medikaments im Blut des Patienten beschreibt, wenn
>
>- die Menge des Medikamentes im Blut pro Stunde um 15% abnimmt,
>- nach 2 Stunden noch 3,2 mg im Blut sind,
>- die Halbwertszeit 5 Stunden ist.

<br>

>[!success]- Lösung
>- Allgemein gilt für eine exponentielle Abnahme $f(t)=a\cdot e^{k\ \cdot \ t}$ mit $k<0$.
>- Hier gibt $t$ die Zeit in Stunden und $f(t)$ die Menge in mg an.
>- Für den Anfangsbestand gilt $a=f(0)=5$.
>  
>![[Exponentielles Wachstum & Abnahme#^7b7181]]

<br>

>[!write] Aufgabe
>Die Vermehrung einer Bakterienkultur lässt sich durch die Funktion $f$ mit 
>
>$\qquad \qquad \qquad f(t)=50e^{0.15t}$
>
>beschreiben. (t: Zeit in Stunden, $f(t)$: Anzahl der Bakterien in Tausend).
>
>- Bestimme die Wachstumsgeschwindigkeit nach 4 Stunden.
>- Ermittle den Zeitpunkt, zu dem der Bestand um 15.000 Bakterien pro Stunde wächst.
>- Bestimme die durchschnittliche Wachstumsgeschwindigkeit in den ersten 4 Stunden.

<br>

>[!success]- Lösung
>![[Exponentielles Wachstum & Abnahme#^14a388]]

<br>

___
# Annotation

| Vorgehen | Rechnung |
| ---- | ---- |
| Setze die Zeiten in f(t) ein.<br>Wandle 7 Monate in $\displaystyle \frac{7}{12}$ Jahre um.<br><br>Setze in der Funktionsgleichung 5000 für $f(t)$ ein und löse die Gleichung nach $t$ auf.<br><br><br><br><br><br><br><br><br>Setze den Wachstumsfaktor $k=0.14$ in die Formel für die Verdopplungszeit<br><br><br> | $\displaystyle \begin{align*}f(3)&=1000\cdot e^{0.14\ \cdot \ 3} \approx 1522 \\ f(\frac{7}{12})&=1000\cdot e^{0.14\ \cdot \ \frac{7}{12}} \approx 1085  \\ \\ 5000 &= 1000e^{0.14t} \qquad \mid : 1000   \\ 5&= e^{0.14t} \qquad \qquad \mid ln() \\ ln(5)&= 0.14t \qquad \qquad \mid :  0.14 \\ t&=\frac{ln(5)}{0.14} \approx 11.5 \end{align*}$<br><br>Nach etwa 11,5 Jahren sind es 5000 Tiere.<br><br><br>$\displaystyle T_V=\frac{ln(2)}{k}=\frac{ln(2)}{0.14} \approx 4.95$<br><br>Alle 4,95 Jahre verdoppelt sich die Anzahl der Tiere auf der Insel. |

^81da2b

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Bestimme aus der prozentualen Abnahme den Wachstumsfaktor $b$ und aus diesem die Wachstumskonstante $k$. | <br>$b=1-\frac{15}{100}=1-0.15=0.85$<br>$k=ln(b)=ln(0.85)\approx -0.163$<br><br>Einsetzen der Werte für $a$ und $k$ ergibt:<br>$f(t)=5e^{-0.163t}$<br>$\quad$ |
| <br>Setze die Angaben $t=2$ und $f(t)=3.2$ und den Anfangsbestand $a=5$ in die allgemeine Funktionsgleichung ein.<br>Löse die Gleichung nach $k$ auf. | <br>$\displaystyle \begin{align*} 3,2&=5\cdot e^{k\cdot 2}\qquad \mid \ : 5 \\ 0.64&=e^{k\cdot 2} \quad \ \qquad \mid ln() \\ ln(0.64)&=k\cdot 2 \quad \qquad \mid \ :2 \\ k&=\frac{ln(0.64)}{2} \approx -0.223 \\ \\ f(t)=5e^{-0.223t}\end{align*}$<br>$\quad$ |
| <br>Setze die Halbwertszeit $T_H=5$ in die Formel für die Halbwertszeit<br><br>$\displaystyle \qquad \qquad \qquad T_h=\frac{ln(\frac{1}{2})}{k}$<br><br>ein. <br><br>Löse die Gleichung nach $k$ auf.<br>$\quad$<br> | <br>Aus $\displaystyle 5=\frac{ln(\frac{1}{2})}{k}$ folgt $\displaystyle k=\frac{ln(\frac{1}{2})}{5} \approx -0.139$ <br><br>$f(t)=5e^{-0.139t}$ |

^7b7181

| Vorgehen | Rechnung |
| ---- | ---- |
| <br>Bestimme die erste Ableitung $f'(t)$ und setze den Zeitpunkt $t=4$ ein.<br>Beachte, dass $f(t)$ die Anzahl in Tausend angibt.  | <br>$f'(t)=50\cdot 0.15\cdot e^{0.15t}$<br>$f'(4)=7.5\cdot e^{0.15 \ \cdot \ 4} \approx 13.666$<br><br>Die Wachstumsgeschwindigkeit beträgt nach 4 Stunden etwa 13 666 Bakterien pro Stunde.<br>$\quad$ |
| <br>Setze die erste Ableitung $f'(t)$ mit 15 gleich und löse die Gleichung nach $t$ auf. | <br>$\displaystyle \begin{align*} 15&=7.5 e^{0.15t}\qquad \ \mid \  : 7.5 \quad \mid ln() \\ ln(2)&=0.15t \quad \ \qquad \mid :0.15 \\ t&=\frac{ln(2)}{0.15} \approx 4.62\end{align*}$<br><br>Der Zeitpunkt ist nach etwa 4,62 Stunden.<br>$\quad$ |
| <br>Teile die Änderung der Bakterienanzahl durch den zugehörigen Zeitraum.<br> | <br>$\displaystyle \frac{f(4)-f(0)}{4-0} \approx \frac{91.106-50}{4}\approx 10.276$<br><br>Das Wachstum beträgt durchschnittlich etwa 10 276 Bakterien pro Stunde<br>$\quad$ |

^14a388
