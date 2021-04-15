# Lab3Web
<h1> Langkah-langkah Praktikum </h1>

<p>
<ol>
  <li><b>Membuat Dokumen HTML</b><br>
  Buatlah dokumen HTML dengan nama "lab3_list.html" seperti berikut.

![Screenshot_79](https://user-images.githubusercontent.com/24362384/114828502-2d265500-9df4-11eb-8b5c-ea7a63db9602.png)

  <li><b>Membuat Ordered List</b><br>
  Kemudian tambahkan kode untuk membuat <i>Ordered List</i> sebagai berikut.
  
  ![Screenshot_80](https://user-images.githubusercontent.com/24362384/114828937-afaf1480-9df4-11eb-8280-9ce61e03b300.png)

  <li><b>Membuat Unordered List</b><br>
  Kemudian tambahkan kode untuk membuat <i>Unordered List</i> sebagai berikut.
  
  ![Screenshot_81](https://user-images.githubusercontent.com/24362384/114829696-9a86b580-9df5-11eb-9609-57212271f6b1.png)
    
  <li><b>Membuat Description List</b><br>
  Kemudian tambahkan kode untuk membuat <i>Description List</i> sebagai berikut.

![Screenshot_82](https://user-images.githubusercontent.com/24362384/114830371-52b45e00-9df6-11eb-8b8b-2365edd882e7.png)

  <li><b>Membuat Tabel</b><br>
  Buatlah file html baru dengan nama <b>lab3_tabel.html</b> seperti berikut.
  
  ![Screenshot_83](https://user-images.githubusercontent.com/24362384/114830807-d53d1d80-9df6-11eb-893d-ba6a7cf4024b.png)

  Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut.
  
 ![Screenshot_84](https://user-images.githubusercontent.com/24362384/114831720-e76b8b80-9df7-11eb-8cce-febafe60aa53.png)

  <b>Mengatur Margin dan Padding</b></br>
  Untuk mengatur margin(jarak tepi) dan padding(spasi) pada cell data, tambahkan atribut <b>cellpadding</b> dan <b>cellspacing</b> pada tag <i>table</i>.
  
```html
<table border="1" cellpadding="4" cellspacing="0">
```
![Screenshot_85](https://user-images.githubusercontent.com/24362384/114832684-f69f0900-9df8-11eb-8e61-55715af43b98.png)

  <b>Menggabungkan Sel Data</b></br>
  Untuk Menggabungkan sel data, gunakan atribut <i>rowspan</i> dan <i>colspan</i>. Atribut <i>rowspan</i> berfungsi untuk menggabungkan baris secara vertikal dan <i>colspan</i> untuk menggabungkan kolom secara horizontal. Tambahan kode untuk menggabungkan baris atau kolom seperti berikut.
  
  
</li></ol>
</p>


<h3> Pertanyaan dan Tugas </h3>
<p>
<ol>
  <li> Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada <i>CSS Cheat Sheet</i> yang diberikan pada file terpisah dari modul ini.
  <li> Apa perbedaan pendeklarasian CSS elemen <b>h1 {...}</b> dengan <b>#intro h1 {...}?</b> berikan penjelasannya!
  <li> Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
  <li> Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikut penjelasan dan contohnya! (&lt;p id="paragraf-1" class="text-paragraf"&gt;)
  </li></ol>

<h3> Jawaban </h3>
<ol>
  <li> Berikut Hasil eksperimen dalam mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada <i>CSS Cheat Sheet</i>.
    
![Screenshot_58](https://user-images.githubusercontent.com/24362384/114273478-5e91d000-9a44-11eb-88be-48d2f2713f39.png)

  <li> Perbedaan antara pendeklarasian CSS elemen <b>h1 {...}</b> dengan <b>#Intro h1 {...}?</b> adalah pada penggunaan tanda "#", dalam penggunaan "#" disebut juga ID Selector, ID Selector digunakan untuk menyeleksi elemen berdasarkan ID tertentu. Contoh di dalam css: #intro h1 {text-align: left}. Contoh tersebut menyeleksi element yang memiliki attribute ID dengan value "intro h1" agar tulisannya rata kiri didalam html. Dengan catatan sebuah halaman atau dokumen tidak boleh terdapat lebih dari satu <i>id</i> dengan value yang sama.
  <li> Deklarasi yang lebih dulu ditampilkan pada browser saat menggunakan deklarasi CSS secara internal, eksternal, dan inline adalah deklarasi CSS secara inline. karena inline merupakan deklarasi yang ditulis langsung pada atribut elemen HTML.<br>
  Contoh jika hanya menggunakan deklarasi eksternal:

![Screenshot_54](https://user-images.githubusercontent.com/24362384/114263408-769b2c80-9a0f-11eb-8bdc-a1920e8e26a6.png)

  Contoh jika menggunakan deklarasi internal dan eksternal:
  
![Screenshot_55](https://user-images.githubusercontent.com/24362384/114263419-8a469300-9a0f-11eb-85f3-9f6f173f4316.png)

  Contoh jika menggunakan deklarasi internal, eksternal, dan inline:
  
![Screenshot_56](https://user-images.githubusercontent.com/24362384/114263431-992d4580-9a0f-11eb-9fff-02f0ee6211c0.png)

  <li>Perbedaan dari selector class dan id adalah selector class di panggil pada css dengan menggunakan tanda titik ".", dan id di panggil pada css menggunakan tanda pagar "#". Lalu perbedaan lainnya adalah selector class dapat di berikan pada banyak element html dan dapat di panggil sekaligus, sedangkan id hanya dapat bekerja pada satu element saja.
  Jika nilai pada selector id dan class sama, maka yang akan muncul adalah nilai pada selector id.
  Contohnya :
  
  ![Screenshot_57](https://user-images.githubusercontent.com/24362384/114273401-12df2680-9a44-11eb-9593-92008c649f4f.png)


  
</li></ol></p>

