-------------------------------------------------
# 1. előadás - Pénztörténet

A pénz általános fogalma: Pénz minden olyan meghatározott értékkel bíró tárgy,
amely a kereskedelmi forgalomban hosszabb-rövidebb ideig, mint állandó fizetési
eszköz használatos, amelynek átadásával dolgokat lehet megvásárolni, illetve
adósságokat törleszteni. Pénz az, amit a piac annak fogad el. Valamint a pénz a
leglikvidebb jószág, ezáltal a csere lebonyolítására a legalkalmasabb eszköz.

A pénz funkciói: 
- Értékmérő
- Forgalmi eszköz
- Fizetési eszköz

<!-- Ezek is? -->
* Csere eszköz
* Elszámolási eszköz
* Fizetési eszköz
* Kincsképző
* Világpénz

A pénztörténet szakaszai:
- Közvetlen árucsere korszaka
- Árupénzek korszaka
- Nemesfémpénz korszaka
- Pénzhelyettesítők korszaka
- Modern pénz korszaka

Csere korszaka:
1. Körülbelül 5000 évvel ezelőtt alakult ki a kereskedelem
2. barter (közvetlen árucsere)
3. Bizonytalan árutermelés

Árupénz korszaka:
- Belső értékkel rendelkező pénzek
- A pénz funkcióit valamely termék töltötte be. Pl.: só, a gabona vagy például a
kagyló

Nemesfémpénz korszaka:
- A pénz funkcióját valamely nemesfém látja el. Pl.: arany, ezüst
- A nemesfémpénz-rendszereknek két formája alakult ki:
  * bimetalizmus
  * monometalizmus

Pénzhelyettesítők korszaka:
- A nemesfémpénz-rendszer termeli ki a pénzhelyettesítőket.
- Ilyen például a kereskedelmi váltó, bankjegy, papírpénz.
- XIX. században vita zajlott az arany-pénzhelyettesítő arányról:
  * Currency-elmélet
  * Banking-elmélet

Modern pénz korszaka:
- A hitelpénz korszaka más néven
- A pénzt a bankrendszer teremti meg

A pénzteremtés módjai:
- Jegybank (készpénz és számlapénz)
- Kereskedelmi bank (számlapénz)

-------------------------------------------------
# 2. előadás - A pénz időértéke

A pénz időértéke azt jelenti, hogy a ma rendelkezésre álló pénzösszeget
magasabbra értékeljük, mint egy későbbi időpontit.

Oka:
- A mai pénzösszeget befektethetjük -> opportunity cost
- Lemondunk a jelenbeli fogyasztásról
- A későbbi pénzbefolyással kapcsolatban a kockázat is megjelenik

Amit vizsgálunk: 
- pénzmozgás
- pénzbeáramlás
- pénzkiáramlás

Egy periódus, egyszerű kamatozás:  
Jövőérték: $FV = C_0 \cdot (1 + r)$ (kamat)  
Jelenérték: $PV = \frac{C_1}{1 + r}$

Több periódus, egyszerű kamatozás:  
Minden évben **csak a tőke kamatozik**, a kamat nem kerül újrabefektetésre.  
Jövőérték: $FV = C_0 \cdot (1 + r \cdot n)$

Több periódus, kamatos kamatozás:  
Jövőérték: $FV = C_0 \cdot (1 + r)^n$  
Jelenérték: $PV = \frac{C_n}{(1 + r)^n}$

Változó nagyságú befizetési sor jelenlegi értéke:  
A vállalati döntések általában állandó intenzitású pénzáramot feltételeznek.
Bizonyos esetekben a pénzáram periódusonkénti kifizetései nem egyenletesek, az
elemzést ezért szükséges kiterjeszteni a változó nagyságú tételekből álló
pénzáramra is.

![[penzugytan___nem_azonos_tagu_penzaramok.excalidraw]]

$r = 5\%$

1. $\frac{10}{1 + 0.05}$
2. $\frac{20}{(1 + 0.05)^2}$
3. $\frac{30}{(1 + 0.05)^3}$

$$
PV = \frac{10}{1 + 0.05} + \frac{20}{(1 + 0.05)^2} + \frac{30}{(1 + 0.05)^3}
$$

Nem azonos tagú pénzáramok: 
Jövőérték:  
$$FV = \sum^n_{i = 1} \frac{C_i}{(1 + r)^i}$$

Nettó jelenérték:  
$$NPV = -C_0 + \sum^n_{i = 1} \frac{C_i}{(1 + r)^i}$$

Az egyedi beruházásra vonatkozó NPV döntési kritérium a következő:  
- A projektbe érdemes beruházni, ha az NPV értéke pozitív.
- Nem érdemes befektetni, ha az NPV negatív.
- Ha az $NPV = 0$, akkor a jelenérték alapján sem elfogadó, sem elutasító döntés
  nem hozható.

## Speciális pénzáramok
Örökjáradék (meghatározott év múlva kezdődő):  
$$
PV = \frac{1}{r} \cdot \frac{1}{(1 + r)^2}
$$

### Annuitás
Az **annuitás** olyan egyenlő tagú pénzáramok (ki- vagy befizetések) sorozatát
jelenti, amely meghatározott ideig esedékes. $n$ éven át tartó, fix összegű
pénzáramlás.
- egyenlő tagú, tehát minden periódusban azonos összeget fizetnek ki (a periódus
  rendszerint egy év vagy egy hónap) 
- meghatározott ideig esedékes, tehát nem a végtelenségig (lásd: örökjáradék)

Jelenértéke: arra ad választ hogy $r\%$ kamatláb mellett $n$ éven át azonos
időközönként esedékes $C$ pénzáramlásnak mennyi a jelenértéke.

Jövőértéke: arra ad választ, hogy $n$ éven át $r\%$ kamatláb mellett esedékes
pénzáramok jövőértéke mennyi. 
- meghatározott időn keresztül esedékes 
- a járadéktag mindig azonos, fix összegű 
- a járadékközök azonos időtartamúak


$$
FV_A = C \cdot \frac{(1 + r)^n - 1}{r}
$$

ahol:
- $FV_A$ az annuitás jövőértéke
- $C$ az éves pénzáram
- $r$ a kamatláb
- $n$ az évek száma

A periódusok elején fizetett annuitás jövőbeli értéke különbözik a normál
annuitástól, mivel az első és utolsó év fizetési tétele is egész éven keresztül
kamatozik. A periódus elején felmerülő annuitás jövőbeli értéke levezethető a
normál annuitás jövőbeli értékéből.

**Növekvő annuitásnak** nevezzük kifizetések vagy bevételek olyan összegekből álló
sorozatát meghatározott időszakra vonatkozóan, amelyek minden
periódusban _konstans arányban növekednek_.  
**Növekvő normál annuitás** esetében a kifizetés vagy bevétel a periódusok
végén, a **növekvő időtartam-annuitásnál** a kifizetési tételek felmerülése a
periódusok elején történik. 

## Elszámolási periódusok és folytonos kamatozás
Az effektív kamat az érvényességi időtartamon belül, a kamatozási periódusok
számának növekedésével nő!

**A végérték koncepciója**  
A nettó végérték (Net Terminal Value – NTV) vagy másként nevezve: nettó jövőbeli
érték ugyancsak alkalmas a projektek elfogadási-elutasítási döntéseinek
megalapozásához. Az NTV a projektélettartam végére vonatkoztatott többletként
fogható fel.

-------------------------------------------------
# 3. előadás -  Államháztartástan

## Alapfogalmak

- **Közszükséglet**: A társadalom részéről javak és szolgáltatások iránt
  megnyilvánuló olyan igény, mely szükséglet csak nehezen bontható le egyéni
  szükségletté. Az államiság és a társadalmi berendezkedés miatt szükségessé váló
  ráfordítások.
- **Közfeladat**: A közszükséglet kielégítése érdekében kifejtett tevékenység, amely
  lehet: - állami
  * önkormányzati
  * non-profit, közhasznú szervezetek  
- **Közkiadás**: A közfeladat megvalósítása folyamán felmerült kifizetések
- **Közbeszerzés**: A közkiadás olyan része, mely törvényben előírt módon
  bonyolódik le.
- **Közpénzügyek**: A közfeladatok ellátása érdekében végzett pénzügyi
  tevékenység.
 
## Közpénzügyek területei

- központi költségvetés
- helyi önkormányzatok
- társadalombiztosítás
- elkülönített állami pénzalapok

## Közpénzügyek irányítása

- központi kormányzat
- helyi hatóságok
- egyéb megbízott szervek 

## Államháztartástan fogalma
1. Az állami bevételek és kiadások összessége
2. Az állam gazdasági tevékenysége. 

