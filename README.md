Nama : ananda Friezy Eka Cahya
NIM: 312410151
KElas: TI24A1

# Praktikum Pemrograman Web - Lab2Web

## Langkah-langkah Praktikum

### 1. Membuat Repository

* Repository baru dengan nama **Lab2Web**.

### 2. Membuat Struktur HTML Dasar

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style_eksternal.css" type="text/css">
    <meta charset="UTF-8">
    <title>CSS Dasar</title>
    <style>
        body { font-family: 'Open Sans', sans-serif; }
        h1 { font-size: 24px; color: #0F189F; text-align: center; }
    </style>
</head>
<body>
    <header>
        <h1>CSS Internal <i>Inline</i></h1>
    </header>
</body>
</html>
```

### 3. Menambahkan Internal CSS

* Mengubah properti pada elemen `<h1>` seperti ukuran font, warna, dan text-align.

### 4. Menambahkan Inline CSS

```html
<p style="text-align:center; color:#ccd8e4;">Contoh paragraf dengan inline CSS</p>
```

### 5. Menambahkan Eksternal CSS

* Membuat file `style_eksternal.css`:

```css
nav a {
    color: blue;
    padding: 5px;
    text-decoration: none;
}
```

### 6. Percobaan Spesifisitas

* Selector `h1 {}` vs `#intro h1 {}` untuk membedakan efek CSS.
* Membandingkan Inline, Internal, dan Eksternal CSS.
* Membandingkan penggunaan `id` dan `class`.

## Screenshots

<img width="785" height="442" alt="image" src="https://github.com/user-attachments/assets/e33506bf-21bd-4256-b35f-ced18b3ff5ea" />

<img width="1552" height="556" alt="image" src="https://github.com/user-attachments/assets/b8be5c4e-bcf2-406f-aa93-44cdd2a99ab2" />


## Kesimpulan

* Inline CSS memiliki prioritas paling tinggi.
* ID selector lebih spesifik dibanding class.
* `#intro h1 {}` hanya berlaku pada elemen tertentu di dalam ID `intro`, sedangkan `h1 {}` berlaku global.
* Penggunaan eksternal CSS lebih baik untuk pemeliharaan kode.
