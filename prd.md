# Product Requirement Document (PRD) - StasTika App

## 1. Analisis Masalah Pengguna (Empiris Lapangan)
Berdasarkan hasil wawancara siswa S01 di SMPN 7 Kota Cilegon, ditemukan titik beban kognitif berikut:
* **Intrinsic Load (IL):** Siswa mengalami kebingungan membedakan rumus persentase (100%) dan sudut pusat (360°) karena komponen pecahannya mirip. Terdapat juga kesenjangan prasyarat pada operasi perkalian/pembagian pecahan.
* **Extraneous Load (EL):** Teks soal cerita yang terlalu panjang memicu memori kerja macet (stuck). Visual monokrom papan tulis memicu split-attention, sementara dekorasi kartun yang ramai memicu efek redundansi (mengganggu konsentrasi).
* **Germane Load (GL):** Siswa sebenarnya memiliki regulasi diri yang baik (membaca teliti -> catat info -> plot titik -> tarik garis), namun membutuhkan tuntunan bertahap (scaffolding) saat menemui jalan buntu.

## 2. Solusi & Spesifikasi Fitur Utama
* **Fitur 1: Formula Mode Toggle Guide (Solusi IL):** Kalkulator dan materi rumus dipisahkan menjadi dua opsi tegas: Mode Persen (Teal) vs Mode Derajat (Amber) agar skema rumus tidak saling bercampur di memori siswa.
* **Fitur 2: Step-by-Step Task Splitter (Solusi EL):** Aplikasi memotong teks soal cerita panjang menjadi 3 alur layar interaktif: (1) Identifikasi Data Diketahui, (2) Perhitungan Pecahan Mandiri/Terbimbing, (3) Visualisasi Grafik Diagram.
* **Fitur 3: Dynamic Colorful & Minimalist Charts (Solusi EL):** Diagram garis dan lingkaran menggunakan warna kontras tinggi dengan label langsung. Dekorasi ilustrasi kartun yang tidak relevan ditiadakan secara total.
* **Fitur 4: Fading Hints & Pacing Control (Solusi GL):** Navigasi dilengkapi kontrol penuh tombol Sebelumnya dan Selanjutnya, serta bantuan coretan hitung pecahan bertahap.
