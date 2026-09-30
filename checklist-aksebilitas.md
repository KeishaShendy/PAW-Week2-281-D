Checklist pemeriksaan dan perbaikan pada halaman HTML.

1.Struktur HTML5 minimum lengkap
  - Memastikan terdapat `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`.

2.Elemen semantik digunakan tepat
  - Menggunakan `<header>`, `<nav>`, `<section>`, dan `<form>`.

3.Form memiliki label, id, name, dan required bila perlu
  - Menambahkan `required` pada input nama karena wajib diisi.
  - Memastikan `label` terhubung dengan `input` melalui `for` dan `id`.

4.Radio/checkbox dikelompokkan dengan fieldset dan legend
  - Menggunakan `<fieldset>` dan `<legend>`.
  - Memperbaiki `name` radio button agar sama (`jenis_kelamin`) sehingga hanya satu pilihan yang dapat dipilih.

5.Heading berurutan dan halaman memiliki title
  - Memperbaiki heading dari `<h3>` menjadi `<h2>`.
  - Memperbaiki tag penutup heading dari `</h2>` agar sesuai.
  - Memastikan halaman memiliki `<title>`.

6.Setiap gambar bermakna memiliki alt text
  - Memastikan gambar memiliki atribut `alt="Kucing oyen"`.