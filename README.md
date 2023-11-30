# Restaurant_Catalouge-PWA
Lanjutan dari proyek aplikasi Restaurant_Catalouge

Fitur yang ada pada aplikasi:
1.	Halaman Utama (Daftar Restoran)
•	Menampilkan daftar restoran yang datanya bersumber dari API: restaurant-api.dicoding.dev. 
•	Menampilkan nama, gambar, dan salah satu di antara kota, rating, dan/atau deskripsi pada restoran.
•	Ada tautan/CTA yang mengarah ke detail restoran pada setiap item-nya.
2.	Halaman Detail Restoran
•	Menampilkan detail dari restoran yang dipilih dari halaman utama (daftar restoran) atau halaman favorit restoran.
•	Pada halaman detail restoran berisi hal-hal berikut.
	Nama restoran
	Gambar
	Alamat
	Kota 
	Deskripsi
	Menu Makanan
	Menu Minuman
	Customer Reviews
•	Ada tombol favorite untuk memasukkan atau menghapus restoran favorit dari database. Penyimpanan ini menggunakan IndexedDB.
3.	Halaman Daftar Restoran Favorit
•	Halaman daftar restoran dapat diakses melalui menu navigasi favorit.
•	Menampilkan restoran yang difavoritkan oleh pengguna (data diambil dari indexedDB).
•	Menampilkan nama, gambar dan salah satu diantara kota, rating, dan atau deskripsi pada restoran.
•	Ada tautan/CTA yang mengarah ke detail restoran pada tiap itemnya.
4.	Native Capability
•	Aplikasi dapat diakses dalam keadaan offline tanpa ada aset yang gagal dimuat, termasuk data yang didapatkan dari API. Menggunakan  workbox.
•	Aplikasi menampilkan icon Add to Home Screen.
•	Aplikasi memiliki custom icon yang ditampilkan pada home screen dan splash screen.
5.	Code Quality
•	Menggunakan ESLint sebagai linter ketika menuliskan kode JavaScript. 
•	Perapkan salah satu style guide, baik Google JavaScript Code Style, AirBnB JavaScript Code Style, atau StandardJS Code Style.
