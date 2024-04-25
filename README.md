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
Comment yang diketik pada saat program dibuat tidak akan ditampikan pada hasil sebuah program. Comment sering kali digunakan untuk menjelaskan sebuah kode sehingga dapat memudahkan ketika ingin mengedit kode tersebut. Untuk membuat comment kita dapat menggunakan `/* */` pada bagian style

```HTML
<!DOCTYPE html>
<html>
<head>
<style>
/* This is a single-line comment */
p {
  color: red;
} 
</style>
</head>
<body>

<p>Hello World!</p>
<p>This paragraph is styled with CSS.</p>
<p>CSS comments are not shown in the output.</p>

</body>
</html>
```
#
### Border
  Dengan CSS Border Properties kita dapat mengatur style, width, dan warna dari elemen border itu sendiri. border style yang dapat kita gunakan seperti:<br>
  `dotted`<br>
  `dashed`<br>
  `solid`<br>
  `double`<br>
  `groove`<br>
  `ridge`<br>
  `inset`<br>
  `outset`<br>
  `none`<br>
  `hidden`<br>

  ```HTML
<!DOCTYPE html>
<html>
<head>
<style>
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
</style>
</head>
<body>

<h2>The border-style Property</h2>
<p>This property specifies what kind of border to display:</p>

<p class="dotted">A dotted border.</p>
<p class="dashed">A dashed border.</p>
<p class="solid">A solid border.</p>
<p class="double">A double border.</p>
<p class="groove">A groove border.</p>
<p class="ridge">A ridge border.</p>
<p class="inset">An inset border.</p>
<p class="outset">An outset border.</p>
<p class="none">No border.</p>
<p class="hidden">A hidden border.</p>
<p class="mix">A mixed border.</p>

</body>
</html>
```
#
### Float
  property `float` digunakan untuk mengatur posisi dan untuk memformat content contohnya gambar. Property float hanya dapat menggunakan 1 perintah. perintah yang dapat digunakan pada `float` adalah <br>
  -`left` yang berarti content tersebut mengambang di bagian kiri <br> 
  -`right` yang berarti content tersebut mengambang di bagian kanan <br>
  -`none`<br>
  -`inherit`
  
  ```HTML
<!DOCTYPE html>
<html>
<head>
<style>
img {
  float: right;
}
</style>
</head>
<body>

<h2>Float Right</h2>

<p>In this example, the image will float to the right in the paragraph, and the text in the paragraph will wrap around the image.</p>

<p><img src="https://th.bing.com/th/id/OIP.9sDxleQnUH7DHq4h2m-qOwHaNK?w=115&h=187&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Pineapple" style="width:170px;height:170px;margin-left:15px;">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas odio, vitae scelerisque enim ligula venenatis dolor. Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Mauris ante ligula, facilisis sed ornare eu, lobortis in odio. Praesent convallis urna a lacus interdum ut hendrerit risus congue. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta. Cras ac leo purus. Mauris quis diam velit.</p>

</body>
</html>
```
#
### Navigation Bar
 Navigation Bar (Navbar) merupakan daftar link. Kita dapat memperbagus tampilan navigation bar pada style sheet. Navigation bar sebelumnya membutuhkan standard html sebagai dasar.

```HTML
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {margin: 0;}

ul.sidenav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 25%;
  background-color: #f1f1f1;
  position: fixed;
  height: 100%;
  overflow: auto;
}

ul.sidenav li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}
 
ul.sidenav li a.active {
  background-color: #4CAF50;
  color: white;
}

ul.sidenav li a:hover:not(.active) {
  background-color: #555;
  color: white;
}

div.content {
  margin-left: 25%;
  padding: 1px 16px;
  height: 1000px;
}

@media screen and (max-width: 900px) {
  ul.sidenav {
    width: 100%;
    height: auto;
    position: relative;
  }
  
  ul.sidenav li a {
    float: left;
    padding: 15px;
  }
  
  div.content {margin-left: 0;}
}

@media screen and (max-width: 400px) {
  ul.sidenav li a {
    text-align: center;
    float: none;
  }
}
</style>
</head>
<body>

<ul class="sidenav">
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

<div class="content">
  <h2>Responsive Sidenav Example</h2>
  <p>This example use media queries to transform the sidenav to a top navigation bar when the screen size is 900px or less.</p>
  <p>We have also added a media query for screens that are 400px or less, which will vertically stack and center the navigation links.</p>
  <p>You will learn more about media queries and responsive web design later in our CSS Tutorial.</p>
  <h3>Resize the browser window to see the effect.</h3>
</div>

</body>
</html>
```

#
### 
