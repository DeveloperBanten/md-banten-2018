---
layout: item
title: "Pengembangan"
date: 2018-05-16 16:25:06 +0700
comments: true
toc: true
cat: Dashboard Pimpinan
---

[![cover-manual-book-dashboard-pimpinan](../images/dashboard-pimpinan/pengembangan/cover-manual-book-dashboard-pimpinan.jpeg)](../images/dashboard-pimpinan/pengembangan/cover-manual-book-dashboard-pimpinan.jpeg)

Document manual book ini dibuat untuk memberikan panduan penggunaan aplikasi **Dashboard Pimpinan**, dimana Aplikasi Dashboar Pimpinan adalah aplikasi antar muka untuk monitoring dan mempermudah Pimpinan untuk melihat dan menilai kinerja SKPD (Satuan Kerja Perangkat Daerah). Perangkat lunak yang di butuhkan untuk pengujian aplikasi adalah Ubuntu 17 sebagai Operasi System. Sumber daya manusia untuk menggunakan aplikasi ini terutama dari Pimpinan dinas Provinsi Banten, penggunaan aplikasi ini terlebih dahulu diberikan pengenalan dan pelatihan yang cukup untuk menggunakan aplikasi *Dashboard Pimpinan*.

### 1. Struktur Menu
Adapun struktur menu pada aplikasi Dashboard Pimpinan adalah sebagai berikut:
#### 1.1 Menu Dashboard
- **Data Pegawai**
- **Fasilitas Kesehatan**

#### 1.2 Menu Data OPD
- **Data OPD**

#### 1.3 **Menu User**

#### **1.4 Menu Settings**

- **Roles**
- **Permission**
- **Menu Permission**

#### **1.5 Menu Api Manager**

- **Host Keys**
- **Client Keys**

#### **1.6 Menu Data Workflow**

- **Workflow**
- **Workflow State**
- **Workflow Transition**
- **Workflow History**

Untuk memulai akses terhadap aplikasi **Dashboard Pimpinan**. Buka web browser (IE, Mozilla Firefox atau yang lainnya) dengan menulis alamat url http://103.83.198.5/#/login (***Dev Version***) kemudian tekan Enter** pada tombol keyboard atau klik tombol **Go** pada browser. Akan muncul tampilan halaman login aplikasi dashboard seperti gambar dibawah ini.

[![tampilan-login-admin](../images/dashboard-pimpinan/pengembangan/tampilan-login-admin.png)](../images/dashboard-pimpinan/pengembangan/tampilan-login-admin.png)

**Gambar 1. Tampilan Login**

Masukkan User Id dan Password, Setelah di isi lengkap dan benar, klik button **Sign in** atau tekan tombol **Enter** pada keyboard. Sehingga akan menampilkan halaman utama sebagai berikut.

