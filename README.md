<h5 align="center"><img src="https://camo.githubusercontent.com/fcccdd4ab52e10be669d69d10a3180b212edb352/687474703a2f2f692e696d6775722e636f6d2f536c62767436352e706e67"></h5>

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Konfigurasi](#konfigurasi) | [Otomatisasi](#otomatisasi) | [Cara Pemakaian](#cara-pemakaian) | [Pembahasan](#pembahasan) | [Referensi](#referensi)
:---:|:---:|:---:|:---:|:---:|:---:|:---:

# Sekilas Tentang
[`^ kembali ke atas ^`](#)

**Clumsy Bird** adalah Sebuah Permainan yang berbasis MelonJS. Permainan ini dapat di install di server maupun dijalankan secara lokal. Gameplay dari permainan ini cukup sederhana. hanya dengan **mengklik**, user dapat memainkan permainan ini. tujuan dari permainan ini adalah mendapat skor setinggi-tingginya.

# Instalasi
[`^ kembali ke atas ^`](#)

#### Kebutuhan Sistem :
- Virtualbox 2.6
- Ubuntu server 16.04
- Ubuntu LTS 16.04

#### Proses Instalasi :
1. Lakukan update server
```
$ sudo apt update
```

2. Install ssh pada Ubuntu server
```
$ sudo apt install ssh
```

3. Login ke dalam server menggunakan SSH
```
$ ssh student@localhost –p 2222
```

4. Install NodeJs.
```
$ sudo apt-get install nodejs
$ sudo apt-get install npm
```
5. Install Grunt dan CLI Grunt
```
$ sudo npm -g install grunt
$ sudo npm install -g grunt-cli
```
6. Install minimatch Dependencies Grunt .
```
$ sudo npm install -g minimatch
```
7. Install Git.
```
$ sudo apt-get install git-core
```
8. Menghubungkan folder nodejs dan node
```
$ sudo ln -s /usr/bin/nodejs /usr/bin/node

```
9. Masuk ke folder clumsy-bird yang telah di unduh di direktori home server
```
$ cd clumsy-bird-master/
```

10. Install Clumsy-Bird.
```
$ sudo npm install
$ sudo npm install grunt --save-dev

```

12. Jalankan Server Game Clumsy-Bird.
```
$ grunt connect
```

13. Masukkan Address localhost:8000 di Browser untuk mengakses Game.
```
$ https://localhost:8000
```
# Konfigurasi

[`^ kembali ke atas ^`](#)

- Tekan tombol **M** untuk mode senyap.


# Maintenance

[`^ kembali ke atas ^`](#)

- tidak ada maintenance


# Otomatisasi
[`^ kembali ke atas ^`](#)

- tidak ada Otomatisasi

# Cara Pemakaian
[`^ kembali ke atas ^`](#)

   Aturan Permainan :

1. **Bird** akan mati jika menyentuh dinding.
2. **Bird** hanya memiliki 1 nyawa
3. **Score** akan bertambah 1 setiap bird berhasil melewati dinding

  Cara Bermain :
  - tekan tombol space untuk membuat **Bird** terbang
  - Hindari dinding yang menghalangi **Bird**
  - Raihlah Score setinggi mungkin.

![Halaman sebelum sign up](https://github.com/airjyp/Komdat---Oxwall/blob/master/Screenshots/halaman%20sebelum%20login.png)


# Pembahasan
[`^ kembali ke atas ^`](#)

**Oxwall** ditulis dalam bahasa pemrograman PHP yang support untuk penggunaan MySQL. **Oxwall** merupakan salah satu aplikasi web jejaring sosial media (CMS) yang cukup simple dan mudah digunakan dengan kelebihan diantaranya :
- Tampilan cukup simple (minimalist) dan *light* saat digunakan.
- Tidak menggunakan memori terlalu besar.
- Design aplikasi yang responsif, sehingga dapat digunakan pada berbagai platforms.
- Fitur **Search** yang cukup detail, dapat mencari berdasarkan kriteria tertentu.
- Dapat dikustomisasi baik untuk situs keluarga, forum, maupun jaringan sosial secara enterprise.

Namun, setiap aplikasi pasti memiliki kekurangan dari segi tertentu, Kekurangan dari **Oxwall** ini adalah :
- Dari segi developer, aplikasi ini belum up-to-date, banyak fitur yang belum di*improve* seiring dengan teknologi aplikasi saat ini sehingga Oxwall tidak lebih baik dari aplikasi yang sudah berkembang saat ini.
- Tidak ada pengaturan yang baik pada pengelolaan privasi pengguna. Siapapun dapat melihat aktivitas maupun profil siapa saja.
- Dalam segi UX, pada saat melakukan sesi register terlalu banyak melakukan input data yang tidak dibutuhkan.



Apabila kira membandingkan **Oxwall** dengan CMS dengan jejaring sosial media seperti Facebook, CMS ini memiliki beberapa keunggulan dan kelemahan. Berikut adalah beberapa perbandingan antara Oxwall dengan Facebook ini :

- **Oxwall** menggunakan memori yang lebih ringan daripada **Facebook** karena modulnya lebih sedikit.
- **Facebook** memiliki plugin yang lengkap dan mendukung semua kustomisasi pada setiap fitur dibandingkan **Oxwall**.
- **Oxwall** memiliki fitur search yang detail berdasarkan kriteria tertentu, berbeda dengan **Facebook**
- **Facebook** memiliki pengguna yang jauh lebih banyak daripada **Oxwall** yang aktif pada forum-forum diskusi atau jejaring sosial yang bersifat enterprise.


# Referensi
[`^ kembali ke atas ^`](#)

1. [About Clumsy-Bird](https://www.oxwall.com/about) - Oxwall
2. [Apache Override](https://www.digitalocean.com/community/tutorials/how-to-rewrite-urls-with-mod_rewrite-for-apache-on-ubuntu-16-04) - DigitalOcean
3. [Mysql PHP Problem](https://developers.oxwall.com/forum/topic/55994?page=1) - Oxwall Forum
4. [Cron Jobs Config](https://wiki.oxwall.com/install:cron) - Oxwall Wiki
5. [Oxwall Review](https://alternativeto.net/software/oxwall/reviews/) - Alternativeto
