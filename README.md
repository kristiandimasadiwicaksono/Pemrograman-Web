# Praktikum Pemrograman Web 1

## Materi
Pada Praktikum ini dapat dipelajari berbagai materi seperti:
  - HTML
  - CSS
  - Javascript

## HTML

### -Heading
  Heading didefinisikan dari tag `<h1>` hingga tag `<h6>`. tag `<h1>` merupakan tag yang biasanya digunakan sebagai judul. semakin tinggi angka yang dipilih untuk heading, maka hasil tulisannya akan semakin kecil.

```HTML
<!DOCTYPE html>
<html>
<body>

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

</body>
</html>
```
#

### -Classes
  Atribut `class` pada HTML digunakan untuk menentukan `class` untuk sebuah elemen HTML. Beberapa elemen HTML dapat berbagi `class` yang sama. Atribut `class` sering digunakan untuk menunjuk ke nama `class` dalam style sheet. Ini juga dapat digunakan oleh JavaScript untuk mengakses dan mengubah elemen dengan nama `class` tertentu.

```HTML
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
<h2>London</h2>
<p>London is the capital of England.</p>
</div> 

<div class="city">
<h2>Paris</h2>
<p>Paris is the capital of France.</p>
</div>

<div class="city">
<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html>
```
#

### -Colors
  Warna HTML ditentukan dengan nama warna yang telah ditetapkan, atau dengan nilai RGB, HEX, HSL, RGBA, atau HSLA. Warna yang dapat dirubah seperti semua huruf/kalimat maupun background.

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>warna</title>
</head>
<body>
    <h1 style="background-color:black;">hitam</h1>
    <h1 style="background-color:pink;">pink</h1>
    <h1 style="background-color:lightblue;">BiruMuda</h1>
    <h1 style="background-color:gold;">Emas</h1>
    <h1 style="background-color:red;">Merah</h1>
    <h1 style="background-color:purple;">Ungu</h1>
    <h1 style="background-color:gray;">Abu-abu</h1>
    <h1 style="background-color:green;">Hijau</h1>

<p style="background-color:red;">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nostrum excepturi sint corrupti? Architecto rerum atque sed! Expedita totam sed quibusdam.</p>

<h3 style="color: blue;">Warna text</h3>
<p style="color: red;">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Odit ipsum sequi sint, perferendis explicabo placeat eaque at optio eligendi. Fugiat.</p>

    <h1 style="border: 3px solid red;">Hello World</h1>

<h1 style="border: 4px solid green;">Hello World</h1>

<h1 style="border: 5px solid blueviolet;">Hello World</h1>


<p>Memiliki warna yang sama dengan biru "Blue" tetapi lebih tua:</p>

<h1 style="background-color:rgb(0, 31, 117);">rgb(0, 31, 117)</h1>
<h1 style="background-color:#0017a9;">#0017a9</h1>
<h1 style="background-color:hsl(229, 94%, 48%);">hsl(229, 94%, 48%)</h1>

<p>Memilika warna yang sama dengan merah "Red", tetapi lebih muda:</p>
<h1 style="background-color:rgba(218, 59, 59, 0.945);">rgba(218, 59, 59, 0.945)</h1>
<h1 style="background-color:hsl(0, 88%, 62%);">hsla(0, 88%, 62%)</h1>

<p>setiap warna memiliki keterangan dan kegelapan nya masing masing</p>
</body>
</html>
```
#
## -Id
  Atribut `id` HTML digunakan untuk menentukan id unik untuk sebuah elemen HTML. Kita tidak dapat memiliki lebih dari satu elemen dengan id yang sama di dalam dokumen HTML.
  ```HTML
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
} 
</style>
</head>
<body>

<h2>The id Attribute</h2>
<p>Use CSS to style an element with the id "myHeader":</p>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```
#
## CSS
### Comments
