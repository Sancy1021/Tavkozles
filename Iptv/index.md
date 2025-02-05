# Távközlési Technikus Vizsga Jegyzőkönyv

## Vizsgafeladat: DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása

### Vizsgázó neve: Visnyei Sándor
### Dátum: 2025.02.03
### A mérést vezete: Sándor Péter
### Csoport: GYAK 1
### Évfolyam: 13E
### A mérés helyszíne: V3
### Munkafeladat leírása: Földfelszíni digitális TV vételi rendszer kiépítése, jelszintmérés, fejállomás beállítása és IPTV stream konfigurálása

---

## 1. Előkészületek

- **Szükséges eszközök ellenőrzése**:
  - Antenna: Iskra P2845
  - Fejállomás: LEMCO SCL-824CT Ip cím: 192.168.1.200 
  - Set-top box: MAG IPTV
  - Hálózati eszköz: IGMP protokollt támogató router
  - Mérőműszer: METEK HDD digitális TV jelmérő
  - Kábelek és csatlakozók: RF csatlakozó, RF16
  - SOHO router  TP-Link Archer C7

- **Multiplex keresése a Miskolc, Avasi adótoronyból**:
  - Frekvencia: [634Mhz]
  - Teljesítmény: [Teljesítmény]
  - Polarizáció: [DNY 234°]
  - Adás típusa: [DVBT]
  
---

## 2. Antenna felszerelése és beállítása

- **Antenna kiválasztása**:
  - Választott antenna: Kültéri
  - Elhelyezés: V3
  
- **Antenna beállítása**:
  - Iránytű és dőlésszögmérőt használtunk az adótorony irányba történő beállításhoz.
  - METEK HDD mérőműszerrel végeztünk finomhangolás.
  
- **Antenna pozíció**:
  - Polarizáció beállítása: [DNY 234°]
    
   <details>
   <img src="https://sancy1021.github.io/Tavkozles/Iptv/Kando-avaskilato.png"/>
   </details> 

---

## 3. Kábelezés, mérési pontok kialakítása és jel bevezetése a fejállomásba

- **Kábelezés**:
  - Koaxiális kábel és osztó csatlakoztatása.
  - Jel elosztása a megfelelő fejállomás bemenetekre.

- **Jelmérés**:
  - Kiemelt multiplexek jelerőssége: 50.3dBuV
  - Jeleket osztotunk az IPTV rendszerbe.

   <details>
   <img src="https://sancy1021.github.io/Tavkozles/Iptv/its_snapshot_0001.bmp"/>
   </details> 

---

## 4. Fejállomás beállítása és IPTV stream konfigurálása

- **Fejállomás beállítása**:
  - Minden bemenetre megfelelő multiplex hozzárendelése.
  - DVB-T jelek IP streamre konvertálása.

- **Multicast IP tartomány konfigurálása**:
  - Multicast IP tartomány: 192.168.1.100 tól 192.168.169.249 defaultgateway 192.168.1.1
  - IPTV csatornák konfigurálása.

- **Router konfigurálása**:
  - DHCP szerver és IGMP beállítása.
  - Hálózati kapcsolat tesztelése és IPTV Set-top-box (MAG IPTV) csatlakoztatása.
  
- **IPTV Set-top-box csatornakeresése**:
  
