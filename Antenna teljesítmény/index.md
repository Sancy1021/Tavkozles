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

| **Antenna Típusa**     | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER Érték (dB)** |
|------------------------|--------------------|------------------------|--------------------|
| ISKRA P20 LOGPER       | [-56,5dBm]         | [9,2Mbps]              | [27,3dB]           |
| ISKRA P2845            | [-56,4dBm]         | [9,5Mbps]              | [27,7dB]           |
| IKUSI FLASHD C48       | [-59,2dBm]         | [8,7Mbps]              | [26,5dB]           |

### 4.2. Mérés 2: 610 MHz Frekvencián

| **Antenna Típusa**     | **RF Frekvencia (MHz)** | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER Érték (dB)** |
|------------------------|-------------------------|--------------------|------------------------|--------------------|
| ISKRA P20 LOGPER       | 730                     | [-60,3dBm]         | [9,3Mbps]              | [23dB]             |
| ISKRA P2845            | 730                     | [-59,5dBm]         | [9.59Mbps]             | [27,5dB]           |
| IKUSI FLASHD C48       | 730                     | [-62,8dBm]         | [9,81Mbps]             | [23,7dB]           |

### Mért képek:

### 1. Mérés:
<details>
    <summary>Iskra P20 LOGPER:</summary>
    Kép: 490 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0001.bmp"/>
</details>

<br>

<details>
    <summary>ISKRA P2845:</summary>
    2. kép: 490 MHz  
    <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0002.bmp"/>
</details>

<br>

<details>
    <summary>IKUSI FLASHD C48:</summary>
    Kép: 490 MHz  
    <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0003.bmp"/>
</details>

<br>

<details>
    <summary>Grafikon:</summary>
    Kép: 490 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0004.bmp.png"/>
</details>

<br>

<details>
    <summary>Diagram:</summary>
    Kép: 490 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0005.bmp.png"/>
</details>

<br>

### 2. Mérés:
<details>
    <summary>IKUSI FLASHD C48:</summary>
    Kép: 730 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0051.bmp"/>
</details>

<br>

<details>
    <summary>ISKRA P2845:</summary>
    Kép: 730 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0053.bmp"/>
</details>

<br>

<details>
    <summary>ISKRA P20 LOGPER :</summary>
    Kép: 730 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0054.bmp"/>
</details>

<br>

<details>
    <summary>Grafikon:</summary>
    Kép: 730 MHz  
   <img src="https://sancy1021.github.io/Tavkozles2/Antenna%20teljes%C3%ADtm%C3%A9ny/its_snapshot_0055.jpg"/>
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

# ISKRA P2845 teljesített a legjobban a legtöbb paraméter alapján:

- **490 MHz-en** a legjobb jelszintet és MER értéket nyújtotta.
- **730 MHz-en** a legjobb jelszintet és MER értéket nyújtotta, valamint bitsebességben is kiemelkedő volt.

### Ha a bitsebesség kiemelten fontos:
- **IKUSI FLASHD C48** 730 MHz-en jobb volt.

## Az **ISKRA P2845** tekinthető a legjobb általános teljesítményű antennának! 🎯
---

**Jegyzőkönyv vezetője**: [Visnyei Sándor]  
**Jegyzőkönyv hitelesítő**: [Sándor Péter]

