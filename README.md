# 📊 Analisis Pola Pangan Harapan (PPH) Konsumsi Nasional

Proyek ini berisi analisis data konsumsi pangan penduduk Indonesia menggunakan indikator **Skor Pola Pangan Harapan (PPH)** dari tahun 2018 hingga 2024 (data terbaru).

Skor PPH merupakan indikator keragaman dan keseimbangan gizi konsumsi pangan penduduk. Semakin tinggi skornya, semakin baik keragaman dan gizi seimbang konsumsi pangan di suatu wilayah.

---

## 💾 Dataset: Skor Pola Pangan Harapan Konsumsi Nasional

| Atribut | Deskripsi | Tipe Data |
| :--- | :--- | :--- |
| **Nama Provinsi** | Nama-nama Provinsi di Indonesia. | Teks (String) |
| **Tahun** | Tahun pengukuran skor PPH, dari 2018 hingga 2024. | Angka (Integer) |
| **Skor PPH** | Nilai Pola Pangan Harapan. Rentang ideal mencapai 100. | Angka (Float) |

### Snippet Data (Contoh Baris):
| Nama Provinsi | Tahun | Skor PPH |
| :--- | :--- | :--- |
| Aceh | 2024 | 83.3 |
| Sumatera Utara | 2024 | 89.2 |
| DI Yogyakarta | 2023 | 95.7 |

---

## 🎯 Tujuan Analisis

Analisis ini bertujuan untuk memberikan wawasan mendalam mengenai kondisi keragaman pangan di Indonesia, khususnya untuk tahun terbaru (**2024**). Tujuan spesifiknya meliputi:

1.  **Evaluasi Kinerja PPH Nasional:** Menganalisis dan memvisualisasikan tren rata-rata Skor PPH nasional dari tahun ke tahun untuk menilai peningkatan atau penurunan keragaman pangan secara umum.
2.  **Identifikasi Kesenjangan Regional:** Mengidentifikasi 5 provinsi dengan **Skor PPH tertinggi** (kinerja terbaik) dan 5 provinsi dengan **Skor PPH terendah** (area prioritas intervensi) pada tahun 2024.
3.  **Perbandingan Tahun ke Tahun:** Menghitung dan memvisualisasikan perubahan Skor PPH rata-rata nasional antara tahun **2023** dan **2024** untuk melihat progres terkini.
4.  **Distribusi PPH:** Memahami sebaran dan statistik dasar (rata-rata, median, rentang) Skor PPH di seluruh provinsi pada tahun 2024.

---

## 🔗 Sumber Data

Data ini dikompilasi dari laporan resmi Badan Pangan Nasional (BAPANAS) atau Badan Pusat Statistik (BPS) Republik Indonesia terkait indikator konsumsi pangan.

* **Institusi Penyedia Data:** Badan Pangan Nasional (BAPANAS) / Badan Pusat Statistik (BPS) Republik Indonesia.
* **Periode Data:** 2018 - 2024 (terbaru).

---

## 💻 Hasil Utama (Ditemukan dalam Output Google Colab)

Hasil analisis yang dihasilkan meliputi:

1.  **Peringkat Provinsi 2024** (Visualisasi Bar Horizontal).
2.  **Tren Garis Waktu** Skor PPH rata-rata nasional.
3.  **Laporan Perubahan** PPH antara tahun 2023 dan 2024.
