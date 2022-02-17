# React useEffect

---

Buat project react baru

## 1.0 - Mengambil data
- Buat komponen `CatList`
- siapkan state `cats` dan `catsTemp`
- Gunakan `useEffect()` yg berjalan 1x saja untuk mengambil data dari API, lalu masukkan data yg sudah didapatkan ke dalam `cats` dan `catsTemp`
  ```
  API -> https://api.thecatapi.com/v1/breeds
  ```
- Lakukan map pada state `cats`, lalu tampilkan:
  - gambar
  - nama kucing
  - origin

---
## 2.0 - Mencari Data

- Di dalam komponen `CatList`, tambahkan `input text` untuk melakukan pencarian data kucing.
- `input text` memiliki atribut `onChange` untuk menyimpan hasil ketikan ke dalam state `inputSearch` 
- Buat `useEffect()` baru, di dalamnya lakukan filter pada state `catsTemp`, lalu lakukan pengecekan satu per satu apakah data yg dicek mengandung kata yg berasal dari state `inputSearch`.
- Hasil dari filter akan disimpan pada state `cats`
- tambahkan `[input]` sebelum penutup kurung `useEffect()` yg baru saja dibuat

---
## 3.0 - Refactor Component

- Buat komponen baru bernama `CatItem`
- Pada komponen `CatList`, pindahkan element yang ada di dalam map ke komponen `CatItem`.
- Lalu panggil `CatItem` di dalam map dengan menerima props data kucing
- sesuaikan data yang digunakan pada `CatItem` sehingga data kucing kembali muncul di browser

---
## 4.0 - Click Item

- Di dalam `CatItem`, beri `onClick` pada element yg di return.
- `onClick` tersebut menjalankan `handleClick`
- `handleClick` berisikan alern yang menampilkan nama kucing

---
## 5.0 - Styling

- Lakukan styling menggunakan CSS atau bootstrap

---
## 6.0 - Deploy

- Buat file `_redirects` di dalam folder `public`
- isi `_redirects` dengan `/* /index.html 200`
- Lalu deploy ke netlify