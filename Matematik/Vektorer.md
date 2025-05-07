# Vektorer i 2D

vektorer skrives således:
$$\vec{a}$$
Vektorer består af 2 koordinater, som beskriver hvor lang den er på x og y aksen, ligesom et punkt i et koordinatsystem. forskellen er bare at det samme vektor kan have uendeligt mange positioner.
$$\vec{a}=\begin{pmatrix}
a_1 \\
a_2 \\
\end{pmatrix}$$

## Ensrettede og modsatrettede vektorer
* To vektorer som peger samme vej og er parallelle er ensrettede vektorer. To vektorer som pejer hver sin vej og er parallelle er modsatrettede vektorer. 

## Nulvektorer og egentlige vektorer

**Nulvektor:**

$$\vec{0}=\begin{pmatrix}
0\\
0\\
\end{pmatrix}$$

* Alle vektorer, som ikke er nulvektoren, er en egentlig vektor.

## Stedvektor
Hvis man vil tegne en vektor til et punkt i planen fra (0,0), så bruger man en stedvektor:

$$\vec{AB}$$

Stedvektoren til et punkt har samme koordinater som punktet selv.

$$A = (a_1,a_2)$$
$$\vec{OA}=\begin{pmatrix}
a_1\\
a_2\\
\end{pmatrix}$$

## Tværvektor
Formel for tværvektor: (hatte vektor)
$$\hat{\vec{a}}=\begin{pmatrix}
-a_2\\
a_1\\
\end{pmatrix}$$

## Vektor mellem 2 punkter
Formel:

$$\vec{AB}=\begin{pmatrix}
x_B-x_A\\
y_B-y_A\\
\end{pmatrix}$$
når man har en vektor mellem 2 punkter, så skriver man det punkt man går fra først, og den punkt man går hen til sidst. ovenover går man fra A til B. 

## Længde af vektor
Formel:
$$|\vec{a}|=\sqrt{a^2_1+a^2_2}$$

Vektor mellem 2 punkter:

$$\vec{|AB|}=\sqrt{(b_1-a_1)^2+(b_2-a_2)^2}$$


## Regne med vektorer

Addition:
$$\vec{a}+\vec{b}=\begin{pmatrix}
a_1+b_1\\
a_2+b_2\\
\end{pmatrix}$$

Subtraktion:
$$\vec{a}-  \vec{b}=\begin{pmatrix}
a_1-b_1\\
a_2-b_2\\
\end{pmatrix}$$

Gange:
$$t*\vec{a}=\begin{pmatrix}
t*a_1\\
t*a_2\\
\end{pmatrix}$$
* $t$ er det tal man vælger at gange med. 

## Skalarprodukt
Man kan ikke gange vektorer sammen, så derfor finder man skalarproduktet istedet. Det giver et tal. 
$$\begin{pmatrix}
a_1\\
a_2\\
\end{pmatrix}*\begin{pmatrix}
b_1\\
b_2\\
\end{pmatrix}=a_1*b_1+a_2*b_2$$

Regneregler for skalarprodukt:
$$\vec{a}*\vec{b}=\vec{b}*\vec{a}$$
$$\vec{a}*(\vec{b}+\vec{c})=\vec{a}*\vec{b}+\vec{a}*\vec{c}$$
$$\vec{a}*\vec{a}=|\vec{a}|^2$$

## Vinkel mellem vektorer
Hvis 2 vektorer udspringer fra samme punkt, så kan man udregne vinklen mellem dem således:  
$$cos(v)=\frac{\vec{a}*\vec{b}}{\vec{|a|}*\vec{|b|}} $$
$$\vec{a},\vec{b}\neq\vec{0}$$

En hurtig måde at finde ud af om en vinkel er spids, ret, eller stump, lyder sådan her:
$$\vec{a}*\vec{b}>0=spids$$
$$\vec{a}*\vec{b}<0=stump$$
$$\vec{a}*\vec{b}=0=ret$$


## Projektion af vektor på vektor
$$\vec{a}_{\vec{b}}=\frac{\vec{a}*\vec{b}}{|\vec{b}|^2}*\vec{b}$$
* resultatet er 2 punkter til en vektor, ikke et tal.
* den lille vektor er den vektor som projektionen er parallel med, og den anden er den vektor som definerer længde og retning.

## Længde af projektion
$$|\vec{a}_{\vec{b}}|=\frac{|\vec{a}*\vec{b}|}{|b|}$$
* resultatet er et tal.

## Beskrive vektor med vinkel og længde 
$$\vec{a}=62∠37,5$$
$$a=tan(V)$$
det hedder polære koordinater
$$\vec{a}=\begin{pmatrix}
x_a\\
y_a\\
\end{pmatrix}$$
det hedder kartesiske koordinater


### Kartesiske til polære koordinater
man udregner længden af sin vektor, og finder tangens til vinklen til det, og tager $tan^{-1}$, og så har man vinklen og længden. 

### Polære til kartesiske koordinater

man tager og siger sin og cos til sin vinkel, og ganger det med længden af ens vektor. 

**Polære koordinater:**
$$r=\sqrt{x^2+y^2}$$
$$θ=tan^{-1}(\frac{y}{x})$$
**$x$ og $y$ koordinater:**
$$x=r*cosθ$$
$$y=r*sinθ$$

## Determinant
$$det(\vec{a}, \vec{b})=\hat{\vec{a}}*\vec{b}=a_1b_2-a_2b_1$$

### Areal og determinant
Arealet af en determinant af 2 vektorer, er lig med den numeriske værdi af determinanten.

## finde funktion ud fra normalvektor og punkt. 
$$a(x-x_0)+b(y-y_0)=0$$

Hvis man kender en normalvektor til en linje, og man kender et punkt på linjen ($P_0$), kan man regne funktionen ud med ovenstående formel.

Vektorer er ortogonale, hvis deres indre produkt er nul.

## Komposanter
* Vi har opløst $\vec{a}$ i 2 komposanter $\vec{v}$ og $\vec{w}$

en komposant er en del af det, som man beskriver en vektor med. f.eks beskriver man ovenstående a med 2 komposanter: v og w.    

## Bevis af Projektion af vektor på vektor



Vigtig måde at conceptualisere vektorer på, er at vektoren skalerer en enhedsvektor på hver akse. x-akse enhedsvektoren hedder i, og y-akse vektoren hedder j. det vil sige at en vektor med 2 på x & 3 på y vil skalere i med 2 og j med 3. De kaldes basisvektorer. 

span er hvor meget af ens koordinatsystem man kan nå med sine basisvektorer. hvis ens basisvektorer i 2D peger i hver sin retning, så kan man nå hele koordinatsystemet. Hvis det peger i samme retning, kan man nå alle punkter på den linje. 

Det fungerer også i 3D, hvor 2 vektorer bare giver dig en  plan i 3D space. 


### Vektor Linear transformation

* Vektor input til vektor output - grunden til man siger transformation er fordi man skal forestille sig bevægelse. 
* En transformation er kun linear, hvis alle linjer ikke kurver, og hvis origin er det samme sted. Det holder linjer parallelle & med ens mellemrum.