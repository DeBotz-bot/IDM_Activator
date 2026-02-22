# 🚀 IDM Activator Pro

**IDM Activator Pro** adalah aplikasi berbasis Python dengan antarmuka
GUI modern yang membantu proses aktivasi Internet Download Manager
secara otomatis melalui konfigurasi registry Windows.

Aplikasi ini memiliki tampilan modern, sistem pengecekan update
otomatis, serta beberapa fitur tambahan untuk mempermudah pengguna dalam
mengelola IDM.

------------------------------------------------------------------------

## ✨ Fitur Utama

-   ⚡ Aktivasi otomatis IDM
-   🛑 Menutup proses IDM sebelum aktivasi
-   💻 Membuka IDM langsung dari aplikasi
-   📥 Download IDM
-   🔄 Auto update dari GitHub
-   📊 Status aktivasi dengan progress bar
-   🎨 Modern GUI berbasis Tkinter
-   🔐 Menggunakan hak akses Administrator

------------------------------------------------------------------------

## 🖥️ Tampilan Aplikasi

Aplikasi memiliki beberapa panel utama:

-   **Status Aktivasi**
-   **Informasi Sistem**
-   **Control Panel**

Menu utama yang tersedia:

-   Exit IDM
-   Aktivasi
-   Buka IDM
-   Download IDM
-   Check Update

------------------------------------------------------------------------

## 📦 Requirements

Sistem yang didukung:

-   Windows 7 / 8 / 10 / 11
-   Python 3.8+

Library Python yang digunakan:

-   tkinter
-   requests
-   Pillow (opsional)
-   subprocess
-   winreg
-   threading

Install dependency:

``` bash
pip install requests pillow
```

------------------------------------------------------------------------

## ▶️ Cara Menjalankan

1.  Clone repository

``` bash
git clone https://github.com/username_anda/IDM-Activator.git
```

2.  Masuk ke folder project

``` bash
cd IDM-Activator
```

3.  Jalankan aplikasi

``` bash
python main.py
```

------------------------------------------------------------------------

## 📥 Build ke EXE

Untuk membuat file executable (.exe) gunakan PyInstaller.

Install PyInstaller:

``` bash
pip install pyinstaller
```

Build aplikasi:

``` bash
pyinstaller --onefile --noconsole --icon=app.ico main.py
```

File hasil build akan muncul di folder:

    dist/

------------------------------------------------------------------------

## 🔄 Sistem Update

Aplikasi menggunakan sistem update otomatis melalui file:

    version.json

Contoh isi file:

``` json
{
  "version": "6.42.B62",
  "notes": "Bug fix and improvement",
  "download_url": "https://github.com/username_anda/IDM-Activator/releases/download/latest/IDM_Activator_Pro.exe"
}
```

------------------------------------------------------------------------

## 📂 Struktur Project

    IDM-Activator/
    │
    ├── main.py
    ├── app.ico
    ├── version.json
    ├── README.md
    └── assets/

------------------------------------------------------------------------

## ⚠️ Disclaimer

Project ini dibuat untuk tujuan edukasi dan pembelajaran pemrograman
Python GUI. Developer tidak bertanggung jawab atas penggunaan software
ini yang melanggar lisensi perangkat lunak pihak ketiga.

------------------------------------------------------------------------

## 👨‍💻 Author

Debotz V1

------------------------------------------------------------------------

## ⭐ Support

Jika project ini membantu kamu, jangan lupa memberikan ⭐ pada
repository GitHub.
