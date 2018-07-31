---
layout: item
title: "Desain dan Perancangan"
date: 2018-05-16 16:25:06 +0700
comments: true
toc: true
---


## ABSTRAK
Dewasa ini perkembangan teknologi komputer sangatlah pesat. Dengan menggunakan aplikasi komputer akan didapat informasi mengenai suatu tampilan objek yang ditampilkan lebih hidup dan menarik. Adanya kemajuan teknologi ini memungkinkan Sistem untuk menjalankan prosedur pemberian dana hibah dan bantuan sosial dapat berjalan lebih baik dan membantu masyarakat dan Pemerintah Provinsi Banten dalam menjalankan kegiatan yang berkaitan dengan hibah dan bantuan sosial yang lebih terstruktur dan lebih transparansi.

## Daftar Isi
* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## 1. PENDAHULUAN

### 1.1 Latar Belakang
Pembangunan Sistem informasi / aplikasi / website saat ini yang berlangsung di lingkungan Pemerintah Provinsi Banten seakan – akan berjalan sendiri – sendiri.
Meskipun sudah ada Peraturan Gubernur No. 35 Tahun 2008 dan Peraturan Gubernur No. 80, belum menjadikan panduan dalam mengembangkan sistem informasi / aplikasi tersebut.
Agar terdapatnya sebuah sitem yang baik dalam menyelenggarakan kegiatan hibah dan bansos maka perlu dibuatnya suatu fasilitas untuk mendukung kegiatan tersebut. dengan dibuatnya aplikasi E-hibahbansos diharapkan dapat memudahkan segala proses kegiatan E-hibahbansos baik dari sisi pemerintahan maupun masyarakat Provinsi Banten.

### 1.2 Maksud dan Tujuan

#### a) Maksud
Maksud dari kegiatan ini adalah untuk melakukan kegiatan pengembangan Sistem Informasi E-hibahbansos.

#### b) Tujuan
Sistem ehibahbansos Provinsi Banten dibangun dengan tujuan untuk terciptanya efisiensi proses, perbaikan prosedur, peningkatan transparansi dan akuntabilitas belanja hibah, bantuan sosial dan bantuan keuangan pada Pemerintah Provinsi Banten.

### 1.3 Ruang Lingkup Pekerjaan
Ruang lingkup pekerjaan ini adalah pengembangan sistem informasi ini dilakukan di Dinas Komunikasi Informasi Statistika dan Persandian Provinsi Banten, adapun hasil dari kegiatan ini untuk dapat digunakan pada instansi dan masyarakat dilingkungan Pemerintah Provinsi Banten.

### 1.4 Ruang Lingkup Sistem Informasi / Aplikasi
a) Menyediakan situs bagi seluruh Organisasi Perangkat Daerah yang ada dilingkungan Pemerintah Provinsi Banten untuk menyimpan Prosedur Operasional Baku yang berlaku dilingkungannya secara digital,

b) Menyediakan proses pengaduan pengadaan / pengembangan sistem informasi / aplikasi / website secara digital untuk seluruh Organisasi Perangkat Daerah dilingkungan Pemeritah Provinsi Banten.

### 1.5 Keluaran yang diinginkan
a) Tersedianya sistem informasi e-hibahbansos bagi sistem informasi / aplikasi / website dan android,

b) Tersedianya dokumen API yang digunakan.

### 1.6 Waktu dan Jadwal Pelaksanaan dan Lokasi Kegiatan
a) Waktu pelaksanaan kegiatan : 3 bulan sejak dikeluarkan SPK sampai dengan pemakaian,
b) Lokasi kegiatan : Kantor OPD terkait dan Dinas Komunikasi Informasi Statistika dan Persandian Pemerintah Provinsi Banten.

## 2. METODE PENELITIAN
Untuk memperoleh data yang dapat menunjang aplikasi ini, maka di perlukan data teoritis dan data dinas terkait untuk mendapatkan data dan informasi yang berhubungan dengan aplikasi ini.
Adapun penyusun melakukan beberapa penelitian yang dilakukan dengan :

### 2.1 Metode Yang digunakan
Menggunakan metode *prototyping* untuk melakukan perancangan sistem informasi berbasis web.
Ilustrasi alur *prototyping*
[![ilustrasi-alur-prototyping](../images/e-hibahbansos/desain-dan-perancangan//alur-prototype.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/alur-prototype.png)

### 2.2 Metode Pengumpulan Data
Untuk mengumpulkan data yang diperlukan untuk membangun sistem ini diadakan wawancara dan studi pustaka. Pengumpulan data ini diperlukan untuk mengetahui permasalahan dan gambaran sistem yang sedang berjalan sehingga dapat mengembangkannya untuk membentuk sistem baru yang dapat mendukung sistem yang sedang berjalan.
a). Wawancara ini dilakukan kepada Pemprov Banten. Wawancara dilakukan kepada sistem analist Pemprov Banten untuk mengetahui permasalahan dalam proses pendataan yang sedang berjalan sekarang.
b). Studi Pustaka, Melakukan pengumpulan melalui buku text, internet sebagai referensi.