| #  | Input  | Program title              | OriginalService ID | LCN1..1023 | Encrypted | TS Output | OutputService ID | IP address   | IP port | Protocol  |
|----|--------|-----------------------------|--------------------|------------|-----------|-----------|------------------|--------------|---------|----------|
| 1  | Input 1 | M1 HD                      | 100                | 0          | FTA       | 1         | 100              | 224.0.0.1    | 1001    | UDP      |
| 2  | Input 1 | M4 Sport HD                | 101                | 0          | FTA       | 1         | 101              | 224.0.0.1    | 1002    | UDP      |
| 3  | Input 1 | Duna HD                    | 102                | 0          | FTA       | 1         | 102              | 224.0.0.1    | 1003    | UDP      |
| 4  | Input 1 | DunaW/M4Sport+             | 103                | 0          | FTA       | 2         | 103              | 224.0.0.1    | 1004    | UDP      |
| 5  | Input 1 | Kossuth Radio              | 130                | 0          | FTA       | 4         | 130              | 224.0.0.1    | 1005    | UDP      |
| 6  | Input 1 | Petofi Radio               | 131                | 0          | FTA       | 4         | 131              | 224.0.0.1    | 1006    | UDP      |
| 7  | Input 1 | Bartok Radio               | 132                | 0          | FTA       | 4         | 132              | 224.0.0.1    | 1007    | UDP      |
| 8  | Input 1 | Danko Radio                | 133                | 0          | FTA       | 4         | 133              | 224.0.0.1    | 1008    | UDP      |
| 10 | Input 2 | M2 HD                      | 200                | 0          | FTA       | 1         | 200              | 224.0.0.1    | 1010    | UDP      |
| 11 | Input 2 | M5 HD                      | 201                | 0          | FTA       | 2         | 201              | 224.0.0.1    | 1011    | UDP      |
| 12 | Input 2 | TV2                        | 202                | 0          | FTA       | 1         | 202              | 224.0.0.1    | 1012    | UDP      |
| 13 | Input 2 | RTL                        | 203                | 0          | FTA       | 1         | 203              | 224.0.0.1    | 1013    | UDP      |
| 14 | Input 2 | MAX4                       | 206                | 0          | FTA       | 2         | 206              | 224.0.0.1    | 1014    | UDP      |
| 15 | Input 2 | Spektrum Home +            | 207                | 0          | FTA       | 2         | 207              | 224.0.0.1    | 1015    | UDP      |
| 16 | Input 2 | MinDig TV Plusz Info       | 208                | 0          | FTA       | 2         | 208              | 224.0.0.1    | 1016    | UDP      |
| 37 | Input 3 | HEVC teszt                 | 524                | 0          | FTA       | 2         | 524              | 224.0.0.1    | 1037    | UDP      |
| 39 | Input 4 | Miskolc TV                 | 1000               | 0          | FTA       | 2         | 1000             | 224.0.0.1    | 1039    | UDP      |


---

## 5. Jelszintmérés és dokumentáció

- **Antenna mérések**:
  - Spektrum analizátor képe:
    
   <details>
   <img src="https://sancy1021.github.io/Tavkozles/Iptv/its_snapshot_0001.bmp"/>
   </details> 

  - Jelszintek: 51dBμV
  - BER: 7,57
  - MER: 23.6dB
  - Multiplex adatok: Frekvencia, szimbólumráta, FEC
  - Időjárási körülmények: 5°C 3,2m/s
  - Páratartalóm: 68%

- **Fejállomás utáni mérések**:
  
   <details>
   <img src="https://sancy1021.github.io/Tavkozles/Iptv/Képernyőkép 2025-02-03 123233.png"/>

   <img src="https://sancy1021.github.io/Tavkozles/Iptv/41-48ch.png"/>
   </details> 


---

## 6. IPTV vizsgálati eszközök telepítése és használata

- **Eszközök telepítése**:
  - VLC, Wireshark, FFmpeg, iPerf3 telepítése sikeresen.
  - Hálózati teljesítménymérés és multicast forgalom vizsgálata iPerf3 és Wireshark segítségével.

- **IPTV stream rögzítése és elemzése**:
  - FFmpeg használata az IPTV stream mentésére és elemzésére.
  - Csomagvesztés és késleltetés vizsgálata.

---

## 7. Mérések és eredmények dokumentálása

- **Mért adatok**:
  - Jelerősség (dBμV): [50.3]
    
    <details>
      
    <img src="https://sancy1021.github.io/Tavkozles/Iptv/its_snapshot_0003 (1).bmp"/>

    <img src="https://sancy1021.github.io/Tavkozles/Iptv/Képernyőkép 2025-02-05 131512.png"/>

    <img src="https://sancy1021.github.io/Tavkozles/Iptv/Képernyőkép 2025-02-05 131337.png"/>
  
    <img src="https://sancy1021.github.io/Tavkozles/Iptv/Képernyőkép 2025-02-05 131210.png"/>

    <img src="https://sancy1021.github.io/Tavkozles/Iptv/Képernyőkép 2025-02-05 130947.png"/>
    
    </details> 

