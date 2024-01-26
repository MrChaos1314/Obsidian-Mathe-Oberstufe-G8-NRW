#Fragen #Wiederholung-EF #Unterthema 

# [[Mathe-Oberstufe Verzeichnis#Wiederholung - EF|Zurück zu Wiederholung-EF]]

___
# [[Ganzrationale Funktionen|Zurück zu ganzrationalen Funktionen]]

___
# Inhaltverzeichnis - Ableitung

- [[Ableitung#Definition|Definition]]
- [[Ableitung#Graphische Ableitung|Graphische Ableitung]]
- [[Ableitung#Tipp|Tipp]]
- [[Ableitung#Merke|Merke]]
- [[Ableitung#Ableitungsregeln|Ableitungsregeln]]
- [[Ableitung#Ableiten ganzrationaler Funktionen|Ableiten ganzrationaler Funktionen]]
- [[Ableitung#Tangente|Tangente]]
- [[Ableitung#Tangentensteigung bestimmen|Tangentensteigung bestimmen]]
- [[Ableitung#Die zweite Ableitung / Höhere Ableitungen|Die zweite Ableitung/Höhere Ableitungen]]
- [[Ableitung#Ableitung - Exponentialfunktionen|Ableitung - Exponentialfunktionen]]
- [[Ableitung#Basiswechsel|Basiswechsel]]
- [[Ableitung#Ableiten - Zusammengesetze Funktionen|Ableiten - Zusammengesetze Funktionen]]

___
# Definition

>[!hint] Definition
>Die **Ableitung** $f'(x)$ einer Funktion $f(x)$ gibt die **Steigung** der Funktion in einem bestimmten Punkt an. Du unterscheidest drei Fälle:
>- Ableitung<span style="color:#00b050"> **positiv**</span> $f'(x)>0$ → Funktion <span style="color:#00b050">**steigt**</span>
>- Ableitung <span style="color:#c00000">**negativ**</span> $f'(x)<0$ → Funktion <span style="color:#c00000">**fällt**</span>
>- Ableitung **<span style="color:#ffff00">null</span>** $f'(x)=0$ → Funktion hat einen **<span style="color:#ffff00">Extrempunkt</span>** (Hochpunkt oder Tiefpunkt) oder einen **Sattelpunkt**
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20231226165651.png|400]]
>
>Durch **Ableiten** findest du die **[[Ableitung#^8d4e95|Tangentensteigung]]** in einem bestimmten Punkt eines Graphen heraus. Ist die Ableitung positiv, dann steigt die Funktion. Ist sie negativ, so fällt der Graph. Ableiten funktioniert bei jeder Funktion unterschiedlich und nach bestimmten **Regeln**.

___
# Graphische Ableitung

>[!info] Vorgehen
>Einerseits kann man die Ableitung rechnerisch bilden, aber auch graphisch darstellen.
>
Vorgehen:
>- Die **[[Extrempunkte|Extremstellen]]** der Funktion werden die **[[Nullstellen]]** der Ableitung 
>- Die **Wendestellen** der Funktion werden die **[[Extrempunkte|Extremstellen]]** der Ableitung
>
>
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20231226171455.png]]

>[!Attention] Frage
>Fraglich wie man die Position vom zweiten Punkt "E" bestimmt, ohne den y-Achsenabschnitt zu kennen.

<br>

___
# Tipp

>[!info]+ NEW-Hilfe
>Methode:
>
| $f(x)$   | N   | E   | W   |     |     |
| -------- | --- | --- | --- | --- | --- |
| $f'(x)$  | -   | N   | E   | W   |     |
| $f''(x)$ | -   | -   | N   | E   | W   |
>N: Nullstelle
>E: Extremstelle
>W: Wendestelle

<br>

___
# Merke

>[!hint] Merke
>- Die **erste Ableitung** gibt die Steigung des Graphen von $f(x)$ an einem Punkt an. 
>- Mit der Ableitung kannst du also an jeder Stelle $x$ die Steigung der Funktion ermitteln. 
>- Wenn du einen $x$-Wert (z.B. $x = 5$)  in die erste Ableitung einsetzt, erhältst du die **Steigung der Funktion** in diesem Punkt.

<br>

___
# Ableitungsregeln

^9bf18f
>[!hint] Ableitungsregeln Übersicht
>![[Ableitung#^58a659]]

<br>

>[!info] Ableitungskreis
>![[Pasted image 20231230124502.png|450]]

<br>

___
# Ableiten ganzrationaler Funktionen

>[!info] Regeln zum Ableiten ganzrationaler Funktionen
>Zum Ableiten ganzrationaler Funktionen verwenden wir [[Potenzregel]], [[Faktorregel]] und [[Summenregel]].

![[Potenzregel#Definition]]

![[Faktorregel#Definition]]

![[Summenregel#Definition]]

<br>

___
# Tangente

^8d4e95

>[!hint] Definition
>- Mit der Steigung in einem Punkt ist die **Steigung der Tangente** gemeint.
>- Das ist eine Gerade, die den Graphen in dem **Punkt** ($P$) berührt.

<br>

>[!info] Graph
![[Pasted image 20231226234343.png|250]]

<br>

___
# Tangentensteigung bestimmen

>[!write] Berechne die Steigung einer [[Mittlere Änderungsrate#^ba9c23|Sekante]]
>- Einer der Punkte ist der Punkt, in dem du die **Ableitung berechnen** willst. Du kannst ihn allgemein **$P(x0|y0)$** nennen.
>- Der **andere Punkt** liegt zum Beispiel weiter **rechts**. 
>  Nenn ihn einfach mal **$Q(x|y)$**.
>>[!info] Graph
>>![[Pasted image 20231226235104.png|250]]

<br>

>[!hint] Vorgehen
>- Um ihre **Steigung $m$** zu berechnen , teilst du den **Abstand der y-Werte** der beiden Punkte durch den **Abstand der x-Werte**.
>
![[Differenzenquotient#Formel]]
>
>- Jetzt willst du von der Sekante zu einer Tangente an der Stelle **$x_0$** kommen. 
>- Dazu verkleinerst du den Abstand zwischen **$x$** und **$x_0$** immer weiter.
>  
>>[!info] Graphische Veranschaulichung
>>![[Pasted image 20231226235833.png|550]]
>
>
>- Mathematisch schreibst du dafür den Limes (Grenzwert) von $x$ gegen $x_0$
>
$\displaystyle \qquad \qquad \qquad \lim_{x\to x_0}\frac{f(\textcolor{olive}{x})-f(\textcolor{purple}{x_0})}{\textcolor{olive}{x}-\textcolor{purple}{x_0}}$	
>
>- Dein Ergebnis ist dann die Tangentensteigung an $x_0$, also die Ableitung an $x_0$:
>
$\displaystyle \qquad \qquad \qquad f'(x_0) = \lim_{x\to x_0}\frac{f(\textcolor{olive}{x})-f(\textcolor{purple}{x_0})}{\textcolor{olive}{x}-\textcolor{purple}{x_0}}$

<br>

>[!hint] Tangentengleichung
>$f_{t}(x)=f'(x_{0}) \cdot (x-x_{0})+y_{0}$
>
>($x_{0}$ und $y_{0}$ sind Punkte eines Punktes P$(x_{0}\mid y_{0})$)

<br>

___

# [[Ganzrationale Funktionen|Zurück zu ganzrationale Funktionen]]

___
# Die zweite Ableitung / Höhere Ableitungen

>[!info] Erläuterung 
>- Von der **Ableitung $f'(x)$** einer Funktion kannst du auch nochmal die Ableitung bilden. Du erhältst dann die **zweite Ableitung $f“(x)$**. 
>  - Sie gibt die Krümmung der Funktion an. 
>- Außerdem kannst du mit zweiten Ableitungen Wendepunkte berechnen.
>$\quad$
>
>erste Ableitung: $f'(x)$
> 
>zweite Ableitung: $f''(x)$ 

![[Extrempunkte#Notwendige Bedingung]]



![[Extrempunkte#Hinreichende Bedingung]]

<br>

___
# [[Exponentialfunktionen|Zurück zu Exponentialfunktionen]]

___
# Ableitung - Exponentialfunktionen

>[!info] Einführung
>Mit Exponentialfunktionen kann man exponentielles Wachstum beschrieben.
>Die Funktion $f$ mit $f(x)=2^x$ gibt zum Beispiel die Anzahl von Bakterien zum Zeitpunkt $x$ Tage an, wenn sich der Bestand täglich verdoppelt.
>Mit der Ableitung von $f$ kann die momentane Geschwindigkeit des Wachstums zu einem beliebigen Zeitpunkt bestimmt werden.
>
>Um eine Regel zur Ableitung von Exponentialfunktionen wie $f(x)=2^x$zu finden, werden sowohl $f$ als auch $f'$ grafisch dargestellt.
>
>Die Graphen lassen vermuten, dass die Ableitung einer Exponentialfunktion ebenfalls eine Exponentialfunktion ist.
>
>>[!info] Graph
>>
>>![[Pasted image 20231229002759.png|450]]

<br>

>[!hint] Definition
>Für die Ableitung von Exponentialfunktionen vom Typ $f(x)=a^{x}(a>0)$ gilt:
>
>$\qquad \qquad \qquad f'(x)= ln(a) \cdot a^{x}$
>
>>[!Attention]- Begründung
>>Weil $a^{x} = e^{ln(a)\cdot x}$ ist kann man die Ableitung von $e^{ln(a)\cdot x}$ zu $ln(a)\cdot a^x$ umformulieren.
>>(Die Ableitung von $e^{ln(a)\cdot x}$ ist $ln(a)\cdot e^{ln(a)\cdot x}$)
>
>
>
>Es gibt eine Basis $e \approx 2.71828$, für die Exponentialfunktion mit $f(x)=e^x$ exakt mit ihrer Ableitungsfunktion übereinstimmt.
>Diese Zahl $e$ heißt **natürliche Exponentialfunktion**.
>
>Für $f(x)=e^x$ gilt $f'(x)=e^x$.
>
>Außerdem ist $F$ mit $F(x)=e^x$ eine Stammfunktion von $f$.
> 

<br>

>[!Bug]- Extra
>![Die Eulersche Zahl](https://www.youtube.com/watch?v=duFVzBr59gA)

<br>

## Basiswechsel

![[Basiswechsel]]

<br>

___
# Ableiten - Zusammengesetze Funktionen

![[Regeln zur Ableitung - Scharfunktionen]]
___
# Annotation

>[!Info]- Annotation  
>[Q](https://studyflix.de/mathematik/ableitung-2066)


| Funktion $f(x)$    | Ableitung $f'(x)$            |
| ------------------ | ---------------------------- |
| Polynome           |                              |
| $f(x) = Zahl$      | $f'(x) = 0$                  |
| $f(x) = m\cdot x+t$      | $f'(x) = m$                  |
| $f(x) = x^2$       |$f'(x) = 2x$                 |
| $f(x) = x^n$       | $f'(x) = n\cdot x^{n\ -\ 1}$          |
| e-Funktion und ln  |                              |
| $f(x)=e^x$         | $f'(x) = e^x$                |
| $f(x)=ln(x)$       | $\displaystyle f'(x) = \frac{1}{x}$        |
| Sinus und Cosinus  |                              |
| $f(x)=sin(x)$      | $f'(x)=cos(x)$               |
| $f(x)=cos(x)$      | $f'(x)=-sin(x)$              |
| Wurzeln und Brüche |                              |
| $\displaystyle f(x)=\sqrt{x}$    | $\displaystyle f'(x)= \frac{1}{2\sqrt{x}}$ |
| $\displaystyle f(x)=\frac{1}{x}$                   |$\displaystyle f'(x)=-\frac{1}{x^2}$                              |

^58a659

>[!info] Potenzgesetze
>$\displaystyle a^{n}\cdot a^{m}= a^{n \ + \ m}$
>$\displaystyle a^{n} : a^{m}= a^{n\ -\ m}$
>$\displaystyle (a^{n})^m= a^{n\ \cdot \ m}$

^254773