# Data Tugas 1

## Dataset yang Dipilih

Isi informasi berikut sebelum Milestone 1.

| Item | Isi |
|---|---|
| Nama dataset | `Indonesia Medical Q&A` |
| Sumber | `[https://huggingface.co/datasets/abid/indonesia-medical-qna]` |
| Lisensi/ketentuan pakai | `Unspecified / Other (Tidak dideklarasikan secara eksplisit di repositori). Namun, karena bersumber dari teknik web scraping pada platform konsultasi kesehatan (seperti Alodokter), secara hukum datanya terikat Hak Cipta milik platform asal. Penggunaan publik disarankan hanya terbatas untuk Riset Akademis / Non-Komersial.` |
| Ukuran | `qna.csv ±2,83 GB; 681.203 baris. Memenuhi syarat tugas karena ukuran dataset >500 MB.` |
| Periode data | `	Sekitar tahun 2017 – 2020 (Selaras dengan penarikan korpus medis berbasis data Alodokter yang dikompilasi oleh kreator pada lini proyek penelitian tersebut).` |
| Unit analisis | `	Teks interaksi Tanya-Jawab (Q&A) Medis bahasa Indonesia yang terdiri dari keluhan/pertanyaan kesehatan pasien (patient query) dan teks jawaban penjelasan resmi dari dokter (doctor response).` |

## Tempat Mencari Dataset

Pilih dataset Indonesia yang legal digunakan, dapat didokumentasikan sumbernya, dan memenuhi batas ukuran tugas.

| Situs | Kegunaan |
|---|---|
| [Satu Data Indonesia](https://data.go.id/) | Portal data terbuka lintas instansi pemerintah Indonesia. |
| [Badan Pusat Statistik](https://www.bps.go.id/) | Statistik sosial, ekonomi, kependudukan, dan data wilayah. |
| [BMKG Data Online](https://dataonline.bmkg.go.id/) | Data cuaca, iklim, gempa bumi, dan observasi meteorologi. |
| [Hugging Face Datasets](https://huggingface.co/datasets) | Dataset publik yang dapat dicari berdasarkan topik, bahasa, atau ukuran. |
| [Kaggle Datasets](https://www.kaggle.com/datasets) | Katalog dataset publik; periksa lisensi dan dokumentasi pembuatnya. |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | Mesin pencari untuk menemukan dataset dari berbagai portal. |

## Cara Memperoleh Data

1. Buka URL sumber di atas.
2. Unduh file ke folder `data/raw/` tanpa mengubah data mentah.
3. Catat nama file dan checksum bila tersedia.
4. Ubah variabel `DATA_PATH` pada `notebooks/01_data_profiling.ipynb` agar menunjuk ke file tersebut.

## Aturan Penyimpanan

- Jangan commit dataset mentah atau hasil olahan berukuran besar ke Git.
- File pada `data/raw/` adalah data asli dan tidak boleh diubah.
- Simpan hasil transformasi yang dapat direproduksi pada `data/processed/`.
