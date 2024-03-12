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
$$\vec{a}+\vec{b}=\begin{pmatrix}
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
    

## Vinkel mellem vektorer
Hvis 2 vektorer udspringer fra samme punkt, så kan man udregne vinklen mellem dem således:  
$$cos(v)=\frac{\vec{a}*\vec{b}}{\vec{|a|}*\vec{|b|}} $$
$$\vec{a},\vec{b}\neq\vec{0}$$

## Projektion af vektor på vektor
