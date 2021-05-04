- 👋 Hi, I’m @alland11
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
alland11/alland11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!--
And here is my Pirple assignement 12

Language: Estonian
Kuigi Javascript ei ole "puhas" objektorienteeritud programmeerimiskeel, on selles siiski teatud konstruktsioonid,
mis võimaldavad objektorienteeritust kasutada. 

Millal üldse OOP lähenemist kasutada (võrreldes sündmuspõhise või protseduurilise lähenemisviisiga)? 
Peamiselt siis, kui OOP eeliseid saab "ära kasutada"
1) Projekti kallal on palju programmeerijaid ning "kõik ei pea kõigest aru saama". Objektide sisse saab keerukust "ära peita".
2) Kui koodi on hea/vajalik korduvkasutada ja jagada. Saab ära kasutada OOP pärimist ja/või prototüüpe.
3) Kui projekt kestab pikka aega ja pidevalt ajas muutub. OOP võimaldab "isoleerida" koodiosi nii, et muudatused ühes osas ei riku (kogemata) ära teisi.
4) Kui projekt on pigem suur/väga suur, siis aitab OOP tõenäoliselt koodi ja selle muudatusi paremini hallata
5) Üks tähelepanek - kui koodis/süsteemis on juba loomupäraselt palju "olekuga" asju (objekte :) - nagu näitekls GUIs - nupud, näidikud jmt kasutaja interaktsiooni nõudvad asjad)
siis võiks seal kaaluda OOP lähenemist

Üldine nõuanne on aga see: kui asi tõotab minna piisavalt suureks ja keerukaks, et ära kasutada (ja neist kasu saada, mitte üksnes "kasutada") OOP peamisi omadusi
1) encapsulation 2) pärimine 3) abstraktsioon ja 4) polümorfism, - siis oleks mõistlik OOP ka kasutusele võtta.

Näitena (triviaalne, aga siiski) võiks OOP puhul kõne alla tulla veebipood/e-pood.

Peamised kasutuslood:
1) Kasutajana tahan ma e-poest kaupu sirvida, nähes nende pilte, omadusi, hinda, saadavust
2) Kasutajana tahan ma e-poest kaupu oma ostukorvi lisada ja eemaldada
3) Kasutajana tahan ma valida kauba kättetoimetuse viisi, kauba eest maksta
3) Kasutajana tahan ma saada "püsikasutajaks", et iga kord oma andmeid ei peaks sisestama
4) Kasutajana tahan ma oma püsikasutaja andmeid muuta või konto kustutada (DGPR!)
5) ... Edasi võib mõelda veel muid võimalikke kasutuslugusid nagu ostuajaloo ja tellimuste täitmise vaatamine, kauba tagastamine, kauba kohta hinnangu andmine, jne, aga praeguseks siin aitab.

Peamised objektid ning nende atribuudid ja meetodid
1) Kasutaja
  1.1. Kasutajanimi (= e-posti aadress) ja nimi
  1.2. Parool
  1.3. Makseviisid
  1.3. Tarneaadressid
  1.4. Ostuajalugu (koosneb tellimustest)
  
  
2) Kaup
  2.1. Pilt
  2.2. Omadused
  2.3. Hind
  2.4. Laoseis (väheneb, kui kaup lisatakse korvi, suureneb, kui kaupa tuuakse juurde või pannakse korvist tagasi)
  
  
3) Ostukorv
  3.1. Kaup ja kogus (saab korvi lisada ja eemaldada)
  

4) Tellimus - ostukorv "muutub" tellimuseks, kui korvis olev kaup "ära ostetakse"
  4.1. Ostukorvi sisu (kaup * kogus)
  4.2. Ostu/tarne aeg
  4.3. Makseviis
  4.4. Tarneviis


Pseudokood Kasutaja lugu

:: Kasutaja siseneb lehele
IF Kasutaja tahab sisse logida CREATE objekt Kasutaja, UPDATE objekt Kasutaja
:: Kasutaja sirvib kaupa -> CREATE objekt Ostukorv
:: Kasutaja lisab/eemaldab kauba -> UPDATE objekt Ostukorv objektiga Kaup
:: Kasutaja vormistab tellimuse -> CREATE Objekt Tellimus, DELETE Objekt Ostukorv
:: IF Objekt Kasutaja UPDATE objekt Kasutaja objektiga Tellimus


Pseudokood BAckoffice admin lugu
IF tuli uus kaup CREATE objekt Kaup, UPDATE objekt KAUP
IF kaup läks müügilt ära DELETE objekt Kaup
IF kaupa tuli juurde UPDATE objekt Kaup

--->
