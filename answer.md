7.

Küsimused:
1. Milline tulemus peaks sellel testil olema, kui kõik töötab korrektselt?
2. Mis juhtub, kui rakendus ei lisa ülesannet nimekirja?

Vastused:
1. Test peab lõppema edukalt (Passed), kuna ülesanne ilmub nimekirja ja toBeVisible() kontroll kinnitab selle nähtavust.
2. Kui ülesanne ei lisandu, ei läbi kontrolli ja test lõpeb veaga (Failed). Playwright näitab, millises etapis tekkis probleem.

1. Mis vahe on manuaalsel ja automaatsel UI-testimisel?

Manuaalse testimise korral kontrollib inimene veebirakendust ise, klõpsates nuppudel ja sisestades andmeid. Automaatse testimise korral teeb seda spetsiaalne programm, näiteks Playwright. Automaatne testimine on kiirem ja võimaldab teste korduvalt käivitada.

2. Mida kontrollib sinu esimene test?

Minu esimene test kontrollib, kas kasutaja saab lisada uue ülesande TodoMVC rakendusse. Test sisestab ülesande tekstiväljale, vajutab Enter-klahvi ja kontrollib, kas ülesanne ilmub ekraanile.

3. Miks kasutatakse Playwrighti testides expect()?

expect() kasutatakse oodatud tulemuse kontrollimiseks. Selle abil saab kontrollida näiteks seda, kas element on nähtav, märkeruut on valitud või ülesanne on lehel olemas.

4. Mida tähendab passed ja mida tähendab failed?
- passed – test läbis edukalt ja oodatud tulemus saavutati.
- failed – test ebaõnnestus ja oodatud tulemust ei saavutatud.
5. Kas ebaõnnestunud test tähendab alati, et veebirakenduses on viga? Selgita.

Ei, ebaõnnestunud test ei tähenda alati, et veebirakenduses on viga. Probleem võib olla ka testikoodis, vales lokaatoris või vales eelduses. Seetõttu tuleb veateade üle kontrollida ja test samm-sammult läbi vaadata.
