<div align="center">

# Praktikum Business Intelligence

### Laboratorium Sains Data — IKOPIN University

![Semester](https://img.shields.io/badge/Semester-Ganjil%202026%2F2027-blue?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<p>
Repository resmi untuk kegiatan <strong>Praktikum Business Intelligence</strong><br/>
Program Studi S1 Sains Data — Tahun Akademik 2026/2027
</p>

<img src="https://admisi.ikopin.ac.id/assets/images/logo.png" width="300"/>

---

</div>

---

## Deskripsi

Praktikum Business Intelligence dirancang untuk memberikan pengalaman **hands-on** dalam mengolah data menjadi informasi yang mendukung pengambilan keputusan. Mahasiswa akan mempelajari proses pengumpulan, pembersihan, transformasi, pemodelan, analisis, dan visualisasi data menggunakan SQL, spreadsheet, Python, serta perangkat Business Intelligence.

> **Mata Kuliah:** Business Intelligence (kode mata kuliah menyesuaikan)  
> **SKS Praktikum:** 1 SKS  
> **Prasyarat:** Pengantar Basis Data, Statistika, dan dasar penggunaan spreadsheet

---

## Tim Pengajar

| Peran | Nama | Kontak |
|-------|------|--------|
| Dosen Pengampu | Mohammad Fahreza, S.E., M.Ti. | - |
| Asisten Laboratorium | Ryan F. F. Hakim, S.Si.D | - |

---

## Setup & Instalasi

### Opsi Environment

| Opsi | Kelebihan | Kekurangan |
|------|-----------|------------|
| **Power BI Desktop** | Cocok untuk membuat model data dan dashboard interaktif | Aplikasi desktop utamanya tersedia untuk Windows |
| **Power BI Service** | Dashboard dapat diakses melalui browser | Fitur berbagi dan kolaborasi bergantung pada lisensi |
| **Looker Studio** | Berbasis browser dan mudah digunakan untuk visualisasi | Fitur dan alur kerja berbeda dari Power BI |
| **Lokal dengan PostgreSQL** | Bebas mengelola database dan query SQL | Perlu instalasi serta konfigurasi lokal |
| **Google Colab / Jupyter** | Praktis untuk latihan pengolahan data dengan Python | Bukan pengganti aplikasi BI untuk seluruh materi |

### Prasyarat Instalasi Lokal

| Software | Versi Minimum | Kegunaan | Link Download |
|----------|---------------|----------|---------------|
| Power BI Desktop | Versi terbaru | Pemodelan data dan pembuatan dashboard | [Power BI Desktop](https://powerbi.microsoft.com/desktop/) |
| PostgreSQL | 16+ | Database relasional dan latihan SQL | [postgresql.org](https://www.postgresql.org/download/) |
| DBeaver Community | Versi terbaru | Mengelola database dan menjalankan query | [dbeaver.io](https://dbeaver.io/download/) |
| Microsoft Excel / LibreOffice Calc | Versi terbaru | Pemeriksaan dan pengolahan data tabular | [Microsoft Excel](https://www.microsoft.com/microsoft-365/excel) |
| Python | 3.10+ | Pengolahan dan analisis data tambahan | [python.org](https://www.python.org/downloads/) |
| Git | 2.30+ | Mengelola versi tugas dan proyek | [git-scm.com](https://git-scm.com/) |

> **Catatan:** Power BI Desktop dapat digunakan untuk membuat laporan secara lokal. Publikasi, berbagi, dan kolaborasi melalui Power BI Service dapat memiliki ketentuan lisensi yang berbeda.

### Setup Lingkungan Python (Opsional)

Buat virtual environment:

```bash
python -m venv .venv
```

Aktifkan virtual environment:

```bash
# Windows PowerShell
.venv\Scripts\Activate.ps1

# macOS / Linux
source .venv/bin/activate
```

Instal dependensi:

```bash
pip install -r requirements.txt
```

### Dependencies Utama

Simpan daftar berikut sebagai `requirements.txt` jika latihan Python digunakan:

```text
# Data processing
numpy>=1.24.0
pandas>=2.0.0
scipy>=1.11.0

# Database connectivity
sqlalchemy>=2.0.0
psycopg[binary]>=3.1.0

# Visualization
matplotlib>=3.7.0
seaborn>=0.13.0
plotly>=5.18.0

# Data analysis and modeling
scikit-learn>=1.3.0

# Read and write common data formats
openpyxl>=3.1.0
pyarrow>=14.0.0

# Notebook and utilities
jupyter>=1.0.0
ipykernel>=6.0.0
python-dotenv>=1.0.0
tqdm>=4.66.0
```

### Validasi Setup

Jalankan query berikut di DBeaver atau klien PostgreSQL untuk memeriksa koneksi database:

```sql
SELECT version();
```

Untuk memeriksa lingkungan Python:

```python
import pandas as pd
import sqlalchemy

print(f"Pandas: {pd.__version__}")
print(f"SQLAlchemy: {sqlalchemy.__version__}")
```

---

## Jadwal Praktikum

> Jadwal dan status di bawah merupakan template. Sesuaikan dengan kalender akademik dan progres praktikum yang sebenarnya.

| Pertemuan | Minggu | Topik | Status | Link Modul |
|:---------:|:------:|-------|:------:|:----------:|
| 1 | 3 | Pengantar Business Intelligence dan Data-Driven Decision Making | 🔴 | - |
| 2 | 4 | SQL untuk Analisis Data | 🔴 | - |
| 3 | 5 | Data Cleaning dan Exploratory Data Analysis | 🔴 | - |
| 4 | 6 | ETL dan Data Integration | 🔴 | - |
| 5 | 7 | Data Warehouse dan Dimensional Modeling | 🔴 | - |
| 6 | 8 | Data Modeling dan Measures pada Power BI | 🔴 | - |
| 7 | 9 | Data Visualization dan Dashboard Design | 🔴 | - |
| 8 | 10 | KPI, Analisis Bisnis, dan Data Storytelling | 🔴 | - |
| 9 | 11 | Analisis Data dengan Python dan Integrasi Data | 🔴 | - |
| 10 | 12 | Publikasi Dashboard, Keamanan, dan Tata Kelola Data | 🔴 | - |
| 11 | 13 | Presentasi Proyek Business Intelligence | 🔴 | - |

> 🔴 Belum Dimulai &nbsp; 🟡 Sedang Berlangsung &nbsp; 🟢 Selesai

---

## Daftar Modul

<details>
<summary><b>📂 Modul 01 — Pengantar Business Intelligence</b></summary>

### Topik
- Pengertian dan tujuan Business Intelligence
- Data, informasi, insight, dan knowledge
- Siklus pengambilan keputusan berbasis data
- Komponen dan arsitektur umum sistem BI
- Contoh penerapan BI dalam organisasi

</details>

<details>
<summary><b>📂 Modul 02 — SQL untuk Analisis Data</b></summary>

### Topik
- `SELECT`, `WHERE`, `ORDER BY`, dan `LIMIT`
- Fungsi agregasi dan `GROUP BY`
- Menggabungkan tabel dengan `JOIN`
- Subquery dan Common Table Expression (CTE)
- Fungsi tanggal dan string untuk analisis
- Menulis query untuk menjawab pertanyaan bisnis

</details>

<details>
<summary><b>📂 Modul 03 — Data Cleaning dan Exploratory Data Analysis</b></summary>

### Topik
- Memahami struktur dan kualitas dataset
- Menangani nilai kosong dan data duplikat
- Memeriksa tipe data dan konsistensi kategori
- Mendeteksi nilai yang tidak wajar
- Melakukan analisis eksploratif menggunakan spreadsheet atau Python
- Menyusun dokumentasi proses pembersihan data

</details>

<details>
<summary><b>📂 Modul 04 — ETL dan Data Integration</b></summary>

### Topik
- Konsep Extract, Transform, Load (ETL)
- Menggabungkan data dari CSV, Excel, dan database
- Transformasi tipe dan format data
- Memahami alur kerja Power Query
- Validasi data sebelum dan sesudah proses transformasi
- Pengantar proses ELT

</details>

<details>
<summary><b>📂 Modul 05 — Data Warehouse dan Dimensional Modeling</b></summary>

### Topik
- Perbedaan database operasional dan data warehouse
- Konsep tabel fakta dan tabel dimensi
- Star schema dan snowflake schema
- Grain atau tingkat detail data
- Surrogate key dan natural key
- Merancang model data untuk kebutuhan analisis

</details>

<details>
<summary><b>📂 Modul 06 — Data Modeling dan Measures pada Power BI</b></summary>

### Topik
- Menghubungkan tabel dan mengatur relasi
- Cardinality dan arah filter
- Tabel fakta dan dimensi dalam model Power BI
- Calculated column dan measure
- Dasar penggunaan DAX
- Membuat measure untuk metrik bisnis

</details>

<details>
<summary><b>📂 Modul 07 — Data Visualization dan Dashboard Design</b></summary>

### Topik
- Memilih visualisasi sesuai tipe data dan tujuan
- Prinsip desain dashboard yang mudah dipahami
- Penggunaan warna, label, skala, dan anotasi
- Filter, slicer, dan interaksi visual
- Menghindari visualisasi yang menyesatkan
- Evaluasi kegunaan dashboard

</details>

<details>
<summary><b>📂 Modul 08 — KPI dan Data Storytelling</b></summary>

### Topik
- Menerjemahkan tujuan bisnis menjadi pertanyaan analisis
- Menentukan Key Performance Indicator (KPI)
- Membandingkan target dan realisasi
- Analisis tren dan segmentasi
- Menyampaikan insight dengan konteks yang tepat
- Menyusun narasi dan rekomendasi berbasis data

</details>

<details>
<summary><b>📂 Modul 09 — Analisis Data dengan Python</b></summary>

### Topik
- Membaca data dari CSV, Excel, dan database
- Seleksi, transformasi, dan agregasi data dengan pandas
- Membuat ringkasan statistik dan visualisasi
- Menggunakan hasil analisis Python sebagai masukan BI
- Pengantar analisis prediktif untuk mendukung keputusan

</details>

<details>
<summary><b>📂 Modul 10 — Publikasi, Keamanan, dan Tata Kelola Data</b></summary>

### Topik
- Publikasi laporan BI
- Pengaturan akses dan hak pengguna
- Pengantar row-level security
- Perlindungan data sensitif dan informasi pribadi
- Dokumentasi sumber, definisi metrik, dan proses transformasi
- Memahami keterbatasan dashboard dan potensi bias data

</details>

<details>
<summary><b>📂 Modul 11 — Proyek Business Intelligence</b></summary>

### Topik
- Menentukan masalah dan pertanyaan bisnis
- Mengumpulkan serta mendokumentasikan sumber data
- Membersihkan dan memodelkan data
- Menyusun KPI dan dashboard interaktif
- Menyampaikan temuan dan rekomendasi
- Mempresentasikan hasil analisis

</details>

---

## Proyek Praktikum

Mahasiswa dapat mengerjakan proyek BI secara individu atau berkelompok sesuai arahan pengajar. Proyek dapat menggunakan dataset publik atau dataset lain yang telah memperoleh izin penggunaan.

### Komponen Proyek

1. **Latar belakang masalah** dan pertanyaan bisnis yang ingin dijawab.
2. **Deskripsi sumber data**, termasuk sumber, periode, dan batasan penggunaannya.
3. **Proses persiapan data**, seperti pembersihan, transformasi, dan integrasi.
4. **Model data** yang digunakan untuk analisis.
5. **KPI dan dashboard** yang menjawab pertanyaan bisnis.
6. **Insight dan rekomendasi** yang didukung oleh data.
7. **Dokumentasi** dan presentasi hasil.

### Sumber Dataset yang Dapat Digunakan

- [Badan Pusat Statistik](https://www.bps.go.id/)
- [Satu Data Indonesia](https://data.go.id/)
- [World Bank Open Data](https://data.worldbank.org/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

> Periksa lisensi dataset sebelum digunakan. Jangan mengunggah data pribadi, rahasia, atau data organisasi tanpa izin.

---

## Daftar Modul Tambahan

| No | Topik | Link Modul |
|:--:|-------|:----------:|
| 1 | SQL untuk Analisis Data | - |
| 2 | Data Cleaning dengan Python dan pandas | - |
| 3 | ETL dengan Power Query | - |
| 4 | Data Warehouse dan Dimensional Modeling | - |
| 5 | DAX Dasar untuk Power BI | - |
| 6 | Prinsip Visualisasi Data | - |
| 7 | KPI dan Data Storytelling | - |

---

### ⚠️ Kebijakan AI Tools

| Penggunaan | Kebijakan |
|------------|-----------|
| Meminta penjelasan konsep, SQL, atau fungsi pada perangkat BI | ✅ Boleh sebagai bahan belajar |
| Menggunakan AI untuk membantu menelusuri error | ✅ Boleh, dengan verifikasi dan pemahaman |
| Menyalin query, dashboard, atau analisis tanpa memahami prosesnya | ❌ Tidak diperbolehkan |
| Mengumpulkan laporan yang dibuat AI tanpa kontribusi dan verifikasi sendiri | ❌ Tidak diperbolehkan |

> **Prinsip:** AI digunakan sebagai **tutor dan alat bantu**, bukan pengganti proses analisis. Mahasiswa harus mampu menjelaskan sumber data, transformasi, rumus, visualisasi, serta kesimpulan yang disajikan.

---

## Tech Stack

<div align="center">

| Kategori | Teknologi |
|----------|-----------|
| Database | PostgreSQL |
| Query | SQL |
| Business Intelligence | Microsoft Power BI |
| ETL dan transformasi | Power Query |
| Spreadsheet | Microsoft Excel, LibreOffice Calc |
| Data processing | Python, pandas, NumPy |
| Visualization | Power BI, Matplotlib, Seaborn, Plotly |
| Database client | DBeaver, pgAdmin |
| Notebook | Jupyter, Google Colab |
| Version control | Git, GitHub |

</div>

---

## Referensi & Resources

### Buku Referensi

| Buku | Penulis | Catatan |
|------|---------|---------|
| *The Data Warehouse Toolkit* | Ralph Kimball dan Margy Ross | Referensi dimensional modeling dan data warehouse |
| *Building the Data Warehouse* | W. H. Inmon | Konsep dan arsitektur data warehouse |
| *Information Dashboard Design* | Stephen Few | Prinsip desain dashboard |
| *Storytelling with Data* | Cole Nussbaumer Knaflic | Komunikasi insight melalui visualisasi data |
| *Business Intelligence, Analytics, and Data Science* | Ramesh Sharda, Dursun Delen, dan Efraim Turban | Gambaran umum BI dan analitik |

### Dokumentasi dan Kursus Online

- [Microsoft Learn — Power BI](https://learn.microsoft.com/power-bi/)
- [Microsoft Learn — Power Query](https://learn.microsoft.com/power-query/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)
- [Google Looker Studio Help](https://support.google.com/looker-studio/)
- [Kaggle Learn](https://www.kaggle.com/learn)
- [Our World in Data](https://ourworldindata.org/)

---

## ❓ FAQ

<details>
<summary><b>Q: Apakah praktikum ini harus menggunakan Power BI?</b></summary>

**A:** Power BI menjadi perangkat utama yang direkomendasikan dalam praktikum ini. Perangkat lain, seperti Looker Studio, dapat digunakan jika diizinkan oleh pengajar atau jika perangkat utama tidak tersedia.
</details>

<details>
<summary><b>Q: Apakah saya memerlukan GPU?</b></summary>

**A:** Tidak. Praktikum Business Intelligence umumnya berfokus pada query, pengolahan data, pemodelan, dan visualisasi. GPU tidak diperlukan untuk kegiatan utama.
</details>

<details>
<summary><b>Q: Apakah semua materi memerlukan Python?</b></summary>

**A:** Tidak. Python digunakan sebagai alat pendukung untuk pengolahan dan analisis data. Materi utama juga menggunakan SQL, spreadsheet, dan perangkat BI.
</details>

<details>
<summary><b>Q: Dataset seperti apa yang boleh digunakan untuk proyek?</b></summary>

**A:** Gunakan dataset publik atau dataset yang penggunaannya telah diizinkan. Pastikan sumber dan lisensinya dicantumkan, serta hindari penggunaan data pribadi atau rahasia tanpa persetujuan.
</details>

<details>
<summary><b>Q: Apa yang harus dilakukan jika dashboard menampilkan hasil yang tidak sesuai?</b></summary>

**A:** Periksa kembali sumber data, proses transformasi, tipe data, relasi tabel, filter, dan rumus yang digunakan. Catat langkah pemeriksaan agar penyebab masalah dapat ditelusuri.
</details>

---

<div align="center">

```
“Without data, you're just another person with an opinion.” — W. Edwards Deming
```

IKOPIN University — Tahun Akademik 2025/2026

</div>
