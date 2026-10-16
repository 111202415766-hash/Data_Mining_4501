# IBM Exploratory Data Analysis for Machine Learning — Learning Repository

Repository pembelajaran pribadi berdasarkan notebook dan dataset yang diunduh dari kursus **IBM: Exploratory Data Analysis for Machine Learning** di Coursera.

> **Catatan integritas akademik:** notebook dari kursus dipertahankan sebagai materi belajar. Periksa ketentuan kursus sebelum membagikan ulang materi berhak cipta. Jangan gunakan repository ini untuk mengunggah jawaban penilaian yang tidak boleh dibagikan. README dan dokumentasi tambahan ditulis untuk membantu navigasi, bukan sebagai materi resmi IBM.

## Peta isi

| Folder | Materi | File utama |
|---|---|---|
| `01-reading-data-demo/` | Demo membaca data dari database SQLite dengan Pandas/SQL | `01a_DEMO_Reading_Data.ipynb`, `data/classic_rock.db` |
| `02-reading-data-lab/` | Latihan membaca data dari database | `01b_LAB_Reading_Data.ipynb`, `baseball.db` |
| `03-eda-lab/` | EDA menggunakan dataset Iris: ringkasan statistik, pengelompokan, dan visualisasi | `01c_LAB_EDA.ipynb`, `iris_data.csv` |
| `04-feature-engineering-demo/` | Feature engineering pada data Ames Housing, termasuk encoding, transformasi, dan fitur interaksi | `01d_DEMO_Feature_Engineering.ipynb`, `data/Ames_Housing_Data.tsv` |
| `05-hypothesis-testing-demo/` | Pengujian hipotesis dan contoh distribusi binomial | `01e_DEMO_Hypothesis_Testing.ipynb` |
| `docs/` | Peta materi, petunjuk menjalankan notebook, dan inventaris dataset | Lihat file di bawah |

## Cara menjalankan

Disarankan menggunakan Python 3.10–3.12. Beberapa notebook lama mungkin memakai API yang telah berubah pada versi pustaka modern; jika muncul error, catat sel dan pesan error lalu sesuaikan secara minimal sambil mempertahankan konsep kursus.

1. Unduh atau clone repository.
2. Buat virtual environment.
3. Instal dependensi.
4. Jalankan Jupyter dari root repository.
5. Buka notebook dan jalankan sel secara berurutan. Notebook membaca file data relatif terhadap folder masing-masing.

### Instalasi

```bash
python -m venv .venv
# Windows PowerShell: .venv\Scripts\Activate.ps1
# macOS/Linux: source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

## Progres belajar

- [ ] Reading Data demo: membaca tabel SQLite menggunakan SQL dan Pandas.
- [ ] Reading Data lab: menyelesaikan latihan database.
- [ ] EDA lab: memeriksa bentuk data, tipe kolom, statistik, kelompok spesies, dan visualisasi Iris.
- [ ] Feature Engineering demo: memahami data cleaning, one-hot encoding, transformasi skew, serta fitur polinomial/interaksi.
- [ ] Hypothesis Testing demo: memahami hipotesis, tingkat kesalahan, dan pengaruh ukuran sampel.

Centang item setelah kamu menjalankan notebook dan menulis interpretasi sendiri.

## Sumber

- Kursus: [IBM — Exploratory Data Analysis for Machine Learning](https://www.coursera.org/learn/ibm-exploratory-data-analysis-for-machine-learning)
- File notebook dan dataset dalam folder modul berasal dari arsip kursus yang disediakan pengguna. Dokumen ini tidak mengklaim sebagai repository resmi IBM.
