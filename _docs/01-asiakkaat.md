---
title: 'Kohan ohje suomeksi'
permalink: /dokumentaatio/asiakkaat/
redirect_from:
  - /theme-setup/
toc: true
---

# 1. Asiakkaat

## 1.1. Lisää uusi asiakas

Asiakkaat lisätään menemällä Asiakkaat-välilehdelle.

![](/assets/files/docs/Asiakkaat/Asiakkaat.png)

Klikkaa Uusi asiakas, saat alasvetovalikon, josta valitset asiakkaan
tyypin.

![](/assets/files/docs/Asiakkaat/Asiakkaatlista.png)

### Henkilötunnus ja sotu-siilo

Kohaan on tehty Suomessa uusi ominaisuus, sotu-siilo, jonne tallennetaan
tietoturvallisesti asiakkaiden henkilötunnukset.

Oheisissa ruutukaappauksissa käytetty sotu on tehty
henkilötunnusgeneraattorin avulla, se ei ole kenenkään henkilön oikea
tunnus, mutta täyttää tunnuksen ominaisuudet tarkistusmerkkiä myöten.
Sotuavaimella muodossa “sotuxxxx” voi hakea asiakkaan tiedot esille,
mutta henkilötunnus ei näy.

Syötä Tarkista sotun olemassaolo -osioon asiakkaan henkilötunnus.

![](/assets/files/docs/Asiakkaat/sotusiilo.png)

Jos henkilötunnusta ei ole ennestään sotu-siilossa, siitä tulee ilmoitus
vihreällä taustalla “Sotu lisätty. Avain sotu322453 löytyi”.

![](/assets/files/docs/Asiakkaat/sotusiilo2.png)

Sotu-avain siirtyy automaattisesti asiakastietoihin Muut määritteet ja
tunnukset -kohtaan kenttään Sosiaaliturvatunnus/Henkilötunnus/Sotu-avain
(kentän nimi voi vaihdella kimpan mukaan).

![](/assets/files/docs/Asiakkaat/sotusiilo3.png)

Jos henkilötunnus on virheellinen, tulee siitä ilmoitus: “Sotu on
virheellinen”.

#### Sotu on jo olemassa

Jos syötetty henkilötunnus on jo sotu-siilossa, tulee ilmoitus “Sotu on
jo olemassa. Avain sotu322453 löytyi”. Tarkista esimerkiksi toisella
välilehdellä asiakas-haussa sotu-avaimella, löytyykö Kohan tietokannasta
asiakastietoja. Jos löytyy, muokkaa löytyneitä asiakastietoja. Jos ei
löydy, niin tee uudet asiakastiedot käyttäen Muut määritteet ja
tunnukset -kentässä sotu-siilon antamaa sotu-avainta.

Ilmoitus sotun olemassa olosta voi tulla myös, jos olet epähuomiossa
tuplaklikannut _Lisää sotu!_ –painiketta. Tuplaklikkaus aiheuttaa sen,
että asiakkaan henkilötunnus oli tallentunut jo ensimmäisellä
klikkauksella sotusiiloon ja toisella klikkauksella Koha antaa yllä
olevan ilmoituksen.

#### Sotu-siilon käyttöliittymä

Sotu-siiloon on olemassa myös toinen käyttöliittymä, jonka kautta
esimerkiksi laskuttajat voivat tarkistaa asiakkaan henkilötunnuksen
sotu-avaimella. Heillä on erilliset tunnukset tarkistusta varten.

---

### Nimi ja yhteystiedot

Syötä asiakkaan koko nimi, syntymäaika ja varaustunniste. Huomaathan,
että kimppasi Kohassa ei välttämättä näy kaikki kuvissa näkyvät kentät.

![](/assets/files/docs/Asiakkaat/Asiakkaantiedot.png)

\- Asiakaslajeihin on määritetty ikärajoituksia. Ohjelma tarkistaa
syntymäajan mukaan, voiko asiakas kuulua siihen asiakaslajiin, johon
häntä ollaan tallentamassa. Voit saada tällaisen virheilmoituksen:  
![](/assets/files/docs/Asiakkaat/ikaraja.png)

Osoite-osiossa “Kunta” tarkoittaa käytännössä postitoimipaikkaa, ei
pelkästään kotikuntaa. Englanninkielistä sanaa City ei voi kääntää
postitoimipaikaksi tässä kohti, koska sama sana on kunta-merkityksessä
muussa yhteydessä. Voit valita postinumeron ja postitoimipaikan myös
Kunta-kentän viereistä alasvetovalikosta.

![](/assets/files/docs/Asiakkaat/Osoite.png)

Syötä Yhteystiedot-osiossa asiakkaan puhelinnumero ja sähköpostiosoite.
Sähköpostiosoite on se osoite, johon asiakasviestit lähtevät. Huom!
Puhelinnumero pitää lisätä myös Asiakkaan viestiasetukset-osiossa, jos
asiakas haluaa varausten noutoilmoitukset tekstiviestinä. Kuvan
teksteistä poiketen tiedot eivät näy kuljetuskuitissa.

