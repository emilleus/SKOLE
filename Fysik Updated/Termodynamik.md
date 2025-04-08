# Termodynamik

# Energi

**Navne:**

* $P$ = Effekt, målt i watt (W)
* $E$ = Energi. målt i Joule (J)
* $ΔE$ = tilvækst i energi, målt i Joule (J)
* $t$ = tid, målt i sekunder (s)
* $ΔT$ = forskel i temperatur, målt i kelvin (k)
* $Q$ = tilført varmeenergi, målt i Joule (J)
* $C$ = Varmekapacitet,  målt i kilo-Joule per grad celcius (kJ/°C)
* $c$ = specifik varmekapacitet, målt i kilo-Jole per grad celcius (kJ/°C)
* $m$ = masse, målt i kilogram (kg)
* $L_s$ = specifik smeltevarme, målt i kilo-Joule per kilogram (kJ/kg)
* $L_f$ = specifik fordampningsvarm, målt i kilo-Joule per kilogram (kJ/kg)
* $A$ = arbejde, målt i Joule (J)

## Effekt

**Formel for effekt:**
$$ effekt = \frac{energi}{tid}$$
$$ P = \frac{E}{t}$$

* Watt er det samme som Joule pr. Sekund. 
* kilo-watt-time er watt * 3600, fordi det er antallet sekunder i en time. 

$$1 kWh = 1000W * 3600 s = 3600000 J = 3,6 MJ$$


## Varme

Varme er ikke bare varme. Når man snakker om varme i Fysik, så snakker man om 2 forskellige ting: Temperatur, og overførsel af varmeenergi. 

Når man skal tilføre varme til f.eks en gryde vand, kan man gøre det på 2 måder: øge varmen tilført, eller tilføre arbejde.

**Formel for tilført varme:**

$$ ΔE = Q + A$$


## Varmekapacitet

Varmekapacitet er hvor meget energi som man skal bruge for at få $x$ materiale til at stige med $y$ temperatur. 

* Der skal 4,18kJ til for at få temperaturen på 1kg vand til at stige med 1°C.

**Formler for Varmekapacitet:**

$$Q = C * Δt$$
$$C = \frac{Q}{Δt}$$
$$Δt = \frac{Q}{C}$$

En anden måde at skrive forholdet på er således:

$$varmekapacitet = \frac{varmetilførsel}{temperaturstigning}$$

## Specifik varmekapacitet

Specifik varmekapacitet er hvor meget energi der skal til for at hæve temperaturen 1°C på 1kg af et materiale.

**Formel for at udregne specifik varmekapacitet af et stof:**

$$c=\frac{C}{m}$$

**Formel for Udvidet varmekapacitet:**

$$Q = m*c*Δt$$
$$c = \frac{Q}{m*Δt}$$



### Energibevarelse
Hvis man gerne vil holde noget varmt/koldt, så skal man komme det i en varmeisoleret beholder. I en totalt varmeisoleret beholder vil energien indeni beholderen være konstant, og tilvæksten i energi er derfor nul.
$$ΔE_{indre}=0$$

Hvis man blander 2 væsker med 2 forskellige temperaturer i en totalt varmeisoleret beholder, ser formlen for at finde fællestemperaturen sådan her ud:
$$t_f = \frac{m_v*c_v*t_v+m_l*c_l*t_l}{m_v*c_v+m_l*c_l}$$


## Tilstandsformer

Et stof skifter tilstandsform når det går f.eks fra solid til væske. Imens et stof undergår ændring af sin tilstandsform, ændrer temperaturen på stoffet sig ikke.

**Specefik smeltevarme:**

$$Q = m*L_S$$


**Specifik fordampningsvarme:**

$$Q = m*L_f$$

**Skema for forskellige stoffers Specifikke smeltevarme og fordampningsvarme:**


|Stof|Specifik smeltevarme|Specifik fordampningsvarme|
|----|--------------------|--------------------------|
|Vand ($H_2O$) | 334,4 |2260 |
|Ethanol (sprit)| 109 |840 | 
|Helium ($He$) | 5,0| 20,0
|Nitrogen ($N_2$)|51|399|
|Hydrogen ($H_2$)|109|893
|Aluminium ($Al$)|397| 10778| 


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


## Gasser

### Idealgasligningen
$$p*V = n*R*T$$
$$R=8,31\frac{Pa*m^3}{mol*K}$$
* man skal bruge de forskellige SI-enheder for at den konstant $R$ dur. hvis man vil bruge andre enheder, så skal mna finde en anden konstant. 
$$n = \frac{m}{M}$$

### Boyle-mariottes lov

$$p=konstant*V == p*V=constant$$

$$p_1*V_1=p_2*V_2$$

### Gay-Lussacs lov

$$\frac{p}{T}=konstant$$

$$\frac{p_1}{T_1}=\frac{p_2}{T_2}$$

## Tryk & Opdrift

### Krafttrekanten:
$$p = \frac{F}{A}$$
$$A = \frac{F}{p}$$
$$F = A*p$$


* Tryk angives i newton pr. $m^2$, som er pascal.
$$1Pa=1N/m^2$$

### Tyngdekraft
Tyngdekraft er produktet af tyngdeaccelerationen gange massen.
$$F_t = m*g$$


### atmosfære & bar
* atmosfærens gennemsnitstryk er ca 101,3 kiloPascal.
Nedenunder er der nogle af de forhold som er vigtige:

$$1 bar = 100kPa$$
$$1 atm = 101,3kPa$$
$$ 1 at = 98,07kPa$$

* atm = atmosfære
* at = teknisk atmosfære

## Tryk i væsker

En væske i et kar påvirker bunden af beholderen med en kraft, fordi jorden trækker i væsken. Man skulle tro at 500L vand i en pool har en større kraft end 10L vand i en spand, men fordi tryk måles i kraft pr. areal, så skal man bruge en formel for at regne det ud. 

### Tryk i en væskesøjle:

$$m = ρ*V = ρ*h*A$$

$$F=ρ*V*g$$

* $p=ρ*h*g$ = trykket i en væskesøjle


## Opdrift 

$$F_{op}=ρ_{væske}*V_{genstand}*g$$

$$F_{total}=F_{bund}-F_{top}$$

* densitet af forskellige stoffer på side 26. (lav skema)

* Tryk på 0 = vacuum
* i scenarier med opdrift, skal man finde opdriften først, finde tyngdekraften af emnet, og finde ud af hvilket tal er størst.
* opdriften findes ved at finde trykket af bunden samt toppen, og minusse trykket fra toppen fra bunden. 
