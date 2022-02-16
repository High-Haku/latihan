# Array

Dikerjakan **tidak boleh menggunakan build-in function** seperti `forEach, map, filter, dll`. 

Jika sudah berhasil, boleh menggunakan build-in function yg tertera pada note

---
## Reverse Array

**ketentuan** :
- membalikkan sebuah array
- Buat fungsi yang menerima parameter data `array`
- kembalikan dalam bentuk `array` 

**Contoh**
```
[1,4,6,7] -> return [7,6,4,1]
[7,4,2,1] -> return [1,2,4,7]
[5] -> return [5]
```
---

## Sum Array

**Ketentuan**:
- menghitung total nilai yang terdapat pada sebuah array
- Buat fungsi yang menerima parameter data `array`
- kembalikan dalam bentuk `number`

**Contoh** :
```
[8,3,9,2,5] -> return 27
[1,1,1,1,1] -> return 5
[0,0,0] -> return 0
[5,7] -> return 12
[8] -> return 8
```

**Note**: bisa pakai `reducer()` 

---

## Linear Search

**Ketentuan**:
- Mencari data pada array
- Buat fungsi yang menerima parameter `angka` yg ingin dicari dan data `array`
- Kembalikan dalam bentuk `number`
- Kembalikan `undefined` jika tidak dikembalikan

**Contoh** :
```
cari 3 : 
[8 ,3 ,9 ,2 ,5] -> return 3

cari 4 :
[2 ,6 ,7 ,4 ,1] -> return 4

cari 9 :
[2 ,6 ,7 ,5 ,1] -> return undefined
```

Note: bisa pakai `find()` 

---

## Fizz Buzz Array

**Ketentuan**:
- Mencari mengubah angka fizz buzz
- Buat fungsi yang menerima parameter data `array`
- Kembalikan dalam bentuk `boolean`

**Contoh** :
```
[8 ,3 ,9 ,2 ,5] -> return [8 ,"fizz" ,"fizz" ,2 ,"buzz"]
[3 ,4 ,6 ,7 ,9] -> return ["fizz" ,4 ,"fizz" ,7 ,"fizz"]
[4 ,5 ,9 ,15 ,19] -> return [4 ,"buzz" ,"fizz" ,"fizz buzz" , 19]
[2 ,4 ,7 ,8 ,1] -> return [2 ,4 ,7 ,8 ,1]
```
Note: bisa pakai `map()` 

---

## Get 3&5 Number

**Ketentuan**:
- Mengambil angka kelipatan 3 dan 5
- Buat fungsi yang menerima parameter data `array`
- Kembalikan dalam bentuk `array`
- Kembalikan `null` jika tidak ditemukan

**Contoh** :
```
[8 ,3 ,9 ,2 ,5] -> return [3 ,9]
[3 ,4 ,6 ,7 ,9] -> return [3 ,6 ,9]
[4 ,5 ,9 ,15 ,19] -> return [5 ,9 ,15] 
[2 ,4 ,7 ,8 ,1] -> return null
```
Note: bisa pakai `filter()` 

---


## Palindrome

**Ketentuan**:
- Mengecek sebuah string yang memiliki makna sama jika dibalik
- Buat fungsi yang menerima parameter `string`
- Kembalikan dalam bentuk `boolean`

**Contoh** :
```
Hallo -> ollaH -> retun False
apa -> apa -> return True
oppa -> oppa -> return True
katak -> katak -> return True
rusak -> kasur -> return False
```
---

## Max and Min

**Ketentuan**:
- Mendapatkan nilai max dan min pada sebuah array
- Buat fungsi yang menerima parameter `angka` yg ingin dicari dan data `array`
- Kembalikan dalam bentuk `object`

**Contoh** :
```
[8, 3, 9, 4 ,5]
Max : 9
Min : 3

[5, 5, 5, 5, 5]
Max : 5
Min : 5
```
Note: bisa pakai `Math.max()` dan `Math.min()`

---

## Get 2D array

**Ketentuan**:
- menghitung total nilai yang terdapat pada sebuah array
- Buat fungsi yang menerima parameter data `array`
- Tampilkan dengan console.log

**Contoh** :
```
[ 
  ["topi", 3], 
  ["kaos", 6], 
  ["jeans", 4], 
]

jumlah topi ada 3
jumlah kaos ada 6
jumlah jeans ada 4
```
Note: bisa pakai `forEach()`

---

## Sum 2D array

**Ketentuan**:
- menghitung total nilai yang terdapat pada sebuah array
- Buat fungsi yang menerima parameter data `array`
- kembalikan dalam bentuk `number`

**Contoh** :
```
[ [1,2,3], [4,5,6], [7,8,9] ] -> return 45

[ [1,2], [4,5,6] ] -> return 18

[ [1,2,3,4,5] ] -> return 15
```
---

## Max Min 2D array

**Ketentuan**:
- menghitung total nilai yang terdapat pada sebuah array
- Buat fungsi yang menerima parameter data `array`
- kembalikan dalam bentuk `array`

**Contoh** :
```
[ [1,2,3], [6,4,5], [7,9,8] ] -> return [ 3, 6, 9 ]

[ [1,2], [4,5,6] ] -> return [ 2, 6 ]

[ [4,2,5,1,3] ] -> return [ 5 ]
```
---
