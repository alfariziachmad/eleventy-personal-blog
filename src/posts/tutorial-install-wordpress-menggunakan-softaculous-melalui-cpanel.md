---
layout: layouts/post.njk
title: Tutorial Install WordPress menggunakan Softaculous melalui cPanel
metaTitle: Tutorial Install WordPress menggunakan Softaculous melalui cPanel
metaDesc: Tutorial Install WordPress menggunakan Softaculous melalui cPanel
date: 2023-04-14T14:24:42.767Z
tags:
  - WordPress
  - Softaculous
  - cPanel
  - Hosting
  - Linux
  - PHP
---
## Pendahuluan

Pada kesempatan kali ini, Saya akan menulis Artikel tentang Tutorial Install WordPress menggunakan Softaculous melalui cPanel. Seperti yang kita ketahui, WordPress merupakan salah satu Content Management System (CMS) open-source gratis yang ditulis dalam Bahasa pemrograman **PHP** dan biasanya dipasangkan dengan Database **MySQL** atau **MariaDB.**

## Persiapan

Pastikan sebelumnya Anda sudah memiliki Layanan Hosting dan Domain serta dapat mengakses Control Panel Layanan Hosting cPanel.

## Instalasi

Jika Anda sudah berhasil login kedalam cPanel, pada Menu **Software,** buka sub-Menu **Softaculous Apps Installer.** 

![Softaculous Apps Installer](/images/softaculous-apps-installer.png "Softaculous Apps Installer")

Setelah Anda membuka sub-Menu Softaculous Apps Installer, Cari “WordPress” pada kolom pencarian, lalu klik tombol “Install”.

![Install WordPress](/images/install-wordpress.png "Install WordPress")

Masukkan Konfigurasi Instalasi WordPress sesuai dengan Konfigurasi Anda.

![Tahap 1 Install WordPress](/images/tahap-install-wordpress-1.png "Tahap 1 Install WordPress")

Pada bagian “Choose Protocol”, Ubah ke "<https://>" atau "<https://www>" jika sebelumnya Anda sudah memiliki Sertifikat SSL.
Pada bagian “Choose Domain”, pilih Domain yang ingin Anda Install WordPress.
Pada bagian “In Directory”, biarkan kosong atau nantinya semua File WordPress Anda tersimpan di dalam Folder **public_html** sebagai “Default Directory” untuk Folder Installer WordPress Anda.
Pada bagian “Please select the version to install”, pilih Versi WordPress yang paling terbaru. Saat Artikel ini dibuat, Versi **6.2** merupakan Versi WordPress paling terbaru.
Pada bagian “Site Setting” dan “Admin Account”, sesuaikan dengan Konfigurasi WordPress Anda.

![Tahap 2 Install WordPress](/images/tahap-install-wordpress-2.png "Tahap 2 Install WordPress")

Pada bagian “Choose Language” dan “Select Plugin(s)”, sesuaikan dengan Konfigurasi WordPress Anda.
Pada bagian “Database Name” dan “Table Prefix”, sesuaikan dengan Konfigurasi WordPress Anda.

![Tahap 3 Install WordPress](/images/tahap-install-wordpress-3.png "Tahap 3 Install WordPress")

Pada bagian “Select Theme”, pilih tema yang ingin Anda Install pada WordPress Anda. Setelah semua Konfigurasi Anda sudah di isi, Klik tombol “Install”

![WordPress Install Successfully](/images/wordpress-install-successfully.png "WordPress Install Successfully")

Jika proses Install WordPress sudah berhasil, maka akan muncul halaman seperti diatas berikut dengan detail WordPress Anda. Untuk mengakses WordPress, Anda dapat klik tombol “Return to WordPress Management”

![WordPress Management Page](/images/wordpress-management-page.png "WordPress Management Page")

Pada Halaman WordPress Management inilah Anda dapat merubah Konfigurasi WordPress, mulai dari Nama Site, konfigurasi Plugin dan Themes, sampai konfigurasi Database.

## Kesimpulan

Demikian Artikel singkat tentang Tutorial Install WordPress menggunakan Softaculous melalui cPanel. Semoga Artikel ini dapat membantu Anda semua dalam melakukan Install WordPress menggunakan Softaculous. Sampai jumpa pada kesempatan lainnya. Terima kasih telah membaca Artikel ini, semoga Anda terhibur :)