# Reading scissors-palvelun vaatimusmäärittely

Tämä vaatimumäärittely on "elävä"-dokumentti, joka päivittyy jatkuvasti.
<!-- Dokumentti on karkea runko, jota voi käyttää projektien vaatimusmäärittelyn pohjana,
mutta se vaatii muokkausta!
Tavoitteena on luoda dokumentti, joka yhdistää palvelumuotoilun ja ohjelmistosuunnittelun saumattomasti yhteen. Tekijä ei ota mitään vastuuta dokumentin sisällöstä.

tv:NarsuMan -->






## Sisällysluettelo ?


* <a href="#Johdatus">Johdatus</a>
* <a href="#Asiakastarina">Asiakastarina</a>
* <a href="#Sidosryhmät ja profiilikuvaukset">Sidosryhmät ja profiilikuvaukset</a>
* <a href="#Sidosryhmäkuva">Sidosryhmäkuva</a>
* <a href="#Asiakastpolku">Asiakastpolku</a>
* <a href="#Yleinen käyttötapaus">Yleinen käyttötapaus</a>
* <a href="#Yleiset toiminnalliset vaatimukset">Yleiset toiminnalliset vaatimukset</a>
* <a href="#Yleiset ei-toiminnalliset vaatimukset">Yleiset ei-toiminnalliset vaatimukset</a>
* <a href="#Palvelu MockUp">Palvelu MockUp</a>
* <a href="#Tärkeimmät ominaisuudet">Tärkeimmät ominaisuudet</a>
* <a href="#Julkaisun suunnitelma">Julkaisun suunnitelma</a>



## Johdatus

Mikä on tämän vaatimusmäärittelydokumentin tehtävä?
* Mihin se liittyy ?
* Tärkeätä tietää/oleellista lukijalle ?
Tämä dokumentti määrittelee oleelliset asiat

### Palvelukuvaus/asiakastarina

Pyri vastaamaan seuraaviin kysymyksiin!

* Mitä määritetyltä palvelulta odotetaan?
* Miten käytön oletetaan tapahtuvan
* Mitä saadaan hyötyä

### Tilaaja

Vastaa seuraaviin kysymyksiin!

* Kuka tilaa määrittelytyön, yhteistiedot ?

### Toimittaja

* Kuka tekee määrittelytyön, yhteistiedot ?


## Asiakastarina

* Kirjoita tähän lyhyt kuvaus miten tuotteen/palvelun tulee toimia.
* [Esimerkki 1]()
* [Esimerkki 2]()
* [Esimerkki 3]()
* [Esimerkki 4]()


## Sidosryhmät ja profiilikuvaukset

Kirjataan näkyviin kaikki sidosryhmät, jotka on tunnistettu liityvän palveluun. Vastaa kysymykseen kuka/mikä on kiinnostunut tuotteesta tai kenellä on sanansa sanottavana liittyen tuotteen kehittämiseen ? Ota selvää mitä sidosryhmiä liittyy tehtäväantoon?

Esimerkkejä! korvaa toimeksiantoon liittyvillä henkilöillä

* [Esimerkki persoonat eri profiileille](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/esimerkki-asiakasprofiilit.md)

| Sidosryhmä/asiakasprofiili | Tehtävä | Muuta |
|:-: | :-: | :-: |
| [Asiakasprofiili-1](asiakasprofiili-1.md) | Jarmo Mainio, 27, eläkeläinen, Vierumäki, kotosin Pohjois-Savosta  | (Matematiikan opettaja) |
| [Asiakasprofiili-2](asiakasprofiili-2.md) | Rigu Rich, 30, IT Yrittäjä, asuinpaikka tuntematon, kotoisin nomands land | Ulkomaalainen |
| [Asiakasprofiili-3](asiakasprofiili-3.md) | Siiri Koikkalainen 99, suurmummo, Hankasalmi,  | (Sokea) |
| [Asiakasprofiili-4](asiakasprofiili-4.md) | John Rambu, 55, tuntematon, Helsinki, (Bad Man) | Hankala asiakas |
| [Asiakasprofiili-5](asiakasprofiili-5.md) | Sad Frog 26 |  | Kiusantekijä | |
| [Asiakasprofiili-6](asiakasprofiili-6.md) | Sad Frog 26 |  | Kiusantekijä | |
|[Sidosryhmä-1](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-asiakasprofiili.md) |  Mungo consulting Oy | Palvelun tarjoaja |
| [Sidosryhmä-2](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-asiakasprofiili.md) | RahoittajaA |  |Yrityksen osakas, Mauri Bosse, omistaa 5 % | |
| [Sidosryhmä-3](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-asiakasprofiili.md) | TuotantotiimiA | yrityksen työntekijät, Kalle, Kille, Pelle ja Pöppö | |
| SuurAsiakasA |  | NordMan Oy, yritysasiakas | |
| Bad Man |  |Kiusantekijä | |
| Snake Consulting Oy | | kilpailija | |



