# Sistem Smart Drying Monitoring  
![Status](https://img.shields.io/badge/status-development-yellow) 
![License](https://img.shields.io/badge/license-Academic-blue) 
![Platform](https://img.shields.io/badge/platform-IoT%20%7C%20Web%20%7C%20Mobile-green)
![Language](https://img.shields.io/badge/code-Flutter%20%7C%20Laravel%20%7C%20Arduino-orange)

---

## Deskripsi Proyek

**Sistem Smart Drying Monitoring** adalah sistem berbasis **Internet of Things (IoT)** yang digunakan untuk **memantau suhu, kelembapan, dan kadar air secara real-time** pada proses pengeringan menggunakan oven.  
Sistem ini dirancang untuk membantu pengguna melakukan **pengawasan otomatis** terhadap proses produksi, sehingga lebih **efisien, hemat energi, dan presisi**.

Data dari sensor dikirim melalui mikrokontroler ke **server IoT**, kemudian divisualisasikan ke:
- **Dashboard web** untuk admin/operator produksi  
- **Aplikasi mobile** untuk pengguna lapangan

---

## Tujuan Utama

- Meningkatkan efisiensi proses pengeringan berbasis data real-time  
- Mengurangi kesalahan manusia dalam memantau suhu dan kelembapan  
- Menyediakan sistem terintegrasi antara **hardware (IoT)** dan **software (web & mobile)**  

---

## Fitur Utama

| Fitur | Deskripsi |
|-------|------------|
| Monitoring Real-time | Memantau suhu, kelembapan, dan kadar air langsung dari sensor |
| Notifikasi Otomatis | Memberikan peringatan jika kondisi melewati batas aman |
| Integrasi Cloud | Data tersimpan otomatis di server IoT / cloud database |
| Dashboard Web | Menampilkan data pengeringan dan histori |
| Aplikasi Mobile | Memantau proses dari smartphone |
| Mikrokontroler IoT | Komunikasi data melalui WiFi |

---

## Komponen yang Digunakan

| Komponen                     | Deskripsi                                             |
| ---------------------------- | ----------------------------------------------------- |
| 🧰 Mikrokontroler            | ESP32 / Arduino dengan modul WiFi                     |
| 🌡️ Sensor Suhu & Kelembapan | DHT22 / DS18B20                                       |
| 💧 Sensor Kadar Air          | Capacitive Soil Moisture Sensor                       |
| 🔥 Oven Pengering            | Alat fisik pengering (modifikasi alat yang sudah ada) |
| ☁️ Server IoT                | Firebase / ThingsBoard / MQTT Broker                  |
| 💻 Dashboard Web             | Laravel / React / Vue.js                              |
| 📱 Mobile App                | Flutter Framework                                     |

---

## Alur Proses Sistem

1. Sensor membaca nilai suhu, kelembapan, dan kadar air  
2. Mikrokontroler mengirim data ke server IoT melalui WiFi  
3. Server menyimpan data ke database cloud  
4. Dashboard web dan aplikasi mobile menampilkan data secara real-time  
5. Sistem mengirim notifikasi jika parameter melebihi ambang batas  

---

## Pengembang

**Nama:** Nurhaliza Anindya Putri  
**Program Studi:** D-IV Teknik Informatika  
**Institusi:** Politeknik Negeri Malang  
**Dosen Pembimbing:** Ibu Meyti Eka Apriyani, S.Kom., M.Kom.  

---

## Rencana Pengembangan

- [ ] Integrasi mikrokontroler ESP32 dengan Firebase  
- [ ] Pembuatan dashboard web berbasis Laravel  
- [ ] Pengembangan aplikasi mobile berbasis Flutter  
- [ ] Pengujian sistem di oven pengering nyata  
- [ ] Analisis efisiensi dan akurasi data  

---

## Lisensi

**Academic License**  
Proyek ini dibuat untuk kebutuhan **skripsi dan penelitian akademik**.  
Diperbolehkan untuk digunakan atau dikembangkan kembali dengan mencantumkan sumber.

---

## Catatan

Sistem ini dapat dikembangkan untuk berbagai skenario pengeringan seperti:
- Pengeringan hasil pertanian (kopi, gabah, rempah)  
- Produk makanan (kerupuk, keripik, buah kering)  
- Material industri yang memerlukan kontrol suhu dan kelembapan  

---
