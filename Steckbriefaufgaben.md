---
cssclasses: hide_properties
tags: [Unterthema]
---

# [[Ganzrationale Funktionen|Zurück]]

___
# Funktionsgleichung bestimmen

>[!hint] Allgemeine Funktionsgleichung
>Die allgemeine Funktionsgleichung einer ganzrationalen Funktion mit **Grad $n$ hat $n+1$ Parameter**.
Also müssen **mindestens** $n+1$ Bedingungen in Gleichungen übersetzt werden.
Bei **symmetrischen** Graphen ist diese Zahl **geringer**.

<br>

>[!hint] Achsensymmetrisch/Punktsymmetrisch
>
>
Funktionsgleichungen zu achsensymmetrischen (bzw. punktsymmetrischen) Graphen haben ausschließlich gerade (bzw. ungerade) Exponenten.
>> [!info] Beispiel
> >**Grad 4 und Achsensymmetrie:**
> >- $f(x)=ax^4+bx^2+c$
>> 
>> **Grad 5 und Punktsymmetrie:**
>> - $f(x)=ax^5+bx^3+cx$

<br>

___

# Beispiel

>[!write] Aufgabe
>- Der **Graph** einer **ganzrationalen Funktion vierten Grades** ist **achsensymmetrisch** und hat **einen Wendepunkt** $x=1$. 
>- Die Gleichung der zugehörigen **Wendetangente** lautet $y=-4x+3.5$.
>
>Bestimmen Sie die Funktionsgleichung.

<br>

>[!success]- Lösung
>![[Steckbriefaufgaben#^57babe]]

<br>

>[!write] Aufgabe
>![[Pasted image 20240103155631.png]]

<br>

>[!success]- Lösung 
>![[Pasted image 20240103155720.png]]

<br>

___
# Annotation
|  |  |
| ---- | ---- |
| Setze die Wendestelle in die Tangentengleichung ein und ermittle die y-Koordinate des Wendepunkts W.<br><br>Der Graph verläuft durch W (A).<br><br>Lese die Steigung im Wendepunkt an der<br>Tangentengleichung ab (B).<br><br>Für W gilt die notwendige Bedingung (C). | **Eigenschaften übersetzen:**<br>Wendepunkt $W({\color{cyan}{1}}\|y_w)$: $y_w={\color{orange}{-4}}*{\color{cyan}{1}}+3.5={\color{lime}{-0.5}}$<br><br>(A) Punkt $W({\color{cyan}{1}}\|{\color{lime}{-0.5}})$ : $f({\color{cyan}{1}})={\color{lime}{-0.5}}$<br><br>(B) Steigung bei $x={\color{cyan}{1}}$: $f'({\color{cyan}{1}})={\color{orange}{-4}}$<br><br>(C) Wendestelle $x={\color{cyan}{1}}$: $f''({\color{cyan}{1}})=0$ |
| Stelle die allgemeine Form der Funktionsgleichung von $f$ auf.<br><br>Aufgrund der Symmetrie fallen hier alle ungeraden Exponenten weg.<br>Bilde $f'(x)$ und $f''(x)$.<br><br>Setze die Bedingungen aus 1. ein und stelle das [[Lineare Gleichungssysteme\|lineare Gleichungssystem]] auf. | **In allgemeine Form einsetzen:**<br>$f(x)=ax^4+bx^2+c$<br>$f'(x)=4ax^3+2bx$<br>$f''(x)=12ax^2+2b$<br><br><br><br><br>(A) $f({\color{cyan}{1}})={\color{lime}{-0.5}}$<br>(B) $f({\color{cyan}{1}})={\color{orange}{-4}}$ <br>(C) $f''({\color{cyan}{1}})=0$<br><br>![[Pasted image 20231227161930.png\|250]] |
| Stelle die zweite Gleichung nach einer der Variablen um (hier $b$).<br><br>Setze den Term für $b$ in (C) ein und ermittle so $a$.<br><br>Durch Rückeinsetzen von $a$ erhält man so $b$.<br><br>Setze nun die Werte für $a$ und $b$ in (A) ein und bestimme den Wert für $c$.<br><br>Setze die Lösung in die allgemeine Form der Funktionsgleichung ein. | **Gleichungssystem lösen**<br>Umstellen von (B) <br>$\ \qquad \qquad \qquad \quad \begin{aligned} b&={\color{cyan}{-2a-2}} \end{aligned}$<br><br>Einsetzen in (C): <br>$\begin{aligned} b &= {\color{cyan}{-2a-2}} \\ 12a + 2({\color{cyan}{-2a-2}}) &= 0 \\ 8a-4 &= 0 \\ \Rightarrow a &= {\color{orange}{0.5}} \end{aligned}$<br><br>Rückeinsetzen:<br>$\qquad \qquad \qquad \quad b=-2*{\color{orange}{0.5}}-2={\color{lime}{-3}}$<br><br>Einsetzen in (A):<br>$\ \quad \begin{aligned}{\color{orange}{0.5}}+({\color{lime}{-3}})+c&=-0.5\\ \Rightarrow c&=2\end{aligned}$<br><br>Lösung:<br>$a=0.5;\ b=-3;\  c=2$<br><br>$f(x)=0.5x^4-3x^2+2$<br> |
| Untersuche mithilfe von $f'''$, ob auch die hinreichende Bedingung für die Wendestelle erfüllt ist. | **Eigenschaft überprüfen**<br><br>$f'''(x)=12x$<br>$f'''(1)=12≠0\Rightarrow$ Wendepunkt liegt vor. <br>$f$ erfüllt alle geforderten Eigenschaften. |
|  |  |

^57babe

