# Mérési Jegyzőkönyv: Antennák Teljesítménye és Jelminőség Összehasonlítása

## 1. Alapadatok

- **Dátum**: 2024. november 13.
- **Helyszín**: [V3 Labor]
- **Időpont**: [Kezdés időpontja] - [Befejezés időpontja]

## 2. Eszközök

- Johansson 8202 DVB-T modulátor
- ISKRA P20 LOGPER antenna (vételre)
- ISKRA P2845 antenna (vételre)
- IKUSI FLASHD C48 antenna (vételre)
- Philips SDV5228 (adó oldalra)
- RF kábelek
- DVB-T vevő (pl. TV vagy mérőműszer)
- METEK HD spektrum/jelszint analizátor
- Laptop a jegyzőkönyv készítéséhez

---

## 3. Mérés Paraméterek és Beállítások

- **RF frekvencia**: Szabad sáv, amibe nem zavar bele az adás.
- **Moduláció**: 16-QAM
- **Sávszélesség**: 8 MHz
- **Jelszint**: -10 dBm
- **Antenna Magasságai**: 144cm 
   
A modulátor beállításai állandóak maradnak az egész mérés során, csak az antenna típusa változik.

---

## 4. Mérési Eredmények

### 4.1. Mérés 1: 490 MHz Frekvencián

| **Antenna Típusa**     | **RF Frekvencia (MHz)** | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER Érték (dB)** |
|------------------------|-------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER       | 490                     | [-56,5dBm]          | [9,2Mbps]              | [27,3dB]           |
| ISKRA P2845            | 490                     | [-56,4dBm]          | [9,5Mbps]              | [27,7dB]           |
| IKUSI FLASHD C48       | 490                     | [-59,2dBm]          | [8,7Mbps]              | [26,5dB]           |

### 4.2. Mérés 2: 610 MHz Frekvencián

| **Antenna Típusa**     | **RF Frekvencia (MHz)** | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER Érték (dB)** |
|------------------------|-------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER       | 610                     | [eredmény]          | [eredmény]             | [eredmény]         |
| ISKRA P2845            | 610                     | [eredmény]          | [eredmény]             | [eredmény]         |
| IKUSI FLASHD C48       | 610                     | [eredmény]          | [eredmény]             | [eredmény]         |

### Mért képek:

<details>
    <summary>Iskra P20 LOGPER:</summary>
    Kép: 490 MHz  
    ![Iskra P20 LOGPER](https://github.com/Sancy1021/Tavkozles2/blob/main/Antenna%20teljes%C3%ADtm%C3%A9ny%20vs.%20jelszint/its_snapshot_0002.bmp)
</details>

<br>

<details>
    <summary>ISKRA P2845:</summary>
    2. kép: 490 MHz  
    !(Antenna teljesítmény vs. jelszint/its_snapshot_0001.bmp)
</details>

<br>

<details>
    <summary>IKUSI FLASHD C48:</summary>
    Kép: 490 MHz  
    ![IKUSI FLASHD C48](https://github.com/1SzatmariAndras6/TAVKOZLES2/blob/main/JEGYZOKONYV/03.%20Antenna%20teljesítmény%20vs.%20jelszint/its_snapshot_0003.bmp)
</details>

---

## 5. Kiértékelés

### 5.1. Jelminőség Összehasonlítása

- **A legjobb antenna és frekvencia kombináció**:
  - [Példa: Az ISKRA P20 LOGPER antenna biztosította a legjobb jelminőséget a 522 MHz frekvencián.]
  
- **Jelszint és MER**:
  - A mérési eredmények alapján az ISKRA P20 LOGPER antenna a legstabilabb jelszinttel és a legjobb MER értékkel rendelkezett a 522 MHz-es frekvencián.
  
- **Bitsebesség**:
  - A legnagyobb bitsebességet az IKUSI FLASHD C48 antenna biztosította a 610 MHz frekvencián.

### 5.2. Beváltás és Értékelés

- **Antennák típusai és teljesítményük**:
  - Az ISKRA P20 LOGPER antenna jobban teljesített alacsonyabb frekvenciákon, míg az IKUSI FLASHD C48 antenna a magasabb frekvenciákon mutatott jobb teljesítményt.
  - A különböző antenna típusok közötti eltérés magyarázható az antenna iránykarakterisztikájával és nyereségével.

---

## 6. Összegzés

- **Mérések időtartama**:
  - Modulátor beállítása, antennák felszerelése: 30 perc
  - Mérések három antennával: 60 perc
  - Jegyzőkönyv készítése és kiértékelés: 30 perc

- **Legjobb antenna**: [Melyik antenna biztosította a legjobb jelminőséget és miért?]

---

**Jegyzőkönyv vezetője**: [Visnyei Sándor]  
**Jegyzőkönyv hitelesítő**: [Sándor Péter]

