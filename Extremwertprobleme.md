#Unterthema 

# [[Ganzrationale Funktionen|Zurück]]

___
# Strategie

>[!success] Lösen von Extremwertproblemen mit Nebenbedingungen
>1.  Beschreiben der Zielgröße, die extremal werden soll, durch eine Formel.
>   Diese kann mehrere Variablen enthalten
>2. Aufsuchen von Nebenbedingungen, die Abhängigkeiten zwischen den Variablen enthalten.
>3. Bestimmen der Zielfunktion, die nur noch von einer Variablen abhängt (welche zweckmäßig ist, zeigt oft erst die Bearbeitung). Angeben des Definitionsbereichs der Zielfunktion.
>4. Untersuchen der Zielfunktion auf Extremwerte unter Beachtung der Ränder des Definitionsbereichs. 
>   Formulieren des Ergebnisses.

<br>

>[!Attention] Eigene Bemerkung
>Extremwertprobleme sind Übungssache.
>
>Sprich:
>Für ein besseres Verständnis → Übungen durchgehen
>
>Eine Skizze kann sehr nützlich sein!

<br>

___
# Beispiel

>[!write] Beispiel
>Ein rechteckiges Spielfeld mit Länge x und Breite y soll von einer 400m langen, an den kurzen Rechtecksseiten halbkreisförmigen Laufbahn umgeben sein.
>- Bestimme die Abmessungen, für die das Spielfeld maximalen Flächeninhalt hat.

<br>

>[!success]- Lösung
>![[Extremwertprobleme#^b9ecff]]

<br>

___
# Annotation

| Vorgehen | Berechnung |
| ---- | ---- |
| <br>Gleichung<br><br> | <br>A=<span style="color:#00b0f0">x</span><span style="color:#ff0000">y</span> (x und y in Metern) |
| <br>Aufstellen der Nebenbedingung | <br>Nebenbedingung:<br>$u={\color{cyan}{2x}}+{\color{lime}{\pi y}}=400$<br>$\displaystyle \color{red}{y=\frac{400}{\pi}-\frac{2}{\pi}x}$<br><br> |
| <br>Zielfunktion und Definitionsbereich<br><br> | <br>$\displaystyle A(x)={\color{cyan}{x}}\left({\color{red}{\frac{400}{\pi}-\frac{2}{\pi}x}}\right)=\frac{400}{\pi}x-\frac{2}{\pi}x^2$ <br><br>mit $0 \leq x \leq 200$<br><br> |
| <br>Bestimmung des lokalen Maximums<br><br> | <br>Ableitung bestimmen:<br>$\displaystyle A'(x)=\frac{400}{\pi}-\frac{4}{\pi}x$ und $\displaystyle A''(x)=-\frac{4}{\pi}$<br><br>Wegen $\displaystyle A''(100)=-\frac{4}{\pi} < 0$ liegt ein lokales Maximum vor.<br><br>$\displaystyle A(100)=\frac{400}{\pi}\cdot 100^{2}-\frac{2}{\pi} \cdot 100^{2}\approx 6366.2$<br><br> |
| <br>Randwerte prüfen, globales Maximum | <br>$A(0)=A(200)=0 < 6366.2$, also kein Randmaximum.<br>Das Lokale Maximum bei $x=100$ ist auch globales Maximum.<br><br> |
| <br>Interpretation | <br>$x=100$ in die Nebenbedingung einsetzen:<br>$\displaystyle y=\frac{400}{\pi}-\frac{2}{\pi} \cdot 100\approx 63.7$<br><br>Für eine Länge von 100m und eine Breite von 63.7m wird der Flächeninhalt des Spielfelds mit $A\approx 6366.2m^2$ maximal.<br><br> |

^b9ecff

