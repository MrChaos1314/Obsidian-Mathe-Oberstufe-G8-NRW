#Mathe #Wiederholung-EF 

# [[Mathe-Oberstufe Verzeichnis#Wiederholung - EF| Zurück]]

___
# Inhaltverzeichnis - Symmetrie

- [[Symmetrie#Definition|Definition]]
- [[Symmetrie#Bestimmung der Symmetrie|Bestimmung der Symmetrie]] 
- [[Symmetrie#Achsensymmetrisch zur y-Achse|Achsensymmetrisch zur y-Achse ]]
- [[Symmetrie#Punktsymmetrisch zum Ursprung|Punktsymmetrisch zum Ursprung]]
- [[Symmetrie#Berechnung mit dem CAS|Berechnung mit dem CAS]]

___
# Definition

>[!hint] Definition
>Bei der Symmetrie von Funktionen unterscheidest du zwischen zwei Arten: Die **Achsensymmetrie** und die **Punktsymmetrie**.

<br>

___
# Bestimmung der Symmetrie

>[!info] Symmetrie von Funktionen bestimmen
>Um das Symmetrieverhalten zu bestimmen, musst du dir immer $f(-x)$ anschauen:
>
>- Die Funktion ist *achsensymmetrisch* zur **y-Achse**, wenn $f(-x) = f(x)$
>\
>**Beispiel** mit $f(x) = x²$:     $f(-x) = (-x)² = x² = f(x)$
>    &nbsp
>- Die Funktion ist **punktsymmetrisch** zum **Ursprung**, wenn $f(-x) = -f(x)$
>    \
>    **Beispiel** mit $f(x) = x³$:      $f(-x) = (-x)³ = -x³ = -f(x)$     

<br>

___
# Achsensymmetrisch zur y-Achse

>[!info] Achsensymmetrie zur y-Achse zeigen
>Rechnerisch muss hier gelten: $f(-x) = f(x)$. Um das für alle $x$ zu zeigen, gehst du am besten so vor:
>
>1. $f(-x)$ **aufstellen**. Du ersetzt überall $x$ mit $-x$.
>1. **Vereinfachen**
>1. **Prüfen**, ob $f(x)$ rauskommt

<br>

>[!write]- Beispiel 
>$f(x) = x^4-2x^2-3$
>1. $f(-x)$ **aufstellen** $f(-x) = (-x)^4-2(-x)^2-3$ 
>2.  **Vereinfachen** $(-x)^4-2(-x)^2-3 = x^4-2x^2-3$
>3.  **Prüfen**, ob $f(x)$ rauskommt $x^4-2x^2-3 = f(x)$
>
>Graph:
>![[Pasted image 20231226130107.png|200]]

<br>

>[!hint] Gerade Exponenten
>Ganzrationale Funktionen der Form $a_nx^n + a_{n-1}x^{n-1} +…+ a_0$ sind genau dann **achsensymmetrisch** zur y-Achse, wenn sie nur **gerade Hochzahlen** haben!
>
>$2x^4+3x^2+\textcolor{red}{2}$ ist also **achsensymmetrisch** zur y-Achse, da $x^4$, $x^2$ und $x^0$ (die $\textcolor{red}{2}$ ist eigentlich $2x^0$, da $x^0=1$) gerade Hochzahlen haben.
>
>>[!Danger] Beachte
>$2x^4+3x+1$ ist **nicht** achsensymmetrisch zur y-Achse, da $x^1$ (also $x$) eine **ungerade Hochzahl** hat. Ihr Symmetrieverhalten ist **weder** punkt- **noch** achsensymmetrisch.

<br>

___
# Punktsymmetrisch zum Ursprung

>[!info] Punktsymmetrie zum Ursprung zeigen
>Rechnerisch muss hier für alle $x$ gelten: $f(-x) = -f(x)$. Um das schnell zu überprüfen, gehst du so vor:
>
>**$f(-x)$ aufstellen**. Das heißt, überall $x$ mit $-x$ ersetzen.
>
>1. **Vereinfachen.**
>2. Ein **Minus ausklammern**.
>3. **Prüfen**, ob du $-f(x)$ hast.

<br>

>[!write]- Beispiel 
>$f(x) = x^5+2x^3-x$
>1. **$f(-x)$ aufstellen.** $f(-x)=(-x)^5+2(-x)^3-(-x)$
>2. **Vereinfachen.** $(-x)^5+2(-x)^3-(-x)=-x^5-2x^3+x$
>3. Ein **Minus ausklammern.**  $-x^5-2x^3+x = – (x^5+2x^3-x)$
>4. **Prüfen**, ob du **$-f(x)$** hast. $– (x^5+2x^3-x) = -f(x)$
>
>Graph:
>![[Pasted image 20231226132144.png|200]]

<br>

>[!hint] Ungerade Exponenten
>Ganzrationalen Funktionen der Form $a_nx^n+a_{n-1}x^{n-1}+…+a_0$ sind genau dann punktsymmetrisch zum Ursprung, wenn sie nur **ungerade Hochzahlen** haben!
>
>>[!success] Anwendbar
>>- $3x^3+2x$ ist **punktsymmetrisch** zum Ursprung, da $x^3$ und $x^1$ ungerade Hochzahlen haben.
>
>$\quad$
>
>>[!failure] Nicht Anwendbar
>>- $3x^3+2x^2+x$ ist **nicht punktsymmetrisch** zum Ursprung, da $x^2$ eine gerade Hochzahl hat. 
>>- $3x^3+2$ ist **nicht punktsymmetrisch** zum Ursprung, da die $2 = 2x^0$ eine gerade Hochzahl hat.

<br>

___
# Berechnung mit dem CAS

![[CAS-Befehle#Symmetrie berechnen]]