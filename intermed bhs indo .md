Dokumen ini berisi semua latihan tingkat menengah. Jika Anda menemukan kesalahan atau bug atau sesuatu yang dapat ditulis dengan lebih baik, silakan hubungi saya. Terima kasih.

== Latihan 006

Tulislah sebuah program yang menghitung dan mencetak nilai sesuai dengan rumus yang diberikan:

Q = Akar pangkat dua dari [(2 * C * D)/H]

Berikut ini adalah nilai tetap dari C dan H:

- C adalah 50. H adalah 30.
- D adalah variabel yang nilainya harus dimasukkan ke dalam program Anda dalam urutan yang dipisahkan dengan koma.

Contoh:

Mari kita asumsikan urutan input yang dipisahkan koma berikut ini diberikan ke program: 100,150,180

Output dari program tersebut seharusnya adalah: 18,22,24

=== Petunjuk:

- gunakan `math.Sqrt` untuk akar kuadrat
- gunakan `math.Round` untuk membulatkan operasi float

== Solusi:

link:006/exercise006.go[]

== Latihan 007

Tulislah sebuah program yang mengambil 2 digit, X,Y sebagai masukan dan menghasilkan sebuah larik 2 dimensi. Nilai elemen pada baris ke-i dan kolom ke-j dari larik tersebut haruslah i*j.
Catatan: i = 0,1.., X-1; j = 0,1, ¡Y-1.

Contoh

Misalkan input berikut diberikan ke program: 3,5

Maka, output dari program tersebut seharusnya adalah:
[[0, 0, 0, 0, 0], [0, 1, 2, 3, 4], [0, 2, 4, 6, 8]]

=== Petunjuk:
Catatan: Jika data input diberikan ke pertanyaan, ini harus diasumsikan sebagai input konsol dalam bentuk yang dipisahkan dengan koma.

=== Solusi:

link:007/exercise007.go[]

== Latihan 008

Tulislah sebuah program yang menerima urutan kata yang dipisahkan koma sebagai input dan mencetak kata-kata tersebut dalam urutan yang dipisahkan koma setelah mengurutkannya menurut abjad.

Misalkan masukan berikut diberikan ke program:
    
    tanpa, halo, tas, dunia

Maka, keluarannya seharusnya adalah:

    tas,halo,tanpa,dunia

=== Petunjuk:

Jika data input diberikan ke pertanyaan, itu harus diasumsikan sebagai input konsol.

=== Solusi:

link:008/exercise008.go[]


== Latihan 009

Tulislah sebuah program yang menerima urutan baris sebagai input dan mencetak baris-baris tersebut 
setelah membuat semua karakter dalam kalimat menjadi huruf besar.

Misalkan masukan berikut diberikan ke program:

    Halo dunia
    Latihan membuat sempurna

Maka, keluarannya seharusnya adalah:

    HELLO DUNIA
    LATIHAN MEMBUAT SEMPURNA

=== Petunjuk
Jika data input diberikan ke pertanyaan, itu harus diasumsikan sebagai input konsol.

=== Solusi:

link:009/exercise009.go[]


== Latihan 009

Tulislah sebuah program yang menerima sebuah urutan kata-kata yang dipisahkan oleh spasi sebagai input dan mencetak kata-kata tersebut setelah menghapus semua kata yang sama dan mengurutkannya secara alfanumerik.

Misalkan input berikut diberikan ke program:

    halo dunia dan latihan membuat sempurna dan halo dunia lagi

Maka, keluarannya seharusnya adalah:

    lagi dan halo dunia latihan membuat sempurna

=== Petunjuk

Dalam kasus data input yang diberikan ke pertanyaan, harus diasumsikan sebagai input konsol.
Kami menggunakan set container untuk menghapus data yang terduplikasi secara otomatis dan kemudian menggunakan sorted() untuk mengurutkan data.

== Solusi:

link:010/exercise010.go[]


== Latihan 011

Tulislah sebuah program yang menerima sebuah deretan bilangan biner 4 digit yang dipisahkan koma sebagai masukannya dan kemudian periksa apakah bilangan-bilangan tersebut habis dibagi 5 atau tidak. Bilangan-bilangan yang habis dibagi 5 akan dicetak dalam urutan yang dipisahkan koma.

Contoh
    0100,0011,1010,1001

Maka outputnya seharusnya adalah:
    1010

Catatan: Asumsikan data dimasukkan melalui konsol.

=== Petunjuk:

Jika data input diberikan ke pertanyaan, itu harus diasumsikan sebagai input konsol.

=== Solusi:

link:011/exercise011.go[]


== Latihan 012

Tulislah sebuah program yang akan menemukan semua angka antara 100 dan 300 (termasuk keduanya) sehingga setiap digit angka tersebut adalah angka genap. Angka-angka yang diperoleh harus dicetak dalam urutan yang dipisahkan dengan koma pada satu baris.

=== Petunjuk:
Jika ada data masukan yang diberikan ke soal, data tersebut harus diasumsikan sebagai masukan konsol.


=== Solusi:

link:012/exercise012.go[]


== Latihan 013

Tulislah sebuah program yang menerima sebuah kalimat dan menghitung jumlah huruf dan angka. 

Misalkan input berikut diberikan ke program:

    halo dunia! 123

Maka, keluarannya seharusnya adalah:

    HURUF 10
    DIGIT 3

=== Petunjuk:
 Dalam hal data input yang diberikan ke pertanyaan, harus diasumsikan sebagai input konsol.

=== Solusi:

link:013/exercise013.go[]