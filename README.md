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
