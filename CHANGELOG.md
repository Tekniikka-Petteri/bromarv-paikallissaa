# Muutosloki

## Versio 58 – 24.8.2026
- Lisätty erillinen **Mitatut merihavainnot** -kortti.
- Hanko Pikku Kolalahti, FMI mareografi (FMISID 134253): merivedenkorkeus N2000-järjestelmässä ja meriveden lämpötila.
- Hanko Längden, FMI aaltopoiju (FMISID 654900): merkitsevä aallonkorkeus, aallon suunta, aallon jakso ja meriveden lämpötila.
- Mitatut FMI-havainnot näytetään erillään Open-Meteon Bromarvin malliennusteesta.
- FMI-havaintohaku on fail-open: virhe, aikakatkaisu tai puuttuva data ei vaikuta sääennusteeseen, paikalliseen saderiskiin, ukkosriskiin, sadetutkaan eikä muuhun sivuun.
- Onnistuneet FMI-havainnot tallennetaan paikalliseen välimuistiin enintään kuudeksi tunniksi.
- Yli 60 min vanha mareografihavainto ja yli 90 min vanha poijuhavainto merkitään vanhaksi.
- Käyttöliittymän suomen- ja ruotsinkieliset tekstit päivitetty v58:aan.
- Kaikki v57:n ominaisuudet säilytetty.
