Oldal készítője: Rutai Tamás

Oldal linkje: https://tomi489.github.io/webfejlesztes/

A weblapom a Tihanyi Hajós Egylet vitorlástáborainak a nem hivatalos oldala. Alapvető információ, képek, és jelentkező felület van benne.

Képeket, és a tábor leírását pár helyen az eredeti weblapról vettem át. (https://www.thesail.hu/)

A javascript kódom az első oldalon található. A funkciója egy visszaszámoló működtetése, ami a nyárig hátralevő napok számát írja ki (ebben az esetben ez az első tábor kezdédének a dátuma).
A dátum dinamikusan van megadva, azaz nem csak a 2024-es nyár elejéig számol vissza, hanem mindig a következő tábor kezdéséig.
Elösször egy stringet hozok létre ami csak a dátum év nélküli részét tartalmazza.
Utána lekérem a mostani dátumot, majd ebből különválasztom az évet, hónapot, és a napot napot, majd átkonvertálom számmá.
Ezután eldöntöm, hogy a tábor kezdésének a dátuma eltele már vagy nem. Ha igen akkor a mai dátum évéhez hozzáadok egyet.
Az így kapott évet átkonvertálom szöveggé, majd összefűzöm a dátum többi részével amit a kód elején definiáltam.
Utána a következő évi táborkezdés dátumából kivonom a mostani dátumot, ez a különbség miliszekundumban van amit napokká konvertálok.
Az így kapott napok számát bizonyos feltételek szerint kiirom más formátumokban a weblapra.

Az egész oldalon a Valera Round fontot használok, ami a google fonts-tól származik.
