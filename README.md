IoT ESP32 Heltec LoRa – Monitoring Suhu & Kelembaban (ThingSpeak)

Deskripsi Proyek:
Proyek ini merupakan implementasi sistem Internet of Things (IoT) menggunakan ESP32 Heltec LoRa 
yang diprogram melalui Arduino IDE. Sistem ini mensimulasikan pembacaan data suhu dan kelembaban 
(sebagai pengganti sensor DHT22) dan mengirimkannya ke platform ThingSpeak untuk ditampilkan secara real-time.

Selain itu, proyek ini juga mengimplementasikan logika digital menggunakan LED dengan konsep flip-flop (aktif HIGH dan LOW).

Tujuan:
- Memahami konsep dasar IoT dan sistem embedded
- Mengimplementasikan logika digital (aktif HIGH & LOW)
- Menghubungkan ESP32 ke jaringan WiFi
- Mengirim data ke cloud (ThingSpeak)
- Menampilkan data secara real-time

Tools: 
- ESP32 Heltec LoRa
- Arduino IDE
- Thingspeak

Cara Kerja Sistem:
1. ESP32 terhubung ke jaringan WiFi
2. LED menyala dan mati secara bergantian (flip-flop)
3. Sistem menghasilkan data suhu dan kelembaban menggunakan fungsi random()
4. Data ditampilkan di Serial Monitor
5. Data dikirim ke ThingSpeak setiap 15 detik
6. Data divisualisasikan dalam bentuk grafik

Demo:
https://thingspeak.mathworks.com/channels/3325150
