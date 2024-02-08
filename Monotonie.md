---
cssclasses: hide_properties
tags: [Mathe, TBD, Wiederholung-EF]
---

# [[Mathe-Oberstufe Verzeichnis#Wiederholung - EF|Zurück]]

___
# Definition

>[!important] Merke
>Unter Monotonie versteht man den **Verlauf** einer Funktion. Sie **gibt an**, ob die Funktion **steigt**, **fällt** oder **konstant** verläuft.
>
>Seien $x_1$ und $x_2$ zwei Stellen einer Funktion, wobei $x_1<x_2$. Dann unterscheidet man anhand der dazugehörigen Funktionswerte $f(x_1)$ und $f(x_2)$ verschiedene Fälle der Monotonie.
>- Ist $f(x_1) < f(x_2)$, dann ist f **streng monoton steigend**,
>- ist  $f(x_1) \leq f(x_2)$, dann ist f **monoton steigend**,
>- ist $f(x_1) > f(x_2)$, dann ist f **streng monoton fallend**,
>- ist $f(x_1) \geq f(x_2)$, dann ist f **monoton fallend**.

<BR>

___
# Monotonie bestimmen

>[!info] Anleitung
>1. Berechne die ersten zwei Ableitungen $f^{\prime}(x)$ und $f^{\prime \prime}(x)$.
>2. Bestimme die [[Nullstellen]] $x_0$ von $f^{\prime}(x)$
>3. Setze die Extremstellen in die zweite Ableitung $f^{\prime \prime}(x)$ ein, um die Art der Extrempunkte zu bestimmen
>4. | $f^{\prime \prime}(x_0) < 0$                                         | $f^{\prime \prime}(x_0)>0$                                           | $f^{\prime \prime}(x_0)=0$                |
| -------------------------------------------------------------------- | -------------------------------------------------------------------- | ----------------------------------------- |
| Hochpunkt: Erst streng monoton steigend, dann streng monoton fallend | Tiefpunkt: Erst streng monoton fallend, dann streng monoton steigend | Sattelpunkt: keine Änderung der Monotonie |                                                              |                                                                      |                                           |

<BR>

>[!write] Beispiel
>Schauen wir uns als Beispiel die folgende Funktion an
>
$f(x) = -3x^5 + 5x^3$.
>
Sie besitzt die Ableitungen 
>
$f^{\prime}(x) = -15x^4 +15x^2$
>
$f^{\prime \prime}(x) = -60x^3 + 30x$
>
und die Extremstellen
>
$x_1 = -1, x_2 = 0 und x_3 = 1$
>
Setzt du die Extremstellen in die zweite Ableitung ein, so erhältst du
>
$f^{\prime \prime}(-1) = -60 \cdot (-1)^3 + 30 \cdot (-1) = 30 \Rightarrow Tiefpunkt$
>
$f^{\prime \prime}(0) = -60 \cdot 0^3 + 30 \cdot 0 = 0 \Rightarrow Sattelpunkt$
>
$f^{\prime \prime}(1) = -60 \cdot 1^3 + 30 \cdot 1 = -30 \Rightarrow Hochpunkt$
>

___

>[!attention] Achtung
>Unvollständig: weitere Bearbeitung [hier](https://studyflix.de/mathematik/monotonie-2157)
