# DVB-T MÉRÉSI JEGYZŐKÖNYV

**Mérés helye:** Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés időpontja:** 2025.01.30

**Mérő műszerek:** METEK HD 24003,  Iskra INDOOR ANTENNA, NYTRO BOX plus
**Felelős személy:** Sándor Péter
**Mérést végezte:** Tomolya Milán

## 1. Cél
A mérés célja a DVB-T jel minőségi paramétereinek ellenőrzése a földfelszíni digitális műsorszórás során. A lényeg, hogy minél 
jobb képminőséget érjünk el és minél tisztább képet kapjunk.


## 2. Mérési helyszín
- **Koordináták:** 48°06’20”N 20°46’48”E  
- **Antenna típusa:** ISKRA G2235-06 szobaantenna  
- **Környezet:** V3 labor, városi környezet  
- **Adó távolsága:** 780,08 m

## 3. Mérési paraméterek

| Paraméter                     | Érték       |
|-------------------------------|-------------|
| Adó frekvencia                 | 634 MHz     |
| Sávszélesség                   | 8 MHz       |
| Moduláció típusa               | DVBT/QPSK/8K/1/32 |
| Jelerősség (RSSI)              | 55.4 dBu    |
| MER (Modulation Error Ratio)   | 21.8 dB     |
| Noise Margin                   | 18.0        |
| Hiba nélkül vett adás időtartama | 200 sec    |

## 4. Mérési eredmények
- **Jelerősség:** 55.4 dBu, stabil a mérés során. Az érték megfelel a DVB-T szabványoknak.
- **Modulációs paraméterek:** A QPSK modulációval mért jel/zaj viszony (SNR) 12 dB körül változott, ami a megfelelő vételt biztosítja.
- **MER:** A mért MER érték 21.8 dB volt, ami hibamentes vételt jelez.

## 5. Elemzés
Első lépésnek kicsomagoltuk a G-2245-06 Indoor Antennát és a NytroBOX-ot. Majd áram alá helyezzük és összedugjuk őket. Bekonfiguráltuk az alapvető beállításokat pl.: nyelv és bekapcsoltuk, hogy szűrje az LTE jeleket. Ezek után beállítottuk az antennát a Metek HDD segítségével, hogy minél jobb legyen a jel és minél tisztább képet kapjunk. Kigyűjtöttem az adatokat a műszerről és visszadugtam a septoboxba. 

A mért jelerősség és modulációs paraméterek megfelelőek a DVB-T vétel biztosításához. A jel/zaj viszony és a MER értékei nem mutattak problémát, a vétel stabil volt, és a jelminőség optimális volt.


## 6. Következtetés
A mérés alapján a DVB-T jel stabil és megfelelő minőségű. A vételi paraméterek az előírt határokon belül voltak, így a rendszer jól működik. Viszonylag tiszta képet kaptunk. 

**Aláírás:**  
Felelős mérő személy: Sándor Péter  
Dátum: 2025.01.30
