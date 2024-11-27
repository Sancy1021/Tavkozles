# Jegyzőkönyv: Johansson 6700 Profiler programozható antennaerősítő-szűrő használata

## 1. Eszközök Bekapcsolása és Bekötése
### Eszközök:
- Johansson 6700 Profiler programozható antennaerősítő-szűrő
- FM antenna (87-108 MHz)
- DVB-T szoba antenna (SMART HD550) (UHF: 470-862 MHz)
- Spektrum analizátor
- Koaxiális kábelek
- Laptop a beállítások elvégzéséhez és jegyzőkönyv készítéséhez

### Bekötés:
- Az FM antennát az FM bemenetre csatlakoztattuk, a DVB-T antennát pedig a VHF/UHF bemenetre.
- Koaxiális kábellel csatlakoztattuk a spektrum analizátort a Johansson 6700 Profiler kimenetéhez.
- A spektrum analizátor segítségével rögzítettük a bemeneti jeleket 45-1000 MHz között.

### Mért jelek (Spektrum analizátor):
- Az analízis során különböző jelek jelentek meg az adott frekvenciatartományokban.

## 2. Csatornaáthelyezés és Jelszint-Optimalizálás
### Csatornaáthelyezési Beállítások:
- **FM antenna**: 101,7 MHz → 183,7 MHz
- **DVB-T VHF antenna**: 5. csatorna → 10. csatorna (220 MHz → 230 MHz)
- **DVB-T UHF antenna**: 28. csatorna → 33. csatorna (500 MHz → 600 MHz)
- **Koax kábel (RF modulátor)**: KábelTV (CH22) → KábelTV (CH23) (600 MHz → 700 MHz)

### AGC (Automatikus Szintszabályzás):
- Az AGC funkciót aktiváltuk a Johansson 6700 Profilerben.
- A kimeneti jelszintet 100 dBu-ra állítottuk, hogy biztosítsuk az egységes jelszinteket.

### Bemeneti és Kimeneti Jelszintek (Spektrum analizátor mérésével):
- **FM antenna**:
  - Bemeneti jelszint: -30 dB
  - Kimeneti jelszint: -20 dB
- **DVB-T (VHF)**:
  - Bemeneti jelszint: -40 dB
  - Kimeneti jelszint: -30 dB
- **DVB-T (UHF)**:
  - Bemeneti jelszint: -35 dB
  - Kimeneti jelszint: -25 dB
- **Koax kábel (RF-modulátor)**:
  - Bemeneti jelszint: -45 dB
  - Kimeneti jelszint: -30 dB

## 3. Szűrő Beállítások és Interferencia Vizsgálat
### LTE Szűrő Tesztelése:
- Az LTE szűrő működését ellenőriztük a 790 MHz feletti interferenciák kiszűrésére.
- A spektrum analizátor segítségével megfigyeltük a kimeneti jeleket a szűrő be- és kikapcsolása után.

### Szűrő Hatása a Jelekre:
- A szűrő alkalmazása előtt és után mérve láttuk, hogy a 790 MHz feletti jelek csökkentek, és a jelminőség javult.

## 4. Jegyzőkönyv Készítése
| **Antenna típusa** | **Eredeti csatorna** | **Áthelyezett csatorna** | **Eredeti frekvencia** | **Áthelyezett frekvencia** | **Bemeneti jelszint (dB)** | **Kimeneti jelszint (dB)** |
|-----------------|----------------------|--------------------------|-------------------|---------------------|---------------------|------------------|
|                 | E28                  | CH 41                    | 530 MHz           | 634 MHz             | 63 dBu              |173.8dBu          |
| FM Antenna      | E31                  | CH 42                    | 554 MHz           | 642 MHz             | 64 dBu              |174.9dBu          |
|                 | E35                  | CH 43                    | 586 MHz           | 650 MHz             | 61 dBu              | 174.6 dBu        |
|                 | E41                  | CH 44                    | 634 MHz           | 658 MHz             | 48 dBu              | 169.7 dBu        |
| HDD 550         | E45                  | CH 45                    | 666 MHz           | 666 MHz             | 59 dBu              | 175.7 dBu        |
|                 | E48                  | CH 46                    | 690 MHz           | 674 MHz             | 56 dBu              | 174.8 dBu        |  




## Összegzés:
- A gyakorlat során sikeresen beállítottuk a Johansson 6700 Profiler antennaerősítőt és szűrőt.
- A jelek áthelyezésével és az AGC használatával elértük az egységes kimeneti jelszinteket.
- A szűrő alkalmazásával a 790 MHz feletti interferenciák jelentősen csökkentek.
- A mért adatok és a spektrum analizátor képei segítettek a megfelelő beállítások dokumentálásában és a gyakorlat sikeres végrehajtásában.

