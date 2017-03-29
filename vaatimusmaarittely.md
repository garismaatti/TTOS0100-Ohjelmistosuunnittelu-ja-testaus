# Reading scissors-palvelun vaatimusmäärittely

Tämä vaatimumäärittely on "elävä"-dokumentti, joka päivittyy jatkuvasti.
<!-- Dokumentti on karkea runko, jota voi käyttää projektien vaatimusmäärittelyn pohjana,
mutta se vaatii muokkausta!
Tavoitteena on luoda dokumentti, joka yhdistää palvelumuotoilun ja ohjelmistosuunnittelun saumattomasti yhteen. Tekijä ei ota mitään vastuuta dokumentin sisällöstä.

tv:NarsuMan -->






## Sisällysluettelo ?


* <a href="#johdatus">Johdatus</a>
* <a href="#palvelukuvaus">Palvelukuvaus</a>
* <a href="#vaatimusmäärittelytyön-tilaaja">Vaatimusmäärittelytyön tilaaja</a>
* <a href="#vaatimusmäärittelyn-toimittaja">Vaatimusmäärittelyn toimittaja</a>
* <a href="#asiakastarina">Asiakastarina</a>

* <a href="#sidosryhmät-stakeholders-ja-profiilikuvaukset-profile-descriptions">Sidosryhmät (Stakeholders) ja profiilikuvaukset (Profile descriptions)</a>
* <a href="#sidosryhmäkuva-stakeholder-map">Sidosryhmäkuva (Stakeholder map)</a>
* <a href="#asiakaspolku-customer-journey">Asiakaspolku (Customer Journey)</a>
* <a href="#tuotteen-yleisi%C3%A4-vaatimuksia-ja-rajoituksia-general-requirements-and-restrictions">Tuotteen yleisiä vaatimuksia ja rajoituksia (General Requirements and restrictions)</a>
* <a href="#yleiset-k%C3%A4ytt%C3%B6tapaukset-general-use-cases">Yleiset käyttötapaukset (General Use Cases)</a>
* <a href="#palveluun-liittyvät-toiminnalliset-vaatimukset-functional-requirements">Palveluun liittyvät toiminnalliset vaatimukset (Functional Requirements)</a>
* <a href="#palveluun-liittyv%C3%A4t-ei-toiminnalliset-vaatimukset-non-functional-requirements">Palveluun liittyvät ei-toiminnalliset vaatimukset (Non Functional Requirements)</a>
* <a href="#suorituskyky-performance">Suorituskyky? (Performance)</a>
* <a href="#luotettavuus">Luotettavuus?</a>
* <a href="#tietoturva">Tietoturva?</a>
* <a href="#käytettävyys">Käytettävyys?</a>
* <a href="#palvelu-mockup-prototyyppi">Palvelu MockUp-prototyyppi</a>
* <a href="#t%C3%A4rkeimm%C3%A4t-tunnistetut-ominaisuudet-features">Tärkeimmät tunnistetut ominaisuudet (Features)</a>
* <a href="#palvelunohjelmiston-arkkitehtuuri">Palvelun/ohjelmiston arkkitehtuuri</a>
* <a href="#yleinen-sijoittelun%C3%A4kym%C3%A4-deployment-diagram-">Yleinen sijoittelunäkymä (Deployment diagram )</a>
* <a href="#arkkitehtuuriinteknologiaan-liityv%C3%A4t-vaatimukset">Arkkitehtuuriin/teknologiaan liityvät vaatimukset</a>
* <a href="#yll%C3%A4pito-maintenance">Ylläpito (Maintenance)</a>
* <a href="#yleinen-tietokantakuvaus-database-er-diagram">Yleinen tietokantakuvaus (Database ER-diagram)</a>
* <a href="#testauksen-vaatimukset-testing-requirements">Testauksen vaatimukset (Testing requirements)</a>
* <a href="#testattavuus">Testattavuus</a>
* <a href="#tunnistetut-riskit-ja-testikohteet">Tunnistetut riskit ja testikohteet</a>
* <a href="#dokumentit-standardit-ja-l%C3%A4hteet">Dokumentit, standardit ja lähteet</a>


## Johdatus

Mikä on tämän vaatimusmäärittelydokumentin tehtävä?
* Mihin se liittyy ?
* Tärkeätä tietää/oleellista lukijalle ?
Tämä dokumentti määrittelee oleelliset asiat

