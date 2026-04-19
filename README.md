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

## 🌐 Akses Web
SSID: WaterTank  
Password: 12345678  
IP: 192.168.4.1

## 📷 Wiring
