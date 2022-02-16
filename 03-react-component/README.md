# React

Latihan di bawah ini saling terhubung

---

## v1.0 - Component

Ambil html dari template

- Buat project react baru
- gunakan template html yg sudah disediakan pada repo ini, lalu paste ke dalam `App.js` project react mu
- Ubah semua atribut `class` menjadi `className`
- Jalankan aplikasi react, dan pastikan sudah berjalan

---

## v2.0 - Component

Refactor template menjadi react compoent

- Buat komponen `Profile.js`, `Hobbies.js`, `Skills.js` di dalam folder `components`
- Pindahkan element yg memiliki id `profile` ke dalam komponen `Profile.js`
- Pindahkan element yg memiliki id `hobbies` ke dalam komponen `Hobbies.js`
- Pindahkan element yg memiliki id `skilss` ke dalam komponen `Skills.js`
- Di dalam `App.js`, panggil `<Profile />`, `<Hobbies />`, dan `<Skills />`
- Setelah dijalankan, hasil tidak berubah karena hanya memindahkan element menjadi komponen

---

## v3.0 - Map

Buat data array untuk Hobbies dan Skills

- Di dalam `Hobbies.js`, buat state array of object yang bernama `hobbies` berisikan nama hobi dan gambarnya. contoh
  ```js
    [
      {name: "nonton", img: "alamat gambar"},
      <!-- dan seterusnya -->
    ]
  ```
  - Hapus semua element yang memiliki className `hobby-item`, dan sisakan 1 element saja.
  - `map` data `hobbies` lalu tampilkan gambar dan nama hobby pada sebuah element yg memiliki className `hobby-item`
- Di dalam `Skills.js`, buat state array of object yang bernama `skills` berisikan nama skill dan gambarnya, contoh
  ```js
    [
      {name: "ngoding", img: "alamat gambar"},
      <!-- dan seterusnya -->
    ]
  ```
  - Hapus semua element yang memiliki className `skill-item`, dan sisakan 1 element saja.
  - `map` data `skills` lalu tampilkan gambar dan nama skill pada sebuah element yg memiliki className `skill-item`

---

## v4.0 - Props

- Buat komponen baru `HobbyItem.js` yg dapat menerima props `hobby`
- Pindahkan element yang memiliki id `hobby-item` ke dalam komponen `HobbyItem.js`
- Panggil `<HobbItem />` di dalam map, lalu kirimkan props `hobby` kedalamnya
- Buat komponen baru `SkillItem.js` yg dapat menerima props `skill`
- Pindahkan element yang memiliki id `skill-item` ke dalam komponen `SkillItem.js`
- Panggil `<SkillItem />` di dalam map, lalu kirimkan props `skill` kedalamnya

---

## v5.0 - onClick

- Di dalam `HobbyItem.js`, beri `onClick` pada elemen yang memiliki className `hobby-item`. Ketika di klik, tampilkan `alert()` yg berisi nama hobby
- Di dalam `SkillItem.js`, beri `onClick` pada elemen yang memiliki className `skill-item`. Ketika di klik, tampilkan `alert()` yg berisi nama skill
