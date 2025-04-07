---
title: "Desain Sistem Secara Terinci"
date: 2024-01-06
draft: false
description: "DESAIN SISTEM SECARA TERINCI"
slug: "desain-sistem-secara-terinci"
tags: ["Sistem informasi"]
series: ["Sistem Informasi"]
series_order: 8
showAuthor: true
showAuthorsBadges : false
---

## Definisi Manfaat Desain SIstem Secara Terinci
Tujuan desain sistem terinci adalah untuk memberikan gambaran yang jelas dan rancang bangun yang lengkap kepada pemrogram komputer dan ahli teknik lainnya yang akan membangun sistem informasi. Desain sistem terinci merupakan tahap desain sistem yang mempunyai dua maksud atau tujuan utama, yaitu untuk memenuhi kebutuhan kepada pemakai sistem dan untuk memberikan gambaran yang jelas dan rancang bangun yang lengkap kepada pemrogram komputer dan ahli teknik lainnya yang akan membangun sistem informasi

## Komponen-komponen yang terdapat di dalam Desain Sistem Terinci

1. **Desain Input Terinci**

Masukan (input) merupakan awal dimulainya proses informasi. Bahan mentah dari informasi adalah data yg terjadi dari transaksi-transaksi yg dilakukan oleh organisasi.. Data hasil dari transaksi merupakan masukan untuk sistem informasi. Dokumen dasar merupakan formulir yang digunakan untuk menangkap (capture) data yang terjadi. Data yang sudah dicatat di dokumen dasar kemudian dimasukkan sebagai input ke sistem informasi untuk diolah.
Mengatur Tataletak Isi Input

Tujuannya

+ Bagi pemakai sistem digunakan untuk menilai isi dan bentuk dari input apakah sudah sesuai dengan yang diinginkan atau belum.

+ Bagi programmer akan digunakan sebagai dasar pembuatan program untuk menghasilkan input yang diinginkan. Programmer membutuhkan desain input ini untuk menentukan posisi kolom, baris dan informasi yang harus disajikan di suatu input.

2. **Desain Output Terinci**

Pada tahap desain output secara umum, desain output ini hanya dimaksudkan untuk menentukan kebutuhan output dari sistem baru. Output apa saja yang dibutuhkan untuk sistem yang baru? Desain output secara umum dimaksudkan untuk menjawab pertanyaan ini. Bagaimana dan seperti apa bentuk dari output-output tersebut? Desain output terinci dimaksudkan untuk menjawab pertanyaan ini. Desain output yang akan dibahas pada bab ini adalah untuk output berbentuk laporan di media keras seperti kertas. Desain output di media lunak dalam bentuk dialog di layar terminal akan dibahas selanjutnya

**Bentuk Laporan**

Bentuk dari laporan yang dihasilkan oleh sistem informasi, yang paling banyak digunakan adalah dalam bentuk tabel dan berbentuk grafik atau bagan

**Mengatur Tata Letak Isi Output**

Pengaturan isi dari output akan secara langsung menentukan kemudahan dari output untuk dipahami dan dimengerti. Pengaturan tata letak output merupakan pekerjaan desain yang penting dan sangat diperlukan baik bagi pemakai sistem maupun bagi programmer. Bagi pemakai sistem digunakan untuk menilai isi dan bentuk dari output apakah sudah sesuai dengan yang diinginkan atau belum.

Bagi programmer akan digunakan sebagai dasar pembuatan program untuk menghasilkan output yang diinginkan. Programmer membutuhkan desain output ini untuk menentukan posisi kolom, baris dan informasi yang harus disajikan di suatu output. Pengaturan tata letak isi output yg akan dicetak di printer dapat digunakan alat bagan tata letak printer (printer layout chart) dan kamus data output.

3. **Desain Dialog Layar Terminal**

Merupakan rancang bangun dari percakapan antara pemakai sistem (user) dengan komputer. Percakapan ini dapat terdiri dari proses memasukkan data ke sistem, menampilkan output informasi kepada user atau dapat keduanya.
Terdapat beberapa strategi membuat dialog layar komputer:

+ **MENU**. Banyak digunakan dalam dialog karena merupakan jalur pemakai (user interface) yang mudah dipahami dan mudah digunakan. Menu berisi dengan beberapa alternatif atau option atau pilihan yang disajikan kepada user. User dapat memilih pilihan di menu dengan cara menekan tombol angka atau huruf yang dihubungkan dengan pilihan tersebut.

+ **Kumpulan Instruksi (Instruction Set)**. Strategi dialog ini dilakukan dengan menuliskan suatu instruksi oleh user dan sistem akan mengartikan instruksi ini serta memberikan respon jawaban.

+ **Dialog Pertanyaan/Jawaban (Question/Answer Dialog)**. Sistem akan menampilkan terlebih dahulu pertanyaan dan user menjawabnya untuk mendapatkan respon lebih lanjut dari sistem.

4. **Desain Database Terinci**

Di tahap desain secara umum sebelumnya, desain database hanya dimaksudkan untuk mengidentifikasikan kebutuhan file-file database yang diperlukan oleh sistem informasi saja. Pada tahap desain terinci ini, desain database dimaksudkan untuk mendefiniskan isi atau struktur dari tiap-tiap file yang telah diidentifikasikan di desain secara umum.

Elemen-elemen data di suatu file database harus dapat digunakan untuk pembuatan suatu output. Demikian juga dengan input yang akan direkamkan di database, file-file database harus mempunyai elemen-elemen untuk menampung input yang dimasukkan. Untuk dapat merancang database terinci digunakan teknik `normalisasi`.

5. **Desain Teknologi Terinci**

Pada desain teknologi secara umum telah ditentukan jenis dan jumlah dari teknologi yang akan digunakan. Yang belum didefinisikan secara pasti pada tahap ini adalah kapasitas dari teknologi simpanan luar yang akan digunakan. Kapasitas simpanan luar yang telah didefinisikan pada tahap desain secara umum hanya ditaksir secara kira-kira terlebih dahulu berdasarkan pengalaman analis sistem.

Setelah file-file database berhasil didesain secara rinci, kebutuhan kapasitas simpanan luar sekarang dapat dihitung dengan lebih tepat. Besarnya kapasitas simpanan luar yg dibutuhkan oleh sistem informasi dapat dihitung berdasarkan besarnya file-file database yg akan menyimpan data untuk satu periode tertentu.