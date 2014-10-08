## Status mahasiswa Amikom Yogyakarta (amk-mhs) - Unofficial v1.1.1

Tool command line untuk melihat status mahasiswa. Status mahasiswa yang biasanya hanya bisa dilihat melalui situs [Amikom.ac.id](http://amikom.ac.id), sekarang bisa diakses melalui command line.

Tool ini unofficial, pengembangnya adalah seorang mahasiswa Amikom Yogyakarta.

### Instalasi di Linux
1. Install Ruby apabila belum ada (namun biasanya di Linux, software Ruby sudah ada)

    Debian dan turunannya: `sudo apt-get install ruby`

    Fedora: `sudo yum install ruby`

    Arch Linux: `sudo pacman -S ruby`

2. Download `amk-mhs` dengan `wget`, atau klik tombol **Download ZIP** di kanan halaman ini.

    `wget https://github.com/rafeyu/amk-mhs/archive/master.zip`


3. Extract file master.zip, kemudian setting `chmod` nya

    `chmod +x amk-mhs`


4. Setelah itu, jalankan perintah:

    `gem install bundler && bundle install`

### Instalasi di Windows
Download file yang ada di [Sourceforge](http://sourceforge.net/projects/amk-mhs/files/Windows/v1.1.1/amk-mhs-setup.exe/download). Klik next-next aja, yang terpenting adalah *check* pada bagian "Add application directory to your environmental path".

![amk-mhs windows](https://www.dropbox.com/s/430skmvdo1eq6oj/amk-mhs-5.jpg)

### Instalasi di Mac
Download file yang ada di [https://github.com/rafeyu/amk-mhs/archive/master.zip](https://github.com/rafeyu/amk-mhs/archive/master.zip), kemudian jalankan layaknya di Linux.


### Contoh penggunaan
`amk-mhs 11.12.5369` : untuk melihat data mahasiswa

`amk-mhs -h` : untuk melihat halaman help

`amk-mhs 11.12.5369 -f /tmp` : untuk mengunduh foto mahasiswa ke direktori tmp

Matur nuwun