## Költségvetési politika
- politikai
- pénzügy-politikai
- ellenőrzési
- gazdaságpolitikai

## Állam gazdasági funkciói
Allokációs:  
  - verseny hiánya
  - externáliák (külső tényezők) léte 
  - piacok komplementaritása
  - információhiány
  - kockázat
  - közjavak léte
  - országos (pl. hadsereg)
  - helyi (pl. közvilágítás)

Elosztási:
  - jövedelmek újraelosztása
  - méltányosság
  - igazságosság
  - hatékonyság

Stabilizációs:
  - csoportérdekek összehangolása
  - többség akaratának megnyilvánulása
  - növekedés, egyensúly
  - foglalkoztatás
  - árstabilizáció

## Államháztartás

- Cél: Államháztartási egyensúly, áttekinthető, hatékony, ellenőrizhető
  gazdálkodás
- Közjavak ellátása: Költségvetési szervek, államháztartáson kívüli szervezetek
- Elvek: 
  * Teljesség elve (minden bevételt és kiadást el kell számolni)
  * Számviteli megalapozottság elve (csak bizonylat alapján)
  * Tartalom elsődlegesség elve (legcélszerűbb elszámolási mód)
  * Következetesség elve (állandóság, összehasonlíthatóság)
  * Bruttó elszámolás elve (bevétel és kiadás egymással szemben nem számolható
    el)

## A magyar államháztartás rendszere
- Gazdasági tevékenység (az állam a társadalmi szükségletek kielégítésére)
- Gazdálkodási rendszer (amelyben a szükségletek kielégítése végbemegy)

## Államháztartás alrendszerei
- központi alrendszer
  * állam
  * központi költségvetés
  * köztestület - irányított köztestület

- önkormányzati alrendszer
  * helyi önkormányzat
  * nemzetiségi önkormányzat
  * a társulás
  * térségi fejlesztési tanács

## Költségvetés
Pénzforgalmi szemléletben tartalmazza a bevételeket és kiadásokat.   
Költségvetési év = naptári év.

### Bevételek különösen
- Közhatalmi bevételek (adók, illetékek, járulék, hozzájárulás, bírság, díj, egyéb)
- Közszolgáltatások ellenértéke
- Támogatások (EU, egyéb)
- Nemzeti vagyon bevételei
- Kapott kamatok

### Kiadások különösen
- Költségvetési szervek működése
- Közfeladatok finanszírozása
- Fizetési kötelezettségek (EU, egyéb nemzetközi)
- Tb-ellátások
- Nemzeti vagyon kiadásai
- Alrendszerek adósságai

## Előirányzat csoportok
- Kiadási előirányzat csoportok:
  * Működési: 
    - Személyi juttatás
    - Járulékok, SZOCHO
    - Dologi kiadás
    - Ellátottak pénzbeli juttatása
    - Egyéb
  * Felhatalmazási:
    - Beruházás, felújítás
    - Egyéb
- Bevételi előirányzat csoportok: 
  * Kiemelt előirányzatokra bontva

Legfontosabb mutatók:
- Kormányzati Pénzügyi Statisztikai Rendszer (GFS, pénzforgalmi szemlélet) (csak
  folyó tételek, tőkemozg. nélkül + priv. bev.+kamat)
- Elsődleges egyenleg: egyenlegek kamatok nélkül
- ESA 2010 szerinti egyenleg: ami az EU stat. Rendszerének megf. számbavételt
  jelent (eredményszemlélet, más bővebb
- az állami részvételi kör pl. MNV Zrt., MÁV Start Zrt.,ÁAK Zrt., MTV Nonprofit
  Zrt.) 

## Költségvetés tervezése és szerkezete
Tervezés alapelvei (13.§):
- Közgazdaságilag megalapozott bevételek, szükséges kiadások tervezhetők
- Csak finanszírozható közfeladatokat lehet tervezni
- Fizetési kötelezettség átvállalásáról az országgyűlés, zárszámadási törvény
  dönt

### Költségvetés előkészítésének folyamata
(A tavaszi költségvetés tervezésekor hamarabb is megtörténhet az egyes lépések
előkészítése.)

| Határidő | Tevékenység |
|----------|-------------|
| Június 30-ig | - Államháztartásért felelős miniszter kidolgozza a tervezés részletes ütemtervét<br> - A fejezetet irányító szervek a kiadott ütemterv alapján megtervezik a bevételeket és kiadásokat |
| Köztes időszakban | - Tárcaegyeztetések, normajavaslatok és fejezeti szöveges indoklások megküldése a Pénzügyminisztériumnak<br> - Törvényjavaslat összeállítása<br> - Államháztartásért felelős miniszter a Kormány elé terjeszti a törvényjavaslatot<br> - A kormány jóváhagyja a törvényjavaslatot |
| Október 15-ig (a választás évében október 30-ig) | - Költségvetési törvényjavaslat megküldése a Költségvetési Tanácsnak véleményezésre (10 napos véleményezési idő, ha Költségvetési Tanács nem ért egyet, akkor a Kormány újra tárgyalja)<br> - Költségvetési törvényjavaslat benyújtása az Országgyűlésnek |

### Helyi önkormányzati költségvetés
#### Tartalma: 
- Bevétel, kiadás, előirányzat csoport, kiemelt önkormányzat
- Költségvetési szervek létszáma
- Egyenlegek (működési és felhalmozási csoportban)
- Pénzmaradványok
- Költségvetési hiány külső és belső finanszírozása
- A költségvetési év azon fejlesztési céljait, amelyek adósságot
  keletkeztetnek és a Stab. Tv. nevesít
- Adósságot keletkeztető ügyletek, az ügyletek futamidejének a végéig, ill. a
  kezesség érvényesíthetőségig a saját bevételek bemutatása a Stab. tv.
  előírásai alapján
- Hatáskörök
- Elkülönítetten az általános tartalék és céltartalék

#### Előkészítés (24.§): 
- A jegyző által előkészített rendelettervezetet február 15-ig nyújtja be a
  polgármester a képviselőtestületnek.
- Átmeneti szabályozásra kerül sor, ha a képviselőtestület március 15-ig nem
  fogadja el a költségvetési rendeletet (25.§)
- Nemzetiségi önkormányzatok, társulások térségi fejlesztési tanácsok
  költségvetése (határozati forma) (26.§)

#### A költségvetés végrehajtásának szabályai
  * A központi költségvetés előirányzat módosítás, átcsoportosítás (31.§)
  * Előirányzat módosítás, átcsoportosítás önkormányzatoknál a képviselőtestület
    döntésével (34.§)
  * Kötelezettségvállalás (36.§), pénzügyi ellenjegyzés (37.§)
  * Teljesítés igazolás, érvényesítés, utalványozás (38.§) (a jogosultakat
    érintő összeférhetetlenség esetei a törvény végrehajtásáról szóló Korm.
    rendeletben találhatók)
  * Költségvetési felügyelő a központi költségvetési fejezeteket irányító
    szervhez (39.§)
  * Rendkívüli intézkedések a központi költségvetés egyenlegének kedvezőtlen
    alakulása miatt (élet-és vagyonbiztonságot veszélyeztető helyzet esetén a
    polgármester jogosult átmeneti intézkedésre) (40.§)

#### A gazdálkodás sajátos szabályai (41.§-47.§)
- Előirányzatok felhasználásának korlátai, bírságbevételek
- Létszám, bér
- Sajátos szabályok
- Vállalkozási tevékenység
- Befizetési kötelezettség

#### Költségvetési támogatások (48.§-56.§)
- Folyósítás
- Beszámolás, visszakövetelés
- Befizetési kötelezettség

#### Az önkormányzati alrendszer támogatása (57.§-60/B.§)
- Támogatások: a helyi önkormányzatok általános működésének és ágazati
  feladatai támogatásainak igénylése
- Évközi felülvizsgálat
- Elszámolás felülvizsgálata

- Hivatali szervezetek (önkormányzati hivatal): (fő)polgármesteri hivatal,
  vármegyei önkormányzati hivatal, közös önkormányzati hivatal, társulási tanács
  munkaszervezete 
- Felelősség: {Mötv. 2011. évi CLXXXIX. Tv. 115. §(1)}:
  * Gazdálkodás biztonságáért: képviselőtestület
  * Szabályszerűségért: polgármester
- Önkormányzati költségvetési szervet alapíthat, gazdasági társaságot hozhat
  létre, társulhat
- A központi kormányzat költségvetéséhez nettó módon kapcsolódik
- Az önkormányzat vagyonnal rendelkezik (a tulajdonából és az őt megillető
  vagyoni értékű jogokból áll, amelyek az önkormányzati feladatok és célok
  ellátását szolgálják)
  1. Törzsvagyon (forgalomképtelen,  korlátozottan forgalomképes)
  2. Üzleti vagyon (forgalomképes {2011. évi CXCVI. tv})

