<!DOCTYPE html>
<html lang="id">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Telserahe | Telang Seger, Sereh & Jahe</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
box-sizing:border-box;
margin:0;
padding:0;
}

body{
font-family:'Poppins',sans-serif;
background:#F6F1E7;
color:#333;
}

header{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo img{
height:60px;
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500;
}

.hero{
min-height:80vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:60px 10%;
background:linear-gradient(120deg,#F6F1E7,#EFE3FF);
}

.hero-text{
max-width:500px;
}

.hero-text h1{
font-size:42px;
color:#5E2A84;
margin-bottom:20px;
}

.hero-text p{
font-size:18px;
margin-bottom:30px;
line-height:1.6;
}

.btn{
background:#C9A25D;
color:white;
padding:14px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block;
}

.hero-img img{
width:320px;
border-radius:20px;
box-shadow:0 10px 30px rgba(0,0,0,0.2);
}

.section{
padding:80px 10%;
text-align:center;
}

.section h2{
font-size:32px;
color:#5E2A84;
margin-bottom:40px;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:30px;
}

.feature{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08);
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:40px;
}

.product-card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.08);
transition:0.3s;
}

.product-card:hover{
transform:translateY(-8px);
}

.product-img{
height:200px;
background:linear-gradient(#7B3FB2,#C9A25D);
border-radius:15px;
margin-bottom:20px;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:22px;
font-weight:600;
}

.product-card h3{
color:#5E2A84;
margin-bottom:10px;
}

.price{
font-size:20px;
font-weight:600;
margin:10px 0 20px 0;
}

.testimonial{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
margin-top:20px;
}

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:80px 20px;
text-align:center;
}

.cta h2{
font-size:36px;
margin-bottom:20px;
}

footer{
background:#3E1A5C;
color:white;
padding:30px;
text-align:center;
}

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center;
}

.hero-img img{
margin-top:40px;
width:250px;
}

}

</style>
</head>

<body>

<header>

<div class="logo">
<img src="logo.png" alt="Logo Telserahe">
</div>

<nav>
<a href="#home">Home</a>
<a href="#manfaat">Manfaat</a>
<a href="#produk">Produk</a>
<a href="#testimoni">Testimoni</a>
<a href="#kontak">Kontak</a>
</nav>

</header>

<section class="hero" id="home">

<div class="hero-text">

<h1>Telang Seger, Sereh & Jahe</h1>

<p>
Minuman herbal alami dengan perpaduan bunga telang, sereh, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p>

<a class="btn" href="#produk">Pesan Sekarang</a>

</div>

<div class="hero-img">
<img src="banner.png" alt="Minuman Telserahe">
</div>

</section>

<section class="section" id="manfaat">

<h2>Manfaat Bahan Alami</h2>

<div class="features">

<div class="feature">
<h3>🌸 Bunga Telang</h3>
<p>Kaya antioksidan dan baik untuk kesehatan tubuh.</p>
</div>

<div class="feature">
<h3>🌿 Sereh</h3>
<p>Menyegarkan tubuh dan membantu detoks alami.</p>
</div>

<div class="feature">
<h3>🫚 Jahe</h3>
<p>Menghangatkan tubuh dan meningkatkan imun.</p>
</div>

<div class="feature">
<h3>🍯 Madu</h3>
<p>Pemanis alami yang sehat dan menambah energi.</p>
</div>

</div>

</section>

<section class="section" id="produk">

<h2>Produk Kami</h2>

<div class="products">

<div class="product-card">
<div class="product-img">250 ml</div>
<h3>Telserahe 250ml</h3>
<p>Ukuran praktis untuk aktivitas sehari-hari.</p>
<div class="price">Rp 6.000</div>
<a class="btn" href="https://wa.me/6281234567890">Pesan</a>
</div>

<div class="product-card">
<div class="product-img">500 ml</div>
<h3>Telserahe 500ml</h3>
<p>Ukuran lebih besar untuk dinikmati bersama.</p>
<div class="price">Rp 10.000</div>
<a class="btn" href="https://instagram.com/telserahee_telang">Pesan</a>
</div>

</div>

</section>

<section class="section" id="testimoni">

<h2>Testimoni Pelanggan</h2>

<div class="testimonial">
⭐️⭐️⭐️⭐️⭐️
<p>"Minumannya segar banget, rasa jahenya pas dan aromanya wangi!"</p>
</div>

<div class="testimonial">
⭐️⭐️⭐️⭐️⭐️
<p>"Unik! Warna telangnya cantik dan rasanya menyehatkan."</p>
</div>

</section>

<section class="cta">

<h2>Segarkan Harimu dengan Telserahe</h2>
<p>Minuman herbal alami yang sehat dan menyegarkan.</p>

<br>

<a class="btn" href="https://instagram.com/telserahee_telang">
Pesan Sekarang
</a>

</section>

<section class="section" id="kontak">

<h2>Kontak Kami</h2>
<p>Instagram : @telserahee_telang</p>

</section>

<footer>
<p>© 2025 Telserahe - Telang Seger, Sereh & Jahe</p>
</footer>

</body>
</html>
