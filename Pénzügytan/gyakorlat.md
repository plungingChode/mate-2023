# Egyszerű kamatozás jövőértéke
$$
C_t = C_0 + (1 + k * t)
$$

ahol:
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $C_0$ a kezdő tőke
- $k$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

# Kamatos kamatozás jövőértéke
$$
C_t = C_0 + (1 + r)^t
$$

ahol:
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $C_0$ a kezdő tőke
- $r$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

# Kamatnapok számításának módszerei

| Módszer   | Hónap napjai    | Év napjai |
|-----------|:---------------:|----------:|
| pontos    | tényleges	      | tényleges |
| angol	    | tényleges	      | 365       |
| francia   | 28, 30, 31      | 360       |
| német	    | 30              | 360       |

$$
C_t = FV_t = C_0 \cdot (1 + k \cdot \frac{\textrm{kamatnapok száma}}{\textrm{év napjainak száma}})
$$

# Névleges kamatláb ($k$) és effektív kamatláb (hozam, $r$)
$$
r = (1 + \frac{k}{m}) ^ m - 1
$$

ahol:
- $r$ az effektív kamatláb
- $k$ a névleges kamatláb
- $m$ az egy év alatti kamatperiódusok száma

## Jövőérték számítás egy évnél rövidebb kamatperiódusú befektetésekre
$$
FV_1 = C_0 \cdot (1 + \frac{k}{m})^m
$$

ahol:
- $FV_1$ az egy év múlva esedékes jövőérték
- $C_0$ a kezdő tőke
- $k$ a névleges kamatláb
- $m$ az egy év alatti kamatperiódusok száma

# EBKM
Mindig **tényleges** kamatnap számítási módszerrel számoljuk!

$$
EBKM = (\frac{C_t}{C_0} - 1) \cdot \frac{1}{t}
$$

ahol:
- $C_t$ a jövőérték
- $C_0$ a jelenérték (kezdő tőke)
- $t$ a befektetés **tényleges** időtartama

#### Példa
#TODO

# Egyszerű kamatozás jelenértéke 
$$
C_0 = PV = \frac{C_t}{(1 + k \cdot t)}
$$

ahol:
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $C_0$ a kezdő tőke
- $k$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

#### Példa <!-- {{{ -->
Egy lineáris kamatozású bankbetét névleges kamatlába 5%. Mekkora összeget kell
ma elhelyeznünk ebbe a bankbetétbe, ha három év múltán 500.000 forintot
szeretnénk belőle felvenni?

$$
C_0 = \frac{500.000}{1 + 0,05 \cdot 3} = 434.783
$$

434.783 Ft-ot kell ma elhelyeznünk a bankbetétbe.
<!-- }}} -->

# Kamatos kamatozás jelenértéke
$$
C_0 = PV = \frac{C_t}{(1 + r)^t}
$$

ahol:
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $C_0$ a kezdő tőke
- $r$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

#### Példa <!-- {{{ -->
Egy kamatos kamatozású bankbetét névleges kamatlába 5%. Mekkora összeget kell ma
elhelyeznünk ebbe a bankbetétbe, ha három év múltán 500.000 forintot szeretnénk
belőle felvenni?

$$
C_0 = \frac{500.000}{(1 + 0.05)^3} = 431.919
$$

431.919 Ft-ot kell ma elhelyeznünk a bankbetétbe.
<!-- }}} -->

# Egyszerű kamatozás hozama
$$
k = (\frac{C_t}{C_0} - 1) \cdot \frac{1}{t}
$$

ahol:
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $C_0$ a kezdő tőke
- $k$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

#### Példa <!-- {{{ -->
1.000.000 Ft befektetésükre a bank 5 év múltán 1.276.300 Ft visszafizetését
ígéri. Mekkora névleges kamatlábnak felel ez meg egyszerű kamatozást
feltételezve?

$$
k = (\frac{1.276.300}{1.000.000} - 1) \cdot \frac{1}{t} = 0,05526 \approx 5,5\%
$$
<!-- }}} -->

# Kamatos kamatozás hozama
$$
r = IRR = \sqrt[\displaystyle t]{\frac{C_t}{C_0}} - 1
$$

ahol:
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $C_0$ a kezdő tőke
- $r$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

#### Példa <!-- {{{ -->
1.000.000 forintos befektetésükre a bank 5 év múltán 1.276.300 forint
visszafizetését ígéri. Mekkora hozamnak felel ez meg, mekkora befektetésünk
belső megtérülési rátája?

$$
r = \sqrt[\displaystyle 5]{\frac{1.276.300}{1.000.000}} - 1 = 0,05 = 5\%
$$
<!-- }}} -->

# Nettó jelenérték számítás
A nettó jelenérték egy adott befektetéshez tartozó pénzáramlások jelenértékeinek
összege. A jövőbeli pénzáramlásokat mindig a piaci hozam segítségével számítjuk
át jelenértékre. 

## Egyszer, $t$ időpontban kifizetést teljesítő befektetések esetén
$$
NPV = -C_0 + \frac{C_t}{(1 + r)^t}
$$

ahol:
- $NPV$ a nettó jelenérték
- $C_0$ a kezdő tőke
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $r$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

#### Példa <!-- {{{ -->
Egy ismerőse egy olyan befektetési lehetőséget ajánl Önnek, ami 400.000 forint
befektetésére 4 év múlva 600.000 forint visszafizetését garantálja. A hasonló
kockázatú és futamidejű befektetések elvárt hozama 10%. Mekkora nettó
jelenértéket ígér a befektetés az Ön számára? Érdemes-e ez alapján elfogadnia az
ajánlatot?

$$
NPV = -400.000 + \frac{600.000}{(1 + 0,1)^4} = -400.000 + 409.808 = 9.808
$$

Érdemes elfogadni, mert $NPV > 0$.
<!-- }}} -->

## Kettőnél több taggal rendelkező pénzáramlása-sorozatokra
$$
NPV = -C_0 + \sum_t{\frac{C_t}{(1 + r)^t}}
$$

ahol:
- $NPV$ a nettó jelenérték
- $C_0$ a kezdő tőke
- $C_t$ a $t$ időszak múlva rendelkezésre álló tőke
- $r$ a kamatláb (más néven hozam)
- $t$ a kamatozási időszak

#### Példa <!-- {{{ -->
Egy ismerőse egy olyan befektetési lehetőséget ajánl Önnek, ami 400.000 forint
befektetésére 1 év múlva 100.000, 2 év múlva 200.000, 3 év múlva 300.000 forint
visszafizetését garantálja. A hasonló kockázatú és futamidejű befektetések
elvárt hozama 10%. Mekkora nettó jelenértéket ígér a befektetés az Ön számára?
Érdemes-e ez alapján elfogadnia az ajánlatot?

$$
\begin{align}
NPV &= -400.000 + \frac{100.000}{(1 + 0.1)^1} + \frac{200.000}{(1 + 0.1)^2} + \frac{300.000}{(1 + 0.1)^3} \\
    &= -400.000 + 90.909 + 165.289 + 225.394 \\
    &= 81.592
\end{align}
$$

Érdemes elfogadni, mert $NPV > 0$.
<!-- }}} -->