#### Az önkormányzat bevételei:
  1. Saját bevétel (pl. helyi adó, vállalkozás, ingatlanhasznosítás, intézményi
     tevékenység, bérleti díj stb.) Mötv. 2011. évi CLXXXIX tv. 106.§
  2. Felhalmozási bevételek
  3. Támogatások (kapott) (általános működési és ágazati, kiegészítő-,
     rendkívüli önkormányzati támogatások, egyéb)
  4. Átengedett, megosztott központi adók: termőföld bérbeadás
  5. Egyéb
  6. Kötvénykibocsátás, hitel-és kölcsön felvétel (kormányzati hitelengedélyhez
     kötött)

#### Az önkormányzat költségvetésének tervezése
- A képviselő-testület megbízásának időtartamára vagy azt meghaladó időszakra
  szóló gazdasági program
- Költségvetési rendelet tervezet (február 15-ig)-> a költségvetést
  rendeletben (nemzetiségi önkormányzat határozatban) állapítják meg
  (képviselő-testület)

#### Önkormányzati gazdálkodási fő szabályok
- Nem tagja a kincstári körnek: önálló pénzgazdálkodás
- Átcsoportosítás a képviselő-testület jóváhagyásával vagy felhatalmazásával
  (pl. polgármester, bizottság)
- Előirányzat módosítás, ha a végrehajtás nem biztosított
- Végrehajtás a polgármester feladata
- Év végi maradványt a képviselő-testület állapítja meg
- Vállalkozói tevékenység eredményének meghatározott részét (Áht. 46.§ (3)
  bekezdés: a társasági adó általános mértékével megegyező hányadát) az irányító
  szerv költségvetésébe kell befizetni
- Hitelt vehet fel, kötvényt bocsáthat ki, kezességet vállalhat a Magyarország
  gazdasági stabilitásáról szóló törvény keretei között, a Kormány engedélyével

#### Az önkormányzati költségvetési szerv gazdálkodási szabályai
- Nem lépheti túl (bér, tb, célfeladat, beruházás-felújítási alap)
- Alapítványokhoz csak engedéllyel járulhat hozzá
- Gazdasági társaságot csak engedéllyel alapíthat
- Vállalkozói tevékenységet elkülönítve kell kezelni
- Hitelt nem vehet fel, kötvényt nem bocsáthat ki, kezességet nem vállalhat

## Központi költségvezés és az önkormányzatok
A 2013. évtől az önkormányzati feladatellátás, ezzel együtt a finanszírozási
rendszer is alapjaiban megváltozott. A helyi önkormányzatok által korábban
ellátott feladatok jelentős részét az állam vette át. 

A feladatellátás állami átvételével egyidejűleg az azokhoz biztosított központi
támogatásokon túl a megosztott jövedelemből a belföldi gépjárműadó 60%-a a
központi költségvetéshez került (2020. évtől pedig a 100%-a), továbbá a helyben
maradó személyi jövedelemadó és az illetékbevétel megosztása megszűnt.  

| Megnevezés | 2023. évi költségvetési tv. szerint támogatás | 2023. év költségvetési tv. szerint bevétel |
|------------|----------------------------------------------:|-------------------------------------------------------------------------:|
| A települési önkormányzatok működésének általános támogatása | 280 665 millió Ft| |
| A települési önkormányzatok egyes köznevelési feladatainak támogatása | 239 832 millió Ft | |
| A települési önkormányzatok egyes szociális, gyermekjóléti és gyermekétkeztetési feladatainak támogatása | 317 447 millió Ft | | 
| A települési önkormányzatok kulturális feladatainak támogatása | 22 680 millió Ft | |
| A helyi önkormányzatok kiegészítő támogatása | 115 081 millió Ft | |
| Önkormányzati szolidaritási hozzájárulás | | 217 000 millió Ft |

(Központi költségvetés és az önkormányzatok: PPT-ben)

## Az államháztartás ellenőrzési rendszere
- Állami számvevőszék
  * Ellenőrzi az államháztartás gazdálkodását, a költségvetési javaslat
    megalapozottságát, a felhasználások szükségességét és célszerűségét
  * Ellenőrzi a zárszámadást
  * Önkormányzatok gazdálkodásának ellenőrzését végzi 

- Kormányzati Ellenőrzési Hivatal
  * A Kormány jóváhagyása alapján végzi vizsgálatait. Elsősorban a minisztériumokat
    ellenőrzi. 

- Egyéb formák
  * Belső kontrollrendszer
  * Belső ellenőrzés
  * Kincstári biztos, önkormányzati biztos
  * Felügyeleti szerv
  * Adóhatóságok
  * Külföld (pl. EU-s források)

## Alrendszerek finanszírozása és számlavezetés
- Kincstár
- Kincstári számla
- Likviditáskezelés
- Számlák
- Költségvetési szervek finanszírozása
- Elkülönített Állami Pénzalapok, Tb-alapok finanszírozása
- Önkormányzati alrendszerek finanszírozása

## Maradvány elszámolás, beszámolás
- Évközi kimutatások
- Végrehajtási beszámoló
- Zárszámadás
  * Állami Számvevőszék véleményezi, és a Kormány terjeszti be
  * A költségvetési évet követő szeptember 30-ig kell beterjeszteni
  * Országgyűlés fogadja el
  * Éves költségvetési törvényekkel megegyező tartalom, szerkezet 

## Kezesség-, garanciavállalás, kötelezettségek
- Adatok információs rendszere
  * Törzsvagyon nyilvántartása
  * Kincstári adatkezelés
  * Adatszolgáltatás

## Elkülönített Állami pénzalapok
- Finanszírozás
  * Kizárólag költségvetési finanszírozás (1992-ig)
  * Részben költségvetési, részben gazdálkodó szerv
  * Kizárólag gazdálkodó szerv
  * Költségvetés, gazdálkodó szerv, munkavállaló
  * Kincstári ügyfél

- Szabályok
  * Fő összegeit, bevételeit és kiadásait alaponként az Országgyűlés hagyja jóvá
  * Alapítvány, társadalmi szervezet, gazdasági társaság nem alapítható
  * Vállalkozási tevékenységet nem végezhet
  * Nem alapíthat, felügyelhet költségvetési szervet
  * Államkincstári folyószmla

| Alapok | Forrás |
|--------|--------|
| Központi Nukleáris Pénzügyi Alap<br>_1996. évi CXVI. tv_ | Paksi Atomerőmű Zrt. Befizetése (2018-ban 22,8 Mrd Ft, 2020-ban 25,5 Mrd Ft, 2023-ban 28,4 Mrd Ft) |
| Nemzeti Foglalkoztatási Alap (GFA)<br>_1991. évi IV. tv._ | - TB járulék megillető rész  (327,7 Mrd)<br> - Egyéb (63,4 Mrd Ft)<br> - 2022. évtől kezdődően szakképzési hozzájárulás a szociális hozzájárulási adóba olvad |
| Wesselényi Ár-és Belvízvédelmi Kártalanítási Alap<br>_2003. évi LVIII. tv._ | |
| Nemzeti Kutatási, Fejlesztési és Innovációs Alap <br>_2014. évi LXXVI. tv._ | Innovációs járulék (121,4 Mrd Ft) |
| Bethlen Gábor Alap<br> _2010. évi CLXXXII. tv._ | Költségvetési támogatás (34,3 Mrd Ft) |
| Nemzeti Kulturális Alap <br>_1993. évi XXIII. tv._ | Játékadó 12,7 Mrd Ft |

## Magyar államkincstár
A kincstári körbe tartozó pénzügyi feladatok centralizált elvégzésével megbízott
szerv

### Jellemzői
- Területi alapon szerveződött
- Állami feladatok finanszírozását szolgálja
- Egységes számlavezetés
- A jogszabályi előírásoknak nem megfelelő megbízások visszautasítása
- Kötelező- a helyi önkormányzatokon kívül – az államháztartás rendszerében a
  költségvetési szervek részére
- Mezőgazdasági és vidékfejlesztési támogatással összefüggő feladatok
- Nyugdíj- és egészségügyi ellátások folyósítása
- Működteti a törzsadat-nyilvántartást

## Társadalombiztosítás
- Alapok
  * Nyugdíjbiztosítási Alap
  * Egészségbiztosítási Alap

- Kiadások (szolgáltatások)
  * Betegségi, anyasági ellátások
  * Baleseti ellátások
  * Nyugdíjellátás

