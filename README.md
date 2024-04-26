# Praktikum Pemrograman Web 1

## Materi
Pada Praktikum ini dapat dipelajari berbagai materi seperti:
  - HTML
  - CSS
  - Javascript

## HTML

### Heading
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Heading.png)
#

### Classes
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Classes.png)
#

### Colors
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Colors.png)
#
## Id
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Id.png)
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Comment.png)
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Border.png)
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/float.png)
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
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Navbar.png)
#
### Form
  Form biasanya digunakan untuk mengisi data kemudian disimpan pada komputer. Tampilan form dapat kita perbagus menggunakan CSS contohnya seperti program dibawah ini.
  
```HTML
<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

label {
  padding: 12px 12px 12px 0;
  display: inline-block;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row::after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
</head>
<body>

<h2>Responsive Form</h2>
<p>Resize the browser window to see the effect. When the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other.</p>

<div class="container">
  <form action="/action_page.php">
  <div class="row">
    <div class="col-25">
      <label for="fname">First Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" placeholder="Your name..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Last Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" placeholder="Your last name..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="country">Country</label>
    </div>
    <div class="col-75">
      <select id="country" name="country">
        <option value="australia">Australia</option>
        <option value="canada">Canada</option>
        <option value="usa">USA</option>
      </select>
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="subject">Subject</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
    </div>
  </div>
  <br>
  <div class="row">
    <input type="submit" value="Submit">
  </div>
  </form>
</div>

</body>
</html>
```
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/forms.png)
#
### Opacity
  property `opacity` digunakan untuk mengatur tingkat transparansi sebuah objek
  
```HTML
<!DOCTYPE html>
<html>
<head>
<style>
div {
  background-color: #04AA6D;
  padding: 10px;
}

div.first {
  opacity: 0.1;
}

div.second {
  opacity: 0.3;
}

div.third {
  opacity: 0.6;
}
</style>
</head>
<body>

<h1>Transparent Box</h1>
<p>When using the opacity property to add transparency to the background of an element, all of its child elements become transparent as well. This can make the text inside a fully transparent element hard to read:</p>

<div class="first"><p>opacity 0.1</p></div>
<div class="second"><p>opacity 0.3</p></div>
<div class="third"><p>opacity 0.6</p></div>
<div><p>opacity 1 (default)</p></div>

</body>
</html>
```
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Opacity.png)
#
## Javascript

### Prompt
  Prompt pada javascript akan memunculkan dialog box untuk diinput oleh user. metode prompt akan mengembalikan nilai yang diinputkan oleh user ketika user menekan tombol "OK"

  ```HTML
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Prompt</h2>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  let text;
  let person = prompt("Please enter your name:", "Harry Potter");
  if (person == null || person == "") {
    text = "User cancelled the prompt.";
  } else {
    text = "Hello " + person + "! How are you today?";
  }
  document.getElementById("demo").innerHTML = text;
}
</script>

</body>
</html>
```
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Prompt.png)
#
### Date
  Di dalam javascript kita juga dapat membuat waktu secara realtime menggunakan object date

  ```HTML
<!DOCTYPE html>
<html>
<body>

<h1>JavaScript Dates</h1>
<h2>Using new Date()</h2>
<p>new Date() without arguments, creates a date object with the current date and time:</p>

<p id="demo"></p>

<script>
const d = new Date();
document.getElementById("demo").innerHTML = d;
</script>

</body>
</html>
```
![App Screenshot]https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Waktu.png
#
### Break
  Break digunakan pada javascript untuk menghentikan perintah baik dari perintah loop maupun switch statement jika sebuah kondisi sudah terpenuhi.
  ```HTML
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Loops</h2>

<p>A loop with a <b>break</b> statement.</p>

<p id="demo"></p>

<script>
let text = "";
for (let i = 0; i < 10; i++) {
  if (i === 3) { break; }
  text += "The number is " + i + "<br>";
}

document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>
```
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Break.png)
#
### Function
  Function adalah perintah yang dapat kita gunakan kembali untuk menyelesaikan tugas tertentui. didalam function terdapat beberapa perintah yang dapat digabungkan.

  ```HTML
<!DOCTYPE html>
<html>
<body>
<h1>JavaScript Functions</h1>

<p>Call a function which performs a calculation and returns the result:</p>

<p id="demo"></p>

<script>
function myFunction(p1, p2) {
  return p1 * p2;
}

let result = myFunction(4, 3);
document.getElementById("demo").innerHTML = result;
</script>

</body>
</html>
```
![App Screenshot](https://github.com/kristiandimasadiwicaksono/Pemrograman-Web/blob/main/Gambar/Functions.png)
