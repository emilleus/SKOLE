# UR-Robotter
det er det vi skal begynde på nu. 

* Opdeles i 2 ategorier: industrirobotter, og servicerobotter.


## 6-akset robotarm

* MOVEJ - så hurtigt så muligt mellem punkter, bruger alle led.
* MOVEL - lineær bevægelse, afviger ikke fra "stien". 
* MOVEP - samme som MOVEL, bare med konstant hastighed og vinkel. 

* CIRKULÆR - en mulighed under MOVEP, hvor man kan lave en cirkulær bevægelse. 

### Koordinatsystem

* World er det store koordinatsystem som robotten arbejder i - starter i (0,0,0). Det er det punkt som alle bases kalibreres efter. Det skal være et sted robotten kan nå.

* Base - der hvor man har monteret robotten. der kan defineres flere bases.

world er selve robottens nul-punkt, og base har så et koordinat til world, som er nul-punktet i base-koordinatsystemet.