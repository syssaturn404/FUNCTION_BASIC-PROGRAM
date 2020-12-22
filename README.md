 <h2><a id="user-content-octocat-fork-and-eight_pointed_black_star-star-this-repo" class="anchor" aria-hidden="true" href="https://github.com/syssaturn404/CLanguage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><img class="emoji" title="Python Programming" alt="design-by-syssaturn404" src="https://github.githubassets.com/images/icons/emoji/octocat.png" height="20" width="20" align="absmiddle"> Syssaturn404 Repo <g-emoji class="g-emoji" alias="eight_pointed_black_star" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2734.png">💫</g-emoji></h2>
<p align="center">
  
 ```
  ___  ___  _______   ___       ___       ________     
|\  \|\  \|\  ___ \ |\  \     |\  \     |\   __  \    
\ \  \\\  \ \   __/|\ \  \    \ \  \    \ \  \|\  \   
  \ \   __  \ \  \_|/_\ \  \    \ \  \    \ \  \\\  \  
   \ \  \ \  \ \  \_|\ \ \  \____\ \  \____\ \  \\\  \ 
    \ \__\ \__\ \_______\ \_______\ \_______\ \_______\
     \|__|\|__|\|_______|\|_______|\|_______|\|_______|
     
>> Fungsi Pada Pemrograman Dasar

Pengertian fungsi
Fungsi / Function adalah satu blok kode yang melakukan tugas tertentu atau satu blok instruksi
yang di eksekusi ketika dipanggil dari bagian lain dalam suatu program.

Tujuan pembuatan fungsi adalah :

  - Memudahkan dalam pembuatan program.
  - Menghemat ukuran program.
  - Keuntungan memakai fungsi :
  - Menguraikan tugas pemrograman rumit menjadi langkah-langkah yang lebih sederhana atau kecil.
  - Mengurangi duplikasi kode (kode yang sama ditulis berulang-ulang) dalam program.
  - Dapat menggunakan kode yang ditulis dalam berbagai program yang berbeda.
  - Memecah program besar menjadi kecil sehingga dapat dikerjakan oleh programmer-programmer
  atau dipecah menjadi beberapa tahap sehingga mempermudah pengerjaan dalam sebuah projek
  Menyembunyikan informasi dari user sehingga mencegah adanya perbuatan iseng seperti 
  memodifikasi atau mengubah program yang kita buat
  Meningkatkan kemampuan pelacakan kesalahan, jika terjadi suatu kesalahan kita tinggal mencari fungsi
  yang bersangkutan saja dan tak perlu mencari kesalahan tersebut di seluruh program.

>> Bentuk umum Sebuah fungsi adalah sebagai berikut :

  - Tipedata namafungsi(daftarparameter).

>> Deklarasi & Definisi
Baik data maupun function / fungsi harus dideklarasikan. Data perlu dideklarasikan agar compiler tahu berapa
byte memori yang harus disediakan untuk data yang bersangkutan,
sedangkan fungsi perlu dideklarasikan agar compiler dapat memeriksa ketepatan pemanggilan fungsi yang bersangkutan.
Deklarasi dan definisi adalah langkah awal dalam setiap penulisan program tidakterkecuali dalam bahasa C++.

>> Parameter
Nilai dalam suatu subprogram FreePascal sifatnya adalah lokal, artinya hanya dapat digunakan pada modul 
atau unit yang bersangkutan saja
tidak dapat digunakan pada modul atau unit program yang lainnya. 
Parameter adalah data masukan untuk subprogram yang nantinya akan diproses lebih lanjut dalam subprogram tersebut.
Dalam Pascal, dikenal dua macam parameter, Yaitu :

  - parameter nilai (value parameter), dan
  - parameter referensi (reference parameter).
  - fungsi dalam Bahasa pemrograman C++, yaitu:
  - parameter masukan.
  - parameter keluaran.
  - parameter gabungan antara masukan dan keluaran.

>> Nilai balik
Fungsi dengan nilai balik adalah suatu fungsi yang dapat mengembalikan suatu nilai ke dalam fungsi utama.
Dalam membuat fungsi, harus didefinisikan tipe data dari niali yang akan dikembalikan. 
Sebelum dapat memanggil suatu fungsi, kita harus mendeklarasikannya terlebih dahulu. 
Pendeklarasian fungsi dengan nilai balik diawali dengan tipe data yang akan dikembalikan nilainya.
Kemudian diikuti dengan nama fungsi dan daftar perameternya.

>> Rekrusif
Rekursif adalah suatu proses yang memanggil dirinya sendiri yang biasanya dilakukan
oleh fungsi atau prosedur pada pemrograman prosedural
seperti contohnya bahasa pemrograman C, atau metode pada pemrograman berorientasi objek seperti C++ atau Java. 
Rekursif akan terus berjalan sampai kondisi berhenti terpenuhi,
oleh karena itu dalam sebuah rekursi perlu adanya blok-blok kode sebagai berikut :

 - Basis
Basis merupakan kode yang menjadi titik berhenti dari sebuah proses rekursi karena proses rekursi
akan terus berjalan berputar memanggil dirinya sendiri sampai sebuah kondisi basis terpenuhi.
Oleh karena itu basis sangat penting dalam sebuah proses rekursi
karena tanpa basis sebuah proses rekursi akan terus dijalankan tanpa henti.

- Rekursi
Rekursi merupakan kode dalam hal ini sebuah blok program (prosedur, fungsi atau metode) memanggil dirinya sendiri
misalnya ada sebuah fungsi hitung hasil faktorial, bahwa di dalamnya blok kode fungsi itu memanggil dirinya sendiri.

>> Pengertian Pointer
Pointer merupakan sebuah variabel yang berisi alamat dari variabel lain. 
Suatu pointer dimaksudkan untuk menunjukan ke suatu alamat memori sehingga 
alamat dari suatu variabel dapat diketahui dengan mudah.
Arti pointer dalam bahasa sehari-hari adalah petunjuk atau bisa di bilang penentu
atau pointer secara sederhana bisa diartikan sebagai tipe data yang nilainya 
mengarah pada nilai yang terdapat pada sebuah area memori (alamat memori). 
Namun dalam bahasa C, Pointer bisa berfungsi sebagai variabel array berarti pointer
sebagai penunjuk elemen array ke-0 dalam variabel C.

>> Fungsi Pointer
Fungsi Pointer yang utama adalah untuk menyimpan alamat memori dari sebuah variable. 
Selain menyimpan alamat dari sebuah variable, Pointer juga berfungsi untuk menyimpan alamat memori dari sebuah fungsi.

>> Modularisasi
konsep-konsep pemrograman adalah kemampuan untuk group beberapa baris kode
ke dalam sebuah unit yang dapat dimasukan dalam program kami.
Yang asli untuk kata ini adalah sub-program. Nama lain meliputi: 
makro, sub-rutin, prosedur, modul dan fungsi.
Fungsi-fungsi penting karena membolehkan kita untuk mengambil program besar dan rumit
untuk membagi mereka menjadi potongan-potongan kecil diatur. 
Karena fungsi yang lebih kecil adalah bagian program secara keseluruhan
Umumnya fungsi jatuh kedalam dua kategori.

>> Control program
Fungsinya hanya di gunakan untuk membagi dan sub control program.
fungsi ini adalah fungsi unik yang di tulis. Lain-lain program dapat 
menggunakan fungsi serupa bahkan fungsi dengan nama yang sama
tetapi isi dari fungsi hampir selalu berbeda.

>> Tugas Spesifik
Fungsinya dirancang untuk digunakn dengan beberapa program.
fungsi ini melakukan tugas tertentu dan dengan itu bisa digunakan dalam berbagai
program karena program lain juga perlu untuk melakukan tugas tertentu.
spesifik tugas fungsi kadang-kadang disebut sebagai blok bangunan.
karena mereka sudah di uji dan oke.
Kita dapat menggunakannya dengan keyakinan lebih efisien untuk menulis program yang besar.
Program utama harus menetapkan adanya fungsi yang di gunakan dalam program ini.
tergantung pada bahasa pemrograman. Terimakasih sudah berkunjung
```
