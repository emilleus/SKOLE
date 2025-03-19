# Calculus

## Differentialregning

### Tretrinsreglen
$$Δy=f(x_0-h)-f(x_0)$$
$$a_s=\frac{Δy}{h}$$
$$a_t=\lim_{h\to0}(a_s)$$

* $Δy$ = funktionstilvæksten
* $x_0$ = fast punkt
* $h$ = dynamisk afstand
* $a_s$ = differenskvotienten, sekant
* $a_t$ = differentialkvotienten, tangent

### Afledede funktioner: 


|$f(x)$|$f'(x)$|
|-|-|
|$x$|$1$|
|$x^n$|$nx^{n-1}$|
|$\frac{1}{x}$|$-\frac{1}{x^2}$|
|$\sqrt{x}$|$\frac{1}{2\sqrt{x}}$|
|$kx$|$k$|
|$k$|$0$|
|$e^x$|$e^x$
|$e^{kx}$|$k*e^{kx}$|
|$ln(x)$|$\frac{1}{x}$
|$a^x$|$a^xln(a)$

### Tangentens ligning

$$y=f(x_0)+f'(x_0)*(x-x_0)$$

* når man finder tangenten på den her måde, skal man bruge et punkt med et x koordinat, og så funktionen af x koordinatet.

### Monotoniforhold

Monotoniforhold handler om hvornår ens funktion er voksende, aftagende, eller på et vendepunkt. Man skriver monotonisætningerne således: 

* $f′(x)>0$ for alle $x∈]a,b[⇒f$ voksende på $ ]a,b[$
* $f′(x)<0$ for alle $x∈]a,b[⇒f$ aftagende på $]a,b[$
* $f′(x)=0$ for alle $x∈]a,b[⇒f$ konstant på $]a,b[$

Hvad sætningen ovenover betyder, for alle værdier over x, så er grafen voksende, og så lign med de andre udtryk. 

Man kan hurtigt se hvor en funktion er voksende og aftagende ved at ploppe den differentierede funktion ind i en graf.

* Man kan ikke differentiere en kurve, hvis den har et knæk i sig, eller hvis den ikke er kontinuerlig.
* den differentierede funktion beskriver hvad hældningen på stamfunktionen er i det punkt. 

### Sumreglen

$$h(x)=f(x) \pm g(x) \rightarrow h'(x)=f'(x) \pm g'(x)$$

### Konstantreglen

$$g(x)=k*f(x) \rightarrow g'(x)=k*f'(x)$$

### Produktreglen

$$h(x)=f(x)*g(x) \rightarrow h'(x)=f'(x)*g(x)+f(x)*g'(x)$$

* Man kan også huske reglen på at man skal "diffe, beholde + beholde, diffe"
* Hvis man vil gange nogle specielle matematiske udtryk, såsom den naturlige logaritme, så skal man differentiere dem hver for sig, og så bruge produktreglen til sidst. 

### Kvotientreglen

$$h(x)=\frac{f(x)}{g(x)} \rightarrow h'(x) = \frac{f'(x)*g(x)-f(x)*g'(x)}{(g(x))^2}$$


### Tangentens ligning

hvis funktionen f er differentiabel i punktet $(x_0f(x_0))$ - dvs at der ikke er et knæk i det punkt, så er ligningen for tangenten i det punkt givet ved

$$y = f(x_0)+f'(x_0)*(x-x_0)$$

Man kan komme frem til den her formel ved at tage udgangspunkt i formlen for den rette linje, og erstatte de 2 faste punkter med 1 fast punkt $(x_0\space \& \space y_0)$, samt 2 dynamiske punkter (x & y). Derefter skal man bare isolere y, samt erstatte $a$ med $f'(x)$.

### Grænseværdier

det er det som jeg kender som limits

$$\lim_{x\to a}$$
$$\lim_{x\to \infty}\frac{1}{x^2}=\infty$$

grænseværdien kan være forskellige alt efter om man tager den fra venstre eller højre. det betyder at der også kan være 2 forskellige løsninger: 

$$\lim_{x\to 4+}$$
$$\lim_{x\to 4-}$$


## Integralregning

### Stamfunktion
Hvis den oprindelige funktion hedder $f$, så hedder stamfunktionen $F$. 

man kan sige, at $F$ er en stamfunktion til $f$, hvis:
$$F'(x)=f(x)$$

#### Uendeligt mange stamfunktioner
alle konstanter, dvs ting i funktionen uden et x, bliver glemt når man finder stamfunktionen. dvs at hvis man differentierer $x^2$ og $x^2 +4$, så får man det samme resultat, $2x$. Derfor skriver man $+c$ for at vise de forskellige mulige stamfunktioner. 

### Ubestemt integral

$$\int{f(x)dx}=F(x)$$

* husk $c$ på slutningen, for at sige at der er integrationskonstant på. 

### Integrerede funktioner
|$f(x)$|$F(x)$|
|-|-|
|$x$|$\frac{1}{2}x^2$|
|$kx$|$\frac{k}{2}x^2$|
|$k$|$kx$|
|$x^n$|$\frac{1}{n+1}x^{n+1}$
|$\frac{1}{x}$|$ln(\|x\|)$
|$a^x$|$\frac{a^x}{ln(a)}$
|$e^x$|$e^x$
|$e^{kx}$|$\frac{1}{k}*e^x$
|$\sqrt{x}$|$\frac{2}{3}x^{3/2}=\frac{2}{3}(\sqrt{x})^3 $
|$ln(x)$|$x*ln(x)-x$

### Regneregler for integraler

#### Sumreglen:
$$\int{f(x)+g(x)dx}=\int{f(x)dx}+\int{g(x)dx}$$

#### Differensreglen:
$$\int{f(x)-g(x)dx}=\int{f(x)dx}-\int{g(x)dx}$$

#### Produkt af konstant og funktion
$$\int{c*f(x)dx}=c*\int{f(x)dx}$$

### Bestemt integral og areal
* Forskellen på en ubestemt og en bestemt integral er at i den ubestemte finder man frem til en funktion, hvor i den bestemte finder man frem til et tal.
* det tal man finder frem til er lig med arealet under en funktion, hvis hele området man udregner er over 0 på y-aksen.

$$\int_a^b{f(x)dx}=[F(x)]^b_a=F(b)-F(a)$$

### Areal mellem 2 grafer

$$Areal_{fg}=\int_a^b{(f(x)-g(x))dx}$$

$a$ og $b$ er integrationsgrænser, og findes ved at sætte de 2 ligninger lig med hinanden, og så løse det som en andengradsligning.