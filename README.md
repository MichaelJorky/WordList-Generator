# WordList Generator

> **Peringatan:** :red_circle: Aplikasi ini dibuat khusus untuk keperluan pendidikan dan penelitian. Penulis tidak bertanggung jawab atas segala bentuk penyalahgunaan atau kerusakan yang mungkin timbul dari penggunaan program ini. Harap gunakan dengan bijak dan hanya di lingkungan di mana Anda memiliki izin eksplisit.

**Aplikasi Wordlist Generator** adalah alat yang digunakan untuk menghasilkan daftar kata (wordlist) atau kombinasi karakter berdasarkan kriteria tertentu, seperti panjang kata, pola, karakter khusus, angka, atau simbol. Daftar ini biasanya digunakan dalam uji keamanan (seperti *penetration testing*) untuk mengevaluasi kekuatan kata sandi dengan mensimulasikan serangan *brute-force* atau *dictionary attack*.

### Fungsi Utama:
1. **Membuat Kombinasi Karakter**: Menghasilkan semua kemungkinan kombinasi dari huruf, angka, dan simbol.
2. **Pola Kustom**: Memungkinkan pengguna menentukan pola (misal: 3 huruf + 2 angka + 1 simbol).
3. **Kriteria Spesifik**: Menyesuaikan output berdasarkan panjang kata, karakter tertentu, atau kata dasar (seperti nama atau tanggal).

### Contoh Penggunaan:
- **Uji Keamanan**: Ethical hacker menggunakan wordlist untuk menguji kerentanan sistem terhadap serangan kata sandi.
- **Pemulihan Data**: Membantu memulihkan kata sandi yang terlupa (jika digunakan secara legal).
- **Penelitian Kriptografi**: Menganalisis pola kelemahan kata sandi.

### Contoh Alat:
- **Crunch**: Tool CLI untuk membuat wordlist dengan pola spesifik.
- **Hashcat**: Tool multifungsi yang bisa menghasilkan dan menguji wordlist.
- **John the Ripper**: Tool *password cracking* dengan fitur pembuatan wordlist.
- **RSMangler**: Membuat variasi kata dari input teks (misal: mengganti huruf dengan angka).

### Aspek Etis dan Legal:
- Penggunaan wordlist generator **hanya legal** jika dilakukan dengan izin pemilik sistem (misal: pengujian keamanan).
- Penggunaan untuk membobol akun atau sistem tanpa izin adalah **tindakan kriminal**.

### Fitur Umum:
- Penyesuaian karakter (huruf besar/kecil, angka, simbol).
- Pembuatan kata berdasarkan kamus (*dictionary-based*).
- Penyimpanan hasil dalam file teks.

### Catatan:
Wordlist generator adalah alat netral. Penggunaannya tergantung pada tujuan pengguna — penting untuk mematuhi hukum dan etika keamanan siber.

#
<b>[ Cara Menggunakan WordList Generator ]</b>

1. Download WordList Generator via: https://github.com/MichaelJorky/WordList-Generator/releases
2. Word Count: adalah jumlah kata yang ingin di Generate.
3. Character Length: adalah panjang karakter, min 1 maks 15.
4. UpperCase: jika UpperCase di ceklis maka "ABCDEFGHIJKLMNOPQRSTUVWXYZ" akan dimasukan dalam daftar Generate.
5. LowerCase: jika LowerCase di ceklis maka "abcdefghijklmnopqrstuvwxyz" akan dimasukan dalam daftar Generate.
6. Digits: jika Digits di ceklis maka "0123456789" akan dimasukan dalam daftar Generate.
7. Symbol: jika Symbol di ceklis maka "@#$_-.,!?&*()[]{}<>%^+=|\/~" akan dimasukan dalam daftar Generate.
8. DateTime: jika DateTime di ceklist maka akan menghasilkan kombinasi tanggal, bulan (number/text), tahun
9. Klik "Generate Word!" untuk memulai menghasilkan WordList.