Tämä on vaatimusmäärittely uudelle web palvelulle. Tämän palvelun ydin alue on tarjota käyttäjille työkaluja helpottamaan varsinkin vieraskielisen tekstin lukemista kuvista.



### Palvelukuvaus

Palvelun ydin alue on tarjota käyttäjille työkaluja helpottamaan varsinkin vieraskielisen tekstin lukemista kuvista. Palvelu tulee auttamaan muuntamaan suuria määriä kuvallista-tekstiä sähköiseen muokattavaan muotoon, sekä tarjoamaan erilaisia työkaluja sen kääntämiseen eri kielille.
Palvelulla pyritään helpottamaan erilaisten ihmisten tarpeita saada selvää mitä kuvissa lukee. Palvelu on suunnattu ammattikseen kääntäville henkilöille, tutkijoille, harrastelijoille ja opiskelijoille joilla on tarvetta esimerkiksi kääntää vanha saksankielinen ohjekirja suomeksi.

Palveluun idea on myös tarjota asiakkaalleen niin sanottu "overlay"-tila jossa käännetty teksti näytetään suoraan vanhan päällä. Tämä yhdistettynä mahd. jakaa katselu/muokkaus oikeuksia muille käyttäjille antaa mahd. näyttää käännöstyötä asiakkaalle nopeasti ja menettämättä tekstiin liittyviä kuvia.





### Vaatimusmäärittelytyön tilaaja

Vaatimusmäärittelytyön tilaajana toimii palvelun tekijä Salopää Ari.




### Vaatimusmäärittelyn toimittaja

Vaatimusmäärittelytyön toimittaa Ari Salopää.



## Asiakastarina

[Paul Yeager](asiakasprofiili-2.md) tarvitsee työkalun auttamaan häntä kääntämään 93 sivuisen ranskan kielisen paperisen huolto-oppaan englanniksi yrityksen työntekijöille jaettavaksi.
Paul aloittaa työnsä skannaamalla huolto-oppaan digitaaliseen muotoon ja syöttää kuvat palveluun. palvelussa Paul pystyy valitsemaan sivuilta teksti osion ja antaa koneen tehdä näille automaattisen käännöksen. koneen vielä miettiessä automaattisia käänöksiä Paul pystyy aloittaamaan tarkistamaan ja korjaamaan ensimmäisen sivun automaattisia käännöksiä. Vaikeammissa sanoissa Paul pystyy käyttämään apunaan sivun reunassa olevaa kääntäjää etsiäkseen nopeasti hyvän ja tarkan käännöksen.
Koska kone tekee suuren osan työstä, nopeutuu käännöksen syntyminen huomattavasti ja Paul saa päivässä aikaan huomattavasti enemmän aikaan kuin ilman palvelua. Iltapäivällä Paul pystyykin jo jakamaan oikeudet työkaverilleen, joka pystyy tarkastelemaan alku sivujen tuotosta samalla kun Paul tekee loppupään viimeistelyjä.

Seuraavana päivänä Paul saa työnsä valmiiksi ja lataa käännetyn tekstin tekstitiedostona ulos palvelusta.



## Sidosryhmät (Stakeholders) ja profiilikuvaukset (Profile descriptions)

Palvelun sidosryhmät ovat Palvelun käyttäjät, Palvelun ylläpitäjät, Crakkerit ja Omistaja.

**Käyttäjä**

Käyttäjät ovat asiakkaita mitä palvelumme palvelee.


**Ylläpitäjät**

Ovat palvelun kehittäjiä ja ylläpitäjiä jotka tekevät, ylläpität, huoltavat palvelua ja auttavat tarvittaessa palvelun käytössä.

**Omistaja(t)**

Palvelun omistajat jotka etsivät rahallista hyötyä palvelun omistuksesta.

**Crakkerit** (Hakkerit)

Uhka palvelulle (ja sen käyttäjille) mahd. hyökkäyksillä itse palvelua vastaan yrittäin häiritä toimintaa tai varastaa tietoja, kuten käyttäjien salasanoja.



## Sidosryhmäkuva (Stakeholder map)

![Sidokuva](images/sidoskartta_2.png)


## Asiakaspolku (Customer Journey)

