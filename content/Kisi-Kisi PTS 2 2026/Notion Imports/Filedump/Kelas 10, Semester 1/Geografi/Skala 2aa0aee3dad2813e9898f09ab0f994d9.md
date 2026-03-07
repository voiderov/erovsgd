# Skala

Owner: Erov
Last edited time: November 13, 2025 12:36 PM

**Skala peta** adalah perbandingan antara jarak pada peta dengan jarak yang sebenarnya di permukaan Bumi. Skala ini mutlak diperlukan agar kita dapat mengukur dan membayangkan kondisi sesungguhnya di lapangan.

Berikut adalah 4 cara menghitung skala peta secara lebih mendalam:

---

### 1. Cara Standar (Membandingkan Jarak Peta dan Jarak Sebenarnya)

Ini adalah metode paling fundamental dan paling umum digunakan. Metode ini mengharuskan kita mengetahui satu data jarak sebenarnya di lapangan.

**Konsep:** Membandingkan langsung Jarak Peta (JP) dengan Jarak Sebenarnya (JS).

Rumus Dasar:

Skala = Jarak pada Peta (JP) : Jarak Sebenarnya (JS)

**Langkah-langkah Terperinci:**

1. **Identifikasi Dua Titik:** Pilih dua titik di peta yang Anda tahu jarak sebenarnya di lapangan (misalnya, jarak antara Balai Desa dan Pasar).
2. **Ukur Jarak Peta (JP):** Gunakan penggaris untuk mengukur jarak antara dua titik tersebut pada peta. Satuan yang paling umum digunakan adalah **sentimeter (cm)**.
    - *Contoh: Jarak Balai Desa ke Pasar di peta = **4 cm**.*
3. **Dapatkan Jarak Sebenarnya (JS):** Cari tahu data jarak sesungguhnya. Data ini bisa dari Google Maps, plang jalan, atau data resmi. Satuan yang umum adalah **kilometer (km)**.
    - *Contoh: Jarak sebenarnya Balai Desa ke Pasar = **2 km**.*
4. **Samakan Satuan (Kunci!):** Ini adalah langkah krusial. Anda tidak bisa membandingkan cm dengan km. Ubah satuan Jarak Sebenarnya (JS) menjadi satuan Jarak Peta (JP), yaitu **cm**.
    - Ingat konversi: **1 km = 100.000 cm**
    - *Perhitungan: JS = 2 km x 100.000 = 200.000 cm*
5. **Hitung Skala:** Masukkan ke dalam rumus perbandingan.
    - Skala = 4 cm : 200.000 cm
6. **Sederhanakan:** Skala peta selalu dinyatakan dalam bentuk **1 : X**. Untuk mendapatkannya, bagi kedua sisi dengan angka Jarak Peta (JP).
    - Skala = (4 dibagi 4) : (200.000 dibagi 4)
    - **Skala = 1 : 50.000**

---

### 2. Membandingkan dengan Peta Lain (Area Sama)

Metode ini digunakan jika Anda memiliki dua peta yang menampilkan area yang sama, tetapi salah satu petanya (Peta A) tidak memiliki skala, sementara Peta B memilikinya.

**Konsep:** Skala berbanding terbalik dengan jarak di peta. Jika jarak di Peta A lebih panjang dari Peta B, berarti Peta A lebih besar (lebih detail) dan penyebut skalanya lebih kecil.

Rumus:

Penyebut Skala Peta Baru = (Jarak pada Peta Lama / Jarak pada Peta Baru) x Penyebut Skala Peta Lama

- **Peta Baru** = Peta yang dicari skalanya
- **Peta Lama** = Peta yang diketahui skalanya

**Langkah-langkah Terperinci:**

1. **Siapkan Dua Peta:** Sebut saja Peta Lama (skala diketahui) dan Peta Baru (skala dicari).
2. **Identifikasi Titik yang Sama:** Tentukan dua titik yang ada di kedua peta (misal, Titik X dan Titik Y).
3. **Kumpulkan Data:**
    - Data Peta Lama (Diketahui): Skala 1 : 100.000 (maka Penyebut Skala = 100.000). Jarak X-Y di peta = **5 cm**.
    - Data Peta Baru (Dicari): Jarak X-Y di peta = **10 cm**.
4. **Masukkan ke Rumus:**
    - Penyebut Skala Baru = (5 cm / 10 cm) x 100.000
    - Penyebut Skala Baru = 0,5 x 100.000
    - Penyebut Skala Baru = 50.000
5. **Hasil:** Skala Peta Baru adalah **1 : 50.000**. (Ini masuk akal, jarak di Peta Baru dua kali lebih panjang, berarti petanya 2x lebih besar, sehingga penyebut skalanya 2x lebih kecil).