## Sidosryhmäkuva (Stakeholder map)

![Sidokuva](images/sidoskartta.png)

[Edit](https://www.draw.io/?title=sidoskartta.png&url=https://github.com/garismaatti/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/raw/master/images/sidoskartta.png?t=0) to edit this image in a browser




## Asiakaspolku (Customer Journey)

Käydään läpi asiakaspolku, jossa käytetään nimettyjä sidosryhmien edustajia

![Asiakaspolku-kuva](images/asiakaspolku.png)



## Yleinen käyttötapaus

* Palvelun kannalta tärkeät käyttötapaukset yhteiskuvassa (Use Case Diagram)

![](https://raw.githubusercontent.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/master/images/Use%20Case%20-%20New%20Page.png)

| Käyttötapaus | | |
|:-:|:-:|:-:|
| [Rekisteröityminen](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-kayttotapauskuvaus.md) | | |
| [Salasanan vaihto](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-kayttotapauskuvaus.md) | | |
| [Avatarin valinta](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-kayttotapauskuvaus.md) | | |
| [Salasanan vaihto](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-kayttotapauskuvaus.md) | | |





## Palveluun liittyvät toiminnalliset vaatimukset

  * Tässä osiossa voidaan nostaa esiin huomioitavia tärkeitä vaatimuksia, jotka on hyvä pitää mielessä!

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|YVA0001| Palvelun täytyy toimia Android versiosssa 4.x alkaen | Tekninen | "ASAP"-tuotantotiimi | P1 |
|YVA0002| Palvelun täytyy toimia Windows Phonessa | totetutus |  "ASAP"-tuotantotiimi | P2 |
|YVA0003| Palvelun täytyy toimia Windows 95:ssa, koska johtajalla on moinen koneessaan! | totetuts |  "ASAP"-tuotantotiimi | P5 |

  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali


Millaisiin osa-alueiseiin voidaan ohjelmisto/palvelu voidaan jakaa.

Onko olemassa erilaisia tuoteversioita eri ympäristöihin, mitä?

  * Työpöytäversio ?
  * Mobiiliversio ?
  * Kenttäversio  

ohjelmiston osa-alueita/lohkoja?

  * Hallintapaneeli ?
  * Tietokanta-palvelut ?
  * Käyttöliittymät ?
  * Autentikointi ?
  * Laskutus ?


## Palveluun liittyvät ei-toiminnalliset vaatimukset

### Suorituskyky?


### Tietoturva?

### Käytettävyys

  * Mitä on otettava huomioon ?
  * Asiakkaan toiveet ?
  * Teknologiset osa-alueet/asiat, jotka vaikuttavat käytettävyyteen?



## Palvelu MockUp-prototyyppi

Palvelun MockUp-prototyyppi on koetettavissa osoitteessa https://ninjamock.com/s/GLJRL

![](images/Mockup_v1.png)

## Tärkeimmät tunnistetut ominaisuudet (Features)


  * Kirjataan tärkeimmät ominaisuudet
  * Mitä ovat oleelliset ominaiduudet ?
  * [Tsekkaa MVP - Minimum Viable Product Features](https://en.wikipedia.org/wiki/Minimum_viable_product)

| Ominaisuus | Prioriteetti | Muuta |
| :-: | :-: | :-: |
| [Käyttäjä voi kirjautua 1](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi rekisteröityä 2](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi kirjautua ulos 3](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi luoda uuden projektin 4](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi poistaa projektin 5](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi uudelleen nimetä projektin 6](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi ladata uuden kuvan palveluun 7](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi uudelleen nimetä kuvan 8](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi uudelleen järjestää kuvia 9](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi lisätä uuden notaation 10](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi poistaa notaation 11](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi muokata notaatiota 12](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi tallentaa notaation 13](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi vaihtaa seuraavaan käsiteltävään kuvaan 14](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi vaihtaa eleltävään käsiteltävään kuvaan 15](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi siirtyä projekti-näkymän ja kuvalista-näkymän välillä 16](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Käyttäjä voi siirtyä editointi-näkymän ja kuvalista-näkymän välillä 17](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Ominaisuus 18](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Ominaisuus 19](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| [Ominaisuus 20](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |



## Julkaisun suunnitelma


## Riskit  (Risks)

   * Tunnistetaan ohjelmistoon/palveluun liittyviä riskejä..
   * [Riskienhallinta](https://fi.wikipedia.org/wiki/Riskienhallinta)

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|RISK001| Käyttäjämäärän äkillinen lisääntyminen, esim poikkeustilanteen aikana | - | P1 |
|RISK002| Palvelun käytettävyys heikkenee kovan kuormituksen aikana | Toiminnnallinen |  | P5 |
|RISK003| Heikon verkkoyhteyden vaikutus palvelun käyttöön | Toiminnnallinen | - | P3 |

  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali

## Tuotteen yleiset vaatimukset



## Palvelun/ohjelmiston arkkitehtuuri

  * Tämä osio voidaan sisällyttää osaksi teknistä suunnittelua.
  * Vaatimusmäärittelyssä voi kuitenkin olla  hyvä tarvittaessa kuvata yleistä totetutusta ja siihen liittyviä ongelmakohtia


![](https://camo.githubusercontent.com/5c169deb4debb278bb6219208f577843075ddab3/68747470733a2f2f7777772e64726f70626f782e636f6d2f732f6179707170797376726831316133312f636f6e747269626f6172642d6172636869746563747572652e706e673f646c3d31)

   * [Esimerkki elävästä elämästä](https://confluence.csc.fi/display/OPHPALV/Koodistopalvelun+tekninen+dokumentaatio)


### Sijoittelunäkymä (Deployment diagram

  * Vaatimusmäärittelyssä tämä saattaa olla yksi hyödyllisimpiä UML-kuvauksia ?
  * Miten ohjelmisto/palvelu tulee karkeasti toimimaan osana vanhaa totetutusta..
  * Miten olemassa oleva järjestelmä tulee karkeasti toimimaan

![](https://www.lucidchart.com/publicSegments/view/6f727a36-f880-4dca-b5ac-133f6f860697/image.png)


## Riskiperustainen esi-testaussuunnitelma

### Tunnistetut riskit ja testikohtee

  * Riski -> Testaustarve
  * Vaatimus -> Testaustarve


##  Julkaisusuunnitelma ja priorisointi

Julkaisujärjestys ei aina ole lineaarinen. [Ks. Kriittinen polku](https://fi.wikipedia.org/wiki/Kriittinen_polku)
Joskus se saattaa tuntua siltä: [Release Plan](https://wiki.documentfoundation.org/ReleasePlan)


Toiminnallisuudet ja toteuttamisjärjestys

  * Ominaisuus 1 - Maaliskuu 2019
  * Ominaisuus 3 - Huhtikuu 2019
  * Ominaisuus 5 - Toukokuu 2019
  * Ominaisuus 2 - Syyskuu 2019


### Priorisointi


  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali


## Standardit ja lähteet

  * ISTQB
  * IPMA
  * etc..



# Lähteet

# Lähteitä

  * https://fi.wikipedia.org/wiki/Ohjelmiston_vaatimusm%C3%A4%C3%A4rittely
