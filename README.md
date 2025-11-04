<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/19fc74b9-9b09-421b-8434-cf87526ba0f1" /><img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/6cc036f2-91f0-430a-9e42-c2a74be1c365" />README - Tugas UTS Pemrograman Web 1 

Nama : SURYA PUTRRA DARMA JAYA
NIM : 312410405
Kelas : TI.24.A3
----------------------------------------------------
Struktur folder: (sesuai soal)
- index.html (login)
- dashboard.html (role-based: Admin/User)
- stok.html (admin only)
- checkout.html (user only)
- tracking.html (user only)
- css/style.css
- js/data.js  <-- file data sesuai yang Anda berikan (tdk diubah)
- js/script.js
- assets/logo.png 
- img/... 

Akun contoh (ada di data.js):
- User: darma@gmail.com / darma123
- User: putra@gmail.com / putra123
- Admin: surya@gmail.com / surya123

Petunjuk singkat:
1. Buka index.html, login dengan salah satu akun di atas.
2. Setelah login, akan diarahkan ke dashboard. Navigation menyesuaikan role:
   - Admin: lihat menu "Informasi Stok / Katalog" (stok.html) untuk kelola buku.
   ![](imgdocs/admin.png)
   
   - User: gunakan "Pemesanan" (checkout.html) dan "Tracking" (tracking.html).

   ![](imgdocs/checkout.png)

   ![](imgdocs/tracking.png)
3. Semua aksi bersifat simulasi (client-side). Data tersimpan hanya di memori halaman (sessionStorage).
