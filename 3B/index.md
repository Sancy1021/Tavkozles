# Jegyzőkönyv: Távközlés 3B: Amplitúdómoduláció vizsgálata a GRF-1300A trénerrel

- **Mérés helye:** V3 labor
- **Mérés időpontja:** 2025.02.10
- **Felelős személy:** Visnyei Sándor
- **Évfolyam:** 13E
  

## 1. Bevezetés

A kísérlet célja az amplitúdómoduláció (AM) előállítása és spektrális jellemzőinek vizsgálata a GRF-1300A RF és kommunikációs tréner segítségével. A feladat során különböző RF vivőfrekvenciák és moduláló jelek beállításával, valamint 100% és 63%-os modulációs mélységek alkalmazásával vizsgáljuk az AM jel spektrumát, jelszintjét, sávszélességét és modulációs mélységét. A mérési eredmények dokumentálásra kerülnek.

## 2. Használt eszközök

- **GRF-1300A RF és kommunikációs tréner**
- **GSP-730 Spektrumanalizátor**
- **HMO-1002 Digitális tárolós oszcilloszkóp**
- **RF vezeték: 2db 100mm, 1db 800mm**
- **Adapter SMA**

  
  <img src="https://sancy1021.github.io/Tavkozles/3B/grf-1300a.jpg"/>


  <img src="https://sancy1021.github.io/Tavkozles/3B/hmo1002-hero-1200x735-White-b.jpg"/>



## 3. A kísérlet lépései

### Beállítások és első mérés

1. **RF vivőfrekvencia beállítása:** 
   - A GRF-1300A tréner RF kimenetén a vivőfrekvenciát **880 MHz**-re állítottuk.

2. **Moduláló jel előállítása:**
   - A jelgenerátor segítségével **100 kHz-es szinuszjelet** állítottunk elő, amelyet a tréner moduláló bemenetére csatlakoztattunk.

3. **Modulációs mélység beállítása:**
   - **100%-os modulációs mélységet 6dB** állítottunk be.


### Második mérés

1. **Frekvencia módosítása:**
   - A vivőfrekvenciát **900 MHz**-re állítottuk.

2. **Moduláló jel módosítása:**
   - A moduláló jelet **500 kHz**-re módosítottuk.

3. **Modulációs mélység beállítása:**
   - **63%-os modulációs mélységet 10dB** állítottunk be.

## 4. Eredmények

### Első mérés (880 MHz vivőfrekvencia, 100 kHz moduláló jel, 100%-os modulációs mélység)

- **Jelszint:** A mért jelszint az 880 MHz-es vivőfrekvencián a várt értékeknek megfelelően alakult.
- **Spektrumkép:** A spektrumkép egyértelműen mutatta a mellékképeket a vivőfrekvencia körül.
- **Moduláló jel szintje:** Az oszcilloszkópon mért Vpp érték a 100%-os modulációs mélységhez illeszkedett.
- **Modulációs mélység:** A modulációs mélység a várt 100%-os értéket mutatta.
- **Sávszélesség:** A sávszélesség megfelelt az elméleti számításoknak a 100%-os modulációs mélység mellett.


  <img src="https://sancy1021.github.io/Tavkozles/3B/meres900Mhz.jpg"/>


  <img src="https://sancy1021.github.io/Tavkozles/3B/meresVpp 1.24V.png"/>


### Második mérés (900 MHz vivőfrekvencia, 500 kHz moduláló jel, 63%-os modulációs mélység)

- **Jelszint:** A mért jelszint a 900 MHz-es vivőfrekvencián a várt értékekhez közel állt.
- **Spektrumkép:** A spektrumkép a mellékképeket a vivőfrekvencia körül mutatta, amelyek a 63%-os modulációs mélység hatását tükrözik.
- **Moduláló jel szintje:** Az oszcilloszkópon mért Vpp érték a 63%-os modulációs mélységhez illeszkedett.
- **Modulációs mélység:** A modulációs mélység a 63%-os értéket mutatta, amely megfelelt a beállításoknak.
- **Sávszélesség:** A sávszélesség a 63%-os modulációs mélység mellett a vártnak megfelelően alakult.

  <img src="https://sancy1021.github.io/Tavkozles/3B/meres880Mhz.jpg"/>


  <img src="https://sancy1021.github.io/Tavkozles/3B/meresVpp 1.19V.png"/>


## 5. Következtetések

A kísérlet során sikerült az amplitúdómodulációs jelet előállítani és annak spektrális jellemzőit meghatározni. Az eredmények alátámasztották a beállított paraméterek helyességét és a modulációs mélység, valamint a sávszélesség várható viselkedését.
