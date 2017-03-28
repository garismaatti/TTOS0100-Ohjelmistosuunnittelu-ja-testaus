## KÄYTTÖTAPAUKSEN *Uuden käyttäjän rekisteröiminen*

Yleiskuvaus	Kuvataan lyhyesti mikä on käyttötapauksen tarkoitus/ tehtävä.
Esim. Käyttäjä lisää, muuttaa tai poistaa tietoja

Uusi käyttäjä lisää tietonsa palveluun ja hyväksyy käyttäjäehdot palvelun käyytöön ja

## Kuva

![](https://raw.githubusercontent.com/JAMK-IT/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/master/images/Actor%20ja%20case.png)




###Laatija	Kirjataan laatijan nimi.

  * 2017-03-29 / V2	Kirjataan laatimispäivä ja versio.
  * Prosessi	Uuden asiakkaan lisääminen palveluun

### Käyttäjäroolit	Kuvataan käyttötapauksen käyttäjäroolit	Roolin oikeudet

  * rooli 1	Uusi käyttäjä 	hyvin rajoitetut oikeudet
  * rooli 2	Käyttäjä	Peruskäyttäjän oikeudet
  * rooli 3	Järjestelmä		kaikki oikeudet

### Esitiedot/ehdot

  * Uudella käyttäjällä ei saa olla aiempaa tiliä
  * Uudella käyttäjällä on oltava toimiva sähköpostiosoite


### Käyttötapauksen kuvaus

  * 1	Uusi käyttäjä avaa palvelun aloitus näkymän.
  * 2	Uusi käyttäjä aloittaa uuden tilin rekisteröinnin.
  * 3	Uusi käyttäjä syöttää tietonsa järjestelmään ja hyväksyy käyytäjä ehdot.
  * 4	Järjestelmä tarkistaa tietojen muodollisen oikeellisuuden. (P1)
  * 5	Järjestelmä tarkistaa käyttäjän tiedot olevan uusi käyttäjä. perustuen rekisterissä jo oleviin tietoihin. (P2)
  * 6	Järjestä lisää uuden kättäjän tiedot rekisteriin.
  * 7	Järjestelmä lähettää varmennus linkin sähköpostiin ja ilmoittaa tästä uudelle käyttäjälle.
  * 9	Uusi käyttäjä avaa linkin sähköpostissaan. (P3)
  * 10	Järjestelmä kirjaa uuden käyttäjän tiedot aktiiviseksi, nostaa uuden käyttäjän oikeudet käyttäjäksi ja ohjeistaa jatkosta.


### Poikkeukset

  * P1

P1 Järjestelmä ilmoittaa uudelle käyttäjälle, että uuden käyttäjän syöttämissä tiedoissa on virheitä ja pyytää korjaamaan ennen jatkamista.

  * P2

P2 Järjestelmä ilmoittaa uudelle käyttäjälle, että uuden käyttäjän tiedot löytyivät jo järjestelmästä ja ohjeistaa jatkotoimenpiteissä.

  * P3

P3 Uusi käyttäjä ei avaa varmennus linkkiä annetussa ajassa. Järjestelmä poistaa uuden käyttäjän tiedot ilmoittamatta uudelle käyttäjälle.




### Lopputulos

Kuvataan mikä on käyttötapauksen lopputulos. Esim. Käyttäjälle tietoja on päivitetty. Tiedot on tallennettu tietokantaan. Käyttäjälle on lähetetty vahvistus tietojen varmennuksesta.
Muut vaatimukset v1	Kuvataan mitä muita vaatimuksia käyttötapaukselle asetetaan toiminnallisten vaatimusten lisäksi.

  * v1 Käyttäjä tietojen varmennus ei saa kestää yli 25sek.
  * v2 Samalla

v3

### Käyttötiheys	Kuvataan, kuinka usein käyttötapausta suoritetaan..

Esim. Muutoksia tehdään n.100/päivässä

### Muuta	Kuvataan muita käyttötapaukseen liittyviä oleellisia tietoja, kuten avoimia asioita, viittauksia käytettäviin koodistoihin jne.



**Lähde**

Tämä wiki-dokumentin runko pohjautuu [Julkisenhallinnon suosituksiin](http://www.jhs-suositukset.fi/web/guest/jhs/recommendations/173)
