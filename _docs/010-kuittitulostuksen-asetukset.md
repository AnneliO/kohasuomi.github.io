---
title: 'Kohan ohje suomeksi'
permalink: /dokumentaatio/kuittitulostuksen-asetukset/
redirect_from:
  - /theme-setup/
toc: true
---

# 9. Kuittitulostuksen asetukset

Koha-Suomi tukee Firefox ESR-versiota.

## 9.1. Firefoxissa

Avaa selaimen valikko oikeasta yläkulmasta, valitse sieltä Tulosta.

![](/assets/files/docs/Kuittitulostuksen_asetukset/printer1.png)

Mene sivun asetuksiin.  
Muoto ja valinnat -välilehdeltä valitse “Sovita sivun leveyteen”.

![](/assets/files/docs/Kuittitulostuksen_asetukset/tulostin2.png)

Marginaalit ja ylä-/alatunnisteet-välilehdellä muuta kaikki marginaalit
0:ksi ja kaikkiin ylä- ja alatunnisteisiin valitaan —tyhjä—. Tämä
käyttää kaiken tilan kuitin tulostukseen.

![](/assets/files/docs/Kuittitulostuksen_asetukset/tulostin3.png)

Klikkaa lopuksi _OK_.

---

## 9.2 Oletustulostin Firefoxiin

Aseta oletustulostin Firefoxiin, niin et joudu joka kerta valitsemaan
Tulosta-valikosta tulostinta.

Mene vasemmasta yläkulmasta Tulosta-valikkoon.

Valitse käytössä oleva kuittitulostimesi valikosta ja klikkaa
_Ominaisuudet_ tai _Määritykset_ -painiketta, riippuen tulostusikkunan
ulkonäöstä.

![](/assets/files/docs/Kuittitulostuksen_asetukset/printer3.png)

Käy tarkistamassa Asettelu-välilehdeltä, että Paperikoko ja
Tulostuspaperi -asetukset ovat oikein. Toiminnot riippuvat
kuittitulostimen valinnoista.

![](/assets/files/docs/Kuittitulostuksen_asetukset/printer2.png)

Tallenna asetukset valitsemalla _OK_.

Tulosta lopuksi ensimmäinen sivu valitulle tulostimelle painamalla _OK_.

![](/assets/files/docs/Kuittitulostuksen_asetukset/printer4.png)

---

## 9.3 Selaimen määrittely tulostamaan automaattisesti

Mene Firefoxiin. Kirjoita Firefoxin osoiteriville _about:config_. Saat
varoituksen vaarallisesta sivusta, klikkaa _“Otan riskin!”_.

![](/assets/files/docs/Kuittitulostuksen_asetukset/printer5.png)

Kirjoita hakukenttään print.always. Jos ominaisuus
_print.always_print_silent_ löytyy, muuta sen arvoksi true (=kyllä)
klikkaamalla hiiren oikealla painikkeella arvoa false. Valitse valikosta
Vaihda tila.

![](/assets/files/docs/Kuittitulostuksen_asetukset/printer6.png)

Jos tätä ominaisuutta ei löydy (useimmissa selaimissa sitä ei ole
valmiina), lisää tämä ominaisuus:

- klikkaa hiiren oikeaa painiketta ominaisuusalueella ja valitse Uusi
  -&gt; Totuusarvo.

![](/assets/files/docs/Kuittitulostuksen_asetukset/tulostin8.png)

- kirjoita avautuvaan kenttään _print.always_print_silent_ ja
  klikkaa OK. Valitse totuusarvoksi _true_. Tämä muuttaa Firefoxin
  asetuksia siten, että se käyttää aina samoja asetuksia tulostuksessa
  eikä näytä kyselyä tulostamisesta.

VAROITUS  
Näin määritetty print.always_print_silent -asetus estää tulostimen
vaihtamisen Firefoxissa eli jos haluat tulostaa muuta kuin kuitteja,
käytä tulostamiseen toista selainta.

### 9.3.1 Selaimen päivittyessä

Jos Firefox-selain päivittyy, eikä kuittitulostus toimi oikein, tarkista
kuittitulostuksen asetukset. Joskus joutuu myös poistamaan yllä kuvatun
_print.always_print_silent_-määrityksen ja tekemään sen uudelleen.

---

## 9.4 Ponnahdusikkunat

Jos kuitin tulostusvaiheessa tulee ilmoitus, ettei ponnahdusikkunat ole
sallittuja, käy lisäämässä selaimen Tietosuoja ja turvallisuus
-asetuksissa kohtaan “Estä ponnahdusikkunat” poikkeus
kimppasi/kirjastosi Koha-sivustolle.  
![](/assets/files/docs/Kuittitulostuksen_asetukset/ponnahdusikkuna.png)  
![](/assets/files/docs/Kuittitulostuksen_asetukset/sallitut_sivustot.png)
