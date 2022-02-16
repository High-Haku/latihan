# Express

## MRC CRUD

Buatlah sebuah API dengan beberapa endpoint
- /user
- /book

endpoint di atas dapat melakukan
- Mendapatkan semua data
- Mendapatkan data berdasarkan id
- Menambahkan data
- Menghapus data berdasarkan id
- Mengedit data berdasarkan id

Tambahkan middleware ketika sedang menghapus dan mengedit data. Di middleware tambahkan kode ini
```js
console.log(req.method, req.originalUrl)
```