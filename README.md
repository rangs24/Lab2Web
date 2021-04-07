# **PRAKTIKUM 2**
## **Membuat Dokumen HTML**
### **Membuat dokumen HTML dengan code yang sudah disiapkan**

Tampilan pada VSCode

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss1.png)

Tampilan pada browser

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss2.png)

## **Mendeklarasikan CSS Internal**
### **Menambahkan deklarasi CSS Internal pada bagian head dokumen**

Tampilan pada VSCode

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss3.png)

Tampilan pada browser

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss4.png)

## **Menambahkan Inline CSS**
### **Menambahkan deklarasi inline CSS pada tag <p>**

Tampilan pada VSCode

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss5.png)

Tampilan pada browser

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss6.png)

## **Membuat CSS Eksternal**
### **Buat file baru dengan nama style_eksternal.css dan buatlah deklarasi CSS berikut**
![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss7.png)
### **Kemudian tambahkan tag <link> untuk merujuk file CSS yang sudah dibuat pada bagian <head>**
![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss8.png)

Tampilan pada browser

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss9.png)

## **Menambahkan CSS Seelector**
### **Menambahkan CSS Selector menggunakan ID dan Class Selector pada file style_eksternal.css berikut**

Tampilan pada VSCode

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss10.png)

Tampilan pada browser

![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss11.png)

#Jawaban Tugas
1. Sudah dilakukan
2. h1 {...} adalah **Elemen selector** sedangkan #intro h1 adalah **ID Selector** , Elemen Selector ini akan memilih elemen berdasarkan nama tag, sedangkan ID Selector r dideklarasikan dengan menambahkan tanda # sebelum nama id yang akan digunakan.
3. Deklarasi CSS Internal yang akan ditampilkan, Karena ada dua sifat CSS yaitu internal dan eksternal.Jika internal yang dipilih, maka skrip itu dimasukkan secara langsung ke halaman website yang akan didesain. Kalau halaman web yang lain akan didesain dengan model yang sama, maka skrip CSS itu harus dimasukkan lagi ke dalam halaman web yang lain itu.
![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss12.png)
![ScreenshotTugas](https://github.com/rangs24/Lab2Web/blob/master/ss13.png)
4. Aturan prioritas CSS yaitu : 
	- CSS yang dimasukkan dengan metode Inline Style yaitu style yang langsung melekat pada tag dalam tag <body> akan diprioritaskan terlebih dahulu
	- CSS yang dimasukkan denan metode Internal Style Sheet yaitu style yang dideklarasikan pada awal halaman di antara tag <style> dan </style> akan diprioritaskan selanjutnya
	- CSS yang dimasukkan menggunakan metode External Style Sheet ,yaitu style yang dideklarasikan pada sebuah file terpisah yang berekstensi .css akan diprioritaskan terakhir.
Contoh :

Ketikkan script berikut dan simpan dengan nama prioritas.css 

h1 {color: blue;}

Lalu buatlah file HTML nya dan simpan dengan nama cssprioritas.html



<!DOCTYPE HTML>
<html>
<head>
<title>PRIORITAS</title>
<link rel="stylesheet" type="text/css" href="prioritas.css">
<style type="text/css">
	h1 {color:red;}
</style>
</head>

<body>
<h1>Teks ini berwarna apa ?</h1>
</body>
</html>

Pada contoh di atas,tag <h1> berusaha untuk diubah warnanya dengan menggunakan CSS dari file prioritas.css yang ingin mengganti warna menjadi biru.Kedua dengan menggunakan kode CSS yang ada diantara tag <style> dan </style> dengan warna merah.Ketika ditampilkan di browser,maka warna merah yang akan ditampilkan
