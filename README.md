# Data Siswa

Ini adalah proyek "Data Siswa" yang dibuat berdasarkan tutorial dari channel YouTube Dea Afrizal. Proyek ini bertujuan untuk mempelajari bagaimana membangun aplikasi CRUD sederhana menggunakan Node.js, Express, dan MySQL.

## Fitur

- Menampilkan daftar siswa
- Menambahkan siswa baru
- Mengedit informasi siswa
- Menghapus siswa

## Instalasi

1. Clone repositori ini ke dalam direktori lokal Anda:

```bash
git clone https://github.com/username/data-siswa.git
```

2. Masuk ke direktori proyek:

```bash
cd data-siswa
```

3. Install dependensi yang diperlukan:

```bash
npm install
```

4. Konfigurasi Database:

- Buka file `server.js`
- Ubah pengaturan koneksi database sesuai dengan konfigurasi MySQL Anda:

```javascript
const db = mysql.createConnection({
    host: 'localhost',
    database: 'nama_database',
    user: 'username',
    password: 'password'
})
```

5. Jalankan aplikasi:

```bash
node server.js
```

6. Akses aplikasi melalui browser:

Buka browser dan kunjungi `http://localhost:8000`

## Kontribusi

Kontribusi dan perbaikan pada proyek ini sangat diterima. Jika Anda menemukan masalah atau memiliki saran perbaikan, silakan buat *issue* atau kirim *pull request*.

## Sumber Tutorial

Proyek ini dibangun berdasarkan tutorial dari channel YouTube Dea Afrizal. Anda dapat menonton tutorialnya di sini: [Link ke tutorial YouTube](https://youtu.be/JmwDuKzbkNA)

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).
