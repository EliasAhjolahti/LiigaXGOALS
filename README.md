# LiigaXGOALS

Selaimessa toimiva sovellus, joka näyttää päivän Liiga-otteluiden maaliodottamat (xG) ja muut tilastot.

## Ominaisuudet

- Päivän kaikki ottelut valittavissa (oletuksena Ässien ottelu). Jos tänään ei pelata, näytetään viimeisin pelipäivä.
- Joukkueiden xG yhteensä ja erittäin, xG-käyrä ottelun kulusta
- Laukauskartta, jossa pallon koko kertoo laukauksen xG:n
- Pelaajien xG ja tilastot kuvineen (lajiteltava taulukko)
- Maalivahtien torjunnat, xG vastaan ja GSAx
- Hover-selitykset jokaiselle tilastolle
- Päivittyy automaattisesti minuutin välein ottelun aikana

## Käyttö

Avaa `index.html` selaimessa. Asennuksia tai palvelinta ei tarvita, koska data haetaan suoraan liiga.fi:n avoimesta rajapinnasta.

Tietyn ottelun saa auki parametrilla `index.html?game=<ottelun id>`.

Data: [liiga.fi](https://liiga.fi)
