# Latihan Object

## Exercise 1
Buatlah sebuah object hewan yang berisikan:
```
ciri-ciri (property) :
  nama: String
  kaki: Number
  warna: Array
  spesies: String (mamalia/unggas/dll)
  makanan: Array
keahliannya (method) :
  terbang / loncat / berburu / dll
```

Tampilkan dengan console.log seperti ini, Contoh :
```
Ini adalah hewan Kucing
Memiliki 4 kaki
Spesiesnya Mamalia
Kucing ini berwarna oren, putih, item
Makanan kesukaannya Ikan dan Ayam
Suaranya Miaaaaw
```
---

## Exercise 2
Terdapat sebuah data:
```js
const data = 
[
  {
    name: ‘Alpha’,
    class: ‘Dragon’,
    club: ['Bola', 'Bulutangkis']
  },
  {
    name: Beta,
    class: ‘Lizard’,
    club: ['Membaca', 'Bulutangkis']
  },
]
```

Tampilkan dengan console.log seperti ini :
```
Alpha ada di kelas Dragon, dia mengikuti club Bola, Bulutangkis
Beta ada di kelas Lizard, dia mengikuti club Membaca, Bulutangkis
```
---

## Exercise 3
Terdapat sebuah data:
```js
let todos = [
  {id: 3, todo: "belajar coding"},
  {id: 7, todo: "nanti tidur"}
]
```

Buatlah sebuah perintah CRUD sehingga menjadi seperti ini:
```js
printAll()
// hasil:
// 3, "belajar coding"
// 7, "nanti tidur"

printByID(id)
// hasil
// 3, "belajar coding"

add(newTodo)
// hasil
// 3, "belajar coding"
// 7, "nanti tidur"
// 8, "ngerjain tugas"

deleteByID(id)
// hasil
// 3, "belajar coding"
// 8, "ngerjain tugas"

updateByID(id, newTodo)
// hasil
// 3, "belajar CRUD"
// 8, "ngerjain tugas"
```