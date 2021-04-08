## RENTAL BUKU 
---

### Pengerjaan project alokasi 3 hari 
<hr><br>

**Sebelum mengerjakan project pastikan sesuai dengan ERD berikut ini : 
https://dbdiagram.io/d/606e9baeecb54e10c33f40a6

#### Deskripsi Fitur Minimum yang harus include dalam project

1. Pada project terdapat fitur Register, Login, Reset Password, Verifikasi Email dan Logout
(IMPLEMENTASI MENGGUNAKAN JWT)

2. Terdapat 2 role pengguna yaitu :
    * **Admin**
       * Admin dapat melakukan CRUD pada semua data 
    * **User**
       *  User bisa melihat daftar buku
    * 
3. Pada Apps terdapat menu :
    * **Katalog Buku**
    * **Top List**
    * **Terbaru**
    * Menu Top List dan Terbaru bisa di filter berdasarkan Pengarang, Tahun Terbit dan Kategori Buku
  

4. Rules peminjaman:
   * - Dalam satu kali peminjaman, user hanya dapat meminjam max. 3 buah buku 
   * Jika jadwal pengembalian terlambat dari yang dijadwalkan, maka akan dikenakan denda/ hari 
   * Transaksi baru tidak dapat dilakukan apabila denda belum di bayar. 

5. Terdapat fitur reminding yang mengigatkan user untuk mengembalikan buku sehari sebelum jatuh tempo pengembalian.

### NOTE 
1. Pengerjaan project melibatkan fitur yang disediakan oleh framework seperti Migration, Seeder, Middleware dan sebagainya. 