# Tugas Praktikum { Pertemuan ke 6 } <img src=https://qph.fs.quoracdn.net/main-qimg-648763cc041459725b62108f4fdf5b91 width="110px" >

| **Nama**              | **NIM**   | **Kelas** | **Matkul** |
| --------------------- | --------- | --------- | ---------- |
| Dhiyaulhaq Al Maududi | 312310508 | TI.23.A5  | Basis Data |

# Soal Latihan Praktikum

## 1. Tulis semua perintah-perintah SQL percobaan di atas beserta outputnya!

**1. Buat sebuah database dengan nama latihan2**

Untuk membuat database gunakan perintah sebagai berikut :

`CREATE DATABASE [nama_database]`

`CREATE DATABASE latihan2;`

**2. Buat sebuah tabel dengan nama biodata (nama, alamat) didalam database latihan2!**

Untuk membuat Tabel gunakan perintah sebagai berikut :

`CREATE TABLE nama_tabel (
    nama_field1 tipe _data(ukuran), nama_field2 tipe_data(ukuran), ..., nama_fieldn tipe_data(ukuran)
    );`

`CREATE TABLE biodata (
    nama varchar (100),
    alamat text
    );`

**3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom terakhir!**
`ALTER TABLE biodata ADD COLUMN keterangan VARCHAR (15);`

**4.Tambahkan kolom id(int 11) di awal (sebagai kolom pertama)!**
`ALTER TABLE biodata ADD COLUMN id int FIRST; `

**5. Sisipkan sebuah kolom dengan nama phone (varchar 15) setelah kolom alamat!**
Untuk menambahkan kolom setelah kolom lain yaitu dengan perintah `AFTER`

**6. Ubah tipe data kolom id menjadi char(11)!**
Untuk mengubah type data yaitu dengan perintah sebagai berikut :
`ALTER TABLE [nama_tabel] MODIFY nama_field tipe_data_baru(ukuran);`

**7. Ubah nama kolom phone menjadi hp (char 20)!**
Untuk mengubah kolom yaitu dengan perintah sebgai berikut :
`ALTER TABLE [nama_tabel] CHANGE nama_field_lama nama_field_baru tipe_data(ukuran);`

**8. Tambahkan kolom email setelah kolom hp**

**9. Hapus kolom keterangan dari tabel!**
Untuk menghapus kolom dari tabel yaitu dengan perintah sebagai berikut :
`ALTER TABLE [nama_tabel] DROP nama_field;`

**10. Ganti nama tabel menjadi data_mahasiswa!**
Untuk mengganti nama tabel yaitu dengan perintah sebagai berikut :
`ALTER TABLE [nama_tabel] RENAME [nama_tabel_baru];`

**11. Ganti nama field id menjadi nim!**

**12. Jadikan nim sebagai PRIMARY KEY!**
Untuk menambahkan index atau key, gunakan perintah sebagai berikut :

tipe index :

- PRIMARY KEY
- UNIQUE KEY
- FULLTEXT

`ALTER TABLE [nama_tabel] ADD [INDEX|PRIMARY KEY] (nama_field);`

**13. Jadikan kolom email sebagai UNIQUE KEY!**
Perintah nya sama seperti diatas, hanya saja diganti menjadi `UNIQUE KEY`

**Berikut bukti tugas yang sudah dikerjakan**
-  ![Screenshot 2024-04-24 222228](https://github.com/Pynixz/Praktikum1.S2/assets/147568964/a7a31d0a-b2b3-4ff7-aefd-60764111c870)
-  ![Screenshot 2024-04-24 222222](https://github.com/Pynixz/Praktikum1.S2/assets/147568964/4bdccf0e-6ff7-4f5f-a7fe-83eee0ebbdab)
-  ![Screenshot 2024-04-24 222139](https://github.com/Pynixz/Praktikum1.S2/assets/147568964/f42998b6-8830-4a3b-acc9-5bc7d09076d3)
-  ![Screenshot 2024-04-24 222126](https://github.com/Pynixz/Praktikum1.S2/assets/147568964/75ada04e-79ca-4bc6-b7d3-21f39985379e)
