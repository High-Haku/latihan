# React Context

---
## 1.0 - Routing

- Buatlah rute:
  - `/` : Menampilkan komponen `Home` (di dalamnya terdapat komponen `Cats`)
  - `/login` : Menampilkan komponen `Login`
  - `/cat/:namaKucing` : Menampilkan komponen `CatDetail`
  - Selain rute diatas, tampilkan komponen `NotFound404`

---

## 2.0 - Cats

- Buat `CatContext` yg memiliki state `cats`
- Pada komponen `Cats`, ambil data pada API ini
  ```
  https://api.thecatapi.com/v1/breeds
  ```
- Simpan hasil data yg sudah di dapatkan ke dalam `cats` milik `CatContext`, lalu tampilkan datanya
- Setiap data kucing dapat di klik. Ketika di klik, ambil nama kucing lalu ubah url menggunakan `history` menjadi `/cat/{namaKucing}`

---

## 3.0 - Cat Detail

- Pada komponen `CatDetail`, ambil parameter nama kucing dari url lalu ambil data dari api berikut
  ```
  https://api.thecatapi.com/v1/breeds/search?q={namaKucing}
  ```
- Simpan hasil data yg sudah di dapatkan ke dalam state `cat`
- Lalu tampilkan datanya

---

## 4.0 - Login

- Buat `UserContext` yg memiliki state `isLogin`
- Buat data user pada `mockapi.io`
- Jika data yg di input sesuai dengan data pada `mockapi.io`
  - buat data `isLogin` dgn nilai `true` ke dalam `localStorage`
  - ubah `isLogin` milik `UserContext` menjadi `true`
  - pindah ke rute `/`
- Pada `App.js`, ambil `isLogin` dari `UserContext`.
- Gunakan `isLogin` untuk:
  - Munculkan navigasi logout jika `isLogin` bernilai `true`. 
  - Mengalihkan rute `/` ke rute `/login` jika `isLogin` `false`
  - Mengalihkan rute `/login` ke rute `/` jika `isLogin` `true`
- Navigasi logout bertugas mengubah `isLogin` pada `UserContext` dan `localStorage` menjadi `false`
- pada `UserContext`, di dalamnya tambahkan `useEffect` untuk mengambil data `isLogin` dari `localStorage` lalu masukkan isinya ke dalam state `isLogin`.

---


