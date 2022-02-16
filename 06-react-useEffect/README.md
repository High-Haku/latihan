# React useEffect

---
## 1.0 - Mengambil data
- Buat komponen `CatList`
- siapkan state `cats` dan `catsTemp`
- Gunakan `useEffect()` yg bejalan 1x saja untuk mengambil data dari API, lalu masukkan data yg sudah didapatkan ke dalam `cats` dan `catsTemp`
  ```
  API -> https://api.thecatapi.com/v1/breeds
  ```
- Tampilkan data kucing yg berasal dari state `cats`

---
## 2.0 - Mencari Data

- Di dalam komponen `CatList`, tambahkan input text untuk melakukan pencarian data kucing. 
- Hasil ketikan dari input text akan disimpan pada state `input` 
- Buat `useEffect()` baru, di dalamnya lakukan filter pada state `catsTemp` lalu lakukan pengecekan apakah data yg dicek mengandung kata yg berasal dari state `input`.
- Hasil dari filter akan disimpan pada state `cats`
- tambahkan `[input]` sebelum penutup kurung `useEffect()` yg baru saja dibuat
- Amati hasilnya dan ceritakan kembali proses yg sudah dibuat sehingga dapat melakukan data pencarian pada data kucing (buat pada file `penjelasan.md`) 


