
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

/* sembunyikan judul repo github */

h1:first-of-type{
display:none;
}

body{
font-family:'Poppins',sans-serif;
background:#F6F1E7;
color:#333;
}

/* container */

.container{
max-width:1100px;
margin:auto;
padding:0 20px;
}

/* HEADER */

header{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
padding:15px 0;
}

nav{
display:flex;
justify-content:center;
gap:25px;
}

nav a{
color:white;
text-decoration:none;
font-weight:500;
}

/* HERO */

.hero{
display:flex;
align-items:center;
justify-content:space-between;
gap:40px;
padding:70px 0;
background:linear-gradient(120deg,#F6F1E7,#EFE3FF);
position:relative;
overflow:hidden;
}

/* background logo */

.hero::before{
content:"";
position:absolute;
width:420px;
height:420px;
background:url("logo.png") no-repeat center;
background-size:contain;
opacity:0.05;
left:50%;
top:50%;
transform:translate(-50%,-50%);
}

/* TEXT */

.hero-text{
max-width:480px;
position:relative;
z-index:2;
}

.hero-text h1{
font-size:34px;
color:#5E2A84;
margin-bottom:15px;
}

.hero-text p{
font-size:17px;
margin-bottom:25px;
line-height:1.6;
}

/* BUTTON */

.btn{
background:#C9A25D;
color:white;
padding:12px 26px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block;
}

/* SOCIAL */

.social{
margin-top:20px;
display:flex;
gap:12px;
flex-wrap:wrap;
}

.social a{
text-decoration:none;
padding:10px 16px;
border-radius:25px;
font-size:14px;
color:white;
}

.ig{
background:#E1306C;
}

.wa{
background:#25D366;
}

/* IMAGE */

.hero-img img{
width:270px;
mix-blend-mode:multiply;
position:relative;
z-index:2;
}

/* SECTION */

.section{
padding:70px 0;
text-align:center;
}

.section h2{
font-size:28px;
color:#5E2A84;
margin-bottom:35px;
}

/* FEATURES */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
}

.feature{
background:white;
padding:22px;
border-radius:12px;
box-shadow:0 5px 18px rgba(0,0,0,0.08);
}

/* PRODUCTS */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:30px;
}

.product-card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 8px 22px rgba(0,0,0,0.08);
}

.product-img img{
width:170px;
mix-blend-mode:multiply;
}

.price{
font-size:20px;
font-weight:600;
margin:10px 0 18px;
}

/* TESTIMONI */

.testimonial{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08);
margin-top:15px;
}

/* CTA */

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:70px 20px;
text-align:center;
}

/* FOOTER */

footer{
background:#3E1A5C;
color:white;
padding:25px;
text-align:center;
}

/* WHATSAPP FLOAT */

.wa-float{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
width:55px;
height:55px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:26px;
color:white;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,0.25);
}

/* MOBILE */

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center;
padding:50px 0;
}

.hero-img img{
width:210px;
margin-top:25px;
}

.hero-text h1{
font-size:26px;
}

.hero-text p{
font-size:16px;
}

.social{
justify-content:center;
}

}

</style>

</head>

<body>

<header>

<nav>
<a href="#home">Home</a>
<a href="#manfaat">Manfaat</a>
<a href="#produk">Produk</a>
<a href="#testimoni">Testimoni</a>
<a href="#kontak">Kontak</a>
</nav>

</header>

<!-- HERO -->

<section class="hero">

<div class="container hero">

<div class="hero-text">

<h1>Telang Seger, Sereh & Jahe</h1>

<p>
Minuman herbal alami dengan perpaduan bunga telang, serai, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p>

<a class="btn" href="#produk">Pesan Sekarang</a>

<div class="social">

<a class="wa"
href="https://wa.me/6282182167104">
WhatsApp
</a>

<a class="ig"
href="https://instagram.com/telserahee_telang">
Instagram
</a>

</div>

</div>

<div class="hero-img">
<img src="produk.png">
</div>

</div>

</section>

<!-- MANFAAT -->

<section class="section container" id="manfaat">

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

<!-- PRODUK -->

<section class="section container" id="produk">

<h2>Produk Kami</h2>

<div class="products">

<div class="product-card">

<div class="product-img">
<img src="produk250.png">
</div>

<h3>Telserahe 250ml</h3>

<div class="price">Rp 6.000</div>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%0ASaya%20ingin%20memesan%20250ml.%0AJumlah%20:%20">
Pesan
</a>

</div>

<div class="product-card">

<div class="product-img">
<img src="produk500.png">
</div>

<h3>Telserahe 500ml</h3>

<div class="price">Rp 10.000</div>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%0ASaya%20ingin%20memesan%20500ml.%0AJumlah%20:%20">
Pesan
</a>

</div>

</div>

</section>

<!-- TESTIMONI -->

<section class="section container" id="testimoni">

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

<!-- CTA -->

<section class="cta">

<h2>Segarkan Harimu dengan Telserahe</h2>

<p>Minuman herbal alami yang sehat dan menyegarkan.</p>

<br>

<a class="btn"
href="https://wa.me/6282182167104">
Pesan Sekarang
</a>

</section>

<!-- KONTAK -->

<section class="section container" id="kontak">

<h2>Kontak Kami</h2>

<p>WhatsApp : 082182167104</p>
<p>Instagram : @telserahee_telang</p>
<p>Tiktok : @telserahe_telang</p>

</section>

<footer>

<p>© 2026 Telserahe - Telang Seger, Sereh & Jahe</p>

</footer>

<a href="https://wa.me/6282182167104" class="wa-float">💬</a>

</body>
