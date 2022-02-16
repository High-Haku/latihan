# Form

---
## v1.0 - Membuat form

Membuat form Login

- Buat sebuah komponen `Login`
- `Login` memiliki state:
  - `username` (string)
  - `password` (string)
- `Login` Menampilkan:
  - `text input` username
  - `text input` password
  - `button` login
- Pada `text input` username, beri atribut 
  - `onChange` yg menjalankan function `handleChangeUsername` untuk mengubah state `username`
  - `value` bernilai state `username`
- Pada `text input` password, beri atribut
  - `onChange` yg menjalankan function `handleChangePassword` untuk mengubah state `password`
  - `value` bernilai state `password`
- Pada `button` login, beri click untuk munculkan data username dan password pada console

---
## v2.0 - Refactor Login

Pada **v1.0**, **_bagaimana jika terdapat banyak text input? berarti kita harus membuat function untuk masing-masing text input dong??_**

kita akan merapikan supaya lebih efisien

- Buat komponen baru bernama `Login2`
- `Login2` Menampilkan:
  - `text input` username
  - `text input` password
  - `button` login
- `Login2` memiliki state:
  - `user` (_objek_) yg memiliki properti **username** dan **password**
- Pada `text input` **username** dan **password**, beri atribut:
    - `onChange`, menjalankan function `handleChangeInput`
    - `name`, sesuai dengan nama properti pada state `user`
    - `value`, bernilai properti dari state `user`
  - Pada `handleChangeInput`, ubah state `user` dengan memberikan object baru
    ```js
    {
      // ambil isi object yg sekarang
      ...user,

      // ubah properti pada user berdasrakan text input yg aktif
      [event.target.name]: event.target.value
    }
    ```
- Pada `button` login, tampilkan data user di console


