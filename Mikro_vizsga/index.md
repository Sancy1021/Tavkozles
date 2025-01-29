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

<details>
   <img src="https://sancy1021.github.io/Tavkozles/Mikro_vizsga/meres4.PNG"/>
</details> 

#### 2.3. SOHO router beállítása AP módban

- WiFi beállítása:
  - SSID: **Gazda01**, Jelszó: **G1234567**

### 3. Hálózati tesztelés és hibakeresés

#### 3.1. Ping teszt végrehajtása

<pre>
   (pingek.txt)
</pre> 
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
