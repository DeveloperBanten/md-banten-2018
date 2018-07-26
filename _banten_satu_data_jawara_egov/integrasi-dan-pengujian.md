---
layout: item
title: "Integrasi dan Pengujian"
date: 2018-05-16 16:25:06 +0700
toc: true
comments: true
---

## DAFTAR ISI
* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Integrasi dan Pengujian Banten Satu Data JAWARA e-Gov

Banten Satu Data JAWARA e-Gov adalah sebuah aplikasi sistem informasi Provinsi Banten yang berbasis android yang dikeluarkan oleh pemerintah Provinsi Banten untuk memudahkan bagi masyarakat dalam melakukan pencarian informasi serta menjadi satu pintu bagi semua aplikasi dan pelayanan yang tersedia pada Pemerintahan Provinsi Banten.

## 1. Integrasi JAWARA e-Gov
Integrasi aplikasi dilakukan dengan:
1. melalui antar muka aplikasi atau melalui method
2. *focus method level*
3. method di*share* dengan meletakannnya pada sebuah server pusat / dengan mengakses *method* pada aplikasi.

*Application Programming Interface*
mekanisme terdefinisi dibuat untuk berhubungan dengan sumber daya seperti server aplikasi, *middleware*, dan basis data.

Dibawah ini adalah pengintegrasian yang terdapat didalam Banten Satu data JAWARA e-Gov:

### 1.1 Public Function Content
[![Content](../images/jawara-egov/integrasi-dan-pengujian/mocr_public-function_content.png)](dev2018.bantenprov.go.id)

#### 1.2 Public Function Index
[![Index](../images/jawara-egov/integrasi-dan-pengujian/mocr_public-function_index.png)](dev2018.bantenprov.go.id)

#### 1.3 Public Function Menu
[![Menu](../images/jawara-egov/integrasi-dan-pengujian/mocr_public-function_menu.png)](dev2018.bantenprov.go.id)

#### 1.4 Public Function Submenu
[![Submenu](../images/jawara-egov/integrasi-dan-pengujian/mocr_public-function_submenu.png)](dev2018.bantenprov.go.id)

Pada Integrasi ini semua response baik *Success Response* maupun *Error Response* hasilnya akan ditampilkan dalam bentuk Json. 

## 2. Pengujian JAWARA e-Gov

Pada pengujian ini akan menggunakan User Acceptance Test (UAT).

Dibawah ini adalah pengujian yang dilakukan didalam aplikasi Banten Satu Data JAWARA e-Gov:

#### 2.1 Loading JAWARA e-Gov

| Akses                | URL/ Image                               | Ada  | Tidak |
| -------------------- | ---------------------------------------- | ---- | ----- |
| Loading JAWARA e-Gov | [![lihat Category](../images/jawara-egov/pengembangan/loading.jpeg)](../images/jawara-egov/pengembangan/loading.jpeg) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah **Loading JAWARA e-Gov** sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya konten ini *user* dapat melihat di aplikasi android JAWARA e-Gov, jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.2 Dashboard JAWARA e-Gov

| Akses                  | URL/ Image                               | Ada  | Tidak |
| ---------------------- | ---------------------------------------- | ---- | ----- |
| Dashboard JAWARA e-Gov | [![dashboard android](../images/jawara-egov/implementasi/dashboard-android.jpeg)](../images/jawara-egov/implementasi/dashboard-android.jpeg) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah **Dashboard JAWARA e-Gov** sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya konten ini *user* dapat melihat di aplikasi android JAWARA e-Gov, jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.3 Aplikasi Pemerintah

| Akses               | URL/ Image                               | Ada  | Tidak |
| ------------------- | ---------------------------------------- | ---- | ----- |
| Aplikasi Pemerintah | [![aplikasi pemerintah](../images/jawara-egov/implementasi/aplikasi-pemerintah.jpeg)](../images/jawara-egov/implementasi/aplikasi-pemerintah.jpeg) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah **Aplikasi Pemerintah** sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya konten ini *user* dapat melihat di aplikasi android JAWARA e-Gov, jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.4 Aplikasi Publik

| Akses           | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Apliaksi Publik | [![aplikasi publik](../images/jawara-egov/implementasi/aplikasi-publik.jpeg)](../images/jawara-egov/implementasi/aplikasi-publik.jpeg) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah **Aplikasi Publik** sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya konten ini *user* dapat melihat di aplikasi android JAWARA e-Gov, jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".
