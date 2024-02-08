---
cssclasses: hide_properties
tags: [LK, Unterthema]
---

# [[Ganzrationale Funktionen|Zurück]]

___
# Inhaltverzeichnis - Funktionenscharen

- [[Funktionenscharen#Definition|Definition]]
- [[Funktionenscharen#Beispiel|Beispiel]]
- [[Funktionenscharen#Ortskurve|Ortskurve]]
- [[Funktionenscharen#Funktionenschar - Gemeinsame Punkte|Funktionenschar - Gemeinsame Punkte]]

___
# Definition

>[!hint] Definition
>Enthält ein Funktionsterm außer der Variablen $x$ noch einen Parameter $a$, so gehört zu jedem $a$ eine Funktion $f_a$, die jedem $x$ den Funktionswert $f_a(x)$ zugeordnet. 
>
>Die Funktionen $f_a$ bilden eine **Funktionenschar**.
>
Die Koordinaten der charakteristischen Punkte des Graphen einer Funktionenschar hängen häufig von dem Parameter ab.
Für die Berechnung der Punkte werden die Parameter der Funktionen wie eine Zahl behandelt.

<br>

___
# Beispiel

>[!write] Aufgabe
>   **Gegeben** ist die **Funktionenschar** $f_a$ mit 
>   
>   $\qquad f_a(x)=x^3-3ax^2, a \neq 0$.
>   
>   **Bestimme** die **Nullstellen** sowie **Extrem**- und **Wendepunkte** von $f_a$.

<br>

>[!success]- Lösung
>![[Funktionenscharen#^4aca17]]

<br>
___
# Ortskurve

## Definition

>[!hint] Definition
>Für die Tiefpunkte der Graphen von $f_a$ mit 
>
$\qquad \qquad f_a(x) = \frac{1}{3a}x^3-x^2\ ($mit $a>0$ gilt $T_a(2a\mid -\frac{4}{3}a^2))$.
>
>Durchläuft der Parameter $a$ alle zugelassenen Werte, so liegen alle Tiefpunkte auf einer Kurve[^1]. 
Diese Kurve heißt **Ortskurve** oder **Ortslinie** der Tiefpunkte $T_a$.
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20231227231622.png|300]]
>

<br>

## Gleichung bestimmen

>[!info] Vorgehen
>1. x-Koordinate des Tiefpunktes nach dem Parameter umformen:
>   Mit $x=2a$ erhält man $\displaystyle a=\frac{x}{2}$
>
>2. Einsetzen des Terms in die y-Koordinate des Tiefpunktes:
>   $\displaystyle a=\frac{x}{2}$ in $\displaystyle y=-\frac{4}{3}a^2$ 
>   ergibt
>   $\displaystyle y=-\frac{4}{3}*\left(\frac{x}{2}\right)^2=-\frac{4}{3}*\frac{x^2}{4}=-\frac{1}{3}x^2$
>   
>   Alle Tiefpunkte liegen auf dem Graphen der Funktion $g$ mit $\displaystyle g(x)=-\frac{1}{3}x^2$

<br>

## Beispiel

>[!write] Aufgabe
>**Gegeben** ist die **Funktionenschar** $f_a$ mit 
>$\qquad \qquad f_a(x)=\frac{1}{2}x^4-ax^2$ für $a>0$.
>**Bestimme** die **Gleichung** der **Ortskurve** durch die **Tiefpunkte** der Graphen von $f_a$
>
>>[!info]- Graphische Darstellung
>>![[Pasted image 20231228001938.png|300]]

<br>

>[!success]- Lösung
>![[Funktionenscharen#^b00d22]]

<br>

___
# Funktionenschar - Gemeinsame Punkte

## Definition

>[!hint] Definition
>**Teilweise Verlaufen** alle Graphen einer **Funktionenschar** durch **einen** oder **mehrere gemeinsame Punkte**.
Der **Funktionswert** an dieser Stelle **hängt** dann **nicht vom Parameter ab**.

<br>

## Funktionswert bestimmen 

>[!info] Vorgehen
>Um **mögliche** gemeinsame Punkte zu finden, gehe wie folgt vor:
>1. Benenne den Parameter mit $a_1$ bzw. $a_2$ ($a_1 \neq a_2$)
>2. Überprüfe, ob die Gleichung $f_{a_1}(x)=f_{a_2}(x)$ **eine Lösung** hat, die **nicht vom Parameter abhängt**.

<br>

## Beispiel

>[!write] Aufgabe
>Gegeben ist die Funktionenschar $f_a$ mit
>
>$\qquad \qquad f_a(x)=x^3-ax^2-x+a$
>
>Ermittle die Funktionswerte der gemeinsamen Punkte der Funktionenschar $f_a$.
>
>>[!info] Graphische Darstellung
>>![[Pasted image 20231228010121.png|200]]

<br>

>[!success]- Lösung
>![[Funktionenscharen#^023300]]

<br>

___
# Annotation

|  |  |
| ---- | ---- |
| <br>Setze $f_a(x)$ gleich null. <br>Klammere $x^2$ aus und wende den Satz vom [[Nullstellen#^935fdd\|Nullprodukt]] an. | <br>**Nullstellen:**<br>$f_a(x)=x^2(x-3a)=0$<br><br>$x=0$ oder $x =3a$<br><br>$f'_a(x)=3x^2-6ax$<br>$f''_a(x)=6x-6a$<br><br> |
| <br>Beim **Ableiten** wird $a$ wie eine **Konstante** **behandelt**.<br><br>**Bestimme** die **Nullstellen** von $f'_a$ und **setze** diese in $f''_a(x)$ **ein**.<br><br><br>Das **Vorzeichen** von $f''(a)$ hängt von der **Wahl** des **Parameters** $a$ ab.<br>Mache eine **Fallunterscheidung** und gebe für **jeden Fall** die **Hoch-** und **Tiefpunkte** an. | <br>**Extrempunkte:**<br>$f'_a(x)=3x(x-2a)=0$<br><br><br>$x=0$ mit $f''_a(0)=-6a$ <br>und<br>$x=2a$ mit $f''_a(2a)=6a$<br><br>Für $a<0$: <br>$f''_a(0)>0$ und $f''_a(2a)<0$<br>Tiefpunkt $T(0\mid 0)$, <br>Hochpunkt $H_a(2a\mid -4a^3)$ <br>                                                                                                <br>Für $a>0$: <br>$f''_a(0)<0$ und $f''_a(2a)>0$<br>Hochpunkt $H(0\mid 0)$, <br>Tiefpunkt $T_a(2a\mid -4a^3)$<br><br>‎  |
| <br>Die **Nullstellen** von $f''_a$ liefert **für jedes** $a$ einen **Wendepunkt** | <br>**Wendepunkt:**<br>$f''_a(x)=6(x-a)=0$<br><br>$x=a;$ <br>$f'''_a(a)=6;$ <br>Wendepunkt $W_a(a\mid -2a^3)$<br><br> |
^4aca17

|  | <br>$f'_a(x)=2x^3-2ax=2x(x^2-a)$<br><br> |
| ---- | ---- |
| <br>Die **Nullstellen** der **ersten Ableitung** sind Kandidaten für die **Extremstellen**.<br><br>**Setze** die **Nullstellen** in die **zweite Ableitung ein**, um zu **prüfen**, ob und um welche **Art** **Extremum** es sich handelt. | <br>**Nullstellen von** $f'_a$:<br>$x_1=0;\ x_2=\sqrt{a};\ x_3=-\sqrt{a}$<br><br>$f''_a(x)=6x^2-2a$<br><br>$f''_a(0)=-2a<0,\ da\ a>0\ (HP)$<br>$f''_a(-\sqrt{a})=4a>0,\ da\ a>0\ (TP)$<br>$f''_a(\sqrt{a})=4a>0,\ da\ a>0\ (TP)$<br><br>**Tiefpunkte:** $\displaystyle T_1(\sqrt{a}\mid -\frac{a^2}{2});\ T_2(-\sqrt{a}\mid -\frac{a^2}{2})$<br>&nbsp; |
| <br>**Stelle** die Gleichung für die **$x$-Koordinate** nach $a$ **um**.<br><br>Durch **Einsetzen** in die Gleichung für die **$y$-Koordinate** ergibt sich die Gleichung der **Ortskurve**. | <br>$\begin{align} x &= \pm \sqrt{a} \mid \ ^2 \\ x^2 &= a \\ a &= x^2 \end{align}$<br><br>$\displaystyle y=-\frac{a^2}{2}$<br><br>$a=x^2$ in $y$ einsetzen<br><br>$\displaystyle y=-\frac{(x^2)^2}{2}=\frac{x^4}{2}$<br><br> |
|  | <br>**Gleichung der Ortskurve:**<br><br>$\displaystyle t(x)=-\frac{x^4}{2}$<br><br> |

^b00d22

|  |  |
| ---- | ---- |
| <br>Funktionswert zweier beliebiger Funktionen der Schar mit $a_1$ und $a_2$ müssen gleich sein.<br>&nbsp; | <br>$f_{a_1}(x)=f_{a_2} \ (a_1 \neq a_2)$<br><br>$x^3-a_1x^2-x+a_1=x^3-a_2x^2-x+a_2$<br> |
| <br>Durch Auflösen nach $x$ erhält man die $x$-Koordinaten des Schnittpunktes zweier beliebiger Funktionen der Schar.<br>&nbsp; | <br>$\begin{align} x^3-a_1x^2-x+a_1&=x^3-a_2x^2-x+a_2 \quad \mid -x^3+x \\ \\ -a_1x^2+a_1&=-a_2x^2+a_2 \qquad \ \qquad \mid -a_1+a_2x^2 \\ \\a_2x^2-a_1x^2&=a_2-a_1 \\ \\ x^2\cdot (a_2-a_1)&=a_2-a_1 \qquad \qquad \qquad \mid :(a_2-a_1) \\ \\ x^2&=\frac{a_2-a_1}{a_2-a_1} =1 \end{align}$ |
| <br>Die Lösung hängt nicht von $a_1$ oder $a_2$ ab.<br>&nbsp; | <br><br>$\quad \qquad \qquad \qquad x_1=1; \ x_2=-1$<br><br><br> |
| Alle Graphen Verlaufen durch $S_1(1\mid 0)$ und $S_2(-1\mid 0)$ | <br>$f_a(1)=0; \ f_a(-1)=0$<br><br> |

^023300


<br>

___