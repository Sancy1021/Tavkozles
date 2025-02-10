# Jegyzőkönyv: Távközlés 3B: Amplitúdómoduláció vizsgálata a GRF-1300A trénerrel

## 1. Bevezetés

- **Mérés helye:** V3 labor
- **Mérés időpontja:** 2025.02.10
- **Felelős személy:** Visnyei Sándor

A kísérlet célja az amplitúdómoduláció (AM) előállítása és spektrális jellemzőinek vizsgálata a GRF-1300A RF és kommunikációs tréner segítségével. A feladat során megismerkedünk az AM jel spektrumával, valamint mérjük a jelszintet, a sávszélességet és a modulációs mélységet. A kísérlet során használt eszközök és a mérési feladatok részletesen ismertetésre kerülnek.

## 2. Használt eszközök

- **GRF-1300A RF és kommunikációs tréner**
- **Spektrumanalizátor** (a tréner része)
- **Jelgenerátor** a moduláló jel előállításához

<details>
  <summary>Kép megtekintése</summary>
  
  <img src="https://sancy1021.github.io/Tavkozles/3B/"/>

  <img src="https://sancy1021.github.io/Tavkozles/3B/"/>

</details>

## 3. A kísérlet lépései

### 3.1 Beállítások

1. **RF vivőfrekvencia beállítása:** 
   - A GRF-1300A tréner RF kimenetén a vivőfrekvenciát **900 MHz**-re állítottuk.
   
2. **Moduláló jel előállítása:**
   - A jelgenerátor segítségével **1 kHz-es szinuszjelet** állítottunk elő, amelyet a tréner moduláló bemenetére csatlakoztattunk.

3. **Spektrumanalizátor csatlakoztatása:**
   - A tréner RF kimenetét csatlakoztattuk a spektrumanalizátorhoz a méréshez.

### 3.2 Mérések

#### 3.2.1 Jelszint mérése

A spektrumanalizátor segítségével megmértük az AM jel **jelszintjét** a megfelelő frekvencián, az alábbi paraméterekkel:
   - Vivőfrekvencia: 900 MHz
   - Moduláló jel: 1 kHz

#### 3.2.2 Spektrumkép mentése és kiértékelése

A spektrumanalizátor segítségével rögzítettük az AM jel spektrumképét. Az elemzés során az alábbi jellemzők figyelhetők meg:
   - A vivőfrekvencián megjelenik a **fundamentális jel**.
   - A mellékképek (**sidebands**) a vivőfrekvencia körül találhatók, amelyek a moduláció hatására jönnek létre.
   - A spektrumot mentettük a későbbi kiértékeléshez.

#### 3.2.3 Modulációs mélység mérése

A spektrum alapján meghatároztuk az **amplitúdómoduláció mélységét** a következőképpen:
   - A modulációs mélység az alapfrekvenciától való eltérés mértékét mutatja, amely a jel amplitúdója és a vivőfrekvencia közötti kapcsolatot jellemzi.

#### 3.2.4 Sávszélesség meghatározása

A sávszélességet a spektrum alapján mérve meghatároztuk, figyelembe véve a mellékképek távolságát és az AM jel által igényelt sávszélességet.

## 4. Eredmények

- **Jelszint:** A mérés során a jelszint megfelelőnek bizonyult a 900 MHz-es vivőfrekvencián.
- **Spektrumkép:** A spektrum egyértelműen mutatta a mellékképeket a vivőfrekvencia körül, amelyek az AM jel modulációjának eredményeként jelentek meg.
- **Modulációs mélység:** A mérés alapján a modulációs mélység a várt értékekhez közel volt, amely megfelel a 1 kHz-es moduláló jelnek.
- **Sávszélesség:** A sávszélesség meghatározása szerint a jel szélessége a modulációs mélység és a mellékképek alapján kiértékelhető volt.

## 5. Következtetések

A kísérlet sikeresen demonstrálta az amplitúdómoduláció elvét a GRF-1300A tréner segítségével. A mérési eredmények alátámasztják, hogy a vivőfrekvancián történő AM jel előállítása és annak spektrális vizsgálata megfelelő eszközökkel és beállításokkal végezhető el. A jelszint, a sávszélesség és a modulációs mélység meghatározása az elvárt eredményekhez vezetett.

## 6. Mellékletek

- Spektrumkép
- Mért adatokat tartalmazó táblázat

