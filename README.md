<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Roswanda Nuraini</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210328</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A3</td>
  </tr>
  <tr>
    <td>Mata Kuliah</td>
    <td>Pemrograman Web 2</td>
  </tr>
</table>

# Praktikum 1: PHP Framework (Codeigniter)

Lengkapi kode program untuk menu lainnya yang ada pada Controller Page, sehingga semua link pada navigasi header dapat menampilkan tampilan dengan layout yang sama.

### 1. Tampilan <i>article.php</i>

![wanda article php](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/bc870d0b-4209-4150-b012-e68685dd2e1d)

### 2. Tampilan <i>about.php</i>

![wanda about php](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/68310462-7e1f-4694-bf75-6e5b7116de23)

### 3. Tampilan <i>contact.php</i>

![wanda contact php](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/48e8ba8e-3588-4c09-a06d-2a0946ebcc7d)

# Praktikum 2: Framework Lanjutan (CRUD)

Selesaikan programnya sesuai Langkah-langkah yang ada. Anda boleh melakukan improvisasi.

### 4. Mengaktifkan kembali di shell XAMPP http://localhost:8080/ dengan cara :

      cd [nama projek]
      
      php spark
      
      php spark serve

![Screenshot (42)](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/a5abfbec-0fe4-47b6-8284-34e043cd749a)

### 5. Membuat database di phpMyAdmin dengan menambahkan tabel artikel beserta isinya.

![wanda 4](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/8c0c2e52-a079-4400-bfb7-027517e0fb78)

### 6. Selanjutnya masuk ke halaman admin dengan mengakses http://localhost:8080/admin/artikel/ berikut tampilannya :

![wanda 5](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/8fa05a3e-da69-4b3a-ad6c-493f6a530720)

### 7. Dapat melakukan pencarian data di halaman admin, lalu klik tombol cari.

![wanda 6](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/5085ec47-7ae2-497a-800a-c33ec19a1385)

### 8. Kemudian bisa melakukan ubah data dengan klik tombolnya, lalu ubah sesuai keinginan.

![wanda 7](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/08acc198-906e-4eb7-a8cd-6f2d2365110e)

### 9. Setelah itu kita klik navbar artikel dan langsung masuk ke halaman beserta konten yang sudah dibuat.

![wanda 8](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/68fbd095-4bc4-4c8a-a821-0e5490054210)

### 10. Dapat melakukan tambah artikel dengan klik navbar bagian atas, lalu tambah artikel sesuai keinginan.

![wanda 9](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/ef542059-a864-4872-ae79-6048d6c55008)

# Praktikum 3: Framework Lanjutan (Modul Login)

Selesaikan programnya sesuai Langkah-langkah yang ada. Anda boleh melakukan improvisasi.

### 11. Tambahkan tabel pada database lab_ci4 dengan nama user.

![wanda 10](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/0540d5bd-a96a-49d1-b89f-9f30940d84e1)

### 12. Berikut merupakan tampilan halaman login :

![wanda 11](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/10913446-be38-418b-8270-7f0cc16fa81a)

### 13. Setelah itu isi dengan email dan password yang sesuai pada tabel user, sedangkan password_hash sebagai keterangan :

Dalam PHP, fungsi ```password_hash()``` digunakan untuk mengamankan atau mengenkripsi kata sandi (password) pengguna.

Tujuan utamanya adalah untuk melindungi kata sandi pengguna dengan cara yang aman.

Jika penulisan password tidak sesuai yang ada di database maka muncul notif danger/password salah.

```Passwordnya adalah "admin123"```

![wanda 12](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/8fd1d130-7b96-4983-b71b-7b4db582a989)

### 14. Isikan email dan password dengan benar, lalu klik login :

![wanda 13](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/7d8f89d5-0f2a-431b-acdc-48af86788019)

### 15. Berhasil masuk ke tampilan halaman admin makanan.

![wanda 14](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/9962d13c-d834-4704-9028-e679939c443e)

### 16. Kemudian terdapat menu atas logout, jika tidak memerlukan akses web tersebut dan klik :

![wanda 15](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/60d5df8a-d71b-438b-8d50-17b91f1c0a41)

### 17. Kembali ke tampilan halaman login

![wanda 16](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/cd278e6a-db42-43e6-8730-cc7f8c02b4a7)

# Praktikum 4: Pagination dan Pencarian

Selesaikan programnya sesuai Langkah-langkah yang ada. Anda boleh melakukan improvisasi.

### 18. Pilihan penomeran halaman

Terdapat penomeran halaman yang dapat dipilih apabila menu yang disediakan ada banyak, dan bisa memilih nomer secara urut maka akan tampil menu yang lainnya makanan & minuman.

![wanda 17](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/845545fc-e367-4772-aab7-954f0dcb89c5)

Lanjut pilih nomer :

![wanda 18](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/73c1e1ce-2cc7-4c64-b58c-b932adc93c28)

### 19. Pencarian halaman menu makanan & minuman

Buka folder dan file app/Controllers/Artikel.php lalu ubah pada function admin_index paginate ubah menjadi 10 yang tadinya 1.

1 --> Memperkecil halaman page

10 --> Memperluas halaman page

Kemudian lakukan pencarian dengan kata kunci harus judul makanan & minuman yang harus di cari, contohnya :

![wanda 19](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/9b0c7ea7-3ab0-4fd5-96a6-4b5d17e188bf)

Lalu hasil ketika dicari halamannya :

![wanda 20](https://github.com/roswanda11/lab7web-php-ci/assets/115516632/f83bbb27-ae62-4ba5-b9a8-ff039c74165a)


















