Feladat:
Családi büdzsé
Funkcionális specifikáció:
•	Az alkalmazással a regisztrált felhasználók tudják menedzselni a saját családjuk havi költségvetését
•	A családtagok meg tudják adni a saját havi keresetüket
•	Egy családfő fel tud venni új kategóriákat, amelyekhez aztán havi költséglimitet állíthat be, valamint törölhet is közülük (ilyenkor az oda tartozó havi kiadások az ’Egyéb’ kategóriába kerülnek át)
•	Egy családfő l
•	Minden családtag meg tudja nézni a saját családjához tartozó kategóriák aktuális állapotát, hogy a hónapban mennyi pénz maradt még azokra
•	A családtagok felvehetnek tételeket, hogy mire mennyi pénzt költöttek el (+kategória megadása / egyéb)
    o	Ezek között lehessen keresni is
•	A családtagok kérvényezhetik az egyes limitek megváltoztatását, illetve újak felvételét; ezeket a családfők fogadhatják vagy utasíthatják el
•	A családtagok benyújthatnak pénzköltési igényt a családfőknek tárgy és kategória megadásával
•	Legyen lehetőség regisztrálni:
    o	Új családi csoport létrehozásával
    o	Már meglévő családhoz csatlakozással (ez esetben családi kód megadásával, és az adott család családfőjének jóváhagyásával)
•	Minden funkció csak az érvényes regisztráció után, az egyes családokon belül érhető csak el
•	Egy családfő (családi adminisztrátor) szerkesztheti a családjába tartozó egyének jogkörét
Nem funkcionális követelmények
•	Teljesítmény:
    o	20 felhasználó egyidejű kiszolgálása
•	Biztonság:
    o	Legyen titkosított kommunikáció a szerverrel
    o	Jelszavak titkosított tárolása az adatbázisban
    o	Authentikáció
    o	Authorizáció
•	99% rendelkezésre állás
•	Skálázhatóság: a becsült felhasználószám nem igényli
•	Egyszerű, magától értetődő használhatóság

Szerepkörök
•	Vendég: csak a regisztrálást és bejelentkezést érje el
•	Családfő, avagy családi adminisztrátor:
    o	A család adatait, limitjeit stb módosítani tudó felhasználó
    o	A család összes tagjának összes adatát látja, módosíthatja (kivéve bejelentkezési adatok ofc)
•	Családtag:
    o	Saját tételeket láthatja, újakat adhat hozzá
    o	Kérvényezés limitváltoztatásra, új tétel vásárlásra
    o	Család főbb adatait, limitjeit láthatja

Adatbázistáblák
•	Felhasználók
•	Családok
•	Limitek
•	Tételek
