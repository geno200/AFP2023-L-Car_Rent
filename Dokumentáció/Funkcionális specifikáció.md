# Funkcionális Specifikáció


#### Áttekintés

Megrendelőnk egy gépjárművek bérbeadásával foglalkozó cég, ami eddig csak minimálisan digitalizálta magát, most viszont elérkezettnek látja az időt egy weboldal létrehozására, ahol megoszthatják az adatbázisukban szereplő kibérelhető gépjárműveket, valamint felületet biztosíthatnak a regisztrált felhasználóknak ajánlatok kérésére. 

#### Jelenlegi helyzet leírása

A megrendelő egy gyorsan fejlődő, autóbérléssel foglalkozó cég, ahol rövidebb, illetve hosszabb távra lehet különféle kategóriájú járműveket bérelni. Jelenleg 5 alkalmazottja van a vállalkozásnak:

-négy személy, akik az autókat bemutatják az érdeklődő bérlőknek,

-egy cégvezető, aki az anyagi dolgokkal foglalkozik, kiutalja a fizetéseket, rendszerezi a bevételeket, és pénzügyi terveket készít.

A cég jelenleg még nem rendelkezik weboldallal, de a későbbiekben mindenképp szeretnének létrehozni egy weboldalt a leendő ügyfeleik elérése érdekében. Egyelőre csak egy kis bérelt irodával rendelkeznek, ahonnan 3 autó bérelhető. Kizárólag közösségi oldalakon hirdetik magunkat, reklámra még nem költenek. Az érdeklődőkkel jobbára telefonon, esetleg emailben tartják a kapcsolatot. Az aktuális bérelhető járműveket a közösségi oldalakon, és egy katalógusban lehet megtekinteni a cég irodájában. További érdeklődés esetén a helyszínen meg tudják mutatni az érdeklődőnek az autót, amennyiben az, az adott időpontban nincs más részére bérbe adva. A nyilvántartás egyelőre Excel táblázatban valósul meg, minden személyes és pénzügyi adat ilyen formában van tárolva.

#### Vágyálom rendszer leírása

A vállalkozás bővítése érdekében létre szeretnénk hozni egy weboldalt, ahol bérlőinknek lehetősége nyílik megtekinteni a nyilvántartásunkban szereplő bérelhető járműveket. A weboldal a cégünk által kölcsönözhető autók adatait nyilvántartó adatbázishoz kapcsolódik, mely adatbázis a cég adminisztrációját is támogatná, segítségével az üzlet fejlesztését, teljesítményét mérő riportokat készíthetnénk el. A nyilvántartás online kezelésével nem csak a cégvezetés, de a bérlők is naprakész információhoz juthatnak a bérelhető gépjárművekről. Az adatbázisnak emiatt tárolnia kell a cég működéséhez szükséges adatokat (például: munkatársak adatai), valamint a meghirdetett kölcsönözhető autók adatait is, az autókról feltöltött képpel együtt. 

A weboldal megvalósítása során fontos szempont, hogy könnyen üzemeltethető legyen, ugyanakkor bérlőink is könnyen elérjék, platformfüggetlen legyen, reszponzív felülettel rendelkezzen. A weboldal felépítése során fontos a könnyű áttekinthetőség. 

Cégünk a jövőben lehetőséget szeretne biztosítani arra, hogy bérlők közvetlenül a weboldalon keresztül tudják lefoglalni a bérlendő járművet, illetve hosszabb bérlés esetén, a kedvezményezett árváltozást is ki tudja kalkulálni a honlap. A fizetés is a honlapon keresztül történjen.

#### Követelménylista




#### Használati esetek

A weblapot háromféle szerepkörben lehet használni: látogató (nem regisztrált/bejelentkezett felhasználó), bérlő (bejelentkezett felhasználó), admin (a bérbeadással foglalkozó személyzet). Ezek jogosultságai a következők (aktorok):

Látogató: Szabadon böngészheti a hirdetéseket, szűréseket végezhet a keresővel, kinagyíthatja a fotókat, elolvashatja a Rólunk szekciót, valamint regisztrálhat.

Bérlő: A fentebb felsoroltakon kívül elmenthet magának hirdetéseket, továbbá gépjárművet bérelhet egy külön lapon, mely csak a bejelentkezés után válik láthatóvá. A foglalásait törölheti.

Admin: Admin jogosultsági körrel ruházhat fel felhasználókat, valamint el is veheti ezeket a jogokat, és bármikor törölheti bárkinek az accountját. Bármikor törölhet, illetve módosíthatja a hirdetéseket.  A weboldal szerkesztéséhez is kizárólagos joga van. 

![szkör](https://user-images.githubusercontent.com/83767448/229345673-897bebf2-1157-4a54-aaeb-4becb4496ee4.png)


#### Használati esetek aktorok szerinti bontásban

1.) Látogató regisztráció nélkül böngészi az oldalt: oldal felkeresése -> böngészősáv használata -> lenyíló menük használata -> elérhető ajánlatok listázása -> elérhető ajánlatok listázása megadott feltételek alapján -> elérhető gépjármű kiválasztása, részletek megtekintése -> adott gépjárműhöz mellékelt fotók böngészése -> kapcsolatfelvétel az ügyintézőkkel.

2.) Látogató regisztrál: oldal felkeresése -> menüsávról a regisztráció kiválasztása -> személyes adatok megadása -> elérhetőségek megadása -> hozzájárulási nyilatkozat, használati feltételek elfogadása -> sikeres regisztrációról visszaigazolás

3.) Regisztrált felhasználó gépjárművet bérel: oldal felkeresése -> belépés a személyes profilba -> ajánlat kiválasztása -> a bérlő személyes adatainak megadása -> küldés

4.) Regisztrált felhasználó megnézi saját gépjárműbérléseit: oldal felkeresése -> belépés a személyes profilba -> elfogadott ajánlatok listázása -> részletek megtekintése -> törlés

5.) A személyzet (admin) hirdetéseket módosít: oldal felkeresése -> bejelentkezés a személyes profilba -> feladott hirdetések listázása-> hirdetés adatainak módosítása, törlése -> hirdetéshez bérlőt rendel

6.) Admin: oldal admin felületére belép -> felhasználók jogosultsági körét módosítja



#### Képernyőtervek



#### Forgatókönyvek

