# Muutosloki

## Versio 52 – 14.8.2026
- Liikenteen kelikamerat järjestetään automaattisesti etäisyyden mukaan Bromarvin keskustasta.
- Lähin kelikamera näkyy aina ensimmäisenä.
- Kauimpana oleva kelikamera näkyy viimeisenä.
- Järjestys perustuu jo kortissa käytettävään laskettuun etäisyyteen Bromarvin keskipisteestä.
- Muut ominaisuudet säilytetty ennallaan.
- JavaScriptin syntaksi tarkistettu.

## Versio 51 – 14.8.2026
- Heinänkorjuuarvio nimetty uudelleen: **Heinänteko- ja puintisää**.
- Ruotsinkielinen nimi: **Höskörds- och tröskväder**.
- Kausikortin näkyvyys laajennettu kesäkuusta elokuun loppuun.
- Kortti piilotetaan automaattisesti syyskuusta toukokuuhun.
- Kuivumis- ja painekuvauksia päivitetty huomioimaan sekä heinänteko että puinti.
- Muut ominaisuudet säilytetty ennallaan.
- JavaScriptin syntaksi tarkistettu.

## Versio 50 – 13.8.2026
- UV-indeksi erotettu varsinaisesta MET Norway -säähausta.
- UV haetaan kevyellä Open-Meteo Forecast API -pyynnöllä.
- Käytössä on tuntikohtainen `uv_index`, joka huomioi pilvisyyden, ei `uv_index_clear_sky`.
- Näytetään sekä tämänhetkinen UV-indeksi että päivän maksimi (`uv_index_max`).
- Ihonsuojausohje aktivoituu UV-arvosta 3 alkaen.
- UV-haulle lisätty 60 minuutin välimuisti.
- UV-haun virhe ei vaikuta muihin sää-, meri-, kamera- tai siitepölytietoihin.
- Siitepölyhaku ei enää pyydä turhaan UV-arvoa Air Quality API:sta.
- Suomen- ja ruotsinkieliset UV-tekstit päivitetty.
- JavaScript tarkistettu Node.js:n syntaksitarkistuksella.

## Versio 49 – 6.8.2026
- Jäätymisriski-kohdan nimi muutettu muotoon Tienpinnan jäätymisriski.
- Lisätty selite siitä, että arvio koskee nimenomaan tienpintaa.
- Selitteessä kerrotaan arvion perustuvan kelikameroiden tien lämpötilaan ja tienpinnan tilaan.
- Uudet tekstit lisätty suomeksi ja ruotsiksi.
- Muut ominaisuudet säilytetty ennallaan.

## Versio 48 – 5.8.2026
- Korjattu Olosuhteet nyt -kortin sadeikoni.
- Sade-kortissa käytetään nyt aina sadeikonia.
- Aurinkoikonia ei enää näytetä Sade-kortissa silloin, kun sadetta ei ole.
- Muut ominaisuudet ja kaksikielisyys säilytetty ennallaan.

## Versio 47 – 5.8.2026
- Lisätty Olosuhteet nyt -yhteenvetokortti heti Bromarv nyt -kortin jälkeen.
- Yhteenvetoon lisätty sade ja saderiski.
- Puuskille lisätty värilliset rajat: huomio 12 m/s ja vaara 20 m/s.
- Lisätty kelikameroiden tien lämpötilaan ja tienpinnan tilaan perustuva jäätymisriski.
- Lisätty meriolosuhteiden yhteenveto aallonkorkeuden perusteella.
- Lisätty sää-, merisää- ja kelikameratietojen päivitysajat.
- Ratkaisu käyttää vain sivun nykyisiä tietolähteitä eikä lisää uutta sääpalvelua.
- Uudet suomen- ja ruotsinkieliset tekstit lisätty ja tarkistettu.

## Versio 46 – 5.8.2026
- Palautettu livekameroiden säätilanne kartan punaisten kameramerkkien ponnahdusikkunoihin.
- Livekameroissa näkyvät jälleen sääikoni, lämpötila, tuulen voimakkuus ja nuolella esitettävä tuulensuunta.
- Sää haetaan erikseen jokaisen livekamerapaikan koordinaateilla MET Norway -palvelusta.
- Livekamerasää välimuistitetaan 30 minuutiksi.
- Virhetilanteessa näytetään selkeä ilmoitus säätiedon puuttumisesta.
- Uudet suomen- ja ruotsinkieliset tekstit lisätty ja tarkistettu.

## Versio 45 – 5.8.2026
- Seuraavat 8 tuntia -ennuste siirretty heti Bromarv nyt -kortin jälkeen.
- Kelikameroiden tuuli- ja tien lämpötilat korjattu käyttämään Digitrafficin sensorimetatietoja.
- Sensorit tunnistetaan sensorin ID:n, virallisen nimen ja kuvauksen avulla.
- Kelikamerakortteihin lisätty etäisyys Bromarvin keskustasta.
- Kelikameraosio säilytetty sadetutkan jälkeen ennen veneilijän säätä.
- Uudet suomen- ja ruotsinkieliset tekstit lisätty.

## Versio 44 – 5.8.2026
- Korjattu mobiilin todellinen HTML-järjestys ilman CSS:n `order`-kiertotietä.
- Sivu alkaa Bromarv nyt -kortilla myös iPhonessa ja Safarissa.
- Järjestys on: Bromarv nyt → kartta → sadetutka → liikenteen kelikamerat → veneilijän sää → siitepöly.
- Kelikamerakorteissa näytetään vain Sää nyt: tienpinnan tila, tuuli, ilman lämpötila ja tien lämpötila.
- Kelikamerakuvat ovat ei-klikattavia.
- Kartan violetit kelikameramerkit avaavat Fintrafficin lisätiedot.
- Versionumerot päivitetty kauttaaltaan versioon 44.
- Ruotsinkielisen näkymän uudet tekstit käännetty ja tarkistettu.

## Versio 43 – 5.8.2026
- Lisätty 30 km säteellä olevat liikenteen kelikamerat.
- Kelikamerakuvat haetaan täysikokoisina ja pidetään ei-klikattavina.
- Kartan violetit kelikameramerkit avaavat lisätietolinkin.
- Kelikameraosio sijaitsee sadetutkan jälkeen.
- Sivun rakenne alkaa Bromarv nyt -tiedolla.
- Siitepölyosio sijaitsee veneilijän sään jälkeen.
- Suomen- ja ruotsinkieliset käyttöliittymätekstit tarkistettu.
- Korjattu mobiilijärjestys: kelikamerat ovat sadetutkan jälkeen ennen veneilijän säätä.
- Kelikamerakorteissa näytetään vain Sää nyt: tienpinnan tila, tuuli, ilman lämpötila ja tien lämpötila.
- Muut kelikamerakorttien tekniset tiedot on piilotettu.

