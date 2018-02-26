<h5 align="center"><img src="https://github.com/wiranegara777/komdat-clumsy-bird/blob/master/img/screenshot1.png?raw=true"></h5>

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


<h5 align="center"><img src="https://github.com/wiranegara777/komdat-clumsy-bird/blob/master/img/screenshot3.png?raw=true"></h5>

   Aturan Permainan :

1. **Bird** akan mati jika menyentuh dinding.
2. **Bird** hanya memiliki 1 nyawa
3. **Score** akan bertambah 1 setiap bird berhasil melewati dinding

  Cara Bermain :
  - tekan tombol space untuk membuat **Bird** terbang
  - Hindari dinding yang menghalangi **Bird**
  - Raihlah Score setinggi mungkin.

  <h5 align="center"><img src="https://github.com/wiranegara777/komdat-clumsy-bird/blob/master/img/screenshot2.png?raw=true"></h5>


# Pembahasan
[`^ kembali ke atas ^`](#)

**Clumsy Bird** ditulis dalam bahasa pemrograman Framework Javascript yaitu NodeJs, sehingga memiliki beberapa kelebihan :
- Tampilan cukup simple (minimalist) dan *light* saat digunakan.
- Penggunaan memori tidak terlalu besar.
- Design aplikasi yang responsif, sehingga dapat digunakan pada berbagai platforms.
- Gameplay permainan yang cukup sederhana.

Namun **Clumsy-Bird** juga memiliki kelemahan diantaranya:
1. Design level yang sederhana.
    - Clumsy-Bird tidak memiliki level, sehingga user akan terus bermain secara *infinite loop* sampai mati.
    - Clumsy-Bird juga tak memiliki tingkat kesulitan, sehingga game akan berjalan dengan monoton.
2. minimnya fitur dalam game.
    - pengaturan yang dimiliki Clumsy-Bird hanyalah sebuah tombol untuk mengatur *ON/OFF* suara (Mute).
3. tidak ada fitur *Account* untuk menyimpan hasil permainan.
    - Clumsy-Bird hanya bisa dilakukan ketika browser mengakses game, sehingga jika browser di restart. semua progress akan hilang.

# Referensi
[`^ kembali ke atas ^`](#)

1. [About Clumsy-Bird](https://github.com/ellisonleao/clumsy-bird) - Clumsy-Bird
