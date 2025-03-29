# Távközlési Ismeretek - Mérési Feladat Jegyzőkönyv

- **Dátum**: 2024. december 04.
- **Helyszín**: V3 Labor
- **Mérést végző személy**: Visnyei Sándor
- **Csoport**: 13E. Gyak2

---

## Mérési Feladat
**Cím:** A különböző frekvenciák és modulációk miként befolyásolják a jelminőséget  
**Eszközök:**  

- Johansson 8202 DVB-T modulátor
<details>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/johansson8202.png"/>
</details> 

- RF kábel  
- DVB-T vevő (TV vagy mérőműszer)  
- METEK HD spektrum/jelszint analizátor
<details>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/METEKHD.png"/>
</details>

- Laptop  

---

## Célkitűzés
A mérés célja, hogy a hallgatók:  
1. Megismerjék a Johansson 8202 DVB-T modulátor működését és konfigurációját.  
2. Különböző beállításokkal méréseket végezzenek a METEK HD spektrum/jelszint analizátor segítségével.  
3. Értékeljék a modulációk és frekvenciák hatását a jelminőségre.  

---

## Elvégzett Feladatok
1. **Johansson 8202 modulátor hardveres beállítása**  
   - RF frekvencia: 474 MHz  
   - Moduláció típusa: QPSK, 16-QAM, 64-QAM  
   - Sávszélesség: 8 MHz  
   - Jelszint: Optimalizált az eszközön  

2. **DVB-T jel mérése és értékelése**  
 - A METEK HD spektrum/jelszint analizátorral végzett mérések:
 <br>

       Jelszint QPSK: -30.7 dBm

       
<details>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0001.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0003.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0002.bmp"/>
</details>

<br>

       Jelszint 16-QAM: -31.2 dBm  

     
<details>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0006.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0005.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0004.bmp"/>
</details>

<br>

      Jelszint 64-QAM: -31.6 dBm  
     
<details>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0008.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0009.bmp"/>
   <img src="https://sancy1021.github.io/Tavkozles/04. Frekvencia moduláció mérési feladat/its_snapshot_0007.bmp"/>
</details>   

---

## Mérési Eredmények
|**Mérési paraméter**   |**RF frekvencia (MHz)**  |**Moduláció típusa**   |**Sávszélesség (MHz)**   |**Jelszint (dBm)**  |**Bitsebesség (Mbps)**  |**MER érték (dB)**|
|-----------------------|-------------------------|-----------------------|-------------------------|--------------------|------------------------|------------------|
| **Mérési eredmény 1** | 474                     | QPSK                  | 8                       | -30.7              | 3,8Mbps                | 39.9dB           |      
| **Mérési eredmény 2** | 474                     | 16-QAM                | 8                       | -31.2              | 7.7Mbps                | 35.5dB           |  
| **Mérési eredmény 3** | 474                     | 64-QAM                | 8                       | -31.6              | 12.9Mbps               | 39.9dB           |

---

## Összehasonlítás és Záróértékelés
- **Modulációs típusok hatása:**  
  Az eredmények alapján a moduláció növelésével a jelszint csökken, ami az összetettebb modulációk nagyobb érzékenységére utal.  

- **Ajánlott konfiguráció:**  
  Az optimális jelminőség eléréséhez a QPSK moduláció stabilabb jelszintet biztosított.  

- **Megjegyzések:**  
  A mérési környezetben fellépő zavarok minimalizálása érdekében megfelelő árnyékolást alkalmaztunk.  

----
**Jegyzőkönyv vezetője**: Visnyei Sándor  
**Jegyzőkönyv hitelesítő**: Sándor Péter
