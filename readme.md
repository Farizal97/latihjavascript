## everything is object

Ada 2 Type Data 

Primitive
---------
- number
- string
- boolean
- undifined
- null

Object
---------
- Array
- Function
- Object
- Date

Object Oriented Progamming (OOP)
--------------------------------
- Sesama object saling 
- menggunakan store data,structure aplikasi ke dalam module dan keep code clean 

contoh object :

var toyota = {
    nama : 'avanza',
    tahun:'2000',
    warna:'putih'
}

var suzuki = {
    nama : 'apv',
    tahun:'2005',
    warna:'biru'
}

var honda = {
    nama : 'brio',
    tahun:'2015',
    warna:'merah'
}

Classs
----------------------

car = {
 nama 
 tahun
 pabrik
 dsb
}

Constructor atau Prototype
----------------------------

- di beberapa language sering disebut class,didalam javascript sering disebut Constructor atau Prototype

- constructor bisa membuat banyak instance contohnya constructure car bisa membuat object baru misalnya toyota,suzuki,honda,dsb

Inheritance (Turunan)
----------------------

 apa turunan dari car ?
 
 sport = {
 type
 tahun
 mesin
 ukuran
 }
 
 
 family = {
 type
 tahun
 mesin
 ukuran
 }
 
 car = {
    nama:'Mitsubishi'
    tahun:2010
    pabrik:'Sunter'
    jenis:barang = {
    type:'Solar',
    karoseri:'aduhai' ,
    mesin:2000,
    kapasitas: 10 ton
    }
 }
 
 **Constructur function**
 
 	function(){ ... }
 
Kenapa kita membutuhkan constructor function dan pada saat apa?

Karena kita perlu membuat object object baru, pada saat kita membutuh kan new instance - new instance maka kita membutuhkan function constructor. Instance atau copy dari blue print dari sebuah object/function/class.

	function Motor(){ return object; }

**Membuat constructor function**	

* function nama function gunakan huruf besar.
* lewatkan (pass) parameter.
* akses parameter dengan **this**.
* gunakan new keyword untuk invoke/memanggil constructor function.
* Menambahkan value untuk parameter diatas sebagai argumen.
* Gunakan variable invoke untuk menyimpan new object tsb.
* Dengan demikian anda bisa memulai membuat instance baru dengan berbeda value, Instance (baca mengcopy).
* Tampilkan pada console
