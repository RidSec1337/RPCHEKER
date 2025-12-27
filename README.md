# 🚀 XML-RPC Checker Tools

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows-green)
![Thread](https://img.shields.io/badge/Thread-50-orange)
![Status](https://img.shields.io/badge/Status-Stable-success)

Author: RIDXPLOIT

XML-RPC Checker Tools adalah tools berbasis Python yang digunakan untuk melakukan pengecekan massal website WordPress guna mengetahui apakah endpoint xmlrpc.php aktif atau tidak.  
Tools ini dibuat untuk keperluan audit keamanan, bug hunting, security research, dan pembelajaran penetration testing.

====================
FITUR
====================
- Deteksi otomatis website WordPress
- Pengecekan XML-RPC (xmlrpc.php)
- Multi-threading (fixed 50 thread)
- Output terminal berwarna
- Menyimpan hasil XML-RPC aktif otomatis
- Support Linux dan Windows

====================
OUTPUT
====================
good_xmlrpc.txt  
Berisi daftar domain WordPress dengan XML-RPC aktif

====================
INSTALASI (KALI LINUX / LINUX)
====================
apt update && apt upgrade -y
apt install python3 python3-pip git -y
pip3 install requests termcolor

====================
INSTALASI (WINDOWS)
====================
1. Download dan install Python 3.x  
   https://www.python.org/downloads/

2. Pastikan Python sudah ditambahkan ke PATH

3. Install dependency melalui CMD / PowerShell:
pip install requests termcolor

====================
CARA PENGGUNAAN (KALI LINUX / LINUX)
====================
python3 xmlrpc_checker.py

====================
CARA PENGGUNAAN (WINDOWS)
====================
python xmlrpc_checker.py

====================
INPUT FILE
====================
Saat diminta, masukkan file list domain:

ENTER FILE DOMAIN:

Contoh isi file:
example.com
https://target.com
wordpresssite.net

====================
CONTOH OUTPUT
====================
- https://example.com [ YES ] XML-RPC endpoint reachable
- https://site.com [ NOT-WP ] Not a WordPress site
- https://test.net [ TIMEOUT ] Connection timeout

====================
DISCLAIMER
====================
Tools ini dibuat hanya untuk tujuan edukasi dan pengujian keamanan secara legal.  
Segala bentuk penyalahgunaan tools ini sepenuhnya menjadi tanggung jawab pengguna.

====================
TERIMA KASIH
====================
Terima kasih telah menggunakan XML-RPC Checker Tools.  
Jika tools ini bermanfaat, jangan lupa memberikan bintang (star) pada repository ini.

====================
TELEGRAM
====================
Bergabung untuk update tools dan sharing ilmu security:
https://t.me/RIDXPLOIT

Happy Hacking & Stay Ethical