![](/assets/files/docs/Asiakkaat/Yhteystiedot.png)

\- Huom! Puhelinnumero-kenttään ei saa kirjoittaa muuta kuin
puhelinnumeron. Ei esim. perään äiti, isä yms. eikä väliviivaa.
Kansainvälisen suunnan (esim. +358) numeron yhteyteen voi lisätä.

Asiakkaalle voidaan tallentaa myös vaihtoehtoinen osoite. Huom! Tässä on
kimppakohtaisia eroja.

![](/assets/files/docs/Asiakkaat/koha682.png)

### Takaaja

Jos kyseessä on lapsiasiakas, hänelle pitää tallentaa takaaja. Klikkaa
“Hae takaaja” -nappia, niin pääset hakemaan rekisteristä lapselle
takaajan. Huom! takaajakenttiin kirjoitetut tiedot eivät tallennu.
Takaaja haetaan aina Hae takaaja -toiminnolla.

![](/assets/files/docs/Asiakkaat/Takaajantiedot.PNG)

Takaajaa voi hakea joko nimellä tai kirjastokortin numerolla. Valitse
alasvetovalikoista sopivat vaihtoehdot.

![](/assets/files/docs/Asiakkaat/haetakaaja.png)

Saat listan hakuun sopivista asiakkaista. Valitse oikealta “Valitse”
oikean henkilön kohdalla. Huom! Sulje haku-ikkuna aina käytön jälkeen,
sillä se ei sulkeudu automaattisesti.

![](/assets/files/docs/Asiakkaat/takaaja.PNG)

Huom! Jos takaajaa ei löydy asiakasrekisteristä, avaa uusi välilehti ja
tallenna takaajan tiedot rekisteriin. Palaa sen jälkeen lapsiasiakkaan
tietoihin toisella välilehdelle ja tee takaajahaku uudelleen.

### Kirjastotiedot

_Kirjastonhallinta-osio_ sisältää kirjastonkäyttöön liittyviä tietoja.

![](/assets/files/docs/Asiakkaat/kirjastohallinta.png)

\- Lue asiakkaan kirjastokortin numero ylimmäisenä olevaan
“Kirjastokortin numero” -kenttään.

\- Kirjasto-kenttään valitaan asiakkaan kotikirjasto, jota järjestelmä
ehdottaa mm. varausta tehtäessä noutokirjastoksi.

\- Tyyppi-kohdassa voi vaihtaa asiakastyypin. Huom! Jos tässä kohtaa
vaihtaa asiakastyypin, muutos ei tuo esille mm. takaajatieto-kenttää tai
poista sitä näkyvistä. Tätä ei kannata muuttaa. Aloita mielummin alusta,
jos valitsit alussa väärän asiakastyypin.

\- Valitse asiakasviestien kieli kohdassa “Ilmoitusten kieli”.

_Kirjaston asetukset -osio_

![](/assets/files/docs/Asiakkaat/kirjastonasetukset.png)

\- Tullut asiakkaaksi -päivämäärä tulee automaattisesti kuluvan päivän
mukaiseksi.

\- Vanhentuu -kohtaan ei tarvitse merkitä mitään. Tieto tulee
automaattisesti asiakaslajille tehtyjen määritysten mukaan.

\- Huomautus (näkyy verkkokirjastossa) -kohtaan voi merkitä
huomautuksen, jonka asiakas näkee verkkokirjastosta. Huom! Huomautus
näkyy OPACissa, mutta ei Finnassa.

\- Huomautus (näkyy virkailijatyökalussa) -laatikossa oleva huomautus
näkyy vain virkailijoille lainauksessa.

![](/assets/files/docs/Asiakkaat/huomautus.png)

_Kirjautumistunnus -osioon_ voi lukea esim. kirjastokortin numeron tai
erillisen käyttäjätunnuksen, jolla asiakas voi kirjautua
verkkokirjastoon. Huom! Kimppakohtaisia eroja.

![](/assets/files/docs/Asiakkaat/kirjautumistunnus.png)

_Muut määritteet ja tunnukset_

Tähän tulee mm. sotu-avain ja OUTI-kimpalla tässä asetetaan
omatoimikirjaston käyttöesto. Myös muita kimppakohtaisia määritteitä voi
olla käytössä.

![](/assets/files/docs/Asiakkaat/muutmaareetjatunnukset.PNG) ![](/assets/files/docs/Asiakkaat/Omatoimiesto.PNG)

![](/assets/files/docs/Asiakkaat/koha680.png)

### Asiakkaan viestiasetukset

Lopuksi vielä tallennetaan asiakkaan viestiasetukset. Käytettävissä
olevat viestivaihtoehdot vaihtelevat kimpoittain.

![](/assets/files/docs/Asiakkaat/viestiasetukset.png)

