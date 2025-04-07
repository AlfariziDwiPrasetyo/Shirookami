---
title: "Perangkat Permodelan Sistem"
date: 2024-01-07
draft: false
description: "PERANGKAT PERMODELAN SISTEM"
slug: "perangkat-permodelan-sistem"
tags: ["Sistem informasi"]
series: ["Sistem Informasi"]
series_order: 9
showAuthor: true
showAuthorsBadges : false
---

## System Procedure Diagram (Flowmap)
Digunakan untuk mendefinisikan hubungan antara bagian (pelaku proses), proses (manual atau berbasis komputer) dan aliran data (dalam bentuk dokumen masukan dan keluaran).

System Procedure Diagram menggunakan simbol-simbol sebagai berikut:
{{< figure src="/flowmap.png" alt="Flowmap" title="flowmap" >}}

## Entity Relational Diagram (ERD) Terinci

Merupakan jaringan yang menggunakan susunan data yang disimpan dari sistem secara abstrak. Tujuan dari Entity Relational ini adalah untuk menunjukkan objek data dan relationship yang ada pada objek tersebut. Di samping itu Model ER ini merupakan salah satu alat untuk perancangan dalam basis data.

1. **Komponen ERD**

Masukan (input) merupakan awal dimulainya proses informasi. Bahan mentah dari informasi adalah data yg terjadi dari transaksi-transaksi yg dilakukan oleh organisasi.. Data hasil dari transaksi merupakan masukan untuk sistem informasi. Dokumen dasar merupakan formulir yang digunakan untuk menangkap (capture) data yang terjadi. 

Data yang sudah dicatat di dokumen dasar kemudian dimasukkan sebagai input ke sistem informasi untuk diolah.

+ Entity : suatu objek yang dapat dibedakan atau dapat diidentifikasikan secara unik dengan objek lainnya.
![entity](https://ahmadmaulana120504.netlify.app/Public/1.png "Entity simbol")

+ Relationship: hubungan yang terjadi antara satu entity dengan entity lainnya.
![relationship](https://ahmadmaulana120504.netlify.app/Public/2.png "Relationship simbol")

+ Atribut : karakteristik dari Entity yang menyediakan penjelasan detail tentang entity tersebut.
![atribute](https://ahmadmaulana120504.netlify.app/Public/3.png "Atribut simbol")

2. **Derajat Relationship**

+ Unary (Derajat satu): satu buah relationship menghubungkan satu buah entity

+ Binary (Derajat Dua): satu buah relationship menghubungkan dua buah entity.

+Ternary (Derajat Tiga): satu buah relationship menghubungkan tiga buah entity

3. **Cardinality Rasio**

Yaitu menjelaskan batasan pada jumlah entity yang berhubungan melalui suatu relationship. Jenis-jenis Cardinality Rasio:
+ One To One (1:1), yaitu perbandingan antara entity pertama dengan entity kedua berbanding satu berbanding satu

+ One To Many (1:M), yaitu perbandingan antara entity pertama dengan entity kedua berbanding satu berbanding banyak.

+ Many To One (M:1), yaitu perbandingan antara entity pertama dengan entity kedua berbanding banyak berbanding satu.

+ Many To Many (M:M), yaitu perbandingan antara entity pertama dengan entity kedua berbanding banyak berbanding banyak

4. **Langkah-Langkah Membuat ERD**

+ Mengidentifikasi dan menetapkan seluruh entity yang terlibat.

+ Menentukan atribut-atribut key dari masing-masing entity

+ Menetapkan relationship antara satu entity dengan entity lainnya beserta foreign-keynya.

+ Menentukan derajat dan cardinality rasio untuk setiap relationship.

+ Melengkapi himpunan relasi dengan atribut-atribut yang bukan kunci (non key).

5. **Contoh Kasus**

+ Suatu perguruan tinggi mempunyai banyak mahasiswa. Setiap mahasiswa biasanya mengikuti beberapa mata kuliah. Setiap mata kuliah diajarkan oleh seorang dosen dan seorang dosen bisa mengajar beberapa mata kuliah. 

    Pada entitas Mahasiswa diperlukan informasi tentang NIM, Nama_Mhs, Alamat_Mhs dan Jurusan sedangkan Mata Kuliah diperlukan informasi Kd_MK, Nm_Mk, SKS, Semester sedangkan Dosen diperlukan juga informasi tentang Kd_Dosen, Nm_Dosen.

+ Suatu klinik memiliki praktek dokter bersama, sehingga dalam klinik tersebut memiliki banyak dokter. Seorang pasien, apabila akan berobat harus diperiksa oleh dokter dan sebaliknya dokter pun harus memeriksa pasien. Setiap selesai diperiksa pasien biasanya menerima resep berupa obat dan biasanya setiap pasien menerima beberapa jenis obat.

    Informasi tentang dokter adalah kode dokter, nama dokter, spesialis dan tarif. Sedangkan informasi tentang pasien adalah nomor pasien, nama pasien dan alamat. Informasi tentang obat adalah kode obat, nama obat, dosis.

## Normalisasi

`Normalisasi` adalah proses pengelompokkan data ke dalam bentuk tabel atau relasi atau file untuk menyatakan entitas dan hubungan mereka sehingga terwujud satu bentuk database yang mudah untuk dimodifikasi.

**Jenis-Jenis Key:**

+ Super Key: merupakan satu atau lebih atribut yang dapat membedakan setiap baris data dalam sebuah tabel secara unik.

+ Candidate Key: merupakan kumpulan atribut minimal yang dapat membedakan setiap baris data dalam sebuah tabel secara unik.

+ Primary Key: memilih sebuah dari Candidate Key, dimana jaminan keunikan key-nya lebih baik.

+ Alternate Key: Candidate Key yang tidak dijadikan primary key


**Langkah-langkah pembentukan Normalisasi**

+ Bentuk Tidak Normal (Unnormalized Form)
Pada bentuk ini merupakan kumpulan data yang tidak ada keharusan mengikuti format tertentu, dapat saja data tidak lengkap atau terduplikasi.

+ Bentuk Normal Satu ( 1 NF)
Yaitu bila relasi tersebut mempunyai nilai data yang atomic, artinya tidak ada lagi kerangkapan data.

+ Bentuk Normal Dua (2 NF)
Yaitu bila relasi tersebut merupakan 1 NF dan setiap atribut tergantung penuh pada primary key.

+ Bentuk Normal Ketiga (3 NF)
Yaitu bila relasi merupakan 2 NF dan tidak bergantung secara transitif pada primary key

## Contoh Flowmap Pada Sistem Poliklinik

{{< figure src="/1.jpg" alt="bagan" title="bagan" >}}
{{< figure src="/2.jpg" alt="bagan" title="bagan" >}}

## Contoh Flowmap Pada Sistem Informasi Akademik
{{< figure src="/3.jpg" alt="bagan" title="bagan" >}}
{{< figure src="/4.jpg" alt="bagan" title="bagan" >}}
