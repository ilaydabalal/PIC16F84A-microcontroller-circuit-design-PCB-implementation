# PIC16F84A Microcontroller Circuit Design & PCB Implementation

[English](#english) | [Türkçe](#türkçe)

---

## <a name="english"></a>🇬🇧 English

### About the Project
This repository showcases the hardware design, schematic layout, and PCB production of a digital counter system powered by a **PIC16F84A** microcontroller[cite: 1]. Although the source code is not included, this project demonstrates end-to-end hardware development skills, including circuit analysis, component placement, routing, and manual soldering.

### Components & Materials (BOM)
- **Microcontroller:** PIC16F84A / 16F628 (18-pin socket)[cite: 2]
- **Clock Source:** 4MHz Crystal Oscillator + 2x 22pF Capacitors[cite: 2]
- **Display & Drivers:** 2x Common Anode 7-Segment Displays, 2xx16 LCD Display, BC547 Transistors[cite: 2]
- **Power Management:** 7805 Voltage Regulator, 1000uF & 470uF & 100nF Capacitors, 1N4007 Diode, 9V Battery, 2-pin Terminal Block[cite: 2]
- **Control & Inputs:** 3x Mini Push Buttons, 10K Trimpot/Potentiometer[cite: 2]
- **Passives:** Resistors (10K, 150 ohm, 470 ohm), 10x LEDs, Jumper, 10x15cm Copper Clad Board[cite: 2]

### Project Gallery
| Front View (Assembly) | Back View (PCB Traces & Soldering) |
| :------------------: | :--------------------------------: |
| ![Front View](assets/on.jpg) | ![Back View](assets/arka.jpg) |

---

## <a name="türkçe"></a>🇹🇷 Türkçe

### Proje Hakkında
Bu repo; **PIC16F84A** mikrodenetleyici tabanlı, buton kontrollü bir sayıcı ve devre altyapısı için gerçekleştirilen donanım tasarımı, şematik yerleşim ve PCB baskı devre (bakır plaket) uygulamasını içermektedir[cite: 1, 2]. Proje, elektronik devre tasarımı, eleman yerleşimi, yolların çıkarılması ve lehimleme işçiliği gibi pratik donanım becerilerini sergilemektedir.

### Kullanılan Malzemeler (BOM)
- **Mikrodenetleyici:** PIC16F84A veya 16F628 (18 pinli soket)[cite: 2]
- **Osilatör:** 4MHz Kristal Osilatör + 2 adet 22pF Kondansatör[cite: 2]
- **Göstergeler:** 2 adet Ortak Katot/Anot Display, 2x16 LCD Display, BC547 Transistörler[cite: 2]
- **Güç ve Besleme:** 7805 Regülatör, 1000uF, 470uF ve 100nF Kondansatörler, 1N4007 Diyot, 9V Pil, Klemens[cite: 2]
- **Kontroller:** 3 adet Mini Buton, 10K Trimpot / Potansiyometre[cite: 2]
- **Pasif Elemanlar:** Çeşitli dirençler (10K, 150Ω, 470Ω), 10 adet Led, Jumper, 10x15cm Bakır Plaket[cite: 2]

### Proje Görselleri
*   **Ön Yüz (Bileşen Yerleşimi):** Devrenin üzerindeki entegre, display ve kondansatörlerin yerleşimi[cite: 3].
*   **Arka Yüz (Bakır Yollar ve Lehimler):** Manuel baskı devre yolları ve lehim işçiliği[cite: 2].