\- Eräpäiväilmoitus: Ilmoitus lainojen erääntymisestä eräpäivänä.

\- Ennakkoilmoitus: Etukäteisilmoitus lähestyvästä eräpäivästä (Asiakas
voi valita, montako päivää etukäteen ilmoitus tulee). HUOM! Jos tähän
valitsee 0, ei viestiä lähetetä, vaikka rasti olisi paikallaan.

\- Saapumisilmoitus: Ilmoitus asiakkaalle noudettavissa olevasta
varauksesta.

\- Palautuskuitti: Lista asiakkaan juuri palauttamasta aineistosta.

- Lainauskuitti: Lista asiakkaan juuri lainaamista niteistä. Tämä on
  sähköinen versio lainauskuitista.

\- Lisää puhelinnumero “Tekstiviesti numeroon” -kenttään, jotta
tekstiviestit lähetetään. Testiviesti-vaihtoehtoon ei voi laittaa
rastia, jos tässä kentässä ei ole puhelinnumeroa.

- SMS-palveluntuottaja-kohtaan ei tarvitse valita mitään. Ominaisuus ei
  ole käytössä.

Tärkeää

\- Nämä asetukset kumoavat asiakaslajeihin tehdyt oletusvalinnat.

\- Asiakas voi itse muuttaa näitä asetuksia verkkokirjastossa.

- Valitse koosteilmoitus ennakkoilmoitukseen ja eräpäiväilmoitukseen,
  niin asiakas saa yhdessä viestissä kaikkien erääntyvien niteiden tiedot
  eikä jokaisesta lainasta erillistä viestiä!

Lopuksi tallenna tiedot.

Jos järjestelmä epäilee, että olet tekemässä tupla-asiakkaan, saat siitä
huomautuksen. Jos olet varma, että kyseessä ei ole kopio, valitse “Ei
kopio. Tallenna uutena tietueena”.

![](/assets/files/docs/Asiakkaat/kopio.png)

---

## 1.2 Ei-tilastoitavat-lainat

Tämä asiakastyyppi on luotu sellaisille lainoille, joita henkilökunta
tekee työtarkoitusta varten. Huom! Voi olla kimppakohtaisia eroja
asiakastyypin nimessä sekä käytännöissä. Tämän asiakastyypin lainoja ei
oteta mukaan tilastoihin.

![](/assets/files/docs/Asiakkaat/eitilastoituvat.png)

## 1.3 Asiakkaan tietojen kopioiminen

Joissakin tilanteissa on tarpeen käyttää asiakastietojen kopioimista,
esim. saman perheen jäsenille tehdään useita kortteja. Kohassa on
toiminto, jolla voidaan kopioida henkilötiedot, jotka toistuvat eri
tietueissa.

Avaa sen asiakkaan tiedot, jonka haluat kopioida ja klikkaa
Kopioi-nappia tietueen yläreunassa.

![](/assets/files/docs/Asiakkaat/kopioiasiakastiedot.png)

Sukunimi, osoite, sähköpostiosoite, kirjasto, asiakastyyppi sekä
sotuavain (avain päivittyy, kun hakee tallennettavan asiakkaan sotun)
kopioituvat lomakkeeseen. Lisää puuttuvat tiedot ja klikkaa Tallenna.

Tallennuksen jälkeen pääset uuden asiakkaan tietoihin.

## 1.4 Asiakkaan tietojen muokkaaminen

Asiakkaan tietoja voidaan muokata eri painikkeiden kautta.

Koko asiakastietueen muokkaukseen pääset yksinkertaisesti klikkaamalla
Muokkaa-painiketta asiakastietojen yläreunassa.

![](/assets/files/docs/Asiakkaat/muokkaanappi.png)!

### Salasanan vaihtaminen

Asiakkaan salasanaa ei voi nähdä. Asiakastiedoissa salasanan korvaavat
tähdet ovat aina näkyvissä, vaikka salasanaa ei olisikaan tallennettu.
Jos asiakas unohtaa salasanansa, hänelle pitää tallentaa uusi salasana.
Salasanan voi uusia Vaihda salasana-napista. Ks. kuva yllä.

![](/assets/files/docs/Asiakkaat/salasana.png)

\- Koha ei voi näyttää entistä salasanaa. Jätä salasanakenttä tyhjäksi,
jos et halua vaihtaa salasanaa.

\- Jos haluat automaattisesti luodun salasanan, klikkaa “Valitse tästä
luodaksesi satunnaisesti luodun salasanaehdotuksen”. Salasanat näytetään
tekstinä.

- Muista tallentaa.

Muokataksesi jotain tiettyä osiota asiakastiedoissa (esim.
Kirjastotiedot) klikkaa sen osion alla olevaa Muokkaa-linkkiä.

![](/assets/files/docs/Asiakkaat/muokkaanappi2.png)

### Lapsiasiakkaan takaajan vaihtaminen

Mene muokkaamaan lapsen tietoja. Kohdassa Takaajan tiedot klikkaa
“Muuta”.