## 3. HASIL PEMBAHASAN
### 3.1 Perencanaan Aplikasi
Sistem informasi e-hibahbansos adalah untuk mempermudah pemerintah dan masyarakat dalam menyenggarakan kegiatan hibah dan bantuan sosial.

### 3.2. Perancangan Sistem
Permodelan rancangan sistem yang digunakan adalah UML (Unified Modeling Language). Menurut Whitten dan Bentley (2007, p.381), Unified Modeling Language adalah kumpulan rancangan diagram untuk membangun sebuah sistem atau aplikasi yang dimana setiap diagram menyediakan sistem informasi kepada tim pengembang dengan berbagai sudut pandang yang berbeda-beda. UML yang kami gunakan terdiri dari use case diagram, activity diagram, sequence diagram, state chart diagram, class diagram, deploymen diagram dan technology diagram.

#### 3.2.1 Use Cace Diagram
##### 3.2.1.1 Use Case Diagram Super Admin
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180718_usecase-superadmin.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180718_usecase-superadmin.png)

##### 3.2.1.2 Use Case Diagram Pendaftar Hibah Bansos
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20170718_usecase-pendaftar.png)](../images/new_ehibahbansos/desain-dan-perancangan/20170718_usecase-pendaftar.png)

##### 3.2.1.3 Use Case Diagram Organisasi Perangkat Daerah (OPD)
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20170718_usecase-opd.png)](../images/new_ehibahbansos/desain-dan-perancangan/20170718_usecase-opd.png)

#### 3.2.2 Activity Diagram

##### 3.2.2.1 Activity Diagram Super Admin
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180719_activitydiagram-superadmin.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180719_activitydiagram-superadmin.png)

##### 3.2.2.2 Activity Diagram Pendaftar Hibah Bansos
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180719_activitydiagram-warga.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180719_activitydiagram-warga.png)

##### 3.2.2.3 Activity Diagram OPD
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180719_activitydiagram-opd.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180719_activitydiagram-opd.png)

#### 3.2.3 Sequence Diagram

##### 3.2.3.1 Sequence Diagram Super Admin
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180719_sequencediagram_superadmin.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180719_sequencediagram_superadmin.png)

##### 3.2.3.2 Sequence Kegiatan Belanja Hibah Bansos
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180719_sequencediagram-kegiatan.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180719_sequencediagram-kegiatan.png)

#### 3.2.4 State Chart Diagram

##### 3.2.4.1 State Chart Diagram Super Admin
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_statechart-superadmin.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_statechart-superadmin.png)

##### 3.2.4.2 State Chart Diagram Pendaftar Hibah / Bansos
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_statechart-warga.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_statechart-warga.png)

##### 3.2.4.3 State Chart Diagram OPD
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_statechart-opd.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_statechart-opd.png)

#### 3.2.5 Deployment Diagram
[![deployment-diagram](../images/e-hibahbansos/desain-dan-perancangan/deployment-diagram.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/deployment-diagram.jpg)

#### 3.2.6 Technology Stack Diagram
[![technology-stack-diagram](../images/e-hibahbansos/desain-dan-perancangan/technology-stack-diagram.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/technology-stack-diagram.jpg)

### 3.3 Tahapan Pekerjaan :
Tahap-tahap atau langkah yang dilakukan dalam mengembangkan Sistem Informasi E-hibahbansos adalah sebagai berikut:

#### 3.3.1 Analisis dan Perancangan
1). Analisis
Tim pengembang aplikasi akan melakukan analisis jika diperlukan dapat dilakukan survey pendahuluan untuk melihat sejauh mana kebutuhan pengguna akan sistem yang akan dibangun, data-data yang dibutuhkan, dll. Dalam analisis ini dilakukana diskusi-diskusi baik dengan bagian terkait pada satuan kerja.

2). Perancangan Sistem
Perancangan sistem dilaksanakan setelah proses analisis dilaksanakan dan telah disepakati modul dan prosedur-prosedur yang akan diterapkan dalam sistem. Perancangan sistem meliputi kegiatan: penetapan alur data/dokumen, penetapan prosedur, perancangan database, perancangan form dan perancangan interface/dialog layar.

#### 3.3.2 Pembangunan Sistem
Setelah proses analisis dan perancangan sistem selesai dilakukan, tahapan selanjutnya adalah pembangunan sistem, yang meliputi kegiatan. Pembuatan struktur database, pembuatan kode program/koding, pembuatan laporan-laporan.

