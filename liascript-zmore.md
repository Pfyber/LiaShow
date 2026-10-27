<!--
author:   Luka Colarič
email:    luka.colaric@sckr.si
version:  1.0.0
language: sl
narrator: Croatian Male
comment:  Kaj vse zmore LiaScript. Vprašanja, ankete, koda, 3D, simulacije. Vse v eni datoteki markdown.
logo:     img/art_tangram.png
import:   https://raw.githubusercontent.com/LiaTemplates/Pyodide/master/README.md
-->

# Kaj zmore LiaScript

_Šta sve može LiaScript_

Vse, kar boste videli na naslednjih straneh, je napisano v eni sami datoteki markdown. Brez programa, brez strežnika, brez prijave. Datoteka leži na GitHubu, brskalnik iz nje naredi tečaj.

_Sve što ćete videti napisano je u jednoj datoteci markdown. Bez programa, bez servera, bez prijave._

[Poglej izvorno datoteko](https://github.com/Pfyber/LiaShow/blob/main/liascript-zmore.md)

| Poglavje               | Kaj pokaže                                                 |
| ---------------------- | ---------------------------------------------------------- |
| Vprašanja              | 7 vrst kvizov, namigi, rešitve, naključni vrstni red       |
| Ankete                 | 6 vrst anket, rezultati za ves razred                      |
| Matematika in grafi    | formule, kemijske enačbe, diagrami iz besedila, grafi      |
| Koda                   | JavaScript in Python, ki ju dijak ureja in poganja         |
| Živi podatki           | drsniki, vreme v Kranju v živo                             |
| 3D                     | 3D modeli strojev, 3D graf funkcije                        |
| Simulacije             | PhET, Falstad, ChemCollective, MolView, Ventusky           |


## Prosojnice z glasom

_Slajdovi sa glasom_

                    --{{0}}--
To besedilo bere računalnik. V načinu Prosojnice LiaScript sam prebere razlago, medtem ko se na zaslonu po korakih prikazuje vsebina.

Preklopi na način **Prosojnice** (ikona zgoraj desno) in klikni puščico naprej.

_Prebaci na režim Slajdovi i klikni strelicu napred._

                      {{1}}
1. Prvi korak se prikaže ob prvem kliku.

                    --{{1}}--
Prvi korak. Vsak del prosojnice ima lahko svojo razlago.

                      {{2}}
2. Drugi korak ob drugem.

                    --{{2}}--
Drugi korak. Tako lahko dijak sam predela snov, z glasom, v svojem tempu.

                      {{3}}
3. Razlaga je lahko v drugem jeziku kot besedilo. Celoten tečaj lahko prevedete z enim klikom (ikona za jezik).

``` markdown  -Koda
                    --{{1}}--
Prvi korak. Vsak del prosojnice ima lahko svojo razlago.

                      {{1}}
1. Prvi korak se prikaže ob prvem kliku.
```


# Vprašanja

_Pitanja_

Sedem vrst vprašanj. Vsa se preverijo sama, dijak takoj vidi, ali je odgovoril prav. Vsakemu lahko dodate namige, razlago rešitve in omejitev poskusov.

_Sedam vrsta pitanja. Sva se proveravaju sama._


## En ali več pravilnih

_Jedan ili više tačnih_

Koliko je tok pri 12 V in 4 Ω?

<!-- data-randomize -->
[( )] 2 A
[(X)] 3 A
[( )] 48 A
[( )] 0,33 A
[[?]] Ohmov zakon: $I = U / R$
**************************************************************************

$$
I = \frac{U}{R} = \frac{12\ \text{V}}{4\ \Omega} = 3\ \text{A}
$$

**************************************************************************

Kateri materiali so dobri prevodniki?

<!-- data-randomize -->
[[X]] baker
[[ ]] steklo
[[X]] aluminij
[[ ]] guma
[[X]] grafit

``` markdown  -Koda
<!-- data-randomize -->
[( )] 2 A
[(X)] 3 A
[( )] 48 A
[[?]] Ohmov zakon: $I = U / R$
*****************************
Razlaga rešitve, lahko tudi slika ali video.
*****************************
```


## Vpiši odgovor

_Upiši odgovor_

Kako se imenuje enota za upornost?

[[ohm]]
[[?]] Imenuje se po nemškem fiziku Georgu Simonu ...
<script>
  let a = "@input".trim().toLowerCase();
  a == "ohm" || a == "om" || a == "ω"
</script>

Upor 470 Ω je priključen na 9 V. Koliko miliamperov teče skozenj? Dovolj je na eno decimalko natančno.

[[19.1]]
[[?]] Najprej izračunaj v amperih, nato pomnoži s 1000.
<script>
  let x = parseFloat("@input".replace(",", "."));
  Math.abs(x - 9 / 0.470) < 0.1
</script>
**************************************************************************

$I = 9\ \text{V} / 470\ \Omega = 0{,}0191\ \text{A} = 19{,}1\ \text{mA}$

**************************************************************************

Skripta pod vprašanjem sprejme tudi vejico, velike črke in majhna odstopanja.

_Skripta prihvata i zarez, velika slova i mala odstupanja._


## Spustni seznam in vleka

_Padajući meni i prevlačenje_

Kateri element v vezju shranjuje energijo v električnem polju?

[[ upor | (kondenzator) | tuljava | dioda ]]

Povleci pravilno kartico v polje.

Glavno mesto Srbije je

<!-- data-randomize -->
[->[ Niš | (Beograd) | Novi Sad | Kragujevac ]]

``` markdown  -Koda
[[ upor | (kondenzator) | tuljava | dioda ]]

[->[ Niš | (Beograd) | Novi Sad | Kragujevac ]]
```


## Matrika

_Matrica_

Ali je trditev pravilna?

<!-- data-randomize -->
[[pravilno] [napačno]]
[    (X)       ( )    ] Dioda prepušča tok samo v eno smer.
[    ( )       (X)    ] Zaporedno vezani upori imajo manjšo skupno upornost od najmanjšega.
[    (X)       ( )    ] ESP32 ima vgrajen Wi-Fi.
[    ( )       (X)    ] 3D-tiskalnik PLA tiska pri 60 °C.

``` markdown  -Koda
[[pravilno] [napačno]]
[    (X)       ( )    ] Dioda prepušča tok samo v eno smer.
[    ( )       (X)    ] Zaporedno vezani upori ...
```


## Besedilo z vrzelmi

_Tekst sa prazninama_

Vpiši, izberi ali povleci. Vse v enem odstavku.

<!-- data-randomize data-show-partial-solution -->
Ploščica [->[ Arduino ]] je izšla leta [[ 2005 ]]. Danes v delavnici
uporabljamo [[ Raspberry Pi | (ESP32) | Commodore 64 ]], ki ima vgrajen
[->[ (Wi-Fi) | zvočnik ]]. Program zanj pišemo v jeziku [->[ C++ ]].

``` markdown  -Koda
Ploščica [->[ Arduino ]] je izšla leta [[ 2005 ]].
Danes uporabljamo [[ Raspberry Pi | (ESP32) | Commodore 64 ]],
ki ima vgrajen [->[ (Wi-Fi) | zvočnik ]].
```


## Omejeno število poskusov

_Ograničen broj pokušaja_

Po treh napačnih poskusih se pokaže rešitev z razlago.

Katera barvna obročka označujeta upor 47 Ω (prva dva obročka)?

<!-- data-max-trials="3" -->
[( )] rdeča, vijolična
[(X)] rumena, vijolična
[( )] rumena, zelena
[( )] oranžna, siva
**************************************************************************

| Barva     | Številka |
| --------- | -------- |
| rumena    | 4        |
| vijolična | 7        |
| črna      | ×1       |

Rumena (4), vijolična (7), črna (×1) = 47 Ω.

**************************************************************************


# Ankete

_Ankete_

Ankete nimajo pravilnega odgovora. V načinu **Učilnica** (Classroom) vsi v razredu odprejo isti tečaj in rezultati vseh se v živo prikažejo kot graf, anonimno, brez računov in brez strežnika, ki bi shranjeval podatke.

_U režimu Učionica rezultati celog razreda se uživo prikazuju kao grafikon._


## Šest vrst anket

_Šest vrsta anketa_

Kaj si želite naučiti v delavnici?

[[___ ___]]

Koliko let poučujete?

[(1)] manj kot 5
[(2)] 5 do 15
[(3)] več kot 15

Katera orodja ste že uporabljali?

[[3d]] 3D-tiskalnik
[[laser]] laserski rezalnik
[[esp]] ESP32 ali Arduino
[[ai]] umetna inteligenca

Koliko se strinjate?

[(1)(2)(3)(4)(5)]
[               ] Dijaki se bolj učijo, ko kaj izdelajo sami.
[               ] Pri mojem predmetu manjka konkretnih učil.
[               ] Spletna orodja so uporabna pri pouku.

Katero učilo bi naredili prvo?

[[ igra | model | simulacija | kartice ]]

Povleci kartico, ki te najbolj opiše.

[->[ raziskovalec | graditelj | pripovedovalec | organizator ]]

``` markdown  -Koda
[[___ ___]]

[(1)] manj kot 5
[(2)] 5 do 15

[[3d]] 3D-tiskalnik
[[laser]] laserski rezalnik

[(1)(2)(3)(4)(5)]
[               ] Dijaki se bolj učijo, ko kaj izdelajo sami.

[[ igra | model | simulacija | kartice ]]

[->[ raziskovalec | graditelj | pripovedovalec ]]
```


# Matematika in grafi

_Matematika i grafikoni_


## Formule in kemija

_Formule i hemija_

$$
U_C(t) = U_0 \left(1 - e^{-\frac{t}{RC}}\right)
$$

$$
\vec{F} = q\left(\vec{E} + \vec{v} \times \vec{B}\right)
$$

$\ce{2H2 + O2 -> 2H2O}$ · $\ce{CH3COOH <=> CH3COO- + H+}$ · $\ce{^{235}_{92}U + ^{1}_{0}n -> ^{141}_{56}Ba + ^{92}_{36}Kr + 3^{1}_{0}n}$

``` markdown  -Koda
$$
U_C(t) = U_0 \left(1 - e^{-\frac{t}{RC}}\right)
$$

$\ce{2H2 + O2 -> 2H2O}$
```


## Diagram iz besedila

_Dijagram od teksta_

Narisano s tipkovnico, LiaScript iz tega naredi sliko.

``` ascii
  .-----------.      .------------.      .-----------.      .----------.
  |  ideja    |----->| LiaScript  |----->|  GitHub   |----->| dijaki   |
  | (listek)  |      | (markdown) |      |  (objava) |      | (telefon)|
  '-----------'      '------------'      '-----+-----'      '----------'
        ^                                      |
        |              QR koda na učilu        |
        '--------------------------------------'

       +--[ R 1k ]--+--------+
       |            |        |
     (~) 12 V     [C 1µ]   [LED]
       |            |        |
       +------------+--------+
```

_Nacrtano tastaturom, LiaScript od toga pravi sliku._


## Tabela postane graf

_Tabela postaje grafikon_

Polnjenje kondenzatorja: $U_0 = 12\ \text{V}$, $RC = 1\ \text{s}$. Klikni na ikono ob tabeli za preklop med tabelo in grafom.

<!-- data-type="line" data-show data-title="Polnjenje kondenzatorja" data-xlabel="t [s]" data-ylabel="U [V]" -->
| t [s] | napetost na kondenzatorju [V] | napetost na uporu [V] |
| ----- | ------- | ------- |
| 0     | 0       | 12      |
| 0.5   | 4.72    | 7.28    |
| 1     | 7.59    | 4.41    |
| 1.5   | 9.32    | 2.68    |
| 2     | 10.38   | 1.62    |
| 3     | 11.40   | 0.60    |
| 4     | 11.78   | 0.22    |
| 5     | 11.92   | 0.08    |

Navadna tabela v markdownu. Graf nariše LiaScript sam.

_Obična tabela u markdownu. Grafikon crta LiaScript sam._


# Koda

_Kod_

Koda v tečaju ni slika. Dijak jo lahko spremeni in požene, kar v brskalniku.

_Kod u kursu nije slika. Učenik ga menja i pokreće u pregledaču._


## JavaScript

_JavaScript_

Spremeni število in klikni gumb za zagon (levo pod kodo).

``` js
// Pretvorba v dvojiški, osmiški in šestnajstiški sistem
const n = 2026;

const vrstice = [
  "desetiško:     " + n,
  "dvojiško:      " + n.toString(2),
  "osmiško:       " + n.toString(8),
  "šestnajstiško: " + n.toString(16).toUpperCase()
];
vrstice.join("\n")
```
<script>@input</script>


## Python

_Python_

Pravi Python z numpy in matplotlib, ki teče v brskalniku. Klikni gumb za zagon levo pod kodo. Prvi zagon traja do pol minute, ker se Python naloži.

_Pravi Python u pregledaču. Prvo pokretanje traje do pola minuta._

``` python
import numpy as np
import matplotlib.pyplot as plt

g = 9.81    # m/s²
v0 = 20     # začetna hitrost v m/s

fig, ax = plt.subplots()
for kot in [15, 30, 45, 60, 75]:
    a = np.radians(kot)
    t = np.linspace(0, 2 * v0 * np.sin(a) / g, 100)
    ax.plot(v0 * np.cos(a) * t, v0 * np.sin(a) * t - g * t**2 / 2, label=f"{kot}°")

ax.set_xlabel("x [m]")
ax.set_ylabel("y [m]")
ax.set_title("Poševni met pri različnih kotih")
ax.legend()
ax.set_aspect("equal")
plt.show()
```
@Pyodide.eval


# Živi podatki

_Podaci uživo_


## Drsniki

_Klizači_

Premakni drsnika. Tok se izračuna sproti.

Napetost $U$ = <script input="range" min="0" max="24" step="0.5" value="12" default="12" output="U" input-always-active>@input</script> V

Upornost $R$ = <script input="range" min="1" max="100" value="10" default="10" output="R" input-always-active>@input</script> Ω

Tok $I = U / R$ = **<script>(@input(`U`) / @input(`R`)).toFixed(2)</script> A**

Moč $P = U \cdot I$ = **<script>(@input(`U`) * @input(`U`) / @input(`R`)).toFixed(1)</script> W**

Do tekmovanja MAKE&LEARN v Nišu (27. 10. 2027) je še
<script format="relativetime" unit="day" locale="sl">
Math.ceil((new Date("2027-10-27") - new Date()) / 86400000)
</script>.

``` markdown  -Koda
U = <script input="range" min="0" max="24" value="12" output="U" input-always-active>@input</script> V
R = <script input="range" min="1" max="100" value="10" output="R" input-always-active>@input</script> Ω
I = <script>(@input(`U`) / @input(`R`)).toFixed(2)</script> A
```


## Vreme v Kranju v živo

_Vreme u Kranju uživo_

Podatki se naložijo ob odprtju strani s spletne storitve Open-Meteo.

<script run-once="true" style="display: block">
fetch("https://api.open-meteo.com/v1/forecast?latitude=46.24&longitude=14.36&hourly=temperature_2m&forecast_days=5&timezone=Europe%2FLjubljana")
  .then(r => r.json())
  .then(d => {
    let t = "<!-- data-show data-type='line' data-title='Kranj, temperatura v naslednjih 5 dneh' data-ylabel='°C' -->\n"
    t += "| čas | temperatura |\n| --- | --- |\n"
    for (let i = 0; i < d.hourly.time.length; i++) {
      t += "| " + d.hourly.time[i].replace("T", " ") + " | " + d.hourly.temperature_2m[i] + " |\n"
    }
    send.lia("LIASCRIPT: " + t)
  })
  .catch(e => send.lia("Podatkov ni bilo mogoče naložiti."))
"nalagam ..."
</script>

_Podaci se učitavaju sa servisa Open-Meteo pri otvaranju stranice._


# 3D

_3D_


## 3D model motorja

_3D model motora_

Primi z miško in vrti, kolešček približa. Na telefonu z Androidom gumb spodaj desno postavi model v prostor (AR).

_Uhvati mišem i okreći. Na Android telefonu dugme dole desno postavlja model u prostor._

<script run-once="true" style="display: none">
import("https://cdn.jsdelivr.net/npm/@google/model-viewer@4/dist/model-viewer.min.js");
""
</script>

<model-viewer src="https://cdn.jsdelivr.net/gh/KhronosGroup/glTF-Sample-Models@master/2.0/2CylinderEngine/glTF-Binary/2CylinderEngine.glb" alt="Dvovaljni motor" camera-controls auto-rotate ar shadow-intensity="1" exposure="1.1" style="width:100%;height:420px;background:#f5f5f5"></model-viewer>

Dvovaljni motor · _Dvocilindrični motor_

<model-viewer src="https://cdn.jsdelivr.net/gh/KhronosGroup/glTF-Sample-Models@master/2.0/GearboxAssy/glTF-Binary/GearboxAssy.glb" alt="Menjalnik" camera-controls auto-rotate ar shadow-intensity="1" exposure="1.1" style="width:100%;height:420px;background:#f5f5f5"></model-viewer>

Menjalnik · _Menjač_

Modela: Khronos glTF Sample Models. Enako lahko prikažete svoj model iz Tinkercada ali Fusiona, izvožen kot GLB.

``` html  -Koda
<model-viewer src="motor.glb" camera-controls auto-rotate ar></model-viewer>
```


## 3D graf, ki ga spremeniš

_3D grafikon koji menjaš_

Spremeni formulo v prvi vrstici, na primer `Math.sin(x * y / 4)` ali `(x * x - y * y) / 10`, in klikni gumb za zagon (levo pod kodo).

``` js
// Ploskev z = f(x, y)
const f = (x, y) => Math.sin(Math.sqrt(x * x + y * y)) * 2;
const N = 100;   // gostota mreže
const R = 8;     // območje od -R do R

import("https://cdn.jsdelivr.net/npm/three@0.170.0/+esm").then(THREE => {
  const box = document.getElementById("ploskev");
  const id = String(Date.now());
  box.dataset.id = id;
  box.innerHTML = "";
  const w = box.clientWidth || 700, h = 420;

  const scene = new THREE.Scene();
  scene.background = new THREE.Color(0xffffff);
  const cam = new THREE.PerspectiveCamera(45, w / h, 0.1, 200);
  cam.position.set(0, 14, 24);
  cam.lookAt(0, 0, 0);
  const ren = new THREE.WebGLRenderer({ antialias: true });
  ren.setSize(w, h);
  box.appendChild(ren.domElement);

  const geo = new THREE.PlaneGeometry(2 * R, 2 * R, N, N);
  geo.rotateX(-Math.PI / 2);
  const p = geo.attributes.position;
  let lo = Infinity, hi = -Infinity;
  for (let i = 0; i < p.count; i++) {
    const z = f(p.getX(i), p.getZ(i));
    p.setY(i, z);
    lo = Math.min(lo, z);
    hi = Math.max(hi, z);
  }
  const col = [];
  for (let i = 0; i < p.count; i++) {
    const t = (p.getY(i) - lo) / (hi - lo || 1);
    const c = new THREE.Color().setHSL(0.66 - 0.66 * t, 0.75, 0.5);
    col.push(c.r, c.g, c.b);
  }
  geo.setAttribute("color", new THREE.Float32BufferAttribute(col, 3));
  geo.computeVertexNormals();

  const g = new THREE.Group();
  g.add(new THREE.Mesh(geo, new THREE.MeshStandardMaterial({ vertexColors: true, side: THREE.DoubleSide, roughness: 0.6 })));
  g.add(new THREE.LineSegments(new THREE.WireframeGeometry(geo), new THREE.LineBasicMaterial({ color: 0x000000, transparent: true, opacity: 0.06 })));
  g.add(new THREE.AxesHelper(R));
  scene.add(g);
  scene.add(new THREE.AmbientLight(0xffffff, 0.7));
  const sun = new THREE.DirectionalLight(0xffffff, 1.5);
  sun.position.set(5, 10, 7);
  scene.add(sun);

  let drag = false, auto = true, px = 0, py = 0;
  const cv = ren.domElement;
  cv.style.touchAction = "none";
  cv.onpointerdown = e => { drag = true; auto = false; px = e.clientX; py = e.clientY; };
  cv.onpointerup = cv.onpointerleave = () => { drag = false; };
  cv.onpointermove = e => {
    if (!drag) return;
    g.rotation.y += (e.clientX - px) * 0.01;
    g.rotation.x += (e.clientY - py) * 0.01;
    px = e.clientX;
    py = e.clientY;
  };
  cv.onwheel = e => { e.preventDefault(); cam.position.multiplyScalar(e.deltaY > 0 ? 1.1 : 0.9); };

  (function loop() {
    if (box.dataset.id !== id || !box.isConnected) { ren.dispose(); return; }
    if (auto) g.rotation.y += 0.004;
    ren.render(scene, cam);
    requestAnimationFrame(loop);
  })();
});
"Vleci z miško za vrtenje, kolešček za približanje."
```
<script>@input</script>

<div id="ploskev" style="width:100%;height:420px;border:1px solid #ddd"></div>


# Simulacije

_Simulacije_

Kar koli je na spletu, lahko vstavite v tečaj. Dijak ostane na isti strani, ob simulaciji je lahko vprašanje.

_Bilo šta sa veba može da se ubaci u kurs, a pored simulacije pitanje._


## PhET: električni krog

_PhET: strujno kolo_

Sestavi krog z baterijo, žarnico in stikalom. Univerza v Koloradu, brezplačno.

<iframe src="https://phet.colorado.edu/sims/html/circuit-construction-kit-dc/latest/circuit-construction-kit-dc_all.html?locale=sl" width="100%" height="560" style="border:1px solid #ddd" allowfullscreen></iframe>

Kaj se zgodi s svetlostjo, če dodaš drugo žarnico zaporedno?

[( )] sveti močneje
[(X)] obe svetita šibkeje
[( )] nič se ne spremeni


## PhET: poševni met

_PhET: kosi hitac_

Primerjaj s Python grafom iz poglavja Koda.

<iframe src="https://phet.colorado.edu/sims/html/projectile-motion/latest/projectile-motion_all.html?locale=sl" width="100%" height="560" style="border:1px solid #ddd" allowfullscreen></iframe>

Pri katerem kotu je domet največji (brez zračnega upora)?

[[45]]
<script>
  parseFloat("@input") == 45
</script>


## Falstad: usmernik

_Falstad: ispravljač_

Polnovalni usmernik s kondenzatorjem. Tok teče kot rumene pike, levo spodaj se vidi napetost.

<iframe src="https://www.falstad.com/circuit/circuitjs.html?startCircuit=fullrectf.txt" width="100%" height="560" style="border:1px solid #ddd" allowfullscreen></iframe>

Desni klik na element ga uredi. V meniju Circuits je še več sto vezij.

_Desni klik na element ga menja. U meniju Circuits ima još stotine kola._


## ChemCollective: titracija

_ChemCollective: titracija_

Virtualni kemijski laboratorij: standardizacija NaOH z raztopino KHP.

<iframe src="https://chemcollective.org/vlab/101" width="100%" height="900" style="border:1px solid #ddd" sandbox="allow-scripts allow-same-origin allow-forms allow-popups allow-modals" allowfullscreen></iframe>


## MolView: molekula v 3D

_MolView: molekul u 3D_

Kofein. Vrti z miško.

<iframe src="https://embed.molview.org/v1/?mode=balls&cid=2519" width="100%" height="420" style="border:1px solid #ddd" allowfullscreen></iframe>

Celotna aplikacija za risanje molekul: [app.molview.com](https://app.molview.com/)


## Ventusky: oblaki nad nami

_Ventusky: oblaci iznad nas_

Vremenski zemljevid v živo, nad Slovenijo in Srbijo.

<iframe src="https://www.ventusky.com/sl/skupna-pokritost-z-oblaki-zemljevid#p=45.92;16.12;6" width="100%" height="560" style="border:1px solid #ddd" allowfullscreen></iframe>


# Kaj še

_Šta još_

| Možnost              | Kaj pomeni                                                         |
| -------------------- | ------------------------------------------------------------------ |
| Brez povezave        | tečaj se shrani v brskalnik in deluje brez interneta               |
| Prevod               | celoten tečaj se z enim klikom prevede v drug jezik                |
| Učilnica             | rezultati vprašanj in anket celega razreda v živo, skupna koda     |
| Izvoz                | SCORM za Moodle, PDF, spletna stran, aplikacija                    |
| Predloge             | dodatki za Python, vezja, risanje, glasbo, zemljevide              |
| Odprto               | brezplačno, odprta koda, datoteka je vaša                          |

Vse to je napisano v eni datoteki. [Poglej jo](https://github.com/Pfyber/LiaShow/blob/main/liascript-zmore.md), kopiraj in prilagodi svojemu predmetu.

_Sve ovo je jedna datoteka. Kopiraj je i prilagodi svom predmetu._

[Nazaj na delavnico](https://liascript.github.io/course/?https://raw.githubusercontent.com/Pfyber/LiaShow/main/README.md)
