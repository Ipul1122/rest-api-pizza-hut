# Pizza Menu

Proyek ini adalah aplikasi web sederhana untuk menampilkan menu pizza menggunakan HTML, PHP, dan JavaScript. Data menu disimpan dalam file JSON dan ditampilkan di halaman web menggunakan Bootstrap untuk styling.

## Struktur Proyek

- data untuk menyimpan key:value json
- img
- js
- latihan1.php untuk menggunakan program php
- latihan2.html untuk menggunakan program html, boostrap dan javascript

## File Deskripsi

- `data/pizza.json`: File JSON yang berisi data menu pizza.
- `img/`: Folder yang berisi gambar-gambar untuk menu pizza.
- `js/script.js`: File JavaScript yang berisi logika untuk menampilkan menu pizza.
- `latihan1.php`: Halaman PHP yang menampilkan menu pizza menggunakan PHP.
- `latihan2.html`: Halaman HTML yang menampilkan menu pizza menggunakan JavaScript.

## Cara Menjalankan

1. Clone repositori ini ke direktori server lokal Anda (misalnya, `htdocs` untuk XAMPP).
2. Pastikan server lokal Anda berjalan (misalnya, Apache untuk XAMPP).
3. Buka `latihan1.php` atau `latihan2.html` di browser Anda untuk melihat aplikasi.

## Dependencies

- [Bootstrap](https://getbootstrap.com/) untuk styling.
- [jQuery](https://jquery.com/) untuk manipulasi DOM dan AJAX.

## Contoh Data JSON

```json
{
    "menu": [
        {
            "kategori": "pizza",
            "nama": "Meat Lover",
            "deskripsi": "Irisan sosis sapi, daging sapi cincang, burger sapi, sosis ayam.",
            "harga": 49500,
            "gambar": "meat-lover.jpg"
        },
        {
            "kategori": "pizza",
            "nama": "Super Supreme",
            "deskripsi": "Daging ayam dan sapi asap, daging sapi cincang, burger sapi, jamur, paprika merah dan paprika hijau.",
            "harga": 49500,
            "gambar": "supreme.jpg"
        }
    ]
}

## Inspirasi
- const youtube = Sandika Galih
- const link = https://www.youtube.com/watch?v=UNjknizL2EI&list=PLFIM0718LjIW7AsIbnhFg15t9yx4H-sQ0&index=5
console.log(`${youtube}: ${link}`)
