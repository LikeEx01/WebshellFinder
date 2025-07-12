# WebShell-Scanner 

## Badge
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Platform](https://img.shields.io/badge/platform-Termux%20%7C%20Linux%20%7C%20Windows-lightgrey)
![Made With](https://img.shields.io/badge/made%20with-Python-orange)
![Status](https://img.shields.io/badge/status-active-success)

![WebShell Scanner Banner](https://h.top4top.io/p_3480ppnz33.jpg)

## Deskripsi

**WebShell Scanner (WebSehllFinder)** adalah alat pemindaian otomatis untuk mendeteksi keberadaan file backdoor atau webshell pada ribuan situs. Tools ini bekerja dengan cara mencocokkan path berbahaya terhadap daftar target dan memeriksa signature khas dari berbagai jenis WebShell.

Hasil deteksi akan disimpan secara lokal ke file.

## Fitur Utama

- ✅ Deteksi webshell otomatis melalui konten HTML
- ✅ Scan massal dengan multithread (cepat & efisien)
- ✅ Simpan hasil shell aktif ke `WebSellResult.txt`
- ✅ Kompatibel dengan Termux, Linux, dan Windows
- ✅ Anti SSL error & timeout 15 detik

## Persyaratan

- Python 3.x
- Modul Python:
  - `requests`
  - `colorama`
  - `urllib3`

## Instalasi

### Termux
```bash
pkg update && pkg upgrade -y
pkg install python git -y
pip install requests colorama urllib3
```

### Linux / Debian
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git -y
pip3 install requests colorama urllib3
```

## Penggunaan

1. Clone repo:
```bash
git clone https://github.com/LikeEx01/WebshellFinder.git
cd WebShell-Scanner
```

2. Siapkan file `target.txt` berisi list domain:
```
http://example.com
https://site.org
```

3. Jalankan tools:
```bash
python3 scanner.py
```

4. Masukkan nama file target saat diminta:
```
ENTER LIST SITE: target.txt
```

## Output

- Semua URL shell aktif akan disimpan ke:
  ```
  WebSellResult.txt
  ```

Contoh hasil:
```
[Vuln] http://example.com/shell.php --> Web shell found
```

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT).

## Penafian ⚠️

> Alat ini hanya untuk keperluan pembelajaran dan pengujian keamanan yang sah.  
> Dilarang menggunakan tools ini untuk menyerang situs tanpa izin eksplisit dari pemiliknya.  
> Segala risiko ditanggung pengguna sepenuhnya.

## Kontak

- Telegram: [LikeEx01](https://t.me/usernamee1337)
- GitHub: [LikeEx01](https://github.com/LikeEx01)

🔗 **Repo GitHub:** [https://github.com/LikeEx01/WebShell-Scanner](https://github.com/LikeEx01/WebshellFinder.git)