#### 3.3.3 Integrasi dan Pengujian
1). Integrasi
Setelah proses pengembangan sistem selasai dilakukan, tahap selanjutnya adalah Integrasi sistem, yang meliputi kegiatan: pembuatan struktur database terkait integrasi, pembuatan kode program/coding terkait integrasi, pembuatan laporan-laporan terkait integrasi.
Penggunaan webservices / API yang telah disiapkan oleh sistem informasi / aplikasi yang ada.

2). Pengujian
Sistem yang telah selesai dibuat akan diuji coba menggunakan data test sebelum sistem dijalankan. Dalam uji coba sistem ini akan diterapkan metode prototye, yaitu jika terjadi kesalahan/kekurangan baik proses maupuan output sistem, maka kesalahan/kekurangan tersebut akan diperbaiki/ditambahkan, sehingga memungkinkan pengembang untuk kembali ke tahapan pertama yaitu analisa (jika kekurangan sistem memang tidak terdefinisikan dalam dokumen perancangan sistem).

### 3.4 Hasil
Berikut ini adalah hasil eksekusi sistem informasi Dashboard

#### 3.4.1 Tampilan Awal

##### 3.4.1.1 Layout Home
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-awal.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-awal.png)

##### 3.4.1.2 Layout Tampilan Proposal
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-proposal.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-proposal.png)

##### 3.4.1.3 Layout Tampilan Tentang
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-tentang.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-tentang.png)

##### 3.4.1.4 Layout Tampilan Peraturan
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-peraturan.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-20180726_layout_tampilan-peraturan.png)

##### 3.4.1.5 Layout Tampilan Pengumuman
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-pengumuman.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180726_layout_tampilan-pengumuman.png)

#### 3.4.2 Tampilan Superadmin

##### 3.4.2.1 Layout Tampilan Dashboard
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180727_sa_dashboard.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180727_sa_dashboard.png)

##### 3.4.2.2 Layout Tampilan Proposal
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180727_sa_proposal.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180727_sa_proposal.png)

##### 3.4.2.3 Layout Tampilan Workflow

* **Workflow**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_workflow.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_workflow.png)

* **State List**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_state-list.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_state-list.png)

* **Transition List**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_transition-list.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_transition-list.png)

* **Workflow Guard**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_guard.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_guard.png)

* **Workflow Notification**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_notification.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_workflow_notification.png)

##### 3.4.2.4 Layout Tampilan User

* **User List**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_user_user.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_user_user.png)

* **Permission**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_user_permission.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_user_permission.png)

* **Role**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_user_role.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_user_role.png)

##### 3.4.2.5 Layout Tampilan Setting

* **Tentang**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_tentang.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_tentang.png)

* **Peraturan**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_peraturan.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_peraturan.png)

* **Pengumuman**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_pengumuman.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_pengumuman.png)

* **Checklist**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_checklist.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_checklist.png)
  
* **Banner**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_banner.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_banner.png)
  
* **Video**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_video.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_video.png)
  
* **Sosial Media**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_sosial-media.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_sosial-media.png)

* **SKPD**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_skpd.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_skpd.png)
  
* **API Manager**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_api-manager.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_api-manager.png)
  
* **Host Key**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_host-key.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_setting_host-key.png)
  
##### 3.4.2.6 Layout Tampilan Log

* **Log Aktivitas**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_log_log-activitas.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_log_log-activitas.png)
  
* **Log Login**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_log_log-login.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_sa_log_log-login.png)
  
#### 3.4.3 Tampilan OPD

##### 3.4.3.1 Layout Tampilan Dashboard
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_dashboard.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_dashboard.png)

##### 3.4.3.2 Layout Tampilan Proposal

* **Pengecekan Proposal**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_proposal_pengecekan.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_proposal_pengecekan.png)
  
* **Verifikasi Proposal**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_proposal_verifikasi.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_proposal_verifikasi.png)
  
* **Arsip**
  [![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_proposal_arsip.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_opd_proposal_arsip.png)

#### 3.4.4 Tampilan Pendaftar HibahBansos

##### 3.4.4.1 Layout Tampilan Proposal Saya
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_warga_proposal-saya.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_warga_proposal-saya.png)

##### 3.4.4.2 Layout Tampilan Form HibahBansos
[![use-case-diagram-super-admin](../images/new_ehibahbansos/desain-dan-perancangan/20180730_warga_form-hibah-bansos.png)](../images/new_ehibahbansos/desain-dan-perancangan/20180730_warga_form-hibah-bansos.png)

## 4.PENUTUP

Dengan adanya pembuatan dari sistem aplikasi E-hibahbansos diharapkan dapat  terciptanya efisiensi proses, perbaikan prosedur, peningkatan transparansi dan akuntabilitas belanja hibah, bantuan sosial dan bantuan keuangan pada Pemerintah Provinsi Banten.
