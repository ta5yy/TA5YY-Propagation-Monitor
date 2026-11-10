# TA5YY Propagation Monitor

**Gerçek Zamanlı Amatör Telsiz Propagasyon İzleme Sistemi**

**Geliştirici: TA5YY 🇹🇷**

## 🇹🇷 Türkçe

### Proje Hakkında

TA5YY Propagation Monitor, amatör telsiz operatörleri için geliştirilmiş, PSK Reporter MQTT verilerini kullanarak radyo sinyallerinin dünya genelindeki yayılımını gerçek zamanlı olarak görselleştiren web tabanlı bir uygulamadır.

Raspberry Pi 4 ve Raspberry Pi 5 üzerinde Docker ile çalışacak şekilde hazırlanmıştır.

### Özellikler

- Gerçek zamanlı PSK Reporter verileri
- Etkileşimli dünya haritası
- RX (alınan), TX (gönderilen) ve QSO görselleştirmesi
- Filtrelenebilir istasyon kayıtları
- UTC ve Türkiye saati
- Çağrı işareti ve Maidenhead locator yapılandırması
- Raspberry Pi 4/5 ARM64 desteği
- Yerel ağ üzerinden erişilebilen web paneli

### Sistem Gereksinimleri

- Raspberry Pi 4 veya Raspberry Pi 5
- 64-bit Linux (ARM64)
- Docker Engine ve Docker Compose
- İnternet bağlantısı

### Kurulum

1. Bu depodaki `TA5YY_Propagation_Monitor_RPi4_RPi5_TR_v1.1.zip` dosyasını indirin.
2. Türkçe PDF kurulum kılavuzunu açın.
3. Kurulum adımlarını sırasıyla uygulayın.
4. Kendi çağrı işaretinizi, Maidenhead locator bilginizi ve web portunu girin.
5. Kurulum sonunda belirtilen adresten web paneline erişin.

### Önemli Bilgiler

- Uygulama, PSK Reporter üzerinden sağlanan verilere dayanır.
- Telsiz sinyallerini doğrudan çözümlemez.
- Canlı veri akışında kaçırılan geçmiş raporlar otomatik olarak geri alınmaz.
- Web panelini doğrudan internete açmayın.

---

## 🇬🇧 English

### About the Project

TA5YY Propagation Monitor is a web-based application developed for amateur radio operators. It visualizes radio propagation worldwide in real time using PSK Reporter MQTT data.

The application is designed to run on Raspberry Pi 4 and Raspberry Pi 5 using Docker.

### Features

- Real-time PSK Reporter data
- Interactive world map
- RX, TX and QSO visualization
- Filterable station reports
- UTC and Türkiye local time
- Configurable callsign and Maidenhead locator
- Raspberry Pi 4/5 ARM64 support
- Web dashboard accessible over the local network

### System Requirements

- Raspberry Pi 4 or Raspberry Pi 5
- 64-bit Linux (ARM64)
- Docker Engine and Docker Compose
- Internet connection

### Installation

1. Download `TA5YY_Propagation_Monitor_RPi4_RPi5_TR_v1.1.zip` from this repository.
2. Open the English PDF installation guide.
3. Follow the installation instructions.
4. Enter your own callsign, Maidenhead locator and web port.
5. Access the dashboard using the address displayed after installation.

### Important Notes

- The application relies on PSK Reporter data.
- It does not directly decode radio signals.
- Historical reports missed by the live feed are not automatically recovered.
- Do not expose the dashboard directly to the public internet.

---

## Developer / Geliştirici

**TA5YY — Amateur Radio Software Project**

Made in Türkiye 🇹🇷

**73 de TA5YY**