Malli käyttäjä [Jarkko](asiakasprofiili-1) haluaa nopeasti kuvallisessa muodossa olevasta tehtävästä ottaa tehtävä kuvauksen raporttiinsa ja luo seuraavan laisen asiakaspolun tehdessään sen.

![Asiakaspolku-kuva](images/asiakaspolku.png)


## Tuotteen yleisiä vaatimuksia ja rajoituksia (General Requirements and restrictions)

Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit,
sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est,
qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora
incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam,


| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| GENREQ001 | Käyttäjien tunnistus | Tietoturva | - |
| GENREQ002 | Verkkoliikenteen salaus | Tietoturva | - |
| GENREQ003 | Kuvien lataaminen | Käyttäjän sisältö | - |
| GENREQ004 | Vaatimus? | Mikä osa-alue | - |
| GENREQ005 | Vaatimus? | Mikä osa-alue | - |
| GENREQ004 | Vaatimus? | Mikä osa-alue | - |
| GENREQ004 | Vaatimus? | Mikä osa-alue | - |
| GENREQ004 | Vaatimus? | Mikä osa-alue | - |
| GENREQ004 | Vaatimus? | Mikä osa-alue | - |



## Yleiset käyttötapaukset (General Use Cases)

Seuraavana kuva yleisistä käyttötapauksista. Kuvasta puuttuu vielä lieta määrittelemättäiä tapauksia joita lisätään myöhemmin.

![](images/usecases.png)

| Käyttötapaus | Linkki | Muuta |
|:-:|:-:|:-:|
| Käyttötapaus Käyttäjän rekisteröiminen | [Use Case 1](kayttotapaus-1.md) | - |
| Käyttötapaus Käyttäjä kirjautuu palveluun | [Use Case 2](kayttotapaus-2.md) | - |
| Käyttötapaus Uuden kansion luominen | [Use Case 3](kayttotapaus-3.md) | - |
| Käyttötapaus Kuvien lataaminen palveluun | [Use Case 4](kayttotapaus-4.md) | - |
| Käyttötapaus Kuvan uudelleen nimeäminen | [Use Case 5](kayttotapaus-5.md) | - |


## Palveluun liittyvät toiminnalliset vaatimukset (Functional Requirements)

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium,
totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae
dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit,
sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est,
qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora
incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam,
quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ001 | Palvelun pitää toimia uusimmassa Mozilla Firefox selaimessa | Mikä osa-alue | Kuka vastaa |
| REQ002 | Palvelun pitää toimia uusimmassa Google Chrome selaimessa | Mikä osa-alue | Kuka vastaa |
| REQ003 | Palvelun pitää toimia uusimmassa Apple Safari selaimessa | Mikä osa-alue | Kuka vastaa |
| REQ004 | Vaatimus? | Mikä osa-alue | Kuka vastaa |
| REQ005 | Vaatimus? | Mikä osa-alue | Kuka vastaa |


## Palveluun liittyvät ei-toiminnalliset vaatimukset (Non Functional Requirements)

Palvelulla ei tällä hetkellä ole ei-toiminnallisia vaatimuksia.

### Suorituskyky? (Performance)

Palvelun suorituskyvy yritetään pitään miellyttävät käytön rajoissa.

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Kuvien muokkaus palvelussa (kuten kierto) ei saa kestää useita minuutteja | Suorituskyky | järjestelmä |
| REQ00x | Kuvien selaus näkymässä esikatselukuvien ilmestyminen ei saa kestää yli 40sekunttia | Suorituskyky | järjestelmä |
| REQ00x | Vaatimus? | Suorituskyky | järjestelmä |

### Luotettavuus?

Palvelusta pyritään tekemään mahdollisimman luotettava ja palvelu pyritään pitämään ylhäällä koko ajan.

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Palvelun sivuja ei pidä tarvita virkistää kuin max 1/pv luotettavan käytön takaamiseksi | Luotettavuus | Kuka vastaa |
| REQ00x | Vaatimus? | Luotettavuus | Kuka vastaa |
| REQ00x | Vaatimus? | Luotettavuus | Kuka vastaa |


### Tietoturva?

