# Bromarvin paikallissää – Versio 61 – 1.9.2026

- Nykyinen 8 tunnin tuntiennuste säilytetty ennallaan.
- Lisätty erillinen 3 vuorokauden ennuste: huominen + kaksi seuraavaa päivää.
- Näytetään päivän minimi- ja maksimilämpötila, säätila, suurin saderiski, sademäärä ja voimakkain keskituuli.
- Pidempi ennuste muodostetaan samasta MET Norway Locationforecast -datasta ilman uutta pakollista sääpalvelua.
- MET Norway -välimuistin avain päivitetty, jotta v61 saa riittävän pitkän ennusteaikasarjan heti käyttöön.
- Suomen- ja ruotsinkieliset tekstit lisätty.

# Bromarvin paikallissää – Versio 60

- Automaattinen vuodenaikojen peikkokuvien vaihto: kevät 1.3., kesä 1.6., syksy 1.9., talvi 1.12.
- Päivä- ja yökuvat luetaan assets/Kevat, assets/Kesa, assets/Syksy ja assets/Talvi -kansioista.
- Vaihto perustuu Europe/Helsinki-aikavyöhykkeen kalenteripäivään ja toimii automaattisesti vuodesta toiseen.

# Bromarvin paikallissää v59 – 24.8.2026

- Korjattu FMI-meridatan puuttuvien arvojen käsittely: null/tyhjä ei enää muutu arvoksi 0.0.
- Pikku Kolalahden meriveden lämpötila ei enää näytä 0.0 °C, jos havainto puuttuu.
- FMI-hakuaika laajennettu 8 tuntiin, koska eri merisuureet voivat päivittyä eri aikoina.
- FMI-välimuistin avain uusittu, joten v58:n virheelliset nolla-arvot eivät jää selaimen välimuistiin.
- FMI-merihavainnot ovat edelleen täysin valinnainen kerros eivätkä vaikuta sade- tai ukkosriskin laskentaan.

# Muutosloki

## Versio 60 – 24.8.2026
- Lisätty erillinen **Mitatut merihavainnot** -kortti.
- Hanko Pikku Kolalahti, FMI mareografi (FMISID 134253): merivedenkorkeus N2000-järjestelmässä ja meriveden lämpötila.
- Mitatut FMI-havainnot näytetään erillään Open-Meteon Bromarvin malliennusteesta.
- FMI-havaintohaku on fail-open: virhe, aikakatkaisu tai puuttuva data ei vaikuta sääennusteeseen, paikalliseen saderiskiin, ukkosriskiin, sadetutkaan eikä muuhun sivuun.
- Onnistuneet FMI-havainnot tallennetaan paikalliseen välimuistiin enintään kuudeksi tunniksi.
- Yli 60 min vanha mareografihavainto ja yli 90 min vanha poijuhavainto merkitään vanhaksi.
- Käyttöliittymän suomen- ja ruotsinkieliset tekstit päivitetty v59:aan.
- Kaikki v57:n ominaisuudet säilytetty.

### v61 SEO-viilaus 1.9.2026
- Päivitetty hakukoneotsikko ja meta-kuvaus vastaamaan nykyisiä sääominaisuuksia.
- Lisätty luonnollinen sisältö Bromarvin sää-, väder-, sadetutka-, merisää- ja paikallissää-hakuihin.
- Lisätty Bromarvin Mille- ja Nille-peikot näkyvään sisältöön, kuvan alt-teksteihin ja rakenteiseen dataan.
- Päivitetty Schema.org WebSite/WebPage/WebApplication-tiedot versioon 61.
- Päivitetty sitemap.xml:n lastmod.
