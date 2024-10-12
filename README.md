# My Flask App

## Deskripsi
Aplikasi web sederhana yang dikembangkan menggunakan Flask sebagai framework Python. Aplikasi ini menunjukkan fitur-fitur dasar Flask seperti routing, template rendering, dan penggunaan file statis.

## Fitur
- **Home Page**: Halaman utama yang memberikan gambaran tentang Flask.
- **About Page**: Halaman yang menampilkan informasi tentang anggota kelompok.
- **Contact Page**: Halaman dengan form untuk pengguna agar dapat mengirimkan pesan atau pertanyaan.

## Struktur Proyek
```bash
Tugas_Kel5_Flask/
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── templates/
│   │   ├── index.html
│   │   ├── about.html
│   │   ├── contact.html
│   └── static/
│       ├── style.css
│       └── images/
│           ├── anggota1.jpg
│           ├── anggota2.jpg
│           ├── anggota3.jpg
│           ├── anggota4.jpg
│           └── anggota5.jpg
└── run.py
```
## Cara Menjalankan Aplikasi

### Prasyarat
- Python 3.x
- Virtual environment

### Langkah-langkah

1. **Clone repositori ini**:
   ```bash
   git clone https://github.com/username/my_flask_app.git
   cd my_flask_app
   ```

2. **Buat dan aktifkan virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # untuk MacOS/Linux
   # atau
   venv\Scripts\activate      # untuk Windows
   ```

3. **Instal dependensi**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Jalankan aplikasi**:
   ```bash
   python run.py
   ```

5. **Akses aplikasi di browser**:
   Buka `http://127.0.0.1:5000` di browser Anda untuk melihat aplikasi.

## Kontribusi
1. Fork repositori ini.
2. Buat cabang fitur baru (`git checkout -b fitur-anda`).
3. Commit perubahan Anda (`git commit -m 'Menambahkan fitur baru'`).
4. Push ke cabang (`git push origin fitur-anda`).
5. Buat Pull Request.

## Lisensi
Bebas copy