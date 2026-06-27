<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>সুখাদ্য | Sukhaddo</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#faf7f2;
}

header{
background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),url("images/hero.jpg");
background-size:cover;
background-position:center;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

h1{
font-size:60px;
}

p{
font-size:22px;
margin:20px 0;
}

.btn{
display:inline-block;
padding:15px 35px;
background:#ff6600;
color:white;
text-decoration:none;
border-radius:50px;
font-size:20px;
}

.menu{
padding:60px 20px;
max-width:1200px;
margin:auto;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:40px;
color:#ff6600;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 10px 20px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card h3{
padding:15px;
text-align:center;
}

.price{
text-align:center;
color:#ff6600;
font-size:22px;
font-weight:bold;
padding-bottom:20px;
}

footer{
background:#222;
color:white;
padding:40px;
text-align:center;
line-height:2;
}
</style>

</head>

<body>

<header>

<div>

<h1>🍛 সুখাদ্য</h1>

<p>স্বাদে, গুণে ও যত্নে—প্রতিটি আয়োজনে সুখাদ্য</p>

<a class="btn" href="tel:01953775981">📞 অর্ডার করুন</a>

</div>

</header>

<section class="menu">

<h2 class="title">আমাদের জনপ্রিয় মেনু</h2>

<div class="grid">

<div class="card">
<img src="images/mishti-porota.jpg">
<h3>মিষ্টি পরোটা</h3>
<div class="price">৳৬০</div>
</div>

<div class="card">
<img src="images/porota.jpg">
<h3>পরোটা</h3>
<div class="price">৳২০</div>
</div>

<div class="card">
<img src="images/beef-tehari.jpg">
<h3>বিফ তেহারি</h3>
<div class="price">৳২৫০</div>
</div>

<div class="card">
<h3>মরগ পোলাও</h3>
<div class="price">৳১৭০</div>
</div>

</div>

</section>

<footer>

📞 01953-775981<br>

💳 bKash: 01611059190<br>

📧 araf4syl@gmail.com<br>

📘 Facebook: facebook.com/Sukhaddo4mb

</footer>

</body>
</html>
Sukhaddo/
│── index.html
│── menu.html
│── gallery.html
│── contact.html
│── order.html
│── style.css
│── script.js
│── images/
│── admin/
Sukhaddo/
│
├── index.html
├── menu.html
├── gallery.html
├── order.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   ├── logo.png
│   ├── hero.jpg
│   ├── morog-polao.jpg
│   ├── beef-tehari.jpg
│   ├── chicken-tehari.jpg
│   ├── ilish-polao.jpg
│   ├── chicken-khichuri.jpg
│   ├── sobji-khichuri.jpg
│   ├── porota.jpg
│   ├── mishti-porota.jpg
│   ├── alu-singara.jpg
│   └── chicken-singara.jpg
│
└── admin/
    └── dashboard.html
    <section class="hero">
  <div class="hero-content">
    <h1>🍛 সুখাদ্য</h1>
    <p>স্বাদে, গুণে ও যত্নে—প্রতিটি আয়োজনে সুখাদ্য</p>

    <a href="menu.html" class="btn">🍽️ মেনু দেখুন</a>
    <a href="order.html" class="btn btn2">📦 অর্ডার করুন</a>
  </div>
</section>
