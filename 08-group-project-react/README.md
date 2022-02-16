# Project React

Ini adalah tugas akhir kelompok setelah mempelajari materi tentang React. Tugas ini bersifat Project, dikerjakan berkelompok.

Project ini **harus** dikerjakan menggunakan React.js

### Objective:

- Mengetahui level pemahaman peserta
- Melatih peserta dalam kerja sama tim
- Memfasilitasi peserta membuat sebuah web portfolio

### Kriteria
- Terdapat halaman
  - Register
  - Login
  - List Movie
  - List Tv Serries
  - Detail Movie & Tv Serries
- Jika belum login, hanya boleh ke halaman Register dan Login saja
- Ketika salah satu movie di klik, maka pindah ke halaman Detail Movie
- Diberi styling & harus responsiv
- Menggunakan react-router-dom sebagai routing
- Menggunakan context sebagai state management

**Note:** 
Kamu bebas untuk menambahkan Halaman lain atau Fitur lainnya sekreatif mungkin

### API yg digunakan
- Movie Now Playing : 
  `https://api.themoviedb.org/3/movie/now_playing?api_key=<<api_key>>&language=en-US&page=1`
- Detail Movie :
  `https://api.themoviedb.org/3/movie/{movie_id}?api_key=<<api_key>>&language=en-US`
- Tv Serries : 
  `https://api.themoviedb.org/3/tv/on_the_air?api_key=<<api_key>>&language=en-US&page=1`
- Detail Tv :
  `https://api.themoviedb.org/3/tv/{tv_id}?api_key=<<api_key>>&language=en-US`
- Register dan Login : `mockapi.io`

### Link Image
- `https://image.tmdb.org/t/p/w500/<<img_movie>>.png`