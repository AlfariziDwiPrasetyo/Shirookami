---
title: "Bab 4 Analisis Sistem"
date: 2024-01-01
draft: false
description: "ANALISIS SISTEM"
slug: "analisis-sistem"
tags: ["Sistem informasi"]
series: ["Sistem Informasi"]
series_order: 4
showAuthor: true
showAuthorsBadges : false
---

## Definisi Analisa Sistem

`Analisa Sistem`, atau System Analysis, adalah teknik atau metode pemecahan masalah dengan menguraikan bagian-bagian komponen suatu sistem informasi untuk mengidentifikasikan dan mengevaluasi permasalahan, kesempatan, hambatan, dan kebutuhan yang diharapkan sehingga dapat diusulkan perbaikan-perbaikannya. Tujuan dari analisis sistem adalah untuk memperbaiki sistem yang telah dipakai sebelumnya atau membuat sistem baru dari awal, sehingga mendapatkan sistem yang efisien dan menguntungkan bagi pihak.

## Tahapan Analisa Sistem

+ **Identifikasi Masalah:** Ada tiga langkah yang harus dilakukan di dalam tahapan ini yaitu:

1. Mengidentifikasi Penyebab Masalah
Pada tahap ini kita harus dapat mengetahui apa yang menyebabkan masalah terjadi. Misal terjadi penurunan omzet penjualan karena banyak konsumen yang komplain terhadap divisi penjualan tersebut.

2. Mengidentifikasi Titik Keputusan
Setelah penyebab terjadinya masalah dapat ditentukan, selanjutnya juga harus ditentukan titik keputusan penyebab masalah tersebut.
Contoh: penyebab masalah konsumen komplain karena pelayanan yang kurang baik terhadap konsumen. Titik keputusan yang mengakibatkan terjadinya sebab masalah ini adalah penanganan order langganan di bagian order penjualan yang kurang baik kepada pelanggan.

3. Mengidentifikasi Personil-Personil Kunci
Setelah titik-titik keputusan penyebab masalah dapat diidentifikasi beserta lokasi terjadinya, maka selanjutnya yang perlu diidentifikasi adalah personil-personil kunci baik yang langsung maupun tidak langsung dapat menyebabkan terjadinya masalah tersebut.

+ **Memahami Kerja dari Sistem yang Ada:**

Dapat dilakukan dengan mempelajari secara terinci bagaimana sistem yang ada beroperasi. Untuk mempelajari operasi dari sistem ini diperlukan data yang dapat diperoleh dengan cara melakukan penelitian:

1. Menentukan jenis penelitian
2. Merencanakan jadwal penelitian
3. Membuat penugasan penelitian
4. Membuat agenda wawancara
5. Mengumpulkan hasil penelitian

+ **Menganalisis Hasil Penelitian:**  

Langkah ini dilakukan berdasarkan data yang telah diperoleh dari hasil penelitian yang telah dilakukan. Kita dapat menganalisis:

1. kelemahan dari sistem lama tersebut
2. kebutuhan data dan informasi bagi pemakai sistem dan pihak manajemen

+ **Membuat Laporan Hasil Analisis:** 

Isinya adalah:

1. Alasan melakukan analisis sistem
2. Menguraikan permasalahan-permasalahan yang terjadi pada sistem lama
2. Mengidentifikasi penyebab masalah
2. Kesimpulan analisis

## Alat Analisis Sistem

Dalam analisis sistem, alat-alat tertentu digunakan untuk memahami, merancang, dan mendokumentasikan kebutuhan sistem serta proses bisnis. Berikut ini penjelasan lebih rinci tentang beberapa alat analisis sistem yang umum digunakan:

1. Diagram Alir (Flowchart)
Diagram alir adalah representasi visual dari langkah-langkah proses atau alur data dalam sistem. Alat ini membantu mengidentifikasi operasi, alur logika, dan urutan proses yang terlibat dalam sistem. Diagram alir menggunakan simbol standar untuk menunjukkan berbagai jenis aksi atau langkah dalam proses, seperti:

+ Oval: Menunjukkan awal atau akhir dari sebuah proses.
+ Kotak: Menunjukkan suatu instruksi atau tindakan.
+ Rombus (Rhombus): Menunjukkan pengambilan keputusan.
+ Panah: Menunjukkan alur proses.

Manfaat menggunakan diagram alir termasuk kemudahan dalam mengidentifikasi bottleneck,redundansi, atau ketidakefisienan dalam proses.

2. Diagram Use Case
Diagram use case adalah representasi visual yang menunjukkan bagaimana sistem berinteraksi dengan entitas eksternal (biasanya pengguna atau aktor lainnya). Diagram ini membantu mengidentifikasi fungsi sistem dari perspektif pengguna dan bagaimana sistem tersebut memenuhi kebutuhan mereka.

Elemen utama dalam diagram use case termasuk:

+ Aktor: Pengguna atau sistem lain yang berinteraksi dengan sistem.
+ Use Case: Sekumpulan skenario yang menggambarkan interaksi antara aktor dan sistem untuk mencapai tujuan tertentu.
+ Hubungan: Garis yang menghubungkan aktor dengan use case-nya, menunjukkan interaksi.

Diagram use case sangat berguna dalam fase analisis kebutuhan untuk memahami fungsi yang diharapkan dari sistem.

3. Entity-Relationship Diagram (ERD)
ERD adalah alat yang digunakan untuk menggambarkan hubungan antar entitas dalam basis data. Entitas dapat dianggap sebagai objek atau konsep yang informasinya perlu disimpan, dan hubungan menunjukkan bagaimana entitas tersebut berinteraksi satu sama lain.

Elemen utama dalam ERD termasuk:

+ Entitas: Objek atau konsep yang data tentangnya perlu disimpan.
+ Atribut: Informasi yang menyimpan detail tentang entitas.
+ Hubungan: Menunjukkan bagaimana entitas terkait satu sama lain.

ERD membantu dalam desain basis data yang efisien dan normalisasi dengan mengidentifikasi entitas kunci, atribut, dan hubungan mereka.

4. Unified Modeling Language (UML)

UML adalah kumpulan alat pemodelan yang standar dan serbaguna untuk analisis, desain, dan dokumentasi sistem software. UML mencakup berbagai diagram untuk menangani aspek berbeda dari sistem, termasuk struktur dan perilaku sistem. Beberapa diagram UML yang sering digunakan dalam analisis sistem antara lain:

+ Diagram Kelas (Class Diagram): Menunjukkan struktur kelas dalam sistem beserta atribut dan metode mereka.
+ Diagram Sekuens (Sequence Diagram): Menunjukkan bagaimana objek berinteraksi dalam urutan waktu tertentu.
+ Diagram Aktivitas (Activity Diagram): Menunjukkan alur kerja atau proses bisnis dengan alur kontrol atau alur objek.
+ Diagram Komponen (Component Diagram): Menunjukkan organisasi dan ketergantungan antara komponen dalam sistem.
+ Diagram Deployment (Deployment Diagram): Menunjukkan konfigurasi perangkat keras dan software yang menjalankan komponen dan objek sistem.

Menggunakan UML memungkinkan analis dan pengembang untuk memiliki pemahaman yang sama tentang sistem, memfasilitasi komunikasi antar tim, dan menyediakan dokumentasi yang konsisten dan terstruktur untuk sistem yang sedang dikembangkan.

