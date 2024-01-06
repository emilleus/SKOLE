Skal indeholde:

* Jævnstrømsteori
* Ledningsmodstand og Spændingsfald
* Transformere
* Måleteknik
* 1 Faset Vekselstrømsteori
* Motor Teori
* Dimensionering

El-Teori siden her er skrevet ud fra EVU's bog som omhandler el-teori, samt ud fra de ting jeg har lært om el-teori på skolen. https://viewer.ipaper.io/evu/elektrikeruddannelsen/uv-materiale-og-forloeb/el-teori-for-gf-2/?page=1

## Jævnstrømsteori

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
