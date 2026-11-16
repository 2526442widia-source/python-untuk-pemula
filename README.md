# Python untuk Pemula

Repositori latihan belajar dasar-dasar Python. Seluruh contoh kode ditulis dalam satu file, `python-pemula.py`, dan bukti hasil eksekusi tiap bab tersimpan di folder `screenshots/`.

## Materi yang Dipelajari

1. **Pengenalan & Instalasi Python**: memeriksa versi Python dan pip, lalu menyiapkan proyek dan virtual environment.
2. **Variabel dan Tipe Data**: integer, float, string, dan boolean.
3. **Operator**: aritmatika, perbandingan, dan logika (`and`, `or`, `not`).
4. **Kondisi If Else**: `if`, `elif`, `else`, dan aturan indentasi.
5. **Perulangan**: `for`, `while`, `break`, dan `continue`.
6. **Lists dan Dictionaries**: indexing, menambah, mengubah, dan menghapus item.
7. **Function**: argument, `*args`, `**kwargs`, dan default value.
8. **Class dan Object**: property, constructor, dan method.
9. **PIP dan Virtual Environments**: memasang library `colorama` di dalam venv.
10. **Konfigurasi Environment/IDE**: mengatur VS Code agar memakai interpreter dari venv.
11. **README.md & Requirements.txt**: dokumentasi proyek dan daftar dependensi.

## Prasyarat

- Python 3.12 atau lebih baru
- Git
- Visual Studio Code (opsional, disarankan)

## Cara Menjalankan

1. Clone repositori:

   ```
   git clone https://github.com/2526442widia-source/python-untuk-pemula.git
   cd python-untuk-pemula
   ```

2. Buat dan aktifkan virtual environment (Windows PowerShell):

   ```
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   ```

   Jika muncul error *execution policy*, jalankan sekali:

   ```
   Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
   ```

3. Pasang dependensi:

   ```
   pip install -r requirements.txt
   ```

4. Jalankan program:

   ```
   python python-pemula.py
   ```

## Struktur Folder

```
python-untuk-pemula/
├── .vscode/
│   └── settings.json     # konfigurasi interpreter VS Code
├── screenshots/          # bukti hasil eksekusi tiap bab
├── python-pemula.py      # kode seluruh materi
├── requirements.txt      # daftar dependensi
├── .gitignore
└── README.md
```

## Dependensi

| Library    | Versi | Kegunaan                            |
|------------|-------|-------------------------------------|
| colorama   | 0.4.6 | Memberi warna pada output terminal  |

## Riwayat Commit

Setiap bab di-commit secara terpisah dengan format [Conventional Commits](https://www.conventionalcommits.org/), contohnya:

```
feat(basics): add variables and data types examples
feat(control-flow): add if, elif, and else statements
feat(collections): add list and dictionary operations
```