![](/assets/files/docs/Asiakkaat/muutatakaaja.png)

Hae uuden huoltajan tiedot avautuvassa ikkunassa.

![](/assets/files/docs/Asiakkaat/haetakaaja.png)

Valitse hakutuloksesta huoltaja ja klikkaa Valitse.

![](/assets/files/docs/Asiakkaat/takaaja.PNG)

Lapsen tietoihin on nyt vaihtunut huoltaja. Muuta huoltajan suhde,
mikäli tarpeellista (Huom! Kimppakohtaisia eroja). Muista tallentaa
lapsen tiedot!

![](/assets/files/docs/Asiakkaat/muuttunuttakaaja.png)

### Asiakkaan kuva

Asiakkaan kuva voidaan lisätä valitsemalla kuva koneeltasi Lataa
asiakaskuva -osiossa.

![](/assets/files/docs/Asiakkaat/asiakaskuva.png)

\- Tämä osio ei ole näkyvissä, jos järjestelmäasetuksissa on estetty
kuvien tallentaminen

\- Työkaluissa olevalla toiminnolla Asiakaskuvien lataus voi tuoda
palvelimelle eräajona kuvia

### Rajoitukset

Asiakkaiden käyttöoikeuksia voidaan rajoittaa eri syistä johtuen.

![](/assets/files/docs/Asiakkaat/rajoitteet.PNG)

Jos haluat lainauksen virkailijan tarkistavan asiakkaan osoitteen ennen
lainaamista, laita valinta “Kyllä” päälle Tarkista osoite -kohdassa
Käyttäjätilin huomautuksissa.

![](/assets/files/docs/Asiakkaat/vaaraosoite.png)

Jos asiakas ilmoittaa kadottaneensa kirjastokorttinsa, voit merkitä sen
kadonneksi, niin kukaan ei voi väärinkäyttää korttia.

![](/assets/files/docs/Asiakkaat/kadonnutkortti.png)

Asiakkaalle voi antaa myös vapaamuotoisen rajoitteen. Klikkaa “Lisää
rajoite” ja kirjoita syy.

![](/assets/files/docs/Asiakkaat/liikaavelkaa.png)

Rajoitteet voi ohittaa klikkaamalla “Ohita rajoitus tilapäisesti”.
Toimitaan kirjaston/kimpan ohjeiden mukaan.

Rajoitukselle voi laittaa myös automaattisen päättymisajan. Jos et
määritä päättymisaikaa, on rajoite voimassa toistaiseksi.  
Päivämäärä ei näy lainausnäytöllä, kun rajoitteita on enemmän kuin yksi.

![](/assets/files/docs/Asiakkaat/rajoitteenvoimassaoloaika.png)

Kimppakohtaisia määritteitä/rajoitteita voi olla käytössä “Muut määreet
ja tunnukset”-kohdassa.

![](/assets/files/docs/Asiakkaat/omatoimirajoite.png)

Asiakastilin vanheneminen on myös eräänlainen rajoite. Huom!
Kimppakohtaisia eroja.  
Rajoite poistuu, kun tili uusitaan lainausnäytöllä olevasta linkistä
“Uusinta” tai Muita toimintoja- alasvetovalikosta “Asiakkaan
käyttöoikeuden jatkaminen”.

![](/assets/files/docs/Asiakkaat/tilinvanh.png)

### Lapsiasiakas aikuisasiakkaaksi

Lapsiasiakkaasta ei tule automaattisesti aikuista ellei Kohassa ole
siihen liittyvä ajo käynnissä. Lapsen voi muuttaa aikuiseksi Asiakkaan
tiedot -näytöllä valitsemalla Muita toimintoja -valikosta “Päivitä lapsi
aikuiseksi”.

![](/assets/files/docs/Asiakkaat/lapsiaikuiseksi.png)

## 1.5 Asiakkaiden kommenttien ja muutospyyntöjen käsittely

Jos järjestelmäasetuksissa annetaan asiakkaille oikeus muuttaa tietojaan
verkkokirjaston kautta, täytyy muutokset hyväksyä virkailijaliittymän
kautta ennen niiden voimaantuloa. Jos järjestelmässä on hyväksymistä
odottavia muutoksia, niistä näkyy ilmoitus Kohan etusivulla valikoiden
alla (muutaman muun toimenpidettä odottavan toiminnon kanssa).

![](/assets/files/docs/Asiakkaat/odottavatieto.png)

Kun klikkaat Tietojensa muokkaamista haluavat asiakkaat -linkkiä, saat
listan asiakkaan tekemistä muutoksista.

![](/assets/files/docs/Asiakkaat/tietojenmuutos.png)

Linkistä pääset katsomaan asiakkaan tiedoista mm. onko asiakkaalla
rajoitteita, jotka päivityksen yhteydessä on syytä ottaa pois.

## 1.6 Asiakkaan tiedot

