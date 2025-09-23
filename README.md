# Lab1Web
Praktikum 1 — Dasar HTML

**Nama : Nadine Amelia Putri**

**NIM : 312410188**

**Kelas : TI.24.A2**

**Mata Kuliah : *Pemrograman Web 1***

**Dosen : Agung Nugroho, S.Kom., M.Kom**


*Praktikum 1 — Dasar HTML*

### A. Langkah 1: Membuat Struktur Dasar HTML
<img width="579" height="279" alt="Cuplikan layar 2025-09-23 000828" src="https://github.com/user-attachments/assets/cef2c52d-c9fb-48e4-acec-999e74d14953" />

Pertama, saya membuat file `lab1_tag_dasar.html` sebagai halaman utama.
Di dalam file ini saya menuliskan struktur dasar HTML5. Kemudian pada bagian isi, saya menambahkan identitas berupa: *Nama, Nim, Kelas, Mata Kuliah, Nama Dosen*



### B. Langkah 2: Menambahkan Navigasi (Menu Link)
<img width="611" height="319" alt="Cuplikan layar 2025-09-23 000844" src="https://github.com/user-attachments/assets/43a23ef6-517a-4fbf-beaa-eb4a2c1b2f68" />

Selanjutnya saya membuat navigasi menggunakan tag `<nav>` untuk membuat navigasi berisi link ke:
- `lab1_tag_dasar.html` → Menuju Halaman Dasar HTML  
- `lab1_halaman2.html` → Menuju Halaman 2  
- `https://www.google.com` → Menuju situs eksternal Google  

Dibawah navigasi saya menambahkan elemen  `</hr>` untuk membuat garis pemisah



### C. Langkah 3: Membuat Judul dan Paragraf
<img width="1038" height="479" alt="Cuplikan layar 2025-09-23 000859" src="https://github.com/user-attachments/assets/aec0dbaa-03c9-4e94-9c2a-7d263325359d" />

Pada bagian isi utama, saya menambahkan:
- Heading `<h1>` dengan teks Belajar Dasar HTML sebagai judul utama halaman.
- Paragraf `<p>` yang berisi penjelasan tentang pembelajaran HTML dasar.
Saya juga membuat paragraf yang berisi kalimat penjelasan. Pada paragraf ini saya memberikan format teks:  
- Highlight teks menggunakan `<span style="background-color:yellow;">HTML dasar</span>`  
- Huruf miring dengan `<span style="font-style:italic;">Teknik Informatika</span>`
- Huruf tebal dengan `<span style="font-style:bold;">Pemrograman Web</span>`  
- Link `<a>` menuju website resmi Universitas Pelita Bangsa.

  

### D. Langkah 4: Menambahkan Sub Judul dan Paragraf Kedua
<img width="1042" height="601" alt="Cuplikan layar 2025-09-23 000955" src="https://github.com/user-attachments/assets/7667ea89-b2ec-48fc-a206-550d9bffdc8c" />

Berikutnya saya menambahkan sub judul dengan tag `<h2>` dengan teks *Paragraf pada HTML*.  
Lalu saya menambahkan paragraf baru sebagai contoh penggunaan tag `<p>`yang berisi penjelasan singkat tentang paragraf dalam HTML. 



### E. Langkah 5: Menambahkan Gambar
<img width="1070" height="907" alt="Cuplikan layar 2025-09-22 225708" src="https://github.com/user-attachments/assets/1a068dd1-a3ce-47d6-a955-5398e2f1d8a5" />

Dibagian bawah halaman saya menambahkan sub judul `<h3>` dengan teks *Universitas Pelita Bangsa*.  
Setelah itu saya menambahkan gambar logo Universitas Pelita Bangsa menggunakan tag `<img src="logo-Universitas-Pelita-Bangsa.png" width="300">`.  



### F. Langkah 6: Membuat Halaman Kedua
<img width="634" height="252" alt="halaman 2" src="https://github.com/user-attachments/assets/b01a6e4f-8773-485f-9eb3-9e2fc37ef6d2" />


Selain halaman utama, saya juga membuat halaman kedua dengan nama file **lab1_halaman2.html**.  
Halaman ini berisi heading `<h1>` dengan teks **Halaman Kedua**, serta sebuah paragraf sederhana. Kemudian di bagian bawah saya tambahkan link untuk kembali ke halaman utama (`lab1_tag_dasar.html`).  

Halaman Kedua ini berfungsi sebagai contoh penggunaan hyperlink antar halaman lokal.



<img width="738" height="234" alt="Cuplikan layar 2025-09-22 142154" src="https://github.com/user-attachments/assets/6dd74e19-ce22-4831-8ccb-86566d787479" />


