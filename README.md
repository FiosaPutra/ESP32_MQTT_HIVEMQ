https://medium.com/engineering-iot/connecting-esp32-to-hivemq-for-real-time-iot-data-streaming-with-mqtt-8813f48cb1a4

---
https://www.hivemq.com/

---

# ESP32   MQTT HIVEMQ

MQTT (Message Queuing Telemetry Transport) adalah protokol komunikasi ringan berbasis publish-subscribe yang ideal untuk perangkat Internet of Things (IoT) karena efisien di jaringan bandwidth rendah atau tidak stabil, memungkinkan perangkat saling bertukar pesan melalui "topik" dengan perantara "broker", menjadikannya standar untuk komunikasi mesin-ke-mesin (M2M).  
Prinsip Kerja Sederhana:
- Publisher (Penerbit): Perangkat (misalnya sensor) mengirim pesan ke topik tertentu.
Broker (Perantara): Server pusat yang menerima pesan dari Publisher dan mendistribusikannya ke semua yang berlangganan topik tersebut.
Subscriber (Pelanggan): Perangkat atau aplikasi yang "berlangganan" topik tertentu untuk menerima pesan.
Topik (Topik): Kategori pesan (misalnya, "sensor/suhu/ruangan1") yang digunakan untuk menyaring pesan.
## Mengapa MQTT Populer untuk IoT?
- Ringan: Membutuhkan sedikit daya dan bandwidth, cocok untuk perangkat kecil.
- Efisiensi: Bekerja baik di jaringan yang tidak stabil atau memiliki latensi tinggi.
- Skalabilitas: Memisahkan produsen dan konsumen data (publish/subscribe), memungkinkan banyak perangkat terhubung tanpa ketergantungan langsung.
- Berbasis Peristiwa: Reaktif dan efisien untuk mengirim data secara real-time.
- Contoh Penggunaan: Rumah pintar (smart home) untuk mengontrol lampu dan sensor suhu, Otomotif untuk komunikasi kendaraan, Manufaktur untuk pemantauan mesin industri (IIoT), Pemantauan kesehatan jarak jauh.
