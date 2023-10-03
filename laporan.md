# cooKing WebApps
![CooKING Logo](https://github.com/naufaiqr/komdat-laporan/assets/100478607/ffa4e231-8591-4f11-af2b-370fd50acd9d)

### Deskripsi
cooKING adalah sebuah aplikasi berbasis web yang dapat digunakan untuk mencari dan membagikan resep makanan antar sesama pengguna. Adanya cooKING bertujuan untuk mengumpulkan resep-resep makanan yang ada di internet sehingga pengguna akan lebih mudah mencarinya tanpa perlu membuka buku resep atau media sosial.

### Fitur-fitur
- Sign Up & Sign In
- Cari resep
- Filtering resep
- Upload dan hapus resep

### System Requirement (Local)
- File program cooKING
- `XAMPP` Control Panel
- Database (SQL) `PHP MyAdmin`

### Local Installation
- Install XAMPP
- Masukkan file aplikasi web (folder) ke direktori “htdocs” XAmpp: `C:\xampp\htdocs`
- Buka XAMPP
- Nyalakan modul Apache dan MySQL
- Buka browser dan ketik `localhost/(nama folder program)`

### Hosting
- Buka laman web penyedia jasa hosting di browser
- Pergi ke Control Panel (cPanel) dalam web hosting
<img width="779" alt="image" src="https://github.com/naufaiqr/komdat-laporan/assets/100478607/6d893162-3fca-4a6d-8643-7cbaeaa1b219">

- Buka file manager untuk web di cPanel dalam direktori `public_html`
<img width="265" alt="image" src="https://github.com/naufaiqr/komdat-laporan/assets/100478607/84b15634-4b96-428b-8595-2165cbab7fc0">

- Upload file program (upload dalam bentuk ZIP untuk memudahkan proses)
- Ekstrak file ZIP

### Connect Database & Website (PHPMyAdmin)
- Pilih “MySQL Databases” untuk membuat database baru
  <img width="655" alt="image" src="https://github.com/naufaiqr/komdat-laporan/assets/100478607/2840bc8f-0c0b-4b6e-b781-f51e6631bc69">

- Buat Database baru
<img width="751" alt="image" src="https://github.com/naufaiqr/komdat-laporan/assets/100478607/4b42aa61-45ea-456d-b46c-d59e9864da0b">

- Buat user yang akan digunakan untuk diberi akses ke Database (user admin)
<img width="595" alt="image" src="https://github.com/naufaiqr/komdat-laporan/assets/100478607/e2e64560-decf-48dd-8c8b-4831aca58f8a">

- Kembali ke halaman awal cPanel
- Pilih `PHPMyAdmin` untuk mengakses *control* database
- Database baru akan muncul
- Import file database yang sudah disiapkan ke dalam database yang baru dibuat di `PHPMyAdmin`
<img width="856" alt="image" src="https://github.com/naufaiqr/komdat-laporan/assets/100478607/c1a84cb3-c37b-4310-b08c-b577d11395a6">


### Cara Pemakaian
Cara pemakaian webApps ini cukup sederhana karena fitur-fitur yang ada mudah dipahami untuk langsung digunakan.
1. Pengguna dapat langsung melakukan pencarian terhadap resep yang ingin ditemukan pada web tanpa harus melakukan sign up/login dahulu. Selain itu, pengguna juga dapat langsung melihat resep-resep yang baru diunggah oleh pengguna lain.

2. Untuk mengunggah suatu resep, pengguna harus memiliki akun dahulu (sign up).

3. Apabila pengguna sudah memiliki akun, pengguna harus masuk ke akun yang dimiliki (sign in/login).
  
4. Pengguna dapat mengunjungi bagian profile untuk melakukan perubahan terhadap akun dan mengunggah resep. Pengguna juga dapat menghapus akun yang dimiliki.

5. Berikut ini formulir yang harus diisi ketika ingin mengunggah resep.

### Pembahasan
kelebihan dan kekurangan