Kun katsot asiakkaan tietuetta, on vasemmassa reunassa valittavissa
useita eri välilehtiä, joilla on erilaisia tietoja.

![](/assets/files/docs/Asiakkaat/vasen.png)

### Tiedot

Kaikki asiakkaan (henkilö)tiedot näkyvät Tiedot-välilehdellä. Täällä on
yhteystiedot, huomautukset, asiakkaan viestiasetukset ym.

Jos asiakas on lapsi, hänen takaajansa nimi on linkkinä tietueessa.

Lapsiasiakkaalla näkyy Takaajan nimi linkkinä  
![](/assets/files/docs/Asiakkaat/takaajatie.png)

Takaajan tietueessa näkyy kaikkien huollettavien tiedot  
![](/assets/files/docs/Asiakkaat/huollettavat.png)

### 1.6.1 Lainat

Asiakkaan tietojen alapuolella on taulukkonäkymässä asiakkaan lainat,
maksut, varaukset ja rajoitukset. Lainoihin pääsee klikkaamalla
“Lainassa”-painiketta.

![](/assets/files/docs/Asiakkaat/lainat.png)

Tällä näytöllä näkyy myös asiakkaan huollettavien lainat Perheen lainat
-välilehdellä. Näkymässä näkyy myös huollettavalla perheen sisarusten
lainat eli niiden henkilöiden lainat, joilla on sama takaaja.

![](/assets/files/docs/Asiakkaat/perheenlainat.png)

### 1.6.2 Maksut

Asiakkaan maksuhistoria näkyy maksuissa Tili-välilehdellä. Siellä näkyy
myöhästymismaksujen lisäksi myös muut kirjatut maksut, esim.
kirjastokortin uusiminen, noutamattoman varauksen maksut jne.

![](/assets/files/docs/Asiakkaat/tili.png)

Tällä näytöllä on seuraavat sarakkeet:

\- _Pvm:_ päiväys, jolloin maksu luotiin

\- _Maksutapahtuman numero_ kertoo millä numerolla tapahtuma löytyy
kassaohjelmasta.

\- _Maksun kuvaus:_ tieto mistä niteestä maksu muodostuu ja myöhästyneen
niteen eräpäivä sekä linkki nidetietoon

\- _Huomautus:_ tähän tulee maksuun liittyvä huomautus

\- _Summa:_ maksettavien maksujen kokonaissumma

- _Maksettavaa:_ vielä maksamatta oleva määrä

#### Maksujen maksaminen/poistaminen rivi kerrallaan

Jokaisen rivin maksu voidaan maksaa tai poistaa erikseen klikkaamalla
rivillä joko Maksa tai Poista. Maksu voidaan maksaa kokonaan tai
osittain.

![](/assets/files/docs/Asiakkaat/maksurivi.png)

Maksun maksaminen riviltä kokonaan

\- Valitse Maksa sen maksun kohdalla, mikä maksetaan

- Maksun summa tulee Peri asiakkaalta: -laatikkoon

![](/assets/files/docs/Asiakkaat/periasiakkaalta.png)

\- Klikkaa Hyväksy

- Maksu poistuu maksamattomista maksuista ja näkyy kokonaan maksettuna.

Maksun maksaminen riviltä osittain

\- Valitse Maksa sen maksun kodalla, mikä maksetaan.

- Muokkaa summaa, joka tulee Peri asiakkaalta-laatikkoon. Hyväksy.

![](/assets/files/docs/Asiakkaat/osamaksu2.png)

\- Loput maksusta jää Maksettava- sarakkeeseen Maksa
maksuja-välilehdelle.

Maksun poistaminen riviltä

\- Klikkaa Poista sen maksun kohdalta, joka poistetaan. Jatka
valitsemalla Poista tämä maksu.

![](/assets/files/docs/Asiakkaat/poistamaksu2.png)

Maksu siirtyy Maksa maksuja-välilehdeltä Tili-välilehdelle.

![](/assets/files/docs/Asiakkaat/poistettu2.png)

#### Maksa kaikki tai jokin tietty summa maksuista

Maksa kaikki

\- Klikkaa Maksa kaikki -nappia.

![](/assets/files/docs/Asiakkaat/maksa1.png)

\- Klikkaa Hyväksy

Maksa tietty summa maksuista

\- Klikkaa Maksa kaikki -nappia.

- Kirjoita Peri asiakkaalta -laatikkoon asiakkaalta perimäsi rahamäärä.
  Kokonaisvelka näkyy Saatavia yhteensä -kohdassa.

![](/assets/files/docs/Asiakkaat/maksa2.png)

\- Klikkaa Hyväksy.

\- Maksu päivittyy kuittaamaan vanhimmat maksut ensin.

#### Maksa valitut maksut

\- Laita valintamerkki niiden maksujen kohdalle, jotka maksetaan,
klikkaa Maksa valitut.

![](/assets/files/docs/Asiakkaat/maksa3.png)

Valittujen maksujen summa näkyy Peri asiakkaalta -laatikossa.

