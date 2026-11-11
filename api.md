# Data Structure & Scoring Specification (api.md)

Struktur objek data standar yang digunakan aplikasi untuk menyajikan soal literasi matematika terfragmentasi:

## Format Objek Soal (`quizProblems`)
```json
{
  "title": "Konteks 1: Data Makanan Kantin SMPN 7",
  "story": "Kantin sekolah mencatat total penjualan 50 porsi makanan siang ini. Sebanyak 15 porsi di antaranya adalah Soto Ayam.",
  "knownPart": 15,
  "knownTotal": 50,
  "targetType": "Persentase (%)",
  "targetMultiplier": "100%",
  "correctAnswer": 30,
  "unit": "%",
  "hint": "Sederhanakan pecahan 15/50 menjadi 3/10, lalu kalikan dengan 100%."
}
```

## Aturan Penilaian Otomatis
* **Permainan Sortir Rumus:** +25 poin untuk setiap pilihan pengali (`100%` atau `360°`) yang tepat (Maksimal 100 poin).
* **Latihan Literasi PISA:** +50 poin untuk setiap soal cerita kontekstual yang berhasil diselesaikan hingga tahap visualisasi grafik.
