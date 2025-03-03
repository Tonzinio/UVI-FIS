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
  - [Življenjski cikel programske opreme](#Življenjski-cikel-programske-opreme)
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
## 6.1. Uvod v logične strukture
- Računalniška logika temelji na Boolovi algebri.
- Gottfried Wilhelm Leibniz (1690) - ideja univerzalnega formalnega jezika.
- George Boole (1847) - razvil temelje matematične logike.
- Claude Shannon (1930) - uporaba Boolove algebre pri oblikovanju digitalnih vezij.
- Boolova algebra je osnova za digitalno logiko in delovanje računalnikov.

## 6.2. Boolova algebra
- Imenujemo jo tudi preklopna algebra.
- Spremenljivke in funkcije imajo samo dve vrednosti (0 ali 1).
- Osnova za delovanje digitalnih vezij - tranzistorji imajo dve stabilni stanji (on/off).
- Uporaba v računalništvu:
  - Seštevalniki, množilniki, pomikalni registri, števci.

### 6.2.1 Osnovni operatorji
- Disjunkcija (OR, ∨, +)
- Konjunkcija (AND, ∧, *)
- Negacija (NOT, ¬)

## 6.3. Postulati Boolove algebre
**P1: Zaprtost**
- Množica S je zaprta glede na binarni operator, če za vsak par elementov iz množice S in pravila, ki ga definira operator, dobimo element, ki je prav tako element množice S
- Primer: Množica naravnih števil ℕ={1,2,3,…}, je zaprta glede na operator seštevanja (+), ker za vsak par naravnih števil obstaja vsota, ki je prav tako element množice naravnih števil

**P2: Nevtralni element**
- Obstoj nevtralnih elementov: Za vsak x, y ∈ X velja <br>
  p2: za  0 ∈ X, x ∨ 0 = x <br>
  p2': za 1 ∈ X, x ∧ 1 = x <br>

**P3: Komutativnost:** <br>
  - Za vsak x, y ∈ X velja <br>
  p3 : x ∨ y = y ∨ x <br>
  p3’: x ∧ y = y ∧ x <br>
  
**P4: Distributivnost:** <br>
 - Za vsak x, y, z ∈ X velja <br>
 
**P5: Komplementarnost:** <br>
 - Za vsak x ∈ X obstaja ¬x ∈ X in velja <br>
  p5 : x ∨ ¬x = 1 <br>
  p5’: x ∧ ¬x = 0 <br>

**P6: Eksistenca:** <br>
- obstajata vsaj dva elementa x, y ∈ X, tako da x != y

## 6.4. Teoremi Boolove algebre

### 6.4.1. Teoremi z eno spremenljivko
- Idempotentnost:
  - x ⋁ x = x
  - x ⋀ x = x
- Dvojna negacija:
  - ¬¬x = x
- Nevtralni elementi:
  - x ⋁ 1 = 0
  - x ⋀ 0 = 0

### 6.4.2. Teoremi z dvema spremenljivkama
- Absorpcija:
  - x ⋁ (x ⋀ y) = x
  - x ⋀ (x ⋁ y) = x
- De Morganova teorema:
  - ¬(x ⋁ y) = ¬x ⋀ ¬y
  - ¬(x ⋀ y) = ¬x ⋁ ¬y
- Še drugi:
  - (x ⋁ ¬y ) ⋀ y = x ⋀ y
  - (x ⋀ y ) ⋁ y = x ⋁ y
  - (x ⋁ y ) ⋁ ¬x = 1
  - (x ⋀ ¬y ) ⋀ y = 0
### 6.4.3. Teoremi s tremi spremenljivkami
- Asociativnost:
  - x ⋁ (y ⋁ z) = (x ⋁ y) ⋁ z
  - (x ⋀ y) ⋀ z = x ⋀ (y ⋀ z)
## 6.5. Poenostavljanje logičnih izrazov
- Uporaba de Morganovega izreka
  - Primer 1: <br>
    ¬((A + B) ⋅ C) = ¬(A + B) + ¬C = (¬A ⋅ ¬B) + ¬C
  - Primer 2: <br>
    ¬(¬(AB) + CD) = ¬¬(A ⋅ B) ⋅ ¬(C ⋅ D) = A ⋅ B ⋅ (¬C + ¬D) <br>
### 6.5.2. Poenostavljanje izrazov s pravilnostno tabelo
- Na levi strani vhodne spremenljivke (npr. A, B, C).
- Na desni strani izračunane vrednosti funkcije.

| A | B | A ∨ B | A ∧ B |
|---|---|-------|-------|
| 0 | 0 |   0   |   0   |
| 0 | 1 |   1   |   0   |
| 1 | 0 |   1   |   0   |
| 1 | 1 |   1   |   1   |

### 6.5.3. Poenostavljanje z Veitchevim diagramom
- Grafični pripomoček za poenostavljanje logičnih funkcij.
- Združujemo sosednje enice v čim večje skupine.
- Cilj: Izraz poenostaviti z minimalnim številom logičnih operacij. <br>

Veitchev diagram za tri spremenljivke:

![Veitch za 3 spremenljivke](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/veitchza3.png)
  
# Podatkovne strukture in algoritmi

## 7.1. Uvod v algoritme

- Algoritem je postopek za reševanje nekega problema.
- V računalništvu: avtomatiziran postopek za izračunljive probleme, kot so:
  - Finančni izračuni (krediti, varčevanje)
  - Digitalizacija besedil (OCR).
  - Obdelava slik (2D, 3D, animacija).
  - 3D Tiskanje.
  - Obdelava zvoka.
- Pomembnost algoritmov:
  - Za pisanje programov.
  - Pomagajo pri učenju programskih jezikov.
- Pisanje programov zahteva poznavanje kako računalnik "razmišlja" - principi delovanja, operacije, omejitve, podatki...

### 7.1.1. Kako rešiti problem?
1. Prepoznati bistvene lastnosti problema (abstrakcija, modeliranje).
2. Funkcionalna dekompozicija (razčlenitev problema na manjše dele).
3. Spoznavanje majhnih algoritmov in reševanje majhnih problemov.

## 7.2. Opis algoritmov in njihovo zapisovanje

### 7.2.1. Besedni opis algoritma
- Psevdokoda → strukturiran zapis algoritma brez uporabe pravega programskega jezika.
- Pravila za zapis:
1. Prva vrstica vsebuje ime algoritma in vhodne podatke.
2. Uporabljajo se matematični operatorji: +, -, x, /, <, >, =.
3. Pogojni stavki:
```
če pogoj potem
  stavek1
sicer
  stavek2
končaj
```
4. Zanke (ponavljajoče se operacije)
```
dokler pogoj ponavljaj
  stavek1
  stavek2
  ...
končaj
```
5. Spremenljivke:
  - Števec (iterator).
  - Začetna vrednost.
  - Končna vrednost.
  - Korak.
## 7.3. Diagrami poteka algoritmov

### 7.3.1. Osnovni simboli v diagramih poteka <br>

![Diagram za algoritme](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/algoritmi.png) <br>

### 7.3.2. Primer algoritma
- Besedni opis:
```
začetek
vzemi ponev in jajca
če imaš olje potem
  vključi štedilnik
  pristavi ponev
  speči jajca
sicer
  podji v trgovino
  kupi olje
konec
```
- Diagram poteka: <br>

![Diagram poteka](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/diagramPoteka.png) <br>

## 7.4. Preskušanje algoritmov
- Matematično dokazovanje → dokaz pravilnosti algoritma.
- Popoln preizkus → testiranje vseh možnih vhodnih vrednosti.
- Vzorčni poskus → preverjanje začetnih (robnih) primerov.
- Sled algoritma → spremljanje stanja vseh spremenljivk in pogojev v vsakem koraku.

## 7.5. Uvod v podatkovne strukture
- Podatkovne strukture so temeljni gradniki računalništva.
- Določajo organizacijo in shranjevanje podatkov.
- Ključne lastnosti:
  - Omogočajo hiter dostop in učinkovito posodabljanje podatkov.
  - Pomembne za razvoj učinkovitih algoritmov.
  - Predstavljajo shrambo podatkov v pomnilniku.
- Vrste podatkovnih struktur:
  - Primitivne (osnovni podatkovni tipi).
  - Sestavljene (več podatkovnih elementov).
  - Linearne (zaporedno urejene).
  - Nelinearne (grafi, drevesa).

## 7.6. Klasifikacija podatkovnih struktur <br>

![Podatkovne strukture](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/PodatkovneStrukture.png) <br>

### 7.6.1 Primitivne podatkovne strukture

- Ni jih mogoče razgraditi na manjše enote.
- So osnovni gradniki programov.
- Z njimi lahko delamo na strojnem nivoju.
- Vrste:
  - Cela števila (int) - npr. 5, -10, 1000
  - Decimalna števila (float) - npr. 2.15, -7,92
  - Znaki (char) - npr. 'A', 'B', 'C'
  - Logične vrednosti (boolean) - true ali false.

### 7.6.2. Sestavljene podatkovne strukture
- Zgrajene iz primitivnih struktur.
- Delo z njimi na strojnem nivoju ni možno.
- Vsebujejo skupine podatkov:
  - Homogena skupina (vsi elementi istega tipa, npr. tabela števil).
  - Heterogena skupina (različni tipi podatkov, npr. zapisi v bazi podatkov).

Glavne vrste sestavljenih podatkovnih struktur:
1. Linearne podatkovne strukture (urejeni podatki, npr. skladi, vrste, povezani seznami).
2. Nelinearne podatkovne strukture (hierarhični podatki, npr. drevesa, grafi).

### 7.6.3. Linearne podatkovne strukture
- Ohranjajo linearno povezavo med podatkovnimi elementi.
- Vsak element ima predhodnika in naslednika (razen prvega in zadnjega).
- Delijo se na statične in dinamične.

### 7.6.3. Statične podatkovne strukture
- Imajo fiksno velikost.
- Pomnilnik se dodeli ob prevajanju programa.
- Velikosti ni mogoče spreminjati po zagonu, lahko pa spreminja vsebino podatke v njih
- Primer je tabela - ima fiksno velikost, podatke je mogoče spreminjati tudi kasneje
  - Ločimo enodimenzijske, večdimenzijske tabele

### 7.6.5. Dinamične podatkovne strukture
- Velikost se jim spreminja.
- Pomnilnik se dodeli sproti glede na potrebe.
- Prednosti:
  - Učinkovita uporaba pomnilnika.
  - Fleksibilnost pri dodajanju in odstranjevanju elementov.
- Primeri:
  - Povezani seznam (enojno povezani, dvojno, krožni:
  - Sklad – uporablja LIFO (zadnji noter, prvi ven).
  - Vrsta – uporablja FIFO (prvi noter, prvi ven).

### 7.6.6. Nelinearne podatkovne strukture
- Podatki niso razporejeni v zaporednem vrstnem redu.
- Vstavljanje in odstranjevanje podatkov ni izvedljivo na linearnen način.
- Med podatkovnimi elementi obstaja hierarhično razmerje.

Primeri nelinearnih podatkovnih struktur:
1. Drevesa:
  - Binarno drevo (vsako vozlišče ima največ dva otroka).
  - Drevesa za iskanje in razvrščanje podatkov.
2. Grafi:
  - Vozlišča in povezave.
  - Uporaba pri omrežjih, zemljevidih, družbenih omrežjih.
3. Hash tabele:
  - Shranjujejo podatke s pomočjo hash funkcij.
  - Učinkovito iskanje (povezava ključ → vrednost).

## 7.7. Osnovni algoritmi za delo s podatkovnimi strukturami
- Prečkanje (traversing) → prehod skozi elemente strukture.
- Iskanje (searching) → najti določen element v strukturi.
- Vstavljanje (insertion) → dodajanje novih elementov.
- Brisanje (deletion) → odstranjevanje elementov.
- Obračanje (reverse) → sprememba vrstnega reda elementov.
- Odstranjevanje dvojnikov (remove duplicates) → iskanje in brisanje podvojenih vrednosti.

# Uvod v programiranje

## 8.1 Prva generacija računalnikov
- Osnovne komponente:
  - Stikala, elektronke, lučke
  - Brez pomnilnika, podatki so bili shranjeni neposredno v strojni kodi.
- Programiranje:
  - Strojni jezik → nizke ravni, neposredno izvajanje ukazov procesorja.
  - Zahteva vrhunsko poznavanje strojne opreme.
- Slabosti:
  - Programiranje je bilo zelo zapleteno in zamudno.
  - Ni kompleksnih nalog, samo osnovne operacije.
  - Brez pomoči in dokumentacije.

## 8.2. Druga generacija računalnikov
- Prehod na tranzistorje → manjša poraba energije, bolj zanesljivi računalniki.
- Programiranje
  - Zbirni jezik (Assembly Language) → mnemoniki (npr. LDA, ADD, SUB).
  - Uporaba prvih V/I (vhodno-izhodnih) enot.
  - Bolj učinkovit način programiranja kot strojni jezik.
- Primer kode v zbirnem jeziku:
  ```
  org $2000
  start ldaa #$14
  inca
  suba $45
  staa $100
  end
  ```
- Slabosti:
  - Še vedno vezano na konkretne procesorje.
  - Brez visoke abstrakcije → programerji so morali razumeti delovanje strojne opreme.

## 8.3 Tretja generacija računalnikov
- Integrirana vezja → računalniki so postali manjši, hitrejši, z več pomnilnika.
- Pojav prvih višjih programskih jezikov:
  - FORTRAN, COBOL, ALGOL, BASIC, Pascal.
  - Programi so postali prenosljivi med različnimi stroji.
  - Pisanje kode je postalo bolj podobno naravnemu jeziku.
- Primer BASIC programa:
```
10 LET N=10
20 FOR I=1 TO N
30 PRINT "Hello, World!"
40 NEXT I
```
- Prednosti:
  - Lažje popravljanje in razumevanje kode.
  - Uporaba novih vhodno-izhodnih enot (diskretni pogoni, tiskalniki).
  - Programiranje postane bolj dostopno širši javnosti.

## 8.4. Prevajanje in tolmačenje programov

- Programi v višjih programskih jezikih morajo biti prevedeni v strojni jezik.
- Dve metodi prevajanja:
  - Prevajalnik (compiler) → prevede celoten program v izvršljivo datoteko.
  - Tolmač (interpreter) → izvaja program vrstico po vrstico.

### 8.4.1 Prevajalnik (compiler) <br>

![Prikaz prevajalnika](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Prevajalnik.png) <br>

### 8.4.2. Tolmač (interpreter) <br>

![Prikaz tolmača](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/tolmac.png) <br>

- Primer:
```
a = 13
b = 72
c = a + b
print(c)
```
### 8.4.3. Primerjava <br>

| Prevajalnik               | Tolmač                              |
|---------------------------|-------------------------------------|
| Prevede cel program naenkrat | Izvaja programsko vrstico eno za drugo |
| Hiter                     | Počasen                             |
| Generira (.exe)            | Nič ne generira                     |
| Bolj izkorišča procesor    | Manj izkorišča procesor             |
| Uporabija se v produkcijskem okolju | Največ se uporabija pri programiranju in razvojnem okolju |
| C, C++, C#, java           | Python, Ruby, PHP                   |
| Več časa analizira kodo    | Manj časa analizira kodo            |

## 8.5 Četrta generacija računalnikov

- Uporaba mikroprocesorjev → računalniki postanejo dostopni širši javnosti.
- Eksplozija programskih jezikov → hitro programiranje, ni nujno poznavanje strojne opreme.
- Kompleksne naloge
- Primeri jezikov: SQL, R, ABAP (SAP), ColdFusion (spletni razvoj).

## 8.6 Peta generacija računalnikov
- Paralelizacija in umetna inteligenca.
- Vzporedna arhitektura (več procesorskih jeder, večnitenje).
- Uporaba za analizo obsežnih podatkov in strojno učenje.
- Cilji
  - Tehnologije za obdelavo znanja
  - Obdelava obsežnih baz podatkov in znanj
  - Visoko zmogljive delovne postaje
  - Porazdeljene računalniške tehnologije
  - Superračunalnik za znanstveno rabo

## 8.7 Četrta generacija programskih jezikov
- Bolj intuitivni jeziki, bližje naravnemu jeziku.
- Specializirani jeziki za posamezna področja.
- Visoka abstrakcija, avtomatsko generiranje kode.

### 8.7.1 SQL - relacijske baze podatkov
- SQL (Structured Query Language, 1970) za delo z bazami podatkov.
- Enostavno dostopanje do več zapisov hkrati v eni vrstici
- Temelji na relacijski algebri
- Podpira:
  - DML (Data Manipulation Language) → SELECT, INSERT, UPDATE, DELETE.
  - DDL (Data Definition Language) → CREATE, ALTER, DROP.
  - DCL (Data Control Language) → GRANT, REVOKE.
  - DQL (data query language): SELECT
  - TCL (transaction control language): COMMIT, ROLLBACK, BEGIN TRANSACTION

### 8.7.2. ABAP
- Sprva namenjen izdelavi poročil za SAP R/2 platformo.
- Uporablja se za osnovne poslovne aplikacije (upravljanje materialov, finančno in poslovodno računovodstvo) v velikih podjetjih.
- Več nivojev ABAP:
  - SP_BASIS: tehnična podlaga.
  - SAP_ABA: funkcionalnosti za poslovne partnerje in naslove.
  - SAP_UI: orodja za SAP UI5 aplikacije.
  - BBPCRM: poslovna (CRM) aplikacija.
  - SAP ABAP: ERP programski jezik (deli se na module).

 ### 8.7.4. Halida - digitalna obdelava slik
- Namenski specifični jezik (DSL), napisan v C++.
- Izrablja prednosti pomnilnika (vektorske operacije, paralelizacija).
- Uporaben za večjedrne (CPE) in grafične procesorje (GPE).
- Deluje na več platformah (macOS, Linux, Windows).
- Novost: ločitev algoritma od kode, ki določa gnezdenje zank, paralelizacijo, “unrolling” ...
  - Olajša eksperimentiranje z zmogljivostmi (brez ponovnega pisanja samega algoritma).
- Primer: Google PhotoScan, ponekod za obdelavo slik.

### 8.7.5. ColdFusion - spletni razvoj
- Namenski jezik (napisan v Javi).
- RAD platforma za razvoj spletnih aplikacij (hitro oblikovanje).
- Prvotno zasnovan za povezovanje preprostih HTML strani s podatkovnimi bazami.
- Dandanes vključuje IDE (Integrated Development Environment).
- Skripti v jeziku CFML (Coldfusion Markup Language):
  - Sintaksa podobna HTML (oznaka),
  - Programska logika podobna JS (skriptni del).
- Uporaben za dinamične spletne strani in poslovne aplikacije.

### 8.7.6. Prednosti in slabosti 4. generacije
| PREDNOSTI                     | SLABOSTI                              |
|-------------------------------|---------------------------------------|
| **Blížje programerju** (abstrakcija) | Omejení na določeno področje          |
| **Lažje programiranje** (manj kode) | Oddaljenost od strojne opreme → slabša učinkovitost |
| **Manjša možnost napak**      | Zahteven razvoj teh jezikov          |
| **Enostavno vzdrževanie**     | Potrebná je zmogilivejša oprema       |
|                               | Manjša skupnost (manj razširjení)     |

## 8.8. Programski jeziki 5. generacije

- Temeljijo na reševanju problemov z uporabo omejitev in ne z uporabo programerjevega algoritma.
- Usmerjeni v razvoj inteligentnih sistemov, ki lahko sami rešujejo probleme.
- Omogočajo komunikacijo v naravnem jeziku brez zapletenih ukazov.
- Podpirajo samoučeče se sisteme, nevronske mreže in umetno inteligenco.
- Glavne značilnosti:
  - Umetna inteligenca (AI)
  - Strojno učenje
  - Nevronske mreže
  - Vzporedna obdelava podatkov
 
### 8.8.1. Primeri programskih jezikov 5. generacije
- Prolog – uporablja se v umetni inteligenci in logičnem programiranju.
- OPS5 – jezik za ekspertne sisteme.
- Mercury – deklarativen logični jezik, podoben Prologu.
- CVXGen – uporablja se za reševanje optimizacijskih problemov.
- Geometry Expert – za matematično modeliranje in geometrijske dokaze.
- Primer: Mercury (razvit na Univerzi v Melbournu, 1995)
  - Deklarativen logični programski jezik (kot Prolog).
  - Tipiziran jezik – podatki imajo natančno določen tip.
  - Modularna zasnova – programi so sestavljeni iz modulov.
  - Uporaba v umetni inteligenci, verifikaciji programske opreme, lingvistiki.
 
### 8.8.2. Prednosti in slabosti jezika Mercury

| PREDNOSTI                          | SLABOSTI                              |
|------------------------------------|---------------------------------------|
| Omogoča razvoj kompleksnih sistemov | Manj razširjen                        |
| Boljša berljivost kode             | Ni primeren za začetnike             |
| Podpora paralelnemu programiranju   | Potrebno več podrobnosti pri kodiranju |
| Formalna verifikacija programov     | Zahteva več procesorske moči          |

## 8.9. Šesta generacija računalnikov

- Glavne tehnologije:
  - Kvantno računalništvo – izkorišča kvantne bite (qubite) za izračune.
  - Nanotehnologija – uporaba nano naprav za izboljšanje računalniške zmogljivosti.
  - Umetna inteligenca (AI) – vedno večji vpliv v analitiki in avtomatizaciji.
  - Nevronske mreže – zmožnost samostojnega učenja in prilagajanja.
  - Procesiranje naravnih jezikov (NLP) – računalniki razumejo in ustvarjajo človeški jezik.
- Glavne značilnosti:
  - Sistemi se učijo sami (samoučenje).
  - Večja hitrost in računska moč.
  - Izboljšana obdelava podatkov in odločanje.

### 8.9.1. Prednosti in slabosti 6. generacije

| PREDNOSTI                                | SLABOSTI                              |
|------------------------------------------|---------------------------------------|
| Večja povezljivost sistemov              | Povečana ranljivost za vdore          |
| Hitrejše procesiranje ogromnih količin podatkov | Večja nevarnost kibernetskega kriminala |
| Povezovanje različnih naprav (IoT, AI, pametne naprave) | Možna socialna izolacija |

## 8.10 Pregled programskih jezikov skozi leta <br>

![Programski jeziki](https://asset-cdn.tecky.io/2021/10/20/programming_languages_family_trees_uid_616fd206b9de0.png)

## 8.11. Delitev jezikov
- Tradicionalni jeziki
  - Uporabljajo se za razvoj aplikacij.
  - Večina jezikov spada sem (C, C++, Java...).
- Skriptni jeziki
  - Namenjeni avtomatizaciji in povezovanju sistemov (JavaScript, Python, Bash).
- Lastnosti skriptnih jezikov:
  - Izvajajo se sproti (runtime execution).
  - Uporabljajo tolmač namesto prevajalnika.
  - Hitro razvijanje in enostavnejše pisanje kode.

Primeri skriptnih jezikov:
- JavaScript – spletno programiranje.
- Python – podatkovna znanost, avtomatizacija, AI.
- Swift – programiranje za iOS/macOS.
- Ruby – spletni razvoj (npr. Ruby on Rails).
- PHP – strežniško programiranje za spletne strani.

# Življenjski cikel programske opreme

## 9.1. Življenjski cikel programske opreme <br>

![Cikel programske opreme](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/CikelProgramskegaOpreme.png) <br>

## 9.2. Napake pri razvoju
- Sintaktične napake – napake v kodi, ki preprečijo prevajanje.
- Semantične napake – program se sicer izvaja, vendar ne deluje pravilno.
- Posledice napak:
  - Nedelovanje programa.
  - Počasno izvajanje zaradi neučinkovite kode.
  - Napačni rezultati zaradi logičnih napak.
  - Skrite napake (hrošči), ki se pojavijo v določenih pogojih.
- Preskušanje programske opreme:
  - Testiranje uporabniških situacij – preverjanje uporabe programa v realnih situacijah.
  - Notranje in zunanje testiranje – testiranje s strani razvijalcev in zunanjih uporabnikov.
- Hude posledice programskih napak:
  - Mars Climate Orbiter (1998) – izguba sonde zaradi napake v enotah (metrični/sistemski).
  - Boeing 737 MAX (2018, 2019) – težave z avtomatiziranim sistemom MCAS.
  - Ariane 5 raketa (1996) – programerska napaka povzročila eksplozijo.

## 9.3. Programske izdaje
- Programska oprema gre skozi več razvojnih faz pred uradno izdajo.

**Faze programskih izdaj:**
1. Pre-alfa - začetna faza razvoja, program še ni funkcionalen (kaj naj bi program vseboval).
2. Alfa - interni testi, večina funkcij deluje, program še ni stabilen
3. Beta - izdaja omejeni skupini uporabnikov za zunanje testiranje.
4. Kandidat za izdajo gama, delta (release candidate) - skoraj končna verzija, ki vsebuje vse funkcije.
5. Objava izdelka (release to manufacturing) - stabilna verzija, pripravljena za proizvodnjo, glavne napake so odpravljene.
6. Splošna razpoložljivost (general availability) - javno dostopna, uradna različica programa.
7. Podpora (life release) - redne posodobitve in podpora uporabnikom.
8. Konec življenjske dobe (end of life) - konec podpore in posodobitev za program.

## 9.4. Razvojne metodologije
- Obstajata dve glavni skupini razvojnih metodologij:
  1. Klasične metode (razvile so se najprej).
  2. Moderne metode (hiter razvoj, odpravile slabosti klasičnih).

### 9.4.1. Klasične metodologije - Slapovni model (Waterfall)
- Linearen in zaporedni razvojni pristop (vsaka faza se zaključi pred prehodom na naslednjo).
- Sestavljen iz več faz.
- Preprost
- Nekoč je bil zelo priljubljen, danes redkeje.

- Faze slapovnega modela:
  1. Zahteve - zbiranje in analiza zahtev.
  2. Načrtovanje - arhitektura in specifikacije.
  3. Razvoj - kodiranje in testiranje posameznih komponent.
  4. Testiranje - preverjanje pravilnosti celotnega sistema.
  5. Namestitev - prenos produkcijsko okolje.
  6. Vzdrževanje - odpravljanje napak in nadgradnje.

## 9.5. Razvojne metodologije - Moderne metode (Agilne metode)
- Agilne metode omogočajo hitrejši razvoj in boljše prilagajanje spremembam.

**Ključne značilnosti agilnih metod:**
- Iterativni razvoj - stalne izboljšave na podlagi povratnih informacij.
- Minimalno dokumentiranje - poudarek na delujoči programski opremi.
- Sodelovanje z uporabniki, več komunikacije med razvijalci in naročniki.

**Primeri agilnih metod:**
1. SCRUM (1995) - najbolj priljubljena agilna metoda.
2. Extreme programming (XP, 1996) - poudarek na testiranju in preprostosti.
3. Feature-Driven Development (FDD) - razvoj po funkcijah.
4. Rapid Application Development (RAD, 1991) - hitro prototipiranje aplikacij.

### 9.5.1. SCRUM
- Najbolj znana agilna metoda razvoja programske opreme.
- Osredotočena na sodelovanje in timsko delo.
- Iterativni razvoj programske opreme (sprinti).
- Sestava:
  - Cikel (sprint) traja 1-4 tedne, običajno trije cikli.
  - Zahteve so opredeljene s strukturo ciljev (Product Breakdown Structure).
- Sestava:
  - Cikel (sprint) traja 1-4 tedne, običajno trije cikli
  - Zahteve so opredeljene s strukturo ciljev (Product Breakdown Structure).
- 1. cikel - 1. dan:
  - Določitev ciljev in planiranje aktivnosti
  - Predstavnik naročnia izbere funkcijo in jo opredeli z uporabniško izkušnjo
  - Člani ocenijo zahtevnost naloge (Story Points)
  - Sestavi se Sprint Backlog - seznam funkcij za razvoj.
  - Ponovitev postopka do doseganje max. točk cikla.

## 9.6. Dokumentiranje programske opreme
- Dokumentacija je ključna za sledljivost in varnost razvoja.
- Standardi
  - ISO 17799, ISO/IEC 27002 (revidiran 2005, posodobljen 2013, 2022).
- Vrsta dokumentacije:
  1. Razvojna dokumentacija (za razvijalce, ekipo, podjetje).
  2. Uporabniška dokumentacija (za končne uporabnike programske opreme).

### 9.6.1. Razvoja in uporabniška dokumentacija
- Razvojna dokumentacija vključuje:
  1. Dokumenti za zahteve in analizo.
  2. Načrtovalni dokumenti.
  3. Dokumenti za razvoj in implementacijo.
  4. Dokumenti za testiranje.
  5. Dokumenti za vzdrževanje in podporo.
  6. Projektna dokumentacija.

### 9.6.2. Dokumenti za zahteve in analizo
- Dokument o zahtevah (Requirements Document):
  - Opis funkcionalnih in nefunkcionalnih zahtev sistema.
  - Določa specifikacije, kaj sistem počne in kakšne so njegove omejitve.
- Dokument za analizo zahtev (Requirements Analysis Document):
  - Analiza zahtev, določitev prioritet in scenarijev uporabe.
- Specifikacija zahtev programske opreme (System Requirements Definition):
  - Opisuje arhitekturo in podatkovne tokove sistema.

### 9.6.3. Načrtovalni dokumenti
- Arhitekturni načrt (System Architecture Document):
  - Splošna zasnova sistema (komponente, povezave, tehnologije).
- Načrt podatkovne baze (Database Design Document):
  - Struktura baze podatkov (tabele, relacije, omejitve).
- Načrt uporabniškega vmesnika (UI/UX Design Document):
  - Skice, prototipi in vizualna zasnova vmesnika.
- Dokument za načrtovanje podrobnosti (Detailed Design Document):
  - Implementacijske podrobnosti, algoritmi, razredi, metode.

### 9.6.4 Dokumenti za razvoj in implementacijo
- Smernice za kodiranje (Coding Standards Document):
  - Pravila za strukturo kode, imena spremenljivk, komentiranje.
- Dokumentacija kode (Code Documentation):
  - Podrobni opisi funkcij, metod in razredov – olajša razumevanje kode.
- Dnevnik sprememb (Change Log):
  - Beleži vse spremembe, izboljšave in popravke kode skozi čas.

### 9.6.5 Dokumenti za testiranje
- Načrt testiranja (Test Plan)
  - Vključuje strategije testiranja, cilje, obseg, vire in časovne okvire.
- Testni primeri (Test Cases)
  - Opis posameznih testov:
    - Vhodni podatki
    - Pričakovani rezultati
    - Postopki za izvajanje testov
- Poročilo o testiranju (Test Report)
  - Povzetek rezultatov testiranja.
  - Težave, ki so bile odkrite, in njihov status.

### 9.6.6 Dokumenti za vzdrževanje in podporo
- Dokumentacija za namestitev (Installation Guide):
  - Navodila za namestitev programske opreme na različne sisteme.
- Uporabniški priročnik (User Manual):
  - Navodila za končne uporabnike o uporabi programske opreme.
- Priročnik za vzdrževanje (Maintenance Manual):
  - Informacije za vzdrževalce programske opreme.
  - Potrebni popravki, posodobitve in postopki za odpravljanje težav.
 
### 9.6.7 Projektna dokumentacija
- Projektni načrt (Project Plan):
  - Določa cilje projekta, vire, časovni okvir, stroške in odgovornosti ekipe.
- Dokument za upravljanje tveganj (Risk Management Document):
  - Seznam možnih tveganj in načini obvladovanja le-teh.
  - Načrti za odzivanje v primeru težav.
- Poročila o napredku (Progress Reports):
  - Poročila o trenutnem stanju projekta.
  - Vsebuje:
    - Opravljene naloge.
    - Ovire pri razvoju.
    - Načrt za prihodnje korake.

## 9.7 Specifikacija zahtev programske opreme (Software Requirements Specification – SRS)
- SRS združuje ključne zahteve in pričakovanja za programsko opremo.
- Osnovni dokument za:
  - Razvoj.
  - Testiranje.
  - Zagotavljanje kakovosti.
- Osnova za komunikacijo med naročniki, uporabniki, analitiki in načrtovalci.
- Vsebina SRS:
  - Funkcionalne in nefunkcionalne zahteve.
  - Analiza zahtev, vključno s prioritetami in scenariji uporabe.
  - Visok nivo arhitekture in osnovne skice uporabniškega vmesnika.
  - Sprejemljivostni kriteriji in visokonivojski testni primeri.


# Pomen in vloga IT pri ustvarjanju in prenosu znanja

### 10.1 Uvod
- Informacija je temelj vsakega znanja.
- IT (informacijska tehnologija) omogoča:
  - Zbiranje podatkov.
  - Obdelavo informacij.
  - Shranjevanje znanja.
  - Širjenje informacij.

### 10.2 Vpliv IT na ustvarjanje in prenos znanja
- IT ima ključno vlogo pri:
  1. Dostopu do informacij in virov znanja.
  2. Ustvarjanju in organizaciji znanja.
  3. Prenosu znanja in komunikaciji.
  4. Učinkovitem izobraževanju in usposabljanju.
  5. Skladiščenju in dostopnosti znanja za prihodnost.
  6. Spodbujanju inovacij in raziskav.

#### 10.2.1 Dostop do informacij in virov znanja
- Splet omogoča hiter in enostaven dostop do:
  - Raziskovalnih baz.
  - Spletnih enciklopedij.
  - E-knjig, spletnih tečajev, ...
- Digitalne knjižnice in baze podatkov:
  - Dostop do znanstvenih člankov, raziskav.
  - Spodbujajo raziskovalno delo in inovacije na različnih področjih.

#### 10.2.2 Ustvarjanje in organizacija znanja
- IT omogoča:
  - Zbiranje, analiziranje in obdelavo podatkov.
  - Odkrivanje novih oblik znanja s pomočjo podatkovne analize, umetne inteligence in strojnega učenja.
  - Sistematično organizacijo in shranjevanje znanja v podjetjih in organizacijah.

#### 10.2.3 Prenos znanja in komunikacija
- Spletne platforme (Zoom, MS Teams, Slack):
  - Omogočajo sodelovanje na daljavo in lažjo izmenjavo informacij in znanja.
- Družbeni mediji in blogi:
  - Hitro širjenje informacij in razprava v realnem času.

#### 10.2.4 Učinkovito izobraževanje in usposabljanje
- E-izobraževanje in spletni tečaji (Coursera, edX, Udemy):
  - Omogočajo dostopno in fleksibilno učenje.
- Učni sistemi za upravljanje (Moodle, Blackboard):
  - Podpirajo upravljanje učnih gradiv, ocenjevanje, komunikacijo in spremljanje napredka v učnem procesu.
- VR in AR tehnologije:
  - Navidezna in obogatena resničnost omogočata interaktivno in bolj realistično učenje.

**Navidezna resničnost (VR – Virtual Reality)**
- V realnem času
- Simulacija popolnoma virtualnega okolja.
- Področja uporabe:
  - Avtomobilska industrija (testiranje modelov).
  - Letalska industrija (simulacija letov).
  - Arhitektura (3D modeli zgradb).
  - Usposabljanje gasilcev (simulacija požarov).
  - Igre, konstruiranje, turizem.

**Obogatena resničnost (AR – Augmented Reality)**
- Združuje resnični in virtualni svet s pomočjo kamere.
- Področja uporabe:
  - Oblikovanje in gradnja (IKEA Place – virtualno pohištvo v prostoru).
  - Vojska (usposabljanje v simuliranih bojnih razmerah).
  - Promet (letalstvo, avtomobili – navigacija).
  - Vzdrževanje in popravila (interaktivni prikazi navodil).
  - Zdravstvo (kirurški posegi, vizualizacija organov).

#### 10.2.5 Skladiščenje in dostopnost znanja za prihodnost
- Varno shranjevanje podatkov na oblaku ali v podatkovnih centrih.
- Digitalizacija podatkov:
  - Ohranjanje zgodovinskih dokumentov, knjig in drugih pomembnih virov.

#### 10.2.6 Spodbujanje inovacij in raziskav
- IT omogoča hitro eksperimentiranje in testiranje hipotez:
  - Simulacije, modeliranje in analitična orodja pospešujejo inovacije.
- Raziskovalna orodja in programska oprema:
  - Omogočajo natančno analizo podatkov in hitrejše odkrivanje novih znanj.

# Inteligentni sistemi
### 11.1 Inteligentni sistemi – Uvod
- Inteligentni sistemi zaznavajo okolje in samostojno sprejemajo odločitve.
- Lastnosti:
  - Lahko so preprosti (npr. termostat) ali kompleksni (npr. avtonomni roboti).
  - Učijo se in izboljšujejo svoje delovanje.
- Primeri uporabe:
  - Pametni domovi (termostati). <br>
  ![Pametni Termostat](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/pametniTermostat.png) <br>
  - Industrijski nadzorni sistemi.
  - Sistemi umetne inteligence (AI).

### 11.2 Umetna inteligenca
- UI (umetna inteligenca) = je proučevanje in načrtovanje inteligentnih sistemov.
- Glavni cilji UI:
  - Simulacija človeškega razmišljanja.
  - Sposobnost zaznavanja, odločanja in prilagajanja okolju.
- Z zgledovanjem po naravi so nastali:
  - Genetski algoritmi
  - Genetsko programiranje
  - Nevro-evolucija

#### 11.2.1 Genetski algoritmi (GA):
- Navdihnjeni z Darwinovo teorijo evolucije.
- Postopek:
  1. Populacija – naključna populacija možnih rešitev.
  2. Selekcija – najboljši kandidati (ocenjevalna funkcija) preživijo in se razmnožijo.
  3. Križanje in Mutacija – kombinacija lastnosti in naključne spremembe za izboljšanje.
  4. Iteracija – ponavljanje postopka do sprejemljive rešitve.
- Vsak cikel boljša rešitev

#### 11.2.2 Genetsko programiranje (GP):
- Cilj: Samodejno ustvarjanje računalniških programov za reševanje določenih problemov.
- Omogoča inovativne rešitve brez eksplicitnega programiranja problema.

**Značilnosti:**
- Reprezentacija kot drevo:
  - Vozlišča predstavljajo operacije (npr. seštevanje, množenje).
  - Listi predstavljajo spremenljivke ali konstante.
- Selekcija, križanje in mutacija:
  - Uporabljajo se enaki principi kot pri genetskih algoritmih, vendar na programski strukturi.
- Samodejno iskanje programskih rešitev:
  - Ne optimizira le parametrov, temveč tudi strukturo in logiko programa.
- Prilagoditev skozi generacije:
  - Programi se izboljšujejo skozi več generacij, dokler ne dosežejo visoke učinkovitosti.

**Uporaba:**
- Kadar ni možno učinkovito zajeti zapletenih ali spreminjajočih se okoliščin.
- Strojno učenje – optimizacija napovednih modelov.
- Obdelava signalov – avtomatizirana prilagoditev filtrov.
- Odkrivanje novih algoritmov – avtomatsko generiranje novih metod za analizo podatkov.

#### 11.2.3 Nevro-evolucija
- Kaj je nevro-evolucija?
  - Povezuje evolucijske algoritme z umetnimi nevronskimi mrežami.
  - Optimizira nevronske mreže brez človeškega posredovanja.

**Ključni elementi nevro-evolucije:**
- Optimizacija strukture in parametrov:
  - Evolucijski algoritem prilagaja uteži, število slojev in število nevronov v mreži.
  - Poišče najboljšo arhitekturo za določen problem.
- Selekcija, križanje in mutacija za nevronske mreže:
  - Podobno kot pri genetskih algoritmih, vendar se uporablja na nivoju mreže.
  - Postopno izboljševanje nevronskih mrež skozi generacije.
- Samodejno učenje brez človeškega nadzora:
  - Sistem sam odkrije optimalne rešitve, kar je pomembno pri kompleksnih problemih.
  - Uporabno v primerih, kjer je ročno nastavljanje težko ali nemogoče.
- Uporaba pri kompleksnih problemih:
  - Načrtovanje gibanja robotov.
  - Nadzorni sistemi v industriji.
  - Videoigre.

### 11.3 Umetna inteligenca (UI)
- Umetna inteligenca računalnikom in strojem omogoča:
  - Simulacijo človeškega učenja,
  - Razumevanja in reševanja problemov,
  - Odločanja,
  - Zaznavanja okolja,
  - Ustvarjalnosti,
  - Samostojnosti,
  - Prilagajanju okolju.

#### 11.3.1 Povezava UI in inteligentnih sistemov
- Omogočanje avtonomnosti
  - UI omogoča sistemom, da sami prepoznavajo okolico, nevarnosti in sprejemajo odločitve.
  - Primer: Avtonomna vozila prepoznavajo znake, semaforje in ovire ter se prilagajajo prometnim razmeram.
- Učenje iz podatkov
  - UI uporablja strojno učenje za izboljšano napovedovanje, diagnosticiranje in odločanje.
  - Primer: Algoritmi v medicini analizirajo podatke pacientov in predlagajo diagnoze.
- Prilagodljivost in prilagajanje
  - UI omogoča sistemom prilagajanje novim informacijam in spremembam v okolju.
  - Primer: Industrijski roboti prilagajajo proizvodni proces glede na zahteve.
- Obdelava naravnega jezika in interakcija
  - UI razume govor in besedilo ter omogoča interakcijo s človekom.
  - Primer: Siri, Google Assistant in Alexa odgovarjajo na vprašanja in izvajajo ukaze.
- Sistematično odločanje
  - UI analizira kompleksne podatke in sprejema odločitve na podlagi pravil.
  - Primer: Banke uporabljajo UI za prepoznavanje goljufij.
- Integracija več senzorskih podatkov
  - UI združuje informacije iz kamer, radarjev, LIDAR senzorjev in drugih virov.
  - Primer: Avtonomna vozila uporabljajo več tipov senzorjev za celovito razumevanje okolja.

#### 11.4 Tehnologije v inteligentnih sistemih

- Inteligentni sistemi delujejo na različnih področjih in uporabljajo več tehnologij.

**11.4.1 Strojno učenje (Machine Learning)**

- Ključna tehnologija, ki omogoča učenje iz podatkov, izboljšuje napovedi in odločitve.
- Trije glavni tipi algoritmov:
  - Nadzorovano učenje (Supervised Learning) – uporablja označene podatke za učenje.
  - Nenadzorovano učenje (Unsupervised Learning) – odkriva vzorce v neoznačenih podatkih.
  - Učenje s krepitvijo (Reinforcement Learning) – sistem se nagrajuje za pravilne odločitve.

1. Nadzorovano učenje
- Vhodni podatki so znani.
- Učitelj nastavlja izhode na želene vrednosti (človeški nadzor).
- Proces učenja:
  - Večkrat ponavljamo izračune, da algoritem bolj uspešno prepozna vhodne podatke.
  - Uporablja se za kompleksne modele, kjer so podatki že razvrščeni.

**Vrste nadzorovanega učenja:**
- Klasifikacija:
  - Izraža se pri kategoričnih izhodnih spremenljivkah z določenim številom razredov (najmanj dva).
  - Primer: Razvrščanje e-pošte na spam in legitimna sporočila.
- Regresija:
  - Napoveduje realne ali zvezne vrednosti.
  - Primer: Določanje plače glede na delovne izkušnje in zahtevnost dela.

**Primeri uporabe:**
- Ocena tveganja (banke preverjajo kreditno sposobnost strank).
- Prepoznavanje oseb na posnetkih.
- Odkrivanje goljufij v finančnih transakcijah.
- Sistemi priporočil (Netflix, YouTube, spletne trgovine priporočajo izdelke glede na preteklo obnašanje uporabnika).

2. Nenadzorovano učenje
- Algoritem prejme neznane podatke in sam odkriva vzorce brez navodil.
- Brez človeškega nadzora – učitelj ne posega v izhodne vrednosti.
- Uporablja se za velike količine podatkov, ki jih je treba smiselno razvrstiti.

**Vrste nenadzorovanega učenja:**
- Združevanje v gruče (Clustering):
  - Podobni podatki se združujejo v skupine.
  - Primer: Segmentacija strank v trgovini na podlagi nakupnih navad.
- Asociacijska pravila:
  - Algoritem prepoznava vzorce povezav (če - potem) med podatki.
  - Primer: Če stranka kupi določene izdelke, bo verjetno kupila še druge (trgovski algoritmi).
- Zmanjšanje dimenzij:
  - Odstrani manj pomembne podatkovne točke za boljšo vizualizacijo.
  - Primer: Uporaba metode PCA (analiza glavnih komponent) za zmanjšanje števila spremenljivk v analizi podatkov.

**Primeri uporabe:**
- Odkrivanje novih trendov v nakupovalnih vzorcih.
- Klinične diagnoze (analiza simptomov in napovedovanje bolezni).
- Obdelava jezika (klasifikacija besed in kategorizacija člankov).
- Genetske raziskave (analiza DNK in prepoznavanje evolucijskih vzorcev).

3. Učenje s krepitvijo
- Algoritem maksimizira kumulativne nagrade v določenih situacijah.
- Sistem učenja skozi izkušnje:
  - Algoritem (agent) preizkuša različne poteze in na podlagi nagrad in kazni (povratne informacije) prilagaja svoje vedenje.
  - Postopek vključuje interakcijo z okoljem za iskanje optimalnih rešitev.

**Primeri uporabe:**
- Robotika – roboti se učijo gibanja skozi različne izzive (sledenje poti, izogibanje ovíram).
- Obdelava naravnega jezika (NLP) – izboljšava komunikacije z računalniki (Google Assistant, Siri).
- Trženje in oglaševanje – iskanje optimalnih strategij oglasov glede na uporabniške odzive.
- Obdelava slik in umetni vid – analiza medicinskih slik (MRI, CT) za odkrivanje bolezni.
- Avtomatizacija prometa – izboljšava delovanja semaforjev in nadzor prometnih tokov.
- Videoigre – računalniški nasprotniki se učijo igranja skozi ponavljanje.
- Varčevanje z energijo – optimizacija porabe energije v podatkovnih centrih in pametnih napravah.ž

**11.4.2 Globoko učenje (Deep Learning)**
- Uporablja umetne nevronske mreže z več plastmi za analizo kompleksnih vzorcev v že označenih vhodnih podatkih.
- Vrste globokega učenja:
  - CNN (Convolutional Neural Networks) konvolucijske nevronske mreže → prepoznavanje objektov v slikah, tudi če so delno zakriti.
  - DRL (Deep Reinforcement Learning) učenje z globoko krepitvijo → uporablja se v robotiki in igrah, agent se nauči kako se obnašati preko komunikacije in sistema nagrad.
  - RNN (Recurrent Neural Networks) ponavljajoče se nevronske mreže → uporablja se za obdelavo jezika in prepoznavanje govora, razume kontekst in generira besedila.

**Izzivi globokega učenja:**
- Velike zahteve po podatkih → modeli potrebujejo ogromne količine podatkov za učenje.
- Prekomerno prileganje → modeli lahko naučijo šum v podatkih in ne najdejo osnovnih povezav.
- Pristranskost → modeli lahko vsebujejo nepravične ali netočne napovedi, kar zahteva posebne tehnike za zmanjšanje pristranskosti.

**11.4.3 Obdelava naravnega jezika (Natural Language Processing – NLP)**
- Omogoča računalnikom razumevanje, obdelavo in generiranje človeškega jezika.
- Ključna vprašanja pri NLP:
  - Kdo govori?
  - O čem govorijo?
  - Kako se počutijo?
  - Zakaj se tako počutijo?

**Tehnologije NLP vključujejo:**
- Analiza sentimenta → prepoznavanje in izločanje občutkov v besedilih.
- Razumevanje konteksta → razčlenitev stavkov, izločitev samostalniških fraz in tem.
- Prevajanje besedil → avtomatsko prevajanje (Google Translate).
- Klepetalni roboti (chatbot) → avtomatski asistenti za komunikacijo s strankami.

**11.4.4 Računalniški vid (Computer Vision)**
- Tehnologija, ki omogoča zaznavanje in interpretacijo vizualnih informacij (slike, videi).
- Posnema način, kako ljudje vidijo in razumejo okolico.

**Tehnike računalniškega vida vključujejo:**
- Prepoznavanje obrazov → zaznavanje značilnih točk in razdalj na obrazu.
- Prepoznavanje predmetov → klasifikacija objektov v okolju (ljudje, vozila, zgradbe).
- Sledenje gibanja → spremljanje objektov v video sekvencah.

**Primeri uporabe računalniškega vida:**
- Prepoznavanje obrazov → varnostni sistemi, policija, nadzor.
- Analiza gibanja ljudi in vozil → štetje potnikov na letališčih, prometna analiza.
- Avtonomna vozila → odzivanje avtomobila na okolico.
- Slikanje v medicini → diagnosticiranje bolezni, razvoj protetike.
- Obogatena resničnost (AR) → uporaba v igrah, reklamah in interaktivnih aplikacijah.
- Kontrola kakovosti → avtomatsko preverjanje izdelkov v proizvodnji.
- Športna analitika → analiza gibanja športnikov in strategij.
- Kmetijstvo → spremljanje pridelkov z droni, avtomatizirana kmetijska vozila.

**11.4.5 Robotika v zahtevnih okoljih**
- Avtonomni robotski sistemi
  - Delujejo samostojno v kompleksnih okoljih (zrak, voda, tla).
  - Izvajajo naloge, kot so kartiranje, načrtovanje poti, abstrakcija okolja.
- Rehabilitacijski inženiring
  - Pomaga pri obnovi senzomotoričnih funkcij pri ljudeh z nevrološkimi ali mišičnimi motnjami.
- Senzomotorični sistemi
  - Povezava med človekom in strojem (npr. rehabilitacija, kirurška medicina).
- Robotski vid
  - Uporaba malih dronov za digitalizacijo arheoloških najdišč, iskanje in reševanje.
- Nevroinženiring
  - Razvoj nevrorehabilitacijskih naprav in računalniških modelov za stimulacijo živčnega sistema pri amputirancih in diabetikih.
- Dodatna področja robotike:
  - Roboti za gibanje in manipulacijo v ekstremnih okoljih.
  - Pametni tekstil (e-tekstil) → analiza bioloških signalov in spremljanje biomarkerjev.
  - Akustični robotski sistemi → nanoroboti za diagnostiko, 3D tisk tkiv in organov.
  - Robotski materiali → bioelektronika za implantate in kirurgijo.
  - Mehka robotika → roboti po navdihu bioloških sistemov (robotska riba).
  - Avtomatizirana kuhinja → roboti v prehrambeni industriji.

**11.4.6 Sistemi za odločanje**
- Ali po angleško Decision Making Systems so algoritmi, ki omogočajo analizo podatkov in sprejemanje odločitev.
- Vključujejo:
  - Metode optimizacije → matematični modeli za izboljšanje vhodnih parametrov.
  - Napovedne modele → regresija, odločitvena drevesa, nevronske mreže.
  - Pravila, ki jih ustvarja UI → ekspertni sistemi za odločanje.

**Uporaba:**
- Dobavne verige → optimizacija logistike.
- Planiranje dela → avtomatizirano dodeljevanje nalog.
- Ocena tveganja → analiza varnostnih in poslovnih tveganj.
- Industrija → prilagajanje proizvodnih procesov.
- Medicina → računalniška diagnostika bolezni.
- Finance → zaznavanje goljufij, ocena tveganja za kredite.

**Prednosti sistemov za odločanje:**
- Hitrejše in natančnejše odločitve → omogočajo hiter in natančen vpogled v kompleksne podatke.
- Manj napak in večja doslednost → objektivna analiza zmanjšuje človeške napake.
- Boljše sodelovanje → omogočajo učinkovito komunikacijo med oddelki.
- Zmanjšanje tveganja → analizirajo vplive različnih odločitev pred njihovo izvedbo.

**11.4.7 Internet stvari (IoT – Internet of Things)**
- Povezovanje senzorjev in naprav z inteligentnimi sistemi.
- Naprave komunicirajo preko interneta → omogočajo nadzor in avtomatizacijo.
- Sprejemanje odločitev na daljavo → pametni domovi, energetski sistemi, avtomatizacija proizvodnje.

**Primeri IoT naprav:**
- Pametne svetilke, termostati, varnostni sistemi.
- Pametni telefoni, pametni zvočniki.
- IoT v zdravstvu (sledenje pacientom, senzorji vitalnih znakov).

**Zgodovina razvoja IoT:**
- 1972 → Stanfordski laboratorij za umetno inteligenco razvije prvi IoT sistem, računalniško voden prodajni avtomat.
- 1999 → Kevin Ashton prvi uporabi izraz Internet of Things.
- 2004 → Napoved, da bo število IoT naprav preseglo število uporabnikov interneta.
  - 2010 na vsakega človeka priključeno 1,84 naprave.
- 2020 → 50,1 milijarde IoT naprav po napovedi Cisca in Ericssona.

### 11.5 Kronologija <br>
![Kronologija UI](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/kronologijaUI.png) <br>

#### 11.6 Generativna umetna inteligenca
- Temelji na naprednih generativnih modelih strojnega učenja.
- Vrste generativnih modelov:
  - Generativno-adverzalne mreže (GAN)
    - Sestavljata jih dva modela, ki tekmujeta med seboj:
      - Generator ustvarja nove podatke.
      - Diskriminator ocenjuje, ali so ti podatki pristni ali umetni.
    - Uporaba: ustvarjanje realističnih slik, videov, zvokov.
  - Avtokodirniki (Autoencoders)
    - Modeli kodirajo vhodne podatke v stisnjeno predstavitev.
    - Nato dekodirajo te informacije in ustvarijo nove vzorce.
  - Transformerski modeli
    - Uporabljajo arhitekturo Transformer za obdelavo zaporedij in ustvarjanje novih vsebin, na podlagi naučenih vzorcev.
    - Primeri: GPT (besedilo), DALL-E (slike).

**11.6.1 Generativna umetna inteligenca – aplikacije**
- Ustvarjanje besedila
  - Generacija člankov, esejev, zgodb, pesmi.
  - Samodejno ustvarjanje e-poštnih sporočil, povzetkov, odgovarjanje na vprašanja (npr. ChatGPT).
- Generiranje slik
  - Ustvarjanje fotorealističnih slik iz opisov (DALL-E, Stable Diffusion).
  - Restavriranje slik, spreminjanje stilov, generiranje novih umetniških del.
- Ustvarjanje zvoka in glasbe
  - Generacija glasbenih kompozicij, ki posnemajo različne stile.
  - Sintetiziranje govora z naravnim zvenom (virtualni asistenti).
- 3D modeliranje
  - Generiranje 3D objektov za igre, animacije, simulacije.
- Raziskovanje novih materialov
  - Generativni modeli v kemiji in farmaciji odkrivajo nove spojine in zdravila (GNoME - DL).
- Zabava in igre
  - Generiranje vsebin v videoigrah (nivoji, liki, zgodbe).
  - Interaktivni filmi, kjer se zgodba prilagaja uporabniku.
- Oblikovanje
  - Generativni modeli se uporabljajo pri ustvarjanju logotipov, grafičnih elementov in dizajnov.

**Prednosti in izzivi generativne UI:**

| PREDNOSTI | IZZIVI |
|-----------|--------|
| Kreativnost na zahtevo → omogoča ustvarjanje vsebin brez človekovega posredovanja. | Kakovost → generirane vsebine so lahko napačne, nesmiselne ali nenatančne. |
| Prilagodljivost → uporablja se v različnih panogah (umetnost, znanost, medicina). | Etika in zloraba → lažne novice, deepfake videi, ponarejena besedila. |
| Samodejna personalizacija → ustvarjanje prilagojenih vsebin za uporabnike. | Računski stroški → veliki modeli zahtevajo izjemno zmogljive računalniške vire. |
| Povečanje produktivnosti → avtomatizacija ustvarjalnih procesov. | Pomanjkanje originalnosti → generirani podatki so pogosto le preoblikovane kopije obstoječih vzorcev. |


# ChatGPT
- Spada v generativno umetno inteligenco (NLP – obdelava naravnega jezika).
- LLM (Large Language Model) temelji na Transformer arhitekturi.
- Ustanovitelj OpenAI (2015), znani modeli: GPT, DALL-E, Codex.
- Začetek ChatGPT – 2022, najhitreje rastoča aplikacija (100M uporabnikov v dveh mesecih, januar 2023).
- Tehnologije, ki jih uporablja:
  - Računalništvo v oblaku (Azure – Microsoft).
  - Algoritmi za optimizacijo (Adam optimizer) – izboljšanje učinkovitosti učenja.
  - NLP – analiza besedil s sodobnimi metodami obdelave jezika.

**Ključni koncepti ChatGPT:**
- Učenje iz podatkov – uporablja ogromne količine podatkov iz različnih področij.
- Transformer arhitektura – uporablja mehanizem samo-pozornosti (self-attention) za razumevanje pomena besed v stavkih in dokumentih.
- Generativni pristop – ne le analizira vsebine, temveč tudi ustvarja novo besedilo na podlagi učenja.

#### 12.1 Temeljni modeli

- GPT-4 (14. marec 2023) → uporablja ga ChatGPT Plus in Microsoft Copilot.
  - Januar 2024: GPT-4 dosegel le 17 % natančnost pri diagnozi pediatričnih primerov.
- GPT-4o → izboljšana verzija GPT-4, z naprednimi matematičnimi izračuni, jezikovnim razumevanjem, zaznavanjem slik in kontekstualno natančnostjo.
  - Pametnejši, a dražja komunikacija.
- GPT-4o Mini → manjša, cenejša komunikacija, namenjena osnovnim interakcijam s strankami in ustvarjanju preprostih vsebin.
- o1-preview in o1-mini (beta) → modeli za kompleksno sklepanje in reševanje težjih problemov.
- SearchGPT → specializiran model za optimizacijo spletnega iskanja (natančnejši rezultati).
- GPT-3.5 Turbo → hitrejša in cenejša različica za osnovne naloge.

**Dodatni modeli OpenAI:**
- DALL-E – ustvarjanje slik iz besedilnega opisa.
- TTS (Text-to-Speech) – pretvarjanje besedila v naravni govor.
- Whisper – pretvarjanje zvoka v besedilo (podnapisi).
- Embeddings model – pretvarjanje besedila v številčne vektorje.
- Moderation model – preverjanje vsebin na občutljivost ali nevarnost.

#### 12.2 Podatkovni centri
- Grafične procesne enote (GPE)
  - NVIDIA GPU (A100 in H100) → optimizirani za umetno inteligenco.
  - Več 10.000 povezanih GPE omogoča vzporedno procesiranje podatkov.
- Tenzorske procesne enote (TPE)
  - Optimizirane za globoko učenje.
  - Uporabljajo se za treniranje nevronskih mrež in reševanje kompleksnih matematičnih problemov.
- Skupna procesna zmogljivost
  - Dosega več exaflops (10^18 flops/s).
  - Hkrati obdeluje milijone zahtev uporabnikov.
- Centralne procesne enote (CPE)
  - AMD Ryzen 9 5900X (12 jeder, 24 niti, 4,8 GHz).
  - Uporablja se za procesiranje globokega učenja.
  - Predpomnilnik:
    - Cache L1: 64 KB na jedro.
    - Cache L2: 512 KB na jedro.
    - Cache L3: 64 MB skupaj.
  - RAM: 32 GB DDR4 – 3600 MHz.
- Tenzorske procesne enote (TPE)
  - Google TPU (Tensor Processing Unit), specializirana integrirana vezja za pospeševanje strojnega učenja.
  - Zmanjšana natančnost (8-bitna), a 15–30x hitrejši od klasičnih GPE.
  - Optimiziran za tenzorske operacije (matrike).
  - 420 Tflops / poraba 220W - v3
  - Podpira knjižnice: TensorFlow, JAX in PyTorch
  - 2048 kom TPE v3
- Grafični procesorji (GPE)
  - NVIDIA GeForce RTX 3070
    - 6144 jeder, 1,77 GHz, 8 GB GDDR6.
    - Skupaj povezanih 10.000 grafičnih procesorjev za poganjanje AI modelov.
  - CUDA arhitektura:
    - Omogoča paralelno procesiranje.
    - Je API, ki pospešuje procesiranje z GPE
    - Nadomestil je Direct3D in OpenGL
    - Optimizirano za naloge povezane z globokim učenjem.

**Shranjevanje podatkov:**
- Več petabajtov (PB) podatkov.
- SSD diski z visokim pretokom podatkov (4 TB, 14,5 Gb/s, PCIe).

**Mrežne zmogljivosti:**
- Majhna latenca (zakasnitev).
- Velika pasovna širina (ocena 100 Gb/s).

**Energetska poraba:**
- Ogromna poraba
- 1–3 % svetovne porabe energije gre za podatkovne centre.
- Uporaba obnovljivih virov energije (50x večja kot pri poslovnih zgradbah).

**Energetska poraba za 2023:**
- Bing (Microsoft): 7200 MWh za 5–6 mesecev.
- ChatGPT: 1248 MWh za 26 dni.

**Tržna vrednost umetne inteligence:**
- 2023: 196 milijard $.
- 2026 (napoved): 299,64 milijard $.

**Proces učenja modelov UI:**
- Zahteva več 100.000 GPU ur.
- Inferenčni mehanizem omogoča odgovore v realnem času.

**Lokalnost podatkovnih centrov:**
- Več globalnih podatkovnih centrov zagotavlja hitro delovanje.
- Regionalna redundanca → vsak center prilagojen glede na lokacijo.
- Več 100 sočasnih uporabnikov na vozlišče.
- Visoka razpoložljivost → v primeru napake prevzame delo drug podatkovni center.

### 12.3 Prihodnost

#### 12.3.1 Avtomatizacija in produktivnost
- Generiranje vsebin
  - Ustvarjanje poročil, člankov, povzetkov, marketinških gradiv, scenarijev, knjig.
- Pametna orodja za pisanje
  - Samodejno dokončanje, popravki in slogovna analiza.
  - Postanejo standardna komponenta pisarniških in komunikacijskih orodij.
- Avtomatizirano kodiranje
  - UI lahko pomaga pri odkrivanju napak in generiranju celotnih funkcionalnih komponent.

#### 12.3.2 Personalizirana storitev za uporabnike
- Pametni pomočniki
  - Bolj naravni in prilagojeni posamezniku.
  - Pomoč pri načrtovanju, upravljanje IoT naprav, digitalno svetovanje.
- Samopostrežne platforme
  - Avtomatizacija podpore strankam.
  - Natančna analiza povpraševanja in reševanje težav brez človeškega posredovanja.

#### 12.3.3 Izobraževanje in usposabljanje
- Prilagodljivo učenje
  - Osebni mentorji ponujajo prilagojene učne vsebine in odgovore na vprašanja.
- Ustvarjanje učnih načrtov
  - Generacija personaliziranih učnih gradiv, kvizov, povzetkov - lažja priprava vsebin.
- Simulacije in interaktivno učenje
  - Simulacija realnih scenarijev v izobraževalnem okolju (učenje jezikov, reševanje problemov).

#### 12.3.4 Raziskave in znanosti
- Pospeševanje raziskovalnih procesov
  - Analiza znanstvenih člankov, generiranje povzetkov in predlogov za nadaljnje raziskave.
- Odkritje vzorcev v velikih podatkih
  - Uporaba v bioinformatiki, astrofiziki in socialnih vedah.
- Ustvarjanje hipotez
  - Generiranje predlogov za nove eksperimente in raziskovalne smeri.

#### 12.3.5 Zdravstvo
- Klinične aplikacije
  - Generacija zdravniških poročil, analiza pacientovih podatkov in pomoč pri diagnostiki.
- Izobraževanje pacientov
  - Pojasnjevanje medicinskih terminov in protokolov na razumljiv način.
- Podpora zdravnikom
  - Analiza medicinske literature, priprava zdravniških zapisov in oblikovanje personaliziranih terapij.

#### 12.3.6 Industrija in poslovanje
- Analiza trga
  - Generacija poročil o trendih in analiza velikih količin podatkov za podporo odločanju.
- Upravljanje z dokumenti
  - Razvrščanje in povzemanje dokumentov ter iskanje informacij v kompleksnih arhivih.
- Optimizacija delovnih tokov
  - Avtomatizacija administrativnih nalog in izboljšanje učinkovitosti dela.

#### 12.3.7 Kreativne industrije
- Ustvarjanje umetniških del
  - Generacija pesmi, glasbenih besedil, scenarijev in konceptov za videoigre.
- Podpora umetnikom
  - Generiranje osnutkov in inspirativnih vsebin za ustvarjalce.

#### 12.3.8 Pravo in pravne storitve
- Pomoč pri analizi zakonodaje
  - Hiter pregled zakonov in izdelava povzetkov ter analiz.
- Generiranje pravnih dokumentov
  - Pisanje pogodb, pritožb in drugih pravnih besedil.
- Dostopnost prava
  - Preprosta pojasnila pravnih pojmov za širšo javnost.

#### 12.3.9 Etika, regulacija in odgovornost
- Etična uporaba
  - Razvoj politik za odgovorno uporabo umetne inteligence in preprečevanje zlorab (dezinformacije, pristranskost).
- Pravni okviri
  - Določanje lastništva vsebin, ustvarjenih z modeli umetne inteligence.
  - Odgovornost za odločitve, ki jih predlagajo tovrstni modeli.

#### 12.3.10 Novi mejniki v umetni inteligenci
- Avtonomni agenti
  - LLM-ji kot temelj za avtonomne sisteme, ki lahko opravljajo kompleksne naloge z minimalnim človeškim posredovanjem.
- Večmodalni modeli
  - Povezava LLM-jev z drugimi tipi podatkov (slike, zvok, video) za bolj inteligentne in naravne interakcije.

# Računalniška omrežja

#### 13.1 Kaj so računalniška omrežja?
- **Definicija**: Skupina povezanih omrežnih naprav za izmenjavo podatkov, storitev in sredstev.
- **Minimalne zahteve**: Vsaj dve napravi; lahko jih je na milijone (internet).
- **Network Operating System (NOS)**:
  - OS za podporo omrežja (Windows, Unix, Linux, Mac OS).
  - Omogoča povezovanie virov in upravljanje omrežja.
- **Prijava v omrežje**:
  - Uporabniško ime in geslo → omejitev dostopa neavtoriziranih uporabnikov.

#### 13.2 Zgodovina računalniških omrežij
- **Prvi prenosi podatkov**: Zunanji pomnilniki (diskete, magneto-optični diski, USB).
- **Povezovanie s kabil**: Prvi korak k omrežjem.
- **1973 – Bob Metcalfe**: Razvoj Ethernet povezave.
- **Hiter razvoj**:
  - Rast omrežij in vpeljava optike.
  - Prekooceanske povezave omogočajo globalno komunikacijo.

#### 13.3 Vrste računalniških omrežij
1. **LAN (Local Area Network)** – lokalno omrežje
   - Povezuje naprave znotraj stavbe ali podjetja.
   - Standardna oblika omrežij za organizacije (100–1000 povezanih naprav).
2. **MAN (Metropolitan Area Network)** – mestno omrežje
   - Združuje več lokalnih omrežij znotraj mesta ali naselja.
   - Primer: kabelski operaterji in mestna infrastruktura.
3. **WAN (Wide Area Network)** – prostrano omrežje
   - Povezuje lokalna in prostrana omrežja, lahko tudi čez državne meje.
   - Primer: internet ali povezave med poslovnimi enotami po svetu.

#### 13.4 Omrežna oprema
- **Prenosni mediji**:
  - Fizični kabli (optični, UTP, koaksialni).
  - Brezžični prenos (Wi-Fi, Bluetooth, satelitske povezave).
- **Periferne naprave**:
  - Lokalni tiskalniki, pametni telefoni, MP3 predvajalniki.
- **Gostitelji (hosts)**:
  - Strežniki, prenosniki, mrežni tiskalniki, namizni računalniki.
- **Mrežna oprema**:
  - Stikala (switches), usmerjevalniki (routers), dostopne točke (AP).

#### 13.5 Ključni koncepti omrežij
- **Vozlišča (nodes)** – naprave, ki so povezane v omrežje (računalniki, telefoni, tiskalniki).
- **Povezave (links)** – fizične (kabli) ali brezžične (Wi-Fi, Bluetooth).
- **Protokoli** – pravila komunikacije, ki določajo način prenosa podatkov (npr. TCP/IP, HTTP, FTP).
- **Naslavljanje**:
  - IP naslovi – edinstveni identifikatorji naprav v omrežju.
  - MAC naslovi – unikatni fizični naslovi mrežnih kartic.

#### 13.6 Topologija omrežij
- **Veda**, ki proučuje načine povezovanja omrežnih komponent v omrežje.
- **Geometrijski načrt podatkovnega medija** (fizična povezava med dvema ali več vozlišči).
- **Cilj**: Povezava naprav in učinkovito komuniciranje.
- **Delovanje**:
  - Naprave razdelijo podatke na pakete in jih pošljejo prek omrežja.
  - Vsaka naprava predstavlja vozlišče v omrežni topologiji.

##### 13.6.1 Vrste topologij računalniških omrežij
- **Fizična topologija**:
  - Prikazuje natančno postavitev računalnikov, naprav in vodnikov.
  - Pomembna za monterje in vzdrževalce omrežij. <br>
![Fizična topologija](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/fizicnaTopologija.png) <br>

- **Logična topologija**:
  - Določa pot paketa skozi omrežje.
  - Definira podomrežja in razporeditev IP naslovov. <br>
![Logična topologija](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/logicnaTopologija.png)

##### 13.6.2 Topologija vodila (Bus topology)

- **Najstarejša omrežna topologija** – prvi način povezovanja računalnikov.
- **Kako deluje?**
  - Vse naprave so priključene na skupni podatkovni medij.
  - Na obeh koncih vodila so terminatorji (za preprečevanje odboja signala).
  - Vsaka naprava vidi vse pakete, vendar jih obdelajo samo tisti, katerim so namenjeni. <br>
  ![Topologija vodila](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/topologijaVodila.png) <br>
  
- **Težave in omejitve**:
  - Veliko nepotrebnega prometa v omrežju.
  - Možnost trkov paketov → zmanjšuje učinkovitost.
  - Težko odpravljanje napak – težko določiti mesto prekinitve.

| **Prednosti in slabosti topologije vodila** |
|---------------------------------------------|
| **Prednosti**                               |
| Potrebujemo manj kablov.                    |
| Enostavno dodajanje novih uporabnikov.      |
| Ni potrebe po posebnih vozliščih (npr. stikalih, usmerjevalnikih). |
| **Slabosti**                                |
| Kompleksna povezava vozlišč na vodilo.      |
| Težko je določiti mesto napake pri prekinitvi vodila. |
| Veliko možnosti za trke paketov.            |
| Omejena dolžina medija in potreba po bi-direktivnem mediju. |

##### 13.6.3 Topologija obroča (Ring topology)

- **Kako deluje?**
  - Uporabnik se poveže preko kosa kabla – tako nastane obroč.
  - Osnovni gradnik je zveza točka-točka.
  - Novi uporabniki se priključijo preko glavnega medija.
  - Podatki potujejo od enega računalnika do drugega, dokler ne dosežejo cilja.
  - Uporablja se sistem žetona (token passing) – računalnik lahko pošlje podatke le, če ima žeton. <br>
  ![Topologija obroča](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/topologijaObroca.png) <br>

| **Prednosti in slabosti topologije obroča** |
|---------------------------------------------|
| **Prednosti**                               |
| Manj kablov kot pri zvezdni topologiji.     |
| Lažje določanje napak v primerjavi z vodilom. |
| Redundanca – uporaba FDDI (dvojni optični kabel) izboljša zanesljivost. |
| **Slabosti**                                |
| Izpad enega segmenta lahko onesposobi celotno omrežje (če ni redundance). |
| V mreži - mesta za računalnike.             |

##### 13.6.4 Topologija zvezde (Star topology)

- **Kako deluje?**
  - Vsi uporabniki so direktno povezani s centralnim vozliščem (stikalo ali usmerjevalnik).
  - Osnovni gradnik je zveza točka-točka.
  - Uporabniki delijo vire centralnega vozlišča.
  - Zelo primerna je pri komunikacijah med centralnim vozliščem in uporabniki.
  - Danes pri komunikacijah med uporabniki.
  - Centralno (aktivno) vozlišče je računalnik oz. stikalo.

| **Prednosti in slabosti topologije zvezde** |
|---------------------------------------------|
| **Prednosti**                               |
| Manj zmogljivi računalniki lahko delujejo v omrežju. |
| Centralni računalnik ali stikalo opravi večino dela. |
| Izpad ene povezave onesposobi samo enega uporabnika, ne celotnega omrežja. |
| Testiranje, vzdrževanje, diagnosticiranje in vodenje v eni točki. |
| **Slabosti**                                |
| Kabelsko najbolj potratna topologija (veliko kablov). |
| Če odpove centralno vozlišče, odpove celotno omrežje. |
| Več uporabnikov → slabša učinkovitost mreže. |

##### 13.6.5 Hibridna topologija (Hybrid topology)

- **Združuje več različnih topologij** (npr. kombinacija zvezde in obroča).
- **Uporaba pri velikih omrežjih** (npr. korporacije, globalne mreže).
- **Primeri**:
  - WAN omrežja (internet, korporacijska omrežja).
  - ARNES, Renault – kompleksna omrežja, ki povezujejo različne lokacije.
- **Izzivi hibridnih omrežij**:
  - Kompleksna administracija in namestitev.
  - Visoki stroški zaradi uporabe različnih tehnologij.
  - Napredne varnostne funkcije so nujno potrebne za zaščito podatkov.

##### 13.6.6 Topologija drevesa (Tree topology)

- **Struktura hierarhično povezanih omrežij**, kjer so podomrežja razdeljena kot veje drevesa.
- **Primerna za velika omrežja**, kjer je potrebna razširljivost in ločitev funkcionalnosti.
- **Povezuje več zvezdnih omrežij** in omogoča pokrivanje večjih geografskih območij.
- **Najbolj pogosta topologija**.

| **Prednosti in slabosti topologije drevesa** |
|---------------------------------------------|
| **Prednosti**                               |
| Omogoča povezovanje sistemov na velikih razdaljah. |
| Prenos večjih obremenitev – obremenitev se porazdeli. |
| Dodajanje novih uporabnikov je relativno enostavno. |
| **Slabosti**                                |
| Izpad ene povezave lahko izolira celotno podomrežje. |
| Kompleksna shema in zahtevnejši nadzor.     |

##### 13.6.7 Polna topologija (Mesh topology)

- **Vsaka naprava je povezana z vsemi ostalimi napravami v omrežju**.
- **Uporaba**:
  - Brezžična omrežja → prilagodljiva povezava naprav.
  - Primer: Mini mesh usmerjevalnik (2007).

| **Prednosti in slabosti polne topologije** |
|-------------------------------------------|
| **Prednosti**                             |
| Več vozlišč → več možnih poti za prenos podatkov. |
| Odpoved ene povezave ne vpliva na delovanje celotnega omrežja. |
| Izredno zanesljiva in varna.              |
| **Slabosti**                              |
| Zelo visoka cena zaradi velikega števila povezav. |
| Kabelsko najbolj potratna topologija.     |
| Redko uporabljena v praksi zaradi kompleksnosti. |
| Zahtevna namestitev in konfiguracija.     |

#### 13.7 Protokoli v računalniških omrežjih

- **Pravila komunikacije med napravami ali ljudmi v omrežju**.
- **Opredeljujejo način izmenjave podatkov**, vključno z:
  - Predstavitvijo pošiljatelja in prejemnika.
  - Izbiro komunikacijskega medija (osebno, telefon, video, internet).
  - Načinom komuniciranja (govor, pisanje, slike, multimedija).
  - Jezikom komunikacije (npr. HTML za spletne strani, SMTP za e-pošto).
  - Strukturo stavkov, slovnico.
  - Hitrostjo in terminom komunikacije.

#### 13.8 ISO/OSI referenčni model

- **ISO/OSI (Open Systems Interconnection) model** → standardiziran komunikacijski model, ki omogoča uspešno izmenjavo podatkov med napravami različnih proizvajalcev.
- **Ustvarjen pod okriljem ISO (International Organization for Standardization, 1947)**.
- **Zagotavlja kompatibilnost med napravami**.
- **Vsebuje 7 ravni (plasti)**, kjer vsak sloj opravlja specifično nalogo (modulirana zgradba).

##### 13.8.1 Plasti ISO/OSI modela

1. **Aplikacijska plast** – omogoča uporabniško interakcijo.
2. **Predstavitvena plast** – pretvarja podatke v standardizirano obliko.
3. **Sejna plast** – upravlja seje med napravami.
4. **Transportna plast** – zagotavlja zanesljiv prenos podatkov.
5. **Omrežna plast** – določa poti podatkovnih paketov skozi omrežje.
6. **Povezovalna plast** – omogoča dostop do fizičnega medija.
7. **Fizična plast** – definira električne in mehanske lastnosti povezave.

- **Istoimenske plasti se sporazumevajo s pomočjo kontrolne informacije**.
- **Plasti komunicirajo s pomočjo enkapsulacije** (dodajanje glave in repa podatkom med prenosom).
- **Na sistemu A**:
  - Vsaka plast prejme podatke iz zgornje plasti in doda dodatne informacije (glavo/rep/oboje).
- **Na sistemu B**:
  - Prejeta plast odstrani dodatne informacije in posreduje podatke naprej.

##### 13.8.2 Fizična plast

- **Odgovorna za prenos podatkov po omrežju**.
- **Določa**:
  - Mehanske in električne lastnosti povezave.
  - Postopke vzpostavitve, vzdrževanja in prekinitve povezave.
  - Nivo signala in hitrost prenosa podatkov.
  - Največjo možno razdaljo med napravami.
  - Mehanske lastnosti konektorjev.
- **Organizacije**:
  - ISO (International Organization for Standardization) – določa globalne standarde.
  - IEEE (Institute of Electrical and Electronics Engineers) – razvija standarde za omrežja (Ethernet, Wi-Fi).
  - ANSI (American National Standards Institute) – ameriški nacionalni standardi.
  - ITU (International Telecommunication Union) – telekomunikacijski standardi.
  - EIA (Electronics Industry Alliance) – določanje standardov za elektronsko industrijo.
  - FCC (Federal Communication Commission) – regulacija radijskih frekvenc in komunikacij v ZDA.
- **Standardi**:
  - Ethernet - Standardna tehnologija za žično omrežno povezavo, ki omogoča komunikacijo med napravami v lokalnih omrežjih (LAN).
  - IEEE 802.3 - Skupina standardov, ki definirajo Ethernet omrežja, vključno s hitrostmi in načini prenosa podatkov.
  - 100BaseT (fast ethernet) - Različica Etherneta s hitrostjo 100 Mbps, ki uporablja zvite parice (UTP) za prenos podatkov.
  - TokenRing - Omrežni protokol, pri katerem naprave komunicirajo prek obroča in prenos podatkov nadzoruje posebni žeton (token).
  - FDDI - Standard za omrežja z optičnimi vlakni, ki zagotavlja visoke hitrosti prenosa (do 100 Mbps) in odpornost na napake.
  - FrameRelay - Protokol za prenos podatkov v širokopasovnih omrežjih (WAN), ki omogoča učinkovito paketno komutacijo.
  - SIP - Protokol za vzpostavljanje, upravljanje in prekinjanje sej v IP-telefonskih in večpredstavnostnih komunikacijah (VoIP, videokonference).

##### 13.8.3 Povezovalna plast

- **Odgovorna za dostavo sporočil med vozlišči**.
- **Nadzira strojno opremo**, ki upravlja prenosni medij.
- **Omogoča prenos podatkov brez napak**.
- **Pošiljanje paketov preko MAC naslova prejemniku**.
- **Sestavljena iz dveh podplasti**:
  - LLC (Logical Link Control) → nadzor logične povezave, osnova za IP in IPX.
  - MAC (Medium Access Control) → nadzor dostopa do fizičnega medija.
- **Definira**:
  - Enote sporočila (znaki, bloki, paketi).
  - Ugotavljanje in odpravo napak med vozlišči.
  - Omrežno topologijo (vodilo, obroč).
  - Kontrolo pretoka (Flow Control).
  - Protokole za prenos podatkov v omrežje.
- **Standardi**:
  - Ethernet - Standardna tehnologija za žično omrežno povezavo, ki omogoča komunikacijo med napravami v lokalnih omrežjih (LAN).
  - PPP (Point-to-Point Protocol) – Omrežni protokol, ki omogoča prenos podatkov preko točkovnih povezav, pogosto uporabljen pri vzpostavitvi povezav preko modema, ISDN ali VPN.
  - MAC (Media Access Control) – Podplast podatkovne povezave (Data Link Layer) v OSI modelu, ki upravlja dostop naprav do fizičnega omrežja in določa unikatne MAC naslove vsake naprave.
  - LLC (Logical Link Control) – Podplast podatkovne povezave v OSI modelu, ki zagotavlja nadzor nad komunikacijo, sinhronizacijo in odpravo napak v prenosu podatkov med napravami.
  - FDDI - Standard za omrežja z optičnimi vlakni, ki zagotavlja visoke hitrosti prenosa (do 100 Mbps) in odpornost na napake.

##### 13.8.4 Omrežna plast

- **Določa logično naslavljanje in usmerjanje paketov**.
- **Naloge**:
  - Naslavljanje (IP naslovi, preklapljanje paketov).
  - Izbira poti → dinamična ali statična.
  - Usmerjanje paketov prek enega ali več omrežij.
  - Uporaba usmerjevalnih algoritmov za optimalno pot podatkov.
- **Pošiljanje zahtev po storitvah povezavne plasti**.
- **Standardi in protokoli omrežne plasti**:
  - IP (IPv4, IPv6) – osnovni protokol za prenos podatkov.
  - ICMP – pošiljanje diagnostičnih sporočil (ping).
  - OSPF, RIP, EIGRP – usmerjevalni protokoli.
  - IPsec – varnostna plast za zaščiten IP prenos.

##### 13.8.5 Transportna plast

- **Zagotavlja zanesljivost prenosa podatkov med dvema končnima točkama**.
- **Funkcije**:
  - Ureja vrstni red paketov – prispejo v enakem vrstnem redu, kot so bili poslani.
  - Zagotavlja konsistentnost prejetih podatkov.
  - Regulira hitrost prenosa – preprečuje preobremenjenost.
  - Razrešuje zasičenje omrežja.
- **Standardi in protokoli transportne plasti**:
  - TCP (Transmission Control Protocol) → zagotavlja zanesljiv prenos.
  - UDP (User Datagram Protocol) → hitrejši, vendar brez zagotavljanja zanesljivosti.
  - SCTP, DCCP, RSVP – napredni protokoli za specifične uporabe.

##### 13.8.6 Sejna plast

- **Omogoča vzpostavitev, uporabo in zapiranje povezav (sej)**.
- **Določa vrsto komunikacije**:
  - Enosmerna (simplex) – en oddajnik, več sprejemnikov.
  - Napol dvosmerna (half-duplex) – izmenično sprejemanje in oddajanje.
  - Dvosmerna (duplex) – hkratno sprejemanje in oddajanje.
- **Sinhronizacija komunikacije**.
- **Protokoli in standardi**:
  - NetBIOS – omogoča omrežno komunikacijo v operacijskih sistemih.
  - SMPP – protokol za kratka sporočila (SMS).
  - H.245 – nadzor večpredstavnostne komunikacije.
  - PPTP – tuneliranje VPN povezav.
  - PAP, RPC – protokoli za oddaljene klice storitev.

##### 13.8.7 Predstavitvena plast

- **Skrbi za obliko podatkov pri prenosu med napravami**.
- **Pretvarja podatke med različnimi formati**.
- **Funkcije**:
  - Kompresija in dekompresija podatkov → izboljšanje učinkovitosti prenosa.
  - Šifriranje podatkov → zagotavlja varnost prenosa.
  - Standardizirani podatkovni formati → zvok, video, slike (MP3, MP4, JPEG, PNG).
  - Uporaba različnih naborov znakov (ASCII, EBCDIC).
- **Servisi**:
  - Pretvorba podatkov → iz enega formata v drugega.
  - Prevod znakovnih kod → grafični znaki v številke za prenos in shranjevanje.
  - Stiskanje → zmanjšanje količine podatkov za hitrejši prenos.
  - Šifriranje in dešifriranje → zaščita podatkov pred nepooblaščenimi osebami.
  - Serializacija → pretvorba podatkovne strukture v format primeren za shranjevanje ali pošiljanje.
- **Standardi**:
  - LPP (Lightweight Presentation Protocol) – lahek protokol za predstavitveno plast.
  - ICA (Independent Computing Architecture) – oddaljeni dostop do aplikacij.
  - NDR (Network Data Representation) – zapis podatkov pri oddaljenih klicih.
  - EDR (External Data Representation) – standardiziran format podatkov.

##### 13.8.8 Aplikacijska plast

- **Neposredno vidna uporabnikom** in zagotavlja internetne storitve ter procese.
- **Naloge aplikacijske plasti**:
  - Prepoznavanje sogovornika v komunikaciji.
  - Ugotavljanje, ali je zmogljivost omrežja zadostno velika.
  - Sinhronizacija komunikacije med napravami.
- **Standardni protokoli aplikacijske plasti**:
  - DNS (Domain Name System) – prevajanje domen v IP naslove.
  - DHCP (Dynamic Host Configuration Protocol) – dinamična dodelitev IP naslovov.
  - FTP (File Transfer Protocol) – prenos datotek po internetu.
  - HTTP/HTTPS (Hypertext Transfer Protocol Secure) – prikaz spletnih strani.
  - IMAP/POP/SMTP – protokoli za pošto (prejemanje in pošiljanje e-pošte).
  - SIP (Session Initiation Protocol) – vzpostavljanje in prekinjanje VoIP klicev.
  - SSH (Secure Shell) – varna povezava do oddaljenih sistemov.
# Transportni mediji
# Oprema računalniških omrežji
# Kibernetska varnost
---
# Vaje 1
## Računalniška aritmetika

1. Zapis števila 1234,56 v splošni obliki: <br>
$$
1234,56 = 1 \times 1000 + 2 \times 100 + 3 \times 10 + 4 \times 1 + 5 \times 0,1 + 6 \times 0,01
$$ <br>

