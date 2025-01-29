# Jegyzőkönyv

**Vizsga neve:** Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése  

#### 1.Hálózati topológia tervezése és IP-címek

- **Mikrotik LHG18 LTE**: 192.168.88.1  
- **Mikrotik nRay 60GHz Master**: 192.168.88.2  
- **Mikrotik nRay 60GHz Slave**: 192.168.88.3  
- **Router (AP mód)**: 192.168.88.4  
- **Switch (ha szükséges)**: 192.168.88.254  
- **Kliens laptop**: 192.168.88.100-250 (DHCP-ből)

<details>
   <img src="https://sancy1021.github.io/Tavkozles/Mikro_vizsga/VisnyeiS Mikrotik.jpg"/>
</details>  

### 2. Eszközök telepítése és konfigurálása

#### 2.1. Mikrotik LHG18 LTE antenna beállítása

<details>
   <img src="https://sancy1021.github.io/Tavkozles/Mikro_vizsga/teszt1-3.PNG"/>
</details>   


#### 2.2. Mikrotik nRay 60GHz antennapár beállítása

##### Master antenna (192.168.88.2) konfigurálása:
- Csatlakoztassa az eszközhöz Ethernet kábellel.
- Nyisson meg egy böngészőt vagy a WinBox alkalmazást, és lépjen be: http://192.168.88.2
  - Felhasználónév: **admin**, jelszó: **antennán**.
- Állítsa be az eszközt "Master" módban.
- Ellenőrizze az IP címeket, hogy a Slave antenna csatlakozni tudjon.

##### Slave antenna (192.168.88.3) konfigurálása:
- Ismételje meg a fenti lépéseket a 192.168.88.3 IP-n.
- Állítsa be az eszközt "Slave" módban, és csatlakoztassa a Master antennához.
- Ellenőrizze a kapcsolat minőségét és rögzítse a jelminőségi paramétereket: WIRELESS 60G STATUS.

#### 2.3. SOHO router beállítása AP módban

- Csatlakoztassa a routert a laptophoz Ethernet kábellel.
- Nyisson egy parancssort és keresse meg a router IP címét:
  - `arp -a`
- Nyisson meg egy böngészőt és lépjen be az IP címére.
- WiFi beállítása:
  - SSID: **GazdaXX**, Jelszó: **G1234567** (XX - azonosító szám, pl. Gazda01, Gazda02).
- Kapcsolja AP módba és állítsa be az IP-t a 192.168.88.xxx tartományba.

### 3. Hálózati tesztelés és hibakeresés

#### 3.1. Ping teszt végrehajtása

- Nyisson egy parancssort és pingelje meg a következő eszközöket:
  - `ping 192.168.88.1`
  - `ping 192.168.88.2`
  - `ping 192.168.88.3`
  - `ping 192.168.88.4`

Ha problémák lépnek fel, használja a következő parancsokat a hálózati hibák elhárításához:

- `ipconfig`
- `ipconfig /all`
- `ipconfig /release`
- `ipconfig /renew`

#### 3.2. Sávszélesség mérése (iperf használata)

- Telepítse az iperf3 szoftvert a laptopokra:
  - `winget install iperf3`
- Az egyik laptopon futtassa szerverként:
  - `iperf3 -s`
- A másik laptopon futtassa kliensként:
  - `iperf3 -c 192.168.88.xxx`
- Rögzítse az eredményeket és mérje meg a sávszélességet.

### 4. Eredmények és megjegyzések

**Ping tesztek eredményei:**
- 192.168.88.1: válaszidő... ms, csomagok: sikeres/sikertelen
- 192.168.88.2: válaszidő... ms, csomagok: sikeres/sikertelen
- 192.168.88.3: válaszidő... ms, csomagok: sikeres/sikertelen

**Sávszélesség teszt eredményei:**
- Kliens IP: 192.168.88.xxx
- Letöltési sebesség: ... Mbps
- Feltöltési sebesség: ... Mbps

A tesztelések alapján minden eszköz sikeresen csatlakozott a hálózathoz, és a szükséges beállítások megfelelően működnek.

---

**Dátum:** 2025. január 29.  
**Aláírás:** Visnyei Sándor
