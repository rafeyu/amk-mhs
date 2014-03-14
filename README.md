## Status mahasiswa Amikom Yogyakarta - Unofficial v1.0

Tool command line untuk melihat status mahasiswa. Status mahasiswa yang biasanya hanya bisa dilihat melalui situs [Amikom.ac.id](http://amikom.ac.id), sekarang bisa diakses melalui command line.

Tool ini unofficial, pengembangnya adalah seorang mahasiswa Amikom Yogyakarta.

### Instalasi di Linux
1. Install Ruby apabila belum ada (namun biasanya di Linux, software Ruby sudah ada)

    `sudo apt-get install ruby`

2. Download `amk-mhs` dengan `wget`, atau klik tombol **Download ZIP** di kanan halaman ini.

    `wget https://github.com/rafeyu/amk-mhs/archive/master.zip`


Extract file master.zip, kemudian setting `chmod` nya

`chmod +x amk-mhs`

Setelah itu, jalankan perintah:

`gem install bundler && bundle install`

### Instalasi di Windows
Download file yang ada di ~~http://ramdziana.my.id/file/amk-mhs.exe~~ **[Dropbox](https://www.dropbox.com/s/91aame9lw7ul48f/amk-mhs.exe)**, kemudian jalankan dengan command prompt.

### Instalasi di Mac
Download file yang ada di [https://github.com/rafeyu/amk-mhs/archive/master.zip](https://github.com/rafeyu/amk-mhs/archive/master.zip), kemudian jalankan layaknya di Linux.


### Contoh penggunaan
`amk-mhs 11.12.5369` : untuk melihat data mahasiswa

`amk-mhs -h` : untuk melihat halaman help


Matur nuwun