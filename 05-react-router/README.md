# React Router
---
## 1.0 - Membuat Router

- Buatlah rute:
  - `/` : Menampilkan komponen `Home`
  - `/login` : Menampilkan komponen `Login`
  - `/register` : Menampilkan komponen `Register`
  - `/profile` : Menampilkan komponen `Profile`
  - `/product` : Menampilkan komponen `Product`
  - Selain rute diatas, tampilkan komponen `NotFound404`
- Buat navigasi untuk menuju rute yg sudah disiapkan
- Pastikan semua rute sudah berjalan dengan baik

---
## 2.0 - Melakukan Register 

- Komponen `Register`, kita dapat mengisi data
  - Nama
  - Email
  - Password
  - Address (textarea)
  - Birthdate
  - Gender (radio - L / P)
  - Skill (checkbox - Coding, Design, Gaming)
- Ketika tombol register ditekan:
  - tampilkan menggunakan alert hasil registrasi yang sudah diketik
  - simpan hasilnya ke dalam locaStorage dengan nama `user`

---
## 3.0 - Melakukan Login 

- Komponen `Login`, kita dapat mengisi data
  - Email
  - Password
- Ketika tombol login ditekan, lakukan pengecekan terhadap data yg terdapat pada localStorage. 
- Jika data yg di input sesuai, tambahkan `isLogin` ke dalam localStorage dengan nilai `true`. kemudian pindah ke halaman `/profile`
- Jika data yg di input salah, munculkan alert `email dan password salah`

---
## 4.0 - Redirect Profile

- Pada komponen `App`, ambil data `isLogin` dari localStorage
- Pada rute `/profile`, jika `isLogin` bernilai `true` maka lanjut ke komponen `Profile`. Jika `false`, arahkan ke rute `login`
- Pastikan rute sudah berjalan dengan baik jika user belum melakukan login
- Sembunyikan navigasi login jika user sudah melakukan login

---
## 5.0 - Data Profile

- Pada komponen `Profile`, Ambil data `user` dari localStorage
- Simpan data tersebut ke dalam sebuah state
- Tampilkan data dari state yg sudah dibuat