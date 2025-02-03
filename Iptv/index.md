# Távközlési Technikus Vizsga Jegyzőkönyv

## Vizsgafeladat: DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása

### Vizsgázó neve: Visnyei Sándor
### Dátum: 2025.02.03
### Munkafeladat leírása: Földfelszíni digitális TV vételi rendszer kiépítése, jelszintmérés, fejállomás beállítása és IPTV stream konfigurálása

---

## 1. Előkészületek

- **Szükséges eszközök ellenőrzése**:
  - Antenna: [Antenna típus, pl. beltéri/kültéri]
  - Fejállomás: LEMCO SCL-824CT
  - Set-top box: MAG IPTV
  - Hálózati eszköz: IGMP protokollt támogató router
  - Mérőműszer: METEK HDD digitális TV jelmérő
  - Kábelek és csatlakozók előkészítve

- **Multiplex keresése a Miskolc, Avasi adótoronyból**:
  - Frekvencia: [Frekvencia]
  - Teljesítmény: [Teljesítmény]
  - Polarizáció: [Polarizáció]
  - Adás típusa: [Adás típusa]
  
---

## 2. Antenna felszerelése és beállítása

- **Antenna kiválasztása**:
  - Választott antenna: [Beltéri/kültéri]
  - Elhelyezés: [Vételi hely pontos megadása]
  
- **Antenna beállítása**:
  - Iránytű és dőlésszögmérő használata az adótorony irányba történő beállításhoz.
  - METEK HDD mérőműszerrel végzett finomhangolás.
  
- **Antenna pozíció**:
  - [Irány/pozíció megadása]
  - Polarizáció beállítása: [H/V]

---

## 3. Kábelezés, mérési pontok kialakítása és jel bevezetése a fejállomásba

- **Kábelezés**:
  - Koaxiális kábel és osztó csatlakoztatása.
  - Jel elosztása a megfelelő fejállomás bemenetekre.

- **Jelmérés**:
  - Kiemelt multiplexek jelerőssége: [Jelerősség]
  - Jelek elosztása az IPTV rendszerbe.

---

## 4. Fejállomás beállítása és IPTV stream konfigurálása

- **Fejállomás beállítása**:
  - Minden bemenetre megfelelő multiplex hozzárendelése.
  - DVB-T jelek IP streamre konvertálása.

- **Multicast IP tartomány konfigurálása**:
  - Multicast IP tartomány: [IP tartomány]
  - IPTV csatornák konfigurálása.

- **Router konfigurálása**:
  - DHCP szerver és IGMP beállítása.
  - Hálózati kapcsolat tesztelése és IPTV Set-top-box (MAG IPTV) csatlakoztatása.
  
- **IPTV Set-top-box csatornakeresése**:
  - Ellenőrzés: [Csatornák megtalálása és tesztelése]

---

## 5. Jelszintmérés és dokumentáció

- **Antenna mérések**:
  - Spektrum analizátor képe: [Spektrum kép mellékelése]
  - Jelszintek: [dBμV]
  - SNR: [dB]
  - BER: [Bit Error Rate]
  - MER: [Modulation Error Ratio]
  - Csillapítás: [dB]
  - Multiplex adatok: Frekvencia, szimbólumráta, FEC
  - Időjárási körülmények: [Hőmérséklet, szélsebesség]

- **Fejállomás utáni mérések**:
  - Multicast IP címek ellenőrzése.
  - IPTV stream stabilitásának mérése.
  - Hálózati késleltetés: [Késleltetés mérése]
  - Csomagvesztés vizsgálata: [Csomagvesztés mérése]
  - Stream adatok: [Adatok]

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
  - Jelerősség (dBμV): [Érték]
  - Jel-zaj viszony (SNR): [Érték d

