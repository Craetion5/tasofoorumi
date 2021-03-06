## Tasofoorumi

### TESTITUNNUS:
#### Käyttäjätunnus: test
#### Salasana: 12345678

Tavoitteena on luoda foorumi [aikaisemmin ohjelmoimani pelin](https://github.com/Craetion5/otm-harjoitustyo) tasojen jakamista varten. Tämä peli mahdollistaa tasojen muokkaamisen, tallentamisen tekstimuotoiseksi koodiksi ja lataamisen tekstimuotoisesta koodista. Foorumilla olisi tarkoitus olla seuraavia toiminnallisuuksia:

#### Käyttäjäsysteemi

Foorumin käyttäjät voivat luoda tunnuksen, kirjautua sisään ja kirjautua ulos.

#### Tasojen jakaminen

Pelikenttien jakaminen on foorumin keskeinen ominaisuus. Sisäänkirjautuneet käyttäjät voivat jakaa tasoja tekemällä postauksia, joissa jaetaan tekstimuotoinen pelisovelluksessa luotu tasokoodi, ja annetaan tasolle nimi ja mahdollinen kuvaus. Tavalliset käyttäjät voivat poistaa omia tasopostauksiaan, ja pääkäyttäjät voivat poistaa myös muiden tasoja.

#### Tasojen tarkasteleminen ja etsiminen

Foorumilla voi tarkastella käyttäjien postaamia tasoja, ja sisäänkirjautuneet käyttäjät voivat jättää niihin kommentteja. Foorumilla on toiminnallisuudet kaikkien tasojen, käyttäjäkohtaisten tasojen ja pääkäyttäjien valitsemien tasojen listaamiseen.

[Projekti Herokussa](https://mazelevelforum.herokuapp.com/)

[Tietokantakaavio](https://github.com/Craetion5/tasofoorumi/blob/master/documentation/tietokantakaavio.png)

[User storyjä ja SQL-lauseita](https://github.com/Craetion5/tasofoorumi/blob/master/documentation/user_storyt.md)

[Asennusohje](https://github.com/Craetion5/tasofoorumi/blob/master/documentation/ohje.md)

### Jatkokehittelyideoita

* tasolistoihin näkyviin tasojen tekijä
* tasoille tykkäyssysteemi tai tageja
* kirjautumisen tarkistamisen toteuttaminen järkevämmin
* käyttäjille omat sivut tasojen listaamisen lisäksi
* tasojen ja käyttäjien listaamisen lisäksi etsiminen hakusanoilla
* erillisen pelisovelluksen tasokoodien jakamisen sijaan nettisivustolle voisi koodata javascript-pelin jota varten luoduissa tasopostauksissa käyttäjät voisivat suoraan pelata kyseisiä tasoja
