<!--
author:   Luka Colarič
email:    luka.colaric@sckr.si
version:  1.1.0
language: sl
comment:  MAKE&LEARN. Usposabljanje učiteljev / obuka nastavnika, 28.–30. 10. 2026, ŠC Kranj, MladLab.
          Ta tečaj je hkrati primer: vse, kar vidite, je en sam markdown v LiaScriptu.
logo:     img/art_tangram.png
tags:     MAKE&LEARN, Erasmus+, učila, LiaScript
-->

# Od ideje do učila

_Od ideje do nastavnog sredstva_

**MAKE&LEARN** · usposabljanje učiteljev / obuka nastavnika
28.–30. 10. 2026 · ŠC Kranj, MladLab · vsak dan 9.00–12.30

V treh dneh v paru razvijete eno učilo za svoj predmet: od ideje do spletne aplikacije, fizičnega prototipa in objavljene strani. Predznanje programiranja ni potrebno.

_Za tri dana u paru razvijate jedno nastavno sredstvo za svoj predmet. Predznanje programiranja nije potrebno._

![](img/art_abak.png)<!-- style="width:120px" -->
![](img/art_kocka.png)<!-- style="width:120px" -->


## Tri dni, ena ideja

_Tri dana, jedna ideja_

Vsak korak gradi na prejšnjem. Kar napišete prvi dan, na tretji dan uporabite za stran učila.

_Svaki korak se nadovezuje na prethodni. Ono što napišete prvog dana koristite trećeg dana._

``` ascii
  1. dan                              2. dan                     3. dan
 .-----------.   .---------------.   .------------------.   .-----------------.
 |  ideja    |-->| opis učila    |-->| prototip         |-->| stran učila     |
 | list 1, 2 |   | list 3        |   | s QR kodo        |   | list 8          |
 '-----------'   '-------+-------'   | list 5, 6        |   | akcijski načrt  |
                         |           '--------+---------'   | list 9          |
                         v                    ^             '-----------------'
                .------------------.          |
                | delovni zvezek   |          |
                | + aplikacija     |----------'
                | na GitHubu       |   QR koda vodi do aplikacije
                '------------------'
```

| Dan | Naredimo                                                  | Odnesete                            |
| --- | --------------------------------------------------------- | ----------------------------------- |
| 1   | ideja, delovni zvezek in spletna aplikacija z AI           | aplikacija in zvezek na spletu      |
| 2   | SCAMPER, 3D-tisk, laser, karton                            | prototip s QR kodo do aplikacije    |
| 3   | povratna informacija, stran za knjižnico, načrt za razred  | stran učila in akcijski načrt       |

Delate v paru, en učitelj iz Kranja in eden iz Niša. Isti par vse tri dni.

_Radite u paru, jedan nastavnik iz Kranja i jedan iz Niša. Isti par sva tri dana._


## Projekt MAKE&LEARN

_Erasmus+ KA210-VET, partnerstvo manjšega obsega_

| 2                                      | 10                     | 20+                         | 15                 |
| -------------------------------------- | ---------------------- | --------------------------- | ------------------ |
| šoli · škole                           | učiteljev · nastavnika | učil · sredstava            | mesecev · meseci   |
| ŠC Kranj, ETŠ Mija Stanimirović (Niš)  | 5 + 5                  | izdelajo dijaki z učitelji  | 9/2026 – 11/2027   |

Dijaki in učitelji skupaj izdelajo učila za redni pouk, čim več iz recikliranih materialov, s 3D-tiskom ali CNC, kjer ima to smisel.

_Učenici i nastavnici zajedno prave nastavna sredstva za redovnu nastavu._

| Kdaj                 | Kaj                              | Kje       |
| -------------------- | -------------------------------- | --------- |
| okt 2026             | **to usposabljanje**             | Kranj     |
| nov 2026 – jun 2027  | dijaki izdelajo učila            | obe šoli  |
| mar – jun 2027       | spletna knjižnica načrtov        | splet     |
| okt 2027             | predstavitev in tekmovanje       | Niš       |

**Merila dobrega učila:** jasen pedagoški namen, deluje, uporabno pri pouku.

_Kriterijumi: jasna svrha, funkcioniše, upotrebljivo u nastavi._


# 1. dan: od ideje do aplikacije

_1. dan: od ideje do aplikacije_

| Ura   | Blok                              | List |
| ----- | --------------------------------- | ---- |
| 9.00  | Ugani učilo                       |      |
| 9.15  | Spoznavanje in pari               |      |
| 9.30  | Projekt in zgodovina učil         |      |
| 10.00 | Iskanje idej                      | 1, 2 |
| 10.40 | Odmor                             |      |
| 10.55 | Delovni zvezek LiaScript          |      |
| 11.20 | Spletna aplikacija z AI           | 3    |
| 11.55 | Objava na GitHub Pages            | 4    |
| 12.20 | Zaključek                         |      |

**Danes potrebujete:** prenosnik, GitHub račun s potrjenim e-naslovom, dostop do AI (ChatGPT, Claude, Gemini ali Copilot).

_Danas vam treba: laptop, GitHub nalog sa potvrđenom adresom, pristup AI alatu._


## Ugani učilo

_Pogodi sredstvo · 15 min · v paru_

Osem resničnih učil in pripomočkov iz zgodovine. Za vsako izberi ime, nato vsa razvrsti od najstarejšega do najnovejšega.

![A](img/foto_jevons.jpg)
![B](img/foto_quipu.jpg)
![C](img/foto_planimeter.jpg)
![D](img/foto_llull.jpg)
![E](img/foto_genaille.jpg)
![F](img/foto_chladni.jpg)
![G](img/foto_pantograf.jpg)
![H](img/foto_taumatrop.jpg)

**A** [[ Chladnijeva plošča | Genaille–Lucasove palice | (Jevonsov logični klavir) | Llullov krog | Pantograf | Planimeter | Quipu | Taumatrop ]]