![](/assets/files/docs/Asiakkaat/maksa4.png)

\- Klikkaa Hyväksy

- Maksu päivittyy kuittaamaan valitun maksun.

#### Poista kaikki maksut

Klikkaa Poista kaikki maksut -nappia listauksen alapuolella

![](/assets/files/docs/Asiakkaat/maksa5.png)

\- Kaikki maksut poistuvat saatavista ja näkyvät poistettuina maksuina

#### Maksun peruminen

Jos vahingossa merkitset niteen maksun maksetuksi, voit kumota maksun
klikkaamalla Toiminnot-sarakkeessa Peruuta.

![](/assets/files/docs/Asiakkaat/maksa6.png)

\- Klikkauksen jälkeen tulee uusi rivi, jossa näkyy maksun peruutus

![](/assets/files/docs/Asiakkaat/maksa7.png)

Peruutuksen voi vielä perua klikkaamalla uudelleen “Peruuta”.

HOX HOX!!Jos kirjastossa on käytössä kassajärjestelmä, joka on
yhteydessä kirjastojärjestelmään, ohje löytyy kohdasta 4.8.3.6. KORJAA
TÄMÄ

#### Maksun luominen

Sellaisia maksuja, joita järjestelmä ei tee automaattisesti, voi
virkailija tallentaa Lisää maksu -välilehdellä.

![](/assets/files/docs/Asiakkaat/lisaamaksu.png)

\- Valitse ensin maksun tyypppi

- Jos maksu liittyy johonkin niteeseen, voit lisätä sen viivakoodin
  linkiksi niteeseen

Kuvaus-kenttään voi antaa maksun kuvauksen

![](/assets/files/docs/Asiakkaat/maksunkuvaus.png)

Summa-kenttäään annetaan pelkästään maksun määrä (vain numeroita ja
desimaaleja). Tallennuksen jälkeen maksu näkyy yhteenvedossa.

![](/assets/files/docs/Asiakkaat/maksunsumma.png)

#### Hyvitysten luominen

Tämä toiminto luo asiakkaalle saldoon “plussasaldoa”. Hyvitystä voidaan
käyttää maksujen maksamiseen tai maksun anteeksiantoon. HUOM! Tarkista
ensin kirjastosi käytäntö plussasaldon lisäämisestä asiakkaalle. Tämän
käyttäminen ei ole sallittua mm. OUTI-kirjastoissa.

![](/assets/files/docs/Asiakkaat/hyvitys.png)

\- Valitse ensin hyvityksen tyyppi

\- Jos maksu liittyy johonkin tiettyyn niteeseen, lue niteen viivakoodi
Viivakoodi-kenttään

\- Kuvaus-kenttään voit kirjoittaa selityksen

- Anna Summa-kenttään vain numeroita ja desimaaleja, ei
  valuuttamerkkejä.

#### Maksujen tulostaminen

Jokaisen maksurivin lopussa on Tulosta-linkki. Klikkaamalla tästä
linkistä saat tulostettua niteen nimeke- ja maksutiedot sekä tilin
kokonaissaldon.

![](/assets/files/docs/Asiakkaat/maksujentulostus.png)

#### Maksujen maksaminen Ceepos-kassaliittymän kautta

##### Valmistelut ennen maksujen vastaanottoa

Avaa Kohassa asiakkaan Maksa maksuja-välilehti. Valitse sieltä ne
maksut, jotka asiakas maksaa ja klikkaa joko Maksa kaikki tai Maksa
valitut.

![](/assets/files/docs/Asiakkaat/maksamaksuja2.png)

Jos toimipistekoodia ei ole näkyvissä, klikkaa Lisää toimipiste.

![](/assets/files/docs/Asiakkaat/lisäätoimipiste.png)

Toimipiste on sama kuin kassan numero. Jos kirjastossa on useampi kassa,
tulee tähän toimipistekoodi.

![](/assets/files/docs/Asiakkaat/lisäätoimipiste2.png)

![](/assets/files/docs/Asiakkaat/lisäätoimipiste3.png)

Kun toimipiste on valittu, se näkyy näytöllä. Toimipiste näkyy niin
kauan kuin evästeitä (cookies) ei tyhjennetä. Jos evästeet poistetaan,
pitää toimipiste lisätä uudelleen.

![](/assets/files/docs/Asiakkaat/lisäätoimipiste4.png)

##### Maksun lähettäminen kassaohjelmaan

Kun klikkaat toimipisteen numeroa, se muuttuu vihreäksi ja tieto siirtyy
kassaan.

![](/assets/files/docs/Asiakkaat/ceepos6.png)

Odota, että kassajärjestelmä käsittelee maksun. Se ilmenee siten, että
näytölle ilmestyy keltainen pyörivä ympyrä. Voit siirtyä Ceeposiin ja
veloittaa asiakkaalta maksun. Toimi kirjaston Ceepos-ohjeiden mukaisesti
ja palaa sitten takaisin Kohaan, jossa asiakkaan maksut ovat
automaattisesti merkitty suoritetuiksi.

