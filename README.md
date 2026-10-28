<!--
author:   Luka Colarič
email:    luka.colaric@sckr.si
version:  1.3.0
language: sl
comment:  MAKE&LEARN. Usposabljanje učiteljev, 28.–30. 10. 2026, ŠC Kranj, MladLab.
          Ta tečaj je hkrati primer: vse, kar vidite, je en sam markdown v LiaScriptu.
logo:     img/art_tangram.png
tags:     MAKE&LEARN, Erasmus+, učila, LiaScript
translation: Srpski  README.sr.md
-->

# Od ideje do učila

**MAKE&LEARN** · usposabljanje učiteljev
28.–30. 10. 2026 · ŠC Kranj, MladLab · 9.00–12.30

V treh dneh v paru razvijete eno učilo za svoj predmet. Programiranje ni potrebno.

**Slovenščina** · [Srpski](https://liascript.github.io/course/?https://raw.githubusercontent.com/Pfyber/LiaShow/main/README.sr.md)

![](img/art_abak.png)<!-- style="width:120px" -->
![](img/art_kocka.png)<!-- style="width:120px" -->


# 1. dan: od ideje do aplikacije

| Ura   | Blok                           |
| ----- | ------------------------------ |
| 9.00  | Dobrodošli                     |
| 9.10  | Spoznavanje in pari            |
| 9.25  | Ugani učilo                    |
| 9.40  | Projekt in zgodovina učil      |
| 10.00 | Iskanje idej                   |
| 10.40 | Odmor                          |
| 10.55 | Delovni zvezek                 |
| 11.20 | Spletna aplikacija             |
| 11.55 | Objava na spletu               |
| 12.20 | Zaključek dneva                |


## Dobrodošli

_10 min_

V treh dneh boste v paru naredili eno učilo: od ideje do spletne aplikacije, fizičnega prototipa in objavljene strani. Vsak dan gradi na prejšnjem.

``` ascii
                        1. dan                              2. dan             3. dan
 .----------.   .-------------.   .------------------.   .------------.   .---------------.
 |  ideja   |-->| opis učila  |-->| delovni zvezek   |-->|  prototip  |-->|  stran učila  |
 '----------'   '-------------'   | in aplikacija    |   | s QR kodo  |   | akcijski načrt|
                                  '------------------'   '------------'   '---------------'
```

| Dan | Vprašanje dneva                                 |
| --- | ----------------------------------------------- |
| 1   | Kaj bi dijakom pomagalo razumeti snov?          |
| 2   | Kako to dobi obliko, ki jo primeš v roke?       |
| 3   | Kako to delimo z drugimi in prenesemo v razred? |

**Potrebujete:** prenosnik, GitHub račun s potrjenim e-naslovom, dostop do AI (ChatGPT, Claude, Gemini ali Copilot). Ta tečaj imejte odprt ves čas.


## Spoznavanje in pari

_15 min_

**Rezultat:** par za vse tri dni in predmet, za katerega bosta naredila učilo.

1. **Krog:** ime, šola, predmet in najboljše učilo, ki se ga spomnite iz šole. Ena minuta na osebo.
2. **Par:** poiščite nekoga iz druge šole, s čim bolj sorodnim predmetom.
3. **Predmet:** dogovorita se, za čigav predmet bo učilo, ali poiščita temo, ki je skupna obema.
4. Sedita skupaj in oba odprita ta tečaj.

En par, eno učilo. Akcijski načrt na koncu napiše vsak zase, za svoj razred.


## Ugani učilo

_15 min · v paru_

Ogrevanje. Osem resničnih učil iz zgodovine: vsako je nekdo naredil, da bi razložil eno stvar. Za vsako izberite ime, nato vsa razvrstite od najstarejšega do najnovejšega.

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

Vrstni red od najstarejšega do najnovejšega, vpišite črke (npr. A B C …):

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

**Za pogovor:** katero od osmih bi danes uporabili pri svojem pouku in zakaj?


## Projekt MAKE&LEARN

_10 min_

Delavnica je del projekta Erasmus+. Kar naredite te tri dni, boste z dijaki ponovili v svoji šoli.

| 2                                      | 10                     | 20+                         | 15                 |
| -------------------------------------- | ---------------------- | --------------------------- | ------------------ |
| šoli                                   | učiteljev              | učil                        | mesecev            |
| ŠC Kranj, ETŠ Mija Stanimirović (Niš)  | 5 + 5                  | izdelajo dijaki z učitelji  | 9/2026 – 11/2027   |

| Kdaj                 | Kaj                              | Kje       |
| -------------------- | -------------------------------- | --------- |
| okt 2026             | **to usposabljanje**             | Kranj     |
| nov 2026 – jun 2027  | dijaki izdelajo učila            | obe šoli  |
| mar – jun 2027       | spletna knjižnica načrtov        | splet     |
| okt 2027             | predstavitev in tekmovanje       | Niš       |

**Dobro učilo** ima jasen pedagoški namen, deluje in je uporabno pri pouku. Po teh treh merilih bodo ocenjena tudi učila na tekmovanju.


## Zgodovina učil

_10 min_

Vsako učilo je nastalo, ker nekdo nečesa ni znal razložiti samo z besedami.

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

Dijak snov najlažje razume v treh korakih:

| Konkretno                       | Slikovno                           | Abstraktno  |
| ------------------------------- | ---------------------------------- | ----------- |
| Primem pico in jo razrežem.     | Narišem krog, pobarvam polovico.   | Zapišem ½.  |

Pouk pogosto začne kar pri abstraktnem. Dobro učilo doda manjkajoči korak, najpogosteje konkretnega: nekaj, kar dijak prime v roke.

**Kje v vašem predmetu manjka?** S tem vprašanjem gremo v iskanje idej.


## Iskanje idej

_40 min · na papirju_

**Rezultat:** ena ideja, opisana v treh stavkih.

Dobra ideja redko pride prva. Zato najprej veliko idej, potem izbor.

| Korak               | Kako                                                                          | Čas    |
| ------------------- | ----------------------------------------------------------------------------- | ------ |
| 1. Bolečina         | Vsak sam: snov, ki je dijaki nikoli ne razumejo. Ena na listek, čim več.      | 10 min |
| 2. Kako bi lahko …? | V paru izberita tri listke in vsakega prepišita v vprašanje.                  | 10 min |
| 3. Crazy 8s         | A4 prepognite na 8 polj. Vsako minuto ena skica rešitve. Lepota ni pomembna.  | 10 min |
| 4. Izbira           | Vsak s 3 pikami označi skice, ki so mu všeč. Izbereta eno.                    | 10 min |

Primer: bolečina »dijaki ne razumejo Ohmovega zakona« postane vprašanje »Kako bi lahko Ohmov zakon naredili otipljiv?«

Na koncu izbrano idejo zapišite v treh stavkih: **kaj je, kaj dijak z njo počne, česa se nauči.** Po odmoru jo boste prilepili v AI.

[List 1: Iskanje idej (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/01_iskanje_idej.pdf) · [List 2: Crazy 8s (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/02_crazy8s.pdf)


## Odmor

_15 min · nadaljujemo ob 10.55_

Med odmorom preverite, da se lahko prijavite v GitHub in v AI. Po odmoru ju potrebujete.


## Delovni zvezek

_25 min_

**Rezultat:** delovni zvezek za vašo temo.

Vaše učilo bo imelo tri dele. Danes naredimo oba digitalna, jutri fizičnega.

| Del              | Kaj je                                     | Orodje         |
| ---------------- | ------------------------------------------ | -------------- |
| delovni zvezek   | razlaga in vprašanja za dijaka             | LiaScript      |
| aplikacija       | interaktivna vaja: igra, simulacija, kviz  | AI, HTML       |
| fizično učilo    | kar dijak prime v roke, s QR kodo           | 3D-tisk, laser |

LiaScript iz navadnega besedila naredi interaktivni tečaj. Brezplačno, v brskalniku, brez prijave. Tudi ta tečaj je narejen tako. Tako je napisan kviz:

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

Oznak se ni treba učiti. Napiše jih AI, vi preverite vsebino. [Kaj vse zmore LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/Pfyber/LiaShow/main/liascript-zmore.md)

### Vaja: zvezek z AI

1. Kopirajte poziv (ikona desno zgoraj). Zamenjajte besedilo v oglatih oklepajih.
2. Odgovor prilepite v [LiveEditor](https://liascript.github.io/LiveEditor/) in preizkusite vprašanja.
3. Preverite dejstva. Vsaj eno vprašanje popravite sami.
4. LiveEditor pustite odprt. Ob 11.55 zvezek objavimo.

``` text
Si učitelj in avtor gradiv v LiaScriptu. Naredi delovni zvezek v LiaScriptu.

Predmet in letnik: [npr. Elektrotehnika, 2. letnik]
Ideja v treh stavkih: [kaj je, kaj dijak počne, česa se nauči]

Zgradba:
1. Na vrhu komentar <!-- --> z vrsticami author, email, language: sl, comment.
2. "# Naslov" in uvod v treh stavkih.
3. "## Razlaga": največ 10 kratkih stavkov in ena tabela.
4. "## Aplikacija": samo vrstica [Odpri aplikacijo](POVEZAVA).
5. "## Vprašanja": 5 vprašanj. Uporabi oznake LiaScripta:
   en odgovor [( )] in [(X)], več odgovorov [[ ]] in [[X]],
   vpiši odgovor [[odgovor]], izbira [[ a | (b) | c ]].
   Pod vsako vprašanje dodaj namig v vrstici [[?]] in kratko razlago
   med dvema vrsticama zvezdic *****.
6. "## Za učitelja": namen, kako zvezek uporabim v razredu (čas, posamezno
   ali v paru) in česa se dijak nauči. Vsak del v dveh stavkih.

Piši preprosto, za dijake. Ne izmišljuj podatkov.
Vrni samo markdown, brez razlage.
```

Razdelek **Za učitelja** je začetek vaše dokumentacije. Tretji dan iz njega nastane stran učila.


## Spletna aplikacija

_35 min_

**Rezultat:** delujoča aplikacija za vaše učilo.

Zvezek razlaga, aplikacija pa dijaka spravi v akcijo. Vsako od teh učil je ena sama datoteka, ki jo je napisala AI po kratkem opisu.

![RGB izziv](img/shot_rgb.png)
![Phishing detektiv](img/shot_phishing.png)
![ESP32 pinout](img/shot_esp32.png)
![Galerija vrst orodij](img/shot_galerija.png)

**Vrste:** kviz, razvrščanje, iskanje parov, kartice, spomin, časovnica, klik na sliko, simulacija, sestavljanje stavkov.

### List 3: opis učila

AI zna samo to, kar ji poveste. Bolj ko je opis konkreten, boljša je aplikacija. Najpomembnejša je točka 6: pravi seznam vprašanj ali pojmov, ne samo tema.

Kopirajte, izpolnite in pošljite AI.

``` text
Naredi spletno učilo po tem opisu.

1. Naslov: [ ]
2. Predmet in letnik: [ ]
3. Učni cilj, po uporabi dijak zna: [ ]
4. Vrsta: [kviz / razvrščanje / pari / kartice / spomin / časovnica /
   klik na sliko / simulacija / sestavljanje stavkov]
5. Kaj dijak počne, korak za korakom: [ ]
6. Vsebina, moj seznam vprašanj ali pojmov: [ ]
7. En primer, v celoti izdelan: [ ]
8. Kaj vidi dijak, ko je pravilno in ko napačno: [ ]
9. Videz in jezik: [barve, veliki gumbi, slovensko ali srpsko]

Tehnična pravila:
- Ena sama datoteka index.html (HTML, CSS in JS v njej).
- Brez prijave, brez strežnika, brez zunanjih podatkov.
- Deluje na telefonu, računalniku in interaktivni tabli.
- Vsa vsebina v enem preglednem seznamu na vrhu kode.
- Preden napišeš kodo, mi postavi največ 3 vprašanja.

Ko je koda gotova, posebej napiši "Opis za učitelje" v treh stavkih:
kaj aplikacija dela, kako jo uporabim v razredu, kaj dijak pri tem vadi.
```

[List 3 za tisk (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/03_opis_za_ai.pdf)

### Delo z AI

1. Odgovorite na vprašanja AI.
2. Preizkusite aplikacijo v predogledu AI. Če ga ni, kodo shranite kot `index.html` in jo odprite z dvoklikom.
3. Popravljajte eno stvar naenkrat: »Spremeni samo X, ostalo pusti.«
4. Pogovor pustite odprt. Ob 11.55 kodo in opis objavimo.


## Objava na spletu

_25 min_

**Rezultat:** aplikacija in zvezek na spletu, vse o učilu na enem mestu.

**GitHub** je brezplačen prostor za datoteke na spletu. **GitHub Pages** iz teh datotek naredi spletno stran, ki jo odpre vsak telefon. Za učilo naredite en **repozitorij**, to je mapa s tremi datotekami. Vse delate v brskalniku, s kopiranjem in lepljenjem.

| Datoteka     | Vsebina                    |
| ------------ | -------------------------- |
| `index.html` | aplikacija                 |
| `README.md`  | delovni zvezek             |
| `opis.md`    | opis učila, za tretji dan  |

1. **Repozitorij.** Na [github.com](https://github.com) kliknite **New**. Ime z malimi črkami, brez presledkov, npr. `ohmov-zakon`. Izberite **Public** in **Create repository**.
2. **Aplikacija.** Kliknite **creating a new file**. Ime `index.html`, prilepite kodo iz AI, **Commit changes**.
3. **Zvezek.** **Add file → Create new file**. Ime `README.md`. Prilepite zvezek iz LiveEditorja. Besedo `POVEZAVA` zamenjajte z naslovom aplikacije: `https://uporabnik.github.io/ohmov-zakon/` (namesto `uporabnik` vaše GitHub ime). **Commit changes**.
4. **Opis.** **Add file → Create new file**. Ime `opis.md`. Prilepite izpolnjen opis učila in Opis za učitelje iz AI. **Commit changes**.
5. **Objava.** **Settings → Pages**: Branch **main**, **/ (root)**, **Save**. Počakajte 1 do 2 minuti.

**Vaši povezavi**

| Kaj            | Naslov                                                                                      |
| -------------- | ------------------------------------------------------------------------------------------- |
| aplikacija     | `https://uporabnik.github.io/ohmov-zakon/`                                                  |
| delovni zvezek | `https://liascript.github.io/course/?https://raw.githubusercontent.com/uporabnik/ohmov-zakon/main/README.md` |

| Če …                    | Naredite                                                       |
| ----------------------- | -------------------------------------------------------------- |
| stran kaže 404          | počakajte še minuto; ime datoteke mora biti točno `index.html` |
| Pages ni na voljo       | repozitorij mora biti Public                                   |
| zvezek kaže napako      | prilepite ga v LiveEditor in poglejte, kje se prikaz ustavi    |

[List 4: GitHub Pages za tisk (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/04_github_pages.pdf)


## Zaključek dneva

_10 min_

- [x] ideja v treh stavkih
- [x] delovni zvezek z razdelkom Za učitelja
- [x] aplikacija na spletu
- [x] `opis.md` v repozitoriju

1. **Povezavo do aplikacije pošljite vodji v Teams.** Jutri jo vgraviramo na učilo kot QR kodo.
2. Aplikacijo odprite na partnerjevem telefonu. Deluje?
3. Krog: ena stvar, ki vas je danes presenetila.

**Jutri:** iz aplikacije naredimo predmet, ki ga dijak prime v roke. Razmislite, kakšne oblike bi lahko bil.


# 2. dan: izdelava

| Ura   | Blok                 |
| ----- | -------------------- |
| 9.00  | Včeraj               |
| 9.10  | Kaj je dobro učilo   |
| 9.25  | SCAMPER              |
| 9.55  | Varnost in 3D-tisk   |
| 10.35 | Odmor                |
| 10.50 | Laser in QR koda     |
| 11.30 | Prototip             |
| 12.15 | Pokaži in povej      |

**Danes:** aplikacija dobi telo. Ob koncu imate prototip s QR kodo, ki odpre vašo aplikacijo.

**Fotografirajte vsak korak izdelave.** Jutri iz fotografij nastane stran učila.


## Včeraj

_10 min_

Vsak par v 30 sekundah pokaže aplikacijo na telefonu in pove, kaj je bilo najtežje.


## Kaj je dobro učilo

_15 min_

Pet lastnosti, ki jih imajo učila, ki se obdržijo. Vse smo včeraj videli v zgodovini.

| Lastnost                  | Primer                                           |
| ------------------------- | ------------------------------------------------ |
| 1. Samo pokaže napako     | Montessori: kos se ne prilega, če je narobe      |
| 2. En pojem               | Cuisenairjeve palčke: samo števila kot dolžine   |
| 3. Več čutil              | Chladnijeva plošča: zvok vidiš v pesku           |
| 4. Za vse dijake          | abak: deluje brez branja in brez jezika          |
| 5. Iz recikliranega       | karton, odpadni les, stara elektronika           |

Kaj od tega ima vaša ideja že zdaj?

[[1]] samo pokaže napako
[[2]] en pojem
[[3]] več čutil
[[4]] za vse dijake
[[5]] iz recikliranega

Česar nima, poskusite dodati v naslednjem bloku.


## SCAMPER

_30 min · na papirju_

**Rezultat:** ideja za fizični del učila.

SCAMPER je sedem vprašanj, s katerimi obstoječo stvar spremenimo v novo. Najprej vadimo na tujem učilu, potem uporabimo na svojem.

1. Izvlecite kartico s klasičnim učilom in odgovorite na vseh sedem vprašanj, 10 minut.
2. Enako naredite za svoje učilo, 15 minut.
3. Odločite se, kakšen bo fizični del vašega učila, 5 minut.

| Črka | Pomen             | Vprašanje                                       |
| ---- | ----------------- | ----------------------------------------------- |
| S    | Zamenjaj          | Kaj lahko zamenjam: material, vsebino, obliko?  |
| C    | Združi            | S čim ga povežem: zvok, luč, QR koda?           |
| A    | Prilagodi         | Kako ga prilagodim svojemu predmetu?            |
| M    | Spremeni          | Večje, manjše, druge barve, več kosov?          |
| P    | Uporabi drugače   | Za kaj drugega bi ga uporabil?                  |
| E    | Odstrani          | Kaj izpustim, da ostane bistvo?                 |
| R    | Obrni             | Kaj, če naredim obratno?                        |

**Primer, abak:** kroglice zamenjaj z besedami (S), abak za dvojiški sistem (C), za ves razred na steni (M).

[List 5: SCAMPER (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/05_scamper.pdf)


## Varnost

_5 min_

Preden se dotaknemo strojev:

1. Laser ne dela brez nadzora.
2. Odsesavanje je vedno vklopljeno.
3. Šoba 3D-tiskalnika je vroča, nad 200 °C.
4. Ob ognju: pokrov zaprt, stroj ustavi, pokliči.


## 3D-tisk

_35 min_

**Rezultat:** del učila v tiskalniku in datoteka STL.

3D-tiskalnik po računalniškem modelu sloj za slojem zgradi predmet iz plastike. Tisk traja dolgo, zato morajo biti modeli do odmora v tiskalniku.

1. Najdite model na [Printables](https://www.printables.com) ali ga narišite v [Tinkercad](https://www.tinkercad.com) ([video za začetnike](https://www.youtube.com/results?search_query=tinkercad+beginner+tutorial)).
2. Model naj se natisne v največ 20 minutah. Tisk zažene vodja.
3. STL shranite za stran učila.

**Ne veste, kaj bi tiskali?** Kocka za vaš predmet, na 6 ploskvah besede, simboli ali formule.


## Odmor

_15 min · nadaljujemo ob 10.50_


## Laser in QR koda

_40 min_

**Rezultat:** vgravirana QR koda, ki odpre vašo aplikacijo.

Laserski rezalnik po risbi reže in gravira les, karton ali akril. QR koda poveže fizično učilo z aplikacijo: dijak jo skenira s telefonom.

1. Odprite predlogo za laser v Inkscapu.
2. **Extensions → Render → Barcode → QR Code**.
3. Prilepite povezavo do aplikacije.
4. QR naj bo velik vsaj 25 mm.
5. Kodo preizkusite s telefonom na zaslonu, šele nato režite. SVG shranite za stran učila.

Rez gre po vrsti, 3 minute na par. Kdor čaka, že dela prototip.


## Prototip

_45 min · na papirju_

**Rezultat:** prototip, ki ga lahko primete, s QR kodo.

Prototip ni končni izdelek. Pokaže, ali ideja deluje v roki. Najprej karton in odpadni material, nato dodajte natisnjene in izrezane dele.

Na list 6 narišite skico in zapišite materiale. Jutri ju potrebujete za stran učila.

[List 6: Prototip (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/06_prototip.pdf)


## Pokaži in povej

_15 min_

Vsak par 2 minuti: problem, učilo, QR koda. Ostali skenirajo in preizkusijo.

**Jutri:** prinesite fotografije, datoteki STL in SVG ter list 6.


# 3. dan: knjižnica in načrt

| Ura   | Blok                         |
| ----- | ---------------------------- |
| 9.00  | Včeraj                       |
| 9.10  | Kritični prijatelj           |
| 9.30  | Spletna knjižnica učil       |
| 9.45  | Priprava gradiva             |
| 10.05 | Pisanje strani               |
| 10.40 | Odmor                        |
| 10.55 | Akcijski načrt               |
| 11.45 | Oddaja                       |
| 12.00 | Predstavitve                 |
| 12.20 | Zaključek                    |

**Danes:** iz vsega, kar imate, nastane stran učila. Vsak napiše še načrt, kako bo učilo izdelal z dijaki.


## Včeraj

_10 min_

Prevzemite natisnjene dele in jih dodajte prototipu. Fotografirajte končan prototip.


## Kritični prijatelj

_20 min · na papirju_

**Rezultat:** povratna informacija drugega para in ena izboljšava.

Dva para se združita. Kdor učila ni delal, vidi, česar avtor ne vidi več.

1. Par predstavi učilo, 3 minute. Drugi par ga preizkusi.
2. Drugi par napiše po en stavek v vsako polje: **Všeč mi je … · Želim si … · Kaj če …?**
3. Zamenjajta vlogi.
4. Vsak par se odloči, kaj bo spremenil.

[List 7: Kritični prijatelj (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/07_kriticni_prijatelj.pdf)


## Spletna knjižnica učil

_15 min_

Učila iz projekta bodo zbrana v javni spletni knjižnici, v slovenščini, srbščini in angleščini. Vsako dobi svojo stran z enakimi razdelki, da ga lahko ponovi vsak učitelj.

![Primer kazala učil](img/shot_index.png)

| Razdelek                    | Vsebina                                         |
| --------------------------- | ----------------------------------------------- |
| Namen                       | kateri problem rešuje, kaj dijak zna po uporabi |
| Materiali in orodja         | kaj potrebujete, kaj je reciklirano             |
| Izdelava                    | koraki s fotografijami                          |
| Uporaba pri pouku           | kako ga uporabite v uri                         |
| Kako so sodelovali dijaki   | kaj so načrtovali, izdelali in preizkusili      |
| Nadgradnje                  | ideje za naprej                                 |
| Datoteke                    | STL, SVG, povezavi do aplikacije in zvezka      |


## Priprava gradiva

_20 min_

**Rezultat:** mapa z vsem, kar stran potrebuje.

Na računalniku naredite mapo `priimek-ucilo` in vanjo zložite:

```
priimek-ucilo/
   slike/
      naslovna.jpg
      korak-1.jpg
      korak-2.jpg
   datoteke/
      model.stl
      rezanje.svg
```

1. Izberite eno naslovno fotografijo in eno za vsak korak izdelave.
2. Preimenujte jih: `naslovna.jpg`, `korak-1.jpg`, `korak-2.jpg` …
3. Dodajte STL in SVG.
4. V svojem repozitoriju odprite `opis.md` in ga kopirajte. Potrebovali ga boste v naslednjem bloku.


## Pisanje strani

_35 min_

**Rezultat:** stran `index.md`, pripravljena za knjižnico.

Stran napiše AI iz vaših podatkov. Vaša naloga je preveriti, ali je vse res.

1. Kopirajte poziv. Prilepite `opis.md` in razdelek Za učitelja iz zvezka. Dopolnite seznam DOPOLNI.
2. Pošljite AI. Preberite rezultat: kar ni res, zbrišite; dopolnite mesta `[manjka]`.
3. Rezultat shranite kot `index.md` v mapo `priimek-ucilo`.

``` text
Izpolni predlogo strani učila s spodnjimi podatki.
Uporabi samo te podatke, ne izmišljuj. Kjer podatka ni, napiši [manjka].
Kratki stavki, preprost jezik, slovensko.
Pri Izdelavi oštevilči korake in pod vsakega dodaj ![Korak N](slike/korak-N.jpg).
Zadnje vrstice predloge ne spreminjaj.

OPIS UČILA (opis.md):
[prilepi]

ZA UČITELJA (iz delovnega zvezka):
[prilepi]

DOPOLNI:
- Avtorja in šola: [ ]
- Čas izdelave: [npr. 4 šolske ure]
- Materiali, označi reciklirane: [ ]
- Orodja: [laser, 3D-tisk, karton …]
- Koraki izdelave: [1. … 2. … 3. …]
- Kako bodo sodelovali dijaki: [ ]
- Kaj bomo spremenili po kritičnem prijatelju: [ ]
- Povezava do aplikacije in zvezka: [ ]

PREDLOGA:
---
title: ""
date: 2026-10-30
avtorji: []
sola: ""
predmet: ""
letnik: ""
cas_izdelave: ""
tezavnost: ""
materiali: []
reciklirano: true
orodja: []
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

---
Nastalo v projektu Erasmus+ MAKE&LEARN, ki ga sofinancira Evropska unija.
```

Raje najprej na papir? [List 8: Stran učila (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/08_stran_ucila.pdf)


## Odmor

_15 min · nadaljujemo ob 10.55_


## Akcijski načrt

_50 min · vsak učitelj svojega · na papirju_

**Rezultat:** vaš načrt, kako boste do junija 2027 učilo izdelali z dijaki. To je obvezen rezultat projekta.

Do zdaj ste učilo naredili vi. V projektu ga naredijo dijaki. Načrt pove, kdaj, s kom in kako.

Prvih 15 minut dokončajte stran, nato pišite načrt.

1. Predmet, letnik, število dijakov in ekip.
2. Katero učilo bodo izdelali dijaki in kaj se pri tem naučijo.
3. Kaj delate vsak mesec od novembra do junija.
4. Materiali, najprej reciklirani.
5. Kdaj ga preizkusite v razredu.
6. Kako boste dijake vprašali po motivaciji.

| Mesec    | Primer vrstice                                          |
| -------- | ------------------------------------------------------- |
| november | predstavim projekt, dijaki v ekipah iščejo bolečine     |
| december | Crazy 8s in izbira ideje, prvi prototip iz kartona      |

List oddate vodji.

[List 9: Akcijski načrt (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/09_akcijski_nacrt.pdf)


## Oddaja

_15 min_

V skupno mapo v Teamsu naložite mapo `priimek-ucilo`:

```
priimek-ucilo/
   index.md
   slike/
   datoteke/
```

- [ ] `index.md` brez oznak `[manjka]`
- [ ] naslovna fotografija in fotografije korakov
- [ ] STL in SVG
- [ ] na dnu strani vrstica o Erasmus+ MAKE&LEARN
- [ ] akcijski načrt oddan

[List 10: Oddaja (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/10_markdown_oddaja.pdf)


## Predstavitve

_20 min_

Vsak par 3 minute: problem, učilo v roki, kako ga bodo izdelali dijaki. Nato eno vprašanje iz publike.


## Zaključek

_10 min_

| Kdaj      | Kaj                               |
| --------- | --------------------------------- |
| nov 2026  | začetek z dijaki                  |
| jun 2027  | 10 učil na šolo                   |
| okt 2027  | predstavitev in tekmovanje v Nišu |

Repozitorij ostane vaš. Z enakimi pozivi naredite zvezek in aplikacijo za katero koli temo.

1. **Vprašalnik** izpolnite na papirju, anonimno, in ga oddajte vodji.
2. Skupinska fotografija.

[List 12: Vprašalnik (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/12_vprasalnik.pdf)


# Priloge


## Pozivi za AI

| Poziv           | Kdaj       | Kaj vstavite                         | Kaj dobite                        |
| --------------- | ---------- | ------------------------------------ | --------------------------------- |
| Delovni zvezek  | 1. dan     | ideja v treh stavkih                 | zvezek z razdelkom Za učitelja    |
| Aplikacija      | 1. dan     | opis učila (list 3)                  | `index.html` in Opis za učitelje  |
| Stran učila     | 3. dan     | `opis.md`, Za učitelja, nove podatke | `index.md` za knjižnico           |

**Pravila za delo z AI:** konkreten opis, ena sprememba naenkrat, dejstva preverite sami, kar ni res, zbrišite.


## 20 klasičnih učil za navdih

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

[List 11 za tisk (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/11_20_klasicnih_ucil.pdf)


## Delovni listi

| List | Kdaj    | PDF                                                                                                       |
| ---- | ------- | --------------------------------------------------------------------------------------------------------- |
| 1    | 1. dan  | [Iskanje idej](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/01_iskanje_idej.pdf)             |
| 2    | 1. dan  | [Crazy 8s](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/02_crazy8s.pdf)                      |
| 3    | 1. dan  | [Opis za AI](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/03_opis_za_ai.pdf)                 |
| 4    | 1. dan  | [GitHub Pages](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/04_github_pages.pdf)             |
| 5    | 2. dan  | [SCAMPER](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/05_scamper.pdf)                       |
| 6    | 2. dan  | [Prototip](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/06_prototip.pdf)                     |
| 7    | 3. dan  | [Kritični prijatelj](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/07_kriticni_prijatelj.pdf) |
| 8    | 3. dan  | [Stran učila](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/08_stran_ucila.pdf)               |
| 9    | 3. dan  | [Akcijski načrt](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/09_akcijski_nacrt.pdf)         |
| 10   | 3. dan  | [Markdown in oddaja](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/10_markdown_oddaja.pdf)    |
| 11   | priloga | [20 klasičnih učil](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/11_20_klasicnih_ucil.pdf)   |
| 12   | 3. dan  | [Vprašalnik](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/12_vprasalnik.pdf)                 |

[Vsi listi v enem PDF](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/00_vsi_delovni_listi.pdf)


## O tečaju

Erasmus+ KA210-VET MAKE&LEARN · ŠC Kranj · ETŠ Mija Stanimirović
Sofinancira Evropska unija.

Ta tečaj je odprt (CC BY-SA 4.0). Lahko ga kopirate, prevedete in prilagodite.

**Fotografije pri igri Ugani učilo** (Wikimedia Commons)

- A: Nelson, en.wikipedia, [CC BY-SA 2.0](https://commons.wikimedia.org/wiki/File:William_Stanley_Jevons_Logic_Piano.jpg)
- B: Claus Ableiter, [CC BY-SA 3.0](https://commons.wikimedia.org/wiki/File:Inca_Quipu.jpg)
- C: CIA, [javna last](https://commons.wikimedia.org/wiki/File:Compensating_Polar_Planimeter_%2830880918835%29.jpg)
- D: Ramon Llull, Ars magna, [javna last](https://commons.wikimedia.org/wiki/File:Ramon_Llull_-_Ars_Magna_Fig_1.png)
- E: Worrydream, [javna last](https://commons.wikimedia.org/wiki/File:Genaille-Lucas_rulers_full_600.png)
- F: Rodrigo Tetsuo Argenton, eksponat Estes Objethos Atelier, [CC BY-SA 4.0](https://commons.wikimedia.org/wiki/File:Chladni_plate_01.jpg)
- G: Christoph Scheiner, [javna last](https://commons.wikimedia.org/wiki/File:Pantograph_by_Christoph_Scheiner_%28crop%29.png)
- H: taumatrop iz leta 1825, obe strani, [javna last](https://commons.wikimedia.org/wiki/File:Taumatropio_fiori_e_vaso,_1825_Frame_1.png)