---

### 3. Menggunakan Garis Kontur (Peta Topografi)

Metode ini khusus untuk peta topografi (seperti Peta RBI) yang memiliki **garis kontur** (garis khayal yang menghubungkan ketinggian yang sama).

**Konsep:** Ada rumus praktis (empiris) dalam kartografi yang menghubungkan Skala Peta dengan **Interval Kontur (CI)** atau *Contour Interval*. CI adalah beda tinggi antara dua garis kontur yang berdekatan.

Rumus Praktis:

Penyebut Skala = CI x 2.000

*Catatan: Angka **2.000** adalah konstanta yang umum digunakan di Indonesia, berdasarkan standar bahwa CI yang ideal adalah 1/2000 dari penyebut skala.*

**Langkah-langkah Terperinci:**

1. **Cari Interval Kontur (CI):** Lihat legenda peta untuk nilai CI. Jika tidak ada, Anda bisa menghitungnya.
2. **Cara Menghitung CI (jika tidak ada di legenda):**
    - Cari dua garis kontur **indeks** (garis tebal yang ada angkanya).
    - Hitung selisih ketinggiannya.
    - Hitung jumlah "ruang" atau interval antara dua garis indeks tersebut.
    - CI = (Selisih Tinggi Indeks) / (Jumlah Interval)
    - *Contoh: Indeks A = 100 m, Indeks B = 200 m. Di antara keduanya ada 4 garis kontur biasa (sehingga ada 5 interval). Maka CI = (200 - 100) / 5 = 100 / 5 = **20 meter**.*
3. **Pastikan Satuan CI:** Rumus ini bekerja jika CI dalam satuan **meter**.
4. **Hitung Skala:**
    - Penyebut Skala = 20 m x 2.000
    - Penyebut Skala = 40.000
5. **Hasil:** Skala peta tersebut adalah **1 : 40.000**.

---

### 4. Menggunakan Garis Astronomis (Lintang/Bujur)

Metode ini menggunakan fakta bahwa Bumi berbentuk bulat (geoid) dan memiliki sistem koordinat yang jaraknya relatif konstan, terutama untuk garis lintang.

**Konsep:** Jarak 1 derajat (1°) pada garis meridian (garis lintang, Utara-Selatan) di permukaan Bumi selalu dianggap konstan, yaitu sekitar **111 km**.

**Detail Konversi (Sesuai Permintaan Anda):**

Sistem koordinat astronomis menggunakan Derajat (°), Menit (', atau petik satu), dan Detik (", atau petik dua).

- **1° (Derajat)** = **60' (Menit)**
- **1' (Menit)** = **60" (Detik)**

Berikut konversi jaraknya di lapangan (jarak sebenarnya):

- **Jarak untuk 1 Derajat (1°):** Sekitar **111 km**
- **Jarak untuk 1 Menit (1'):** 111 km / 60 = Sekitar **1,85 km** (atau 185.000 cm)
- **Jarak untuk 1 Detik (1"):** 1,85 km / 60 = Sekitar **0,03083 km** (atau 3.083 cm, atau sekitar **30,83 meter**)

**Langkah-langkah Terperinci (Contoh menggunakan Menit):**

1. **Cari Garis Lintang:** Temukan dua garis lintang pada peta.
    - *Contoh: Peta menunjukkan garis lintang 8 derajat 10 menit LS dan 8 derajat 20 menit LS.*
2. **Hitung Selisih Astronomis:**
    - 8 derajat 20 menit LS - 8 derajat 10 menit LS = **10' (10 menit)**.
3. **Hitung Jarak Sebenarnya (JS):** Gunakan konversi 1 menit.
    - JS = 10 x 1,85 km = **18,5 km**.
4. **Ukur Jarak Peta (JP):** Ukur jarak antara dua garis lintang tersebut di peta dengan penggaris.
    - *Contoh: Setelah diukur, Jarak Peta (JP) = **3,7 cm**.*
5. **Samakan Satuan JS:**
    - JS = 18,5 km x 100.000 = **1.850.000 cm**.
6. **Hitung Skala (Kembali ke Cara 1):**
    - Skala = JP : JS
    - Skala = 3,7 cm : 1.850.000 cm
7. **Sederhanakan (Bagi kedua sisi dengan 3,7):**
    - Skala = 1 : (1.850.000 / 3,7)
    - **Skala = 1 : 500.000**

> Peringatan Penting: Metode astronomis ini paling akurat jika Anda mengukur jarak antar garis Lintang (Utara-Selatan). Jarak antar garis Bujur (Timur-Barat) hanya sekitar 111 km di Khatulistiwa dan akan menyempit (semakin kecil) mendekati kutub.
> 

---