**_Jawaban Soal Diatas_**

**Soal 1**
Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

Jawaban:

Perubahan kode HTML (misalnya menambahkan heading, paragraf, hyperlink, atau gambar) akan langsung memengaruhi tampilan di browser tanpa perlu kompilasi.

Kesalahan penulisan tag HTML tidak menimbulkan error fatal (seperti “syntax error” pada bahasa pemrograman). Hal ini karena HTML bersifat toleran terhadap kesalahan. Browser akan mencoba memperbaiki secara otomatis.
Namun, akibatnya bisa:
- Tampilan menjadi tidak sesuai (contoh: teks tidak diformat, layout berantakan).
- Elemen tertentu tidak muncul.
- Validasi HTML gagal ketika diperiksa di validator W3C.

contohnya:

<img width="955" height="115" alt="image" src="https://github.com/user-attachments/assets/96aa5c1a-bba1-4fbc-bea3-861f23e37a6d" />


pada line 37 tag tidak tertutup `</h3>` yang akan menghasilkan tampilan teks disamping gambar bukan di atas

<img width="626" height="332" alt="Cuplikan layar 2025-09-23 010057" src="https://github.com/user-attachments/assets/f31f7be2-5e0d-4bad-bac4-c8dba59a2ec7" />


**Soal 2**
Apa perbedaan dari tag ```<p>``` dengan tag ```<br>```, berikan penjelasannya!

Jawaban

Tag `<p>`(paragraph):
- Digunakan untuk membuat paragraf.
- Memiliki jarak (margin) otomatis di atas dan bawah.
-` Merupakan elemen block-level (mengisi satu blok penuh).
- contohnya:

```html
<p>Ini paragraf pertama.</p>
<p>Ini paragraf kedua.</p>
```

Tag `<br>` (break line):
- Digunakan untuk pindah baris baru tanpa membuat paragraf baru.
- Tidak menambah jarak antar baris.
- Termasuk elemen inline.
- contoh:

```html
  Kalimat pertama<br>
  Kalimat kedua<br> 
  Kalimat ketiga.
```

**3. Perbedaan Atribut `title` dan `alt` pada Tag <img>**

Jawaban: Kedua atribut ini memberikan informasi tambahan pada gambar, namun fungsinya berbeda.

`<alt>` (alternative text):
- Menyediakan teks alternatif jika gambar tidak dapat dimuat.
- Digunakan oleh screen reader untuk membantu pengguna difabel.
- Wajib digunakan untuk alasan aksesibilitas.

`<title>`:
- Menyediakan informasi tambahan yang ditampilkan sebagai tooltip ketika kursor diarahkan ke gambar.
- Tidak berfungsi sebagai pengganti gambar.

Kesimpulan: alt berfungsi sebagai deskripsi pengganti, sedangkan title berfungsi sebagai informasi tambahan interaktif.

**4. Pengaturan Ukuran Gambar dengan `<width>` dan `<height>`**

Atribut `<width>` dan `<height>` digunakan untuk mengatur dimensi gambar. Namun, penggunaannya perlu diperhatikan agar proporsional.

- Jika kedua atribut diisi sesuai rasio asli gambar, tampilan tetap proporsional.
- Jika hanya salah satu atribut diisi, browser akan otomatis menyesuaikan atribut lainnya sesuai proporsi asli gambar.
- Jika keduanya diisi tidak sesuai rasio, maka gambar akan terlihat terdistorsi (gepeng atau melebar).

Kesimpulan: Untuk menjaga proporsionalitas, sebaiknya cukup mengisi salah satu atribut saja (misalnya `<width>`), atau pastikan nilai `<width>` dan `<height>` sesuai dengan rasio gambar asli.

**5. Fungsi Atribut target pada Tag `<a>`**

Atribut target digunakan untuk menentukan lokasi atau cara link dibuka pada browser.

```target="_blank"``` → Membuka link di tab/jendela baru.

```target="_self"``` → Membuka link di halaman yang sama (nilai default).

```target="_top"```` → Membuka link di halaman penuh, keluar dari frame.

```target="_parent"``` → Membuka link di frame induk (jika halaman berada dalam frameset).

Contoh:

```<a href="halaman2.html" target="_blank">Buka di tab baru</a>```

```<a href="halaman2.html" target="_self">Buka di halaman ini</a>```


Kesimpulan: Pemilihan nilai target disesuaikan dengan kebutuhan navigasi web, apakah ingin tetap pada halaman yang sama, membuka tab baru, atau keluar dari struktur frame.
