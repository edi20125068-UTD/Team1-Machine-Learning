# Team1-Machine-Learning

[![CCDS Project template](https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter)](https://cookiecutter-data-science.drivendata.org/)

> Tugas Project Python Machine Learning — Team 1, Kelas 24C3.

## 👥 Anggota Tim

| Nama             | NIM      | Role              |
|------------------|----------|-------------------|
| Edi Suryadi      | 20125068 | Product Manager   |
| Dede Rifki       | 20124089 | Software Engineer |
| Nazwa Nurhafidah | 20124105 | UI/UX Designer    |
| Najwa Annisa     | 20124093 | Software Engineer |

## 📁 Struktur Folder (CCDS)

~~~
├── LICENSE
├── Makefile
├── README.md
├── docs/              <- Dokumentasi proyek
├── models/            <- Model ML yang sudah dilatih
├── notebooks/         <- Jupyter notebooks eksplorasi
├── references/        <- Referensi & data dictionary
├── reports/           <- Laporan & visualisasi
├── tests/             <- Unit tests
├── pyproject.toml
└── team1_machine_learning/   <- Source code utama
    ├── config.py
    ├── dataset.py
    ├── features.py
    ├── plots.py
    └── modeling/
        ├── train.py
        └── predict.py
~~~

## ⚙️ Cara Setup

~~~bash
git clone https://github.com/edi20125068-UTD/Team1-Machine-Learning.git
cd Team1-Machine-Learning
pip install -r requirements.txt
~~~

## ✍️ Panduan Commit (Gitmoji)

Format: `<emoji> <tipe>: <deskripsi>`

| Emoji | Tipe | Kapan Dipakai |
|-------|------|---------------|
| ✨ | feat | Tambah fitur/folder baru |
| 🐛 | fix | Perbaiki bug |
| 📝 | docs | Update dokumentasi |
| 📦 | build | Update requirements.txt |
| 🎨 | style | Formatting |
| 🔥 | remove | Hapus file |

## 🌿 Branch Strategy

- `main` → branch utama, jangan commit langsung
- `feature/<nama>` → untuk fitur baru
- `docs/<nama>` → untuk update dokumentasi
- `fix/<nama>` → untuk perbaikan bug
- Selalu buat Pull Request sebelum merge ke main!
