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

Primer modela oddaje in sprejema informacije
![Model Oddaje in sprejema informacije](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Motnje.png)

- Vrste komunikacijskih kanalov:
  - Časovni kanal - informacija se prenese skozi čas (npr. zapis zgodovinskih dogodkov).
  - Prostorski kanal - informacija se prenese na različne lokacije v istem trenutku (npr. televizijski signal).
- Motnje:
  - Pri prenosu informacij se lahko pojavijo šumi, ki vplivajo na kakovost informacije.
  - Motnje lahko izkrivijo sporočilo ali povzročijo njegovo izgubo.

## 2.1. Oblike podatkov

## 2.1.1. Analogni podatki

- Najdemo jih v naravi (npr. zvok, temperatura, barve).
- Lastnosti:
   -  Neprekinjena vrednost - neomejeno število stanj.
   -  Natančnost odvisna od opazovalca.
   -  Občutljivost na motnje - manj stabilni pri prenosu in shranjevanju.
   -  Potreba po digitalizaciji - za obdelavo v računalniku jih je treba pretvoriti v digitalno obliko. <br>

    Prikaz analogne oblike podatka:
  
   ![Analogni podatek](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Digital.png)

  ## 2.1.2. Diskretni podatki
  - Končne vrednosti, ki so definirane v določenem intervalu (npr. števila, lestvice ocen):
  - Lastnosti:
    - **Določljivo območje vrednosti** - npr. ocene v šoli od 1 do 5.
    - **Človeku domači** - uporabljamo jih pri štetju in merjenju.
    - **Občutljivi na motnje** - še vedno se izpostavljenji motnjam, a manj kot analogni.
    - **Težji za procesorje** - ker niso enostavno pretvorljivi v dvojiški sistem. <br>
 
    Prikaz diskretne oblike podatka:
    
    ![Diskretni podatki](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Diskretni%20podatki.png)

## 2.1.3. Digitalni podatki
  - **Dvojiški sistem (0 in 1)** - računalniška obdelava temelji na digitalnih podatkih.
  - **Lastnosti:**
    -  Natančno določeno območje vrednosti.
    -  Človeku tuji
    -  Najmanj občjutljivi na motnje - omogočajo zanesljivo shranjevanje in prenos.
    -  Obvezna predstavitev v razumljivi obliki - zato uporabljamo kodiranje besedil, slik in zvoka.
    -  Izredno razširjeni zaradi visoke učinkovitosti obdelave. <br>

  Prikaz digitalne oblike podatka:
    
  ![Digitalni podatki](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/Digitalni%20podatki.png)

## 2.1.4. Pretvorba podatkov za delo z računalnikom
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
  
![Kitajske številke](https://github.com/Tonzinio/UVI-FIS/blob/main/Slike/%C5%A1tevilkice.png) <br>

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

# Pretvorba podatkov
# Teorija informacij
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
