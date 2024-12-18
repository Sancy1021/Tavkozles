# Jegyzőkönyv

## Mérési Feladat: Bitsebesség és Jelminőség Hatása

- **Mérés helye:** V3 labor
- **Mérés időpontja:** 2024. december 18.
- **Felelős személy:** Visnyei Sándor

## Cél

A feladat célja, hogy megértsük a különböző bitsebességek hatását a DVB-T jelek minőségére a Johansson 8202 modulátor használatával, különös figyelmet fordítva a többcsatornás jelgenerálásra.

---

## Eszközök

- 2db Johansson 8202 DVB-T modulátor
- DVB-T vevő (pl. TV vagy mérőműszer)
- RF kábelek
- METEK HD spektrum/jelszint analizátor
- Laptop jegyzőkönyv készítéséhez

---

## Feladat

1. **Modulátor konfiguráció:**
   - RF frekvenciák beállítása: 698 MHz és 690 MHz
   - Moduláció: 64-QAM
   - Sávszélesség: 8 MHz
   - Bitsebesség beállítása: 
     - TV1: 15 Mbps
     - TV2: 10 Mbps

2. **Bitsebesség és Jelminőség Összefüggése:**

   Az alábbi mérési eredmények alapján látható, hogy a bitsebesség növekedése általában csökkenti a jelminőséget, mivel a MER (Modulation Error Ratio) értékei alacsonyabbak lesznek magasabb bitsebességnél. Ugyanakkor az RF frekvencia is befolyásolja az eredményeket, mivel a különböző frekvenciák eltérően viselkedhetnek a jelek sugárzásakor.

3. **Összegzés és Kiértékelés:**

   **Összehasonlítás:**
   - A mérési eredmények alapján a legjobb jelminőséget (MER) a TV2 program érte el 690 MHz-en, 12.68 Mbps bitsebességgel, ahol az MER értéke 40 dB volt.
   - A TV1 programnál a legjobb MER érték 34.4 dB volt 14.029 Mbps bitsebességnél és 698 MHz frekvencián.
   - Az eredmények azt mutatják, hogy az alacsonyabb bitsebesség és kedvezőbb RF környezet jelentősen hozzájárul a jobb jelminőséghez.

   **Optimális beállítások:**
   - Az RF frekvenciák közötti interferencia minimalizálásához javasolt a csatornák gondos elosztása. A 690 MHz frekvencia jobb eredményeket adott, ezért előnyben részesíthető.
   - A jelminőség (MER) javítása érdekében érdemes alacsonyabb bitsebességet használni, különösen olyan programoknál, ahol a stabil jel elengedhetetlen.
   - A sugárzási teljesítményt növelni szükséges, különösen 698 MHz esetében, ahol a jelszint gyengébb volt.
   - Ajánlott adaptív modulációs technológiák alkalmazása, amelyek az aktuális környezeti feltételekhez igazítják a bitsebességet és a modulációt.

---

## Mérési eredmények

| Mérési paraméter         | RF frekvencia (MHz) | Program neve | Bitsebesség (Mbps) | Jelszint (dBm) | MER érték (dB) |
|--------------------------|---------------------|--------------|---------------------|----------------|----------------|
| Mérési eredmény 1        | 690 MHz             | TV2          | 12.68 Mbps          | -35.2 dBm      | 40 dB          |
| Mérési eredmény 2        | 698 MHz             | TV1          | 14.029 Mbps         | -31.9 dBm      | 34.4 dB        |
| Mérési eredmény 3        | 690 MHz             | TV2          | 18.9 Mbps (max)     | -35.2 dBm      | 39.4 dB        |

---

## Képek és Diagrammok

<details>
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0001.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0002.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0003.bmp"/>

---
<br>


   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0004.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0005.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0006.bmp"/>

---
<br>


   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0007.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/its_snapshot_0008.bmp"/>

---
<br>
   
   <img src="https://sancy1021.github.io/Tavkozles/05 Bitsebesség jelminőség mérés/9772640a-cde7-45e4-8f24-9ededfb55cda.png"/>
</details>   

---

