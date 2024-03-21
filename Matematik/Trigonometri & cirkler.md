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
$$sin(A)*hyp=\frac{mod*hyp}{hyp}$$
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

## Radianer

Hvis man skal omregne grader til vinkel: 

* 1 grad = $\frac{π}{180}$
og så ganger man med graderne. det dur kun hvis radius er lig med 1. 

$$vinkel i radianer = \frac{buelængde}{radius}$$