**B** [[ Chladnijeva plošča | Genaille–Lucasove palice | Jevonsov logični klavir | Llullov krog | Pantograf | Planimeter | (Quipu) | Taumatrop ]]

**C** [[ Chladnijeva plošča | Genaille–Lucasove palice | Jevonsov logični klavir | Llullov krog | Pantograf | (Planimeter) | Quipu | Taumatrop ]]

**D** [[ Chladnijeva plošča | Genaille–Lucasove palice | Jevonsov logični klavir | (Llullov krog) | Pantograf | Planimeter | Quipu | Taumatrop ]]

**E** [[ Chladnijeva plošča | (Genaille–Lucasove palice) | Jevonsov logični klavir | Llullov krog | Pantograf | Planimeter | Quipu | Taumatrop ]]

**F** [[ (Chladnijeva plošča) | Genaille–Lucasove palice | Jevonsov logični klavir | Llullov krog | Pantograf | Planimeter | Quipu | Taumatrop ]]

**G** [[ Chladnijeva plošča | Genaille–Lucasove palice | Jevonsov logični klavir | Llullov krog | (Pantograf) | Planimeter | Quipu | Taumatrop ]]

**H** [[ Chladnijeva plošča | Genaille–Lucasove palice | Jevonsov logični klavir | Llullov krog | Pantograf | Planimeter | Quipu | (Taumatrop) ]]

Vrstni red od najstarejšega do najnovejšega, vpiši črke (npr. A B C …):

[[B D G F H C A E]]
<script>
  "@input".toUpperCase().replace(/[^A-H]/g, "") == "BDGFHCAE"
</script>
*****************************************************************

| Črka | Učilo                          | Kaj uči                                  | Leto        |
| ---- | ------------------------------ | ---------------------------------------- | ----------- |
| B    | Quipu, vozlana vrvica Inkov     | zapis števil v desetiškem sistemu        | 15. stol.   |
| D    | Llullov krog (Ars magna)        | kombinatorika, kombiniranje pojmov       | okoli 1305  |
| G    | Pantograf                       | povečava risbe, podobnost, razmerja      | 1603        |
| F    | Chladnijeva plošča              | zvočno valovanje, stojno valovanje       | 1787        |
| H    | Taumatrop                       | zaznavanje slike, začetek animacije      | 1825        |
| C    | Polarni planimeter (Amsler)     | ploščina nepravilnega lika               | 1854        |
| A    | Jevonsov logični klavir         | logično sklepanje, Boolova logika        | 1869        |
| E    | Genaille–Lucasove palice        | množenje brez prenašanja                 | 1891        |

*****************************************************************


## Spoznavanje in pari

_Upoznavanje i parovi · 15 min_

1. Ime, šola, predmet.
   _Ime, škola, predmet._
2. Najboljše učilo, ki se ga spomniš iz šole.
   _Najbolje sredstvo kog se sećaš iz škole._
3. Poišči par iz druge šole.
   _Nađi par iz druge škole._


## Zgodovina učil

_Istorija nastavnih sredstava_

![Abak](img/art_abak.png)
![Globus](img/art_globus.png)
![Zemljevid sestavljanka](img/art_zemljevid.png)
![Froeblovi darovi](img/art_froebel.png)
![Montessori](img/art_montessori.png)
![Cuisenairjeve palčke](img/art_cuisenaire.png)
![Logo želva](img/art_zelva.png)
![Mikrokrmilnik](img/art_plosca.png)
![AI](img/art_ai.png)

| Leto         | Učilo                    | Ideja                                          |
| ------------ | ------------------------ | ---------------------------------------------- |
| antika       | abak                     | računanje in mestne vrednosti                  |
| 15. stol.    | globus                   | Zemlja v roki                                  |
| okoli 1766   | zemljevid sestavljanka   | prva sestavljanka je bila zemljevid             |
| 1837         | Froeblovi darovi         | kocke, valji in krogle za prvi vrtec           |
| 1907         | Montessori pripomočki    | pripomoček sam pokaže napako                   |
| 1952         | Cuisenairjeve palčke     | števila kot dolžine                            |
| 1967         | Logo želva               | otroci programirajo robota, ki riše            |
| 2005         | mikrokrmilniki           | Arduino, kasneje micro:bit in ESP32            |
| 2022         | umetna inteligenca       | danes z njo sami naredimo spletno učilo        |


## Konkretno, slikovno, abstraktno

_Konkretno, slikovno, apstraktno_

| Konkretno                       | Slikovno                           | Abstraktno  |
| ------------------------------- | ---------------------------------- | ----------- |
| Primem pico in jo razrežem.     | Narišem krog, pobarvam polovico.   | Zapišem ½.  |

Najboljša učila so preprosta. Pri večini predmetov manjka prav konkretna stopnja: nekaj, kar dijak prime v roke.

_Najbolja sredstva su jednostavna. Najčešće nedostaje konkretni nivo._

Kje v vašem predmetu manjka konkretna stopnja?

[[___ ___]]


## Iskanje idej

_Traženje ideja · 40 min · list 1 in 2_

**Rezultat:** ena izbrana ideja, opisana v treh stavkih.

_Rezultat: jedna izabrana ideja, opisana u tri rečenice._

| Korak            | Kaj                                                       | Čas    |
| ---------------- | --------------------------------------------------------- | ------ |
| Bolečina         | snov, ki je dijaki nikoli ne razumejo, en listek na idejo | 10 min |
| Kako bi lahko …? | bolečino prepišeta v vprašanje                            | 10 min |
| Crazy 8s         | 8 skic v 8 minutah na prepognjenem A4                     | 10 min |
| Izbira           | partner s 3 pikami označi najboljše, izbereta eno         | 10 min |

### List 1: Iskanje idej

_Radni list 1: Traženje ideja_

Bolečine (snov, ki je dijaki ne razumejo):

