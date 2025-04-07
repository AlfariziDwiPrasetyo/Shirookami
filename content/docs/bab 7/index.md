---
title: "Desain Sistem Secara Umum"
date: 2024-01-04
draft: false
description: "DESAIN SISTEM SECARA UMUM"
slug: "desain-sistem-secara-umum"
tags: ["Sistem informasi"]
series: ["Sistem Informasi"]
series_order: 7
showAuthor: true
showAuthorsBadges : false
---

## Definisi Desain Model Secara Umum
Sistem analis dapat mendesain model dari sistem informasi yang diusulkan dalam bentuk Physical System & Logical Model. Bentuk Physical System dapat digambarkan dengan system flowchart. Dan Logical Model dapat digambarkan dengan Data Flow Diagram (DFD).

## Data Flow Diagram

Data Flow Diagram digunakan untuk menggambarkan suatu sistem yang telah ada atau sistem baru yang akan dikembangkan secara logika.

**Simbol yang digunakan dalam Data Flow Diagram**
+ External Entity (Kesatuan Luar)

+ Data Flow (Arus Data)

+ Process (Proses)

+ Data Store (Simpanan Data)

![atribute](https://123projectlab.com/wp-content/uploads/2020/01/DFD-Symbol1.jpg)


1. **External Entity (Kesatuan Luar)**

Kesatuan luar merupakan kesatuan (entity) di lingkungan luar sistem yang dapat berupa orang, organisasi, atau sistem lainnya yang berada di lingkungan luarnya yang akan memberikan input atau menerima output dari sistem. Kesatuan luar dapat berupa:
+ a. Suatu kantor, departemen, atau divisi dlm perusahaan

+ b. Orang atau sekelompok orang di organisasi tsb

+ c. Suatu organisasi atau orang yg berada di luar organisasi seperti misalnya langganan, pemasok

+ d. Penerima akhir dari suatu laporan yang dihasilkan oleh sistem

Simbol: kesatuan luar dapat digambarkan dengan suatu notasi kotak.

2. **Data Flow (Arus Data)**

Arus data mengalir diantara proses, simpanan data dan kesatuan luar. Arus data ini menunjukkan arus dari data yang dapat berupa masukan untuk sistem atau hasil dari proses sistem dan dapat berbentuk sbb:
+ a. Formulir atau dokumen yang digunakan di perusahaan

+ b. Laporan tercetak yang dihasilkan oleh sistem

+ c. Masukan data untuk komputer

+ d. Data yang dibaca atau direkamkan ke suatu file

+ e. Suatu isian yang dicatat pada buku agenda

Simbol: Arus data dpt digbrkan dengan suatu panah.

3. **Process (Proses)**

Suatu proses adalah kegiatan atau kerja yang dilakukan oleh orang, mesin atau komputer dari hasil suatu arus data yang masuk ke dalam proses untuk dihasilkan arus data yang akan keluar dari proses.

Simbol: Lingkaran.

4. **Data Store (Simpanan Data)**

Simpanan data merupakan simpanan dari data yang dapat berupa:
+ a. Suatu file atau database di sistem komputer

+ b. Suatu arsip atau catatan manual

+ c. Suatu tabel acuan manual

+ d. Suatu agenda atau buku




## Bentuk Data Flow Diagram

Terdapat 2 bentuk Data Flow Diagram yaitu Physical Data Flow Diagram (Diag. Arus Dt Fisik) dan Logical Data Flow Diagram (Diag. Arus Dt Logika). Data Flow Diagram Fisik lebih tepat digunakan untuk menggambarkan sistem yang ada (sistem lama) dan lebih menekankan pada bagaimana proses dari sistem yang diterapkan. Sedangkan diagram arus data logika digunakan utk menggambarkan sistem yang akan diusulkan dan lebih menekankan proses-proses apa yang terdapat dalam sistem.

contoh :

|No.|Kesatuan Luar | Input            | Output          |
|:-:|:-------------|:----------------:|----------------:|
|1. | Mahasiswa    |Biodata Mahasiswa |Kartu Mahasiswa  |

## Pedoman Menggambarkan Data Flow Diagram
1. Identifikasikan terlebih dahulu semua kesatuan luar yang terlibat di sistem.

2. Identifikasikan semua input dan output yang terlibat dengan kesatuan luar.

3. Gambarkanlah terlebih dahulu suatu diagram konteks. Dari diagram konteks ini akan digambar dengan lebih terinci lagi yang disebut dengan level 0. Tiap-tiap proses di level 0 akan digambar secara lebih terinci lagi disebut dengan level 1. Tiap-tiap proses di level 1 akan digambar secara lebih terinci lagi disebut dengan level 2 dst sampai tiap-tiap proses tidak dapat digambar lebih terinci lagi.

4. Gambarlah bagan berjenjang untuk semua proses yang ada di sistem terlebih dahulu. Bagan berjenjang digunakan untuk mempersiapkan penggambaran DAD ke level-level lebih bawah lagi.

5. Gambarlah sketsa DAD untuk diagram level 0 berdasarkan proses di bagan berjenjang.

6. Gambarlah DAD utk level-level berikutnya yaitu level 1 dst utk tiap-tiap proses yg dipecah-pecah sesuai dengan bagan berjenjangnya.

## Langkah Langkah Desain Secara Umum

1. **Desain Input:**

+ a. Identifikasi Kebutuhan Pengguna:
Lakukan analisis kebutuhan pengguna untuk menentukan jenis data yang diperlukan.

+ b. Pilih Metode Input:
Tentukan cara pengguna akan memasukkan data (misalnya, formulir web, antarmuka pengguna grafis, dll.).

+ c. Validasi Input:
Rencanakan mekanisme validasi untuk memastikan bahwa data yang dimasukkan pengguna sesuai dengan kebutuhan sistem.

2. **Desain Output:**

+ a. Definisi Format Output:
Tentukan format keluaran yang diinginkan, seperti laporan, grafik, atau antarmuka pengguna.

+ b. Pilih Metode Output:
Tentukan cara informasi akan disampaikan kepada pengguna (misalnya, cetak, tampilan layar, atau pengiriman email).

+ c. Desain Responsif:
Pastikan output dapat diakses dengan baik pada berbagai perangkat dan resolusi layar.

3. **Desain Database:**

+ a. Analisis Kebutuhan Data:
Tentukan jenis data yang akan disimpan dan hubungan antar mereka.

+ b. Normalisasi Database:
Terapkan aturan normalisasi untuk menghindari duplikasi data dan meningkatkan efisiensi penyimpanan.

+ c. Pemilihan Sistem Manajemen Basis Data (DBMS):
Pilih DBMS yang sesuai dengan kebutuhan aplikasi Anda (misalnya, MySQL, PostgreSQL, atau MongoDB).

+ d. Desain Skema Database:
Tentukan struktur tabel, kunci primer, kunci asing, dan indeks.

**4. Desain Teknologi:**

+ a. Pilih Platform:
Tentukan platform atau lingkungan tempat aplikasi akan diimplementasikan (misalnya, web, mobile, atau desktop).

+ b. Pilih Bahasa Pemrograman:
Pilih bahasa pemrograman yang sesuai dengan kebutuhan aplikasi dan preferensi tim pengembang.

+ c. Integrasi API:
Tentukan apakah perlu mengintegrasikan aplikasi dengan layanan pihak ketiga melalui API.

+ d. Keamanan:
Rencanakan langkah-langkah keamanan, seperti otentikasi pengguna, enkripsi data, dan perlindungan terhadap serangan.

## Diagram Konteks dan Bagan Berjenjang Sistem Poliklinik 

{{< figure src="/Bagan_Berjenjang.jpg" alt="bagan" title="bagan" >}}


## Desain Input Secara Umum
Berikut adalah desain input `Login` untuk menginputkan email dan password jika inputan sesuai maka akan di lanjutkan ke step berikutnya

{{< figure src="/login.png" alt="Login" title="Login desain" >}}

## Desain Output Secara Umum
Berikut adalah desain output `Dashboard` dari aplikasi Rumah Sakit

{{< figure src="/dashboard2.png" alt="Dashboard" title="Dashboard desain" >}}

## Desain Menu User Interface Secara Umum
Berikut adalah desain menu nya

{{< figure src="/menu ui.png" alt="Dashboard" title="Menu desain" >}}