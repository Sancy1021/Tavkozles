Távközlési Technikus Vizsgafeladat
Vizsga neve: Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése
Időtartam: 2 óra

1. Előkészítés és tervezés
1.1. Eszközök gyári beállításainak visszaállítása (Factory Reset)
Mikrotik LHG18 LTE antenna resetelése:
Az eszközt áramtalanítani kell.
Nyomja meg és tartsa lenyomva a reset gombot.
Csatlakoztassa vissza az áramot, miközben nyomva tartja a reset gombot.
Tartsa lenyomva, amíg a status LED villogni nem kezd (kb. 5 másodperc).
Engedje el a gombot. Az eszköz ekkor visszaáll a gyári beállításokra.
Mikrotik nRay 60GHz antennák resetelése:
Ismételje meg a fenti lépéseket mindkét antennán (192.168.88.2 és 192.168.88.3).
SOHO router resetelése:
Keresse meg a reset gombot az eszközön.
Áramtalanítás után nyomja meg a reset gombot.
Kapcsolja vissza az eszközt, és tartsa lenyomva 10 másodpercig, amíg a gyári visszaállítás befejeződik.
1.2. Hálózati topológia tervezése
Rajzolja meg a hálózati diagramot, amely tartalmazza az összes eszközt és azok kapcsolatait (használja a Draw.io alkalmazást). Az IP-címek a következőképpen legyenek kiosztva:

Mikrotik LHG18 LTE: 192.168.88.1
Mikrotik nRay 60GHz Master: 192.168.88.2
Mikrotik nRay 60GHz Slave: 192.168.88.3
Router (AP mód): 192.168.88.4
Switch (ha szükséges): 192.168.88.254
Kliens laptop: 192.168.88.100-250 (DHCP-ből)
IP-címek és alhálózati maszk:
Alhálózati maszk: 255.255.255.0
Ügyeljen az IP-ütközések elkerülésére!
2. Eszközök telepítése és konfigurálása
2.1. Mikrotik LHG18 LTE antenna beállítása
Csatlakoztassa a laptopot az Mikrotik LHG18 LTE-hez Ethernet kábellel.
Állítsa be a laptop IP-címét az antenna konfigurálásához:
IP: 192.168.188.2
Alhálózati maszk: 255.255.255.0
Átjáró (gateway): 192.168.188.1
Nyisson meg egy böngészőt, vagy a WinBox alkalmazást és lépjen be az LTE antenna konfigurációs felületére:
Cím: http://192.168.188.1
Felhasználónév: admin, jelszó: antennán.
Konfigurálja az LTE kapcsolatot a szolgáltató APN beállításaival.
Állítsa be az antenna IP-jét: 192.168.88.1, és engedélyezze a DHCP-t a 192.168.88.100-250 IP tartományra.
Ellenőrizze a kapcsolat állapotát, és rögzítse a jelerősség paramétereit: RSRP, RSRQ, SINR, RSSI.
Végezzen ping tesztet egy külső szerverhez (pl. 8.8.8.8).
2.2. Mikrotik nRay 60GHz antennapár beállítása
Master antenna (192.168.88.2) konfigurálása:
Csatlakoztassa az eszközhöz Ethernet kábellel.
Nyisson meg egy böngészőt vagy a WinBox alkalmazást, és lépjen be: http://192.168.88.2
Felhasználónév: admin, jelszó: antennán.
Állítsa be az eszközt "Master" módban.
Ellenőrizze az IP címeket, hogy a Slave antenna csatlakozni tudjon.
Slave antenna (192.168.88.3) konfigurálása:
Ismételje meg a fenti lépéseket a 192.168.88.3 IP-n.
Állítsa be az eszközt "Slave" módban, és csatlakoztassa a Master antennához.
Ellenőrizze a kapcsolat minőségét és rögzítse a jelminőségi paramétereket: WIRELESS 60G STATUS.
2.3. SOHO router beállítása AP módban
Csatlakoztassa a routert a laptophoz Ethernet kábellel.
Nyisson egy parancssort és keresse meg a router IP címét:
arp -a
Nyisson meg egy böngészőt és lépjen be az IP címére.
WiFi beállítása:
SSID: GazdaXX, Jelszó: G1234567 (XX - azonosító szám, pl. Gazda01, Gazda02).
Kapcsolja AP módba és állítsa be az IP-t a 192.168.88.xxx tartományba.
3. Hálózati tesztelés és hibakeresés
3.1. Ping teszt végrehajtása
Nyisson egy parancssort és pingelje meg a következő eszközöket:
ping 192.168.88.1
ping 192.168.88.2
ping 192.168.88.3
ping 192.168.88.4
Ha problémák lépnek fel, használja a következő parancsokat a hálózati hibák elhárításához:

ipconfig
ipconfig /all
ipconfig /release
ipconfig /renew
3.2. Sávszélesség mérése (iperf használata)
Telepítse az iperf3 szoftvert a laptopokra:
winget install iperf3
Az egyik laptopon futtassa szerverként:
iperf3 -s
A másik laptopon futtassa kliensként:
iperf3 -c 192.168.88.xxx
Rögzítse az eredményeket és mérje meg a sávszélességet.
4. Eredmények és megjegyzések
Ping tesztek eredményei:

192.168.88.1: válaszidő... ms, csomagok: sikeres/sikertelen
192.168.88.2: válaszidő... ms, csomagok: sikeres/sikertelen
192.168.88.3: válaszidő... ms, csomagok: sikeres/sikertelen
Sávszélesség teszt eredményei:

Kliens IP: 192.168.88.xxx
Letöltési sebesség: ... Mbps
Feltöltési sebesség: ... Mbps
A tesztelések alapján minden eszköz sikeresen csatlakozott a hálózathoz, és a szükséges beállítások megfelelően működnek.

Dátum: 2025. január 29.
Aláírás:Visnyei Sándor
