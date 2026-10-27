<!--
author:   Luka Colarič
email:    luka.colaric@sckr.si
version:  1.2.0
language: hr
comment:  MAKE&LEARN. Obuka nastavnika, 28–30. 10. 2026, ŠC Kranj, MladLab.
          Ovaj kurs je ujedno primer: sve što vidite je jedan markdown u LiaScriptu.
logo:     img/art_tangram.png
tags:     MAKE&LEARN, Erasmus+, nastavna sredstva, LiaScript
translation: Slovenščina  README.md
-->

# Od ideje do nastavnog sredstva

**MAKE&LEARN** · obuka nastavnika
28–30. 10. 2026 · ŠC Kranj, MladLab · 9.00–12.30

Za tri dana u paru razvijate jedno nastavno sredstvo za svoj predmet. Programiranje nije potrebno.

[Slovenščina](https://liascript.github.io/course/?https://raw.githubusercontent.com/Pfyber/LiaShow/main/README.md) · **Srpski**

![](img/art_abak.png)<!-- style="width:120px" -->
![](img/art_kocka.png)<!-- style="width:120px" -->


## Tri dana, jedna ideja

``` ascii
                        1. dan                              2. dan             3. dan
 .----------.   .-------------.   .------------------.   .------------.   .---------------.
 |  ideja   |-->| opis        |-->| radna sveska     |-->|  prototip  |-->|  stranica     |
 '----------'   | sredstva    |   | i aplikacija     |   | sa QR kodom|   |  akcioni plan |
                '-------------'   '------------------'   '------------'   '---------------'
```

Svaki korak se nadovezuje na prethodni. Ono što napišete prvog dana, trećeg dana postaje stranica sredstva.

Radite u paru, jedan nastavnik iz Kranja i jedan iz Niša. Isti par sva tri dana.


# 1. dan: od ideje do aplikacije

| Vreme | Blok                            |
| ----- | ------------------------------- |
| 9.00  | Pogodi sredstvo                 |
| 9.15  | Upoznavanje i parovi            |
| 9.30  | Projekat i istorija sredstava   |
| 10.00 | Traženje ideja                  |
| 10.40 | Pauza                           |
| 10.55 | Radna sveska LiaScript          |
| 11.20 | Veb aplikacija sa AI            |
| 11.55 | Objava na GitHub Pages          |
| 12.20 | Završetak                       |

**Potrebno:** laptop, GitHub nalog sa potvrđenom e-adresom, AI alat (ChatGPT, Claude, Gemini ili Copilot).


## Pogodi sredstvo

_15 min · u paru_

Osam stvarnih sredstava iz istorije. Za svako izaberi ime, zatim ih poređaj od najstarijeg do najnovijeg.

![A](img/foto_jevons.jpg)
![B](img/foto_quipu.jpg)
![C](img/foto_planimeter.jpg)
![D](img/foto_llull.jpg)
![E](img/foto_genaille.jpg)
![F](img/foto_chladni.jpg)
![G](img/foto_pantograf.jpg)
![H](img/foto_taumatrop.jpg)

**A** [[ Hladnijeva ploča | Ženaj–Lukasovi štapići | (Dževonsov logički klavir) | Lulov krug | Pantograf | Planimetar | Kipu | Taumatrop ]]

**B** [[ Hladnijeva ploča | Ženaj–Lukasovi štapići | Dževonsov logički klavir | Lulov krug | Pantograf | Planimetar | (Kipu) | Taumatrop ]]

**C** [[ Hladnijeva ploča | Ženaj–Lukasovi štapići | Dževonsov logički klavir | Lulov krug | Pantograf | (Planimetar) | Kipu | Taumatrop ]]

**D** [[ Hladnijeva ploča | Ženaj–Lukasovi štapići | Dževonsov logički klavir | (Lulov krug) | Pantograf | Planimetar | Kipu | Taumatrop ]]

**E** [[ Hladnijeva ploča | (Ženaj–Lukasovi štapići) | Dževonsov logički klavir | Lulov krug | Pantograf | Planimetar | Kipu | Taumatrop ]]

**F** [[ (Hladnijeva ploča) | Ženaj–Lukasovi štapići | Dževonsov logički klavir | Lulov krug | Pantograf | Planimetar | Kipu | Taumatrop ]]

**G** [[ Hladnijeva ploča | Ženaj–Lukasovi štapići | Dževonsov logički klavir | Lulov krug | (Pantograf) | Planimetar | Kipu | Taumatrop ]]

**H** [[ Hladnijeva ploča | Ženaj–Lukasovi štapići | Dževonsov logički klavir | Lulov krug | Pantograf | Planimetar | Kipu | (Taumatrop) ]]

Redosled od najstarijeg do najnovijeg, upiši slova (npr. A B C …):

[[B D G F H C A E]]
<script>
  "@input".toUpperCase().replace(/[^A-H]/g, "") == "BDGFHCAE"
</script>
*****************************************************************

| Slovo | Sredstvo                         | Šta uči                                  | Godina      |
| ----- | -------------------------------- | ---------------------------------------- | ----------- |
| B     | Kipu, čvorovana uzica Inka       | zapis brojeva u dekadnom sistemu         | 15. vek     |
| D     | Lulov krug (Ars magna)           | kombinatorika, kombinovanje pojmova      | oko 1305.   |
| G     | Pantograf                        | uvećanje crteža, sličnost, razmere       | 1603.       |
| F     | Hladnijeva ploča                 | zvučni talasi, stojeći talasi            | 1787.       |
| H     | Taumatrop                        | opažanje slike, početak animacije        | 1825.       |
| C     | Polarni planimetar (Amsler)      | površina nepravilnog lika                | 1854.       |
| A     | Dževonsov logički klavir         | logičko zaključivanje, Bulova logika     | 1869.       |
| E     | Ženaj–Lukasovi štapići           | množenje bez prenosa                     | 1891.       |

*****************************************************************


## Upoznavanje i parovi

_15 min_

1. Ime, škola, predmet.
2. Najbolje nastavno sredstvo kog se sećaš iz škole.
3. Nađi par iz druge škole.


## Projekat MAKE&LEARN

_Erasmus+ KA210-VET, partnerstvo malog obima_

| 2                                      | 10                     | 20+                          | 15                 |
| -------------------------------------- | ---------------------- | ---------------------------- | ------------------ |
| škole                                  | nastavnika             | sredstava                    | meseci             |
| ŠC Kranj, ETŠ Mija Stanimirović (Niš)  | 5 + 5                  | prave učenici sa nastavnicima | 9/2026 – 11/2027   |

Učenici i nastavnici zajedno prave nastavna sredstva za redovnu nastavu, što više od recikliranih materijala.

| Kada                 | Šta                              | Gde        |
| -------------------- | -------------------------------- | ---------- |
| okt 2026             | **ova obuka**                    | Kranj      |
| nov 2026 – jun 2027  | učenici prave sredstva           | obe škole  |
| mar – jun 2027       | veb biblioteka nacrta            | veb        |
| okt 2027             | predstavljanje i takmičenje      | Niš        |

**Dobro sredstvo:** ima jasnu svrhu, funkcioniše, upotrebljivo je u nastavi.


## Istorija nastavnih sredstava

![Abakus](img/art_abak.png)
![Globus](img/art_globus.png)
![Mapa slagalica](img/art_zemljevid.png)
![Frebelovi darovi](img/art_froebel.png)
![Montesori](img/art_montessori.png)
![Kizenerovi štapići](img/art_cuisenaire.png)
![Logo kornjača](img/art_zelva.png)
![Mikrokontroler](img/art_plosca.png)
![AI](img/art_ai.png)

| Godina       | Sredstvo                 | Ideja                                          |
| ------------ | ------------------------ | ---------------------------------------------- |
| antika       | abakus                   | računanje i mesne vrednosti                    |
| 15. vek      | globus                   | Zemlja u ruci                                  |
| oko 1766.    | mapa slagalica           | prva slagalica je bila mapa                    |
| 1837.        | Frebelovi darovi         | kocke, valjci i kugle za prvi vrtić            |
| 1907.        | Montesori pribor         | pribor sam pokazuje grešku                     |
| 1952.        | Kizenerovi štapići       | brojevi kao dužine                             |
| 1967.        | Logo kornjača            | deca programiraju robota koji crta             |
| 2005.        | mikrokontroleri          | Arduino, kasnije micro:bit i ESP32             |
| 2022.        | veštačka inteligencija   | danas sa njom sami pravimo veb sredstvo        |


## Konkretno, slikovno, apstraktno

| Konkretno                        | Slikovno                            | Apstraktno  |
| -------------------------------- | ----------------------------------- | ----------- |
| Uzmem picu i isečem je.          | Nacrtam krug, obojim polovinu.      | Zapišem ½.  |

Najbolja sredstva su jednostavna. Najčešće nedostaje konkretni nivo: nešto što učenik uzme u ruke.

**Gde u vašem predmetu nedostaje?** Tim pitanjem počinjemo traženje ideja.


## Traženje ideja

_40 min · na papiru_

**Rezultat:** jedna ideja, opisana u tri rečenice.

| Korak                | Šta                                                     | Vreme  |
| -------------------- | ------------------------------------------------------- | ------ |
| 1. Problem           | gradivo koje učenici ne razumeju, jedan listić po ideji | 10 min |
| 2. Kako bismo mogli? | problem pretvorite u pitanje                            | 10 min |
| 3. Crazy 8s          | 8 skica za 8 minuta na presavijenom A4                  | 10 min |
| 4. Izbor             | svako sa 3 tačke označi najbolje, izaberete jednu        | 10 min |

Primer: Kako bismo mogli Omov zakon da učinimo opipljivim?

Na kraju izabranu ideju zapišite u tri rečenice: **šta je, šta učenik radi sa njom, šta nauči.** Trebaće vam odmah posle pauze.

[List 1: Traženje ideja (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/01_iskanje_idej.pdf) · [List 2: Crazy 8s (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/02_crazy8s.pdf)


## Pauza

_15 min · nastavljamo u 10.55_


## Radna sveska LiaScript

_25 min_

**Rezultat:** radna sveska za vašu temu.

LiaScript od običnog teksta pravi interaktivni kurs. Besplatno, u pregledaču, bez prijave. I ovaj kurs je napravljen tako.

Ovako je napisan kviz:

``` markdown
Kolika je struja pri 12 V i 4 Ω?

[( )] 2 A
[(X)] 3 A
[( )] 48 A
```

I ovako radi:

Kolika je struja pri 12 V i 4 Ω?

[( )] 2 A
[(X)] 3 A
[( )] 48 A

Oznake ne morate da učite. Piše ih AI, vi proveravate sadržaj. [Šta sve može LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/Pfyber/LiaShow/main/liascript-zmore.md)


### Vežba: sveska sa AI

1. Kopiraj upit (ikona gore desno). Zameni tekst u uglastim zagradama.
2. Odgovor zalepi u [LiveEditor](https://liascript.github.io/LiveEditor/) i isprobaj pitanja.
3. Proveri činjenice. Bar jedno pitanje popravi sam.
4. Ostavi otvoreno. U 11.55 ga lepiš na GitHub.

``` text
Ti si nastavnik i autor materijala u LiaScriptu. Napravi radnu svesku u LiaScriptu.

Predmet i razred: [npr. Elektrotehnika, 2. razred]
Ideja u tri rečenice: [šta je, šta učenik radi, šta nauči]

Struktura:
1. Na vrhu komentar <!-- --> sa redovima author, email, language: hr, comment.
2. "# Naslov" i uvod u tri rečenice.
3. "## Objašnjenje": najviše 10 kratkih rečenica i jedna tabela.
4. "## Aplikacija": samo red [Otvori aplikaciju](LINK).
5. "## Pitanja": 5 pitanja. Koristi oznake LiaScripta:
   jedan odgovor [( )] i [(X)], više odgovora [[ ]] i [[X]],
   upiši odgovor [[odgovor]], izbor [[ a | (b) | c ]].
   Ispod svakog pitanja dodaj nagoveštaj u redu [[?]] i kratko objašnjenje
   između dva reda zvezdica *****.
6. "## Za nastavnika": svrha, kako svesku koristim u razredu (vreme,
   pojedinačno ili u paru) i šta učenik nauči. Svaki deo u dve rečenice.

Piši jednostavno, za učenike, na srpskom (latinica). Ne izmišljaj podatke.
Vrati samo markdown, bez objašnjenja.
```


## Veb aplikacija sa AI

_35 min_

**Rezultat:** veb aplikacija za vaše sredstvo koja radi.

Svako od ovih sredstava je jedna datoteka koju je napisala AI po kratkom opisu.

![RGB izazov](img/shot_rgb.png)
![Phishing detektiv](img/shot_phishing.png)
![ESP32 pinout](img/shot_esp32.png)
![Galerija vrsta alata](img/shot_galerija.png)

**Vrste:** kviz, razvrstavanje, parovi, kartice, memorija, vremenska linija, klik na sliku, simulacija, slaganje rečenica.

### List 3: opis sredstva

AI zna samo ono što joj kažete. Što je opis konkretniji, aplikacija je bolja. Ovaj opis koristite još jednom, trećeg dana za stranicu sredstva.

Kopiraj, popuni i pošalji AI.

``` text
Napravi veb nastavno sredstvo po ovom opisu.

1. Naslov: [ ]
2. Predmet i razred: [ ]
3. Cilj učenja, posle upotrebe učenik zna: [ ]
4. Vrsta: [kviz / razvrstavanje / parovi / kartice / memorija /
   vremenska linija / klik na sliku / simulacija / slaganje rečenica]
5. Šta učenik radi, korak po korak: [ ]
6. Sadržaj, moj spisak pitanja ili pojmova: [ ]
7. Jedan primer, ceo: [ ]
8. Šta učenik vidi kada je tačno i kada je netačno: [ ]
9. Izgled i jezik: [boje, velika dugmad, srpski ili slovenački]

Tehnička pravila:
- Jedna jedina datoteka index.html (HTML, CSS i JS u njoj).
- Bez prijave, bez servera, bez spoljnih podataka.
- Radi na telefonu, računaru i interaktivnoj tabli.
- Sav sadržaj u jednom preglednom spisku na vrhu koda.
- Pre nego što napišeš kod, postavi mi najviše 3 pitanja.

Kada je kod gotov, posebno napiši "Opis za nastavnike" u tri rečenice:
šta aplikacija radi, kako je koristim u razredu, šta učenik pri tome vežba.
```

[List 3 za štampu (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/03_opis_za_ai.pdf)

### Rad sa AI

1. Odgovori na pitanja AI.
2. Isprobaj aplikaciju u pregledu AI. Ako ga nema, sačuvaj kod kao `index.html` i otvori ga dvoklikom.
3. Menjaj jednu stvar odjednom: »Promeni samo X, ostalo ostavi.«
4. Ostavi razgovor otvoren. U 11.55 lepiš kod i opis na GitHub.


## Objava na GitHub Pages

_25 min_

**Rezultat:** aplikacija i sveska na vebu, sve o sredstvu u jednom repozitorijumu.

Sve radite u pregledaču, kopiranjem i lepljenjem.

1. **Repozitorijum.** Na [github.com](https://github.com) klikni **New**. Ime malim slovima, bez razmaka, npr. `omov-zakon`. Izaberi **Public** i **Create repository**.
2. **Aplikacija.** Klikni **creating a new file**. Ime `index.html`, zalepi kod iz AI, **Commit changes**.
3. **Sveska.** **Add file → Create new file**. Ime `README.md`. Zalepi svesku iz LiveEditora. Reč `LINK` zameni adresom aplikacije: `https://korisnik.github.io/omov-zakon/` (umesto `korisnik` tvoje GitHub ime). **Commit changes**.
4. **Opis.** **Add file → Create new file**. Ime `opis.md`. Zalepi popunjen opis sredstva i Opis za nastavnike iz AI. **Commit changes**.
5. **Objava.** **Settings → Pages**: Branch **main**, **/ (root)**, **Save**. Sačekaj 1 do 2 minuta.

**Vaša dva linka**

| Šta            | Adresa                                                                                      |
| -------------- | ------------------------------------------------------------------------------------------- |
| aplikacija     | `https://korisnik.github.io/omov-zakon/`                                                    |
| radna sveska   | `https://liascript.github.io/course/?https://raw.githubusercontent.com/korisnik/omov-zakon/main/README.md` |

| Ako …                   | Uradi                                                       |
| ----------------------- | ----------------------------------------------------------- |
| stranica pokazuje 404   | sačekaj još minut; datoteka se mora zvati tačno `index.html` |
| Pages nije dostupan     | repozitorijum mora biti Public                              |
| sveska pokazuje grešku  | zalepi je u LiveEditor i pogledaj gde se prikaz zaustavlja   |

[List 4: GitHub Pages za štampu (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/04_github_pages.pdf)


## Danas

- [x] ideja u tri rečenice
- [x] radna sveska sa odeljkom Za nastavnika
- [x] aplikacija na vebu
- [x] `opis.md` u repozitorijumu

**Link do aplikacije pošaljite voditelju u Teams.** Sutra ga graviramo na fizičko sredstvo kao QR kod.


# 2. dan: izrada

| Vreme | Blok                       |
| ----- | -------------------------- |
| 9.00  | Juče                       |
| 9.10  | Šta je dobro sredstvo      |
| 9.25  | SCAMPER                    |
| 9.55  | Bezbednost i 3D štampa     |
| 10.35 | Pauza                      |
| 10.50 | Laser i QR kod             |
| 11.30 | Prototip                   |
| 12.15 | Pokaži i ispričaj          |

**Danas:** aplikacija dobija telo, prototip sa QR kodom.

**Fotografišite svaki korak izrade.** Sutra od fotografija nastaje stranica sredstva.


## Juče

_10 min_

Svaki par za 30 sekundi pokazuje aplikaciju na telefonu.


## Šta je dobro sredstvo

_15 min_

1. Samo pokazuje grešku.
2. Jedan pojam.
3. Više čula.
4. Za sve učenike.
5. Od recikliranog.

Šta od toga vaša ideja već ima?

[[1]] samo pokazuje grešku
[[2]] jedan pojam
[[3]] više čula
[[4]] za sve učenike
[[5]] od recikliranog


## SCAMPER

_30 min · na papiru_

**Rezultat:** bolja ideja za fizički deo sredstva.

Izvucite karticu sa klasičnim sredstvom i preradite ga sa sedam pitanja. Zatim izaberite šta uzimate za svoje sredstvo.

| Slovo | Značenje           | Pitanje                                         |
| ----- | ------------------ | ----------------------------------------------- |
| S     | Zameni             | Šta mogu da zamenim: materijal, sadržaj, oblik? |
| C     | Kombinuj           | Sa čim ga povezujem: zvuk, svetlo, QR kod?      |
| A     | Prilagodi          | Kako ga prilagođavam svom predmetu?             |
| M     | Izmeni             | Veće, manje, druge boje, više delova?           |
| P     | Upotrebi drugačije | Za šta drugo bih ga upotrebio?                  |
| E     | Ukloni             | Šta izostavljam da ostane suština?              |
| R     | Obrni              | Šta ako uradim obrnuto?                         |

**Primer, abakus:** kuglice zameni rečima (S), abakus za binarni sistem (C), za ceo razred na zidu (M).

[List 5: SCAMPER (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/05_scamper.pdf)


## Bezbednost

1. Laser ne radi bez nadzora.
2. Usisavanje je uvek uključeno.
3. Mlaznica 3D štampača je vruća, preko 200 °C.
4. Kod vatre: poklopac zatvoren, zaustavi mašinu, pozovi.


## 3D štampa

_40 min_

**Rezultat:** odštampan deo sredstva i STL datoteka.

1. Nađi model na [Printables](https://www.printables.com) ili ga nacrtaj u [Tinkercad](https://www.tinkercad.com) ([video za početnike](https://www.youtube.com/results?search_query=tinkercad+beginner+tutorial)).
2. Iseci (slicer): do 20 minuta štampe.
3. Datoteku donesi do štampača. STL sačuvaj za stranicu sredstva.

**Izazov:** kocka za vaš predmet, na 6 strana reči, simboli ili formule.


## Pauza

_15 min · nastavljamo u 10.50_


## Laser i QR kod

_40 min_

**Rezultat:** gravirani QR kod koji otvara vašu aplikaciju.

1. Otvori šablon za laser u Inkscapeu.
2. **Extensions → Render → Barcode → QR Code**.
3. Zalepi link do aplikacije.
4. QR neka bude najmanje 25 mm, kao gravura.
5. Proveri kod telefonom na ekranu, tek onda seci. SVG sačuvaj za stranicu sredstva.

Rez ide po redu, 3 minuta po paru. U međuvremenu radite prototip.


## Prototip

_45 min · na papiru_

**Rezultat:** prototip koji se drži u ruci, sa QR kodom.

Prvo karton i otpadni materijal, zatim odštampani i isečeni delovi. Ne mora biti gotovo: važno je da ideja radi u ruci.

Na list 6 nacrtajte skicu i zapišite materijale. Trebaće vam sutra.

[List 6: Prototip (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/06_prototip.pdf)


## Pokaži i ispričaj

_15 min_

Svaki par 1 minut: problem, sredstvo, QR kod. Ostali skeniraju.


# 3. dan: biblioteka i plan

| Vreme | Blok                                  |
| ----- | ------------------------------------- |
| 9.00  | Juče                                  |
| 9.10  | Kritički prijatelj                    |
| 9.30  | Veb biblioteka nastavnih sredstava    |
| 10.05 | Pisanje stranice                      |
| 10.40 | Pauza                                 |
| 10.55 | Stranica i akcioni plan               |
| 11.45 | Predaja                               |
| 12.00 | Prezentacije                          |
| 12.20 | Šta sledi, upitnik                    |

**Danas:** od svega što imate nastaje stranica sredstva. Svako piše i plan rada sa učenicima.

**Pripremite:** `opis.md` iz repozitorijuma, odeljak Za nastavnika iz sveske, list 6, fotografije, STL i SVG.


## Kritički prijatelj

_20 min · na papiru_

**Rezultat:** povratna informacija drugog para i jedno poboljšanje.

1. Par predstavlja sredstvo drugom paru, 3 minuta.
2. Drugi par piše po jednu rečenicu u svako polje: **Sviđa mi se … · Voleo bih … · Šta ako …?**
3. Zamenite uloge.
4. Odlučite šta ćete promeniti.

[List 7: Kritički prijatelj (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/07_kriticni_prijatelj.pdf)


## Veb biblioteka nastavnih sredstava

_15 min_

Svako sredstvo dobija svoju stranicu, na slovenačkom, srpskom i engleskom. Sve stranice imaju iste odeljke, pa ih je lako uporediti i ponoviti.

![Primer spiska sredstava](img/shot_index.png)

| Odeljak                       | Sadržaj                                         |
| ----------------------------- | ----------------------------------------------- |
| Svrha                         | koji problem rešava, šta učenik zna posle        |
| Materijali i alati            | šta je potrebno, šta je reciklirano             |
| Izrada                        | koraci sa fotografijama                         |
| Upotreba u nastavi            | kako ga koristite na času                       |
| Kako su učestvovali učenici   | šta su planirali, napravili i isprobali         |
| Nadogradnje                   | ideje za dalje                                  |
| Datoteke                      | STL, SVG, linkovi do aplikacije i sveske        |

Stranica je napisana u markdownu, kao i vaša sveska. Piše je AI iz vaših beleški.


## Pisanje stranice

_35 + 50 min_

**Rezultat:** stranica `index.md`, spremna za biblioteku.

1. Kopiraj upit. Zalepi `opis.md` i Za nastavnika, dopuni podatke koji nedostaju.
2. Pošalji AI. Pročitaj rezultat: ono što nije tačno obriši; dopuni mesta `[nedostaje]`.
3. Rezultat sačuvaj kao `index.md` (u Teamsu: nova datoteka, zalepi).

``` text
Popuni šablon stranice nastavnog sredstva podacima ispod.
Koristi samo ove podatke, ne izmišljaj. Gde podatka nema, napiši [nedostaje].
Kratke rečenice, jednostavan jezik, srpski (latinica).
Kod Izrade numeriši korake i ispod svakog dodaj ![Korak N](slike/korak-N.jpg).
Poslednji red šablona ne menjaj.

OPIS SREDSTVA (opis.md):
[zalepi]

ZA NASTAVNIKA (iz radne sveske):
[zalepi]

DOPUNI:
- Autori i škola: [ ]
- Vreme izrade: [npr. 4 školska časa]
- Materijali, označi reciklirane: [ ]
- Alati: [laser, 3D štampa, karton …]
- Koraci izrade: [1. … 2. … 3. …]
- Kako će učestvovati učenici: [ ]
- Šta menjamo posle kritičkog prijatelja: [ ]
- Link do aplikacije i sveske: [ ]

ŠABLON:
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

## Svrha
## Materijali i alati
## Izrada
## Upotreba u nastavi
## Kako su učestvovali učenici
## Nadogradnje
## Datoteke

---
Nastalo u projektu Erasmus+ MAKE&LEARN, koji sufinansira Evropska unija.
```

Radije prvo na papir? [List 8: Stranica sredstva (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/08_stran_ucila.pdf)


## Pauza

_15 min · nastavljamo u 10.55_


## Akcioni plan

_svaki nastavnik svoj · na papiru_

**Rezultat:** vaš plan kako ćete do juna 2027. napraviti sredstvo sa učenicima. To je obavezan rezultat projekta.

Na listu odgovorite:

1. Predmet, razred, broj učenika i timova.
2. Koje sredstvo će napraviti učenici i šta pri tome nauče.
3. Šta radite svakog meseca od novembra do juna.
4. Materijali, prvo reciklirani.
5. Kada ga isprobavate u razredu.
6. Kako ćete pitati učenike o motivaciji.

List predajete voditelju.

[List 9: Akcioni plan (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/09_akcijski_nacrt.pdf)


## Predaja

_15 min_

U zajedničku fasciklu u Teamsu otpremite fasciklu sa imenom `prezime-sredstvo`:

```
prezime-sredstvo/
   index.md
   slike/
      naslovna.jpg
      korak-1.jpg
   datoteke/
      model.stl
      rezanje.svg
```

- [ ] `index.md` bez oznaka `[nedostaje]`
- [ ] naslovna fotografija i fotografije koraka
- [ ] STL i SVG
- [ ] na dnu stranice red o Erasmus+ MAKE&LEARN
- [ ] akcioni plan predat

[List 10: Predaja (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/10_markdown_oddaja.pdf)


## Prezentacije

_20 min_

Svaki par 1 minut: problem, sredstvo, kako će ga napraviti učenici.


## Šta sledi

| Kada      | Šta                                 |
| --------- | ----------------------------------- |
| nov 2026  | početak sa učenicima                |
| jun 2027  | 10 sredstava po školi               |
| okt 2027  | predstavljanje i takmičenje u Nišu  |

Repozitorijum ostaje vaš. Istim upitima pravite svesku i aplikaciju za bilo koju temu.

**Upitnik o obuci** popunite na papiru, anonimno, i predajte voditelju.

[List 12: Upitnik (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/12_vprasalnik.pdf)


# Prilozi


## Upiti za AI

| Upit            | Kada       | Šta unosite             | Šta dobijate                              |
| --------------- | ---------- | ----------------------- | ----------------------------------------- |
| Radna sveska    | 1. dan     | ideja u tri rečenice    | sveska sa odeljkom Za nastavnika          |
| Aplikacija      | 1. dan     | opis sredstva (list 3)  | `index.html` i Opis za nastavnike         |
| Stranica        | 3. dan     | `opis.md`, Za nastavnika, novi podaci | `index.md` za biblioteku     |

**Pravila za rad sa AI:** konkretan opis, jedna izmena odjednom, činjenice proveri sam, ono što nije tačno obriši.


## 20 klasičnih sredstava za inspiraciju

| #  | Sredstvo                       | Godina     | Šta uči                      | Izrada             |
| -- | ------------------------------ | ---------- | ---------------------------- | ------------------ |
| 1  | Neperovi štapići               | 1617.      | množenje                     | laser              |
| 2  | logaritmar                     | oko 1630.  | logaritmi                    | laser              |
| 3  | geotabla                       | 1950-ih    | likovi, površina, uglovi     | laser, klinovi     |
| 4  | Dinsove kocke                  | 1960-ih    | mesne vrednosti, binarno     | 3D štampa          |
| 5  | Montesori zlatne perle         | poč. 1900. | jedinice, desetice, stotine  | perle, žica        |
| 6  | Soma kocka                     | 1933.      | prostorna predstava          | drvo, 3D štampa    |
| 7  | Hanojska kula                  | 1883.      | rekurzija, algoritmi         | laser, štapovi     |
| 8  | Keplerova tela                 | 1596.      | geometrijska tela            | laser, 3D štampa   |
| 9  | astrolab                       | antika     | zvezde, vreme, uglovi        | laser              |
| 10 | planetarijum (orrery)          | oko 1704.  | kretanje planeta             | 3D štampa, zupčanici |
| 11 | mehanički brojač               | 1642.      | prenos pri sabiranju         | 3D štampa          |
| 12 | camera obscura                 | antika     | optika, oko                  | karton, sočivo     |
| 13 | stereoskop                     | 1838.      | 3D vid                       | laser, sočiva      |
| 14 | zoetrop                        | 1834.      | animacija                    | karton, laser      |
| 15 | laterna magika                 | 17. vek    | projekcija                   | kutija, LED        |
| 16 | Albertijev disk                | 1467.      | šifrovanje                   | laser              |
| 17 | Žakardove bušene kartice       | 1804.      | programiranje                | laser              |
| 18 | Morzeov telegraf               | 1830-ih    | kodiranje signala            | drvo, ESP32        |
| 19 | Vezalijusova anatomija         | 1543.      | slojevi tela                 | laser, papir       |
| 20 | Segenova tabla                 | 1840-ih    | oblici, inkluzija            | laser              |

[List 11 za štampu (PDF)](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/11_20_klasicnih_ucil.pdf)


## Radni listovi

| List | Kada    | PDF                                                                                                      |
| ---- | ------- | -------------------------------------------------------------------------------------------------------- |
| 1    | 1. dan  | [Traženje ideja](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/01_iskanje_idej.pdf)          |
| 2    | 1. dan  | [Crazy 8s](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/02_crazy8s.pdf)                     |
| 3    | 1. dan  | [Opis za AI](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/03_opis_za_ai.pdf)                |
| 4    | 1. dan  | [GitHub Pages](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/04_github_pages.pdf)            |
| 5    | 2. dan  | [SCAMPER](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/05_scamper.pdf)                      |
| 6    | 2. dan  | [Prototip](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/06_prototip.pdf)                    |
| 7    | 3. dan  | [Kritički prijatelj](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/07_kriticni_prijatelj.pdf) |
| 8    | 3. dan  | [Stranica sredstva](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/08_stran_ucila.pdf)        |
| 9    | 3. dan  | [Akcioni plan](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/09_akcijski_nacrt.pdf)          |
| 10   | 3. dan  | [Markdown i predaja](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/10_markdown_oddaja.pdf)   |
| 11   | prilog  | [20 klasičnih sredstava](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/11_20_klasicnih_ucil.pdf) |
| 12   | 3. dan  | [Upitnik](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/12_vprasalnik.pdf)                   |

[Svi listovi u jednom PDF-u](https://github.com/Pfyber/LiaShow/blob/main/delovni-listi/00_vsi_delovni_listi.pdf)


## O kursu

Erasmus+ KA210-VET MAKE&LEARN · ŠC Kranj · ETŠ Mija Stanimirović
Sufinansira Evropska unija.

Ovaj kurs je otvoren (CC BY-SA 4.0). Možete ga kopirati, prevesti i prilagoditi.

**Fotografije u igri Pogodi sredstvo** (Wikimedia Commons)

- A: Nelson, en.wikipedia, [CC BY-SA 2.0](https://commons.wikimedia.org/wiki/File:William_Stanley_Jevons_Logic_Piano.jpg)
- B: Claus Ableiter, [CC BY-SA 3.0](https://commons.wikimedia.org/wiki/File:Inca_Quipu.jpg)
- C: CIA, [javno vlasništvo](https://commons.wikimedia.org/wiki/File:Compensating_Polar_Planimeter_%2830880918835%29.jpg)
- D: Ramon Lul, Ars magna, [javno vlasništvo](https://commons.wikimedia.org/wiki/File:Ramon_Llull_-_Ars_Magna_Fig_1.png)
- E: Worrydream, [javno vlasništvo](https://commons.wikimedia.org/wiki/File:Genaille-Lucas_rulers_full_600.png)
- F: Rodrigo Tetsuo Argenton, eksponat Estes Objethos Atelier, [CC BY-SA 4.0](https://commons.wikimedia.org/wiki/File:Chladni_plate_01.jpg)
- G: Christoph Scheiner, [javno vlasništvo](https://commons.wikimedia.org/wiki/File:Pantograph_by_Christoph_Scheiner_%28crop%29.png)
- H: taumatrop iz 1825, obe strane, [javno vlasništvo](https://commons.wikimedia.org/wiki/File:Taumatropio_fiori_e_vaso,_1825_Frame_1.png)