##### Näkymä Kohan Maksut-osiossa

Kohassa asiakkaan Tili-välilehdellä näkyy maksutapahtuman numero. Muista
aina varmistaa, että maksusta on ilmestynyt yksi uusi maksurivi maksun
tapahtumanumerolla, ja että maksurivillä maksettu summa on oikein.

![](/assets/files/docs/Asiakkaat/testimaksu.png)

Kun klikkaat maksutapahtuman rivillä, se maalaa siihen maksutapahtumaan
liittyvät rivit.

![](/assets/files/docs/Asiakkaat/testimaksu2.png)

Ongelmatilanteissa ota yhteyttä joko oman kirjaston/kimpan Koha-tukeen
tai kirjastosi Ceepos-ohjelman pääkäyttäjään.

### 1.6.3 Kiertolistat

Kiertolistat tarkoittaa lehtikiertolistaa eli jos kirjaston työntekijä
on jonkun lehden sisäisellä kiertolistalla.

![](/assets/files/docs/Asiakkaat/lehtikierto1.png)  
![](/assets/files/docs/Asiakkaat/lehtikierto2.png)

### 1.6.4 Muutosloki

Muutoslokille kertyy tietoa, kun asiakkaan tietoja on katsottu tai
muokattu ja jos asiakastieto on tullut asiakashaussa hakutuloslistalle.
Täällä näkyvät myös lainaus- ja palautustapahtumat, jos niin on
asetuksissa määritetty.

![](/assets/files/docs/Asiakkaat/lokitiedot.png)

\- _Pvm-sarake_ kertoo tarkan ajan (päivämäärä ja kellonaika), jolloin
asiakkaan tiedoissa on tapahtunut jotain

\- _Virkailija-sarake_ näyttää sen työntekijän tunnuksen, joka tietoja
on katsellut tai tehnyt muutokset/haun (virkailijan nimi ja
borrowernumber)

\- _Osio-sarake_ näyttää missä Kohan osiossa katselu/muutos on
tapahtunut

\- _Toiminto-sarakkeesta_ näkee mitä asiakkaan tiedoissa on tehty

\- _ID-tunnus-sarakkeessa_ näkyy, kenen asiakkaan tietoja on muutettu
(asiakkaan nimi ja borrowernumber)

\- _Tiedot-sarake_ kertoo tarkemmin mitä tapahtuma koskee esim. mikä
nide on lainattu tai asiakkaan kirjautuminen automaatille

- _Käyttöliittymä-sarakkeesta_ näkee onko loki kertynyt
  virkailijaliittymästä (intranet), Kohan verkkokirjastosta tai Finnasta
  (opac) tai palautus-/lainausautomaatilta (sip, opac). Rest-merkintä
  tulee silloin, kun asiakkaan tietoihin on otettu yhteyttä restin kautta
  esim. Ceepos ja Ellibs.

### 1.6.5 Ilmoitukset

Tällä näytöllä näkyy asiakkaalle lähteneet tai lähtemässä olevat
ilmoitukset. Ilmoittamistapa valitaan asiakastiedoissa asiakkaan
viestiasetuksissa.

<img src="Lahetetytilmoitukset.PNG" title="Kuvakaappaus Ilmoitukset-välilehdeltä" alt="Kuvakaappaus Ilmoitukset-välilehdeltä" style="width:65.0%" />

\- _Ilmoitus_-sarakkeessa näkyy viestin otsikko. Klikkaamalla viestin
nimeä pääset näkemään koko viestin.

\- _Tyyppi_-sarakkeessa näkyy, missä muodossa viesti on lähetetty.
Koha-Suomessa käytössä: printti, sms, sposti, suomi.fi

\- _Tila_-sarakkeesta näkee viestin lähetyksen tilan  
lähetetty: viesti on lähetetty eteenpäin järjestelmästä varsinaiseen
lähettävään järjestelmään  
odottaa: viestiä ei ole vielä lähetetty eteenpäin lähettävään
järjestelmään  
\\**\\** epäonnistunut: viestin lähetys on epäonnistunut. Osa
lähettävistä järjestelmistä (esim. tekstiviestioperaattorit) palauttaa
Kohaan epäonnistumisen syyn, jolloin se näkyy
Toimitushuomautus-sarakkeessa.

\- _Aika_-sarakkeessa näkyy viestin lähetysaika. Tieto päivittyy aina,
kun viestiä yritetään lähettää uudelleen eli kyse ei ole viestin
luontiajankohdasta.

