# Bromarvin paikallissää – muutosloki

## Versio 54 – siitepöly, näkyvyys ja paine-ennuste korjattu (21.8.2026)

### Korjattu
- Siitepölyosio ei enää käytä vain yhden nykyhetken tuntiarvoa, joka saattoi näyttää illalla kaikki arvot virheellisesti 0.0.
- Siitepölykorteissa näytetään nyt kunkin lajin suurin malliennustettu pitoisuus seuraavan 24 tunnin aikana.
- Siitepölyn välimuistiavain vaihdettiin, jotta vanhat nolla-arvot eivät jää selaimeen.
- Paineen 6 tunnin tieto käyttää MET Norwayn tulevaa aineistoa ja näyttää nyt paine-ennusteen seuraavalle noin 6 tunnille.

### Lisätty
- Veneilijän säähän lisättiin näkyvyys kilometreinä.
- Näkyvyydelle näytetään sanallinen luokka: hyvä, kohtalainen, heikko tai erittäin heikko.
- Alle 5 km näkyvyys huomioidaan Veneilijän sää -kortin varoitustasossa ja alle 1 km näkyvyys nostaa olosuhteet haastaviksi.

### Säilytetty
- Päivä- ja yöpeikot sekä automaattinen päivä/yö-kuvan vaihto.
- Yökuvassa peikoilla on yömyssyt.
- Korjattu 8 tunnin saderiski.
- Kartta, sadetutka, kelikamerat, UV, merisää ja muut nykyiset toiminnot.
