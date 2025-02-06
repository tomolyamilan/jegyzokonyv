# Jegyzőkönyv: Távközlési Technikus Vizsgafeladat

---

**Vizsgázó neve:** [Tomolya Milán]  
**Vizsga dátuma:** [2025.02.03]      
**Adótorony:** [Miskolc, Avasi adótorony]  

---

### 1. Előkészületek (10 perc)

- **Eszközök ellenőrzése:**  
  Ellenőriztem, hogy minden szükséges eszköz rendelkezésre állt, és minden működött rendeltetésszerűen.

    -**Antenna:** Logper  
    -**Fejállomás:** LEMCO SCL-824CT  
    -**Set-top box:** MAG IPTV  
    -**Mérőműszer:** METEK HDD   
    -**Hálózati eszközök:** Switch HP Procurve 2312 J4817A    


- **Multiplexek keresése:**  
  Az adótorony adatbázisában elérhető multiplexek információit keresve az alábbiakat rögzítettem:  
  - **Frekvencia:** [Frekvencia]  
  - **Teljesítmény:** [Teljesítmény]  
  - **Polarizáció:** [Polarizáció]  
  - **Adás típusa:** [Adás típusa]  

---

### 2. Antenna felszerelése és beállítása (30 perc)

- **Antenna kiválasztása:**  
  A feladathoz beltéri antennát választottam, mivel az optimális vételt a V3 labor egyik megfelelő pontján biztosította.

- **Antenna beállítása:**  
  Az antenna pontos irányba állításához iránytűt és dőlésszögmérőt használtam. A METEK HDD mérőműszer segítségével végeztem el a finomhangolást.

    -**Antenna típusa:**[Iskra P-20 Logper] 
    -**Mérési eszközök:** [Iránytű, dőlésszögűmérő, METEK HDD mérőműszer] 
    -**Jelerrősség:** [52 dBuV]  
    -**Irány:** Dél-Nyugat [233°]   
    -**Polarizáció:** [Horizontális]      

---

### 3. Kábelezés, mérési pontok kialakítása és jel bevezetése a fejállomásba (25 perc)

- **Kábelezés:**  
  Az antenna koaxiális kábellel és osztóval lett összekötve a fejállomással. A jelek megfelelő elosztásához jelosztót használtam.

- **Jel bevezetése:**  
  A jelet sikeresen bevittem a villamos 3 laborba, hogy az IPTV hálózaton keresztül továbbítható legyen.

---

### 4. Fejállomás beállítása és IPTV stream konfigurálása (25 perc)

- **Fejállomás beállítása:**  
  A fejállomás bemeneteire megfelelő multiplexeket rendeltem. A szabadon fogható (FTA) DVB-T jelet feldolgoztam és IP streamre konvertáltam.

- **Multicast IP tartomány:**  
  A megfelelő multicast IP tartomány kiválasztására és konfigurálására került sor, így a streamelt IPTV csatornák hozzá lettek rendelve.

- **IPTV Set-top-box konfigurálása:**  
  A MAG IPTV Set-top boxot csatlakoztattam és konfiguráltam. A hálózati kapcsolatot beállítottam, és a csatornakeresés sikeresen lezajlott.

---

### 5. Jelszintmérés és dokumentáció (30 perc)

- **Mérések az antennánál:**  
  - **Spektrum analizátor kép:** [Kép mellékelve]  
  - **Jelszint:** [Jelszint (dBμV)]  
  - **Jel-zaj viszony (SNR):** [SNR (dB)]  
  - **Bit Error Rate (BER):** [BER]  
  - **Modulation Error Ratio (MER):** [MER (dB)]  
  - **Csillapítás:** [Csillapítás (dB)]  
  - **Lock állapot:** [ ] Igen [ ] Nem  
  - **Hőmérséklet:** [Hőmérséklet]  
  - **Időjárási körülmények:** [Szélsebesség, egyéb]  
  - **Multiplex adatok:** [Frekvencia, szimbólumráta, FEC]

- **Mérések a fejállomás után (IPTV stream):**  
  - **Multicast IP címek ellenőrzése:** [Multicast IP címek: 239.1.1.1-239.1.1.40]  
  - **IPTV stream stabilitás:** [Stabil] / [Instabil]  
  - **Hálózati késleltetés és csomagvesztés:** [Késleltetés] / [Csomagvesztés]  
  - **Stream adatok:** [Adatok mentve]

---

### 6. Eszközök telepítése és hálózati tesztelés

- **VLC, Wireshark, FFmpeg, iPerf3 telepítése:**  
  A szükséges IPTV vizsgálati eszközök telepítése sikeresen megtörtént a winget csomagkezelő használatával.  
  - **VLC:** [Telepítve]  
  - **Wireshark (TShark):** [Telepítve]  
  - **FFmpeg:** [Telepítve]  
  - **iPerf3:** [Telepítve]  

- **Hálózati teljesítmény tesztelése (iperf3):**  
  - **Multicast IP cím:** 239.1.1.1  
  - **Sávszélesség:** 10 Mbps  
  - **Ping teszt:** [Válaszidő: ms]  
  - **Traceroute vizsgálat:** [Útvonal ellenőrzés]

- **Wireshark elemzés:**  
  A multicast csomagok figyelése és a stream rögzítése sikeresen megtörtént. A csomagvesztés és hibák elemzése is megtörtént az FFmpeg segítségével.

---

### Összegzés:

A feladatot sikeresen elvégeztem. Minden lépést megfelelően teljesítettem a DVB-T jel fejállomásba küldése és az IPTV rendszer kiadása során. Az IPTV stream megfelelően működik, és a hálózati tesztelések is eredményesen zajlottak.

---
