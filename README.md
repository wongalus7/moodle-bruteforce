# Moodle-Bruuteforce - Moodle Single Login Page Bruteforce with custom powerful wordlist!
![Moodle-Bruuteforce](https://i.imgur.com/GmrBSba.png)
**Moodle-Bruuteforce** - Moodle Single Login Page Bruteforce with custom powerful wordlist ini dibuat untuk melakukan bruteforce login pada halaman login Moodle menggunakan kombinasi username dan password. Didesain untuk mempermudah penetration testing login dengan custom wordlist yang bisa dihasilkan secara dinamis (simple and powerful) lalu dilanjutkan bruteforce menggunakan file wordlist default (wordy.txt).


## Fitur
- Mass username dan mass generate wordlist
- Custom Wordlist Generator: Buat wordlist otomatis dengan kombinasi kata dasar, simbol, dan angka.
- Multithreading: Percepat proses bruteforce dengan menggunakan banyak thread.
- Moodle Token Detection: Secara otomatis menangani token login Moodle jika diperlukan.
- User-Friendly Output: Progress tracking dan hasil percobaan ditampilkan secara real-time.
- File Wordlist Support: Gunakan wordlist tambahan dari file wordy.txt.

## Requirements
Sebelum menjalankan alat ini, pastikan Kamu telah menginstal dependensi berikut:
Kamu dapat menginstal yang dibutuhkan untuk menjalankan tools ini menggunakan perintah berikut di terminal:

```bash
apt update
apt upgrade
apt install python3
apt install python3-pip
apt install git
pip3 install requests colorama urllib3
git clone https://github.com/wongalus7/moodle-bruteforce
cd moodle-bruteforce
python3 brute.py
```
## Disclaimer
Tools ini dibuat untuk tujuan edukasi dan penetration testing. Penggunaan alat ini untuk menyerang atau mengeksploitasi sistem tanpa izin adalah ilegal. Pembuat tools ini (@wongalus7) tidak bertanggung jawab atas penggunaan alat ini secara tidak sah.

Author: https://github.com/zelsaddr/Moodle_Bruteforcer
