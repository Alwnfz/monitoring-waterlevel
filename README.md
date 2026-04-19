# monitoring-waterlevel
# Water Tank Monitoring System (LoRa 915 MHz)

## 📌 Deskripsi
Sistem monitoring ketinggian air menggunakan sensor JSN-SR04T dan komunikasi LoRa 915 MHz.

## ⚙️ Komponen
- Arduino Uno
- ESP32
- JSN-SR04T Ultrasonic Sensor
- LoRa SX1278 (915 MHz)
- LCD I2C

## 🔧 Fitur
- Monitoring tinggi air (cm)
- Persentase volume (%)
- Status: Kosong, Normal, Full, Overflow
- Transmisi data via LoRa
- Monitoring via Web (offline)

## 📡 Arsitektur
Transmitter → LoRa → Receiver (ESP32 + Web + LCD)


## 📷 Wiring
<img width="514" height="601" alt="image" src="https://github.com/user-attachments/assets/e0a2830f-2490-43cb-981c-9d838e581ded" />
Wiring Arduino uno to Lora 915 mHz

<img width="736" height="435" alt="WhatsApp Image 2026-04-19 at 22 23 07" src="https://github.com/user-attachments/assets/851eaa68-9bda-4595-b8c8-bc048296398a" />
Wiring Arduino uno to JSN SR04T

