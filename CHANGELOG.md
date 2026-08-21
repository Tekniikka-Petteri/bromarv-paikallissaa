# Bromarvin paikallissää – muutosloki

## Versio 54 – 20.8.2026
- Korjattu Bromarv nyt -kortin asettelu: sääotsikko, lämpötila, sääteksti ja sääikoni ovat kuvan päällä.
- Päiväkuvan rajaus säädetty niin, että MILLE- ja NILLE-nimilaatat pysyvät näkyvissä.
- Lisätty automaattinen päivä-/yökuvan vaihto.
- Yökuvassa peikoilla on yömyssyt.
- Korjattu Seuraavat 8 tuntia -ennusteen 0 % saderiski tilanteessa, jossa MET Norway ennustaa sadetta mutta ei anna erillistä todennäköisyysarvoa.
- Täydelliseen pakettiin lisätty 404.html, favicon.svg, Google-vahvistustiedosto, robots.txt, site.webmanifest, sitemap.xml ja JULKAISUOHJE.txt.
- JSON-LD-metatiedot päivitetty versioon 54.


## v54 testattu korjaus
- Päiväpeikkokuva vaihdettu puhtaaseen versioon.
- Yöpeikkokuva vaihdettu puhtaaseen versioon ilman valmiiksi leivottuja säätietoja.
- Hero-kuvan rajaus säädetty niin, että Mille- ja Nille-nimikyltit näkyvät paremmin.
- Paketissa mukana myös assets-kansio, jotta peikkokuvat näkyvät GitHub Pagesissa sekä paikallisesti.


## v54 – paine-ennusteen korjaus
- Korjattu virhe, jonka vuoksi **Paineen muutos 6 h** näytti jatkuvasti +0.0 hPa.
- MET Norway ei anna tässä haussa kuuden tunnin mennyttä painehistoriaa, joten vanha laskenta vertasi käytännössä nykyarvoa itseensä.
- Kohta on muutettu muotoon **Paine-ennuste 6 h**.
- Arvo lasketaan nyt MET Norwayn seuraavien kuuden tunnin ilmanpaine-ennusteesta.
- Seliteteksti kertoo nyt tulevasta painekehityksestä eikä väitä näyttävänsä mennyttä kuuden tunnin muutosta.
