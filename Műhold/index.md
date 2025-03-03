# Távközlési Technikus Vizsga Jegyzőkönyv

## Vizsgafeladat: Műholdas vételi rendszer telepítése, konfigurálása és mérése

### Vizsgázó neve: Visnyei Sándor
### Dátum: 2025.02.03
### A mérést vezete: Sándor Péter
### Csoport: GYAK 1
### Évfolyam: 13E
### A mérés helyszíne: V3
### Munkafeladat leírása: Földfelszíni digitális TV vételi rendszer kiépítése, jelszintmérés, fejállomás beállítása és IPTV stream konfigurálása

## 1. Szükséges eszközök

- **Parabolaantenna**: D80 Mesh hálós acél parabola antenna (tripodra szerelve)
- **Műholdvevő fej (LNB)**: Inverto ULTRA vagy Ekselans SATCR LNB
- **Set-top box**: Amiko HD 8265+
- **Mérőműszer**: METEK HDD műholdas jelmérő
- **Koaxiális kábelek és csatlakozók** 
- **Jelosztó**: 2-es műholdas jelosztó
- **Szerelési eszközök**: villáskulcs

- ### 2. Antenna és LNB felszerelése 
- Antenna összeszerelése és rögzítése
- LNB felszerelése és polarizáció beállítása
- Jelosztó beépítése

### 3. Antenna beállítása és műhold azonosítása 
- telefonos iránytű segítségével beállítás (SatFinder)
- METEK HDD műszerrel műhold azonosítása és finomhangolás

- **Mérések és dokumentáció:**
  - Spektrum analizátor képe
    
  <img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0001.bmp"/>

  # M1 HD – Kódolt Csatorna

Ez a kép az **M1 HD** televíziócsatorna műsorának vételi adatait mutatja egy műholdas vagy kábeles dekóderen keresztül. A képernyőn egy figyelmeztetés látható, amely jelzi, hogy a csatorna **kódolt (Scrambled)**, és csak jogosultsággal rendelkező előfizetők számára érhető el.

## **Csatorna adatai:**
- **Szolgáltatás ID:** 101 (**M1 HD**)
- **Hálózat ID:** 158
- **ONID:** 106
- **Felbontás:** 1920×1080 (Full HD)

## **Videó és Audió adatok:**
- **VPID / Bitráta:** 1101 / **3.989220 Mb/s**
- **APID / Bitráta:** 1201 / **0.415802 Mb/s**

  
  <img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0002.bmp"/>
  
  <img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0003.bmp"/>
     
  - Jelszintek és jelminőség
  - Antenna pozíciók azimut195,7°  eleváció 33,6°
  - Kimenő feszültség és áramerősség az LNB-nél
  - Polarizáció
  - Transzponder adatok (frekvencia, szimbólumráta, FEC)
  - Időjárási körülmények

### 4. Kábelezés és eszközök csatlakoztatása
- Jel bevezetése a laborba
- LNB és set-top box összekapcsolása
- Set-top box és TV csatlakoztatása


### 5. Set-top box beállítása és csatornakeresés 
- Nyelv és régió beállítása
- Műhold és transzponder beállítása
- Automatikus csatornakeresés
- **Mérések és dokumentáció:**
  - Jelszintek és jelminőség
  - Transzponder adatok
  - Kimenő feszültség az LNB-re
  - Időjárási körülmények: napos

### 6. Jelszintmérés és dokumentáció 

<img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0002.bmp"/>
 
# Műholdas Jelszintmérés – Eutelsat 9A

## Mérési adatok:
- **Frekvencia:** 11958 MHz  
- **Polarizáció:** Vertikális  
- **Szimbólumsebesség:** 27500 kS/s  
- **Jelerősség:** 83.2 dBµV  
- **MER (Modulation Error Ratio):** 11.9 dB  
- **CBER (Channel Bit Error Rate):** 2.7E-2  

## Értékelés:
A mérés eredményei alapján a jelvétel stabil, de a minőség nem optimális, mivel a **MER érték 11.9 dB**, ami a határérték közelében van a jó vételhez.  
Ha szükséges, az **antennát finomhangolni lehet** a jobb jelerősség és minőség érdekében.


