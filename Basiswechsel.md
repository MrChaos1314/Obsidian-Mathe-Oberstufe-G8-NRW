---
cssclasses: hide_properties
tags: [GK, Unterthema]
---

# [[Exponentialfunktionen|Zurück]]

___
# Erläuterung

>[!hint] Erläuterung
>Um Exponentialfunktionen mit beliebigen Basen ableiten zu können, werde diese mit Potenzen zur Basis $e$ beschrieben.
>
>Man schreibt die Basis mithilfe des natürlichen Logarithmus und der $e$-Funktion um.
>Anschließend wendet man das Gesetz für das Potenzieren von Potenzen an.
>
>Bsp.:
>
>$\displaystyle \begin{align*} 2^{x}&=(e^{ln(2)})^{x}\qquad (\text{denn}\  2=e^{ln(2)}) \\ \\ &=e^{ln(2)\ \cdot \ x}\end{align*}$
>
>>[!hint] Exponentialfunktionen mit Basis $e$ darstellen
>>Jede Exponentialfunktion mit beliebiger Basis lässt sich als eine Exponentialfunktion mit Basis $e$ schreiben:
>>
>>$f(x)=b^{x}=e^{ln(b)\ \cdot \ x}$
>
>$\qquad$
>
>>[!hint] Ableitung
>>Die Funktion $f$ mit $f(x)=b^{x}$ und $b∈ \mathbb{R}, b>0$ hat die Ableitung $f'(x)=ln(b)\ \cdot \ b^x$
>>
>>$\begin{align*}f(x)&=5^{x} \\ f'(x)&=ln(5) \cdot  5^{x} \\ f''(x)&=ln(5) \cdot  ln(5) \cdot  5^{x} = (ln(5))^{2}  \cdot 5^x \end{align*}$
>
>$\quad$
>
>>[!info] Anmerkung
>>Der Beweis des Satzes erfolgt über die Umschreibung in eine Exponentialfunktion mit Basis $e$ und anschließende Anwendung der Kettenregel.
>>Es gilt:
>>
>>$\qquad \qquad f(x)=b^x=(e^{ln(b)})^x=e^{ln(b)\ \cdot \ x}$
>>
>>Somit folgt 
>>
>>$\qquad \qquad f'(x)= (e^{ln(b) \ \cdot \ x}) \cdot ln(b) =ln(b) \cdot b^x$
>
>$\quad$
>
>>[!info] Wiederholung 
>>![[Ableitung#^254773]]

<br>

___
# Beispiel

>[!write] Aufgabe
>Gegeben ist die Funktion $f$ mit 
>
>$\qquad \qquad \qquad f(x)=2^x$
>
>Bestimme die erste Ableitung der Funktion $f$.

<br>

>[!success]- Lösung
>$f'(x)=ln(2)\cdot 2^{x}\approx 0.69315\cdot2 ^x$

<br>
