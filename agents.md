# Adaptive Learning & Scaffolding Logic (agents.md)

Logika cerdas di dalam aplikasi StasTika mengadaptasi peran agen pembimbing belajar untuk menjaga kestabilan beban kognitif siswa:

## 1. Cognitive Load Guard (Task Splitter Logic)
* **Peran:** Mencegah kelebihan beban memori kerja (working memory overload).
* **Cara Kerja:** Mengunci tahap perhitungan sebelum siswa berhasil memilah dan menginput angka "Data Bagian" dan "Total Data" dengan benar pada Tahap 1.

## 2. Adaptive Scaffolding (Fading Hints)
* **Peran:** Memberikan bantuan bertingkat saat siswa kesulitan menghitung pecahan.
* **Cara Kerja:** 
  * **Klik Hint 1:** Menampilkan bentuk pecahan dasar dari soal (contoh: `15/50`).
  * **Klik Hint 2:** Menampilkan langkah penyederhanaan pecahan dan pengalinya (contoh: `3/10 × 100%`).