Palvelussa tietoturva on otettu huomioon palvelun koko elinkaaren ajan ja tietoturvaa kehitetään jatkuvana prosessina.

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Kaikki liikenne pitää olla salattu | Tietoturva | järjestelmä |
| REQ00x | Oletuksena vain käyttäjä itse näkee omat kuvansa | Tietoturva | järjestelmä |
| REQ00x | Helposti arvattavia salasanoja ei sallita | Tietoturva | järjestelmä |
| REQ00x | Heikkoja salasanoja ei sallita | Tietoturva | järjestelmä |
| REQ00x | Kuvat skannataan viirusten varalta | Tietoturva | järjestelmä |
| REQ00x | Kaikki syöte kentät sanitoidaan | Tietoturva | järjestelmä |


### Käytettävyys

Palvelun käyttöliittymä oletetaan olevan yleinen tietokoneen selain, muita laitteita tai ohjelmia ei tässä vaiheessa tueta.

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Käyttöliittymän väri-teema pitää miellyttää silmää | Käytettävyys | Kuka vastaa |
| REQ00x | Tekstit pitää olla selkeästi luettavissa | Käytettävyys | Kuka vastaa |
| REQ00x | Silmiä ärsyttäviä väri-vastaväri kohtia ei saa löytyä | Käytettävyys | Kuka vastaa |
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa |
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa |


## Palvelu MockUp-prototyyppi


Palvelun MockUp-prototyyppi on koetettavissa osoitteessa https://ninjamock.com/s/GLJRL

![](images/Mockup_v1.png)


## Tärkeimmät tunnistetut ominaisuudet (Features)

qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora
incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam,
quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?

| Ominaisuus | Prioriteetti | Muuta |
| :-: | :-: | :-: |
| [Ominaisuus 1 Käyttäjä voi kirjaustua](ominaisuuskuvaus-1.md) | | |
| [Ominaisuus 2 Kuvien hallinta](ominaisuuskuvaus-2.md) | | |
| [Ominaisuus 3 Käännöksien hallinta](ominaisuuskuvaus-3.md) | | |
| [Ominaisuus 4 Kansioiden hallinta](ominaisuuskuvaus-4.md) | | |
| [Ominaisuus 5](ominaisuuskuvaus-5.md) | | |
| [Ominaisuus 6](ominaisuuskuvaus-6.md) | | |
| [Ominaisuus 7](ominaisuuskuvaus-7.md) | | |




## Julkaisun suunnitelma

| Aika + Ominaisuuus | Kuvaus | Vastuu | Prioriteetti |
|:-:|:-:|:-:|:-:|
| 1.1.201x [Ominaisuus 1](ominaisuuskuvaus-1.md) | | |
| 1.4.201x [Ominaisuus 2](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| 15.4.201x [Ominaisuus 3](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |
| 5.5.201x [Ominaisuus 4](https://github.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/blob/master/pohja-ominaisuuskuvaus.md) | | |


# Palvelun/ohjelmiston arkkitehtuuri

### Yleinen sijoittelunäkymä (Deployment diagram )

![](https://openclipart.org/image/800px/svg_to_png/17266/berteh-flow-diagram-symbols.png&disposition=attachment)


# Arkkitehtuuriin/teknologiaan liityvät vaatimukset

### Ylläpito (Maintenance)

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Vaatimus? | Yllläpito | Kuka vastaa |
| REQ00x | Vaatimus? | Tekninen | Kuka vastaa |
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa |
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa |
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa |

### Yleinen tietokantakuvaus (Database ER-diagram)

ER-kaavio

![](http://www.conceptdraw.com/solution-park/resource/images/solutions/entity-relationship-diagram-(erd)/Design_Elements(Crows-Foot-ERD).png)


# Testauksen vaatimukset (Testing requirements)

### Testattavuus

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa |
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa |
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa |
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa |
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa |



# Tunnistetut riskit ja testikohteet

  * Riski -> Testaustarve
  * Vaatimus -> Testaustarve



### Dokumentit, standardit ja lähteet

qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora
incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam,
quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?


*Lähteet*

| ID | Lähde | Kuvaus | Linkki |
|:-:|:-:|:-:|:-:|
| Id0 | Wikipedia | Vaatimusmäärittely |   https://fi.wikipedia.org/wiki/Ohjelmiston_vaatimusm%C3%A4%C3%A4rittely
- |
| - | -  | - |
| - | -  | - |
| - | -  | - |