[[___ ___ ___ ___]]

Kako bi lahko …? _Kako bismo mogli …?_

[[___]]

Primer: Kako bi lahko Ohmov zakon naredili otipljiv?

Izbrana ideja v treh stavkih: kaj je, kaj dijak z njo počne, česa se nauči.

_Izabrana ideja u tri rečenice: šta je, šta učenik radi, šta nauči._

[[___ ___ ___]]

Te tri stavke boste prilepili v prvi poziv za AI.

_Ove tri rečenice ćete zalepiti u prvi upit za AI._

### List 2: Crazy 8s

_8 ideja za 8 minuta_

Crazy 8s rišete na papir: A4 prepognite na 8 polj, ena minuta na polje. Tukaj zapišite le izbrano skico z besedami.

[[___ ___]]


## Odmor

_Pauza · 15 min · nadaljujemo ob 10.55_


## Delovni zvezek LiaScript

_Radna sveska LiaScript · 25 min_

**Rezultat:** delovni zvezek za vašo temo, shranjen kot `README.md`.

_Rezultat: radna sveska za vašu temu, sačuvana kao `README.md`._

LiaScript iz navadnega besedila naredi interaktivni tečaj s kvizi, slikami in videom. Brezplačno, v brskalniku, brez prijave. Ta tečaj, ki ga gledate, je narejen prav tako.

_LiaScript od običnog teksta pravi interaktivni kurs. Ovaj kurs je napravljen isto tako._

![LiveEditor](img/qr_lia.png)<!-- style="width:160px" -->

