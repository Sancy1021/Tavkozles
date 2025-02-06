# Jegyzőkönyv: Hálózati konfiguráció és tesztelés

## Bevezetés

Ez a jegyzőkönyv a TP-LINK router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.




## Eszközök
A tesztelés során a következő eszközökkel dolgoztam:
- **Cisco Switch**: A hálózati eszközök közötti kapcsolatot biztosította.
- **TP-LINK router**: A hálózat központi irányítószerveként szerepelt.
- **HP laptop**: A teszteléshez használt számítógép, amelyről a ping tesztek és egyéb parancsok futtak.
- **Mobiltelefon**: Ezzel csatlakoztam a TP-LINK routerhez, hogy a laptop és a többi eszköz között pingelni tudjak.
## 1. A számítógép IP beállításainak lekérdezése
Parancs: `ipconfig`
<details>
  <summary>Kép megtekintése</summary>
  
  <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 110224.png"/>


</details>

## 2. Az aktuális IP-cím eldobása
Parancs: `ipconfig /release`
<details>

  <summary>Kép megtekintése</summary>

 <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 112945.png"/>

</details>

## 3. Új IP-cím kérése
Parancs: `ipconfig /renew`
<details>

  <summary>Kép megtekintése</summary>

    <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 110254.png"/>

</details>

## 4. A routing tábla megjelenítése
Parancs: `netstat -a`
<details>

  <summary>Kép megtekintése</summary>

  <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 110142.png"/>

</details>

## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: `ping microsoft.com`
<details>

  <summary>Kép megtekintése</summary>

  <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 111720.png"/>

</details>

## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: `tracert www.ipon.hu`
<details>

  <summary>Kép megtekintése</summary>

  <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 110954.png"/>

</details>

## 7. Használt portok listázása
Parancs: `netstat -f`
<details>

  <summary>Kép megtekintése</summary>

 <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 114332.png"/>
 
</details>

## 8. Hálózati kapcsolatok megjelenítése
Parancs: `netsh interface show interface`
<details>

  <summary>Kép megtekintése</summary>

  <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 115007.png"/>

</details>

## 9. DNS-beállítások aktualizálása
Parancs: `ipconfig /flushdns`
<details>

  <summary>Kép megtekintése</summary>

   <img src="https://sancy1021.github.io/Tavkozles/WLAN/Képernyőkép 2025-02-06 115135.png"/>
   
</details>

## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: `net use`
<details>

  <summary>Kép megtekintése</summary>

  ![netuse](https://github.com/PavlyasB/IPhalo/blob/main/Képek/netuse.png?raw=true)

</details>

## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: `nslookup www.ipon.hu`
<details>

  <summary>Kép megtekintése</summary>

  ![Ipon](https://github.com/PavlyasB/IPhalo/blob/main/Képek/ipon.png?raw=true)

</details>

## 12. Telefon rákapcsolódva a Wi-Fi-re
<details>
  <summary>Kép megtekintése</summary>

  ![telcsati](https://github.com/PavlyasB/IPhalo/blob/main/Képek/telefoncsati.PNG?raw=true)
</details>

## 13. Telefon pingelése laptopról
<details>
  <summary>Kép megtekintése</summary>

  ![telping](https://github.com/PavlyasB/IPhalo/blob/main/Képek/Telefon-ping.png?raw=true)
</details>

## 14. Router konfigurációk
<details>
  <summary>Kép megtekintése</summary>

  ![routercon](https://github.com/PavlyasB/IPhalo/blob/main/Képek/routerconfig.png?raw=true)
</details>

<details>
  <summary>Kép megtekintése</summary>

  ![routercon1](https://github.com/PavlyasB/IPhalo/blob/main/Képek/routerjelszo.png?raw=true)
</details>

<details>

  <summary>Kép megtekintése</summary>

  ![routercon2](https://github.com/PavlyasB/IPhalo/blob/main/Képek/pingletilt.png?raw=true)
</details>

## Összegzés
A tesztelés során a **Linksys router**, a **Catalyst 2950 switch** és a többi hálózati eszköz zökkenőmentesen működtek együtt. Az IP-konfigurációk kezelése, a routing tábla megjelenítése és a különböző hálózati parancsok futtatása sikeresen zajlott. A mobiltelefonnal való csatlakozás lehetővé tette a laptop és a többi eszköz közötti kommunikációt.
