# 🔋 Battery Tester Pro (Pil Ölçer)

**Battery Tester Pro**, Arduino Uno ve Python kullanarak geliştirdiğim, açık kaynaklı (Open Source) ve Windows XP estetiğine sahip profesyonel bir pil analiz aracıdır.

![License](https://img.shields.io/badge/license-GPLv3-blue.svg)
![Python](https://img.shields.io/badge/python-3.x-yellow.svg)
![Arduino](https://img.shields.io/badge/platform-Arduino-teal.svg)

## 🌟 Özellikler / Features

* **🇬🇧/🇹🇷 Multi-Language:** English and Turkish support.
* **🖥️ Fullscreen Interface:** Immersive XP-style UI (Toggle with F11).
* **📊 Smart Analysis:** Doesn't just show voltage; advises on battery health without being destructive.
* **🔌 Wiring Guide:** On-screen instructions for Arduino connection.

## 🛠️ Kurulum / Installation

### 1. Arduino Setup
1. `arduino_code/battery_sensor.ino` dosyasını Arduino IDE ile açın.
2. Devreyi aşağıdaki şemaya göre kurun:
   * **Battery (+)** -> **A0 Pin**
   * **Battery (-)** -> **GND Pin**
   * *(Opsiyonel)* Daha hassas ölçüm için A0 ve GND arasına 100-220 Ohm direnç ekleyin.
3. Kodu Arduino kartınıza yükleyin.

### 2. Python Setup
1. Bilgisayarınızda Python yüklü olmalıdır.
2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pyserial tk