[LiveEditor](https://liascript.github.io/LiveEditor/) · [Kaj vse zmore LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/Pfyber/LiaShow/main/liascript-zmore.md)

### Kako je napisan kviz

_Kako je napisan kviz_

``` markdown
Koliko je tok pri 12 V in 4 Ω?

[( )] 2 A
[(X)] 3 A
[( )] 48 A
```

In tako deluje:

Koliko je tok pri 12 V in 4 Ω?

[( )] 2 A
[(X)] 3 A
[( )] 48 A

| Zapis                 | Pomen                       |
| --------------------- | --------------------------- |
| `[( )] [(X)]`         | en pravilen odgovor         |
| `[[ ]] [[X]]`         | več pravilnih odgovorov     |
| `[[odgovor]]`         | vpiši odgovor               |
| `[[___]]`             | prosto besedilo, brez ocene |

Izbira s seznama: `[[ a | (b) | c ]]`

Teh oznak se ni treba učiti na pamet. AI jih napiše namesto vas, vi preverite vsebino.

_Ove oznake ne morate da učite napamet. AI ih piše umesto vas._

### Vaja: delovni zvezek z AI

_Vežba: radna sveska sa AI_

1. Kopiraj poziv spodaj. V oglatih oklepajih zamenjaj besedilo s svojim.
   _Kopiraj upit. Tekst u uglastim zagradama zameni svojim._
2. Odgovor AI prilepi v [LiveEditor](https://liascript.github.io/LiveEditor/) in preizkusi vsa vprašanja.
   _Odgovor zalepi u LiveEditor i isprobaj sva pitanja._
3. Preveri dejstva. Vsaj eno vprašanje popravi sam.
   _Proveri činjenice. Bar jedno pitanje popravi sam._
4. Shrani kot `README.md` (v LiveEditorju: meni, Download).
   _Sačuvaj kao `README.md`._

Poziv lahko napišete tudi v srbščini.

_Upit možete napisati i na srpskom._

``` text
Si učitelj in avtor gradiv v LiaScriptu. Naredi delovni zvezek v LiaScriptu.

Predmet in letnik: [npr. Elektrotehnika, 2. letnik]
Tema: [npr. Ohmov zakon]
Ideja za učilo (list 1): [prilepi tri stavke]

Zgradba:
1. Na vrhu komentar <!-- --> z vrsticami author, email, language: sl, comment.
2. "# Naslov" in uvod v treh stavkih.
3. "## Razlaga": največ 10 kratkih stavkov in ena tabela.
4. "## Aplikacija": samo vrstica [Odpri aplikacijo](POVEZAVA). Povezavo dodam pozneje.
5. "## Vprašanja": 5 vprašanj. Uporabi te oznake LiaScripta:
   en odgovor [( )] in [(X)], več odgovorov [[ ]] in [[X]],
   vpiši odgovor [[odgovor]], izbira [[ a | (b) | c ]].
   Pod vsako vprašanje dodaj namig v vrstici [[?]] in kratko razlago
   med dvema vrsticama zvezdic *****.
6. "## Za učitelja": namen, kako zvezek uporabim v razredu (čas, posamezno
   ali v paru) in česa se dijak nauči. Vsak del v dveh stavkih.

Piši preprosto, za dijake. Ne izmišljuj podatkov.
Vrni samo markdown, brez razlage.
```

Razdelek **Za učitelja** je prvi del vaše dokumentacije. Na 3. dan ga boste uporabili za stran učila.

_Odeljak Za nastavnika je prvi deo vaše dokumentacije._


## Spletna aplikacija z AI

_Veb aplikacija sa AI · 35 min · list 3_

**Rezultat:** delujoča datoteka `index.html` in kratek opis aplikacije za učitelje.

_Rezultat: datoteka `index.html` koja radi i kratak opis za nastavnike._

Vsako od teh učil je ena datoteka HTML, ki jo je napisala AI po kratkem opisu.

![RGB izziv](img/shot_rgb.png)
![Phishing detektiv](img/shot_phishing.png)
![ESP32 pinout](img/shot_esp32.png)
![Galerija vrst orodij](img/shot_galerija.png)

**Vrste orodij:** kviz, razvrščanje, iskanje parov, kartice, spomin, časovnica, klik na sliko, simulacija, sestavljanje stavkov.

### List 3: Opis učila za AI

_Radni list 3: Opis za AI_

Opis je najpomembnejši list delavnice. Iz njega nastane aplikacija, na 3. dan pa stran učila. Pišite konkretno, kot bi razlagali kolegu.

_Opis je najvažniji list radionice. Iz njega nastaje aplikacija, a trećeg dana stranica sredstva._

Naslov · _Naslov_

[[___]]

Predmet in letnik · _Predmet i razred_

[[___]]

Učni cilj: po uporabi dijak zna … · _Cilj učenja_

[[___]]

Vrsta orodja · _Vrsta alata_

[(kviz)] kviz
[(razvrscanje)] razvrščanje
[(pari)] iskanje parov
[(kartice)] kartice
[(spomin)] spomin
[(casovnica)] časovnica
[(slika)] klik na sliko
[(simulacija)] simulacija
[(stavki)] sestavljanje stavkov

Kaj dijak počne, korak za korakom · _Šta učenik radi_

[[___ ___]]

Vsebina: tvoj seznam vprašanj ali pojmov · _Sadržaj_

[[___ ___ ___ ___]]

En primer, v celoti izdelan · _Jedan primer_

[[___ ___]]

Pravilno in napačno: kaj vidi dijak · _Povratna informacija_

[[___]]

Videz in jezik · _Izgled i jezik_

[[___]]

### Poziv za aplikacijo

_Upit za aplikaciju_

Kopiraj poziv, prilepi svoj list 3 in pošlji.

_Kopiraj upit, zalepi svoj list 3 i pošalji._

``` text
Naredi spletno učilo po spodnjem opisu.

[prilepi celoten list 3]

Tehnična pravila:
- Ena sama datoteka index.html (HTML, CSS in JS v njej).
- Brez prijave, brez strežnika, brez zunanjih podatkov.
- Deluje na telefonu, računalniku in interaktivni tabli.
- Vsa vsebina (vprašanja, pojmi) v enem preglednem seznamu na vrhu kode,
  da jo lahko sam spremenim.
- Preden napišeš kodo, mi postavi največ 3 vprašanja.

Ko je koda gotova, posebej napiši še "Opis za učitelje" v treh stavkih:
kaj aplikacija dela, kako jo uporabim v razredu, kaj dijak pri tem vadi.
```

### Delo z AI

_Rad sa AI_

1. Odgovori na vprašanja AI.
   _Odgovori na pitanja AI._
2. Kodo shrani kot `index.html` in jo odpri v brskalniku.
   _Sačuvaj kod kao `index.html` i otvori ga u pregledaču._
3. Popravljaj z eno spremembo naenkrat: »Spremeni samo X, ostalo pusti.«
   _Jedna izmena odjednom: »Promeni samo X, ostalo ostavi.«_
4. Ko deluje, shrani kopijo. Preizkusi še na telefonu.
   _Kad radi, sačuvaj kopiju. Isprobaj i na telefonu._
5. **Opis za učitelje** prepiši na list 4.
   _Opis za nastavnike prepiši na list 4._


## Objava na GitHub Pages

_Objava na GitHub Pages · 25 min · list 4_

**Rezultat:** dve povezavi, ki delujeta na vsakem telefonu: aplikacija in delovni zvezek.

_Rezultat: dva linka koja rade na svakom telefonu: aplikacija i radna sveska._

1. Prijava na [github.com](https://github.com).
2. **New repository**: ime z malimi črkami brez presledkov, npr. `ohmov-zakon`. Izberi **Public**. V polje **Description** prilepi prvi stavek opisa za učitelje.
3. **Add file → Upload files**: `index.html` in `README.md`. Klikni **Commit changes**.
4. **Settings → Pages**: Source **Deploy from a branch**, Branch **main**, mapa **/ (root)**, **Save**.
5. Počakaj 1 do 2 minuti in osveži stran. Na vrhu se pokaže povezava do aplikacije:
   `https://uporabnik.github.io/ohmov-zakon/`

_Isti koraci: novi repozitorijum, otpremi datoteke, Settings → Pages, sačekaj minut-dva._

![github.com](img/qr_github.png)<!-- style="width:140px" -->

**Delovni zvezek kot tečaj**

1. V repozitoriju odpri `README.md`, klikni svinčnik in besedo `POVEZAVA` zamenjaj s povezavo do aplikacije. **Commit changes**.
2. Klikni **Raw** in kopiraj naslov strani.
3. Pred naslov dodaj `https://liascript.github.io/course/?` in odpri.

_U `README.md` zameni reč POVEZAVA linkom aplikacije, klikni Raw i ispred adrese dodaj liascript.github.io/course/?_

| Če …                         | Naredi                                                       |
| ---------------------------- | ------------------------------------------------------------ |
| stran kaže 404               | počakaj še minuto; datoteka se mora imenovati `index.html`    |
| povezave v Pages ni          | preveri, ali je repozitorij Public                            |
| zvezek kaže napako           | v LiveEditorju preveri, kje se prikaz ustavi, in popravi      |

### List 4: Moje povezave

_Radni list 4: Moji linkovi_

Povezava do aplikacije · _Link do aplikacije_

[[___]]

Povezava do delovnega zvezka · _Link do radne sveske_

[[___]]

Opis za učitelje (trije stavki iz odgovora AI) · _Opis za nastavnike_

[[___ ___ ___]]

Kaj bi še dodal? · _Šta bih još dodao?_

[[___ ___]]


## Danes

_Danas_

- [x] ideja iz bolečine
- [x] delovni zvezek z razdelkom za učitelja
- [x] spletna aplikacija na GitHub Pages
- [x] opis za učitelje na listu 4

Povezavo do aplikacije pošljite vodji. **Jutri** iz nje naredimo QR kodo in jo vgraviramo na fizično učilo.

_Link do aplikacije pošaljite voditelju. Sutra od njega pravimo QR kod i graviramo ga na fizičko sredstvo._


# 2. dan: izdelava

_2. dan: izrada_

| Ura   | Blok                 | List |
| ----- | -------------------- | ---- |
| 9.00  | Včeraj               |      |
| 9.10  | Kaj je dobro učilo   |      |
| 9.25  | SCAMPER              | 5    |
| 9.55  | Varnost in 3D-tisk   |      |
| 10.35 | Odmor                |      |
| 10.50 | Laser in QR koda     |      |
| 11.30 | Prototip             | 6    |
| 12.15 | Pokaži in povej      |      |

**Danes:** aplikacija dobi telo. Ob koncu dneva imate prototip, ki ga lahko primete, s QR kodo do aplikacije.

_Danas aplikacija dobija telo: prototip koji se drži u ruci, sa QR kodom do aplikacije._

**Fotografirajte vsak korak izdelave.** Fotografije potrebujete jutri za stran učila.

_Fotografišite svaki korak izrade. Fotografije vam trebaju sutra._


## Včeraj

_Juče · 10 min_

Vsak par v 30 sekundah pokaže svojo aplikacijo na telefonu. Vsak dobi majhen list s QR kodo svoje aplikacije: danes jo vgraviramo.

_Svaki par za 30 sekundi pokazuje aplikaciju. Svako dobija mali list sa svojim QR kodom._


## Kaj je dobro učilo

_Šta je dobro nastavno sredstvo · 15 min_

1. Samo pokaže napako. _Samo pokazuje grešku._
2. En pojem. _Jedan pojam._
3. Več čutil. _Više čula._
4. Za vse dijake. _Za sve učenike._
5. Iz recikliranega. _Od recikliranog._

Katero od petih ima tvoja ideja že zdaj? · _Šta tvoja ideja već ima?_

[[1]] samo pokaže napako
[[2]] en pojem
[[3]] več čutil
[[4]] za vse dijake
[[5]] iz recikliranega


## SCAMPER

_Sedam pitanja za novu ideju · 30 min · list 5_

**Rezultat:** izboljšana ideja za fizični del učila.

_Rezultat: poboljšana ideja za fizički deo sredstva._

| Črka | Slovensko         | Srpski              | Vprašanje                                       |
| ---- | ----------------- | ------------------- | ----------------------------------------------- |
| S    | Zamenjaj          | Zameni              | Kaj lahko zamenjam: material, vsebino, obliko?  |
| C    | Združi            | Kombinuj            | S čim ga povežem: zvok, luč, QR koda?           |
| A    | Prilagodi         | Prilagodi           | Kako ga prilagodim svojemu predmetu?            |
| M    | Spremeni          | Izmeni              | Večje, manjše, druge barve, več kosov?          |
| P    | Uporabi drugače   | Upotrebi drugačije  | Za kaj drugega bi ga uporabil?                  |
| E    | Odstrani          | Ukloni              | Kaj izpustim, da ostane bistvo?                 |
| R    | Obrni             | Obrni               | Kaj, če naredim obratno?                        |

**Primer, abak:** kroglice zamenjaj z besedami (S), abak za dvojiški sistem (C), za ves razred na steni (M).

Izvlecite kartico s klasičnim učilom in ga predelajte s SCAMPER. Na koncu izberite, kar lahko uporabite pri svojem učilu.

_Izvucite karticu sa klasičnim sredstvom i preradite ga pomoću SCAMPER._

### List 5: SCAMPER

_Radni list 5: SCAMPER_

Učilo s kartice · _Sredstvo sa kartice_

[[___]]

S · Zamenjaj

[[___]]

C · Združi

[[___]]

A · Prilagodi

[[___]]

M · Spremeni

[[___]]

P · Uporabi drugače

[[___]]

E · Odstrani

[[___]]

R · Obrni

[[___]]

Kaj od tega vzamem za svoje učilo · _Šta od ovoga uzimam za svoje sredstvo_

[[___ ___]]


## Varnost

_Bezbednost_

1. Laser ne dela brez nadzora. _Laser ne radi bez nadzora._
2. Odsesavanje vedno vklopljeno. _Usisavanje uvek uključeno._
3. Šoba 3D-tiskalnika je vroča, nad 200 °C. _Mlaznica je vruća, preko 200 °C._
4. Ob ognju: pokrov zaprt, stroj ustavi, pokliči. _Kod vatre: poklopac zatvoren, pozovi._


## 3D-tisk

_3D-štampa · 40 min_

1. Najdi model na [Printables](https://www.printables.com) ali ga nariši v [Tinkercad](https://www.tinkercad.com).
2. Razreži: do 20 minut tiska.
3. Datoteko prinesi k tiskalniku.

![Tinkercad](img/qr_tinkercad.png)<!-- style="width:120px" -->
![Printables](img/qr_printables.png)<!-- style="width:120px" -->

**Izziv:** kocka za tvoj predmet, na 6 ploskvah besede, simboli ali formule.

_Izazov: kocka za tvoj predmet, na 6 strana reči, simboli ili formule._

Shrani datoteko STL. Na 3. dan jo priložiš strani učila.

_Sačuvaj STL datoteku. Trećeg dana je prilažeš stranici sredstva._

[Video: Tinkercad za začetnike](https://www.youtube.com/results?search_query=tinkercad+beginner+tutorial)


## Odmor

_Pauza · 15 min · nadaljujemo ob 10.50_


## Laser in QR koda

_Laser i QR kod · 40 min_

**QR koda v Inkscapu**

1. Odpri predlogo za laser.
2. Extensions → Render → Barcode → QR Code.
3. Prilepi povezavo do svoje aplikacije.
4. QR naj bo vsaj 25 mm, kot gravura.

Pred rezanjem kodo preizkusi s telefonom na zaslonu. Rez gre po vrsti, 3 minute na par. Medtem delaš prototip iz kartona.

_Pre rezanja proveri kod telefonom. Rez ide po redu, 3 minuta po paru._

Shrani datoteko SVG za stran učila. · _Sačuvaj SVG datoteku._


## Prototip

_Prototip · 45 min · list 6_

**Rezultat:** prototip, ki ga lahko primete, s QR kodo do aplikacije.

_Rezultat: prototip koji se drži u ruci, sa QR kodom do aplikacije._

Najprej karton in odpadni material, nato natisnjeni in izrezani deli. Ni treba dokončati: šteje, da ideja deluje v roki.

_Prvo karton i otpadni materijal, zatim odštampani i isečeni delovi._

### List 6: Moj prototip

_Radni list 6: Moj prototip_

Ime učila · _Ime sredstva_

[[___]]

Skico narišeš na papir. Tukaj zapiši materiale in ali so reciklirani.

[[___ ___ ___]]

Orodja · _Alati_

[[karton]] karton
[[les]] odpadni les / otpadno drvo
[[laser]] laser
[[3d]] 3D-tisk / 3D-štampa
[[elektronika]] elektronika (ESP32)

QR koda vodi do · _QR kod vodi do_

[[___]]


## Pokaži in povej

_Pokaži i ispričaj · 15 min_

Vsak par 1 minuto: problem, učilo, QR koda. Ostali skenirajo.

_Svaki par 1 minut: problem, sredstvo, QR kod._


# 3. dan: knjižnica in načrt

_3. dan: biblioteka i plan_

| Ura   | Blok                             | List  |
| ----- | -------------------------------- | ----- |
| 9.00  | Včeraj                           |       |
| 9.10  | Kritični prijatelj               | 7     |
| 9.30  | Knjižnica, markdown, predloga    |       |
| 10.05 | Pisanje strani                   | 8     |
| 10.40 | Odmor                            |       |
| 10.55 | Stran in akcijski načrt          | 8, 9  |
| 11.45 | Oddaja                           | 10    |
| 12.00 | Predstavitve                     |       |
| 12.20 | Kaj sledi, vprašalnik            | 12    |

**Danes:** iz vsega, kar ste napisali v dveh dneh, nastane stran učila. Vsak učitelj napiše še načrt, kako bo učilo izdelal z dijaki.

_Danas od svega što ste napisali nastaje stranica sredstva. Svaki nastavnik piše i plan rada sa učenicima._

Pripravite: liste 1 do 7, razdelek **Za učitelja** iz delovnega zvezka, fotografije, datoteki STL in SVG.

_Pripremite: listove 1 do 7, odeljak Za nastavnika, fotografije, STL i SVG datoteke._


## Kritični prijatelj

_Kritički prijatelj · 20 min · list 7_

Par predstavi učilo drugemu paru v 3 minutah. Drugi par napiše po en stavek v vsako polje. Nato zamenjajta vlogi.

_Par predstavlja sredstvo drugom paru za 3 minuta. Drugi par piše po jednu rečenicu u svako polje._

### List 7: Kritični prijatelj

Všeč mi je … · _Sviđa mi se …_

[[___ ___]]

Želim si … · _Voleo bih …_

[[___ ___]]

Kaj če …? · _Šta ako …?_

[[___ ___]]

Kaj bova spremenila · _Šta ćemo promeniti_

[[___ ___]]


## Spletna knjižnica učil

_Veb biblioteka nastavnih sredstava · 15 min_

Ena stran na učilo: namen, materiali, koraki, uporaba pri pouku, datoteke. Slovensko, srbsko, angleško. Objavi ŠC Kranj.

_Jedna stranica po sredstvu. Na slovenačkom, srpskom i engleskom. Objavljuje ŠC Kranj._

![Primer kazala učil](img/shot_index.png)

Stran je napisana v markdownu, enako kot vaš delovni zvezek:

| Napišeš                      | Dobiš               |
| ---------------------------- | ------------------- |
| `# Naslov`                   | velik naslov        |
| `## Podnaslov`               | manjši naslov       |
| `- alineja`                  | seznam              |
| `1. korak`                   | oštevilčen seznam   |
| `**krepko**`                 | **krepko**          |
| `![opis](slike/1.jpg)`       | slika               |
| `[besedilo](povezava)`       | povezava            |


## Predloga za stran učila

_Šablon za stranu sredstva_

Predloga `index.md` je v skupni mapi v Teamsu. Vsak razdelek ima svoj vir.

_Šablon `index.md` je u zajedničkoj fascikli u Teamsu. Svaki odeljak ima svoj izvor._

| Razdelek strani             | Vir                                          |
| --------------------------- | -------------------------------------------- |
| naslov, predmet, letnik     | list 3                                       |
| Namen                       | list 3 (učni cilj), Za učitelja              |
| Materiali in orodja         | list 6                                       |
| Izdelava                    | fotografije in list 8                        |
| Uporaba pri pouku           | Za učitelja, opis za učitelje z lista 4      |
| Kako so sodelovali dijaki   | list 8, pozneje akcijski načrt               |
| Nadgradnje                  | list 7 (Kaj če …?)                           |
| Datoteke                    | STL, SVG, povezavi z lista 4                 |

``` markdown
---
title: "Ime učila"
date: 2026-10-30
avtorji: ["Ime Priimek", "Ime Priimek"]
sola: "ŠC Kranj / ETŠ Mija Stanimirović"
predmet: "Elektrotehnika"
letnik: "2. letnik"
materiali: ["karton", "odpadni les"]
reciklirano: true
orodja: ["laser", "3D-tisk"]
naslovna: "slike/naslovna.jpg"
licenca: "CC BY-SA 4.0"
---

## Namen
## Materiali in orodja
## Izdelava
## Uporaba pri pouku
## Kako so sodelovali dijaki
## Nadgradnje
## Datoteke

Nastalo v projektu Erasmus+ MAKE&LEARN, ki ga sofinancira Evropska unija.
```


## Pisanje strani

_Pisanje strane · 35 + 50 min · list 8_

**Rezultat:** izpolnjena predloga `index.md` s fotografijami.

_Rezultat: popunjen šablon `index.md` sa fotografijama._

1. Izpolni list 8: zberi zapiske z listov in iz zvezka.
   _Popuni list 8 iz svojih beleški._
2. Izberi fotografije: ena naslovna, ena za vsak korak.
   _Izaberi fotografije: jedna naslovna, jedna za svaki korak._
3. List 8 in predlogo prilepi v AI s pozivom spodaj.
   _List 8 i šablon zalepi u AI sa upitom ispod._
4. Preberi rezultat. Vse, kar je AI dodal in ni res, zbriši. Dopolni mesta, označena z `[manjka]`.
   _Pročitaj rezultat. Sve što nije tačno obriši. Dopuni mesta označena sa `[manjka]`._

``` text
Izpolni spodnjo predlogo strani učila z mojimi zapiski.

Pravila:
- Uporabi samo podatke iz zapiskov. Ne izmišljuj.
- Kjer podatka ni, napiši [manjka].
- Kratki stavki, preprost jezik, slovensko.
- Pri Izdelavi oštevilči korake in pod vsak korak dodaj
  ![Korak N](slike/korak-N.jpg).
- Zadnje vrstice predloge ne spreminjaj.

Zapiski:
[prilepi list 8]

Predloga:
[prilepi predlogo index.md]
```

### List 8: Stran učila, osnutek

_Radni list 8: Stranica sredstva, nacrt_

Naslov učila · _Naziv sredstva_

[[___]]

Predmet, letnik, čas izdelave · _Predmet, razred, vreme izrade_

[[___]]

Namen · _Svrha_

[[___ ___]]

Materiali in orodja (označi reciklirano) · _Materijali i alati_

[[___ ___]]

Izdelava po korakih · _Izrada korak po korak_

[[___ ___ ___ ___]]

Uporaba pri pouku · _Upotreba u nastavi_

[[___ ___]]

Kako so sodelovali dijaki · _Kako su učestvovali učenici_

[[___ ___]]

Nadgradnje · _Nadogradnje_

[[___]]


## Odmor

_Pauza · 15 min · nadaljujemo ob 10.55_


## Akcijski načrt

_Akcioni plan · list 9 · vsak učitelj svojega_

**Rezultat:** načrt, kako boste učilo do junija 2027 izdelali z dijaki. To je obvezen rezultat projekta.

_Rezultat: plan kako ćete do juna 2027. napraviti sredstvo sa učenicima. Obavezan rezultat projekta._

Predmet in letnik · _Predmet i razred_

[[___]]

Število dijakov in ekip · _Broj učenika i timova_

[[___]]

Učilo, ki ga bodo izdelali dijaki · _Sredstvo koje će napraviti učenici_

[[___ ___]]

Učni cilj · _Cilj učenja_

[[___]]

| Mesec      | Kaj delamo · _Šta radimo_ |
| ---------- | ------------------------- |
| november   |                           |
| december   |                           |
| januar     |                           |
| februar    |                           |
| marec      |                           |
| april      |                           |
| maj        |                           |
| junij      |                           |

Časovnica po mesecih · _Vremenski plan_

[[___ ___ ___ ___ ___ ___ ___ ___]]

Materiali, najprej reciklirani · _Materijali_

[[___ ___]]

Kdaj preizkus v razredu · _Kada test u razredu_

[[___]]

Kako bom dijake vprašal po motivaciji · _Kako ću pitati učenike o motivaciji_

[[___ ___]]


## Oddaja

_Predaja · 15 min · list 10_

```
priimek-ucilo/
   index.md
   slike/
      naslovna.jpg
      korak-1.jpg
   datoteke/
      model.stl
      rezanje.svg
```

- [ ] mapa z imenom `priimek-ucilo`
- [ ] v njej `index.md`, brez oznak `[manjka]`
- [ ] mapa `slike/` z naslovno fotografijo in koraki
- [ ] mapa `datoteke/` (STL, SVG)
- [ ] na dnu strani vrstica o projektu Erasmus+ MAKE&LEARN
- [ ] naloženo v skupno mapo v Teamsu
- [ ] akcijski načrt oddan
- [ ] vprašalnik izpolnjen


## Predstavitve

_Prezentacije · 20 min_

Vsak par 1 minuto: problem, učilo, kako ga bodo izdelali dijaki.

_Svaki par 1 minut: problem, sredstvo, kako će ga napraviti učenici._


## Kaj sledi

_Šta sledi_

| Kdaj      | Kaj                              |
| --------- | -------------------------------- |
| nov 2026  | začetek z dijaki                 |
| jun 2027  | 10 učil na šolo                  |
| okt 2027  | predstavitev in tekmovanje v Nišu |

Vaš delovni zvezek in aplikacija ostaneta na GitHubu. Z enakimi pozivi lahko naredite gradivo za katero koli drugo temo.

_Vaša radna sveska i aplikacija ostaju na GitHubu. Istim upitima možete napraviti materijal za bilo koju temu._


## Vprašalnik o usposabljanju

_Upitnik o obuci · list 12 · anonimno_

1 = sploh se ne strinjam, 5 = popolnoma se strinjam
_1 = uopšte se ne slažem, 5 = potpuno se slažem_

Vsebina usposabljanja je bila jasna. · _Sadržaj obuke je bio jasan._

[(1)] 1
[(2)] 2
[(3)] 3
[(4)] 4
[(5)] 5

Usposabljanje je uporabno za moj pouk. · _Obuka je korisna za moju nastavu._

[(1)] 1
[(2)] 2
[(3)] 3
[(4)] 4
[(5)] 5

Metodo so-ustvarjanja znam uporabiti z dijaki. · _Znam da primenim kokreaciju._

[(1)] 1
[(2)] 2
[(3)] 3
[(4)] 4
[(5)] 5

Vsebina je povezana z mojim predmetom. · _Sadržaj je povezan sa mojim predmetom._

[(1)] 1
[(2)] 2
[(3)] 3
[(4)] 4
[(5)] 5

Kaj je bilo najbolj koristno? · _Šta je bilo najkorisnije?_

[[___ ___]]

Kaj bi spremenili? · _Šta biste promenili?_

[[___ ___]]


# Priloge

_Prilozi_


## Vsi pozivi za AI

_Svi upiti za AI_

Trije pozivi iz delavnice na enem mestu. Uporabite jih lahko za katero koli temo.

_Tri upita iz radionice na jednom mestu._

| Poziv                  | Kdaj      | Vhod                  | Izhod                                  |
| ---------------------- | --------- | --------------------- | -------------------------------------- |
| Delovni zvezek         | 1. dan    | list 1                | `README.md` z razdelkom Za učitelja    |
| Aplikacija             | 1. dan    | list 3                | `index.html` in opis za učitelje       |
| Stran učila            | 3. dan    | list 8, predloga      | izpolnjen `index.md`                   |

Pozivi so v poglavjih [Delovni zvezek LiaScript](#Delovni-zvezek-LiaScript), [Spletna aplikacija z AI](#Spletna-aplikacija-z-AI) in [Pisanje strani](#Pisanje-strani).

**Pravila za delo z AI**

1. Daj AI konkreten opis, ne samo teme.
2. Ena sprememba naenkrat.
3. Dejstva vedno preveri sam.
4. Kar ni res, zbriši.

_Konkretan opis. Jedna izmena odjednom. Činjenice proveri sam. Ono što nije tačno obriši._


## 20 klasičnih učil za navdih

_20 klasičnih sredstava za inspiraciju_

| #  | Učilo                          | Leto       | Kaj uči                      | Izdelava          |
| -- | ------------------------------ | ---------- | ---------------------------- | ----------------- |
| 1  | Napierjeve palice              | 1617       | množenje                     | laser             |
| 2  | logaritemsko računalo          | ok. 1630   | logaritmi                    | laser             |
| 3  | geoplošča                      | 1950-a     | liki, ploščina, koti         | laser, zatiči     |
| 4  | Dienesove kocke                | 1960-a     | mestne vrednosti, dvojiško   | 3D-tisk           |
| 5  | Montessori zlate perle         | zač. 1900  | enice, desetice, stotice     | perle, žica       |
| 6  | Soma kocka                     | 1933       | prostorska predstava         | les, 3D-tisk      |
| 7  | Hanojski stolp                 | 1883       | rekurzija, algoritmi         | laser, palice     |
| 8  | Keplerjeva telesa              | 1596       | geometrijska telesa          | laser, 3D-tisk    |
| 9  | astrolab                       | antika     | zvezde, čas, koti            | laser             |
| 10 | planetarij (orrery)            | ok. 1704   | gibanje planetov             | 3D-tisk, zobniki  |
| 11 | mehanski števec                | 1642       | prenos pri seštevanju        | 3D-tisk           |
| 12 | camera obscura                 | antika     | optika, oko                  | karton, leča      |
| 13 | stereoskop                     | 1838       | 3D vid                       | laser, leči       |
| 14 | zoetrop                        | 1834       | animacija                    | karton, laser     |
| 15 | laterna magika                 | 17. stol.  | projekcija                   | škatla, LED       |
| 16 | Albertijev disk                | 1467       | šifriranje                   | laser             |
| 17 | Jacquardove luknjane kartice   | 1804       | programiranje                | laser             |
| 18 | Morsejev telegraf              | 1830-a     | kodiranje signalov           | les, ESP32        |
| 19 | Vesalijeva anatomija           | 1543       | plasti telesa                | laser, papir      |
| 20 | Séguinova deska                | 1840-a     | oblike, vključevanje         | laser             |


## Natisljivi delovni listi

_Radni listovi za štampu_

Vsi delovni listi so tudi v PDF za tisk, v mapi `delovni-listi/`.

[Vsi delovni listi v enem PDF](delovni-listi/00_vsi_delovni_listi.pdf)


## O tečaju

Erasmus+ KA210-VET MAKE&LEARN · ŠC Kranj · ETŠ Mija Stanimirović
Sofinancira Evropska unija. / Sufinansira Evropska unija.

Ta tečaj je odprt (CC BY-SA 4.0). Lahko ga kopirate, prevedete in prilagodite.

**Fotografije pri igri Ugani učilo** · _Fotografije u igri Pogodi sredstvo_ (Wikimedia Commons)

- A: Nelson, en.wikipedia, [CC BY-SA 2.0](https://commons.wikimedia.org/wiki/File:William_Stanley_Jevons_Logic_Piano.jpg)
- B: Claus Ableiter, [CC BY-SA 3.0](https://commons.wikimedia.org/wiki/File:Inca_Quipu.jpg)
- C: CIA, [javna last](https://commons.wikimedia.org/wiki/File:Compensating_Polar_Planimeter_%2830880918835%29.jpg)
- D: Ramon Llull, Ars magna, [javna last](https://commons.wikimedia.org/wiki/File:Ramon_Llull_-_Ars_Magna_Fig_1.png)
- E: Worrydream, [javna last](https://commons.wikimedia.org/wiki/File:Genaille-Lucas_rulers_full_600.png)
- F: Rodrigo Tetsuo Argenton, eksponat Estes Objethos Atelier, [CC BY-SA 4.0](https://commons.wikimedia.org/wiki/File:Chladni_plate_01.jpg)
- G: Christoph Scheiner, [javna last](https://commons.wikimedia.org/wiki/File:Pantograph_by_Christoph_Scheiner_%28crop%29.png)
- H: taumatrop iz leta 1825, obe strani, [javna last](https://commons.wikimedia.org/wiki/File:Taumatropio_fiori_e_vaso,_1825_Frame_1.png)
