# 🏙️ Analisis Pasar Airbnb di Bangkok: Insight Bisnis dari Data

Repositori ini berisi analisis mendalam terhadap data listing Airbnb di Bangkok, Thailand. Tujuannya adalah untuk menggali insight bisnis yang dapat ditindaklanjuti bagi investor properti, manajer properti, dan calon host yang ingin memasuki pasar sewa jangka pendek di salah satu kota metropolitan paling dinamis di Asia Tenggara.

---

## 📊 Ikhtisar Proyek

Proyek ini melakukan **analisis data eksplorasi (EDA)** untuk menjawab pertanyaan-pertanyaan bisnis kunci seputar:

- Dinamika harga listing
- Popularitas lokasi
- Karakteristik properti
- Lanskap kompetitif host di pasar Airbnb Bangkok

Dengan memahami tren ini, para pemangku kepentingan dapat membuat keputusan yang lebih cerdas untuk **memaksimalkan pendapatan dan tingkat hunian**.

---

## 📁 Dataset

Analisis ini menggunakan dataset `Airbnb_Bangkok_cleaned.csv`, sebuah versi yang telah dibersihkan dari data publik listing Airbnb. Dataset mencakup atribut seperti:

- `price`: Harga per malam (dalam USD)
- `neighbourhood`: Distrik/wilayah di Bangkok
- `room_type`: Tipe properti (Entire home/apt, Private room, dll.)
- `minimum_nights`: Jumlah malam minimum untuk menginap
- `number_of_reviews`: Total ulasan yang diterima
- `availability_365`: Ketersediaan properti dalam setahun
- `host_id`: ID unik tiap host
- ... dan lainnya

---

## 🎯 Pertanyaan Kunci

Analisis ini bertujuan menjawab beberapa pertanyaan penting berikut:

1. Bagaimana struktur harga bervariasi berdasarkan tipe kamar dan lokasi?
2. Di distrik mana permintaan tertinggi terjadi?
3. Seberapa kompetitif pasar Airbnb di Bangkok?
4. Bagaimana tingkat hunian dan strategi durasi menginap memengaruhi pendapatan?

---

## 💡 Insight Utama

### 1. Harga & Lokasi
- **Tipe Kamar adalah Faktor Utama**  
  Entire home/apt menghasilkan pendapatan tertinggi, dengan harga rata-rata lebih dari dua kali lipat dibandingkan private room.
- **Lokasi Premium**  
  Distrik seperti Pathum Wan, Bang Rak, dan Watthana memiliki harga sewa tertinggi.
- **Peluang di Pasar Menengah**  
  Distrik seperti Phra Khanong dan Chatuchak menawarkan harga terjangkau dengan aksesibilitas baik.

### 2. Popularitas & Permintaan
- **Hotspot Utama**  
  Watthana memiliki jumlah listing dan ulasan terbanyak, menandakan permintaan dan persaingan tinggi.
- **Tingkat Hunian Tinggi**  
  Distrik seperti Phra Nakhon dan Bang Kapi menunjukkan tingkat okupansi yang sangat tinggi.

### 3. Dinamika Host & Pasar
- **Dominasi Host Profesional**  
  Sekitar 10% host mengelola lebih dari 5 properti, menguasai lebih dari 42% listing.
- **Dua Model Bisnis Airbnb**  
  - *Sewa Jangka Pendek (1-3 malam)*: Membangun reputasi dan ulasan.
  - *Sewa Jangka Panjang (30+ malam)*: Cocok untuk ekspatriat dan digital nomad.

### 4. Karakteristik Properti
- **Preferensi Privasi**  
  70% listing adalah Entire home/apt – menunjukkan preferensi tamu terhadap privasi.
- **Strategi Minimum Nights**  
  45% listing memiliki minimum stay ≥ 30 malam — segmen yang sering diabaikan.

---

## 🛠️ Teknologi yang Digunakan

- Python 3
- **Pandas** – untuk manipulasi dan analisis data
- **NumPy** – untuk operasi numerik

---

## 🚀 Cara Menjalankan Analisis

1. **Pastikan Python & pustaka telah terinstal**:

```bash
pip install pandas numpy
