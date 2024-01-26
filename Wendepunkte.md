#Unterthema 

# [[Ganzrationale Funktionen|Zurück]]

___
# Definition

>[!hint] Wendepunkte
>Ein Wendepunkt ist der **Punkt an dem der Funktionsgraph sein Krümmungsverhalten ändert**. 
>
Der Graph wechselt hier entweder von einer Linkskurve in eine Rechtskurve oder umgekehrt. 
>
Dieser Wechsel wird auch Bogenwechsel genannt.

<br>

___
# Berechnung

>[!hint] Vorgehen
>1. Bestimme die zweite und dritte [[Ableitung]] der Funktion $f$.
>
>2. Setze die zweite Ableitung gleich $0$: **$f''(x) = 0$**
>
>3. **Setze die Nullstellen** der zweiten Ableitung in die dritte Ableitung **ein**.
>
>4. Setze die Nullstellen der zweiten Ableitung in die ursprüngliche Funktion f(x) ein. 
>
>5. Bestimme die **Art des Wendepunktes**. Es gilt:
>   - $f'''(x) > 0$: 
>     _Die Kurve geht von rechts nach links. (Rechts-links-Wendepunkt)_
>$\quad$
>
>   - $f'''(x) < 0$: 
>     _Die Kurve geht von links nach rechts. (Links-rechts-Wendepunkt)_
>     $\quad$
>   - $f'''(x)=0$
>
>>[!write]- Beispiel
>>$f(x) = x^3 -3x^2$
>>
>>1. Als Erstes berechnen wir die ersten drei Ableitungen der Funktion mit den [[Ableitung#Ableitungsregeln|Ableitungsregeln]].
>> 
>> - $f'(x) = 3x^2 – 6x$
>> - $f''(x) = 6x – 6$
>> - $f'''(x) = 6$
>>
>><br>
>>
>>2. Nun setzen wir die zweite Ableitung gleich null und ermitteln die x-Werte:
>>   
>> - $f''(x)=0$
>> - $6x – 6 = 0$
>> - $x = 1$
>>
>><br>
>>
>> 3. Um zu überprüfen, ob es sich tatsächlich um eine Wendestelle handelt, setzt du den Punkt in die dritte Ableitung ein.
>>   
>> - $f'''(1) = 6 ≠ 0$
>>
>> Die dritte Ableitung ist ungleich null und damit hast du bei $x = 1$ eine Wendestelle berechnet.
>>
>>&nbsp;
>>
>>4. Du weißt nun, dass bei **$x = 1$** eine Wendestelle existiert. Setze jetzt den x-Wert in die Funktion $f$ ein, um so die y-Koordinate des Wendepunktes zu ermitteln.
>> 
>> - $f(1) = 1^3 – 3 · 1^2 = -2$
>>
>> Insgesamt haben wir damit den Wendepunkt an der Stelle **$W (1|-2)$** bestimmt.
>
>
Ist die dritte Ableitung gleich $0$, kann es sein, dass überhaupt kein Wendepunkt vorliegt. 
Um das zu testen, benutzt du die **zweite Ableitung**. Mit ihr kannst du die Krümmung deines Graphen an verschiedenen Stellen herausfinden.
>
>>[!write]- Beispiel
>>Du hast einen **möglichen Wendepunkt** bei $x = 0$ gefunden, doch die dritte Ableitung ist **gleich $0$**. 
>>
>>Um zu testen, ob es sich wirklich um einen Wendepunkt handelt, wählst du zwei Stellen aus, die auf dem Graphen links und rechts von $x = 0$ liegen.
>> 
>>Zum Beispiel $x = -1$ und $x = 1$. Die setzt du dann in $f''(x)$ ein:
>>
>>- Ist die zweite Ableitung **größer $0$**, ist die Kurve **linksgekrümmt**.
>>- Ist die zweite Ableitung **kleiner $0$**, ist die Kurve **rechtsgekrümmt**.
>
>$\qquad$
>
>>[!Attention] Achtung
>>Gibt es keinen Vorzeichenwechsel, herrscht links und rechts von $x = 0$ dieselbe Krümmung. 
  >Es handelt sich also **nicht** um einen Wendepunkt!
>
>
>### Wendepunkt - Notwendige Bedingung
>
>- $f''(x) = 0$
>
>### Wendepunkt - Hinreichende Bedingung
>
>- $f'''(x)≠ 0$
>
>>[!Attention] Achtung
>>Wenn die dritte Ableitung **gleich $0$** ist, kann es sich um einen Sattelpunkt handeln: 
>>Das ist auch ein Wendepunkt, jedoch ist beim Sattelpunkt zusätzlich die **Steigung**, also die erste Ableitung, **gleich $0$**!

