# Uvod v informatiko (Zapiski) - 2024/25
Zapiski iz predavanj in vaj pri predmetu Uvod v Informatiko<br>


![Informatika](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRA2KK6rLwzQRYMp7IbaLnYlxSjMlpFDMwNUg&s) <br>

# Kazalo
  ## Predavanja
  - [Razvoj računalništva in informatike](#Razvoj-računalništva-in-informatike)
  - [Podatki in informacije](#Podatki-in-informacije)
  - [Številski sistemi](#Številski-sistemi)
  - [Pretvorba podatkov](#Pretvorba-podatkov)
  - [Teorija informacij](#Teorija-informacij)
  - [Logične strukture](#Logične-strukture)
  - [Podatkovne strukture in algoritmi](#Podatkovne-strukture-in-algoritmi)
  - [Uvod v programiranje](#Uvod-v-programiranje)
  - [Življenski cikel programske opreme](#Življenski-cikel-programske-opreme)
  - [Pomen in vloga IT pri ustvarjanju in prenosu znanja](#Pomen-in-vloga-IT-pri-ustvarjanju-in-prenosu-znanja)
  - [Inteligentni sistemi](#Inteligentni-sistemi)
  - [ChatGPT](#ChatGPT)
  - [Računalniška omrežja](#Računalniška-omrežja)
  - [Transportni mediji](#Transportni-mediji)
  - [Oprema računalniških omrežji](#Oprema-računalniških-omrežji)
  - [Kibernetska varnost](#Kibernetska-varnost)
## Vaje





# Razvoj računalništva in informatike

  ## 1. Uvod

  - **Računalništvo:** Znanstvena veda, ki proučuje delovanje računalnikov, vključno s strojno in programsko opremo.
  - **Informatika:** Ukvarja se z zbiranjem, analiziranjem, shranjevanjem in dostopom do podatkov ter informacij.
  - **Informacija:** Sporočilo, ki prinese novo vrednost uporabniku in vpliva na znanje, odločanje ter ravnanje.

## 1.2. IK, IKT in IS

- **Informacijska tehnologija (IT):** Strojna in programska oprema, osnova za informacijske sisteme.
- **Informacijsko-komunikacijska tehnologija (IKT):** Vključuje telekomunikacijsko in računalniško opremo.
- **Informacijski sistem (IS):** Omogoča zajem, obdelavo in posredovanje informacij.

## 1.3 Zgodovina računalništva

### 1.3.1 Mehanski pripomočki

- **Abakus (2000 pr. Kr., Kitajska):** Prvi računalni pripomoček.
- **Antikiterski mehanizem (100. pr. Kr.):** Analogni računalnik za astronomske izračune.
- **Wilhelm Schickard (1623):** Prvi mehanski kalkulator za seštevanje in odštevanje.
- **Blaise Pascal (1642):** "Pascaline" - prvi mehanski kalkulator, ki upošteva prenose.
- **Gotfried Wilhelm Leibniz (1694):** Kalkulator, ki izvaja tudi korenjenje in množenje.
- **Charles Babbage (1820, 1834):** Diferenčni in analitični stroj - predhodnik sodobnih računalnikov.

### 1.3.2 Elektronski računalniki

- **Konrad Zuse (1941):** Prvi programabilni elektronski računalnik Z3.
- **ENIAC (1945):** Prvi popolnoma elektronski računalnik v ZDA.

## 1.4 Programska oprema
- **Ada Lovelace:** Prvi program za analitični stroj (*Bernoullijeva števila*).
- **Alan Turing:** Razvoj teoretičnega računalništva, Turingov stroj (1936).
- **John von Neumann:** Definiral računalniško arhitekturo z ločenim pomnilnikom za podatke in ukaze. <br>

Von Neumanov Model Računalnika:

![Von Nuemanov Model](http://sasa.musiclab.si/eri1/INFORMATIKA/Informacijska_tehnologija/slike/vonNeumannovModel.gif)

## 1.5 Generacije računalnikov

**1. GENERACIJA (1940-1956)**
   - Elektronske cevi, veliki in energetsko potratni računalniki (ENIAC, EDVAC).
   - Programiranje neposredno v strojni kodi.

**2. GENERACIJA (1956-1963)**
   - Tranzistorji nadomestijo elektronske cevi → MANJŠA PORABA ENERGIJE, VEČJA HITROST.
   - Novi programski jeziki (assembly)

**3. GENERACIJA (1963-1971)**
  - Integrirana vezja (IC) povečajo zmogljivost.
  - Razvoj višjih programskih jezikov (BASIC, Fortran, Cobol).

**4. GENERACIJA (1971-1990)**
  - Mikroprocesorji (Intel 4004) → razvoj osebnih računalnikov.
  - Operacijski sistemi UNIX, MS-DOS.
  - Razcvet programiranja (C, Pascal, Java).

**5. GENERACIJA (1990-Danes)**
  - Paralelno procesiranje, umetna inteligenca, oblačne storitve.
  - Jeziki: Prolog, Mercury (usmerjeni v AI in podatkovno rudarjenje).

**6. GENERACIJA (Prihodnost)**
  - Nevronske mreže, kvantni računalniki, umetna inteligenca.
  - Vizualni programski jeziki brez kode.

## 1.6 Razvoj informatike
  - **Howard H. Aiken (Harvard Mark I):** Prvi elektromehanski računalnik.
  - **Grace Hopper:** Razvoj programskega jezika COBOL.
  - **IBM 702 (1955):** Prvi poslovni računalnik s trakom.
  - **IBM 7030 Stretch (1961):** Prvi superračunalnik s tranzistorji.
  - **IBM 360 (1964):** Prvi računalnik s široko uporabnostjo.

## 1.7 Pomembni koncepti v informatiki
  - **Objektno orientirano programiranje (Simula, 1967):** Pojmi razred, objekt, dedovanje.
  - **Relacijski podatkovni model (Edgar Codd, 1970):** Podatkovne baze v obliki tabel.
  - **Internet (ARPANET, 1969):** Razvoj TCP/IP in DNS.
  - **Superračunalniki:** Cray-1 (1975), Fujitsu NWT (1994).

## 1.8 Osebni računalniki
  - **Prvi osebni računalniki (1973-1985):** Micral, ZX Spectrum, Commodore 64, IBM XT/AT.
  - **Bill Gates (Microsoft, MS-DOS, 1980):** Priljubljenost osebnih računalnikov.

---

# Podatki in informacije

## 2. Nastanek informacij
- Informacije so prisotne v vseh vidikih življenja.
- Informacija ima vrednost šele, ko se prenese.
- Elementi prenosa informacij:
  1. Oddajnik → vir informacije.
  2. Sprejemnik → tisti, ki informacijo prejme.
  3. Komunikacijski kanal → medij, po katerem se informacija prenese. <br>

Primer modela oddaje in sprejema informacije:

![Model Oddaje in sprejema informacije](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Motnje.png)

- Vrste komunikacijskih kanalov:
  - Časovni kanal - informacija se prenese skozi čas (npr. zapis zgodovinskih dogodkov).
  - Prostorski kanal - informacija se prenese na različne lokacije v istem trenutku (npr. televizijski signal).
- Motnje:
  - Pri prenosu informacij se lahko pojavijo šumi, ki vplivajo na kakovost informacije.
  - Motnje lahko izkrivijo sporočilo ali povzročijo njegovo izgubo.

## 2.1. Oblike podatkov

### 2.1.1. Analogni podatki

- Najdemo jih v naravi (npr. zvok, temperatura, barve).
- Lastnosti:
   -  Neprekinjena vrednost - neomejeno število stanj.
   -  Natančnost odvisna od opazovalca.
   -  Občutljivost na motnje - manj stabilni pri prenosu in shranjevanju.
   -  Potreba po digitalizaciji - za obdelavo v računalniku jih je treba pretvoriti v digitalno obliko. <br>

    Prikaz analogne oblike podatka:
  
   ![Analogni podatek](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Digital.png)

  ### 2.1.2. Diskretni podatki
  - Končne vrednosti, ki so definirane v določenem intervalu (npr. števila, lestvice ocen):
  - Lastnosti:
    - **Določljivo območje vrednosti** - npr. ocene v šoli od 1 do 5.
    - **Človeku domači** - uporabljamo jih pri štetju in merjenju.
    - **Občutljivi na motnje** - še vedno se izpostavljenji motnjam, a manj kot analogni.
    - **Težji za procesorje** - ker niso enostavno pretvorljivi v dvojiški sistem. <br>
 
    Prikaz diskretne oblike podatka:
    
    ![Diskretni podatki](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Diskretni%20podatki.png)

### 2.1.3. Digitalni podatki
  - **Dvojiški sistem (0 in 1)** - računalniška obdelava temelji na digitalnih podatkih.
  - **Lastnosti:**
    -  Natančno določeno območje vrednosti.
    -  Človeku tuji
    -  Najmanj občjutljivi na motnje - omogočajo zanesljivo shranjevanje in prenos.
    -  Obvezna predstavitev v razumljivi obliki - zato uporabljamo kodiranje besedil, slik in zvoka.
    -  Izredno razširjeni zaradi visoke učinkovitosti obdelave. <br>

  Prikaz digitalne oblike podatka:
    
  ![Digitalni podatki](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Digitalni%20podatki.png)

### 2.1.4. Pretvorba podatkov za delo z računalnikom
  - **Besedila** → znaki tipkovnice se kodirajo v digitalno obliko.
  - **Slike** → celotna slika se pretvori v nize digitalnih vrednosti.
  - **Zvok** → analogni signal (npr. govor) se digitalizira tako, da ohranimo amplitude in frekvence.
   
# Številski sistemi

## 3.1. Vrste številskih sistemov
Številske sisteme delimo glede na pravilo za predstavljanje števil:
- Aditivni (seštevalni)
- Mešani (seštevalni in množilni)
- Pozicijski (mestni)
## 3.2. Aditivni številski sistemi
- Prvi uporabniki: **Egipčani** (okoli 3000 pr. Kr.)
- Hieroglifi kot simboli za različne vrednosti (1, 10, 100, 1000…)
- Pomembne lastnosti:
  - Uporabljajo večkratnike števila 10.
  - Ničla nima simbola. 
## 3.3. Mešani številski sistemi
- Kitajski sistem uporablja dva zapisa:
  - **Tradicionalni** (vertikalni zapis).
  - **Moderni** (horizontalni zapis).
- Primer Kitajskega zapisa:
  - 406 = 4 x 100 + 6 → 四百〇六
  - 4600 = 四千六百<br>
  
 | Poenostavljen simbol | Vrednost |
 |----------------------|---------|
 | 〇                  | 0       |
 | 一                  | 1       |
 | 二                  | 2       |
 | 三                  | 3       |
 | 四                  | 4       |
 | 五                  | 5       |
 | 六                  | 6       |
 | 七                  | 7       |
 | 八                  | 8       |
 | 九                  | 9       |
 | 十                  | 10      |
 | 百                  | 100     |
 | 千                  | 1000    |


- Druge uporabe mešanih sistemov:
  - Merjenje časa (24 ur, 60 minut, 60 sekund).
  - Denarni apoeni (kovanci in bankovci različnih vrednosti).
  - Koledarski sistemi (maji, lunin koledar, japonski koledar).

## 3.4. Rimski številski sistem
- Nepozicijski sistem (vrednost številke je vedno enaka ne glede na položaj).
- Uporablja princip odštevanje (npr. IV = 4, IX = 9).
- Pravila:
  - Simboli so razporejeni od večjega k manjšemu (npr. XV = 15).
  - Ne več kot 3 enaki simboli zapored (npr. III = 3, 4 != IIII, ampak IV).
  - Črta nad številom pomeni množenje s 1000.

Primer:
 - MCMLXXI = 1971

| Simbol | Vrednost |
|--------|---------|
| I      | 1       |
| V      | 5       |
| X      | 10      |
| L      | 50      |
| C      | 100     |
| D      | 500     |
| M      | 1.000   |

## 3.5. Pozicijski številski sistemi
- Vsaka števka ima svojo vrednost glede na položaj (osnova b in eksponent n določata vrednost).
- Splošna formula:
$N = a_n b^n + a_{n-1} b^{n-1} + \dots + a_1 b + a_0 + a_{-1} b^{-1} + a_{-2} b^{-2} + \dots$
- **b** = baza (osnova sistema)
- **a** = števke
- **n** = eksponent (pozicija)

## 3.6. Najpogostejši številski sistemi v računalništvu
1. **Dvojiški** (b = 2, števke: 0,1)
2. **Štiriški** (b = 4, števke: 0,1,2,3)
3. **Osmiški** (b = 8, števke: 0-7)
4. **Šestnajstiški** (b = 16, števke: 0-9, A-F)

## 3.7. Binarna aritmetika
Osnovne operacije:
- **Seštevanje**
- **Odštevanje**
- **Množenje**
- **Deljenje**

Seštevanje (C predstavlja prenos oz. carry):

| A  | B  |A+B | C  |
|----|----|----|----|
| 0  | 0  | 0  | 0  |
| 0  | 1  | 1  | 0  |
| 1  | 0 | 1  | 0  |
| 1  | 1 | 0  | 1  |

Odštevanje (C zopet predstavla prenos oz. carry):

| A  | B  |A-B | C  |
|----|----|----|----|
| 0  | 0  | 0  | 0  |
| 0  | 1  | 1  | 1  |
| 1  | 0 | 1  | 0  |
| 1  | 1 | 0  | 0  |

Množenje:

| A  | B  |A*B |
|----|----|----|
| 0  | 0  | 0 |
| 0  | 1  | 0 |
| 1  | 0 | 0  |
| 1  | 1 | 1  |

 Deljenje:

 | A  | B  |A/B |
 |----|----|----|
 | 0  | 0  | Ni definirano |
 | 0  | 1  | 0 |
 | 1  | 0 | Ni definirano  |
 | 1  | 1 | 1  |

 ## 3.8. Pretvarjanje med številskimi sistemi
 Osnovno pravilo pretvorbe:
 - Število delimo z osnovno sistema v katerega pretvarjamo.
 - Beležimo ostanke.
 - Postopek ponavljamo, dokler kovicent ne postane 0.
 - Končni zapis je obrnjen vrstni red ostankov.

 ### 3.8.1. Pretvorba iz desetiškega v binarni sistem
 Primer: pretvorba števila 23(10) v dvojiški sistem
 1. 23 $\div$ 2 = 11, ostanek **1**
 2. 11 $\div$ 2 = 5, ostanek **1**
 3. 5 $\div$ 2 = 2, ostanek **1**
 4. 2 $\div$ 2 = 1, ostanek **0**
 5. 1 $\div$ 2 = 0, ostanek **1**

 Rezultat: 23(10) = **10111**(2)

 Preizkus:<br>
 $23 = 1 \cdot 2^{4} + 0 \cdot 2^{3} + 1 \cdot 2^{2} + 1 \cdot 2^{1} + 1 \cdot 2^{0} = 16 + 4 + 2 + 1$

### 3.8.2. Pretvorba iz desetiškega v šestnajstiški sistem
Primer: pretvorba števila 29(10) v šestnajstiški sistem
1. 29 $\div$ 16 = 1, ostanek 13 (**D**)
2. 1 $\div$ 16 = 0, ostanek **1**

Rezultat: 29(10) = **1D**(16)
Preizkus:
$29 = 1 \cdot 16^{1} + 13 \cdot 16^{0} = 16 + 13$

## 3.9. Eniški in dvojiški komplement
Predstavitev negativnih števil v binarnem sistemu.

### 3.9.1. Eniški komplement
- Vse bite obrnemo (0 → 1, 1 → 0).
- Primer:
  - 9(10) = 001001(2)
  - Eniški komplement: 110110(2)

### 3.9.2. Dvojiški komplement
- Eniškemu komplementu dodamo 1.
- Primer:
  - 9(10) = 001001(2)
  - Eniški komplement: 110110(2)
  - Dvojiški komplement: 110110 + 1 = 110111(2)

## 3.10. Predznačena in nepredznačena št.
- **Nepredznačena števila:** samo pozitivna (0 do $2^{n}$ - 1).
- **Predznačena števila:** ločena obravnava pozitivnih in negativnih števil.

### 3.10.1. Predznačena števila - dvojiški komplement
- Pozitivna števila se zapisujejo normalno (kot nepredznačena).
- Negativna števila se zapisujejo kot dvojiški komplement.

Pozitivna števila:

| Desetiško | Binarno (8-bitno) |
|---------|----------------|
| 127    | 0111 1111      |
| 126    | 0111 1110      |
| ...     | ...            |
| 1      | 0000 0001      |
| 0      | 0000 0000      |

Negativna števila:

| Desetiško | Binarno (8-bitno) |
|---------|----------------|
| -1      | 1111 1111      |
| -2      | 1111 1110      |
| ...     | ...            |
| -127    | 1000 0001      |
| -128    | 1000 0000      |

## 3.11. Decimalna števila
- Plavajoča vejica omogoča predstavitev zelo velikih ali zelo majhnih števil.
- Splošna formula: $N = M \cdot b^{E}$
  - **M (mantisa)** - glavna vrednost.
  - **b (baza)** - osnova sistema (običajno 2).
  - **E (eksponent)** - premik decimalne vejice.

a) Primer:

$123 = 1{,}23 \cdot 10^{2} = 12{,}3 \cdot 10^{1} = 123 \cdot 10^{0}$

b) Primer:

$0{,}9 \cdot 10^{4} + 14{,}1 \cdot 10^{5}$

Najprej izenačimo eksponente

$0{,}09 \cdot 10^{5} + 14{,}1 \cdot 10^{5} = 14{,}19 \cdot 10^{5}$

Zapišemo rezultat

$14{,}19 \cdot 10^{5} = 1{,}419 \cdot 10^{6}$

### 3.11.1. Enotna predstavitev
- Enojna natančnost (32 bitov)
  - 1 bit za predznak (0 = pozitiven, 1 = negativen).
  - 8 bitov za eksponent.
  - 23 bitov za mantiso.

| 31   | 30–23       | 22–0        |
|------|-------------|-------------|
| S    | Eksponent   | Mantisa     |

## 3.12. Enote shranjevanja podatkov
- Bit (najmanjša enota, vrednost 0 ali 1).
- Byte (B) = 8 bitov.

### 3.12.1.
Po IEC standardu iz 1999

| Ime    | Predpona | Vrednost                         |
|--------|----------|----------------------------------|
| kibi   | Ki       |  $2^{10} = 1.024$            |
| mebi   | Mi       |$2^{20} = 1.048.576$         |
| gibi   | Gi       | $2^{30} = 1.073.741.824$     |
| tebi   | Ti       | $2^{40} = 1.099.511.627.776$ |
| pebi   | Pi       | $2^{50} = 1.125.899.906.842.624$ |
| exbi   | Ei       | $2^{60} = 1.152.921.504.606.846.976$ |

# Pretvorba podatkov

## 4.1. Pretvorba podatkov
Podatke je treba pretvoriti v obliko, ki jo računalnik razume in obdeluje.
Glavna področja pretvorba:
- Besedila
- Slike
- Zvok

## 4.2. Pretvorba besedil

### 4.2.1. Kodiranje znakov
Zgodovinsko:
- **Brailova pisava** - kodiranje za slepe.
- **Morsejeva abeceda** - kodiranje z uporabo kratkih in dolgih signalov.
- **Zastavice v mornarici** - vizualni sistem kodiranja.

Kodirne tabele v računalništvu:
- **ASCII** (American Standard Code for Information Interchage)
  - 7-bitni sistem, sprva omogočal 128 znakov.
  - 8-bitni razširjeni ASCII podpira 256 znakov.
  - Primer: A = 65(10), B = 66(10)
  - Problem: ne podpira posebnih znakov (č, ž, š...).
- **UTF-8** (Unicode Transformation Format)
  - Rešitev za neangleške znake in razširjena uporaba na spletu.
  - Združljiv z ASCII za prvih 128 znakov.
  - Podpira več kot 1 miljon znakov.
  - Spremenljiva dolžina: lahko uporablja 8, 16, 24 ali 32 bitov.

## 4.3. Pretvorba slik

### 4.3.1. Bitne slike
- Vsaka slika je sestavljena iz točk (pikslov).
- Vsako točko opisuje koordinata in barva.
- Lastnosti bitnih slik:
  - Ločljivost - večja kot je ločljivost, več podatkov vsebuje slika.
  - Shranjevanje v različne formate.
  - Uporabljene aplikacije: MS Paint, Adobe Photoshop, Corel Photo-Paint.

### 4.3.2. Kodiranje barv
- Človeško oko zaznava barve preko receptorjev:
  - Čepki (RGB) - za barve.
  - Paličice - za svetlobo.
- Barvne palete za monitorje:
  - RGB (rdeča, zelena, modra) → uporaba pri monitorjih.
  - CMYK (cyan, magenta, rumena, črna) → uporaba pri tiskanju.
  - Sive lestvice → monokromatske slike.

### 4.3.3. Barvna globina (bitna globina)
- Določa, koliko barv lahko prikaže določena naprava.
- Odvisna je od grafične kartice in zaslona.
- Višja bitna globina = več barv in boljši prikaz.

| BITNA GLOBINA | MOŽNE BARVE |
|---------------|-------------|
| 1-bit | Črna-bela (2 barvi) npr. črna = 0, bela = 1 |
| 2-bit | 4 barve; začetna 00, končna 11 |
| 4-bit | 16 barv; črna, bela in 14 sivin |
| 8-bit | 256 barv; črna, bela in 254 sivin |
| 3-bit RGB | črna, bela in 6 za RGB |
| 6-bit RGB | vsaka komponenta ima 2 bit, 64 barv |
| 24-bit RGB | vsaka komponenta 8 bitov, 16,777216 Mbarv |
| 48-bit RGB | vsaka komponenta 16 bitov, 281.474.976.710.656 barv |

### 4.3.4. Barvne palete za tiskarske naprave
- CMYK paleta
- Pantone PMS - Pantone Matching System
- Hexachrom Pantone 6 barv:
  - CMKY + oranžna (O) in zelena (G)
  - bolj svetle in jasnejše slike
  - bolj natančne barve

### 4.3.5. Shranjevanje bitnih slik
**Nekompresirani formati:**
- BMP, TIFF, PNG ...
- Velikost datoteke = $\frac{\text{Širina} \times \text{Višina} \times \text{Barvna globina}}{8}$
- Prednosti:
  - Ni izgube kakovosti pri urejanju ali shranjevanju.
  - Uporabno za grafično oblikovanje in obdelavo slik.
- Slabosti:
  - Zelo velike datoteke.
  - Neučinkovito za prenos po spletu.
**Kompresirani formati:**
- JPEG, GIF, WEBP, ...
- Brezizgubno stiskanje (lossless compression):
  - Lempel-Ziv-Welch (LZW) algoritem (GIF, PNG).
  - Prednost: zmanjša velikost brez izgube podatkov.
- Izgubno stiskanje (lossy compression):
  - JPEG, WEBP, HEIF uporabljajo diskretno kosinusno transformacijo (DCT).
  - Prednost: močno zmanjša velikost slike.
  - Slabost: lahko pride do izgube kakovosti in artefaktov (zamegljeni robovi).

### 4.3.6. Vektorske slike
Vektorske slike odpravljajo slabosti bitnih slik:
- Ločljivost ni omejena (slike lahko povečujemo brez izgube kakovosti).
- Vrtenje, popravljanje, ...
- Učinkovite za oblikovanje logotipov, diagramov, zemljevidov.
- Uporablja se visoka geometrijska natančnost, krajevni vektorji, krivulje, točke, ...
- Primeri programov:
  - Adobe Illustrator (profesionalno oblikovanje).
  - CorelDRAW (grafično oblikovanje).
  - AutoCAD (tehnične risbe, arhitektura).
  - Blender, Cinema 4D (3D grafika in animacija).

**Vektorizacija:**
- Proces pretvorbe bitne slike v vektorsko olbiko.
- Piksli se spremenijo v geometrijske oblike (krivulje, črte, poligoni).
- Prednosti vektorizacije:
  - Ni izgube kakovosti pri povečavi.
  - Hitrejše risanje in manipulacija.
  - Manjša velikost datotek.
- Uporaba:
  - Grafično oblikovanje, tisk, 3D modeliranje, kartografija, ...

### 4.3.7. Shranjevanje vektorskih slik
- Neomejena ločljivost (primerno za tisk).
- Manjša velikost datoteke v primerjavi z bitnimi slikami.
- Idealno za oblikovanje logotipov, pisav, ...
- Neprimerno za kompleksne fotografije (fotografije niso vektorske).
- Težja pretvorba v vektorsko sliko kot obratno.

| FORMAT | UPORABA | PROGRAMI |
|--------|---------|----------|
| SVG (Scalable Vector Graphics) | Spletna grafika | Brskalniki, Inkscape |
| EPS (Encapsulated PostScript) | Tisk in ilustracije | Adobe Illustrator, CorelDRAW |
| AI (Adobe Illustrator format) | Profesionalna grafika | Adobe Illustrator |
| DXF, DWG | Tehnične risbe | AutoCAD, SolidWorks |
| CDR (CorelDRAW format) | Grafično oblikovanje | CorelDRAW |

## 4.4. Pretvorba zvoka

### 4.4.1. Analogine signal in digitalizacija zvoka
**Lastnosti analognega signala:**
- Neprekinjen signal, ki ga lahko izmerimo v kateremkoli trenutku.
- Preveč podatkov za neposredno shranjevanje - potrebno je vzorčenje in kvantizacija.
- Primeri analognih signalov: zvok v naravi, glasba na gramofonski plošči.

**Pretvorba analognega signala v digitalni zapis:**
Za shranjevanje in obdelavo zvoka je potrebna digitalizacija, ki vključuje:
1. Filtriranje (pasovni filter) → odstranitev šuma.
2. Vzorčenje (sampling) → zajem posameznih točk signala.
3. Kvantizacija → zaokroževanje vrednosti na diskretne stopnje.

### 4.4.2. Nyquist-Shannonov teorem vzorčenja
- Določa najmanjšo frekvenco vzorčenja, ki je potrebna za pravilno obnovitev signala.
- Pravilo: frekvenca vzorčenja mora biti vsaj 2x večja od najvišje frekvence signala. <br>
$f_a > 2 \cdot f_v \quad f_v \text{... pasovna širina signala}$ <br>
- Primer:
  - Ljudje slišimo do 20 kHz, zato mora biti frekvenca vzorčenja vsaj 40 kHz.

### 4.4.3. Kvantizacija zvoka
- Vsak vzorec dobi digitalno vrednost (številčno predstavitev).
- Višja bitna globina pomeni boljšo kakovost zvoka. <br>
![Digitalizacija zvoka](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/digitalizacijazvoka.png)
- Pasovni filter - odstranitev šuma (NF, VF)
- Vzorčenje - zajemanje posameznih točk
- Kvantizacija:
  - A/D pretvorniki
  - Kvantizacijska napaka → razlika med dejansko in digitalizirano vrednostjo
  - Kvantizacijski šum → povprečna vrednost kvantizacijske napake.

### 4.4.4. Shranjevanje zvoka
**Nekompresirani avdio formati:**
- Shranjujejo zvok brez izgube kakovosti.
- Problem je velikost.
- Primeri:
  - WAV - standard v Windowsu
  - AIFF - Apple različica WAV formata
  - PCM - format na audio CD-jih
**Kompresirani avdio formati:**
- Zmanjšajo velikost datoteke, lahko pa izgubijo kakovost.
- Kompresija brez izgub (lossless formats)
  - Ohranja izvirni zvok, a še vedno zmanjša velikost datoteke.
  - Primeri:
      - FLAC - odprtokoden, priljubljen za arhiviranje glasbe
      - ALAC - Apple Lossless
      - APE - manj znan, manj razširjen format
- Kompresija z izgubo (lossy formats)
  - Zmanjša velikost z odstranitvijo podatkov, ki jih človeško uho ne zazna.
  - Primeri:
      - MP3 - najbolj razšrijen format
      - AAC - boljša kakovost kot MP3 pri enaki velikosti
      - OGG Vorbis - odprtokodna alternativa za MP3

# Teorija informacij

## 5.1 Osnovni pojmi teorije informacij
Teorija informacij je matematična študija kvantifikacije, shranjevanja in prenosa informacij.
- Utemeljitelj: Claude Shannon (1948).
- Prispevala sta tudi Harry Nyquist in Ralph Hartley.

Ključni pojmi:
- **Entropija** - mera negotovosti pri naključnem dogodku.
- **Redundanca** - količina odvečnih podatkov.
- **Količina informacij** - merilo za vrednost prejete informacije.
- **Kapaciteta prenosnega kanala** - najvišja možna hitrost prenosa podatkov.

## 5.2. Verjetnost stanja
- Ozanaka: p(A) - verjetnost dogodka A.
- Obseg: p(A) $\in [0,1]$
  - p(A) = 0 → dogodek se ne bo zgodil
  - p(A) = 1 → dogodek se bo zagotovo zgodil
  - Vsota vseh verjetnosti mora biti 1: $\sum p_i = 1.$

Primeri:
1. Sistem z enim stanjem:
    - p = 1 $\div$ 1 = 1
2. Sistem z dvema stanjema:
    - p(A) = 1 $\div$ 2 = 0,5
    - p(B) = 1 $\div$ 2 = 0,5
3. Sistem s tremi stanji:
    - p(A) = 1 $\div$ 3 = 0,333
    - p(B) = 1 $\div$ 3 = 0,333
    - p(C) = 1 $\div$ 3 = 0,333

## 5.3. Entropija (Shannonova entropija, 1948)
Definicija:
- Mera negotovosti izida poskua povezanega s slučajno spremenljivko.
- Večja kot je negotovost, večja je entropija.
- Je merilo za količino informacije, ki jo dobimo, ko poznamo vrednost slučajne spremenljivke po izvedbi poskusa. <br>
$H(X) = - \sum p_{i} \log_{2} p_{i}$ <br>
Primeri Shannonove entropije:
1. Met kovanca (2 izida, enaka verjetnost):
  - p = 1 $\div$ 2 = 0,5 <br>
$H = -\sum_i p_i \log_2 (p_i)$ <br>
$H = -(p_1 \cdot \log_2 (p_1) + (p_2 \cdot \log_2 (p_2)))$ <br>
$H = -(0.5 \cdot \log_2 (0.5) + (0.5 \cdot \log_2 (0.5))) = 1 \ \text{b}$ <br>

2. Met kocke (6 izidov, enaka verjetnost):
  - p = 1 $\div$ 6 <br>
$H = -\sum_i p_i \cdot \log_2(p_i)$ <br>
$H = -6\left( p_1 \cdot \log_2(p_1) \right)$ <br>
$H = -6\left( \frac{1}{6} \cdot \log_2\left(\frac{1}{6}\right) \right) = -\log_2\left(\frac{1}{6}\right) = 2,585 \ \text{b}$ <br>

## 5.4. Količina informacija
- Koliko nove informacije pridobimo, ko se zgodi dogodek.
- Merimo jo z logaritmom inverzne verjetnosti dogodka.

Formula: <br>
$I = \log_2 \left( \frac{1}{p_i} \right) \quad p_i \ldots \text{vejetnost pojava i-te možne vrednosti}$ <br>
*če ima nek poskus n enako verjetnih izidov, nastane pri prejetju sporočila* $\log_2\text{n}$ *enot informacije, če imamo sistem z enim stanjem* $l = \log_{2}(1) = 0$ <br>

Primeri:
1. Met kovanca (n = 2): <br>
$l = \log_{2} n = \log_{2} 2 = 1$ <br>
Količina informacije je 1 bit.
2. Met kocke (n = 6) <br>
$l = \log_{2} n = \log_{2} 6 = 2.58496$ <br>
Količina informacij so 3-je biti.

## 5.5. Redundanca
Definicija:
- Razlika med entropijo zbira in njegovo največjo vrednostjo.
- Zmanjšanje redundantnih podatkov → bolj učinkovit prenos podatkov.
Uporaba redundance:
- Pri stiskanju podatkov (odstranjevanje nepotrebnih podatkov).
- Pri odpravljanju napak v komunikacijskih sistemih (self-healing code).
Primer:
- Stavek "Cat is on the mat" vsebuje redundantne (odvečne) besede.
- Če skrajšamo v "Cat on mat", bistvo sporočila ostane isto.

## 5.6. Kapaciteta prenosnega kanala
Definicija:
- Največja količina informacij, ki jih lahko kanal zanesljivo prenese v določenem času. <br>
![Kapaciteta prenosnega kanala](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/kapaciteta.png)<br>
1. Koder (Oddajnik) - pošilja informacijo.
2. Prenosni kanal - medij, po katerem se prenašajo podatki.
3. Dekoder - sprejme in dekodira informacijo.
- Kapaciteta kanala se meri v bitih na sekundo (bps).

## 5.7. Informacijski dobitek
Definicija:
- Količina informacij o naključni spremenljivki, ki jo pridobimo z opazovanjem druge spremenljivke.
Formula: <br>
$IG(T, a) = H(T) - H(T|a)$ <br>
- H(T) - začetna entropija sistema.
- H(T|A) - pogojna entropija T glede na vrednost a.
- IG (Information Gain) - koliko informacij smo pridobili.

Primet - met kovanca:
- Pred metom kovanca imamo **dve možnosti** (glava ali cifra), obe enako verjetni: <br>
$H(T) = - \left( \frac{1}{2} \log_2 \frac{1}{2} + \frac{1}{2} \log_2 \frac{1}{2} \right) = 1 \, \text{bit}$ <br>
- Ko **izvedemo met** in zvemo rezultat (**a** = "glava" ali "cifra"), negotovst izgine, saj izpid poznamo: <br>
$H(T|a) = 0 \, \text{bitov}$ <br>
- Torej, **informacijski dobitek** je: <br>
$IG = H(T) - H(T|a) = 1 - 0 = 1 \, \text{bit}$ <br>
To pomeni, da smo **z metom kovanca pridobili 1 bit informacije**, saj smo iz dveh enako verjetnih možnosti izbrali eno.

Še en primer: <br>
Profesor ima danes popoldan predavanja, ki trajajo 3 ure. Koliko znaša informacijski dobitek, ko je profesor uspešno odpredaval 1 uro?
1. Korak: začetna entropija <br>
$H = - \left( \frac{1}{4} \log_2 \frac{1}{4} + \frac{1}{4} \log_2 \frac{1}{4} + \frac{1}{4} \log_2 \frac{1}{4} + \frac{1}{4} \log_2 \frac{1}{4} \right) = 2 \, \text{b}$ <br>
2. Korak: končna entropija - po prvi uri <br>
$H = - \left( \frac{1}{2} \log_2 \frac{1}{2} + \frac{1}{2} \log_2 \frac{1}{2} \right) = 1 \, \text{b}$ <br>
3. Korak: informacijski dobitek <br>
$ID = H(\text{začetna}) - H(\text{končna}) = 2 \, \text{b} - 1 \, \text{b} = 1 \, \text{b}$


  


# Logične strukture
# Podatkovne strukture in algoritmi
# Uvod v programiranje
# Življenski cikel programske opreme
# Pomen in vloga IT pri ustvarjanju in prenosu znanja
# Inteligentni sistemi
# ChatGPT
# Računalniška omrežja
# Transportni mediji
# Oprema računalniških omrežji
# Kibernetska varnost