[![dashboard-home-awal](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)
**Gambar 2. Tampilan Awal**

#### 2. Menu Dashboard
Halaman muka Dashboard Pimpinan Menampilkan 2 grafik:

- *Dashboard Kepegawaian*
- *Dashboard Fasilitas Kesehatan*

Seperti ditunjukan pada gambar berikut ini:

[![dashboard-home-awal](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)](../images/dashboard-pimpinan/pengembangan/dashboard-home-awal.png)
**Gambar 3. Halaman Utama (Home)**

Untuk menampilkan detail dashboard Data Pegawai dengan mengklik tombol **Data Pegawai**.
maka akan ditampilkan jumlah Pegawai Aktif, Pegawai Pensiun, Pindah/Keluar, dan Meninggal Dunia. Seperti ditunjukan pada gambar berikut ini:

[![grafik-data-kepegawaian](../images/dashboard-pimpinan/pengembangan/grafik-data-kepegawaian.png)](../images/dashboard-pimpinan/pengembangan/grafik-data-kepegawaian.png)
**Gambar 4. Detail Prosentase dan Grafik Data Kepegawaian**

Untuk menampilkan detail dashboard Fasilitas Kesehatan dengan mengklik tombol **Fasilitas Kesehatan**. maka akan ditampilkan data Jumlah Rumah Sakit, Dokter, Bed Rawat Inap, dan Ambulance. Seperti ditunjukan pada gambar berikut ini:

[![grafik-fasilitas-kesehatan](../images/dashboard-pimpinan/pengembangan/grafik-fasilitas-kesehatan.png)](../images/dashboard-pimpinan/pengembangan/grafik-fasilitas-kesehatan.png)

**Gambar 5. Detail Prosentase dan Grafik Fasilitas Kesehatan**

#### 3. Menu OPD
Menu OPD adalah tampilan aplikasi yang dipergunakan untuk Superadmin dan Admin, di mana bisa untuk Input, Hapus, Edit, Update, View data OPD yang ada, dengan menekan atau klik tombol **create** akan tampil form tabel untuk penambahan data. Seperti yang ditunjukan pada gambar berikut ini:

**Data OPD**
[![data-opd-list](../images/dashboard-pimpinan/pengembangan/data-opd-list.png)](../images/dashboard-pimpinan/pengembangan/data-opd-list.png)
**Gambar 6. List Data OPD**

Klik tombol Create sistem aplikasi akan menampilakan gambar di bawah ini

[![add-data-opd](../images/dashboard-pimpinan/pengembangan/add-data-opd.png)](../images/dashboard-pimpinan/pengembangan/add-data-opd.png)
**Gambar 7. Form Tabel Tambah Data OPD**

#### **4. Menu User**

Menu User adalah tampilan aplikasi yang dipergunakan untuk Superadmin dan Admin, di mana bisa untuk Input, Hapus, Edit, Update, View data yang ada, dengan menekan atau klik tombol **create** akan tampil form tabel untuk penambahan data. Seperti pada gambar dibawah ini:

**User List**

[![users-list-tabel-admin](../images/dashboard-pimpinan/pengembangan/users-list-tabel-admin.png)](../images/dashboard-pimpinan/pengembangan/users-list-tabel-admin.png)

**Gambar 8. List Tabel Users**

Klik tombol Create sistem aplikasi akan menampilakan gambar di bawah ini

[![add-user-admin](../images/dashboard-pimpinan/pengembangan/add-user-admin.png)](../images/dashboard-pimpinan/pengembangan/add-user-admin.png)

**Gambar 9. Form Tabel Add User**

#### **5. Menu Settings**

Menu Settings adalah tampilan aplikasi yang dipergunakan untuk Superadmin dan Admin, di mana bisa untuk Input, Hapus, Edit, Update, View data yang ada, dengan menekan atau klik tombol **create** akan tampil form tabel untuk penambahan data. Didalam menu settings ada beberapa bagian menu, diantaranya adalah dengan tampilan gambar seperti dibawah ini:

**Roles**

[![role-users-list-admin](../images/dashboard-pimpinan/pengembangan/role-users-list-admin.png)](../images/dashboard-pimpinan/pengembangan/role-users-list-admin.png)

**Gambar 10. List Role User**

#### **6. Menu Api Manager**

Menu Api Manager adalah tampilan aplikasi yang dipergunakan untuk Superadmin dan Admin untuk mengelola *request* API. Didalam menu Api Manager ada beberapa bagian menu, diantaranya adalah dengan tampilan gambar seperti dibawah ini:

**Host Keys**

[![list_host_keys](../images/dashboard-pimpinan/pengembangan/list_host_keys.png)](../images/dashboard-pimpinan/pengembangan/list_host_keys.png)

**Gambar 11. List Host Keys**

Klik tombol Request, sistem aplikasi akan menampilkan gambar di bawah ini

[![add_host_keys](../images/dashboard-pimpinan/pengembangan/add_host_keys.png)](../images/dashboard-pimpinan/pengembangan/add_host_keys.png)

**Gambar 12. Form Tabel Tambah Host Keys**

**Client Keys**

[![list_client_keys](../images/dashboard-pimpinan/pengembangan/list_client_keys.png)](../images/dashboard-pimpinan/pengembangan/list_client_keys.png)

**Gambar 13. List Data Api Clients**

Klik tombol Create, sistem aplikasi akan menampilkan gambar di bawah ini

[![add_client_keys](../images/dashboard-pimpinan/pengembangan/add_client_keys.png)](../images/dashboard-pimpinan/pengembangan/add_client_keys.png)

**Gambar 14. Form Tabel Tambah Api Client**

#### **7. Menu Data Workflow**

Menu Data Workflow adalah tampilan aplikasi yang dipergunakan untuk Superadmin dan Admin untuk melihat alur status API Request. Didalam menu Data Workflow terdapat beberapa bagian menu, diantaranya adalah dengan tampilan gambar seperti dibawah ini:

**Workflow**

[![list_data_workflow](../images/dashboard-pimpinan/pengembangan/list_data_workflow.png)](../images/dashboard-pimpinan/pengembangan/list_data_workflow.png)

**Gambar 15. List Tabel Data Workflow**

Klik tombol Create sistem aplikasi akan menampilakan gambar di bawah ini

[![add_data_workflow](../images/dashboard-pimpinan/pengembangan/add_data_workflow.png)](../images/dashboard-pimpinan/pengembangan/add_data_workflow.png)

**Gambar 16. Form Tabel  Tambah Workflow**

**Workflow State**

[![list_workflow_state](../images/dashboard-pimpinan/pengembangan/list_workflow_state.png)](../images/dashboard-pimpinan/pengembangan/list_workflow_state.png)

**Gambar 17. List Tabel Data Workflow State**

Klik tombol Create sistem aplikasi akan menampilakan gambar di bawah ini

[![add_workflow_state](../images/dashboard-pimpinan/pengembangan/add_workflow_state.png)](../images/dashboard-pimpinan/pengembangan/add_workflow_state.png)

**Gambar 18. Form Tabel Tambah Workflow State**

**Workflow Transition**

[![list_workflow_transition](../images/dashboard-pimpinan/pengembangan/list_workflow_transition.png)](../images/dashboard-pimpinan/pengembangan/list_workflow_transition.png)

**Gambar 19. List Tabel Data Workflow Transition**

Klik tombol Create sistem aplikasi akan menampilakan gambar di bawah ini

[![add_workflow_transition](../images/dashboard-pimpinan/pengembangan/add_workflow_transition.png)](../images/dashboard-pimpinan/pengembangan/add_workflow_transition.png)

**Gambar 20. Form Tabel Tambah Workflow Transition**

**Workflow History**

[![list_workflow_history](../images/dashboard-pimpinan/pengembangan/list_workflow_history.png)](../images/dashboard-pimpinan/pengembangan/list_workflow_history.png)

**Gambar 21. List Tabel Data Workflow History**