- Bevételek
  * Járulékok
    - Nyugdíjztosítási Alap 10%
  * Szankciók (pótlékok, bírságok)<br>Art. szerint
  * Központi költségvetésből pl. anyasági támogatás, nyugdíjszerű szociális
    ellátások
  * Kamatbevételek, hozadékok
  * Egyéb

-------------------------------------------------
# 4. előadás -  Bankrendszer, bankok működési mechanizmusa

## Bank fogalma 
Bármely bank amely egy adott uniós országban jogosult a bank elnevezés
használatára, az az egész Unió területén használhatja ezt, függetlenül attól,
hogy az adott országban banknak minősülne-e, vagy sem.  
_(Európai Parlament és a Tanács 2013/36/EU irányelve)_

## Bank fogalma Magyarországon
A hitelintézetekről és a pénzügyi vállalkozásokról szóló 2013. évi CCXXXVII.
Törvény definiálja a bankokat.

Egy bank általában a következő tevékenységeket folyamatosan végzi:
- betétgyűjtés,
- a hitelnyújtást,
- a fizetési forgalom bonyolítását. 

## Hitelintézet - bank
Hitelintézet fogalma? #wtf  
A fizetési forgalom lebonyolítása nem kötelező eleme a tevékenységének. 

## Fintech cégek
Azok a cégek, kezdeményezéseket nevezik így, amelyek pénzügyi, technológiai
újítások segítségével klasszikus banki szolgáltatásokat képesek nyújtani nem
banki formában.

## Banki funkciók mióta léteznek?
- Árucsere korszaka
- Árupénz korszaka
- Nemesfémpénz korszak
- Pénzhelyettesítők korszaka
- Modern pénz korszaka

## Bankrendszer fogalma
Egy ország bankrendszere alatt a bankjainak az összességét értjük.

- Kereskedelmi bankokat,
- Szakosított és speciális egyéb bankokat,
- Nemzeti bankot.

## Bankok, bankrendszer története
- 1848-49: Pesti Magyar Kereskedelmi Bank
- 1918: Osztrák – Magyar Bank felszámolása
- <wbr>1921. július 11. Magyar Királyi Állami Jegyintézet
- <wbr>1924. június 24. MNB, első elnöke: Popovics Sándor
- (1946. augusztus 1.)
- <wbr>1947. vége: Államosítás
- <wbr>1987. január 1.
- <wbr>1991. október: Jegybank független
- 2004-től Központi Bankok Európai Rendszere (KBER)

## Központi bank feladatai
- Bankjegy és érme kibocsátás (kizárólagos!) 
- Deviza és aranytartalék kezelése 
- Fizetési forgalom zavartalanságának biztosítása 
- Monetáris politika kivitelezése 
- Statisztikai feladatok 
- Erősíti a pénzügyi stabilitást

A bankok a rájuk bízott forrásokkal gazdálkodnak, több szempontnak is meg kell felelniük:

- Nyereséget kell termelniük,
- Likvidnek kell maradniuk,
- Biztosítaniuk kell a bank megfelelő tőkebázisát is.

## Pénzteremtés
A pénz áru és bankpasszíva, amely a pénz összes funkcióját betöltheti. 

A pénz teremtésének két módja van:
- Hitelnyújtással, azaz pénz jön létre, ha valamelyik kereskedelmi bank hitelt
  nyújt valamely gazdasági szereplőnek (ügyfél). Ezért hívják a modern
  pénzt hitelpénznek is.
- Külföldi deviza vétele során, vagyis akkor, ha az adott ország valamely bankja
  külföldi fizetőeszközt (devizát) vásárol egy gazdasági szereplőtől.

A pénz kikerülése a gazdaságból szintén kétféle módon történhet. 
- Hitel visszafizetéssel
- Külföldi fizetőeszköz (deviza) eladásával

## Bank működési modellek
- **Kereskedelmi (commercial) bankok**
  * lakosság részére
  * vállalkozások részére
  * széleskörű banki szolgáltatások
- **Befektetési (investment/merchant) bankok**
  * pénzügyi forrásokat közvetít
- **Univerzális bankok**
  * megjelentek a befektetési tevékenységek is
  * néhány befektetési tevékenység:
    - értépapírügyletek,
    - underwriting ügyletek - értékpapírok kibocsátásának garantálása,
    - biztosítások,
    - derivatív ügyletek,
    - vagyonkezelés és tanácsadás. 
- Szakosított és speciális hitelintézetek
  * jelzálog-hitelintézetek
  * lakás takarék pénztárak

## Banki szolgáltatások
A bankok azok a pénzügyi intézmények, amelyek a mindenkor hatályos jogszabályok
alapján üzletszerűen végezhetik az alábbi tevékenységeket. 

Sőt bank üzletszerűen csak olyan tevékenységet végezhet, mely az alábbiak szerinti pontokba tartozik bele.

