# personal-web-nihayatus-sa-adah
personal web nihayatus sa'adah menggunakan PHP, MySQL, HTML, dan TailwindCSS

**1. **Halaman Dashboard Admin****

a. Fungsi Halaman: Halaman utama admin setelah berhasil login. Berfungsi menampilkan informasi ringkas dan akses cepat ke manajemen konten.

b. Elemen:
•	Header:
o Judul situs: Personal Web | Nihayatus Sa’adah

c. Greeting Section:
o	Pesan: “Halo, niha! Apa kabar? 😊”
o	Memberikan kesan personal dan ramah untuk admin yang login.

d. Statistik Ringkas:
o	Artikel: 6
o	Gallery: 16
o	Tampil dalam bentuk kotak info berwarna (kemungkinan hijau dan biru).
•	Navigasi Sidebar:
o	Beranda
o	Kelola Artikel
o	Kelola Gallery
o	About
o	Logout (berwarna merah menonjol sebagai tombol keluar)
•	Footer:
o	© 2025 | Created by Nihayatus Sa’adah

<img width="650" alt="Screenshot 2025-07-02 202401" src="https://github.com/user-attachments/assets/9438bcf9-2aec-4441-b9eb-def5620b1881" />

**2. Halaman Kelola Artikel**

a. Fungsi Halaman:
Untuk menampilkan dan mengelola seluruh artikel yang sudah dimasukkan admin. Termasuk fitur tambah, edit, dan hapus artikel.

b. Elemen:
•	Header:
o	Tulisan // HALAMAN ADMIN //

c. Tombol Tambah Artikel:
o	"+ Tambah Artikel" (berwarna biru, biasanya tombol bootstrap)

d. Tabel Data Artikel:
o	Kolom:
1.	No
2.	Nama Artikel
3.	Isi Artikel
4.	Aksi
o	Data:
	Judul artikel panjang seperti “Perang Iran-Israel: Apakah keterlibatan AS bakal picu Perang Dunia III?”
	Aksi: tombol Edit dan Hapus

<img width="650" alt="Screenshot 2025-07-02 202448" src="https://github.com/user-attachments/assets/9a6e99fd-069f-4d6e-a761-5e0f68b17b65" />

**3. Halaman Kelola Gallery**

a. Fungsi Halaman:
Menampilkan daftar gambar beserta keterangan dan menyediakan fitur edit & hapus galeri foto.

b. Elemen:

Judul Halaman: “Kelola Gallery”

Tabel Galeri:
o	Kolom: No, Foto, Keterangan, Aksi
o	Data contoh:

	Foto 1: “perkemahan se-jawabarat”
	Foto 2: “serah terima jabatan ketua osis”
	Foto 3: “cek hb with bu bidan”

o	Tindakan: Edit dan Hapus

<img width="650" alt="Screenshot 2025-07-02 205139" src="https://github.com/user-attachments/assets/904972ca-36c4-4ac4-825e-f21a50af0272" />

**4. Halaman kelola About**

a. Fungsi Halaman:
Untuk mengatur konten halaman About Me yang akan ditampilkan ke pengunjung.

b. Elemen:
•	Judul Halaman: “Kelola Halaman About”

•	Konten Teks:

o	Berisi paragraf:
"Saya adalah seorang yang menyukai dunia komputer sejak kecil. Dari kecil saya suka mengetik di laptop walaupun hanya mengetik biasa tanpa tahu artinya. Saat ini saya sedang menempuh pendidikan di Fakultas Ilmu Komputer. Walaupun saya tidak terlalu paham dengan dunia coding, saya ingin terus belajar dan mengembangkan diri di bidang ini."

•	Tombol Aksi:

o	Edit dan Hapus

<img width="650" alt="Screenshot 2025-07-02 202606" src="https://github.com/user-attachments/assets/b12c21f1-1420-4875-b74c-719a292bb2ca" />

**5. Halaman Login Administrator**

a. Fungsi Halaman:
Tempat admin melakukan proses login ke dalam sistem admin web.

b. Elemen:

•	Input Form:
o	Username
o	Password

•	Tombol:
o	Login
o	Cancel

•	Pengingat Username:
o	Username yang digunakan adalah "niha"

•	Footer:
o	© 2025 - Nihayatus Sa’adah

<img width="650" alt="Screenshot 2025-07-02 202756" src="https://github.com/user-attachments/assets/3777eae9-9b67-4465-b949-441402195be9" />

**6. Halaman Utama Website**

a. Fungsi Halaman:
Halaman awal yang dilihat pengunjung umum (user) berisi artikel-artikel terbaru.

b. Elemen:

•	Header / Navbar:
o	Link navigasi: Artikel, Gallery, About, Login

•	Konten Artikel Terbaru:
o	Judul: “Di mana posisi Indonesia dalam konflik Iran-Israel?”
o	Isi: Ringkasan isi artikel (paragraf pendek)
o	Disajikan dalam gaya card news

c. Daftar Artikel Lainnya:
o	Ditampilkan secara ringkas, kemungkinan dengan link ke detail artikel.

<img width="650" alt="Screenshot 2025-07-02 202912" src="https://github.com/user-attachments/assets/86065dc0-7c7a-4ca9-8d22-661c034d62e9" />

**7. Halaman About Me (User View) (about.php)**

a. Fungsi Halaman:
Menampilkan informasi pemilik web kepada pengunjung umum.

b. Elemen:

•	Judul: "About Me | Nihayatus Sa’adah"

•	Konten Teks:
o	Paragraf yang sama seperti versi admin:
"Saya adalah seorang yang menyukai dunia komputer sejak kecil..."

•	Desain:
o	Warna utama: dominasi ungu / pastel
o	Tampilan bersih dan rapi

<img width="650" alt="Screenshot 2025-07-02 203656" src="https://github.com/user-attachments/assets/08a949e6-90e7-4b98-8c45-47fc27939e7d" />

**8. Halaman Gallery (User View) (gallery.php)**

a. Fungsi Halaman:
Menampilkan galeri foto kegiatan pribadi pemilik web kepada pengunjung.

b. Elemen:

•	Judul: “Gallery | Nihayatus Sa’adah

<img width="650" alt="Screenshot 2025-07-02 203724" src="https://github.com/user-attachments/assets/0b33024b-7d4d-4fb7-8808-b2bcddbaedcd" />
