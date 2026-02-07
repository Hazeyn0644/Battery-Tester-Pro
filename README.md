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

🛠️ Kurulum / Installation

1. Arduino Setup
Open the file inside arduino_code folder with Arduino IDE. / arduino_code klasöründeki dosyayı Arduino IDE ile açın.
Connect your circuit: / Devrenizi kurun:
Battery (+) -> A0 Pin
Battery (-) -> GND Pin
(Recommended) Add a 100-220 Ohm resistor between A0 and GND for load testing. / (Önerilen) Yük testi için A0 ve GND arasına 100-220 Ohm direnç ekleyin.
Upload the code to your Arduino. / Kodu Arduino kartınıza yükleyin.

2. Python Setup
Ensure Python is installed on your computer. / Bilgisayarınızda Python'un yüklü olduğundan emin olun.
Install required libraries (if not using the automatic launcher): / Gerekli kütüphaneleri yükleyin (otomatik başlatıcı kullanmıyorsanız):

🚀 Kullanım / Usage

Windows Users
Simply double-click on run.bat file. The script will automatically install necessary libraries and launch the XP interface.
Sadece run.bat dosyasına çift tıklayın. Script, gerekli kütüphaneleri otomatik kontrol edecek ve XP arayüzünü başlatacaktır.

Linux / Mac Users
Open a terminal in the project directory and run: Proje dizininde terminal açın ve şu komutu girin:
(Make sure to update the COM PORT in the python script if needed / Gerekirse python kodundaki COM PORT ayarını güncelleyin)

📸 Ekran Görüntüleri / Screenshots
(Screenshots will be added here / Ekran görüntüleri buraya eklenecek)

📜 Lisans / License
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.
Bu proje GNU General Public License v3.0 altında lisanslanmıştır. Detaylar için LICENSE dosyasına bakınız.

Developer: Hazeyn0644
