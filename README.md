1. Projektleírás

A Metal Maze egy Scratch környezetben fejlesztett labirintusjáték, amely metal zenei tematikára épül.

A játékos egy pengető (pick) sprite-ot irányít egy labirintusban, miközben gyűjthető elemeket kell összeszednie meghatározott időn belül, majd el kell érnie a kijáratnál található célobjektumot.

2. Játékmenet

2.1 A játékos feladata:

1 percen belül 5 darab gyűjthető „metal finger” sprite összegyűjtése, ezt követően a labirintus kijáratának elérése és a célként megjelölt "gitár" sprite megérintése. Sikeres teljesítés esetén a játék zenei visszajelzést ad.

2.2 Irányítás

Nyíl billentyűk (↑ ↓ ← →): mozgás a labirintusban.

2.3 Időkorlát

A játék indulásakor egy 60 másodperces visszaszámláló aktiválódik.
Amennyiben az idő lejár, mielőtt a játékos teljesítené a célokat, a játék véget ér.

3. Hangrendszer

A projekt kiemelt eleme a hangalapú visszajelzés:

Gyűjthető sprite érintésekor: gitár akkord hangeffekt kerül lejátszásra.

A célként szolgáló gitár sprite elérésekor: rövid metal zenei részlet szólal meg.

4. Technikai megvalósítás

4.1 Felhasznált sprite-ok

Pengető (játékos karakter)

Metal finger (gyűjthető objektum)

Gitár (célobjektum)

4.2 Főbb funkcionális elemek

Ütközésérzékelés (touch detection)

Időzítő rendszer (visszaszámlálás)

Eseményalapú hangkezelés

Gyűjtési számláló

Játékállapot-kezelés (nyerés / vesztés)
