Skal indeholde:

* Jævnstrømsteori
* Ledningsmodstand og Spændingsfald
* Transformere
* Måleteknik
* 1 Faset Vekselstrømsteori
* Motor Teori
* Dimensionering

El-Teori siden her er skrevet ud fra EVU's bog som omhandler el-teori, samt ud fra de ting jeg har lært om el-teori på skolen. https://viewer.ipaper.io/evu/elektrikeruddannelsen/uv-materiale-og-forloeb/el-teori-for-gf-2/?page=1

# Jævnstrømsteori

### Ohms lov 
$$ U = I*R$$
$$I = \frac{U}{R}$$
$$R = \frac{U}{I}$$

* $U$ = spænding, Målt i Volt (V)
* $I$ = strøm, målt i Ampere (A)
* $R$ = Modstand, Målt i Ohm (Ω)

### Effektloven
$$ P = U*I$$
$$ U = \frac{P}{I}$$
$$ I = \frac{P}{U}$$

* $P$ = effekt, målt i watt (W)

### Forbindelsesmuligheder

**Serieforbindelse**
$$ U_T = U_1 + U_2 + U_3$$
$$I_T = I_1 = I_2 = I_3$$
$$R_T = R_1 + R_2 + R_3$$

**Parallelforbindelse**
$$U_T = U_1 = U_2 = U_3$$
$$I_T = I_1 +I_2+I_3$$
$$R_T = (R_1^{-1 } + R_2^{-1} + R_3^{-1})^{-1} $$
$$R_T = \frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_3}}$$

**Blandede forbindelser**

når man skal udregne blandede forbindelser, så skal man altid simplificere. 

### Elektromotorisk kraft & Spændingskilder
når spændingskilden til et kredsløb f.eks er et batteri, vil der være en indre modstand i batteriet, som man kalder $R_i$. og fordi der er en indre modstand, er der også en indre spænding, som ændrer sig efter hvilken strøm som kredsløbet får. 

* Den indre og den ydre spænding/modstand sidder i serie, så man skal tænke på det som et seriekredsløb. 

**Navne:**

$E$ = Spænding Ubelastet

$I_K$ = Kortslutningsstrøm

$U_i$ = Indre spænding, Batteri

$U_y$ = Ydre spænding, lygte

$U$ = Klemspænding, samlet ydre spænding

$I_B$ = strøm (belastningsstrøm)

**Formler:**
$$E = U + U_i$$
$$U_i = R_i * I_B$$
$$U_i  =E - U_y$$
$$U = R_y * I_B$$
$$I_K = \frac{E}{U_i}$$
$$U = E - U_i$$
$$I_B = \frac{E}{R_T}$$
$$I_B = \frac{E}{R_i + R_y}$$
$$R_i = R_T - R_y$$
$$R_y = R_T - R_i$$

## Ledningsmodstand & Spændingsfald

### ledningsmodstand
Når man udregner ledningsmodstand for et specifikt materiale, så går man ud fra de her variabler: 
* 1M lang leder
* 1 kvadrat-mm tyk leder
* 20°C leder

man bruger formlen frac{}{}

**Navne:**

$Ω$ = modstand

$L$ = længde af leder i meter.

$q$ = tykkelsen af leder i millimeter.

$R_L$ = modstanden i leder. 

$φ$ = modstandsfylde / materiale.

**Formler:**

$$CU = 0,0175\frac{Ω*mm^2}{M} | Specifikke \ modstand$$
$$R_L = \frac{φ(\frac{Ω*mm^2}{M})*L_{(M)}}{q_{(mm^2)}}$$

# 1-faset vekselstrømsteori

## Vekselstrømsbølgen
Vekselstrøm veksler mellem positiv og negativ ladning hele tiden. hvor ofte at de skifter mellem positiv og negativ afgøres af frekvensen. den normale frekvens i danmark er 50hz, hvilket vil sige 50 perioder i sekundet. En periode er når spændingen når max værdien både i plus og minus, og tilbage til 0 igen.

**Formel for frekvens:**
$$t=\frac{1}{f} = \frac{1}{50} = 0,02s$$
Man har også Maxværdier og effektiv værdier i vekselstrøm. Max-værdien er den værdi som bølgen når på sit toppunkt, og effektivværdien er den gennemsnitlige spænding/strøm i en given periode.

**Formel for U_max og U_eff:**
$$U_{eff} = \frac{U_{max}}{\sqrt{2}}$$
$$U_{Max}=U_{eff}*\sqrt{2}$$

## Faseforskydning
Faseforskydning er den vinkel, som fase og strøm er forskudt ift. hinanden. Man udregner faseforskydningsvinklen ved hjælp af sin, cos og tan: 

$$∠φ =cos^{-1}\bigg(\frac{hos}{hyp}\bigg)$$
$$∠φ = sin^{-1}\bigg(\frac{mod}{hyp}\bigg)$$
$$∠φ = tan^{-1}\bigg(\frac{mod}{hos}\bigg)$$

## 1-faset kredsløbsteori
* Serieforbindelse = regner med spænding
* Parallelforbindelse = regner med strøm


Der er 3 typer belastninger i et vekselstrømskredsløb:

**Ohmsk:**
* Når man har en ohmsk belastning, så udregner man det på samme måde som i et jævnstrømskredsløb.

**Induktiv:**
* Induktiv belastning vil forskyde strømmen 90 grader bagud ift spænding, eller forskyde spænding 90 grader forud ift strømmen.
* spændingstrekant til venstre, strømtrekant til højre. 

**Kapacitiv:**
* Kapacitiv belastning ivl forskyde strømmen 90 grader forud ift spænding, eller forskyde spænding 90 grader bagud ift strømmen.
* spændingstrekant til højre, strømtrekant til venstre.

**Navne:**

* $U$ = klemspænding
* $I$ = strøm
* $Z$ = impedans / samlet modstand
* $S$ = Samlet effekt
* $U_V$ = ren ohmsk spænding
* $I_V$ = ren ohmsk strøm
* $R$ = ren ohmsk modstand
* $P$ = ren ohmsk effekt
* $U_L$ = induktiv spænding
* $I_L$= induktiv strøm
* $X_L$= induktiv modstand
* $Q_L$ = induktiv effekt
* $U_C$ = kapacitiv spænding
* $I_C$ = kapacitiv strøm
* $X_C$ = kapacitiv modstand
* $Q_C$ = kapacitiv effekt

**Formler:** 
$$X_L = 2*π*F*L$$
$$X_C = \frac{10^6}{2*π*F*C}$$
$$C = \frac{500000}{π*f*X_C}$$
$$cosφ = \frac{hos}{hyp} = \frac{U_V}{U} = \frac{I_V}{I} = \frac{R}{Z} = \frac{P}{S} $$
$$S = \sqrt{P^2 + Q_L^2}$$

# 3-faset vekselstrømsteori

## Motorer

### Motorplader

### 3 faset asynkron motor
* Kobles på 2 måder: Trekant og Stjerne. 

* Trekant = høj spænding, lav strøm
* stjerne = lav spænding, høj strøm. 
### Stjerne-Trekant motor
Lavet så den først er i stjernekobling, og derefter trekantkobling. Grunden til at man gør det sådan, er fordi det så er nemmere at trække en stor motor igang, fordi stjernekoblingen har en lavere effekt.

### Dahlandermotor (2-trins motor)
En dahlandermotor fungerer ved at den er trekantkoblet, men at der er 2 spoler per side, og 
