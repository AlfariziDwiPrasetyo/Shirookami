---
title: "Perancangan Sistem"
date: 2025-04-07
draft: false
description: "Analisis & perancangan berorientasi objek bab 2"
slug: "perancangan-sistem-apbo"
tags: ["Analisis & perancangan berorientasi objek"]
series: ["APBO"]
series_order: 2
showAuthor: true
showAuthorsBadges : false
---

## 1. Desain Sistem Secara Umum

Desain sistem secara umum menggambarkan bagaimana keseluruhan sistem akan berjalan, termasuk proses, aliran data, serta relasi antar bagian dalam sistem. Tujuannya adalah memberikan gambaran awal sistem sebelum masuk ke tahap detail dan implementasi teknis.

### Tujuan Perancangan Sistem

| No | Tujuan                                |
|----|----------------------------------------|
| 1  | Menyusun struktur sistem yang efisien  |
| 2  | Menentukan alur informasi dan data     |
| 3  | Menyiapkan fondasi untuk implementasi  |
| 4  | Meningkatkan pemahaman antar tim       |

---

## 2. Desain Sistem Secara Terinci

Perancangan terinci dibagi menjadi dua pendekatan utama, yaitu:

- **Pendekatan Terstruktur**
- **Pendekatan Berorientasi Objek**

Keduanya digunakan untuk menggambarkan sistem dari dua sisi berbeda, namun saling melengkapi.

---

### a. Pendekatan Terstruktur

Pendekatan ini berfokus pada alur proses dan struktur data menggunakan beberapa diagram:

#### 1) System Flowchart

System Flowchart menggambarkan proses aliran data dalam sistem dari awal hingga akhir secara menyeluruh. Diagram ini melibatkan proses input, pemrosesan, dan output dalam bentuk simbol.

**Contoh System Flowchart:**

![System Flowchart](https://i0.wp.com/niagaspace.sgp1.digitaloceanspaces.com/blog/wp-content/uploads/2023/05/16182647/8-contoh-flow-chart-untuk-membantu-pengambilan-keputusan.webp?resize=745%2C678&ssl=1)

#### 2) Data Flow Diagram (DFD)

DFD menggambarkan aliran data antar proses dalam sistem. DFD terbagi menjadi beberapa level:
- **Context Diagram** (Level 0)
- **Level 1**: Rinciannya dari Context Diagram

| Simbol | Keterangan     |
|--------|----------------|
| 🟦     | Proses         |
| 🟩     | Data Store     |
| ⬜     | Entitas Eksternal |
| ➡️     | Alur Data       |

#### 3) System Procedure Diagram (Flowmap)

Flowmap menunjukkan prosedur atau urutan kerja di dalam sistem. Diagram ini menggambarkan urutan langkah-langkah dan dokumen yang terlibat dalam suatu proses bisnis.

---

### b. Pendekatan Berorientasi Objek (UML)

Pendekatan ini menggunakan **Unified Modeling Language (UML)** untuk menggambarkan sistem berbasis objek. UML membantu dalam dokumentasi dan pemahaman sistem dari sisi entitas (objek), atribut, dan hubungan antar objek.

#### Jenis-jenis Diagram UML:

| Diagram               | Kegunaan                                               |
|-----------------------|--------------------------------------------------------|
| Use Case Diagram      | Menunjukkan aktor dan interaksi dengan sistem          |
| Class Diagram         | Menjelaskan struktur kelas dan relasi antar kelas      |
| Activity Diagram      | Menggambarkan alur aktivitas/proses                    |
| Sequence Diagram      | Menampilkan urutan pesan antar objek                   |

---

### Contoh Use Case Diagram:

![Use Case Diagram](https://www.plantuml.com/plantuml/png/SoWkIImgAStDuNBCoKnEICt9BKajI2f9pSd91jL8pSd91ILBpSd91J0BpSd9pSd91IQoArU0)

---

### Kesimpulan

Dengan adanya pendekatan terstruktur dan berorientasi objek dalam desain sistem, pengembang memiliki panduan visual yang komprehensif dan terorganisir. Hal ini membantu memastikan sistem dikembangkan sesuai kebutuhan, efisien, dan mudah dipelihara.

---

**Catatan:** Semua diagram dapat dibuat menggunakan tools seperti **draw.io**, **Lucidchart**, atau **StarUML**.
