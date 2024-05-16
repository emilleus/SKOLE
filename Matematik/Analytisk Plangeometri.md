## Analytisk Plangeometri
* Foregår i et koordinatsystem
* man noterer punkterne: $A(3;6)$
* hvis man skal skrive længden fra et punkt til et andet, skriver man det sådan her: $|AB|$. 

Formel for afstanden mellem 2 punkter:
$$|AB| = \sqrt{(y_2-y_1)^2+(x_2-x_1)^2}$$
$$|AB| = \sqrt{(y_A-y_B)^2+(x_A-x_B)^2}$$
$$|AB| = \sqrt{(Δy)^2+(Δx)^2}$$


Formel for at finde midtpunktet af $|AB|$:
$$M_{AB} = \bigg(\frac{x_1+x_2}{2};\frac{y_1+y_2}{2}\bigg)$$

* man skriver midtpunktet som $M_{AB}$  

### Rette linjer 

**ligningen for den rette linje:**

$$y=ax+b$$

### Linjers skæring 

* $l$ = linje

For at finde skæringspunktet mellem 2 rette linjer, skal man udregne det som 2 ligninger med 2 ubekendte. $x$ og $y$ er så koordinaterne på hvor de krydser. 

$$ m: x+2y-2=0$$
$$ l: y=-x+7$$


''
$$x+2y-2=0$$
$$x+2(-x+7)-2=0$$
$$x+(-2x)+14-2=0$$
$$-x+12=0$$
$$x=12$$

''

$$y=x+7$$
$$y=-12+7$$
$$y=-5$$

Skæringspunkt = $(12;-5)$

### Regne vinkler mellem 2 rette linjer. 

når man skal udregne vinklen mellem 2 rette linjer, skal man bruge tangens. Man dele vinklen i 2, så man skaber 2 retvinklede trekanter, og udregne dem hver for sig. 

Den modstående vinkel er lig med hældningskoefficienten, og den hosliggende vinkel er lig med 1. 

$$l: y=3x+\frac{1}{2}$$
$$m: y=-2x+-3$$

$$tanV_1= \frac{3}{1}=3$$
$$tan^{-1}(3)=71,57°$$

$$tanV_2= \frac{-2}{1}=-2$$
$$tan^{-1}(-2)=-63,44°$$

Derefter skal man tage den numeriske værdi af en vinkel minus den anden, så man er efterladt med en positiv vinkel.

$$tanV=V_1-V_2=71,57-(-63,44)=135°$$
* Den positive værdi af den ene vinkel minus den anden vinkel. 
* her tager man den _numeriske værdi._ det betyder at man tager tallet, om det er positivt eller negativt, og laver det positivt. 

* $V_1 = tan^{-1}(a_1)$
* $V_2 = tan^{-1}(a_2)$

første = 1,85°
anden = 45° 

### Projektion af punkt på linje
Hvis vi har en linje $m$ og et punkt $P$, der ikke nødvendigvis ligger på linjen $m$, kan vi tegne en linje $n$ fra dette punkt og ned til linjen, sådan at linjen $n$ står vinkelret på linjen $m$. Det punkt $p_0$, hvor linjen skærer linjen $m$, kalder vi _projektioen_ af punktet $p$ på linjen $m$. 


vinkelrette linjer med hældninger $a_1$ og $a_2$ =
$$a_1 *a_2=-1$$

$$a_1=\frac{-   1}{a_2}$$

* man kalder en linje som står vinkelret på en anden linje for en normal.

### Cirklens ligning

$$r=\sqrt{(x-a)^2+(y-b)^2}$$

* Man bruger $(a;b)$ istedet for $(x;y)$ når man har koordinaterne til centrum på en cirkel.  
* hvis man har et punkt som man vil se om ligger på cirkelperiferien, så kan man sætte sin $(x;y)$ værdier ind i formlen, for at tjekke om punktet ligger på cirkelperiferien.

for at finde ud af om punktet ligger indenfor radiussen af cirklen, så skal man regne det ud med $(x;y)$ værdier, og hvis den er mindre end radiussen, så er den indenfor, og hvis den er over radiussen, så er den udenfor. er den lig med, ligger den på cirkelperiferien.

**Opgaveeksempel:**
* $C=(3;4)$
* $r=6$

$$(x-a)^2+(y-b)^2=r^2$$

$$(x-3)^2+(y-4)^2=6^2$$

### Tangent til cirklen

* tangent er en linje som kun rører noget på et enkelt punkt.



## Funktioner
### Lineær funktion

$$f(x)=y$$
Lineære funktioner er når at funktionen ikke ændrer sig, men bare er en lige linje.    
$$y=ax+b$$
- a = hældningskoefficienten / stigningstallet, hvor meget y stiger for hver x.
- b = hvor i y aksen funktionen krydser 0x.

**Ligefrem proportionalitet**

ligefrem proportionalitet er det koncept, som de fleste lineære funktioner følger. det kan beskrives sådan her:
$$y = k * x$$
- k = konstant, hvor meget y værdien vokser ift. x.

**Omvendt proportionalitet**
Eksempel på funktion med omvendt proportionalitet:
$$y=\frac{1}{x}$$
man kan sige, at groft sagt, så ”y aftager i samme takt som x vokser”, hvilket betyder, at hvis x vokser med 5 gange, så bliver y 5 gange mindre.

