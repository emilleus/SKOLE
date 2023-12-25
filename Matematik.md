
# Matematik Dokument
Emil andreasen

# Indholdsfortegnelse
1. [Geometri](#Geometri)
2. [Trigonometri](#Trigonometri)
3. [Ligninger](#Ligninger)
4. [Funktioner](#Funktioner)


## Geometri
Geometri omhandler forskellige 2D og 3D figurer, og hvad man kan bruge dem til. I den her del af dokumentet har vi formler til hvordan man regner sig frem til forskellige værdier i figurer, og hvad de forskellige værdier betyder. 

### Cirkler 

**Værdier i en cirkel**:

$O$ = omkreds

$A$ = areal

$d$ = diameter

$r$ = radius

$v$ = vinkel af cirkeludsnit

$b$ = buelængde, uudsnit af omkreds

**Formler**:

Omkreds af en cirkel: $$O=π*d$$

Areal af en cirkel: $$A=π*r^2$$

Buelængde udspændt af en vinkel: $$b=\frac{2*π*r}{360}*v$$

Areal af et cirkeludsnit: $$A =\frac{π*r²*v}{360}$$

Areal af en cirkelring: $$A=π* (R^2-r^2)$$

### Trekanter

**Værdier i en trekant:**

$A$ = areal

$h$ = højden fra grundlinjen til den højeste overflade

$g$ = grundlinjen

**Formler:**

Arealet af en trekant: $$A={1\over2 \\ *h*g}$$

Pythagoras Læresætning: $$a^2 + b^2 = c^2$$

Medianen af en trekant: $$M_a=\frac{1}{2}*\sqrt{2*(b^2+c^2)-b^2}$$

### Firkanter

**Værdier i en firkant:**

$A$ = Areal

$d$ = diagonaler mellem 2 punkter

$g$ = grundlinjen

$h$ = højden fra grundlinjen til toppen af firkanten. 

**Formler:**

Areal af en rombe: $$A={1\over2}*d1*d2$$

Areal af et Parallellogram: $$A=g*h$$

Areal af et trapez: $$A={1\over2}*h*(BC+AD)$$

### Prismer

**Værdier i en prisme:**

$V$ = Volumen

$G$ = grundflade

$h$ = højden

**Formler:**
Rumfang af en prisme: $$V=G*h$$

### Cylindere

**Værdier i en Cylinder:**

$V$ = Volumen 

$A$ = Areal

$r$ = radius

$h$ = højde

**Formler:**

Rumfang af en cylinder: $$V=π*r2*h$$

Overflade Areal af en cylinder: $$A=(2*π*r*h)+(2*π*r^2)$$

Rumfang af et cylinderrør: $$V=π⋅(R^2-r^2)⋅h$$

### Pyramider
en lille note til pyramider er at man kan komme frem til $h_s$ ved at bruge pythagoras, ved at tage længden eller bredden af pyramidens bund, og dele den i to. 

**Værdier i en Pyramide:**

$V$ = volumen

$A$ = areal

$G$ = grundflade

$h$ = højden

$h_s$ = højden af siden af en pyramide

**Formler:**
Rumfang af en Pyramide: $$V={1\over3}* G * h$$

Sideflade af en Pyramide: $$A=12*h_s*3$$
  
### Kegler

**Værdier i en kegle:**

$r$ = radius

$s$ = sidens længde, keglens højde


**Formler:**
Krumme overfladeareal af en kegle: $$A = π * r * s$$

Fulde Overfladeareal af en kegle: $$A=π*r*s+r$$

Rumfang af en kegle: $$V=\frac{1}{3}*π*r^2*h$$

### Kugler

**Værdier i en kugle:**

$r$ = radius

**Formler:**

Overfladeareal af en kugle: $$A=4*π*r^2$$
Rumfang af en kugle: $$V=\frac{4}{3}*π*r^3$$

## Trigonometri

### Enhedscirklen
* sin(V) aflæses i y-aksen, i det punkt hvor linjen skærer enhedscirklen.
* cos(V) aflæses i x-aksen, i det punkt hvor linjen skærer enhedscirklen.
* tan(V) aflæses i y-aksen, på det punkt hvor linjen skærer den tangent som sidder på (1,0).

$$sinV=\frac{mod}{hyp}||mod=hyp*sin(V)|| hyp=\frac{mod}{sin(V)}$$
$$cosV=\frac{hos}{hyp}||hos=hyp*cos(V)||hyp=\frac{hos}{cos(V)}$$
$$tanV=\frac{mod}{hos}||mod=hos*tan(V)||hos=\frac{mod}{tan(V)}$$

### Sinus, Cosinus og Tangens

**Bevis for sinus, cosinus og tangens**

De originale formler, som vi skal bevise:
$$sin(V)=\frac{mod}{hyp}$$
$$cos(V)=\frac{hos}{hyp}$$
$$tan(V)=\frac{mod}{hos}$$

1. Først, så skal man starte med enhedscirkel, og ud fra den enhedscirkel, kan vi tegne 3 ensvinklede trekanter. De tre tekanter har følgende værdier:

2. så skal man vise hvor man får de forskellige værdier fra.

3. derefter skal man finde en forstørrelsesfaktor for trekant 1 og 3. Det gør man således:
$$f=\frac{hyp}{1}=hyp$$

4. så skal man bare gange forstørrelsesfaktoren med med cos(V), og omskrive formlen, så den ligner den originale. Sådan her:
$$cos(V)*hyp=hos$$
$$\frac{hyp*cos(V)}{hyp}=\frac{hos}{hyp}$$
$$cosV=\frac{hos}{hyp}$$

5. På den måde har vi fundet frem til cos(V) beviset. Nu skal vi gøre det samme, men med sinus i stedet for cosinus. Det gør vi sådan her:
$$sin(V)*hyp=mod$$
$$\frac{sinV*hyp}{hyp}=\frac{mod}{hyp}$$
$$sin(V)=\frac{mod}{hyp}$$

6. på den måde har vi nu også sinusbeviset. Nu mangler vi kun Tangens, og for at kunne finde frem til tangens, så skal vi bruge en ny forstørrelsesfaktor. Den forstørrelsesfaktor er mellem trekant 2 og 3. den ser sådan her ud:
$$f=\frac{hos}{1}=hos$$

7. nu har vi den nye forstørrelsesfaktor. Den kan vi så bruge til at komme frem til at regne os frem til tangens, sådan her:
$$tan(V)*hos=mod$$
$$\frac{tan(V)*hos}{hos}=\frac{mod}{hos}$$
$$tan(V)=\frac{mod}{hos}$$

8. og på den måde har vi nu beviserne for sinus, cosinus og tangens.

**Anvendelse af sinus, cosinus og tangens**

Her er et eksempel på hvordan man bruger trigonometri i den retvinklede trekant.

Først, så har vi en retvinklet trekant, hvor vi kender 3 værdier. Den ene er vinkel C på 90, grader, og så 2 yderligere værdier. Vi kender disse værdier:

* C = 90°
* a = 15,42cm
* b = 11,38cm

1. først, så kan vi regne tangens til vinkel A ud, fordi vi kender både den hosliggende, og den modstående:
$$tan(A)=\frac{mod}{hos}=\frac{15,42}{11,38}=1,355$$

2. nu skal vi så regne vinklen ud, ved hjælp af tan<sup>-1</sup>.
$$tan^{-1}(1,355)=53,57°$$

3. nu har vi regnet vinkel A ud. Det næste vi kan gøre er at regne hypotenusen ud. Det gør vi ved at omskrive formlen for sinus, så vi isolerer hyp.
$$sin(A)=\frac{mod}{hyp}$$
$$sin(A)*hyp=\frac{mod*hyp}{hyp}$$Funktioner & Polyno
$$sin(A)*hyp=mod$$
$$\frac{sin(A)*hyp}{sin(A)}=\frac{mod}{sin(A)}$$
$$hyp=\frac{mod}{sin(A)}$$

4. nu har vi isoleret hyp, så vi kan udregne den, og det gør vi ved at indsætte vores værdier:
$$hyp=\frac{15,42}{sin(53,57)}=19,16cm$$

5. nu mangler vi kun den sidste vinkel, og den er meget ligetil, fordi det bare er vinkelsummen af en trekant minus de kendte vinkler:
$$B = 180-90-53,57=36,43°$$

6. og nu har vi alle værdier i trekanten.

### Sinusrelationen

**Bevis af sinusrelationen**

Først, relationen som vi vil regne os frem til:
$$\frac{a}{sin(A)}=\frac{b}{sin(B)}=\frac{c}{sin(C)}$$

1. først, så har vi en vilkårlig trekant, som er blevet delt på midten, så det skaber 2 retvinklede trekanter.

2. derefter skal vi nu udtrykke h<sub>B</sub> på 2 forskellige måder, med de 2 trekanter. Vi starter med trekant A. Det gør vi sådan her:
$$sin(A)=\frac{h}{c}$$
$$sin(A)*c=\frac{h*c}{c}$$
$$h=sin(A)*c$$

3. nu skal vi gøre det samme, bare med den anden trekant. Det gør vi sådan her:
$$sin(C)=\frac{h}{a}$$
$$sinC*a=\frac{h*a}{a}$$
$$h=sin(C)*a$$

4. nu har vi 2 måder at udtrykke h<sub>B</sub> på. siden begge ligninger giver det samme resultat, kan man skrive det sådan her:
$$sin(A)*c=sin(C)*a$$

5. nu skal vi omskrive formlerne, så vi kan nå frem til målet. Det første dividere med sin(A) på begge sider, så vi isolerer c.
$$\frac{sin(A)*c}{sin(A)}=\frac{sin(C)*a}{sin(A)}$$
$$c=\frac{sin(C)*a}{sin(A)}$$

6. nu skal vi så dividere med c på begge sider, så vi også isolerer a.
$$\frac{c}{sin(C)}=\frac{sin(C)*a}{sin(A)*sin(C)*}$$

$$\frac{c}{sin(C)}=\frac{a}{isn(A)}$$
7. og på den måde er vi nu kommet frem til sinusrelationen.

**Anvendelse af sinusrelationen**

$$\frac{a}{sin(A)}=\frac{b}{sin(B)}$$
$$\frac{sin(A)}{a}=\frac{sin(B)}{b}$$

Vi starter med en vilkårlig trekant, hvor vi kender 3 værdier. De værdier skal være et par, og en værdi mere. Vi kender disse værdier:

* A = 61,65°
* a =20,91cm
* B = 24,42°

1. først, så skal vi finde ud af hvad B vil være. Det gør vi ved at indsætte vores kendte værdier ind i sinusrelationen, sådan her:
$$\frac{20,91}{sin(61,65)}=\frac{b}{sin(24,42)}$$

2. så skal vi isolere b, så den står alene. Det gør vi ved at gange med B på begge sider:
$$\frac{20,91*sin(24,42)}{sin((61,65)}=\frac{b*sin(24,42)}{sin(24,42)}$$
$$b=\frac{20,91*sin(24,42)}{sin(61,65)}= 9,82cm$$

3. nu har vi regnet b ud. Fordi vi også har 2 vinkler i trekanten, kan vi regne den sidste vinkel ud. Vi ved at vinkelsummen i en trekant er 180°, så vi skal bare reducere de kendte vinkler fra vinkelsummen.
$$C = 180-24,42-61,65=93,93°$$

4. nu har vi også vinkel C. nu skal vi bare gentage det samme som med siden b, bare med siden c i stedet. 
$$\frac{20,91}{sin(61,64)}=\frac{c}{sin(93,93)}$$
$$\frac{20,91*sin(93,93)}{sin(61,64)}=\frac{c*sin(93,93)}{sin(93,93)}$$
$$c=\frac{20,91*sin(93,93)}{sin(61,64)}= 23,7cm$$

5. nu har vi alle værdierne i trekanten, og har dermed løst den.

### Cosinusrelationen

**Bevis af cosinusrelationen**

Først, relationen som vi vil nå frem til:
$$c^2=a^2+b^2-2ab*cos(C)$$

1. først, så har vi en vilkårlig trekant, som er blevet delt på midten, så det skaber 2 retvinklede trekanter.

2. derefter skal vi nu udtrykke h på 2 forskellige måder, med de 2 trekanter. Vi starter med trekant A. Det gør vi sådan her:
$$h^2=c^2-(b-x)^2$$

3. nu skal vi gøre det samme, bare med den anden trekant. Det gør vi sådan her:
$$h^2=a^2-x^2$$

4. nu har vi 2 måder at udtrykke h på. siden begge ligninger giver det samme resultat, kan man skrive det sådan her:
$$c^2-(b-x)^2=a^2-x^2$$

5. nu skal vi bare omskrive formlerne, så vi kan nå frem til målet. Det gør vi ved at tilføje (b-x)<sup>2</sup> på begge sider, så vi får isoleret c<sup>2</sup>.
$$c^2-(b-x)^2+(b-x)^2=a^2-x^2+(b-x)^2$$
$$c^2=a^2-x^2+(b-x)^2$$

6. nu skal vi ophæve parantesen, så den ikke er der mere. Det gør vi ved at gange (b-x) med hinanden, sådan her:
$$c^2=a^2-x^2+b^2+x^2-2bx$$
$$c^2=a^2+b^2-2bx$$

7. nu skal vi have fjernet x fra ligningen. Den måde vi gør det på, er ved at tage udgangspunkt i cos(C), og omskrive den formel, så vi isolerer x. det gør vi sådan her:
$$cos(C)=\frac{x}{a}$$
$$cos(C)*a=\frac{x*a}{a}$$
$$x=cos(C)*a$$

8. nu har vi isoleret x. Nu skal vi indsætte hvad x er lig med ind i vores ligning fra før, så den kommer til at se sådan her ud:
$$c^2=a^2+b^2-2ab*cos(C)$$

9. og på den måde har vi nu også regnet os frem til cosinusrelationen.

**Anvendelse af cosinusrelationen**

$$a^2=b^2+c^2-2bc*cos(A)$$
$$cos(A)=\frac{b^2+c^2-a^2}{2bc}$$

Vi starter med en vilkårlig trekant, hvor vi kender 3 forskellige værdier. De værdier vi kender er alle de 3 sider af trekanten.

* a = 15,74cm
* b = 17,97cm
* c = 8,56cm 

1. først, så skal vi regne os frem til en af vinklerne. Jeg starter med vinkel C. det gør vi ved at indsætte vores værdier i cosinusrelationen, sådan her:
$$cos(C)=\frac{15,74+17,97-8,56}{2*15,74*17,97}=0,8792$$

2. nu har vi en cosinusværdi, men for at vi kan finde vinklen, så skal vi ”omvende” den. Det gør vi med cos<sup>-1</sup> funktionen, sådan her:
$$cos^{-1}(0,8792)=28,45°$$

3. nu har vi den første vinkel. Nu skal vi gøre det samme med en anden vinkel, i det her tilfælde vinkel A. det gør vi sådan her:
$$cosA=\frac{17,97+8,56-15,74}{2*17,97*8,56} = 0,4825$$

4. så skal vi gøre de samme som værdien til vinkel c, og ”omvende” den.
$$cos^{-1}(0,4825)=61,15°$$

5. nu har vi 2 vinkler, og vi kan nu finde den sidste vinkel ved at reducere de 2 vinkler fra vinkelsummen.
$$B = 180-28,45-61,15=90,4°$$

6. og nu har vi alle værdier i trekanten, og har løst trekanten.

### Trigonometriske Funktioner

### Sfærisk trigonometri

## Ligninger

**Rækkefølgen for at løse ligninger:**

1. Løse Parenteser først.
2. Derefter potenser og rødder, fra venstre til højre.
3. Derefter skal man gange og dividere, fra venstre til højre.
4. Til sidst skal man plus og minus, fra venstre til højre.

**Hvis der er parenteser:**
Så skal man gange tallet foran ind i parentesen, f.eks.:
$$3(x+6)-2 =2(x+9)$$
$$3x+18-2=2x+18$$

**Hvis der er brøker:**
så skal man matche nævnerne (nederste tal), så de er det samme på begge sider af lighedstegnet, f.eks.:
$$\frac{x+7}{3}-\frac{3x-7}{4}=\frac{x-1}{2}$$
$$\frac{4x+28}{12}-\frac{9x-21}{12}=\frac{6x-6}{12}$$
**Procenter i ligninger:**

Eksempel på hvordan man regner 8% ud af 200kr:
$$\frac{x}{200}=\frac{8}{100}$$
$$\frac{200*x}{200}=\frac{200*8}{100}$$
$$x=\frac{200*8}{100}=16kr$$

### Ligninger med 2 ukendte
når man skal løse en ligning med 2 ukendte værdier, så skal der være 2 forskellige ligninger. Der er 2 forskellige metoder til at løse en ligning med 2 ukendte: *Substitutionsmetoden*, og *Lige store coefficienter metoden*.

#matematik 
### 2 Ligninger med 2 ukendte:

**Substitutionsmetoden:**
1. Først, så har man 2 ligninger:
$$6x-2y=12 \qquad 4x+8y=64$$

2. så tager man den ene ligning, og isolerer enten x eller y.
$$6x-2y=12$$
$$6x=12+2y$$
$$x=2+0,33y$$

3. Derefter skal man tage resultatet, og bruge det i den anden ligning:
$$4x+8y=64$$
$$4(2+0,33y)+8y=64$$
$$8 + 1,33y +8y=64$$
$$8+9,33y=64$$
$$9,33y=56$$
$$y=6$$

4. nu har vi så fundet værdien for den ene ukendte. nu skal vi indsætte den værdi i den anden formel, som vi ordnede tidligere.
$$x = 2 + 0,33y$$
$$x = 2 + 2$$
$$x = 4$$

5. på den måde har vi nu regnet både x og y værdierne ud.

**Lige store koefficienters metode:**

1. Først, så har man 2 ligninger:
$$3x +4y-23=0 \qquad 2x+3y-4=0$$

2. så skal man få en af de ukendte værdier til at være det samme på begge sider. Det gør man ved at gange hele ligningen med x værdien i den anden ligning.
$$6x+8y-46=0 \qquad 6x-9y-12=0$$

3. fordi x værdierne er det samme, så kan man fjerne dem fra begge ligninger.
$$8y-46=0 \qquad -9y-12=0$$

4. så skal man lave en samlet ligning ud af de 2 ligninger.
$$8y-46=-9y-12$$

5. så skal man ordne ligningen, så man finder værdien for den ukendte.
$$17y-46=-12$$
$$17=34$$
$$\frac{17y}{17} = \frac{34}{17}$$
$$y = 2$$

6. så skal man tage den ukendte som vi nu kender, og indsætte den i en af de 2 originale ligninger, for at finde den sidste ukendte.
$$3x +4(2)-23=0$$
$$3x+8-23=0$$
$$3x-15=0$$
$$3x=15$$
$$\frac{3x}{3}=\frac{15}{3}$$
$$x=5$$

7. og på den måde kender vi nu begge de ukendte værdier.

### Andengradsligninger

Ordnet andengradsligning:
$$ax^2 +bx+c=0$$
Formel til at løse en ordnet andengradsligning:
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
$$x=\frac{-b\pm\sqrt{d}}{2a}$$
$d$ = Diskriminanten.
diskriminanten fortæller os noget om hvor mange løsninger at ligningen har.
$$(d>0) = 2\;løsninger$$
$$(d=0) = 1 \;løsning$$
$$(d<0) = 0 \; løsninger$$
- Hvis der ikke er nogen løsning til en andengradsligning, så betyder det at parablen ikke rammer x i koordinatsystemet.


**Eksempel på Andengradsligning opgave:**

1. Først, så har vi en andengradsligning:
$$3x^2+7x=20$$

2. den skal vi ordne. Det gør vi sådan her:
$$3x^2+7x-20=20-20$$
$$3x^2+7x-20=0$$

3. nu skal vi indsætte den ordnede ligning i formlen, og løse den.
$$x=\frac{-7\pm\sqrt{7^2-4*3*-20}}{2*3}$$
$$x=\frac{-7\pm\sqrt{7^2+240}}{6}$$
$$x=\frac{-7\pm\sqrt{289}}{6}$$
$$x=\frac{-7\pm17}{6}=\begin{Bmatrix}\frac{-7+17}{6}=1,5 \\ \frac{-7-17}{6}=-4 \end{Bmatrix}$$

4. og på den måde har vi fundet de 2 løsninger for andengradsligningen.

### Differentialligninger

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

**Beregning af stigningstallet ud fra 2 punkter**
$$a=tanV=\frac{y^2-y^1}{x^2-x^1}$$
- Hvis vi har 2 punkter, som hedder (9,3) og (6,5), så regner man det ud sådan her:
$$a=\frac{9-6}{3-5}$$
$$a=\frac{3}{-2}=-1,5x$$

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


### Eksponentiel funktion
### Potens funktion
### Andengradspolynomiet

Andengradspolynomier hænger sammen med Andengradsligninger, fordi man bruger formlen for andengradsligninger til at udregne det punkt/punkter, hvor andengradspolynomiet skærer x-aksen. 

* Hvis a er positiv, så er parablen smilende, altså den går opad. Hvis a er negativ, så går parablen nedad.
* b står for hvor tangenten rører y aksen, eller punkt c. b står derfor for hældningstallet.
* c står for skæringen på y aksen,
* de 2 resultater man får fra andengradsligningen, er de 2 steder hvor den skærer x-aksen, som kaldes rødder.

**Toppunktsformlen:**
* Man finder et koordinatpunkt med den her formel.
$$T_p=\bigg(\frac{-b}{2a},\frac{-d}{4a}\bigg)$$

## Logaritmer

## Calculus

### Differentialregning
**Sekant og Tangent**
* Sekant er når man tegner en linje gennem en funktion med 2 punkter. 
* Tangent er når man tegner en linje gennem en funktion med 1 punkt. 


## Vektorer
### Vektorer i planen
### Vektorer i rummet


## Statistik
