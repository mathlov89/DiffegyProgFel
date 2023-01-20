# DiffegyProgFel
Differenciálegyenletek programozási feladatok (BMETE91AM43)

*A tantárgy az alábbi témakörök ismeretére épít: Python programozási nyelv ismerete, közönséges differenciálegyenletek
*A tantárgy szerepe a képzés céljának megvalósításában: TTK Matematika BSc képzés kötelezően választható tárgya
*Az aktuális tárgykövetelmények a követelmények.pdf fájlban találhatók.

## A tantárgy rövid leírása

A tárgy célja a Differenciálegyenletek 1 című tárgy tematikájához kapcsolódó programozási feladatok megoldása révén a hallgatók programozási képességeinek szinten tartása, és egyúttal a Differenciálegyenletek 1 tárgy keretében tanult elméleti anyag mélyebb megértésének elősegítése számítógépes szimulációkon keresztül. A tárgy egyben kitekintést biztosít a kapcsolódó alkalmazásokra és modern szimulációs technikákra is.

## A tárgy részletes tematikája

1. Automatikus differenciálás differenciálgeometriai alkalmazásokkal (autograd, jupyter interact).
 
2. Kezdetiérték problémák numerikus megoldása: SIR, SIS és SEIRS járványterjedési modellek szimulációja (scipy beépített ODE solverek, jupyter interact).

3. Geometriai integrátorok Hamilton rendszerek szimulációjára: a középponti módszer, illetve az explicit, implicit és szimplektikus Euler sémák összehasonlítása a matematikai inga példáján (generátorok Python-ban, egyszerű animáció készítése).

4. Merev egyenletek bemutatása a Robertson reakció példáján: egy explicit és egy implicit séma összehasonlítása, Hibrid dinamikai rendszerek szimulációja: a pattogó labda, Zénón jelenség és Julia solver hívása Python-ból.

5. A paraméterek megváltozásának hatása a megoldásokra. Lokális érzékenységvizsgálat: 2-butén cisz-transz izomereinek egymásba alakulásának tanulmányozása, Bifurkációk: logisztikus növekedési modellel leírt populáció dinamikájának kvalitatív megváltozása túlhalászás hatására. 

6. Diszkrét idejű dinamikai rendszerek: káosz, Lyapunov-exponens, invariáns mérték, fraktál dimenzió, Takens tétele és alkalmazásai (ok-okozati kapcsolat kimutatása, anomália detektálás).

7. Zajjal terhelt dinamikai rendszer állapotbecslése, rendszeridentifikáció: Kálmán szűrő és részecskeszűrők (szekvenciális Monte-Carlo módszerek), ARX modellek, LSTM hálók.

8. Egydimenziós peremérték problémák megoldása: stacionárius hővezetési probléma rúdon (véges differencia módszer), terhelt rúd lehajlásának szimulációja (véges elem módszer), fluidum áram sebességprofiljának szimulációja a határrétegben (Blausius egyenlet, neurális hálók).

9. Sztochasztikus differenciálegyenletekkel (SDE) kapcsolatos kezdetiérték feladatok: numerikus megoldás (Euler-Maruyama séma, Milstein módszer, SDE Runge-Kutta módszer), alkalmazási páldák (sztochasztikus populáció növekedési modell, illetve egy ún. futures contract korrekt árának meghatározása, ahol a kereskedett termék árfolyama mean-reverting tulajdonságot mutat).

10. Sztochasztikus differenciálegyenletek (SDE) és másodrendű lineáris differenciálegyenletekre vonatkozó peremérték feladatok kapcsolata: peremérték probléma megoldása Monte-Carlo eljárással, diffúziós folyamatokkal kapcsolatos kérdések visszavezetése peremérték feladatra.

11. A Langevin sztochasztikus differenciálegyenlet két fontos alkalmazása: előírt eloszlású véletlen vektor generálása (Markov-lánc Monte-Carlo), nemkonvex függvény globális minimumának a megkeresése.

12. Bevezetés a kontinuumok diszkrételemes modellezésébe Python-nal (DEM): a DEM módszer bemutatása egy egyszerűen implementálható példán keresztül, ismerkedés a Yade nyílt forráskódú Python DEM csomaggal. 
