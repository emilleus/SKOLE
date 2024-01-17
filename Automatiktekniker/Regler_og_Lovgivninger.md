Skal Indeholde: 

* Oversigt over de forskellige love vi følger efter, og hvad det er for nogle, og hvad de indeholder
* Udsnit fra dem som er vigtige at kunne. 
* Hvordan man navigerer bøgerne.



## Automatikteknisk dokumentation

når man snakker sikkerhedsvurdering, så skal man bruge 13849-1 og 60204-1

## dimensionering: 
DS/EN 60204-1_2018 er den standard vi bruger.

* fra strømforsyningen til maskinens dele. 
$$I_B < I_{NOB} < I_Z$$

$I_B$ = belastningsstrømmen, strømmen man læser på mærkepladen.

* strømmen på maskinen skal være mindre end maksstrømmen på sikringen, søm skal være mindre end maksstrømmen på kablet. 

* standarden foro hvad kabler kan holde til temperaturmæssit er 90C. 
* strømmen giver varme / er det som varmer kablet. 

* man dimensionerer efter Fase-Nul kortslutningsstørm (IKmin), fordi det tager længere tid for IKmin at blive afbrudt, ergo kan der blive skabt mere varme i kablet. 

* man bliver ved med at gå tværsnit på kabler op, indtil at OB, KB og ΔU er opfyldt. 

* Overbelastningssikring = OB & ΔU dimensionering.
* Automatsikring = KB dimensionering. 

Man vil også bruge automatsikring til det hele i nogle tilfælde, såsom hvis man ikke har en motor, men et varmelegeme istedetfor. 