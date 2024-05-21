Skal Indeholde: 

* Oversigt over de forskellige love vi følger efter, og hvad det er for nogle, og hvad de indeholder
* Udsnit fra dem som er vigtige at kunne. 
* Hvordan man navigerer bøgerne.



## Automatikteknisk dokumentation

når man snakker sikkerhedsvurdering, så skal man bruge 13849-1 og 60204-1

## dimensionering: 
DS/EN 60204-1_2018 er den standard vi bruger.

* fra strømforsyningen til maskinens dele. 
$$I_B < I_{N} < I_Z$$

$I_B$ = belastningsstrømmen, strømmen man læser på mærkepladen.

* strømmen på maskinen skal være mindre end maksstrømmen på sikringen, søm skal være mindre end maksstrømmen på kablet. 

* standarden foro hvad kabler kan holde til temperaturmæssit er 90C. 
* strømmen giver varme / er det som varmer kablet. 

* man dimensionerer efter Fase-Nul kortslutningsstørm (IKmin), fordi det tager længere tid for IKmin at blive afbrudt, ergo kan der blive skabt mere varme i kablet. 

* man bliver ved med at gå tværsnit på kabler op, indtil at OB, KB og ΔU er opfyldt. 

* Overbelastningssikring = OB & ΔU dimensionering.
* Automatsikring = KB dimensionering. 

Man vil også bruge automatsikring til det hele i nogle tilfælde, såsom hvis man ikke har en motor, men et varmelegeme istedetfor. 

* side 260 - a, b , c ,d ,e 
* Side 185 - forskellige kvadrater
* Side 263 - korrektionsfaktorer, temoeratur og samlet fremføring

## Dimensionering
$$I_B\le I_N\le I_Z$$

**Begreber:**
* $I_B$ = Belastningsstrømmen - Hvor meget strøm motoren bruger. 
* $I_N$ = Beskyttelsesudstyrets mærkestrøm - Automatsikrings størrelse, indstilling af termorelæ.
* $I_Z$ = Kabel / lednings strømværdi. 

### OB-Dimensionering

### ΔU-Dimensionering
$$R_l=\frac{R_{aflæst}*længden}{1000}$$
$$ΔU_{maskine}=I_B*R_l*\sqrt{3}*cosφ$$
$$ΔU_{maskine}\%=\frac{ΔU_{maskine}*100}{400}$$

### KB-dimensionering
