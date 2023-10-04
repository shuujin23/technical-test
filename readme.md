# Technical Test Backend Developer #

## Algorithm Test ##

1. Buatlah penyelesaian dari soal berikut dengan bahasa pemrograman yg anda kuasai untuk menampilkan N buah bilangan ganjil pertama. Test Case:
<table>
  <tr>
    <td><b>Input</b></td>
    <td><b>Output</b></td>
  </tr>
  <tr>
    <td>N = 4</td>
    <td>1 3 5 7</td>
  </tr>
  <tr>
    <td>N = 2</td>
    <td>1 3</td>
  </tr>
  <tr>
    <td>N = 10</td>
    <td>1 3 5 7 9 11 13 15 17 19</td>
  </tr>
</table>

2. Buat penyelesaian soal berikut dengan bahasa pemrograman yg anda kuasai untuk menentukan sebuah kalimat apakah termasuk palindrome atau bukan. Palindrome adalah adalah suatu kata, frasa, angka, maupun susunan lainnya apabila dibaca dari depan atau belakang bunyinya tetap sama. Test Case:
<table>
  <tr>
    <td><b>Input</b></td>
    <td><b>Output</b></td>
  </tr>
  <tr>
    <td>“A man, a plan, a canal: Panama”</td>
    <td>palindrome</td>
  </tr>
  <tr>
    <td>"race a car"</td>
    <td>Bukan palindrome</td>
  </tr>
</table>

3. Dari kedua table di bawah, buat satu table transaksi baru yg paling efektif untuk menampung data user yg tergabung di satu asosiasi tertentu.
<br> <b>Table User</b>
<br> ![image](https://github.com/shuujin23/technical-test/assets/8181423/4e0f3169-bfb0-49eb-9af0-ab28c5c34673)
<br> <b>Table Asosiasi</b>
<br> ![image](https://github.com/shuujin23/technical-test/assets/8181423/873d6776-21ac-4998-8c6d-19dbd285ff20)

4.	Berdasarkan table yg sudah dibuat di **soal no 3**, buat query untuk menampilkan data user mana terdaftar di asosasi apa. Contoh output:

<div style="padding-left:100px">
  <table>
    <tr>
      <td><b>no</b></td>
      <td><b>username</b></td>
      <td><b>asosiasi_name</b></td>
    </tr>
    <tr>
      <td>1</td>
      <td>User001</td>
      <td>Asosiasi Mahasiswa Kedokteran</td>
    </tr>
    <tr>
      <td>2</td>
      <td>User002</td>
      <td>Asosiasi Mahasiswa Informatika</td>
    </tr>
  </table>
</div>

5.	Berdasarkan table yg sudah dibuat di **soal no 3**, buat query untuk menampilkan berapa jumlah user yg tergabung pada setiap organisasi.
6.	Perhatikan script program berikut: <br> ![image](https://github.com/shuujin23/technical-test/assets/8181423/9adcf355-40ba-4c32-b9af-86ca2df8e813) <br>

   Dari **class Animal** tersebut, buat sebuah class bernama **Cat** yang mewariskan sifat dari **class Animal**. Kemudian print/tampilkan function **walk** dengan cara membuat instance dari class **Cat** tanpa membuat ulang **function walk di class Cat**.

## Project Test ##
Buat API Services, menggunakan C# dengan asp.net core framework. Dengan fungsi-fungsi:
  1. Login
  2. Logout
  3. Create user
  4. Update user
  5. Update password user
  6. Delete user
  7. Get list user dengan filter email
<br>
Gunakan EF core untuk ORM nya, coba buat projectnya menggunakan prinsip SOLID dan clean code semaksimal mungkin
<br>
<br>
Kumpulkan hasilnya dalam bentuk <b>compressed file</b>, boleh dipisah per nomor atau boleh digabung. Khusus untuk soal project, silakan <b>upload ke git Anda</b>, kemudian <b>kirimkan link projectnya saja</b>, jangan lupa permissionnya di setting ke public agar kami bisa clone. Semua file tersebut dikirimkan ke email <b>dev@anargya.co.id</b> maksimal <b>H+2 pukul 23.59 WIB sejak submission ini dikirim</b>. Jika ada pertanyaan silakan di posting di bagian issue. Terima kasih