- **pénzügyi szolgáltatások**
  * betét gyűjtése és más visszafizetendő pénzeszköz nyilvánosságtól történő
    elfogadása;
  * hitel és pénzkölcsön nyújtása, pénzügyi lízing;
  * [[#^penzforgalmi-szolgaltatas|pénzforgalmi szolgáltatás]];
  * [[#^leteti-szamla|letéti szolgálatás]], [[#^szef-szolgaltatas|széf szolgáltatás]];
  * valutával, devizával (ide nem értve a pénzváltási tevékenységet), váltóval,
    illetve csekkel saját számlára vagy bizományosként történő kereskedelmi
    tevékenység;
  * [[#^elektronikus-penz|elektronikus pénz]] kibocsátása;
  * papír alapú készpénz-helyettesítő fizetési eszköz (pl. papír alapú utazási
    csekk, váltó) kibocsátása, illetve az ezzel kapcsolatos szolgáltatás nyújtása;
  * kezesség és garancia vállalása, valamint egyéb bankári kötelezettség
    vállalása;

- **pénzügyi szolgáltatás közvetítése**;
- **hitelreferencia szolgáltatás**: lényege, hogy a bank az ügyfeléről banktitkot
  nem sértő információt ad át díjazás ellenében, illetőleg ennek minősül a
  központi hitelinformációs rendszert kezelő pénzügyi vállalkozás által történő
  adatkezelés is;
- **követelésvásárlási tevékenység**.
- **kiegészítő pénzügyi szolgáltatások**
  - pénzváltási tevékenység;
  - fizetési rendszer működtetése;
  - pénzfeldolgozási tevékenység;
  - pénzügyi ügynöki tevékenység a bankközi piacon.
- **biztosításközvetítői tevékenység**
- **befektetési szolgáltatási tevékenység**
  - pénzügyi eszközre (értékpapír, deviza, származtatott termékek) vonatkozóan végzett megbízás felvétele és továbbítása, megbízás végrehajtása az ügyfél javára, sajátszámlás kereskedés,
  - portfóliókezelés,
  - befektetési tanácsadás,
  - jegyzési garanciavállalás;
  - befektetési szolgáltatási tevékenységet kiegészítő szolgáltatások;
  - aranykereskedelmi ügyletek;
  - részvénykönyvvezetés.

A hitel és a kölcsön között jogi értelemben van különbség, Míg a hitel a pénz
rendelkezésre állítását jelenti, addig a kölcsön tényleges pénzfolyósítást
jelent. 

Pénzforgalmi szolgáltatás a **bankszámlavezetés és a bankszámlavezetéshez
kapcsolódó** összes tevékenység, mint a bankszámlára történő készpénz be-,
illetve bankszámláról történő készpénz kifizetés, a fizetési műveletek
bankszámlák közötti teljesítése (átutalás, csoportos beszedés stb.), továbbá a
készpénzátutalás. ^penzforgalmi-szolgaltatas

A **letéti számla** meghatározott célra elkülönített pénzeszközök nyilvántartására
és kezelésére nyitott bankszámla, amelyen letétként elhelyezett pénzeszközök
felett a bank, mint letétkezelő a jogszabályban, illetve a letevővel kötött
szerződésben meghatározott módon rendelkezhet (pl. ügyvédi letét). ^leteti-szamla

A **széf szolgáltatás** lényege, hogy a bank kiemelt ügyfelek számára nyújtson olyan
többletszolgáltatást, melynek keretében az ügyfelek
értéktárgyakat/értékpapírokat biztonságos és értékbiztosított helyen
tárolhatnak. ^szef-szolgaltatas

Az **elektronikus pénz** készpénz átvétele, illetőleg számlapénz átutalása ellenében
kibocsátott elektronikus pénzeszközön tárolt pénzérték, amelyet elektronikus
fizetés céljából a kibocsátón kívül más is elfogad. Ilyen például a SZÉP kártya.
^elektronikus-penz

### Egy átlagos kereskedelmi bank főbb tevékenységeinek fontosabb dimenziói
- Termékek
  * Megtakarítási termékek
  * Hitel termékek
  * Pénzforgalmi szolgáltatások
  * Befektetési termékek
  * Bankközi finanszírozás
  * Saját számlás kereskedés
- Ügyféltípusok
  * Háztartások
  * Kis- és középvállalkozások 
  * Nagyvállalatok (corporate)
  * Bankok, intézmények
  * Állam, önkormányzat
  * Központi bank
- Üzletág
  * Lakossági (retail)
  * Vállalati (corporate)
  * Projektfinanszírozás
  * Befektetési szolgáltatás
  * Kártya
  * Treasury
  * Letétkezelés
- Értékesítési csatorna
  * Fiók
  * On-line
  * Mobil bank
  * Call Center
  * Referens
  * Közvetítő

## Bankszabályozás
A bankok szabályozása – tértől és időtől függően – mindig _egyfajta alku_ az
állam és a bankok között. 

1907 - FED létrehozása : A FED feladata a rendszerméretűhatások kezelése volt:
a fertőzés megállítása, azaz, hogy az egyik pénzintézet csődje ne rántsa magával
a többi intézményt.

1933-ban fogadták el a **Glass-Steagall törvény**t, melynek a legközismertebb
jellemzője a befektetési és a kereskedelmi banki tevékenységek elválasztása. 

A törvény egyidejűleg létrehozta a **Szövetségi Betétbiztosítási Alap**ot.

A Glass-Steagall törvény egészen 1999-ig volt életben, amíg a
**Gramm-Leach-Bliley törvény** felül nem írta azt. A dereguláció szellemében
elfogadott Gramm-Leach-Bliley törvény lehetővé tette a banki szereplők
koncentrálódását, a tevékenységek kibővítésével **univerzális bankóriások**
jöttek létre.

A 2010. július 21-én életbe lépett Dodd-Frank Wall Street reform és
fogyasztóvédelmi - szakzsargonban csak Dodd-Frank – törvény. A Dodd-Frank
törvény legfontosabb területei a prudenciális felügyelés, a rendezett
felszámolási eljárás és a fogyasztóvédelem, azonban a törvény messze túlmutat
ezeken a területeken.   
A törvény szigorúbb makroprudenciális sztenderdeket alkalmaz, különös
tekintettel a magukban nagyobb rendszerszintű kockázatot hordozó pénzügyi
intézményekre, **nagyobb rálátást garantál a FED számára a nem banki szektor
ellenőrzésére**, magasabb fokú transzparenciát követel meg a származtatott
ügyletek piacán.

![[penzugytan__szabalyozas_es_gazdasagi_novekedes]]

A szabályozások célja, hogy a bankok **prudens** módon folytassák tevékenységüket. A
**prudencia** a banki működés egyik alapeleme, lényege a bankok biztonságos és
felelős működésének biztosítása, ezáltal a betétesek és az ügyfelek érdekeinek
védelme. 

A szabályozás esetében három különböző típust lehet megkülönböztetni:
- a [[#^makroprudencialis-szabalyozas|makroprudenciális szabályozás]]t;
- a [[#^mikroprudencialis-szabalyozas|mikroprudenciális]] és
- az [[#^uzleti-magatartas-szabalyozas|üzleti magatartás szabályozás]]át.

A **makroprudenciális szabályozás** a pénzügyi rendszer egészének a biztonságára
fókuszál, tehát nem az egyes banki szereplőkre, hanem azok intézkedéseinek
aggregált hatásaira. Ennek a biztonsági hálónak két lényeges eleme van: a
betétbiztosítás és a végső hitelezői funkció. Ezt a funkciót többnyire jegybank
látja el, mely egy intézmény finanszírozási problémája esetén végső hitelezőként
tud likviditást nyújtani, ha a szükséges likviditás nem érhető el a bankközi
piacról. ^makroprudencialis-szabalyozas

A **mikroprudenciális szabályozás** az egyes bankok felügyeletére fókuszál,
különös tekintettel a tőkemegfelelésre. ^mikroprudencialis-szabalyozas
 
Az **üzleti magatartás szabályozása** pedig a bankok üzletvitelével foglalkozik,
melynek az utóbbi időkben egyre erősebb fogyasztóvédelmi aspektusa van.
^uzleti-magatartas-szabalyozas

### Bázeli bizottság szabályozó sztenderdjei
A prudenciális szabályozásban a **Nemzetközi Fizetések Bankja** (BIS, Bank for
International Settlements) keretén belül működő **Bázeli Bankfelügyeleti
Bizottság** (BCBS, Basel Committe on Banking Supervision) a legfőbb globális
normaalkotó, mely Bizottság a nemzetközi bankfelügyeleti együttműködés
előrevitelélenek fórumaként is működik.

A Bank for International Settlements **60 ország jegybankjának** a tulajdona.

A G10 országok 1974-ben alapították meg a BIS mellett működő **Bázeli
Bizottságot**.

![[penzugytan__bazel_2|700px]]
 
A Bázel III szabályrendszer fő jellemzői az alábbiak. Bázel II-höz képest **nem
változott**:
- Három pilléres megközelítés: minimum szabályozói tőke, gazdasági tőke
  (ICAAP-SREP), nyilvánosság;
- Hitel, piaci és működési kockázatok tőkekövetelmény számítási módszerei.

**Ami változott**:
- Szigorodott a tőke fogalma és a tőkemegfelelés elvárt szintje;
- Új likviditási követelmények és mutatók kerültek bevezetésre;
- Tőkeáttétel korlátozása;
- Új kockázati fogalmak beemelése, pl. elszámolási, partner;
- Belső irányítási szabályok és a javadalmazás szigorítása;
- Tőkepufferek bevezetése a prociklikusság és a rendszerkockázat csökkentése
  érdekében.

A Bázeli Bizottság 2017 decemberében hozta nyilvánosságra azokat a jövőbeni változtatásokat, melyekkel véglegesnek tekinti a Bázel III csomagot. Ennek főbb elemei:
- a tőkeáttétel további szigorítása;
- a különböző módszertanokkal számított kockázattal súlyozott eszközök és
  tőkekövetelmények összehasonlíthatóság érdekében ún. tőkepadló bevezetése;
- az egyes kockázatok (piaci, fejlett módszerek, működési stb.) tőkekövetelmény
  számítási módszereinek felülvizsgálata.

Bár a Bizottság a javasolt további változtatásokat következetesen a Bázel III
csomag részeként emlegeti, a **szakmai zsargonban ezt már Bázel IV**-nek szokták
nevezni.

## Bankfelügyelet
Feladata a bankrendszer biztonságának és stabilitásának megőrzése.

Az európai bankfelügyelet az EKB-ból és a részt vevő országok nemzeti
felügyeleteiből áll.
Az európai bankfelügyelet fő céljai:
- szavatolni az európai bankrendszer biztonságát, szilárdságát,
- növelni a pénzügyi integrációt és stabilitást,
- garantálni a következetes felügyeleti munkát.

### Bankrohamok
A bankrohamok a pénzügyi válságok leglátványosabb megnyilvánulásai közé
tartoznak, melyek során a betétesek tömegesen veszik ki megtakarításaikat a
pénzintézetekből, ezzel jelentős károkat okozva a gazdaságnak.

### A biztonsági háló elemei
- különleges jogi-szabályozási környezet,
- szigorú engedélyezési, felügyeleti rendszer;
- a bankok belső döntési és ellenőrzési  rendszere (néha a hazainál is szigorúbb
  anyavállalati előírásokkal);
- bankközi intézmények (pl.: bankközi pénzpiac, adósnyilvántartás);
- végső hitelezőként a jegybank;
- hatékony bankválság megoldási technikák (bankszanálás)

**betétbiztosítás**: a betétesek végső  menedéke

### OBA
**Alapítás**: 1993-ban  
**Szabályozás**: az 1996. évi CXII. (hitelintézeti) törvény által

**Az OBA jellemzői**:
- "sui generis" intézmény
- jogi személy
- nem társaság (nem részvénytársaság)
- nem költségvetési (állami) intézmény
- az ÁSZ ellenőrzi
- pénzeszközei másra nem használhatók
- adót nem fizet
 
**Irányító testület**: Igazgatótanács  
Nincs felügyelőbizottság, nincs részvényesi kör

- Csatlakozási díj (a jegyzett tőke 0,5%-a)
- Éves tagdíj 
- Az állampapír befektetések hozama

Ha nem lenne elegendő:
- Hitel a jegybanktól
- Hitel más hitelintézettől (kérésre állami  kezességgel)
- Kötvénykibocsátás lehetősége

Védett:
  - betétek
  - folyószámlák
  - 2003 utáni kibocsátású hitelintézteti **letéti jegy** és **kötvény**
  - magánszemélyek betétei
  - társaságok betétei
  - közösségi betétek

Nem védett:
  - nem nevesített betétek
  - 100 EUR feletti betét rész
  - <wbr>2003. január 1. előtt kibocsátott hitelintézeti letéti jegy és kötvény

<!-- TODO: ábra - PPT 51. dia -->

Az OBA-nak jogszabály által meghatározott határidőn belül kell kártalanítani a
biztosított betéteseket, amely a 25 éves fennállás alatt fokozatosan rövidült,
és a jövőben 7 munkanapra csökken.

Ez növekvő erőforrásokat (pl. informatikai beruházásokat) igényel az OBA
részéről a jövőben is.

<!-- TODO: ábra - PPT 52. dia -->

-------------------------------------------------
# 5. előadás - Aktív és passzív bankügyletek és a faktorálás

Passzív bankügyletek (a banknak kötelezettsége keletkezik)
- Betétek gyűjtése
- Értékpapír kibocsátás
- Jegybanki forrásos

Aktív bankügyletek (a banknak követelése keletkezik)
- Hitelezés
- Váltóleszámítolás
- Lízing
- Faktoring

Semleges bankügyletek
- értékpapír kezelés
- pénzváltás
- széfszolgáltatás

## Fogalmak
- **Hitel általános értelemben**: meghatározott pénzösszeg, követelés vagy áru
  átengedése meghatározott időtartamra és kamatfizetés ellenében ^hitel
- **Bankkölcsön**: tényleges pénzfolyósítást jelent 
- **Bankhitel**: a pénz rendelkezésre tartása 
- **Rendelkezésre tartási jutalék**: csak a kölcsönként ténylegesen fel nem vett
  hitelkeret után kell fizetni (%) 
- **Kamat**: a kölcsön ára, a kölcsönvett pénz használati díja (%)
- **Fedezet**: a vállalkozásban rejlő képesség, hogy ki tudja termelni a felvett
  kölcsön aktuális tőketörlesztő részletét és kamatát – közgazdasági kategória
- **Biztosíték**: járulékos jellegű kötelem, amely mindig valamilyen
  alapkötelezettséghez kapcsolódóan kerül kikötésre – jogi kategória ^biztositek
  * A hitelező kockázatát minimalizálja 
  * A hitelező pozícióját az adós anyagi, pénzügyi helyzetének változásától
    függetleníti.
- **Türelmi idő**: Az az időtartam, amely alatt csak kamatfizetési kötelezettség
  van, de tőketörlesztésre nem kerül sor – Közép-, illetve hosszú lejáratú hitelek
  esetén kérhető, a futamidő első néhány hónapját, vagy 1-2 évét érintheti.
  Könnyebbség a hitelfelvevő számára.
- **Hitel (kölcsön) átütemezés**: a kölcsön lejárati időpontjának
  megváltoztatása
- **Saját erő**: A kölcsön felvételéhez szükséges önrész. Mértéke változó,
  általában 20-30 százalék. Hitelezési alapelv: Hitel, kölcsön, csak saját
  források kiegészítésére nyújtható.


## [[#^biztositek|Biztosíték]]kal szembeni követelmények
- **Könnyen kiköthető**: jogi szempontból „tiszta”. 
- **Könnyen értékelhető**: azaz piaci értékének meghatározása nem ütközik
  akadályokba,
- **Piacképes**: a piacon valamilyen fizető eszközzé akadálytalanul átváltható,
  értékesíthető 
- **Értékálló**: a piaci értéke hosszabb távon nem csökken azon érték alá,
  amelyet eredeti állapotában képviselt. 
- **Tartós**: a hasznos élettartama alapján hosszabb időn át őrzi meg azt a
  tulajdonságát (fizikai, kémiai), hogy a piacon eladható, likviddé tehető. 
- **Könnyen ellenőrizhető**.

## [[#^biztositek|Biztosíték]]ok csoportosítása
Személyi jellegű
  - kezesség
    * egyszerű kezesség
    * készfizető kezesség
  - bankgarancia
  
Tárgyi (dologi)
  - zálog
  - óvadék

## [[#^hitel|Hitel]]költségek
- Hitelbírálati díj
- Kezelési díj
- Értékbecslési díj
- THM: Teljes Hiteldíj Mutató, Egységes, minden hitelező által kötelezően
  használt mutató, amelyből kiderül, hogy az adott hitel felvétele után az adósnak
  1 év alatt a tőkén túl mekkora összeget kell visszafizetnie

## [[#^hitel|Hitel]]ek csoportosítása
### 1. Közgazdasági jellege szerint
- **Pénzteremtő**: A pénzteremtő hitel esetén a kereskedelmi bank aktíváinak és
  passzíváinak összege egyaránt nő.
- **Pénzújraelosztó**: A pénzújraelosztó hitelnél viszont az aktívák rendeződnek
  át, de összegük nem nő. A betétgyűjtéssel nem foglalkozó hitelintézetek csak
  pénzújraelosztó hitelt tudnak nyújtani.

### 2. Lejárat szerint
A hiteleknek mindig van lejárata, más néven futamideje.
Futamidőnek nevezzük a hitel folyósításától a tőke és kamatai teljes megfizetéséig meghatározott időt.
Magyarországon, az éven belüli (max. 12 hónap) és az éven túli (12 hónapnál hosszabb) kifejezés használata terjedt el a hitelek tekintetében.

- **Rövid** lejáratú hitel: A futamidő max. 12 hónap
- **Közép** lejáratú hitel: A futamidő 1-3 év (egyes országokban 1-5 év)
- **Hosszú** lejáratú hitel: A fenti kettőnél hosszabb futamidő

### 3. Technikai forma szerint
- **Folyószámla hitel**:
  * A folyószámla hitel számlabetéthez kapcsolódó hitelkeret megállapítása meghatározott időtartamra (ez történhet úgy is, hogy évente felülvizsgálva, mindig egy további évre érvényes).
  * Igénybevétele a számlán lévő pénzforgalom függvénye, a betét összegét a hitelkeret erejéig meghaladó kifizetések, terhelések eszközölhetők, a hitelkeret felhasználása így naponta változhat.
  * Régebbi ügyfélkapcsolat alapján, jó hitelképességű ügyfeleiknek nyújtanak folyószámla hitelt a bankok.

- **Számlahitel**: A számlahitel eseti hitelnyújtás, minden egyes
  hitelszerződésből eredő követelés és annak visszafizetése külön számlán kerül
  nyilvántartásra.
  
- **Leszámítolási hitel** 

- **Értékpapír megvásárlása**: Az értékpapír megvásárlása, mint hitelügylet a
  hitelviszonyt megtestesítő papírokra vonatkozik, történhet forgatási és
  befektetési (pl. államkötvény) céllal.

### 4. Cél szerint
- **Forgóeszközt finanszírozó hitel**: A forgóeszközt finanszírozó hitellel
  átmeneti, vagy tartós forgóeszköz szükségletet lehet kielégíteni. Előbbi rövid,
  utóbbi közép vagy hosszú lejáratú hitel. A rövid lejáratú is kétféle lehet
  aszerint, hogy a vállalkozás egész forgóeszközére (üzemviteli hitel) vonatkozik,
  vagy egy ügyletéhez kapcsolódik. Ilyen ügylet pl. az export- előfinanszírozás,
  az import utófinanszírozás, vagy gabonavetésre vonatkozó hitel.

- **Beruházást finanszírozó hitel**: A beruházási hitel tárgyi eszköz
  megvásárlását, termelőalapok létrehozását (pl. ültetvénylétesítés), építést
  szolgálhat. Többnyire hosszú lejáratú, ritkább esetben fordul elő egy-egy tárgyi
  eszköz megvásárlására felvett rövid lejáratú beruházási hitel.

- **Projektet finanszírozó hitel**: A fejlesztési hitel vagy projekt hitel
  nyújtása általában refinanszírozási forrásból történik, nagyobb projekteknél a
  kockázat megosztása, a nagykockázatra vonatkozó előírások betartása miatt több
  bank nyújt együttesen hitelt, ezt szindikált hitelnek nevezzük.

### 5. A hitelfelvevők szerint
- **Költségvetésnek és szervezeteinek nyújtott hitel**: Ide tartozik az
  állampapír vásárlása, valamint pl. az önkormányzatoknak nyújtott hitel.

- **Bankközi hitel**

- **Vállalkozói hitel**: A vállalkozói hitelek forgóeszközök, beruházások,
  fejlesztések finanszírozását szolgálják.

- **Lakossági hitelek**: A lakosság esetében fogyasztási (áruvásárlási),
  személyi (cél megjelölése nélkül) és építési- ingatlanvásárlási hiteleket
  különböztetünk meg.

### 6. Fedezet szerint
- **Kézizálog, vagy lombardhitel**: Az óvadékkal fedezett hitel (kézizálog -
  óvadék olyan piacképes ingó vagyontárgy vagy betétszámla, amelyet tulajdonosa a
  hitel  utamidejére a banknál helyez el, s amennyiben a hitelt nem tudja
  visszafizetni, a kézizálog automatikusan a bank tulajdonába megy át.)

- **Jelzáloghitel**: Fedezete ingatlan.

- **Okmányos hitel**: Fedezete áruokmány, pl. közraktárjegy.

## A [[#^hitel|hitel]]ezési eljárás szakaszai
1. Előzetes hiteltárgyalás
1. Hitelkérelem benyújtása
1. Hitelbírálat (ügyfélminősítés és ügyletminősítés)
1. Hiteldöntés
1. Hitelszerződés megkötése
1. Kölcsönszerződés megkötése
1. Kölcsön folyósítása
1. Hitelfigyelés
1. Utolsó törlesztőrészlet visszafizetése

**Pénzforgalmi számla**: Csak addig lehet a felhasználásával kiadásokat eszközölni,
amíg van rajta fedezet.

**Folyószámla**: Olyan pénzforgalmi számla, amihez hitelkeret is tartozik.
Hasonló, de a rulírozó hitelkerettel nem azonos!

## Faktoring
A faktoring egy jellemzően keretjellegű megállapodás a faktor és árut,
szolgáltatást halasztott fizetéssel értékesítő szállító, vagy halasztott
fizetéssel fizetendő követelés jogosultja (eladó) között, amely az alábbiakra
terjed ki:
- A faktor megvásárolja a szállító/eladó számlakövetelését vagy egyéb
  követelését azonnali fizetés vagy azonnali részfizetés és a kötelezett
  teljesítésekor elszámolási kötelezettség mellett.
- Nyilvántartja és kezeli a követeléseket,
- Beszedi a követeléseket, illetve a faktoring megállapodásban meghatározottak
  szerinti behajtási tevékenységet végez.
- Védelmet nyújt az adósok fizetési késedelme, mulasztása ellen. 

## Faktoring típusai
### 1. Eladott követelések száma szerint
- **csoportos** faktorálás: egyetlen követelést adnak el.
- **egyedi** faktorálás: ez a gyakoribb, amikor egy cég egy adott időszak
  (negyedév, félév) alatt keletkezett követeléseit adják el.

### 2. Földrajzi elhelyezkedés szerint
- **belföldi** faktoring: résztvevőinek, tehát a vevőnek, a szállítónak s a
  faktornak a székhelye ugyanabban az országban van. A legtöbb esetben vevői
  kockázat átvállalása nélkül működik.
- **nemzetközi** faktoring: esetében a vevői kockázat átvállalása általánosan
  jellemző. Az ügyletnek jellemzően négy szereplője van az exportőr, az importőr,
  az export országban működő exportfaktor és az importőr országban működő
  importfaktor, de sok esetben három szereplős egy faktor szereplővel. 

### 3. Visszkereseti jog szerint 
- **visszkereset nélküli** faktoring ügylet esetén az eladó finanszírozási
  díjat és kockázatvállalási díjat fizet a faktornak, cserébe a faktor vezeti
  követeléseinek nyilvántartását és ellenőrzi azokat, követelései ellenértékét
  beszedi és átvállalja a vevő fizetésképtelenségi kockázatát. 

- **visszkeresetes** faktoring esetén a faktor visszkereseti jogot köt ki, nem
  vállalja át a vevő nemfizetési kockázatát. Tehát a vevő bármilyen okból történő
  nemfizetésének következményeit az ügyfél viseli. A faktor egy általa
  meghatározott limit erejéig finanszírozza az ügyletet, végzi a kereskedelmi
  forgalom nyilvántartását, ellenőrzését és a kintlévőségek beszedését. Ha a
  fizetésre kötelezett nem törleszt, akkor az adósnak kell fizetnie. Hazánkban
  gyakoribb az a megoldás.

### 4. Információ megosztása szerint
- **csendes** faktorálás: az ügylet során azt nem értesítjük, akivel szemben
  fennáll a követelés. 
- **nyílt** faktorálás: az ügylet valamennyi szereplőjét értesítik a
  részletekről. 

## Forfertírozás
A forfetírozás nem más, mint egy későbbi időpontban esedékes, általában gépek és
beruházási termékek szállításából és/vagy a beruházásokhoz kapcsolódó
szolgáltatások nyújtásából eredő közép-, illetve hosszú lejáratú követelések
visszkereset nélküli megvásárlása.

## Faktorálás és forfertírozás összehasonlítása
| Faktorálás | Forfertírozás |
|------------|---------------|
| Követelés megvásárlás (egyszerű áruvásárlásból adódó köv.) | Követelés eladás |
| Rövid lejáratú követelések (60-90 napos) eladása | Éven túli követelésre vonatkozik (pl. beruházásokhoz kapcsolódó követelések) |
| Belföldi és export követelés | Mindig exportkövetelésre vonatkozik |
| Kétféle kockázattal veszi meg | Mindig visszkereseti jog fenntartása nélküli követeléssel kapcsolatos |

-------------------------------------------------
# 6. előadás - Fizetési módok és a lízing

## Fizetési és elszámolási rendszer
Minden országban a jegybank (központi bank) alakítja ki az országos fizetési és elsz

A fizetési módokat három csoportba soroljuk:
1. Készpénzes. Ez a világon egyre visszaszorulóban van, zömmel lakossági
   vásárlásoknál alkalmazzák.
2. Készpénz kímélő. Ide tartozik a csekk, a bankkártya és a váltó. E folyamatban
   a készpénz vagy késleltetve, vagy egyáltalán nem jelenik meg.
3. Készpénz nélküli. Jellemző fizetési mód mind a belföldi, mind a külföldi
   pénzfogalomban. Bankszámlák segítségével bonyolódik, tulajdonképpen
   bankszámlák közötti átírás. 

Fajtái: 
- átutalás,
- beszedési megbízás (inkasszó),
- akkreditív

## Bankszámlaszerződés
A készpénz kímélő és a készpénz nélküli fizetési módok alapfeltétele a
hitelintézet és az ügyfél között bankszámlaszerződés létrejötte. Ezen
szerződésben mindkét fél jogait és kötelezettségeit is rögzítik.  
Minden bankszámlához pénzforgalmi jelzőszám tartozik, ami azonosítja a bankot, a
fizetési művelet helyét (bankfiók) és a számlatulajdonost. Összesen 16 vagy 24
karaktert tartalmaz.

A hitelintézet feladatai és jogai:
- számlanyitás, pénzforgalom bonyolítása, alszámlák vezetése
- számlakivonat készítése, kiküldése
- a napi egyenleg után látra szóló kamatfizetés
- előírja a megbízások benyújtásának formáit, szabályait (aláírások,
  formanyomtatványok)

Az ügyfél jogai és kötelezettségei:
- teljes körű rendelkezés a számla felett
- a számla kezeléséért, a pénzforgalom bonyolításáért jutalék fizetése a banknak
- az érkező terhelésekre fedezet biztosítása

## Számlák fajtái
- **Elszámolási** számla vagy **pénzforgalmi** számla: A pénzforgalmi számlákról
  valamennyi fizetési mód teljesíthető, egyenlege pozitív vagy nulla, nem szolgál
  meghatározott célt.

- **Folyószámla**: A folyószámla olyan pénzforgalmi számla, amelyhez hitelkeret
  kapcsolódik, egyenlege ezen keret mértékéig negatív is lehet.

- **Elkülönített számlák** (fedezetigazolási, csekk vagy váltó fedezeti, stb.):
  Az elkülönített számlákról csak a meghatározott célra történhet kifizetés.

- **Betétszámlák** (takarékbetétek és határidős betétszámlák): A betétszámlák
  egyenlege csak pozitív lehet. A takarékbetét a megtakarítások elhelyezésére, a
  lekötött betét átmeneti időszakra feleslegessé vált pénzösszegek határidős
  lekötésére szolgál.

- **Hitelszámlák**: A hitelszámla az eseti hitelösszeg felhasználásának és
  törlesztésének nyilvántartására szolgál.

- **Devizaszámlák**: A devizaszámla az ügyfél birtokában jutott külföldi
  fizetőeszköz elhelyezését szolgálja.

- **Értékpapír-letéti számla**: Az értékpapír-letéti számlákon az ügyfelek
  értékpapírjait és azzal végzett műveleteket tartják nyilván.

## Készpénz helyettesítők

### Csekk
A csekk értékpapír (okirat), kibocsátója kötelezettséget vállal a csekken
szereplő összeg számlakövetelése terhére történő kifizetésére. Szigorú törvényi
előírásoknak megfelelő formájú értékpapír.

Lehet: névre, rendeletre és bemutatóra szóló. A rendeletre szóló forgatható, a
bemutatóra szóló fizetési eszközként funkcionál.

A csekk a rövid lejáratú fizetések lebonyolítását szolgálja (általában 8 nap).
Az üzleti életben a készpénz felvételre nem jogosító csekk terjedt el, a
külföldi fogalomban pedig a rendeletre szóló.

Két alaptípusa: a fizetési csekk és az átírási csekk. Előbbi készpénz
felvételére szolgál, utóbbi bankszámlák közötti pénzmozgást tesz csak lehetővé.
Az utazási csekk fix összegű fizetési csekk, külföldi utazásoknál biztonsági
szerepe is van.

### Bankkártya
A bankkártya jellege szerint:
- betéti típusú (DebitCard): csak a betét összegéig lehet vele kifizetéseket
  eszközölni
- hitelkártya (CreditCard): hosszabb időre, hitelszerződés alapján, folyósított
  hitel felhasználását biztosítja
- vegyes típusú (MixedCard)

Felhasználás alapján lehet:
- csak belföldi használatú
- csak külföldi használatú
- bel- és külföldön egyaránt használható

A fizetés időbeni különbsége alapján:
- előre fizetett vagy vásárolt (pl. telefonkártya): ezeket általában nem bankok
  bocsátják ki, meghatározott célra használhatók
- azonnali fizetést megtestesítő (betéti típusú és egyes vegyes típusúak)
- későbbi fizetést biztosító (hitelkártyák és egyes vegyes típusúak)

Alkalmazott technológia szerint:
- dombornyomású
- mágnescsíkos
- chipes és optikailag leolvasható

A legbiztonságosabb a chipes és az optikailag leolvasható kártya. Használatához
személyi azonosító (ún. PIN-kód) szükséges.

Az **ATM** (Automatic Teller Machine): készpénz felvételére, készpénz befizetésére
és információ szolgáltatására alkalmas.

**POS-terminál** (Point of Sale): kártya leolvasó, a fizetés helyén alkalmazott
berendezés.

### Váltó
A váltó olyan értékpapír, amely egyoldalú és jogcímmentes pénztartozást
(követelést) testesít meg, és különleges váltójogi szabályok alá esik.

A fizetésre kötelezett szerint lehet:
- **Saját** váltó: kiállítója kötelező fizetési ígéretet tesz, hogy a váltó
  összegét a megjelölt időpontban kifizeti. Szereplői: kibocsátó (kötelezett),
  rendelvényes (kedvezményezett).

- **Idegen** váltó: kiállítója egy másik személyt szólít fel a váltóösszeg
  kedvezményezett részére történő kifizetésre meghatározott időre. Szereplői:
  kibocsátó, címzett (kötelezett), rendelvényes  kedvezményezett). Az idegen váltó
  akkor érvényes, ha a címzett cégszerűen aláírta.

Törvényes kellékei:
- váltó elnevezés, 
- konkrét összeg fizetésére vonatkozó ígéret vagy feltétlen meghagyás, 
- fizetésre kötelezett neve, címe, 
- lejárat (esedékesség) időpontja, 
- fizetés helye, 
- rendelvényes neve, címe, 
- a váltó kiállítás napja, helye, 
- a kibocsátó (kiállító) aláírása.

A váltó birtokosa a váltóval a következőket teheti:
- megvárja az esedékesség időpontját és behajtja követelését
- fizetési eszközként használja, forgatja. Ennek szereplői: forgató,
  forgatmányos.
- hitelintézetnél leszámítoltatja, azaz esedékesség előtt a hitelintézet
  gyakorlatilag jelenértéken megveszi a váltót, s ezzel a váltó birtokosává válik.

Az üzleti bankok váltóügyletei:
- leszámítolás,
- viszontleszámítolás,
- váltó beszedés

## Készpénz nélküli fizetési módok
Az **átutalás** a fizetésre kötelezett kezdeményezésére, számlájának terhére a
jogosult számláján történő jóváírás.

A **beszedési megbízás (inkasszó)** a jogosult kezdeményezésére a kötelezett
számlájának megterhelésével a jogosult számláján történő jóváírás. A jogosult
saját bankját megbízza, hogy követelését szedje be. Lehet azonnali (prompt) vagy
határidős. Előbbi esetben a fizetés azonnal megtörténik (a gyakorlatban ez
bírósági végzés vagy törvényi felhatalmazás, továbbá konkrét ügyletre
vonatkozóan a fizetésre kötelezett nyilatkozata alapján lehetséges). Határidős
inkasszó esetén a fizetésre kötelezett kifogást emelhet (visszkereseti joga van)
és a fizetés bizonyos idő elteltével csak akkor teljesül, ha a kötelezett nem
emel kifogást.

Az **akkreditív** a vevő bankjának (ún. nyitó bank) fizetési ígérete, amelyet a
vevőtől kapott megbízás alapján tesz, arra kötelezve magát, hogy ha az eladó az
előre meghatározott feltételeket teljesíti, részére fizetést teljesít. Általában
nemzetközi fizetésekhez kapcsolódik.

## Lízing
Eszköz alapú finanszírozási szerződés. Egy olyan szerződési forma, amely a
bérlet és az adásvétel keveredéséből alakult ki, de egyik sem található meg
benne tiszta formában. A lízing a beruházási hitelek alternatívája lehet
eszközvásárlás esetén. Különböző lízingfajták esetén más-más jellemzőre kerül a
hangsúly.

Előnyei:
- Addicionális beruházás finanszírozás egyszeri, nagy összegű tőkelekötés nélkül
- Eszközfedezettsége révén kevesebb egyéb biztosítéki elemet igényel
- Számviteli előnyök egyes lízing konstrukcióknál
- Adóelőnyök egyes lízing konstrukcióknál

Alanyai és menete:
![[penzugytan__lizing_alanyai_menete|700px]]

Fajtái:
- pénzügyi
  * nyíltvégű
  * zártvégű
- operatív
  * nyíltvégű
  * zártvégű

### Operatív lízing
Más néven tartós bérlet. Esetén lejáratkor a bérbe (lízingbe) adónál marad az
eszköz tulajdonjoga. Rövid lejáratú bérleti szerződés, az amortizációt a
lízingtársaság számolja el. A lízingtársaság költségei több egymást követő
lízingügylet során térülnek. A lízing tárgy újra lízingbe adható. Ilyen típusú
lízing például az autókölcsönzés, vagy a padlószőnyeg tisztító gép kölcsönzése.

### Nyílt végű operatív lízing
- A lízingdíjak tőkerészre eső ÁFA tartalma visszaigényelhető.
- A lízingdíj kamatrésze költségként elszámolható.
- Kevesebb a  fizetendő kamat.
- A lízingbe vevő jogosult az értékcsökkenés elszámolására.
- Maradványértékes konstrukcióval csökkenthető a havi törlesztő részletek
  mértéke.
- A futamidő lejárta után a lízingbe vevő dönthet a lízing tárgy
  megvásárlásáról, a lízingbe vevő kijelölheti a vásárlót.

### Zárt végű operatív lízing
- Tulajdonjog megléte nélkül is a vállalkozások saját könyveikben tarthatják
  nyilván a lízingelt gépjárművet.
- A tőkerész ÁFA-jának teljes összegét meg kell fizetni
- A lízingbe vevő jogosult az értékcsökkenés elszámolására
- Továbbá illetékköteles eszközöknél a vagyonszerzési illetéket a lízingbe
  vevőnek a futamidő elején kell megfizetnie
- A lízingtárgy automatikusan a lízingbe vevő tulajdonába kerül

### Egyéb lízing fajták
- **Allízing**, ha nem a lízingbe vevő használja a lízingbe vett tárgyat, hanem
  tovább adja lízingbe, bérletbe. Csak olyan társaság teheti meg, amelyik maga is
  jogosult lízing tevékenységre.

- **Visszlízing** az eladó a saját tulajdonát képező tárgyat eladja a
  lízingcégnek, majd lízingszerződést köt az eladott tulajdonra a lízingcéggel

- **Teljeskörű szolgáltatás**, a lízing mellett a lízingbe vevő teljes körű
  szolgáltatást kap, és mindent egy díjba sűrítve fizet meg