**Beregning af stigningstallet & skæring på y-aksen ud fra 2 punkter**
$$a=\frac{y^2-y^1}{x^2-x^1}$$
$$b = y_1-a*x_1$$
- Hvis vi har 2 punkter, som hedder (9,3) og (6,5), så regner man det ud sådan her:
$$a=\frac{9-6}{3-5}$$
$$a=\frac{3}{-2}=-1,5x$$

derefter kan vi regne b ud sådan her:

$$b = 6-(-1,5)*5$$

**Opgave Eksempel: Lineære funktioner**

Du har et firma, og skal vælge mellem 2 fragtfirmaer til at levere varer: det ene firma vil have 17,54kr pr km kørt, og et opstartsgebyr på 222,67kr. det andet firma vil have 28,39kr pr km kørt, og kræver ikke noget opstartsgebyr. Vi skal finde ud af hvor mange km fragtfirmaerne skal køre, for at det koster det samme for dem begge.

1. først, så kan vi opstille funktionsforskrifterne for begge fragtfirmaer. Det ser sådan her ud:
$$Firma \;1:f(x)=17,54x+222,67$$
$$Firma\:2:f(x)=28,39x$$

2. fordi vi ved at f(x) er det samme som y, så kan man også skrive det sådan her:
$$y = 17,54x+222,67$$
$$y = 28,39x$$

3. derefter skal man opsætte dem som 2 ligninger med 2 ubekendte, sådan her:
$$y = 17,54x+222,67\; |\; y = 28,39x$$

4. så kan man bare gå i gang med at løse den som en andengradsligning, sådan her:
$$y = 17,54x+222,67 \;|\; y = 28,39x$$
$$28,39x=17,54x+222,67$$
$$28,39x-17,54x=17,54x-17,54x+222,67$$
$$10,85x=222,67$$
$$\frac{10,85x}{10,85}=\frac{222,67}{10,85}$$
$$x = 20,52$$

5. det betyder at efter 20,52km, så vil prisen for begge leverandører være det samme. Hvis man vil finde ud af hvad prisen ville være, skal man bare gange den med en af formlerne:
$$20,52*28,39 = 582,56$$
$$20,52*17,54+222,67=582,59$$

### Andengradspolynomiet

Andengradspolynomier hænger sammen med Andengradsligninger, fordi man bruger formlen for andengradsligninger til at udregne det punkt/punkter, hvor andengradspolynomiet skærer x-aksen. 

* Hvis a er positiv, så er parablen smilende, altså den går opad. Hvis a er negativ, så går parablen nedad.
* b står for hvor tangenten rører y aksen, eller punkt c. b står derfor for hældningstallet.
* c står for skæringen på y aksen,
* de 2 resultater man får fra andengradsligningen, er de 2 steder hvor den skærer x-aksen, som kaldes rødder.

**Toppunktsformlen:**
* Man finder et koordinatpunkt med den her formel.
$$T_p=\bigg(\frac{-b}{2a},\frac{-d}{4a}\bigg)$$

**Diskriminantformlen:**
$$x = \frac{-b±\sqrt{d}}{2a}$$
$$d = b^2 -4ac$$

## Distanceformlen

$$Dist(P,l)=\frac{ax_1+b-y_1}{\sqrt{a^2+1}}$$

* $x_1$ og $y_1$ er punktets koordinater, $a$ og $b$ er linjens hældningskoefficent og skæring.

## Skæring mellem linje og cirkel
der er 3 muligheder for skæring mellem linje og cirkel: enten skærer den ikke, så der er 0 skæringer, ellers tangerer den cirklen, hvor der er 1 skæring, og ellers skærer den igennem cirklen, hvor der så er 2 skæringer. 

Den måde man afgør om linjen skærer cirklen, er ved at bruge cirklens centrum som $x_1$ og $y_1$ koordinater, og så beregne afstanden. Hvis afstanden er mindre en radius, er der 2 skæringer, og hvis den er lig med radius, er der 1 skæring, og hvis den er større end radius, er der ingen skæringer.

Hvis man vil finde skæringspunkterne, så skal man ophæve sin cirkels ligning. Det gør man ved at bruge sin linjes formel som y-koordinat, og så lave en andengradsligning, sådan her:
$$(x-2)^2+(y+1)^2=20$$
$$y=x+3$$
$$(x-2)^2+(x+3+1)^2=20$$
$$(x-2)^2+(x+4)^2=20$$
$$$$
## Skæringspunkt mellem 2 lineære funktioner
hvis man vil finde skæringspunktet mellem 2 linjer, skal man først opstille dem så de er lig med hinanden:
$$f(x)=g(x)$$

derefter skal man udligne udtrykkene med hinanden, så man får et svar:
$$4x-1=x+5$$
$$3x=6$$
$$x=2$$
på den måde har man fundet x-koordinatet. Hvis man vil finde y-koordinatet, så skal man bare indsætte sin x-værdi i sin ligning:
$$4(2)-1$$
$$7$$

## skæringspunkt mellem 2 andengradsfunktion & anden funktion
samme som ovenstående, men istedet for man det til at ligne en ordnet andengradsfunktion:
$$-x^2+2=-2x+2$$
$$-x^2+2x=0$$
så finder man diskriminanten, og løser opgaven:
$$d=b^2-4ac=2^2-4*(-1)*0=4$$
og så finder man sine 2 løsninger:
$$x=\frac{-b\pm\sqrt{d}}{2a}=\frac{-2\pm\sqrt{4}}{2*(-1)}=0 \&2$$
når man så skal finde sine 2 y-værdier for hvor de skærer, skal man bare indsætte sine 2 x-værdier i en af forskrifterne - vi bestemmer selv hvilken, og ser hvad det bliver til:
