# Energi
Der er x forskellige former for energi:

* Elektrisk Energi
* Kemisk Energi
* Termisk Energi
* Kinetisk Energi
* Potential Energi
* Kerne Energi
* Stråleenergi 

I fysik bruger man SI-enheden Joule til energi. 
* 1kWh = 3,6 MJ


## Effekt

$$ effekt = \frac{energi}{tid}$$

* Watt er det samme som Joule pr. Sekund. 

F.eks Hvis en brødrister bruger 30000 J på et minut, så kan man regne effekten ud sådan her:
$$ \frac{30000 J}{60 s} = 500W$$
$$ P = \frac{E}{t}$$

* $P$ = Effekt (kWh)
* $E$ = energi (J)
* $t$ = tid (s)

$$1 kWh = 1000W * 3600 s == 3600000 J = 3,6 MJ$$


## Varme

Varme er ikke bare varme. Når man snakker om varme i Fysik, så snakker man om 2 forskellige ting: Temperatur, og overførsel af varmeenergi. 

$$ ΔE = Q + A$$

* $ΔE$ = Tilvæksten i Energi (J)
* $Q$ = Den tilførte varmeenergi - F.eks fra komfuret
* $A$ = Arbejde fra omgivelser - F.eks at røre i gryden. 

Når man skal tilføre varme til f.eks en gryde vand, kan man gøre det på 2 måder: øge varmen tilført, eller tilføre arbejde.
$$ΔE_{indre}=Q+A$$

## Varmekapacitet

Varmekapacitet er hvor meget energi som man skal bruge for at få $x$ materiale til at stige med $y$ temperatur. 

* Der skal 4,18kJ til for at få temperaturen på 1kg vand til at stige med 1°C.

**Formler for Varmekapacitet:**

$$Q = C * Δt$$
$$C = \frac{Q}{Δt}$$
$$Δt = \frac{Q}{C}$$

En anden måde at skrive forholdet på er således:

$$varmekapacitet = \frac{varmetilførsel}{temperaturstigning}$$

* $Q$ = tilført varmeenergi

* $Δt$ = forskellen i temperatur

* $C$ = Varmekapacitet

## Specifik varmekapacitet

Specifik varmekapacitet er hvor meget energi der skal til for at hæve temperaturen 1°C på 1kg af et materiale.

Formel:

$$c=\frac{C}{m}$$

* $c$ = specifik varmekapacitet (J)
* $C$ = varmekapacitet (J)
* $m$ = masse (kg)

For at finde den specifikke mængde energi tilført, skal man bruge den her formel:
$$Q = m*c*Δt$$
$$c = \frac{Q}{m*Δt}$$

* $Q$ = Varme tilført, det samme som $ΔE_{indre}$ (J)

* $m$ = massen (kg)

* $c$ = den specifikke varmekapacitet (J)

* $Δt$ = forskellen i temperatur (k)

### Energibevarelse

## Tilstandsformer

**Specefik smeltevarme:**

$$Q = m*L_S$$

m = masse (kg)

L_S = specifik smeltevarme (kJ)

**Specifik fordampningsvarme:**
$$Q = m*L_f$$

* m = masse (kg)
* L_F = specifik fordampningsvarme

**Skema for forskellige stoffers Specifikke smeltevarme og fardampningsvarme:**

|Stof|Specifik smeltevarme|Specifik fordampningsvarme|
|--

## nyttevirkning
nyttevirkning er det samme som i el-teori, så bare energi man får ud over energi der kommer ind. 

$$η = \frac{E_{udnyttet}}{E_{E_{tilført}}}$$



## Opgave: Isterning fra -18C til 100C
fra -18C til 0C kan vi bruge formlen nedenunder. Isterningen vejer 10g. 

$$Q_1 = m*c*Δt = 0,01*2040*18 = 367,2J$$

Før at vi så kan udregne fra 0 grader til 100, så skal vi først smelte isterningen til vand. det gør vi med Specifik smeltevarme. OBS på at det er i kJ istedet, så man skal gange tallene med $10^3$. 

$$Q_2 = m*L_s = 0,01*334.400 = 3344J$$

Derefter kan vi bruge formlen for specifik varmekapacitet for at udregne $Q_3$:
$$Q_3 = m*c*Δt = 0,01*4180*100 = 4180J$$

og til sidst skal vi udregne specifik fordampningsvarme. samme princip som $Q_2$:
$$Q_4 = m*L_f = 0,01*2260000 = 22600J$$

$$Q = 367,2+3344+4180+22600 = 30491,2J$$
