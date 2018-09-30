<h1 align="center" style="border-bottom: none;"> Elmélet-001</h1>
<h3 align="center">Szövegszerkesztők frontend fejlesztéshez</h3>

Frontend fejlesztéshez akár egy egyszerű szövegszerkesztő alkalmazás is használható, mint például a `Notepad` vagy a `TextEdit`, de érdemes pár szempontot igénybe venni:


- **szintaxis kiemelése**: a kulcsszavak, vezérlési szerkezetek, különböző típusú literálok felismerése, és eltérő módon történő megjelenítése színezéssel vagy egyéb tipográfiai módon (kiemeléssel, betűtípusváltással) gyorsabb eligazodást tesz lehetővé a kódban.

- **intelligens behúzások**: a kód olvashatóságát növeli, ha az egymásba ágyazott vezérlési szerkezeteket beljebb kezdjük. Mindenképpen szükséges, hogy egy szerkesztő program támogassa ezt, és ne kelljen minden sort azzal kezdenünk, hogy a megfelelő helyre pozicionáljuk a kurzort. Ugyancsak ide tartozik több sor behúzásának egyszerre történő megváltoztatása, ami megint csak egy tipikus feladat a szerkesztés során, pl. egy kódrészlet elágazás egyik ágába ágyazásakor, vagy onnan kivételekor, vagy egyszerűen másoláskor.

- **blokkok összecsukása és kibontása**: a forráskód sok egymásba ágyazott utasításblokkból állhat. Hasznos lehet ezeket a blokkokat igény szerint összecsukni, hogy jobban átlássuk a forráskód szerkezetét. Ha újra egy blokk részleteire vagyunk kíváncsiak, akkor a blokk kinyitható. Így ezzel nemcsak elágazások, ciklusok, de teljes függvények tehetők egysorossá a megjelenítés szintjén.

- **kódkiegészítés**: több okból is hasznos lehet az, ha a szerkesztő ajánlatokat ad a kód befejezésére. Ilyen eset lehet például egy beépített függvény nevének kiegészítése, vagy saját változók és függvények neveinek felismerése. Ez egyrészt gyorsítja a kódolást, másrészt minimalizálja az elírásokból fakadó hibákat. A JavaScript dinamikus jellege miatt nehéz teljes körű kódkiegészítést adni, de már az is nagy segítség, ha a szerkesztő felajánlja az eddig bevezetett változóneveinket.

- **kóddarabkák**: ugyancsak nagy mértékben növeli a fejlesztés hatékonyságát, ha az állandóan visszatérő szintaxiselemeket egy rövidebb kódrészlet beírásával elő tudjuk hívni. Egy jó szerkesztőben ezekben a kóddarabkákban jelezhető, hogy mely részeit lehet beírás után átírni. Így egészen bonyolult nyelvi formák is gyorsan bevihetők. Érdemes ilyen kóddarabkákat a vezérlési szerkezetekhez írni, mert így gyorsan legenerálhatók a vezérlési szerkezet állandó elemei (zárójelek, utasításblokk, stb), és csak a változó részeket kell átírni. Egy számlálós ciklus például legenerálható a for szócska beírásával, és helyette megjelenik a `for (var i = 0; i < hossz; i++) { ... }` szöveg, ahol az `i`, a hossz tetszőlegesen átírható.

- **debugolási lehetőségek**: végképp hasznos, ha magában a szerkesztőben elvégezhető a kód debugolása, nyomkövetése, változók értékeinek listázása.

- **verziókezelővel való integráció**:


## Szövegszerkesztők:

- [Sublime](https://www.sublimetext.com/)
- [Brackets](http://brackets.io/)
- [Atom](https://atom.io/)
- [Visual Studio Code](https://code.visualstudio.com/)

### Hibrid szerkesztők:

- [Dreamweaver](https://www.adobe.com/hu/products/dreamweaver.html)
- [Webstorm](https://www.jetbrains.com/webstorm/)

### Online szövegszerkesztők:

- [Cloud 9](https://aws.amazon.com/cloud9/?origin=c9io)
- [Codeanywhere](https://codeanywhere.com/)