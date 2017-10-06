## Status mahasiswa Amikom Yogyakarta (amk-mhs) - Unofficial v1.1.1

Tool command line untuk melihat status mahasiswa. Status mahasiswa yang biasanya hanya bisa dilihat melalui situs [Amikom.ac.id](http://amikom.ac.id), sekarang bisa diakses melalui command line.

Tool ini unofficial, pengembangnya adalah seorang mahasiswa Amikom Yogyakarta.

### Instalasi di Linux
1. Install Ruby apabila belum ada (namun biasanya di Linux, software Ruby sudah ada)

    Debian dan turunannya: `sudo apt-get install ruby`

    Fedora: `sudo dnf install ruby`

    Arch Linux: `sudo pacman -S ruby`

    Gentoo: `sudo emerge -av dev-lang/ruby`

2. Download `amk-mhs` dengan `wget`, atau klik tombol **Download ZIP** di kanan halaman ini.

    `wget https://github.com/rafeyu/amk-mhs/archive/master.zip`


3. Setelah itu, jalankan perintah:

    `gem install bundler && bundle install`

### Instalasi di Windows

Download file yang ada di [laman release](https://github.com/rafeyu/amk-mhs/releases/tag/v1.1.1). Klik next-next aja, yang terpenting adalah *check* pada bagian "Add application directory to your environmental path".

![amk-mhs windows](https://lh3.googleusercontent.com/-4tnp5tYniYk/VDTttE-e0tI/AAAAAAAADWg/UYza2i360_E/s507/amk-mhs-5.jpg)

#### Status pengembangan di Windows

Saya tak punya lagi mesin Windows untuk menguji `amk-mhs`. Bagi yang ingin mengerjakan dukungan tools ini pada Windows, saya biasa menggunakan [ocra](https://rubygems.org/gems/ocra) untuk mem-build berkas .rb menjadi .exe yang kemudian saya bundel ke dalam installer menggunakan [Inno Setup](http://www.jrsoftware.org/isinfo.php). Skrip untuk membundel dapat dilihat di dir `Inno scrupt build/install.iss`, modpath.iss dipakai untuk menambah kotak dialog *add environmental path*.

### Instalasi di Mac
Download file yang ada di [https://github.com/rafeyu/amk-mhs/archive/master.zip](https://github.com/rafeyu/amk-mhs/archive/master.zip), kemudian jalankan layaknya di Linux.


### Contoh penggunaan
`amk-mhs 11.11.1111` : untuk melihat data mahasiswa

`amk-mhs -h` : untuk melihat halaman help

`amk-mhs 11.11.1111 -f /tmp` : untuk mengunduh foto mahasiswa ke direktori tmp

Matur nuwun
