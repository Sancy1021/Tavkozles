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

  



  
  <img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0003.bmp"/>
  
  ## **Műholdas vétel mérési adatai:**  

- **Frekvencia:** 1358.0 MHz  
- **Műhold:** Eutelsat 9A  
- **Transzponder:** 11958V27500  
- **Moduláció:** DVB-S2 / 8PSK / 2/3  
- **Jelszint:** **83.0 dBuV**  
- **Zajmargó:** 4.7 dB  
- **MER (Modulációs hibaarány):** 11.5 dB  
- **CBER (Bitek előtti hibaarány):** 2.12E-2  
- **VBER (Végső hibaarány):** 0.00E-6  
- **Csomaghiba:** 0  
- **Eltelt idő:** 4 másodperc  

  ---
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


<img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0007.bmp"/>

A képernyő jobb alsó sarkában egy információs panel jelenik meg, amely a csatorna technikai adatait tartalmazza:

| Paraméter         | Érték |
|-------------------|----------------|
| **Service ID**    | 1003 |
| **Network ID**    | Unknown |
| **Resolution**    | 1920×1080 (Full HD) |
| **VPID / Bitrate** | 512 / 3.854752 Mb/s |
| **APID / Bitrate** | 662 / 0.358582 Mb/s |

## Egyéb jellemzők
- **FREE** – Ingyenes csatorna
- **HD** – Nagy felbontású adás
- **H264** – H.264 videókódolás
- **AC3** – Dolby Digital (AC3) hangformátum


<img src="https://sancy1021.github.io/Tavkozles/Műhold/its_snapshot_0009.bmp"/>

## Áttekintés
Ez a kép egy műholdas jelmonitorozó eszköz kijelzőjéről készült. Az eszköz egy **Astra 1** műholdas frekvenciát figyel (1724.0 MHz), és egy DVB-S2 modulációjú jelet elemez.

## Technikai adatok

| Paraméter          | Érték |
|--------------------|----------------|
| **Frekvencia**     | 1724.0 MHz |
| **Műhold**        | Astra 1 |
| **Transzponder**  | 12324V29700 |
| **Moduláció**     | DVB-S2 / 8PSK / 2/3 |
| **Jelerősség**    | 88.0 dBuV |
| **Zajmargó (Noise Margin)** | 6.5 |
| **MER (Modulation Error Ratio)** | 13.3 dB |
| **CBER (Channel Bit Error Rate)** | 7.07E-3 |
| **VBER (Viterbi Bit Error Rate)** | 0.00E-6 |
| **Csomaghibák (Packet Errors)** | 0 |
| **Eltelt idő** | 5 másodperc |

## Konstellációs Diagram
A képernyő jobb oldalán látható **Konstellációs diagram** megmutatja a digitális jel minőségét. A piros pontok elhelyezkedése a négypontos rácson az adás stabilitására és zajszintjére utal.

## Értelmezés
- **Jelerősség (Power)**: Erős (88.0 dBuV)
- **MER (Modulation Error Ratio)**: Közepes (13.3 dB)
- **CBER és VBER**: A CBER érték viszonylag magas (7.07E-3), ami hibás bitarányt jelez, míg a VBER értéke kiváló (0.00E-6), ami azt jelenti, hogy a hibajavító algoritmusok megfelelően működnek.
- **Konstellációs diagram**: A pontok szórása jelzi a jelerősség és a zajhatások egyensúlyát.

---
*Ez a kép egy műholdas jelerősség és minőségmérő kijelzőjéről készült, amely fontos információkat nyújt egy adott műholdas csatorna vételének állapotáról.*

<img src="https://sancy1021.github.io/Tavkozles/Műhold/20250304_084705.jpg"/>

## Áttekintés
Ez a kép egy műholdas jelkereső (**Signal Finder**) képernyőt mutat, amely a vevőegység által érzékelt műholdas adás minőségét és erősségét méri. A rendszer a **28.2E Astra 2E/2F/2G** műholdat vizsgálja az **11038 V 23000 2/3** transzponderrel.

## Technikai adatok

| Paraméter         | Érték |
|------------------|------|
| **SNR (Signal-to-Noise Ratio)** | 80.2 dB |
| **AGC (Automatic Gain Control)** | 99% |
| **BER (Bit Error Rate)** | 0 |
| **Lock (Jelzárás)** | (Zárolva) |
| **Tuner típusa** | DVB-S2 NIM (DVB-S2X) |
| **Keresési mód** | Előre beállított transzponder (Predefined transponder) |
| **Műhold** | 28.2E Astra 2E/2F/2G |
| **Transzponder** | 11038 V 23000 2/3 |

## Értelmezés
- **SNR (Jel-zaj arány)**: 80.2 dB, ami kiváló jelerősséget jelent.
- **AGC (Automatikus erősítés szabályzás)**: 99%, ami azt mutatja, hogy a rendszer maximálisan beállította az erősítést a lehető legjobb vétel érdekében.
- **BER (Bithibaarány)**: 0, ami azt jelzi, hogy nincs érzékelhető jelhiba.
- **Lock (Jelzárás)**: A vevőegység stabilan beállt a jelre.

## Felhasználói lehetőségek
A képernyő jobb oldalán egy műholdas antenna ikon látható egy iránytűvel, amely arra utal, hogy a felhasználó új keresést indíthat az **OK** gomb megnyomásával, vagy kiléphet az **EXIT** gombbal.

---
*Ez a kijelző egy műholdvevő beállítási és diagnosztikai funkcióját mutatja, amely segítséget nyújt a megfelelő műholdas jel megtalálásában és stabil vételében.*






