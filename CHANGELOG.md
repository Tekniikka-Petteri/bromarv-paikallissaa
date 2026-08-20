# Bromarvin paikallissää – muutosloki

## Versio 54 (20.8.2026)

### Korjaukset
- Korjattu Bromarv nyt -kortin asettelu: otsikko, lämpötila, sääteksti ja sääikonin kapseli näkyvät jälleen **kuvan päällä** kuten v53:ssa.
- Korjattu **Seuraavat 8 tuntia** -ennusteen saderiski, jotta se ei jää 0 %:iin silloin kun tuntiennusteessa näkyy sadetta tai sadekuvake.
- Lisätty saderiskille varalogiikka MET Norway -datalle, jos todennäköisyys puuttuu mutta sadetta ennustetaan millimetreinä.

### Uutta
- Lisätty automaattinen **päivä/yö-kuvan vaihto** Bromarv nyt -korttiin.
- Päivällä näytetään normaali Bromarvin satamakuva.
- Yöllä näytetään yökuva, jossa peikoilla on **yömyssyt**.
- Päivä- ja yökuvat toimitetaan paikallisina tiedostoina `assets`-kansiossa.

### Säilytetty ennallaan
- Kartta, sadetutka, meriolosuhteet, siitepöly, livekamerat ja kelikamerat.
- Rakenteen järjestys: Bromarv nyt → Olosuhteet nyt → Seuraavat 8 tuntia → kartta/sadetutka → kelikamerat → veneilijän sää → siitepöly.
