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


C:\Users\Admin>ping 192.168.88.1

Pinging 192.168.88.1 with 32 bytes of data:
Reply from 192.168.88.1: bytes=32 time<1ms TTL=64
Reply from 192.168.88.1: bytes=32 time<1ms TTL=64
Reply from 192.168.88.1: bytes=32 time<1ms TTL=64

Ping statistics for 192.168.88.1:
    Packets: Sent = 3, Received = 3, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 0ms, Average = 0ms

C:\Users\Admin>ping 192.168.88.2

Pinging 192.168.88.2 with 32 bytes of data:
Reply from 192.168.88.2: bytes=32 time<1ms TTL=64
Reply from 192.168.88.2: bytes=32 time<1ms TTL=64
Reply from 192.168.88.2: bytes=32 time<1ms TTL=64

Ping statistics for 192.168.88.2:
    Packets: Sent = 3, Received = 3, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 0ms, Average = 0ms

C:\Users\Admin>ping 192.168.88.3

Pinging 192.168.88.3 with 32 bytes of data:
Reply from 192.168.88.3: bytes=32 time=1ms TTL=64
Reply from 192.168.88.3: bytes=32 time=1ms TTL=64
Reply from 192.168.88.3: bytes=32 time=1ms TTL=64
Reply from 192.168.88.3: bytes=32 time=1ms TTL=64

Ping statistics for 192.168.88.3:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 1ms, Maximum = 1ms, Average = 1ms

C:\Users\Admin>

C:\Users\Admin>ping 192.168.88.4

Pinging 192.168.88.4 with 32 bytes of data:
Reply from 192.168.88.4: bytes=32 time<1ms TTL=64
Reply from 192.168.88.4: bytes=32 time<1ms TTL=64
Reply from 192.168.88.4: bytes=32 time<1ms TTL=64
Reply from 192.168.88.4: bytes=32 time<1ms TTL=64

Ping statistics for 192.168.88.4:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 0ms, Average = 0ms


#### 3.2. Sávszélesség mérése (iperf használata)



### 4. Eredmények és megjegyzések

**Ping tesztek eredményei:**
- 192.168.88.1: válaszidő... ms, csomagok: sikeres/sikertelen
- 192.168.88.2: válaszidő... ms, csomagok: sikeres/sikertelen
- 192.168.88.3: válaszidő... ms, csomagok: sikeres/sikertelen

**Sávszélesség teszt eredményei:**


---

**Dátum:** 2025. január 29.  
**Aláírás:** Visnyei Sándor