- _Toimitushuomautus_-sarakkeeseen tulee näkyviin viestin lähetyksen
  epäonnistumisen syy, jos Koha saa siitä tiedon. Lähinnä
  tekstiviestioperaattorit palauttavat virheen syyn.  
  _Message is duplicate_ tarkoittaa, että Koha on hylännyt viestin, koska
  se on täsmälleen samanlainen kuin hiljattain lähetetty toinen viesti.
  Näitä näkyy erityisesti tekstiviestien yhteydessä.  
  _Message validity period has expired_ tarkoittaa, että viestiä on
  yritetty lähettää maksimimäärä kertoja.  
  _Unknown error_ tarkoittaa, että viestin epäonnistumisen syytä ei
  tiedetä tai pystytä tarkentamaan. Syy voi olla esim. asiakkaan
  puhelinnumero voi olla väärä tai hänen puhelimensa ei ota vastaan
  tekstiviestejä, tai operaattorin päässä on häiriö.  
  _Recipient is temporarily unreachable_ tarkoittaa, että vastaanottajaan
  ei ole saatu yhteyttä  
  \\**\\** _ERROR 4 2 messages failed: Unallowed recipient phone number_
  tarkoittaa, että asiakkaan puhelinnumerossa on jotain vikaa tai se on
  väärässä muodossa (esim. lankapuhelin)

### 1.6.6 Tilastot

Tilastot-osiossa näkyy asiakkaan lainatilasto edelliseltä ja kuluvalta
päivältä. Lainat on jaoteltuna aineistolajeittain ja hyllypaikoittain.
Taulukossa näkyy myös kuluvan päivän palautukset ja lainat.

![](/assets/files/docs/Asiakkaat/asiakkaantilastot.png)

### 1.6.7 Hankintaehdotukset

Jos asiakas on tehnyt verkkokirjastossa hankintaehdotuksia, ne näkyvät
asiakkaan tiedoissa Hankintaehdotukset-osiossa.

![](/assets/files/docs/Asiakkaat/hankintaehdotukset.png)

Samalla sivulla voi myös tehdä asiakkaan puolesta hankintaehdotuksen.
Paina “Uusi hankintaehdotus” -nappia, jolloin avautuu lomake. Täytä
vähintään punaisella merkityt pakolliset tiedot ja paina sitten
lomakkeen alareunasta “Lähetä ehdotuksesi”.

![](/assets/files/docs/Asiakkaat/teeuusihankintaehdotus.png)

![](/assets/files/docs/Asiakkaat/teeuusihankintaehdotus2.png)

## 1.7. Asiakkaan hakeminen

Klikkaamalla linkkiä Asiakkaat saat hakulaatikon, jossa voit selata tai
hakea asiakkaiden tietoja. Haku toimii millä tahansa nimen osalla tai
kortin numerolla.

![](/assets/files/docs/Asiakkaat/haeasiakkaita.png)

Klikkaamalla pientä plus-merkkiä \[+\] hakulaatikon oikealla puolella
saat lisää hakuominaisuuksia käyttöösi. Täällä voit mm. rajata hakusi
kirjastoittain tai asiakaslajeittain.

![](/assets/files/docs/Asiakkaat/plushaku.png)

Hakukenttiin tekemiesi valintojen perusteella voit hakea asiakasta eri
tavoin.

![](/assets/files/docs/Asiakkaat/hakukentät.png)

\- Perushaku:  
Anna asiakkaan nimi tai nimen osa, käyttäjätunnus tai kirjastokortin
viivakoodi.

\- Sukunimi:  
Anna asiakkaan sukunimi tai sukunimen osa.

\- Sähköposti:  
Anna mikä tahansa osa sähköpostiosoitteesta ja valitse hakutyypiksi
_sisältää_ (ei alkaa)

\- Asiakkaan ID:  
Anna Kohan Asiakkaan ID-numero (eri kuin kirjastokortti)

\- Käyttäjätunnus:  
Anna asiakkaan kirjastokortin numero tai osa siitä.

\- Puhelinnumero:  
Anna puhelinnumero kokonaisuudessaan kuten se on syötetty järjestelmään
tai käytä tyhjää merkkiä numeroiden jaksotteluun. Esim. Haettaessa
numeroa (013) 267 6200 voit kirjoittaa sen juuri samalla tavalla tai
muodossa 013 267 6200.

\- Katuosoite:  
Anna mikä tahansa asiakkaan osoitteen osa (kaikki osoitekentät
huomioiden) ja valitse hakutyypiksi _sisältää_.

\- Syntymäaika:  
Ohjeteksti ilmestyy kertomaan missä muodossa syntymäaika pitää antaa.
Muoto PP.KK.VVV tarkoittaa, että päivät, kuukausi ja vuosi erotetaan
toisistaan pisteellä.

Voit myös valita jokaisessa haussa hakutyypin alkaa tai sisältää.
Valinta sisältää toimii vapaasanahaun kaltaisesti eli haettu merkkijono
voi olla missä tahansa kohdassa hakukentässä.

![](/assets/files/docs/Asiakkaat/syntymäpäivä.png)

Voit myös selata asiakkaita sukunimen ensimmäisen kirjaimen mukaan
linkkinä olevien kirjainten mukaan.

![](/assets/files/docs/Asiakkaat/aastaoohon.png)
