# labpy03
Nama        : M.Ridho Febrian<p>

Kelas       : TI.24.A.5 <p>

Nim         : 312410500 <p>

Mata kuliah : Bahasa Pemrograman <p>

# Alur Algoritma latihan1: latihan1.py
1. Start - Program dimulai

2. Import random - Mengimpor modul random untuk menghasilkan bilangan acak

3. Input jumlah bilangan 'n' - User memasukkan berapa banyak bilangan acak yang ingin dihasilkan

4. Inisialisasi count = 0 - Membuat variabel count untuk menghitung berapa bilangan yang sudah dihasilkan

5. Pengecekan count < n

Jika ya: lanjut ke langkah berikutnya

Jika tidak: program selesai

6. Generate bilangan acak 'a' - Menghasilkan bilangan acak antara 0 dan 1

7. Pengecekan a < 0.5

Jika ya:
Print bilangan 'a'
Increment count
Kembali ke pengecekan count < n


Jika tidak:
Kembali ke pengecekan count < n

8. End - Program selesai

Catatan penting:

Program akan terus menghasilkan bilangan acak sampai mendapatkan n bilangan yang nilainya < 0.5
Bilangan acak yang dihasilkan berada dalam rentang 0 sampai 1
Hanya bilangan yang < 0.5 yang akan dicetak dan dihitung
Loop akan terus berjalan sampai mendapatkan jumlah bilangan yang diinginkan (count = n)

# tampilan code program python nya:
![foto](https://github.com/ridhofebriann/labpy03/blob/main/ss%20latihan1.png?raw=true)

# Berikut hasil code program python yang sudah di jalankan:
![foto](https://github.com/ridhofebriann/labpy03/blob/main/ss2%20latihan1.png?raw=true)


# Alur Algoritma latihan2: latihan2.py
1. Fungsi hitung_keuntungan

Input/Parameter:

Modal awal usaha

Array persentase laba bulanan
Inisialisasi Variabel:

Variabel untuk total keuntungan = 0
Array kosong untuk menyimpan laba bulanan
Proses Perhitungan (Perulangan):

Untuk setiap bulan:
Hitung laba = modal awal × persentase bulan tersebut
Simpan laba ke dalam array laba bulanan
Tambahkan laba ke total keuntungan
Tampilkan laba bulan tersebut
Output/Return:

Nilai total keuntungan
Array laba bulanan

2. Fungsi Main

Set Nilai Awal:

Modal awal = 100 juta rupiah

Array persentase laba 8 bulan:

Bulan 1-2: 0%

Bulan 3-4: 1%

Bulan 5-7: 5%

Bulan 8: 3%

Eksekusi Program:

Panggil fungsi hitung_keuntungan
Terima nilai kembalian:

Total keuntungan

Array laba bulanan

Tampilkan total keuntungan

3. Alur Data

Input:
Modal awal (nilai tetap)
Array persentase laba (nilai tetap)

Proses:
Perhitungan laba per bulan
Akumulasi total keuntungan
Penyimpanan data laba bulanan

Output:
Laba per bulan (ditampilkan)
Total keuntungan (ditampilkan)

4. Detail Perhitungan

Bulan 1: Modal × 0% = 0

Bulan 2: Modal × 0% = 0

Bulan 3: Modal × 1% = 1 juta

Bulan 4: Modal × 1% = 1 juta

Bulan 5: Modal × 5% = 5 juta

Bulan 6: Modal × 5% = 5 juta

Bulan 7: Modal × 5% = 5 juta

Bulan 8: Modal × 3% = 3 juta

Total = 20 juta

5. Struktur Output

Per Bulan:
Nomor bulan
Jumlah laba dalam rupiah

Akhir:
Total keuntungan dalam rupiah

6. Validasi

Program mengasumsikan:

Modal awal positif

Persentase dalam desimal

Jumlah bulan tetap (8)

Tidak ada validasi input

7. Tujuan Program

Menghitung keuntungan bulanan

Mengakumulasi total keuntungan

Menampilkan laporan laba rugi sederhana

# berikut foto code program python nya:
![foto](https://github.com/ridhofebriann/labpy03/blob/main/ss1%20latihan2.png?raw=true)

# berikut hasil code program python yang sudah di jalankan:
![foto](https://github.com/ridhofebriann/labpy03/blob/main/ss2%20latihan2.png?raw=true)


# Alur algoritma latihan3: latihan3.py
1. Inisialisasi

Set saldo awal = 1.000.000

Tampilkan pesan selamat datang

Tampilkan saldo awal

2. Loop Utama (while True)

Tampilkan menu:

Tarik Tunai

Cek Saldo

Keluar

Minta input pilihan dari pengguna

3. Proses Pilihan

Jika pilihan = 1 (Tarik Tunai):

a. Minta input jumlah penarikan

b. Validasi jumlah penarikan:

Jika jumlah > saldo: Tampilkan pesan error

Jika jumlah <= 0: Tampilkan pesan error

Jika valid:

Kurangi saldo dengan jumlah penarikan

Tampilkan jumlah penarikan dan saldo baru

Jika pilihan = 2 (Cek Saldo):

a. Tampilkan saldo saat ini

Jika pilihan = 3 (Keluar):

a. Tampilkan pesan terima kasih 

b. Keluar dari loop (break)

Jika pilihan tidak valid: a. Tampilkan pesan error

4. Kembali ke awal loop (langkah 2) jika tidak memilih keluar

5. Program selesai

# berikut code program python nya:
![foto](https://github.com/ridhofebriann/labpy03/blob/main/ss1%20latihan3.png?raw=true)

# berikut hasil code program yang sudah di jalankan:
![foto](https://github.com/ridhofebriann/labpy03/blob/main/ss2%20latihan%203.png?raw=true)
